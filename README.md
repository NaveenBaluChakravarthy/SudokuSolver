# SudokuSolver
Solve sudoku 9x9 using a strategic algorithm rather than backtracking


### Data Preparation Approach
<ol>
<li>Get the images of The Hindu Sudoku Puzzles.
<li>Perform thresholding, perspective cropping and extract the individual boxes.
<li>Convert the boxes into 28 x 28 image and label the digits.
<li>Write the data to a csv file.
<ol>

### Model Training Approach
<ol>
<li>Train the neural network on the data thus prepared.
<li>Idea: Very similar to MNIST.
<ol>

### Implementation Approach
<ol>
<li>Get the image of the puzzle to be solved.
<li>Perform the same preprocessing steps as in the preparation phase. 
<li>Use the model to recognize the digits from the puzzle.
<li>Feed the recognized digits to the algorithm that solves the puzzle.
<li>Display the solved puzzle as grid / use an empty board to construct the solved puzzle.
</ol>


