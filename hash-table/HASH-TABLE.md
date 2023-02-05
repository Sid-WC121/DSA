<h1 align="center"> Hash Table</h1>
<br>

<p> A hash table is a data structure used to implement an associative array, a structure that can map keys to values.In a hash table, data is stored in an array format where each data has a unique index value.Accessing the data becomes very fast if we knows the index.The efficiency of the mapping depends on the efficiency of the hash function used.<p>
  
- #### Hashing <em>is the process of creating a fixed size output from input of variable size using mathematical formulas known as hash function.</em> 
- #### It works by taking in a key and using a hash function to calculate an index in an array at which the corresponding value is stored.

  
> #### Note:
> <em>It is the data structure that satisfies the demand for a data structure that can perform atleast the search/retrieval operation in constant time complexity <b>O</b>(1)</em>
<p align="center">
<img src="/hash-table/hash-table.png" alt="Undirected graph" style="height: 250px; width:600px;"/>
</p>


##  :sparkle: Applications of Hashing
1.  - Database Indexing
2.  - Caching: Hashing is used in cache memory to quickly look up data based on its key.
3.  - Password Storage: Hashing is used to securely store passwords by turning a password into a fixed-length hash value that can be compared for authentication purposes, without having to store the original password.
<p align="right">etc...</p>

***
<h3><em>Example:-</em></h3>

#### Keys: 36,18,72,43,6
<p> H(k) = k % 8  (i.e, range from 0 to 7)</p>
<p align="center">
<img src="/hash-table/example1.jpg" alt="Undirected graph" style="height: 300px; width:350px;"/>
</p>

***

## :sparkle: Techniques:
1. Direct Addressing (open addressing)
2. Seperate Chaining (chaining)
