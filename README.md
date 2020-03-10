# numpytutorial
My numpy learnings

#Numpy Day1:
- import numpy as np
- mylist = [1,2,3,4]
- myndarray = np.array(mylist) // array([1,2,3,4])
- myndarray +=1 // array([2,3,4,5])
- myndarray2 = myndarray +1 // array([3,4,5,6])
- myndarray2 + myndarray // array([5,7,9,11])
- myndarray2 * myndarray // array([6,12,20,30])
- myndaary2.shape //dimension of ndarray (4,)
- myndarray2d = np.array([[1,2,2,3], ['a','b','c','d']]) // 2d array
- myndarray2d.shape //(2,4)
- myndarray2d = np.array([[1,2,2,3], ['a','b','c']]) // 2d array
- myndarray2d.shape //(2,) // uneven

#Numpy Day2:
- myndarray.dtype => actual datatype of data in np array
- All Data in an nparray are tried to converted into a single datatype, in the order string, float, int
- myndarray.size => number of elements in total in np array
- myndarray.ndim => give the dimension of the array
- myndarray.fill(value) => will fill the corresponding value in all the index of the given ndarray
