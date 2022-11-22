# [Patika.dev](https://www.patika.dev/) Sorting Project 1
**[22,27,16,2,18,6]**

1. Write the steps of the array given above according to the **insertion sort**.
2. Write the **Big-O notation**.
3. After the array is sorted if we want to search for the number 18 , what is the **time complexity**?

### **1-**
*Step 1* : [**22**|27,16,2,18,6] \
*Step 2* : [22,**27**|16,2,18,6] \
*Step 3* : [22,**16**,27|2,18,6] -> [**16**,22,27|2,18,6] \
*Step 4* : [16,22,**2**,27|18,6] -> [16,**2**,22,27|18,5] -> [**2**,16,22,27|18,6] \
*Step 5* : [2,16,22,**18**,27|6] -> [2,16,**18**,22,27|6] \
*Step 6* : [2,16,18,22,**6**,27] -> [2,16,18,**6**,22,27] -> [2,16,**6**,18,22,27] -> [2,**6**,16,18,22,27] \
Sorted array = [2,6,16,18,22,27]
### **2-**
Big-O = O(n<sup>2</sup>)
### **3-**
If we search for the number 18, time complexity will be **average case**.

-------------------
**[7,3,5,8,2,9,4,15,6]**

Write the first four steps of the array given above according to **selection sort**.

*Step 1* : [7,3,5,8,**2**,9,4,15,6] -> [**2**,3,5,8,7,9,4,15,6] \
*Step 2* : [2,**3**,5,8,7,9,4,15,6] \
*Step 3* : [2,3,5,8,7,9,**4**,15,6] -> [2,3,**4**,8,7,9,5,15,6] \
*Step 4* : [2,3,4,8,7,9,**5**,15,6] -> [2,3,4,**5**,7,9,8,15,6]