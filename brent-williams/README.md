##### How did you determine which rules should be placed in each new CSS file?
Broad styles for an individual element type (input, nav, etc) went into base. Things that position larger elements go into layout (nav positioning, for example). Anything with nested selectors goes into modules, because the things being handled are far too specific for base and don't deal with the overarching layout of the page.

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I did split some css rules that had been grouped together into two so that the layout/base info goes there and the module info stays in the module.
