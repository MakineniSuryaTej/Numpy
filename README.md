# Numpy

Numpy functions:

## 1)1-D array:
np.array([....])

## 2)n-D array:
np.array([[....],...,[....]])

## 3)0's array:
np.zeros((n,m)) --> n,m are dimensions

## 4)array with same number:
np.full((n,m),v) --> n,m are dimensions and v is the value to be filled

## 5)array with a range:
np.arange(l,u) (or) np.arange(l,u,step) --> l,u are lowerlimit and upperlimit and step is step count

## 6)array with random numbers:
np.random.randint(l,u,n) --> l,u are lowerlimit and upperlimit for random numbers and n is number of numbers to be added to array

## 7)Chage shape:
np.shape=(n,m)

## 8)Joining arrays vertically:
np.vstack((array1,array2,...))

## 9)Joining arrays horizantally
np.hstack((array1,array2,...))

## 10)Joining arrays column wise
np.column_stack((array1,array2,...))

## 11)Intersection:
np.intersect1d(array1,array2)

## 12)Differnce:
np.setdiff1d(array1,array2)

## 13)Addition:
np.sum([array1,array2],axis=)

## 14)Basic math:
array=array+v
array=array*v
array=array-v
array=array/v --> v is any value

## 15)Mean,Median,Standard deviation
np.mean(array)
np.median(array)
np.std(array)

## 16)Save and Load numpy array
np.save(name,array)
np.load(name.npy)
