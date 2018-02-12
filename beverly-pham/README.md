##### How did you determine which rules should be placed in each new CSS file?

I determined where to place each rule based on whether it was for: the general styling of the entire page, if it was a general positioning rule, or if it was a smaller component of the page.

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I refactored to combine a few selectors that all had `float: left` and there were a couple that had `float:right` so I refactored those together.