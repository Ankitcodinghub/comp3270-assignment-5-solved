# comp3270-assignment-5-solved
**TO GET THIS SOLUTION VISIT:** [COMP3270 Assignment 5 Solved](https://www.ankitcodinghub.com/product/comp3270-solved-5/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118145&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP3270 Assignment 5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
Objectives of this assignment:

• USE THIS FILE AS THE STARTING DOCUMENT YOU WILL TURN IN. DO NOT DELETE ANYTHING FROM THIS FILE: JUST INSERT YOUR ANSWERS.

• IF USING HAND WRITING (STRONGLY DISCOURAGED), USE THIS FILE BY CREATING SUFFICIENT SPACE AND WRITE IN YOUR ANSWERS.

• FAILING TO FOLLOW TURN IN DIRECTIONS /GUIDELINES WILL COST A 30% PENALTY.

What you need to do (Insert in this file your answers):

1. (20 points) Implement the NaïveSort and MergeSort algorithms to sort an array.

submit your source code in your preferred language (as long as it is supported on Tux machines).

Provide here the instructions to compile and execute your code

2. ( 5 points) Collect the execution time T(n) as a function of n for the two algorithms

No need to submit a table of the values you collect. Just state here if you collected data and submit a cvs file containing the values n, TNaive(n), and TMerge(n) where TNaive(n), and TMerge(n) are respectively the execution time of NaïveSort and MergeSort for an array of size n.

3. (20 points) Plot on the same graph the running time TNaive(n), and TMerge(n) of each algorithm. Insert here the plot…

4. (20 points) Using a pertinent graph/plot with your data (hint: look at previous programming assignments how we can determine the shape of T(n) and its asymptotic growth), show/illustrate what the time complexity of NaïveSort is.

Insert here the plot…

Discuss here the pertinent plot that determines the asymptotic growth of Naive Sort

5. (20 points) Using a pertinent graph/plot with your data (hint: look at previous programming assignments), show/illustrate what the time complexity of MergeSort is.

Insert here the plot…

Discuss here the plot plot that determines the asymptotic growth of MergeSort

6. (15 points) Discuss the results comparing the two algorithms. Discuss here the plot. Which algorithm is better?

Objective:

The objective of this programming assignment is to implement in Java the NaïveSort and MergeSort algorithms presented in the lectures to sort a list of numbers. We are interested in comparing the two algorithms. For this exploration, you will collect the execution time T(n) as a function of n and plot on the same graph the execution times T(n) of the two algorithms. Finally, discuss your results.

Program to implement

collectData()

Generate an array G of HUGE length L (as huge as your language allows) with random values capped at 0x7ffffffe.

for n = 4000 to L (with step 1,000)

for each algorithm NaïveSort and MergeSort do copy in Array A n first values from Array G

Start timing // We time the sorting of Array A of length n Sort A using one of the two algorithms.

Store the value n and the value T(n) in a file F where T(n) is the execution time

//Think here about value(s) to collect for the pertinent graph/plot for questions 4, 5, and 6

What should be L? L must be as large as possible such that 1) you collect enough data to produce meaningful plots, 2) it would not take too much time to collect data, and 3) your machine can handle.

Data Analysis

Use any plotting software (e.g., Excel) to plot the values T(n) in File F as a function of n. File F is the file produced by the program you implemented. Discuss your results based on the plots.

Report

• Your report is this file in which you inserted your answers

• Good writing is expected. • Recall that answers must be well written, documented, justified, and presented to get full credit.

What you need to turn in:

• Electronic copy of your source program (standalone) that collects data

• csv file containing n, TNaive(n), and TMerge(n)

• Electronic copy of the report (this file including your answers) (standalone). Submit the file as a Microsoft Word or PDF file.

Grading

1. (20 points) Implement the NaïveSort and MergeSort algorithms to sort an array A.

2. ( 5 points) Collect the execution time T(n) as a function of n for the two algorithms

3. (20 points) Plot on the same graph the running time of the two algorithms.

4. (20 points) Using a pertinent graph/plot with your data (hint: look at previous programming assignments), show/illustrate what the time complexity of NaïveSort is.

5. (20 points) Using a pertinent graph/plot with your data (hint: look at previous programming assignments), show/illustrate what the time complexity of MergeSort is.

6. (15 points) Discuss the results comparing the two algorithms.
