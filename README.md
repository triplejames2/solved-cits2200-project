Download Link: https://assignmentchef.com/product/solved-cits2200-project
<br>
All questions work with a greyscale image specified as a 2D int array. The array is indexed first by row, then by column. Every row in the array will be the same length. Every element in the array will be non-negative and no greater than 255. A value of 0 represents a black pixel, and a value of 255 represents white, with shades of grey in between.

Time complexity specifications use R for number of rows, C for number of columns, and P = R*C for number of pixels.

<h2>public int floodFillCount(int[][] image, int row, int col)</h2>

Compute the number of pixels that change when performing a black flood-fill from the pixel at ( row , col ) in the given image. A flood-fill operation changes the selected pixel and all contiguous pixels of the same colour to the specified colour. A pixel is considered part of a contiguous region of the same colour if it is exactly one pixel up/down/left/right of another pixel in the region.

Marks (4 total):

Correctness: +2 marks

Complexity: (where Q is the number of queries)

O(PC + Q) : +1 mark

O(P log C + Q log C) : +1 mark

Faster is possible but will not receive additional marks Quality: +2 marks

<h1>Required Work</h1>

Your report must be provided as a PDF named report.pdf

Your report must for each problem:

Explain why your chosen algorithm will give the correct answer (that is, a logical argument for why it is correct)

Provide an analysis explaining the time complexity of your implementation (and memory complexity if relevant)

<h1>Testing</h1>

Your code must compile correctly when compiled with:

After compiling, you can test your code using the provided sample unit tests with:

<h1>Assessment</h1>

Each problem will be marked separately and the results combined for a total of 20 marks (mark distributions provided above). For each problem, you will receive marks based on:

Correctness

Compiles without error

Gives correct results

Complexity

Efficient code

Complexity targets are provided above

Quality

Convincing and well presented arguments in report

Code readable and easy to follow, including sufficient commenting

For all components, you will be assessed on how well the evidence demonstrates your understanding of the content.

Your submitted work will serve as evidence of understanding of the project content.

Any work that is not your own original work does not constitute evidence of understanding.

You are permitted to research prior work that others have done on these problems, but any work you reference must be cited in your report.

Your code must be wholly your own original work.