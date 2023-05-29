Binary Tree Project, a Concise Overview:
----------------------------------------

Binary Tree: A binary tree is a hierarchical data structure in computer science
consisting of nodes, where each node has at most two children, referred to as
the left child and the right child. The binary tree is called "binary" because
each node can have a maximum of two children.

Binary Search Tree (BST): A binary search tree is a type of binary tree with an
additional property that makes it suitable for efficient searching. In a BST,
for any node, all the values in its left subtree are smaller than its value,
and all the values in its right subtree are greater than its value. This
property allows for fast searching, insertion, and deletion operations.

Time Complexity Gain compared to Linked Lists: Binary trees can provide
significant time complexity improvements over linked lists for certain operations.
Searching, insertion, and deletion operations in a balanced binary search tree
have an average time complexity of O(log n), where n is the number of nodes.
In contrast, linked lists have a time complexity of O(n) for the same operations.
Binary trees achieve this improvement by exploiting the hierarchical structure
and the binary search property.

Depth, Height, and Size of a Binary Tree:

Depth:
The depth of a node in a binary tree is the number of edges from the root node to
that particular node.
Height:
The height of a binary tree is the maximum depth among all the nodes in the tree.
It represents the length of the longest path from the root to any leaf node.
Size:
The size of a binary tree is the total number of nodes present in the tree.

Traversal Methods in Binary Trees:
Traversal refers to the process of visiting each node in a binary tree in a specific
order.
The commonly used traversal methods are:

Inorder traversal: Visit the left subtree, then the current node, and finally the right subtree.
Preorder traversal: Visit the current node, then the left subtree, and finally the right subtree.
Postorder traversal: Visit the left subtree, then the right subtree, and finally the current node.
Level-order traversal: Visit nodes at each level from left to right, starting from the root and
moving downwards.
Complete, Full, Perfect, and Balanced Binary Trees:

Complete Binary Tree:
A complete binary tree is a binary tree in which all levels, except possibly the last,
are completely filled, and all nodes are as left as possible. In the last level, the nodes are
filled from left to right.
Full Binary Tree:
A full binary tree is a binary tree in which every node has either zero or two children.
In other words, every node is either a leaf node or has two children.
Perfect Binary Tree:
A perfect binary tree is both complete and full. It is a binary tree in which all levels
are completely filled with the maximum possible number of nodes, except for the last level.
Balanced Binary Tree:
A balanced binary tree is a binary tree in which the heights of the left and right subtrees
of every node differ by at most one. It ensures that the tree remains balanced, leading to
improved performance for various operations.
