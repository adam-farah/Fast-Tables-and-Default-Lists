# Fast-Tables-and-Default-Lists
This was the third assignment of class COMP 2402 at Carleton University, taught by Professor Dr. Patrick Ryan Morin.

Author: Adam Farah

This was split into 2 parts. Skeleton code was provided by Dr.Morin, therefore only the code I the student wrote will only be up hear to see.

Part 1 Random Access Table: 
        Implement the FasterTable class that supports the following operations...       
        1.rows() returns the number of rows in the Table (constant time)        
        2.cols() returns the number of columns in the Table (constant time)        
        3.get(i,j) return the item at row i and column j in the Table (constant time)        
        4.set(i,j,x) set the item at row i and column j to x in the Table and return the value previously stored there (constant time)   
        5.addRow(i) insert a new row at index i. This creates cols() new entries in the Table, 
          which are all initialized to null. This causes the indices of rows i,…,rows()-1 to increase by 1. 
          (O(cols() + rows()-i) time)
        6.removeRow(i) remove row i. This causes the indices of rows i+1,…,rows()-1 to decrease by 1. (O(cols() + rows()-i) time)
        7.addCol(i) inserts a new column at index i. This creates rows() new entries in the Table, which are all initialized to null. 
          This causes the indices of columns i,…,cols()-1 to increase by 1. (O(rows() + cols()-i) time)
        8.removeCol(i) removes column i. This causes the indices of columns i+1,…,cols()-1 to decrease by 1. (O(rows() + cols()-i) time)

Part 2 A Fast Default List:
  Starting with the SkipListList class, implement a FastDefaultList class that represents an infinite list with indices 0,1,2,3,…,∞ 
  When we start, every value in this list is assigned the default value null. Otherwise, this class behaves just like a List; 
  it has the add(i,x), remove(i), set(i,x), and get(i) that behave just like the same methods in a list. 
  Each of these operations should run in O(log n) time. The size() method is already implemented for you, 
  it returns the largest value you can store in an int
       


Files:
  A2Table.java(Skeleton code not uploaded)
  DumbDefaultList.java(Skeleton code not uploaded)
  FastDefaultList.java(Skeleton code not uploaded)
  FasterTable.java
  Table.java(Skeleton code not uploaded)
  Tester.java(Skeleton code not uploaded)

Other: README
