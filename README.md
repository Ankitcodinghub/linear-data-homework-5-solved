# linear-data-homework-5-solved
**TO GET THIS SOLUTION VISIT:** [Linear Data Homework 5 Solved](https://www.ankitcodinghub.com/product/data-structure-important-solved-6/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110167&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Linear Data Homework 5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1. All submitted code must compile under JDK 8. This includes unused code, so don’t submit extra files that don’t compile. Any compile errors will result in a 0.

2. Do not include any package declarations in your classes.

3. Do not change any existing class headers, constructors, instance/global variables, or method signatures.

4. Do not add additional public methods.

5. Do not use anything that would trivialize the assignment. (e.g. don’t import/use java.util.ArrayList for an Array List assignment. Ask if you are unsure.)

6. Always be very conscious of efficiency. Even if your method is to be O(n), traversing the structure multiple times is considered inefficient unless that is absolutely required (and that case is extremely rare).

7. You must submit your source code, the .java files, not the compiled .class files.

8. After you submit your files, redownload them and run them to make sure they are what you intended to submit. You are responsible if you submit the wrong files.

Heaps

For this assignment, you will be coding a max heap that is backed by an array. A max heap is a type of binary tree with two main properties.

• Shape Property: The tree must be complete, meaning that all levels of the tree must be full except the bottommost level, which if not full must be filled from left to right.

• Order Property: Each node’s data is larger than the data in its two children. There is no explicit relationship between sibling nodes.

These properties imply that the largest element in the heap will be at the root of the heap.

Grading

Here is the grading breakdown for the assignment. There are various deductions not listed that are incurred when breaking the rules listed in this PDF, and in other various circumstances.

Methods:

add 20pts

remove 20pts

getMax 5pts

isEmpty 5pts

clear 5pts

BuildHeap 20pts

Other:

Checkstyle 10pts

Efficiency 15pts

Total: 100pts

A note on JUnits

If you need help on running JUnits, there is a guide, available on Canvas under Files, to help you run JUnits on the command line or in IntelliJ.

Style and Formatting

It is important that your code is not only functional but is also written clearly and with good style. We will be checking your code against a style checker that we are providing. It is located on Canvas, under Files, along with instructions on how to use it. We will take off a point for every style error that occurs. If you feel like what you wrote is in accordance with good style but still sets off the style checker please email Tim Aveni (tja@gatech.edu) with the subject header of “[CS 1332] CheckStyle XML”.

Javadocs

Vulgar/Obscene Language

Any submission that contains profanity, vulgar, or obscene language will receive an automatic zero on the assignment. This policy applies not only to comments/javadocs but also things like variable names.

Exceptions

When throwing exceptions, you must include a message by passing in a String as a parameter. The message must be useful and tell the user what went wrong. “Error”, “BAD THING HAPPENED”, and “fail” are not good messages. The name of the exception itself is not a good message.

For example:

Bad: throw new IndexOutOfBoundsException(‘‘Index is out of bounds.’’);

Good: throw new IllegalArgumentException(‘‘Cannot insert null data into data structure.’’);

Generics

If available, use the generic type of the class; do not use the raw type of the class. For example, use new LinkedList&lt;Integer&gt;() instead of new LinkedList(). Using the raw type of the class will result in a penalty.

Forbidden Statements

• package

• System.arraycopy()

• clone()

• assert()

• Arrays class

• Array class

• Thread class

• Collections class

• Collection.toArray()

• Reflection APIs

• Inner or nested classes

• Lambda Expressions

• Method References (using the :: operator to obtain a reference to a method)

If you’re not sure on whether you can use something, and it’s not mentioned here or anywhere else in the homework files, just ask.

Debug print statements are fine, but nothing should be printed when we run your code. We expect clean runs – printing to the console when we’re grading will result in a penalty. If you submit these, we will take off points.

Provided

The following file(s) have been provided to you. There are several, but we’ve noted the ones to edit.

1. MaxHeap.java

This is the class in which you will implement your max heap. Feel free to add private helper methods but do not add any new public methods, inner/nested classes, instance variables, or static variables.

2. MaxHeapStudentTests.java

This is the test class that contains a set of tests covering the basic operations on the MaxHeap class. It is not intended to be exhaustive and does not guarantee any type of grade. Write your own tests to ensure you cover all edge cases.

Deliverables

You must submit all of the following file(s). Please make sure the filename matches the filename(s) below, and that only the following file(s) are present. If you make resubmit, make sure only one copy of the file is present in the submission.

After submitting, double check to make sure it has been submitted on Canvas and then download your uploaded files to a new folder, copy over the support files, recompile, and run. It is your responsibility to re-test your submission and discover editing oddities, upload issues, etc.

1. MaxHeap.java
