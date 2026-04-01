# Case Study: Applying Linear Regression to Chess

### From House Prices to Piece Values
In the Andrew Ng course, we used Linear Regression to predict house prices based on size. In my chess project, I repurposed this:
* **Features ($x$):** The number of pieces (Pawns, Knights, Bishops, etc.) on the board.
* **Target ($y$):** The "evaluation" or win-probability of the position.

### The Optimization Challenge
I used the **Gradient Descent** algorithm I documented in my notes to find the "optimal weights" for each piece. 
* **Learning Rate ($\alpha$):** I had to tune this carefully to ensure the model converged on thousands of games pulled from the Chess.com API .



### Why No Libraries?
By implementing the cost function and update rules manually, I gained a deeper understanding of how the model "punishes" incorrect piece valuations during training.
