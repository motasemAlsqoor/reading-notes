# Trees

In computer science, a tree is a widely used abstract data type that simulates a hierarchical tree structure, with a root value and subtrees of children with a parent node, represented as a set of linked nodes. (1)

A tree data structure can be defined recursively as a collection of nodes (starting at a root node), where each node is a data structure consisting of a value, together with a list of references to nodes (the "children"), with the constraints that no reference is duplicated, and none points to the root.

## common terminology used in tree data structure

nodes : is a tree component that has it value and reference to other node

root : the first node in the tree 

leaf : node has not references : no children

left : the node reference to the direct left child

right : the node reference to the direct right child

edge : link between parent an child nodes

Height:  The height of a tree is the number of edges from the root to the furthest leaf

## Tree Traversal 

Tree traversal allow us to access the tree nodes .

there are tow types of tree traversal

1. Depth First

2. Breadth First

### Depth First

depth first means to look in the depth (height) at the biggining of the traversal

several methods to applay depth-first traversal

pre-order : root->left->right
in-order : left->root->right
post-order :left->right->root

the most common programming techniques for tree traversal is recursion 

means that we rely on the call stack to navigate back up the tree when we have reached the end of a sub-path .

### Breadth First 

Breadth first traversal iterates through the tree by going through each level of the tree node-by-node


