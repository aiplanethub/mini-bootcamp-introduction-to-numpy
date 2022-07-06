# Add, Remove and Sort

### Adding an Element

* Create a NumPy array:

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_2186b550d321487a9909a9ec444a9126.png)
* You can use append method to add an element in a NumPy array:
![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_58bc473d9854431bb9990f69b22de612.png)
* You can also add an element to a Python list using np.append() method. But the returned object is a NumPy array.
![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_18f126fa76aa4e8f91bc3d9227b82740.png)
* You can also add a list of elements. Try doing this by yourself. For example, **`np.append(arr, [11, 22])`**.



### Caution!

* A NumPy array doesn’t support append() method directly on the array. The given snippet will clear this:

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_e2d929a0a1364f349944d7efa8f1ee30.png)

* But a Python list supports append() method directly on the Python list:

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_0e9ebedab4af4ec182a00ac030aa1029.png)

### Removing an Element

* You can remove an element from an array using delete method of NumPy. See the snippet below:

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_1c155f3fc71f4d70b86e909f17d15727.png)

* You can also remove an element from a Python list using np.delete() method.

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_78e3feebccde4ae8a13524c812d32422.png)

### Sorting an Array

* You can quickly sort an array in ascending order as:

![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_774336a540cb48aea69db51322a427b9.png)

* You can sort a NumPy array or a Python list by using ‘.sort()’ directly on the array or the list. You can try this by yourself.