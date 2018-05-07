##### How did you determine which rules should be placed in each new CSS file?

I'll try and break this up by each .css file.
This is just by my interpretation but in the SMACSS directions base.css file should have most of the generic stuff from reset.css. 
Just like what SMACSS said layout.css should have "In SMACSS, layout Rules refer to the composition of common primary modules that typically appear on every page in your site or app. FOr example, the header, footer, primary nav, and aside to name a few." So from my guess just like what was stated above, I only placed header, footer, nav and aside...
The modules.css file might be kind of straight forward. I haven't confirmed my logic with anyone else but my guess is that anything you want to modify specifically should be placed in this file. Hence all the . and # for classes and IDs

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

No... I mean I didn't really see a point. The page worked perfectly fine. I'm not even sure if I needed to do any refactoring. 
