**LOCAL STORAGE FOR WEB APPLICATIONS**

- Persistent local storage is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state.

**COOKIES**

local storage of small amounts of data. But they have three potentially dealbreaking downsides:

- Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
- Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
- Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful

**HTML5 STORAGE**

*“Local Storage” or “DOM Storage.”*

- it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually)

**check for HTML5 Storage**

`if (Modernizr.localstorage) {`
 ` // window.localStorage is available!`
`} else {`
 ` // no native support for HTML5 storage :(`
 ` // maybe try dojox.storage or a third-party solution`
`}`

**USING HTML5 STORAGE**

- HTML5 Storage is based on named key/value pairs.
- You store data based on a named key, then you can retrieve that data with the same key. 
- The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. 
- If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.