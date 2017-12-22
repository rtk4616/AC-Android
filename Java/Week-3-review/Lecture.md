
# Review

---

# Objectives
* Answer the questions you have
* Review String functions
* Writing a While Loop
* Switch statements
* Review HashMaps
* Review Sets
* Review Stacks
* Review Queues
* Review creating classes with methods
* Review everything that has been taught.
* Solve some HackerRank problems

---

## Review String functions

> **Exercise** Write three examples for creating a String object. Use the empty
string constructor, the constructor that accepts a char array and a constant
assignment.

> **Exercise** Refer to the Strings Api for this question. What method is used
in strings to find the first occurrence of a character? What method is used to
find the last occurrence?

> **Exercise** Write a function that counts the number of vowels in a string, up
to the first letter 'z'. For example 'aeizou' should return 3. Use a for loop.

---

## Writing a While Loop
> **Exercise** Write a function that counts the number of vowels in a string, up
to the first letter 'z'. For example 'aeizou' should return 3. Use a while loop.

> **Exercise** Write a while loop that prints out "{A Number} bottles" 100
times, once per line. '{A Number}' should be replaced with the numbers 0 to 99,
counting upwards.

> **Exercise** Write a while loop that prints out "{A Number} bottles" 100
times, once per line. '{A Number}' should be replaced with the numbers 99 to 0,
counting downwards.

---

## Switch statements
> **Exercise** Write a for loop that iterates through an array of integers, and
prints out "Found 3" each time the number 3 is found, and " Saw 5" each time
the number 5 is found. Use a switch statement to compare the numbers

---

## HashMap Questions
> **Question 1**
What is the difference between a HashMap and HashTable?

> **Question 2**
When creating a HashMap and specifying the type using a Map variable, how many
types must you provide?

> **Question 3**
What function returns a list of the HashMap keys? What function returns a list
of the values?

> **Question 4**
When would you use a HashMap?

---

## Set Questions
> **Question 5**
How many elements in a Set can be null?

> **Question 6**
What is the parent class of Set?

> **Question 7**
What interfaces extend Set?

> **Question 8**
What is the difference between a Set and a List?

---

## Stack Questions
> **Question 9**
How many interfaces does Stack implement?

> **Question 10**
Draw a picture of a stack after the following code is executed
```java
Stack<Integer> stack = new Stack<>();
stack.push(5);
stack.push(8);
stack.peek();
stack.pop();
stack.push(4);
```
> **Question 11**
What is the difference between a Stack and a Set?

---

## Queue Questions
> **Question 12**
If I wanted to remove an element from a queue, but not throw an exception if the
queue is empty, what function would I use?
> **Question 13**
If I wanted to get the value of the head of a queue, and throw an exception if
there is no value, what function would I use?

> **Question 14**
What are the interfaces that extend the Queue interface?

---

## Data Structure programs
> **Question 1**
Using a HashMap, write a function that accepts a char, and returns the name of
a fruit that starts with that letter.

> **Question 2**
Using a HashMap and a Queue, build a function that simulates a donut shop. The
HashMap will use the types of donuts as keys, and will use Queues to hold the
number of donuts available.

Initialize the donut shop hashmap with the following values:
```java
Chocolate -> {Sprinkles, Chips, Swirl}
Cinnamon -> {}
Blueberry -> {Swirl, Frosting }
```
Then write a function that, using a while loop, constantly reads a String from
input. If the string matches a key of the hashmap, print the next donut from
that queue and remove it. If the queue is empty print "No more left";

> **Question 3**
After having built a donut shop, we want to expand into a donut empire. Using a
stack, create a data structure that holds 3 donut shop hashmaps. When a user
requests a donut, each donut shop must now be checked to see if that donut is
available.

---

## Classes and Methods

> **Question 1**
Create a class Food with string fields `name` and `type` with getters and setters
Create a Fruit that has boolean method isRipe() and extends Food.
In a main method, create and print a food instance whose name is Burrito and a fruit Apple.

---

## Hacker Rank Anyone?

---