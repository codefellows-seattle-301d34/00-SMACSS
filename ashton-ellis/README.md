##### How did you determine which rules should be placed in each new CSS file?
Code that belonged in base was fairly straightforward. The two rules that applied to the entire page went there.

All of the CSS rules related to layout went in the layout.css file, as obvious as that sounds. Most of the rules that include floats and margins went there.

The remaining of the reles live in module.css. At first i was feeling like module was too long, but i remembered that the SMACCS article said that module does end up containing most of your rules.

The heuristic that i used was: 'if i comment out the link to the modules.css file, everything on the page should stay where it is, more or less, even if it looks wildly different'.

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I chose not to refactor very much, since the code is working nicely as is, and i don't think that we'll be interacting with chocolate pizza any more (at least i hope so). If i were to refactor, i think i would change the id selectors in module.css to class selectors and child selectors, so that those modules could be applied to other elements on the page that have similar characteristics.
