# cse220-lab-2-solved
**TO GET THIS SOLUTION VISIT:** [CSE220 Lab 2 Solved](https://www.ankitcodinghub.com/product/cse220-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119724&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE220 Lab 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Instructions for students:

1. Complete the following methods on Linked lists.

4. The submission format MUST be maintained. You need to copy paste all your codes in ONE SINGLE .txt file and upload that. If format is not maintained, whole lab submission will be canceled.

5. If you are using JAVA, you must include the Tester class containing the main method which should test your other methods in MyList class and print the outputs according to the tasks.

7. Usage of built in methods/libraries are NOT ALLOWED

8. The google form link for this lab is provided in BUX under LAB 2-Linked Lists subsection under the SPRING21 CSE220 lab tab.

Linked List

Task 1:

i) Create a Node class which will hold two fields i.e an integer element and a reference to the next Node.

ii) Create a Linked list Abstract Data Type (ADT)named MyList.The elements in the list are Nodes consisting of an integer type key (all keys are unique) and a reference to the next node.

[You are not allowed to use any global variable other than head]

1. Constructor:

a. MyList (int [] a) or def __init__ (self, a)

Pre-condition: Array cannot be empty.

Post-condition:This is the default constructor of MyList class. This constructor creates a list from an array.

2. void showList ( ) or def showList(self) (2)

Precondition: None.

Postcondition: Outputs the keys of the elements of the order list. If the list is empty, outputs “Empty list”.

3. boolean isEmpty ( ) or def isEmpty(self) (1)

Pre-condition: None.

Post-condition: Returns true if a list is empty. Otherwise, returns false.

4. void clear ( ) or def clear(self) (1)

Pre-condition: The list is not empty.

Post-condition: Removes all the elements from a list.

5. void insert (Node newElement) or def insert(self, newElement) (3) Pre-condition: None.

Post-condition: This method inserts newElement at the tail of the list. If an element with the same key as newElement already exists in the list, then it concludes the key already exists and does not insert the key.

6. void insert (int newElement, int index) or def insert(self, newElement, index) (4)

Pre-condition: The list is not empty.

Post-condition: This method inserts newElement at the given index of the list. If an element with the same key as newElement value already exists in the list, then it concludes the key already exists and does not insert the key. [You must also check the validity of the index].

7. Node remove (int deleteKey) or def remove(self, deletekey) (4)

Pre-condition: List is not empty.

Post-condition: Removes the element from a list that contains the deleteKey and returns the deleted key value.

1. Write a function to find out the even numbers that are present in the list and output another list with those numbers. (3)

Sample Input Sample Output

1 -&gt; 2 -&gt; 5 -&gt; 3 -&gt; 8 2 -&gt; 8

101 -&gt; 120 -&gt; 25 -&gt; 91-&gt; 87 -&gt; 1 120

2. Write a function to find out if the element is in the list or not. (3)

Sample Input Sample Output

1 -&gt; 2 -&gt; 5 -&gt; 3-&gt; 8 and 7 False

101 -&gt; 120 -&gt; 25 -&gt; 91-&gt; 87 -&gt; 1 and 87 True

3. Write a function to reverse the list. [You are not allowed to create any other list] (3)

Sample Input Sample Output

1 -&gt; 2 -&gt; 5 -&gt; 3-&gt; 8 8 -&gt; 3 -&gt; 5 -&gt; 2 -&gt; 1

4. Write a function to sort the list. [You are not allowed to create any other list] (3)

Sample Input Sample Output

1 -&gt; 2 -&gt; 5 -&gt; 3-&gt; 8 1 -&gt; 2 -&gt; 3 -&gt; 5 -&gt; 8

5. Write a function that prints the sum of the values in the list. (4)

Sample Input Sample Output

1 -&gt; 2 -&gt; 5 -&gt; 3-&gt; 8 19

6. Write a function that rotates the elements of the list k times. [You are not allowed to create any other list]. (4)

Sample Input Sample Output

3 -&gt; 2 -&gt; 5 -&gt; 1-&gt; 8, left, 2 5 -&gt; 1 -&gt; 8 -&gt; 3 -&gt; 2

3 -&gt; 2 -&gt; 5 -&gt; 1-&gt; 8, right, 2 1 -&gt; 8 -&gt; 3 -&gt; 2 -&gt; 5
