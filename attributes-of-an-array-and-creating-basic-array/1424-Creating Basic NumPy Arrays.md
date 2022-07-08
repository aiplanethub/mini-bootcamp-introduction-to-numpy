# Creating Basic NumPy Arrays

### array( )

You can use the array() function to create a numpy array.

You can see here that the first row in arr is nothing but the first inner list \[1, 2, 5, 7]; similarly, the other rows are other inner lists index-wise.
![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_44efcf1dafe3476e97b5f5529e7c7905.png)

### arange( )

Use arange() function to create collection of continuous integers.
![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_aa60921d6a504e1f9042be8a10a69062.png)

Here, 10 means arange will generate the first ten integers starting from 0. Similarly, if you pass 5 inside the bracket, it will generate numbers from 0 to 4 (i.e., first five integers): \[ 0, 1, 2, 3, 4 ]

### zeros( )

If you want to create a collection of zero values, you can use the zeros() function available in NumPy.

The zeros() function creates an n-dimensional array of zeros. If no shape is specified, then it will create a one-dimensional array:

For instance, 5 means it will generate five zeros.
![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_444ffe58ce9840bf889fa46a035dbc27.png)

### ones( )

In case you want a collection of ones, NumPy has a function called ones().

Here 4 means ones() will generate four ones.

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_cbbec70928ee4bb59f14918a1ea72752.png)

### linspace( )

linspace() generates values that are equally spaced from each other.

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_540ae4787ad640fc955fcf8ca0539f6a.png)

If you don’t pass the ‘num’ argument, it will generate 50 equally spaced values.