##### How did you determine which rules should be placed in each new CSS file?

I followed SMACSS convention. For the Base Rules, I put code that defines the default styling. I did not put anything in the base that refered to class or ID. For the Layout Rules, I included the code that refers to the major components of the layout, focusing on the parts that refer to IDs and classes. For the Modules Rules, I included the code that refers to the minor components of the layout. I did not include anything that refers to IDs, instead only including classes and element selectors.

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I did not refactor the existing CSS.