# EJS Partials

- Mainly to reuse the same HTML across multiple views.

- It makes large websites easier to maintain as you don’t have to go and change a piece of text in every page it appears in. Instead, you define that reusable bundle of code in a file andinclude it wherever you need it.

**How to create those partials**

- *Example*

- For same navigation bar and footer appear in both the home and post view. This makes them perfect candidates for partials!

- Under the views/partials/ directory create a file callednavbar.ejs which will contain only the HTML for the navigation bar at the top of the home and post pages

- footer.ejs in that same directory

- Now that we have our partials defined, we can use them in our home.ejs and post.ejs templates!

**Notes**

- *In EJS, any JavaScript or non-HTML syntax you include in your templates is always surrounded by <% %> delimiters*


- *The <%- %> tags allow us to output the unescaped content onto the page (notice the -). This is important when using the include() statement since you don’t want EJS to escape your HTML characters like ‘<’, ‘>’*
