# Arrays

### Learning Objectives

* Understanding keywords
* Arrays
* Lists vs. Arrays

### Understanding Keywords

Before jumping into what arrays are all about, we need to recap what we learned about lists in the “Introduction to Python Programming” course. In addition, we need to know some keywords such as “Dimension”.

### List

* As the name suggests, **list is an ordered sequence of data. In real life, if you could make a list of things that come to your mind** (or event for any specific purpose), it could be something like this –
  * Brush
  * Leuven
  * 48851964400
  * 3.14
  * Mom
* **You could make your own list & include whatever you want in it.** So, in my list, I have included what I do early in the morning, my city, my mobile number, the value of pi to two digits, and mom.
*   If you look at it, my list has different types of data – strings, float, and integer. And this is the kind of flexibility Python List provides. It can hold different types of data types. **Declaring a list is pretty straightforward. You use square brackets (\[]) and separate the items by commas.** Let me write an example - 

    `A = ["Brush", "Leuven", 48851964400, 3.14, "Mom"]`

### Dimensions

**Now, what are dimensions?** Let’s take the example of a box to explain this. A box has three dimensions - width, length, and depth (or height). Similarly, in data science, we will work with “N” dimensions in a data structure (list, arrays, vectors, etc.). “N” could be any number.

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_830f0e57f72e4069934a6c31dbbefdc4.png)

### What are Arrays?

* Similar to a list, an array is a data structure that can hold more than one value at a time.
* **However, an array can only hold a collection of ordered elements of the same data type.**

### Examples of Arrays & Lists

**Arrays - Examples**

* \[1, 2, 3, 4, 5] is an array of integers.
* \[ ‘a’, ‘b’, ‘c’, ‘d’, ‘e’ ] is an array of strings.
* \[\[ 1 , 2 , 3 , 4],\
     \[ 5, 6, 7, 8 ]] is a 2 dimensional array.

**Lists - Examples**

* \[ 1, 2, 3, ‘a’, 5 ] is a list containing both integers and a string.
* \[ 1, 2, 3, 4, ‘b’, \[ 1, 2, 3 ] ] is a list containing integers, a string, and another list.

### Why Arrays?

* A combination of Arrays, together with Python, could save you a lot of time. Arrays help reduce the overall size of your code.

### List vs Array

* A list can store different data types such as integers, strings, etc., whereas an array stores only single data type values, i.e., you can only have an array of integers, an array of strings, etc.