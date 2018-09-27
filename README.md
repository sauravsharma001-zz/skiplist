# **SkipList DataStructure Implementation**
- Project Description
  Implement the following operations of skip lists. Starter code is provided. Do not change the signatures of methods declared to be public. You can add additional fields, nested classes, and methods as needed.
  - add(x): Add a new element x to the list. If x already exists in the skip list,
    replace it and return false.  Otherwise, insert x into the skip list and return true.
  - ceiling(x): Find smallest element that is greater or equal to x.
  - contains(x): Does list contain x?
  - first(): Return first element of list.
  - floor(x): Find largest element that is less than or equal to x.
  - get(n): Return element at index n of list.  First element is at index 0.
    Call either getLinear or getLog.
  - getLinear(n): O(n) algorithm for get(n).
  - getLog(n): O(log n) expected time algorithm for get(n).
    This method is optional, but code it correctly to earn EC.
  - isEmpty(): Is the list empty?
  - iterator(): Iterator for going through the elements of list in sorted order.
  - last(): Return last element of list.
  - rebuild(): Reorganize the elements of the list into a perfect skip list.
  - remove(x): Remove x from the list. If successful, removed element is returned.  Otherwise, return null.
  - size(): Return the number of elements in the list

## **Group Members**:
- Saurav Sharma (sxs179830)
- Sudeep Maity (sdm170530)
- Shiva Prasad Reddy Bitla (sxb180066)

## **Software stack used while developing and running the project**:
- Language: Java 8
- Compiler: jdk1.8.0_171

## **Instructions to compile and run the project from command line**:
- Naviagate to "sxs179830" and open command prompt at this location
- Compile the source file 
   - "javac -cp . sxs179830\SkipList.java"
- Run the program using following command
   - "java sxs179830.SkipList"
