# Responsive Web Design(RWD):

Dynamically adapts to different browser and device viewports, changing layout and content along the way

**Responsive vs. Adaptive vs. Mobile**

- Responsive means to react quickly and positively to any change
- adaptive means to be easily modified for a new purpose or situation or change
- Mobile means to build a separate website commonly on a new domain solely for mobile users

**Responsive Web Design components:**

- **flexible layouts:**

building the layout of a website with a flexible grid, capable of dynamically resizing to any width using relative length units, most commonly percentages or em units for  width, margin, or padding

*for css3:  vw, vh, vmin, and vmax units.*

*Target/parent width= result*

- **media queries**

provide the ability to specify different styles for individual browser and device circumstances, the width of the viewport or device orientation

*ways to use media queries:*

 - @media rule
 - @import rule
 - linking to a separate style sheet from within the HTML

*media types*

- all
- screen
- print
- tv
- braille

*Logical Operators in Media Queries*
- and, 
- not, 
- only.

*Media Features:*

- Height & Width
- Orientation
- Aspect Ratio
- Pixel Ratio 
- Resolution

 
- **flexible media**

- max-width = 100%

*Embedded media:*

- The parent element needs to have a width of 100% ,height of 0.
- Padding is then given to the bottom of the parent element, the value of which is set in the same aspect ratio of the video.
 


# All About Floats

- Float is a CSS positioning property. To understand its purpose and origin, we can look to print design
- Floats can be used to create entire web layouts.

**Clearing the Float**

An element that has the clear property set on it will not move up adjacent to the float like the float desires, but will move itself down past the float. 

**Techniques for Clearing Floats**

- The Empty Div Method
- The Overflow Method
- The Easy Clearing Method 

