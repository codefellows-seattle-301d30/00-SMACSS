##### How did you determine which rules should be placed in each new CSS file?

I thought about the structure of the DOM and what parts I'd be likely to change over time and under what circumstances. For example if the company rebranded (new styling with new logo, etc.), it would be easier to modify the nav and footer in the base (a style available across all pages). Where as there were some unique challenges for the recipe card which was a special layout item (it also didn't work when in modules because of the li CSS in layout). The aside, however seems to be module that might be on mahy pages on a site, but not all and seemed to belong in that file as a result. 

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

Honestly, I didn't think to do this because everything was working and I didn't want to break it.

But prompted by the question, I've gone through and I still didn't see much to refactor. I did refactor the aside, but that's it. It may be that I don't yet totally understand refactoring. (I get the benefits conceptually when creating new code, but I don't get doing it to existing code fully, yet.)
