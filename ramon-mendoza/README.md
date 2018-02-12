##### How did you determine which rules should be placed in each new CSS file?

Well as the documentation said I put font changes and colors and such in the base css. Then in layouts I put the css that modifies things such as borders, margins and padding. And finally in the modules css I put in modifications to the images and lis.

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I split some of the css code across all of the css files.  For example on the h2 element, I have the font changes in the base.css and the margin changes in the layout css. I'm not sure if it's the best way to implement the SMACSS documentation but I thought I would try it out and see if it worked and it the page looks the same.
