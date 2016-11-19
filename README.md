# sudoku
solution to solve sudoku programmatically

Nov 17 night, I was on my flight back to Denver from Boston
I was tired and try to solve the sudoku on the magazine 

It took me 12 minutes to completely solve the easy one, then I got stuck with the second one, the medium, then I started asking this question, "do you necessarily have to guess at certain stage". 

In another way, after you fill in as many cells as you can, that will leave certain cells easily than the others to guess, say I was constantly murmuring to myself things like 
- "the number 1 must exist in either this cell or that"
- "the cell could either be 1 or 2"

In this scenario, do you have to guess? in a sense, that if you guess one value, that might add more constraints to other cells and solve the question completely, or it might add more constraints to a level it leads to a conflict. 

This small ipython notebook that I wrote kind of proves that I was right. 
After a few rounds of checking, it turned out that I might have to guess.
