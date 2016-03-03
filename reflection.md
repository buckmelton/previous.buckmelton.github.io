# Reflection: Challenge 3.5 - Your Website, part 3

### Link to my live site:

http://buckmelton.github.io

### Questions:

* **What did you learn about CSS padding, borders, and margin by doing this challenge?**

	I learned about the CSS Box Model.  In the CSS Box Model, the Content is at the center of the box.  The Content is surrounded by the Padding, which is always transparent.  The Padding is surrounded by the Border, which can be given a color and a style.  The Border is surrounded in turn by the Margin, which is also always transparent.  The Padding, Border, and Margin can all be given widths, and their top, right, bottom, and left sides can all be given independent widths.

	If you assign a width or height to an element, it only sets the width and height of the Content.  To figure out how much space the element will take up, you must add the Padding, Border, and Margin to the width and height you've specified.

	I also learned about 'margin collapse'.  There are two main situations where margin collapse occurs.  First, if one element is on top of another, the margin between them isn't the sum of their margins.  Rather, the margin between them is taken to be the larger of the two margins.  Second, if an element is a child of another element, again the larger of the two margins is taken to be the margin of the parent element.  So if the parent has a top margin of 0px, and the child has a top margin of 20px, the parent will be given a top margin of 20px.

* **What did you learn about CSS positioning?**

	It's very difficult and not at all intuitive for a beginner, or even intermediate, web page designer.  When using float and inline, elements can appear in unexpected places.  For example, if all elements of a parent container are float, some browsers consider the parent to have a height of 0px, meaning the next element below the parent element can jump up to appear above the floated child elements.

	I need to do a lot more studying to get a better feel for positioning.

* **What aspects of your design did you find easiest to implement? What was most difficult?**

	The easiest aspects were the font, color, and image choices.  The most difficult was the positioning and correct padding and margins for the various sections.

* **What did you learn about adding and formatting elements with CSS in this challenge?**

	I learned that it's very convenient to have the styling isolated to the CSS file, and also that it's very convenient to be able to experiment with different styles in the Inspector.  I also started to get a feel for how and when to use tags versus classes versus ids for styling.