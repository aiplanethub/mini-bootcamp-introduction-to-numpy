# Shape, Size, and Data Type of an Array

### Create a NumPy Array

Import NumPy and create a NumPy array.
![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_d7f1fc45347e4253b985c00a12bbeabe.png)

### Size of an Array

NumPy array has an attribute called size that tells you the total number of elements in the array.

You can check the size of a NumPy array using the ‘.size’ attribute. It returns the total number of elements present in the array:
![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_d1f961ba41a24af3ba878299dfb1089a.png)

### Data Types of Array

You can check the type of data in the NumPy array using the ‘.dtype’ attribute. The data type of array ‘arr’ is ‘int’ (integer). Here, ‘32’ is related to memory allocation.
![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_f5b98b95eb0244efa598e1f4ed4b9f94.png)

Note: If you have a 64-bit computer, dtype might be displayed as int64, and if you have 32-bit, it might be displayed as int32

### Shape of an Array

An array has an attribute called shape that tells you the number of items along each axis.

If we have an array with two axes, the shape attribute will tell you the total number of rows and columns in that array.

The shape attribute of NumPy returns a tuple of integers that represents the number of items along each axis.

Consider the given array ![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_530044a7272b4532939636c2d4703d40.png)
You can check the shape of a NumPy array using the method ‘.shape’. In array ‘arr’, there are four rows and three columns.
![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_c3567d70ab164e8c8e33a8a9f51820b1.png)

### Dimension of an Array

Consider the given array ![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_6b54bac4a846482d9c4e3bcd51317871.png)

An array has an attribute called dimension that tells you the number of axes in the array.

You can check the number of dimensions of a NumPy array using the ‘.ndim’ attribute. The array ‘arr’ is 2-dimensional (i.e., the array has two axes).
![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_2bbc30f7e1b44b4f8083f3bd6833c82a.png)

### type() function and dtype method

Everything in Python is an object.

Suppose you have an object and want to know what type of object it is; you will use the type() function to get this information.

Now you know the object is a NumPy ndarray. To know the data type in that array, you will use the attribute ‘.dtype’. This is also called the type of NumPy array.

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_005ee3200e284fae8771eef7ece07edc.png)

### Caution: dtype method on Python Lists

Note that Python lists don’t support the ‘.dtype’ attribute or any other methods supported by a NumPy array.

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_15bb7755796640a987bee8429fed7326.png)