# comp90086-assignment-3-fundamental-matrix-calculation-solved
**TO GET THIS SOLUTION VISIT:** [COMP90086 Assignment 3-Fundamental Matrix Calculation Solved](https://www.ankitcodinghub.com/product/comp90086-assignment-3-fundamental-matrix-calculation-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101707&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP90086 Assignment 3-Fundamental Matrix Calculation Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Assignment 3: Fundamental Matrix Calculation

Introduction

In this project you will implement the calculation of a Fundamental matrix using your own algorithms. You can use the keypoint detection and matching approach used in the week 8 Workshop, as well as code for drawing lines on images, but the implementation of the Fundamental Matrix calculation must be your own work.

Coding tasks

Your tasks are:

1. Find keypoints and correspondences between two images 2. To implement the 8 point algorithm you will need to:

</div>
</div>
<div class="layoutArea">
<div class="column">
a. b. c.

d. e.

f.

g.

h. i.

</div>
<div class="column">
Shift and scale the pixel coordinates

Compute the design matrix from sets of (at least) 8 points

Perform an SVD of the design matrix to find its null space (you can use a library function for the SVD)

Compose the draft fundamental matrix F

Perform an SVD of the draft fundamental matrix, set the smallest singular value to zero and reassemble so that F now has determinant = 0

Calculate which correspondences are inliers and which are outliers using this F. You will need to allow for some error because the keypoint coordinates won’t lie exactly on the epipolar line so you will need to allow for 1-2 pixels error for a correct correspondence. Also remember to take into account any scaling you applied at step a.

Wrap steps b-f in a RANSAC loop that runs enough times that you have a probability &gt; 99% of finding 8 inliers and computing a good quality F. Re-estimate F using all the inliers.

Compute F in terms of the original pixel coordinates (ie undo the effects of step a).

</div>
</div>
<div class="layoutArea">
<div class="column">
3. Randomly

to your best F estimate and display these on the images, together with their epipolar lines.

</div>
</div>
<div class="layoutArea">
<div class="column">
sample ten keypoint pairs from correspondences you have detected as inliers

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
If you make this a separate cell in your jupyter notebook, you can run the cell more than once to see different random samplings.

Report

Your report should describe why you need each of these steps and any design choices you have made along with numerical quantities, e.g. choice of error tolerance at step f, or the calculation needed to determine the number of RANSAC iterations at step g.

You should also discuss whether there are images that work better than others in the dataset and why.

Dataset

The dataset is the kusvod2 dataset. Image files are of the form &lt;something&gt;A.png and &lt;something&gt;B.png for each image pair.

Using Library Code

You may use library code for everything except the implementation of the 8 point algorithm which you must implement yourself. This means that you can use library implementations of keypoint detection and correspondence (e.g. SIFT or FAST and BRIEF) as well as implementations of SVD or other linear algebra operations.

Submission

You should make two submissions on the LMS: your code and a short written report explaining your method and results. Your report should be no more than 1500. Submission will be made via the Canvas LMS. Please submit your code and written report separately under the Assignment 3: Code and the Assignment 3: Report links on Canvas.

<ul>
<li>● &nbsp;Your code submission should include the Jupyter Notebook (please use the provided template) with your code and any additional files we will need to run your code. You do not need to include the provided images in your submission.</li>
<li>● &nbsp;Your written report should be a .pdf with your answers to each of the questions. The report should address the questions posed in this assignment and include any images, diagrams, or tables required by the question.
Evaluation

Your submission will be marked on the correctness of your code/method, including the quality and efficiency of your code. You should use built-in Python functions where appropriate and use descriptive variable names. Your written report should clearly explain your approach and any experimentation used to produce your results, and include all of the specific outputs required by the question (e.g., images, diagrams, tables, or responses to sub-questions).
</li>
</ul>
</div>
</div>
</div>
</div>
