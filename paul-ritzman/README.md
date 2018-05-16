##### How did you determine which rules should be placed in each new CSS file?

I reasoned about which rules effected the layout of the HTML or which had an effect on how other elements around that one were displayed, versus styling a specific element (or multiple similar elements) without necessarily impacting the layouts of other element around it. - An example of what I mean is with the .l-recipe class: I put this in layout.css since this has an impact on how multiple other elements (ul vs li) are represented, as well as elements around it (paragraphs before, and footer after).

I was debating whether or not to put the logo ID in the layout.css file as well, since it impacted multiple other elements, but opted to leave it in modules.css, since it was more contained than the .l-recipe class in the overall impact on general DOM layout it had.

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I did not. I was considering moving "float: left" and "float: right" into their own classes, but decided not to since this could get overwhelming if one were to do this for other, similar rules. There could be a point where one could have separate classes for every rule used more than once, versus a set of rules that can be applied to multiple elements.
