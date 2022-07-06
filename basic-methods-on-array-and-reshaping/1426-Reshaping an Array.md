# Reshaping an Array

### Can you reshape an array?

### YES!

* Using **np.reshape()** will change the shape of your array.
* Also, there won’t be any changes in the original data other than the shape.
* **Caution:** Whenever you use reshape() method, you need to make sure that the array you want to produce after reshaping needs to have the same number of elements as the original array.
* Suppose you have an array with 24 elements. If you want to reshape this array, you need to make sure that your new array also has a total of 24 elements. You can reshape this array into (8, 3), (6, 4), (12, 2), and so on, as all these will also have total of 24 elements (8 $\times$ 3 = 24, 6 $\times$ 4 = 24, 12 $\times$ 2 = 24).
* Create an array with 24 elements in it.

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_d85e39a7f4e74d9dac246a3097d5aba6.png)

* Use **np.reshape()** to change the shape of arrays as shown in the code snippet here.
* Array with shapes (8, 3), (6, 4) and (2, 12) have 24 elements in it.
* All of these three arrays have the same values that were present in the initial array **‘arr’**.

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_f1b85ed25c3d409db09f3a0b411f94b0.png)

### Reshaping a Python List

Using np.reshape() you can change the shape of a Python list but the returned object is of type numpy.ndarray, i.e., it becomes a NumPy array.

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_255537b3a8824cb495fb0ea12970e8a8.png)

### Using reshape() directly on Array

You can use reshape() method directly on the NumPy array:

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_9928af58075644438a46a7068191289e.png)
**Caution!** Using reshape() method on a Python list will throw an ‘AttributeError’.
![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_0009281e95ee445fa02692e4f20556a3.png)