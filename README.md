# cs204-take-home-exam-6--outside-the-wall-solved
**TO GET THIS SOLUTION VISIT:** [CS204 Take-Home Exam 6– Outside The Wall Solved](https://www.ankitcodinghub.com/product/cs204-advanced-programming-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109404&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS204 Take-Home Exam 6– Outside The Wall Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
DISCLAIMER:

Introduction

The aim of this assignment is to practice inheritance and polymorphism. The goal is to implement a base abstract class with three subclasses. The base class will be a container class which is an abstract class. Then you will implement a sorted LinkedList, Stack and Queue classes that inherit from the Container class. The main function is given and you are only supposed to implement the classes.

This assignment will not be included in the curve, so you will not lose anything if you do not

submit it. If you do the assignment and if it works as desired, you will have 3 points added to

your overall grade! Thus, it is completely your choice 🙂

grade can be at most what your program gets from CodeRunner if you obey the rules. Please

note that this is an “ALL OR NOTHING”-grading assignment: there will not be any partial

credits.

Program Flow

The program will iteratively ask the user to select a data structure and then an operation.

The data structures are: 0- LinkedList, 1- Stack, 2- Queue The operations are:

0- Insert: Insert an integer to the corresponding data structure. You can assume that no duplicates will be inserted.

1- Delete: Delete an integer from the corresponding data structure.

2- Print: Print the corresponding data structure.

The program will terminate if the user enters 3 as the first of the coupled inputs, which semantically stands for “Exit” (i.e. 3- Exit).

The base class will define these functions as pure virtual functions. Then all the subclasses will implement these functions according to their definitions, as given below. Also, every data structure should display a message explaining the operation being carried out. For further information, please refer to the sample runs.

We will inspect your class implementations thoroughly. This means, disobeying the Object Oriented Design or Inheritance philosophies will hurt your grade badly.

Sorted Linked List Stack Queue

Insert Insert in order Insert to the top Insert to the rear

Delete Delete number Delete number if it is at top Delete number if it is at front

Print Print the contents of the respective container

For the sorted linked list class, we will never use a case where a non-existing element will be supplied for deletion.

Sample Runs

Below, we provide some sample runs of the program that you will develop. The italic and bold phrases are the standard input (cin) taken from the user (i.e., like this). You have to display the required information in the same order and with the same words/spaces as here; in other words, there must be an exact match!

Sample Run 1

0

0

5

5 is inserted into the linked list.

0

2

Printing the linked list:

5

0

0

8

8 is inserted into the linked list.

0

2

Printing the linked list:

5 8

0

0

2

2 is inserted into the linked list.

0

2

Printing the linked list:

2 5 8

0

1

5

5 is deleted from the linked list.

0

1

2

2 is deleted from the linked list.

0

2

Printing the linked list:

8

1

1

5

5 cannot be deleted from the stack.

1

0

1

1 is inserted into the stack.

1

1

7

7 cannot be deleted from the stack.

1

1

1

1 is deleted from the stack.

1

2

Printing the stack:

2

2

Printing the queue:

2

0

7

7 is inserted into the queue.

2

0

1

1 is inserted into the queue.

2

2

Printing the queue:

7 1

2

1

1

1 cannot be deleted from the queue.

2

1

7

7 is deleted from the queue.

2

2

Printing the queue:

1

3

Destructing the linked list.

Destructing the stack.

Destructing the queue. Exiting..

Some Important Rules

Submit via SUCourse ONLY! Paper, e-mail or any other methods are not acceptable.

The internal clock of SUCourse might be a couple of minutes skewed, so make sure you do not leave the submission to the last minute. In the case of failing to submit your THE on time:

“No successful submission on SUCourse on time = A grade of zero (0) directly.”

What and where to submit (PLEASE READ, IMPORTANT)

It’d be a good idea to write your name and last name in the program (as a comment line of course). Do not use any Turkish characters anywhere in your code (not even in comment parts). If your full name is “Duygu Karaoğlan Altop”, and if you want to write it as comment; then you must type it as follows:

// Duygu Karaoglan Altop

Since the grading process will be automatic, you are expected to strictly follow these guidelines. If you do not follow these guidelines, your grade will be zero (0). Any tiny change in the output format will result in your grade being zero (0), so please test your programs yourself, and against the sample runs that are available at the relevant assignment submission page on SUCourse.

In the CodeRunner, there are some visible and invisible (hidden) test cases. You will see your final grade (including hidden test cases) before submitting your code. There is no re-submission. You don’t have to complete your task in one time, you can continue from where you left last time but you should not press submit before finalizing it. Therefore, you should make sure that it’s your final solution version before you submit it. Also, we still do not suggest that you develop your solution on CodeRunner but rather on your IDE on your computer.

How to get help?

Good Luck!

Ahmed Salem, Duygu Karaoğlan Altop
