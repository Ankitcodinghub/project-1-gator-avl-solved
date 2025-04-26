# project-1-gator-avl-solved
**TO GET THIS SOLUTION VISIT:** [Project 1 Gator Avl Solved](https://www.ankitcodinghub.com/product/project-1-gator-avl-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101860&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Project 1 Gator Avl Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (5 votes)    </div>
    </div>
<h1>Problem Statement</h1>
Binary Search Trees (BST) can often be an efficient and useful way to store and retrieve sorted data. However, the efficiency of these data trees relies heavily on how balanced a BST is. For example, searching through the BST on the left is much more efficient than searching through the BST on the right, despite both figures showing valid BST with the exact same elements.

To avoid inefficient binary search trees, we use balanced Binary Search Trees.&nbsp; A balanced BST has a balance factor of less than ±<em>threshold</em>, where the balance factor is the difference in heights of the left and right subtrees at any given tree node. One such balanced tree is an AVL tree that maintains a <em>threshold </em>of <strong>1</strong>. As soon as a node in an AVL tree has a balance factor of +2/-2, “tree rotations” are performed to maintain balance in the tree.

In this project, you will be designing a custom AVL tree to organize UF student accounts based on GatorIDs. You will build methods for insertion, deletion, search, and traversals for an AVL tree data structure. These methods would be called based on certain commands that are invoked in the main method. You are responsible for

<ul>
<li>Designing the interface/modules/functions of the standard AVL Tree and the operations required to execute the respective commands.</li>
<li>Parsing the input and ensuring data and command validation,</li>
<li>Building the main function to parse the inputs and calling the respective functions to match the output.</li>
<li>Testing your code within the constraints.</li>
</ul>
<h1>Functionality</h1>
Your program must support the following commands:

<table width="616">
<tbody>
<tr>
<td width="148"><strong>Command</strong></td>
<td width="93"></td>
<td width="375"><strong>Function</strong></td>
</tr>
<tr>
<td width="148">insert <em>NAME ID</em></td>
<td width="93">●</td>
<td width="375">Add a Student object into the tree with the specified name, <em>NAME </em>and GatorID number, <em>ID</em>.</td>
</tr>
<tr>
<td width="148"></td>
<td width="93">●</td>
<td width="375">Balance the tree automatically if necessary.</td>
</tr>
<tr>
<td width="148"></td>
<td width="93">●</td>
<td width="375">The <em>ID </em>must be unique.</td>
</tr>
<tr>
<td width="148"></td>
<td width="93">●</td>
<td width="375">The <em>ID </em>and <em>NAME </em>must satisfy the constraints stated below.</td>
</tr>
<tr>
<td width="148"></td>
<td width="93">●</td>
<td width="375">Also, prints “successful” if insertion is successful and prints “unsuccessful” otherwise.</td>
</tr>
<tr>
<td width="148"></td>
<td width="93">●</td>
<td width="375"><em>NAME </em>identifier will be separated by double inverted commas for parsing, e.g. “Josh Smith”.</td>
</tr>
<tr>
<td width="148">remove <em>ID</em></td>
<td width="93">●</td>
<td width="375">Find and remove the account with the specified <em>ID </em>from the tree.</td>
</tr>
<tr>
<td width="148"></td>
<td width="93">●</td>
<td width="375">[<strong>Optional</strong>: Balance the tree automatically if necessary. We will test your code only on cases where the tree will be balanced before and after the deletion. So you can implement a BST deletion and still get full credit]</td>
</tr>
<tr>
<td width="148"></td>
<td width="93">●</td>
<td width="375">If deletion is successful, print “successful”.</td>
</tr>
<tr>
<td width="148"></td>
<td width="93">●</td>
<td width="375">If the <em>ID </em>does not exist within the tree, print “unsuccessful”.</td>
</tr>
<tr>
<td width="148"></td>
<td width="93">●</td>
<td width="375"><strong>You must prioritize replacing a removed node with its inorder <em>successor </em>for the case where the deleted node has two children.</strong></td>
</tr>
<tr>
<td width="148">search <em>ID</em></td>
<td width="93">●</td>
<td width="375">Search for the student with the specified <em>ID </em>from the tree.</td>
</tr>
<tr>
<td width="148"></td>
<td width="93">●</td>
<td width="375">If the <em>ID </em>was found, print out their <em>NAME</em>.</td>
</tr>
<tr>
<td width="148"></td>
<td width="93">●</td>
<td width="375">If the <em>ID </em>does not exist within the tree, print “unsuccessful”.</td>
</tr>
<tr>
<td width="148">search <em>NAME</em></td>
<td width="93">●</td>
<td width="375">Search for the student with the specified name, <em>NAME </em>in the tree.</td>
</tr>
<tr>
<td width="148"></td>
<td width="93">●</td>
<td width="375">If the student name was found, print the associated <em>ID</em>.</td>
</tr>
<tr>
<td width="148"></td>
<td width="93">●</td>
<td width="375">If the tree has more than one object with the same <em>NAME</em>, print each <em>ID </em>on a new line with no other spaces and in the same relative order as a pre-order traversal.</td>
</tr>
<tr>
<td width="148"></td>
<td width="93">●</td>
<td width="375">If the name does not exist within the tree, print “unsuccessful”.</td>
</tr>
<tr>
<td width="148"></td>
<td width="93">●</td>
<td width="375"><em>NAME </em>identifier will be surrounded by double quotes for parsing, e.g. “Josh Smith”.</td>
</tr>
<tr>
<td width="148">printInorder</td>
<td width="93">●</td>
<td width="375">Print out a comma separated inorder traversal of the names in the tree.</td>
</tr>
<tr>
<td width="148">printPreorder</td>
<td width="93">●</td>
<td width="375">Print out a comma separated preorder traversal of the names in the tree.</td>
</tr>
<tr>
<td width="148">printPostorder</td>
<td width="93">●</td>
<td width="375">Print out a comma separated postorder traversal of the names in the tree.</td>
</tr>
<tr>
<td width="148">printLevelCount</td>
<td width="93">●</td>
<td width="375">Prints the number of levels that exist in the tree.</td>
</tr>
<tr>
<td width="148"></td>
<td width="93">●</td>
<td width="375">Prints 0 if the head of the tree is null. For example, the tree in <strong><em>Fig. 1 </em></strong>has 4 levels.</td>
</tr>
<tr>
<td width="148">removeInorder <em>N</em></td>
<td width="93">●</td>
<td width="375">Remove the <em>N</em>th GatorID from the inorder traversal of the tree (<em>N </em>= 0 for the first item, etc).</td>
</tr>
<tr>
<td width="148"></td>
<td width="93">●</td>
<td width="375">If removal is successful, print “successful”.</td>
</tr>
<tr>
<td width="148"></td>
<td width="93">●</td>
<td width="375">[<strong>Optional</strong>: Balance the tree automatically if necessary. We will test your code only on cases where the tree will be balanced before and after the deletion. So you can implement a BST deletion and still get full credit]</td>
</tr>
<tr>
<td width="148"></td>
<td width="93">●</td>
<td width="375">If the <em>N</em>th GatorID does not exist within the tree, print “unsuccessful”.</td>
</tr>
</tbody>
</table>
<h1>AVL Tree Data Structure</h1>
In order to receive full credit for this project, you must attempt to create an AVL Tree data structure/object class that is used in your main program. Additionally, this AVL tree should:

<ul>
<li>Also meet the requirements for a Binary Search Tree (BST)</li>
<li>Be sorted by numerical GatorID, not lexical Name</li>
<li>Be sorted from least to greatest (nodes of lesser value are in the left subtree, nodes of greater value are in the right subtree)</li>
<li>Make appropriate use of public and private methods</li>
</ul>
<h1>Testing Constraints</h1>
<ul>
<li>1 &lt;= <em> of Commands </em>&lt;= <em>1000</em></li>
<li>1 &lt;= <em>Unique UFIDs &lt;= 100,000</em></li>
<li>1 &lt;= <em>Length of a command &lt;= 1000</em></li>
<li>A command will always run for a single line and will never contain new line characters (‘\n’), except at the end.</li>
</ul>
<h1>Data Validation and Design Requirements</h1>
<ul>
<li>Data (You need to validate the following and print “unsuccessful” if data or commands are invalid and move to the next command) ○ UFIDs are strictly 8 digits long.
<ul>
<li>Names must include only alphabets from [a-z, A-Z, and spaces]</li>
</ul>
</li>
</ul>
○&nbsp;&nbsp;&nbsp; Any invalid or misspelled commands must be ignored with an

“unsuccessful” message followed by the execution of the next command.

<ul>
<li>Design/Implementation
<ul>
<li>You must design your own AVL tree from scratch.</li>
</ul>
</li>
</ul>
○&nbsp;&nbsp;&nbsp; You must use the four standard AVL rotations to keep all results standardized for our test cases.

○&nbsp;&nbsp;&nbsp; You must use C++14 and ensure that your code G runs public test cases on Gradescope.

○&nbsp;&nbsp;&nbsp; Additionally a starter template is provided which you can use for locally testing your code which can help you in saving some delay time if you were to repeatedly use a cloud based grader: <a href="https://ufl.instructure.com/courses/471516/files/74778786?wrap=1">Project1.zip</a>

<h1>Sample Input/Output</h1>
<h2><strong>Input</strong></h2>
8 insert “Brandon” 45679999 insert “Brian” 35459999 insert “Briana” 87879999 insert “Bella” 95469999 printInorder remove 45679999 removeInorder 2 printInorder

* <strong>Note</strong>: Line 1 denotes the number of lines or the total number of commands that follow.

<strong>Output </strong>successful successful successful successful Brian, Brandon, Briana, Bella successful successful Brian, Briana

<h1>Testing</h1>
Test your code on Starter template and/or Gradescope. You have five available test cases and you can submit any number of times.

In addition to the 5 public test cases, after the due date your submission will be tested with 10 additional test cases. In order to maximize your grade, you need to <strong>create your own test cases </strong>and run them against your code <strong>in the starter template</strong>. In particular, you should test your code with test cases that include over <strong>100 insertions </strong>into your tree and small tests that cover every case of the four rotations.

<h1>Project 1 Breakdown Slides</h1>
<strong>Slides found </strong><a href="https://docs.google.com/presentation/d/1llw2u6PmbgUjE1nQM_Qyc4lVMeb84_UVINRpQvrycqE/edit#slide=id.p">here</a>

<a href="https://docs.google.com/presentation/d/1llw2u6PmbgUjE1nQM_Qyc4lVMeb84_UVINRpQvrycqE/edit#slide=id.p">Links to an external site.</a>

<h2>FAQs</h2>
The course staff will maintain an active FAQ Google document to answer your questions. <a href="https://docs.google.com/document/d/1X1giXYQStDsqXYawDLNuEJaucUcHsmr9kgSIVnwC_Z4/edit">Links </a><a href="https://docs.google.com/document/d/1X1giXYQStDsqXYawDLNuEJaucUcHsmr9kgSIVnwC_Z4/edit">to an external site.</a>

<h1>Grading</h1>
<ul>
<li><strong>Implementation [75 points]</strong>
<ul>
<li>Your code will be tested on 15 test cases each worth 5 points:</li>
</ul>
</li>
</ul>
■&nbsp;&nbsp;&nbsp; 5 publicly available test cases that are a part of Starter template and/or Gradescope

■&nbsp; 10 test cases that will be added by the course staff during grading

<ul>
<li><strong>Documentation [15 Points]</strong>
<ul>
<li>Submit a document addressing these prompts:</li>
</ul>
</li>
</ul>
■&nbsp;&nbsp;&nbsp; What is the time complexity of each method (<strong>corresponding to a command</strong>) in your implementation? Reflect on the worst case time complexity represented in Big O notation.

■&nbsp;&nbsp;&nbsp; <strong>Note </strong>that the methods here refer to the methods you call for the respective commands. You don’t need to analyze the time complexities of helper methods, constructors, etc. although you have to account for helper methods time complexities when you analyze a command that calls those helper functions.&nbsp; [10 points]

■&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; What did you learn from this assignment and what would you do differently if you had to start over? [5 points] ●&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>Code Style and Design [10 Points]</strong>

○&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 6 points for design decisions and code modularity ■&nbsp; We inspect the following in your code:

■&nbsp;&nbsp;&nbsp; <a href="https://stackoverflow.com/questions/14000762/what-does-low-in-coupling-and-high-in-cohesion-mean">High cohesion</a>

■&nbsp;&nbsp;&nbsp; <a href="https://stackoverflow.com/questions/14000762/what-does-low-in-coupling-and-high-in-cohesion-mean">Links to an external site.</a>

■

■&nbsp;&nbsp;&nbsp; Appropriate modularity

■&nbsp;&nbsp;&nbsp; Relevant access modifiers

■&nbsp;&nbsp;&nbsp; Proper memory management

■&nbsp;&nbsp;&nbsp; Efficient mechanisms for passing parameters in your function signatures

■ The client (your int main() method) should not have objects that interact with memory directly – or a well defined API for your AVL Tree

○&nbsp;&nbsp;&nbsp; 1 point for appropriate comments

○&nbsp;&nbsp;&nbsp; 1 point for consistent whitespace mechanism

○&nbsp;&nbsp; 2 points for consistent naming conventions ●&nbsp;&nbsp; <strong>Bonus [5 points] – Capped to 100 points</strong>

○&nbsp;&nbsp;&nbsp; You can score 5 bonus points if you submit a separate file containing 5 test cases (1 point/test) using the Catch Framework. These tests should be different than the public test cases. <strong>Your score is however capped to 100 points for this project. </strong>This means that if you pass 14 tests and submit bonus test files, you will get a 100 provided you score full points on the documentation. Also, if you pass 15 tests and score 23 on documentation and design, + 5 points on bonus, you will still score 100 points [your score is 103 but is capped to 100 in this case].

<h2>Submission</h2>
<ul>
<li>You are required to upload on Gradescope the following:</li>
</ul>
○&nbsp;&nbsp;&nbsp; at least <strong><em>one </em></strong>.cpp file that has your implementation of the entire project including the main. If you use header files or more than one .cpp file, upload all of them together on Gradescope. Feel free to choose the names for your header and .cpp files. <strong>Make sure at least one .cpp file contains the main() method.</strong>

○&nbsp;&nbsp;&nbsp; one pdf file that has your documentation and your name on the front page of the pdf. Name this pdf as <strong><em>Report.pdf</em></strong>.

<ul>
<li>Optionally, you can submit the catch tests in a pdf file called: <strong><em>pdf </em></strong>if you decide to submit the unit tests.</li>
<li><strong>Failure to follow these instructions will lead to 10% non-negotiable penalty</strong></li>
</ul>
