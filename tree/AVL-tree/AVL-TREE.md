<p align="right">
<kbd>
<a href="https://github.com/Sid-WC121/DSA" >Main</a><br>
</kbd>
<kbd>
<a href="https://github.com/Sid-WC121/DSA/blob/main/heap/HEAP.md" >next (heap)</a>
</kbd>
</p>
<h1 align="center"> AVL Tree</h1>
<br>
<p>An AVL tree is quite similar to a binary search tree, but with an additional property that ensures the height of the tree remains balanced. In an AVL tree, the difference in height between the left and right subtrees of any node can be at most 1. This helps to ensure that the tree remains balanced, even after multiple insertions and deletions.</p>
<p>When a node is inserted or deleted in an AVL tree, the tree may become unbalanced. To restore balance, the AVL tree uses rotations, a process that rearranges the nodes of the tree. There are two types of rotations in AVL trees: single rotations and double rotations. Single rotations are used to correct a difference in height of two subtrees that is greater than 1, while double rotations are used to correct a difference in height of two subtrees that is equal to 2.</p>
<p>The advantage of using an AVL tree over a standard binary search tree is that it provides faster search, insertion, and deletion times, since the height of the tree remains relatively small even with many nodes. The time complexity for operations in an AVL tree is O(log n), where n is the number of nodes in the tree.</p>
