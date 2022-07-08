# Compare Python List and NumPy Array

|                                Python List                                 |                                   NumPy Array                                   |
| :---------------------------------------------------------------------------: | :-----------------------------------------------------------------------------: |
|                    Can contain data of different data types                   |                        Can contain data of same data type only                       |
| Takes a huge amount of time and memory for numerical computations of large data | Very cheap in terms of time and memory for numerical computations of large data |

### Compare Python List & Numpy Array

* Create two lists:
![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_07b39217ebdb47769c630a3e71be234e.png)
* Import NumPy and Create two numpy arrays using the two Python lists:
![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_4b825af8e4f941348c7e7ed23d7169ed.png)
* Define a function that will perform element-wise addition of two Python lists.
![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_2ba18daf0bf24bb99e82e050f41d7434.png)
* Define a function that will perform element-wise addition of two NumPy arrays.
![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_2abbd6f105de4147b79ce25ddb97e9df.png)
* Notice the time taken by both the functions (i.e. list\_sum() and numpy\_arr\_sum()) to perform the same task.
![image.png](https://dphi-live.s3.amazonaws.com/media_uploads/image_9e225242fd594d8da52af9b6cca2ce4f.png)
* You can observe here that the time taken by the python list to do the element-wise sum is much more than the NumPy arrays.