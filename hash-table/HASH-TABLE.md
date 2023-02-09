<p align="right">
<kbd>
<a href="https://github.com/Sid-WC121/DSA" >Main</a><br>
</kbd>
</p>
<h1 align="center"> Hash Table</h1>
<br>

<p> A hash table is a data structure used to implement an associative array, a structure that can map keys to values.In a hash table, data is stored in an array format where each data has a unique index value.Accessing the data becomes very fast if we knows the index.The efficiency of the mapping depends on the efficiency of the hash function used.<p>
  
- #### Hashing <em>is the process of creating a fixed size output from input of variable size using mathematical formulas known as hash function.</em> 
- #### It works by taking in a key and using a hash function to calculate an index in an array at which the corresponding value is stored.

  
> #### Note:
> <em>It is the data structure that satisfies the demand for a data structure that can perform atleast the search/retrieval operation in constant time complexity <b>O</b>(1)</em>
<p align="center">
<img src="/hash-table/hash-table.png" style="height: 250px; width:600px;"/>
</p>


##  :sparkle: Applications of Hashing
1.  - Database Indexing
2.  - Caching: Hashing is used in cache memory to quickly look up data based on its key.
3.  - Password Storage: Hashing is used to securely store passwords by turning a password into a fixed-length hash value that can be compared for authentication purposes, without having to store the original password.
<p align="right">etc...</p>

***
> Index Mapping (also known as Trivial Hashing) is a simple form of hashing where the data is directly mapped to an index in a hash table. The hash function used in this method is typically the identity function, which maps the input data to itself. In this case, the key of the data is used as the index in the hash table, and the value is stored at that index.
***
<h3><em>Example:-</em></h3>

#### Keys: 36,18,72,43,6
<p> H(k) = k % 8  (i.e, range from 0 to 7)</p>
<p align="center">
<img src="/hash-table/example1.jpg" style="height: 300px; width:350px;"/>
</p>

***

## :sparkle:Collision
*A collision in a hash table occurs when two different keys produce the same index (hash value) in the array. This means that the same bucket in the array is being used to store different key-value pairs, which can lead to ambiguity and incorrect behavior.*

## :sparkle:Collisions Handling Techniques:
1. Direct Addressing (open addressing)
2. Seperate Chaining (chaining)

<h3> :one: Direct Addressing (open addressing)</h3>

>This method involves searching for the next available bucket in the array if the original index is already occupied. There are several variations of open addressing, including linear probing, quadratic probing, and double hashing.

1. **`Linear probing` :-** _In this method, the next available bucket is found by incrementing the index until an empty bucket is found. This can result in clusters of occupied buckets, which can reduce the overall performance of the hash table._
2. **`Quadratic probing` :-** _In this method, the next available bucket is found by incrementing the index using a quadratic function, such as i^2, where i is the number of probes. This method helps to avoid the clustering issue seen in linear probing._
3. **`Double hashing` :-** _In this method, a secondary hash function is used to determine the next index to probe. This method helps to ensure that keys are distributed uniformly across the indices of the array, reducing the likelihood of collisions._

<h3> :two: Seperate Chaining (chaining)</h3>

> This method involves creating a linked list at each index in the array, so that multiple key-value pairs can be stored in the same bucket. When a collision occurs, the new key-value pair is simply added to the end of the linked list at that index.

<p align="center">
<kbd>
<a href="https://github.com/Sid-WC121/DSA" >Main</a><br>
</kbd>
</p>
