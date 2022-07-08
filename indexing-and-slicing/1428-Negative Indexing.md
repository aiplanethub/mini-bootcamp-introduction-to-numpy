# Negative Indexing

### Rows and Columns With Negative Indexes

Another way to reference NumPy arrays in Python is using negative indexing. The below diagram shows how Python labels elements using negative indices. Essentially, the last element in an axis is labeled -1, the second last as -2, and so on.

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_01b4a5f6edf74d4bb73b817e22ad5059.png)

### Using Negative Single Index

* Using negative indexing on a 1-D array
* Pass the negative index of the element in a square bracket [ ].

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_b9b36de511384379b1d965ffccaf803d.png)

* Using negative indexing on a 2-D array
* Pass the negative index of the element in a square bracket \[].
* Try executing num\_arr\[-1]\[-2] in your notebook

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_5b22edf8316b434db20d19d2ac9d5bda.png)

### Negative Index Intervals

* Now you know how index intervals work on a NumPy array.
* You also know how negative indexing works on Python lists.
* See the snippet shown here. Can you think of how to get the output in the yellow box using negative indexing? Try doing this on your own first.

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_015b28c80bed43b0832b3bbc078b1764.png)

* The following code didn't give the correct solution. Can you figure out why?
![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_be0fd5147d584d11babfc633830b1464.png)
* Here's the correct solution. Phew!
![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_90f5fdc17e2349c191f1dd878c3bca7c.png)