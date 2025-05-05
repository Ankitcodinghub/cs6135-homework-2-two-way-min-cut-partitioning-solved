# cs6135-homework-2-two-way-min-cut-partitioning-solved
**TO GET THIS SOLUTION VISIT:** [CS6135 Homework 2-Two-way Min-cut Partitioning Solved](https://www.ankitcodinghub.com/product/cs6135-homework-2-two-way-min-cut-partitioning-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94608&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6135 Homework 2-Two-way Min-cut Partitioning Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

Let 𝐶𝐶 be a set of cells and 𝑁𝑁 be a set of nets. Each net connects a subset of cells. The two-way min-cut partitioning problem is to partition the cell set into two groups 𝐴𝐴 and 𝐵𝐵. The cost of a two-way partitioning is measured by the cut size, which is the number of nets having cells in both groups. In this homework assignment, you are asked to implement FM ALGORITHM to solve the problem of two-way min- cut partitioning. Note that any form of plagiarism is strictly prohibited. If you have any problem, please contact TA.

2. ProblemDescription

The two-way min-cut partitioning problem is defined as follows:

<ol>
<li>(1) &nbsp;Input:
 A netlist for a circuit (.nets)

 The size of each cell (.cells)
</li>
<li>(2) &nbsp;Output:</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
1. Introduction and Goal

</div>
</div>
<div class="layoutArea">
<div class="column">
 The final cut size and a partition result (.out) (3) Objective:

</div>
</div>
<div class="layoutArea">
<div class="column">
Partition the circuit in two sub-circuits 𝐴𝐴 and 𝐵𝐵, such that the cut size is minimized under the constraint of |𝑎𝑎𝑎𝑎𝑎𝑎𝑎𝑎(𝐴𝐴) − 𝑎𝑎𝑎𝑎𝑎𝑎𝑎𝑎(𝐵𝐵)| &lt; 𝑛𝑛 , where

</div>
</div>
<div class="layoutArea">
<div class="column">
10 𝑎𝑎𝑎𝑎𝑎𝑎𝑎𝑎(𝐴𝐴) is the sum of all cell sizes in 𝐴𝐴, 𝑎𝑎𝑎𝑎𝑎𝑎𝑎𝑎(𝐵𝐵) is the sum of all cell

</div>
</div>
<div class="layoutArea">
<div class="column">
sizes in 𝐵𝐵, and 𝑛𝑛 is the sum of all cell sizes in the circuit.

</div>
</div>
<div class="layoutArea">
<div class="column">
3. Input File

<ol>
<li>(1) &nbsp;The .cells file:
This input file specifies a list of cells. Each cell statement starts with its cell

name (unordered) and size (a positive integer).
</li>
<li>(2) &nbsp;The .nets file:

This input file specifies a list of nets. Each net statement starts with the keyword “NET” and the name of the net. The cells that are connected by the net are listed between a pair of braces following the net name.

1
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Example:

.cells .nets

c21 NETn1{c2c3c4} c32 NETn2{c3c7}

c41 NETn3{c3c5c7} c72 NETn4{c1c3c5c7} c51 NETn5{c2c4c8} c11 NETn6{c4c6}

c82 NETn7{c2c6c8}

c6 2

P.S. We will give a testcase generator coded by ruby. It’s applicable to ruby v1.9.3 and beyond.

4. Output File The .out file:

Report the cells in each group and the cut size. Please strictly follow the output format or your result will be treated as illegal. You can run the “verifier” to check whether your result is legal or not.

Output Format:

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>cut_size #
A #cell_in_groupA
cell_ID
...
B #cell_in_groupB
cell_ID
...
</pre>
</div>
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Example:

cut_size 1 A4

c1

c3

c5 c7 B4 c2 c4 c6 c8

5. Language/Platform

<ol>
<li>(1) &nbsp;Language: C/C++</li>
<li>(2) &nbsp;Platform: Unix/Linux</li>
</ol>
6. Report

Your report should contain the following content, and you can add more as you wish. The more the better.

<ol>
<li>(1) &nbsp;Your name and student ID</li>
<li>(2) &nbsp;How to compile and execute your program, and give an execution example.
If you implement parallelization, please let me know how to execute it with

single thread.
</li>
<li>(3) &nbsp;The final cut size and the runtime of each testcase
P.S. You could use the command time to measure runtime. e.g., $ /usr/bin/time -p ./main

and find out how much time you spent on I/O and how much time you spent
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
$ echo “alias time ‘/usr/bin/time -p'” &gt;&gt; ~/.tcshrc

Re-log in then $ time ./main is equal to $ /usr/bin/time -p ./main

</div>
</div>
<div class="layoutArea">
<div class="column">
(4) Runtime = 𝑇𝑇 + 𝑇𝑇 . For each case, please analyze your runtime 𝐼𝐼𝐼𝐼 𝑐𝑐𝑐𝑐𝑐𝑐𝑐𝑐𝑐𝑐𝑐𝑐𝑐𝑐𝑐𝑐𝑐𝑐𝑐𝑐𝑛𝑛

</div>
</div>
<div class="layoutArea">
<div class="column">
on the computation (FM Algorithm).

(5) The details of your implementation containing explanations of the

following questions:

I. Where is the difference between your algorithm and FM Algorithm

described in class? Are they exactly the same?

3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
<ol start="2">
<li>Did you implement the bucket list data structure?

 If so, is it exactly the same as that described in the slide? How

many are they?

 If not, why? You had a better data structure? Or, is bucket list

useless?
</li>
<li>How did you find the maximum partial sum and restore the result?</li>
<li>Please compare your results with the top 5 students’ results from last
year and show your advantage either in runtime or in solution quality. Are your results better than them?

<ul>
<li> &nbsp;If so, please express your advantages to beat them.</li>
<li> &nbsp;If not, it’s fine. If your program is too slow, then what do you
reckon the bottleneck of your program is? If your solution quality is inferior, what do you think that you could do to improve the result in the future?
</li>
</ul>
</li>
<li>What else did you do to enhance your solution quality or to speed up your program?</li>
<li>What have you learned from this homework? What problem(s) have you encountered in this homework?</li>
<li>If you implement parallelization, please describe the implementation details and provide some experimental results</li>
</ol>
7. RequiredItems

Please compress HW2/ (using tar) into one with the name CS6135_HW2_{StudentID}.tar.gz before uploading it to iLMS.

(1) src/containsallyoursourcecode,yourMakefileandREADME.

 README must contain how to compile and execute your program. An

example of README is like the following figure:

4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
(2) output/containsallyouroutputsoftestcasesfortheTAtoverify. (3) bin/containsyourexecutablefile.

(4) CS6135_HW2_{STUDENT_ID}_report.pdfcontainsyourreport.

The file structure would be like the following figure:

You can use the following command to compress your directory on a workstation:

<pre>    $ tar -zcvf CS6135_HW2_{StudentID}.tar.gz &lt;directory&gt;
</pre>
For example:

<pre>    $ tar -zcvf CS6135_HW2_109062501.tar.gz HW2/
</pre>
8. Grading

<ul>
<li> &nbsp;80%: The solution quality (final cut size) and the runtime of each testcase, hidden testcases included. Note that this part will be executed with single thread version.</li>
<li> &nbsp;20%: The completeness of your report</li>
<li> &nbsp;5% (bonus): Parallelization.
5
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
P.S. Using C++11

The C++11 standard is implemented in GCC 4.8.1 and beyond, yet the default version of gcc in our CAD servers (ic21~ic29) is 4.1.2.

You need to source /tools/linux/gnu/setup_toolkit.csh to link gcc to gcc 4.8.5.

However, it’s too much work and too forgettable that you need to source it every time when you log in on a server.

Instead, you can create a shell resource file called .tcshrc in the root folder and put the source command in it. Just enter the following command once, re-log in, and then it won’t never bother you anymore.

$ echo “source /tools/linux/gnu/setup_toolkit.csh” &gt;&gt; ~/.tcshrc

P.S. hMETIS

If you have time, you can learn how to run hMETIS and compare your results with those generated by hMETIS. (http://glaros.dtc.umn.edu/gkhome/metis/hmetis/overview)

Notes:

 The executable file name must be named as hw2.

 Please use the following command format to run your program.

<pre>    $ hw2 *.nets *.cells *.out
</pre>
E.g.: $ hw2 p2-1.nets p2-1.cells p2-1.out

 Program must be terminated within 10 minutes for each testcase.

 Grading is based on final cut size (primary) and runtime (secondary).

6

</div>
</div>
</div>
