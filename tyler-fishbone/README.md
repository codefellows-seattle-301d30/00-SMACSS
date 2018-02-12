##### How did you determine which rules should be placed in each new CSS file?

**Base:** general font family and body background color in here.

**Layout:** here I put everything that seems to solely have things to do with positioning on the screen.

**Modules:** in this section I put everything that had specifics of a single element. turned out to be the majority of the css code. 


---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I didn't really do much refactoring, just took out some small things that ended up being redundant.

The thing I shied away from was breaking up selectors. Take the aside button{} selector. It has float: left; along with other decorative styling. I'm working if in SMACSS you're supposed to break up the selector and put the float right in layout and have a separate selector in modlues that contains the non layout styling information...