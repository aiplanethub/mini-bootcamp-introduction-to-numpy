# Positive Indexing

### Rows and Columns Indexes in an Array

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_194a8f60ef314804a038fc8fd0808300.png)

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_2e1524b1fea644be9b415e670acf6eea.png)

* Conclusion: If you want to get the 4th element from an array, you should extract the element that is present at index 3.
* Generalizing: If you want to get the nth element from an array, you should extract element that is present at index (n-1).

### Positive Single Indexing in an Array

Say you have an array with elements: [10, 20, 30, 40] in it. You want to get the 3rd element from the array. Use square brackets ([ ]) and pass the index number (2 in this case) in that square brackets as you used to do for Python lists.

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_6824133f1d0e40e7bd8d099de7bb3148.png)

Now, what is the dimension of the array? Yep, it's 1!

Remember how we used to extract an element from a nested list in Python? No? No worries. You will remember once you jump to the below part.

### Positive Single Indexing in Python Nested List

The below snippet will help you remember how to get one element from a Python nested list.

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_0ac2e3e4d34e4f38a69216f386730488.png)

### Positive Single Indexing in a NumPy Array

The array here is of dimension 2. You can compare Python nested list and a NumPy 2D array.

In NumPy 2D array, when you pass a single index in the square bracket, it will give you the entire row present at that index.

You can pass comma-separated values in the square bracket to get one element from a particular row and a particular column.

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_da95bf2b8a254676b25538318e7d7653.png)

In the snippet shown here, num_arr[0, 0] will get you the element present at row indexed at 0 and column indexed at 0. Try num_arr[0][0] in your Notebook and see what you get.

### Positive Index Intervals in a NumPy Array

You can use semicolon (:) while indexing to get slices of elements from NumPy array.

In the snippet, num_arr[0, 0:2] will get you the row indexed at 0 and the columns indexed from 0 (inclusive) to 2 (exclusive).

This is also known as slicing an array.

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_2bccfcaff05346a8a5ea16605eeeb2c5.png)

You can slice rows and columns as shown in the snippet.

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_1bc00921b7aa45458451d520fcf8d8b4.png)

In the snippet, num_arr[1:3, 2:4] will get you the rows starting from index 1 to rows ending at index 3 (exclusive, means excluding 3) i.e. row 1 and row 2, columns starting from index 2 and ending at index 4 (exclusive) i.e. column 2 and column 3.

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_4a73796728a94017b8846101073d8cbc.png)