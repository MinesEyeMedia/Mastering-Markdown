# GitHub Specific Tricks & Tips

## Creating Checkboxes
One thing we may wish to do in a markdown document is to create a checkable checkbox. This isn't available in all renderers but Github specifically, and a few other sites and apps ('Bear' included) support them.

Let's imagine we have a list, and we want that list to be able to be checked off. We can make our list in the standard way by putting an asterisk before the list item, then we put a set of **square brackets WITH A SPACE BETWEEN THEM** ```[ ]``` before the list item. We also need to make sure there is a space **BETWEEN** the closing bracket and actual list item for it to parse out the correct markup.

* [ ] Get Milk
* [ ] Crack Eggs
* [x] Cook Bacon
* [ ] Toast Bread

*_If we place an 'X' inside of one of the brackets it will default that box as checked, as seen above. (The 'x' inside the bracket is **NOT** case-sensitive.)_