# csc230-exercise-07-solved
**TO GET THIS SOLUTION VISIT:** [CSC230 Exercise 07 Solved](https://www.ankitcodinghub.com/product/csc230-exercise-07-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;62759&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC230 Exercise 07 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
For this exercise, you get to fill in a missing parts in a program that works with a grid of small integers, stored in a variable-sized array.&nbsp; The program is called hilltop.c.&nbsp; Its job is to find local maxima in the grid, values that are larger than any of their neighboring values.&nbsp; You can download the exercise files from the course webpage, or using the following curl commands:

curl -O https://www.csc2.ncsu.edu/courses/csc230/exercise/exercise07/hilltop.c curl -O https://www.csc2.ncsu.edu/courses/csc230/exercise/exercise07/input-1.txt curl -O https://www.csc2.ncsu.edu/courses/csc230/exercise/exercise07/expected-1.txt curl -O https://www.csc2.ncsu.edu/courses/csc230/exercise/exercise07/input-2.txt curl -O https://www.csc2.ncsu.edu/courses/csc230/exercise/exercise07/expected-2.txt

&nbsp;

The following shows what’s in the first sample input file, input-1.txt.&nbsp; The first two values give the size of the grid of numbers (rows then columns).&nbsp; The remaining lines give the contents of the grid, with a row on each input line.

4 5

7 49 73 58 30

72 44 78 23&nbsp; 9

40 65 92 42 87

3 27 29 40 12

&nbsp;

We’ll say a local maximum is a value that’s greater than the value in any of its (up to) eight neighboring elements in the grid.&nbsp; So, for example, the 72 at the start of row 1 is a local maximum.&nbsp; It has five neighbors (7, 49, 44, 65 and 40), and its value is greater than any of them.&nbsp; The 92 in row 2 and the 87 in row 2 are also local maxima.

&nbsp;

When you run your program it should read the grid description from standard input.&nbsp; Like in the example above, this will give with the grid size, then all the values in the grid.&nbsp; You can assume the input is valid; you don’t need to detect invalid or missing values (but, you can if you want to).

&nbsp;

For output, your program should report the row and column locations of all the local maxima in the grid.&nbsp; Report them in row-major order, from the top row of the grid to the bottom and from left to right within each row.&nbsp; Rows and columns are numbered starting from zero.&nbsp; So, for example, if you run your program on the example above, it should produce the following output.

&nbsp;

$ ./hilltop &lt; input-1.txt

<ul>
<li>0</li>
<li>2</li>
</ul>
2 4

<h1>Completing the Implementation</h1>
On the course homepage and in the following AFS directory, you’ll find a partial implementation for this program, along with a couple of sample inputs and expected output files.

&nbsp;

/afs/eos.ncsu.edu/courses/csc/csc230/common/www/sturgill/exercise07

&nbsp;

To complete the program, you’ll need to do the following.

&nbsp;

<ul>
<li>In main, add code to read the number of rows and columns of the grid from standard input and create a variable-sized, two-dimensional array to store the grid of values. Make your array exactly the right size to hold the values you’re about to read.</li>
</ul>
&nbsp;

<ul>
<li>Fill in the readGrid() function with code to read input values into your array. Since arrays are automatically passed by reference, this function can change the contents of your array, even though</li>
</ul>
you created that array in main.&nbsp; (when you’re reading an int value with scanf(), don’t forget to put the &amp; in front of the parameter, even if that parameter is an array element.)

&nbsp;

<ul>
<li>Add a function call in main() to call your readGrid() function, right after you’ve created your array.</li>
</ul>
&nbsp;

<ul>
<li>Fill in the parameters and the body of the reportMaxima() function so it goes through all the elements of the array and reports the row and column location of any local maxima. In my solution, I when through all the elements of the array, and, for each one, I compared its value with all its neighbors.&nbsp; This took a quadruply-nested loop the way I did it, but you can solve the problem other ways if you want to.</li>
</ul>
&nbsp;

Remember, C doesn’t do bounds checking on arrays, so, when you’re looking at the neighbors of an element, you’re probably going to need some code to make sure you don’t accidentally check locations that are off the edge of the grid.

&nbsp;

<ul>
<li>Add a function call in main() to call your reportMaxima() function.</li>
</ul>
<h1>Optional (extra credit)</h1>
After reading the size of the array, all values should be initialized (using loops) to zeros.

The input after the array size can consist of <em>0 or more</em> rows, up to but not exceeding the number of rows expected.&nbsp; Each row can consist of <em>0 or more elements (or columns),</em> up to but not exceeding the number of columns expected.&nbsp; Values not provided in the input should remain initialized to 0.&nbsp; So, for instance, the following would be possible:

<strong>4 5 </strong>

<strong>7 49 73 58 30 </strong>

<strong>72 44 78 23 9 </strong>

<strong>40 65 92 42 87 </strong>

<ul>
<li><strong>27 29 40 12 </strong></li>
</ul>
i.e. all element values provided, all initialization values overwritten

&nbsp;

<ul>
<li><strong>5 </strong></li>
</ul>
<strong>7 49 73 </strong>

<strong>72 44 78 23&nbsp; </strong>

<strong>40 65 92 42 87 </strong>

i.e. last 2 elements of the first row have values of 0, the last 1 element of the second row has value 0, and the last row of the array is entirely 0

&nbsp;

<strong>4 5 </strong>

i.e. no values provided for any array elements, so all 0!

&nbsp;

An optional input, <strong>optional-input-3.txt</strong>, will be provided, as well as the expected output, <strong>optional-output-3.txt</strong>.

&nbsp;

If you elect to do this optional part, do not break your non-optional part!

&nbsp;
