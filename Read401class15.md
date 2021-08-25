Trees
===
A tree is a hierarchical data structure defined as a collection of nodes. Nodes represent value and nodes are connected by edges. A tree has the following properties:

The tree has one node called root. The tree originates from this, and hence it does not have any parent.
Each node has one parent only but can have multiple children.
Each node is connected to its children via edge.

![](https://d1m75rqqgidzqn.cloudfront.net/wp-data/2020/10/06115257/image-9.png)

---

Types of Trees
===

`General Tree`: A tree in which there is no restriction on the number of children a node has, is called a General tree. Examples are Family tree, Folder Structure.

`Binary Tree`: In a Binary tree, every node can have at most 2 children, left and right.  In diagram below, B & D are left children and  C, E & F are right children.

`Full Binary Tree`: If every node in a tree has either 0 or 2 children, then the tree is called a full tree. The tree in the above diagram is not a full binary tree as node C has only the right child.
`Perfect Binary` tree: It is a binary tree in which all interior nodes have two children and all leaves have the same depth or same level.

`Balanced Tree`: If the height of the left and right subtree at any node differs at most by 1, then the tree is called a balanced tree.

`Binary Search Tree`: It is a binary tree with binary search property. Binary search property states that the value or key of the left node is less than its parent and value or key of right node is greater than its parent. And this is true for all nodes.

---

Depth First
===
Depth first traversal is where we prioritize going through the depth (height) of the tree first. There are multiple ways to carry out depth first traversal, and each method changes the order in which we search/print the root. Here are three methods for depth first traversal:

Pre-order: `root >> left >> right`
In-order: `left >> root >> right`
Post-order: `left >> right >> root`

---

![](ibrahem.png) 
#### **Ibarhem Al-omari**
> [GitHub](https://github.com/ibrahemomari)

>[LinkedIn](https://www.linkedin.com/in/ibrahem-omari-5967a5198/)

> Email: ibrahem.omari96@gmail.com