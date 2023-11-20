### ***Date*** : 4-6 November 2023
### ***Title*** : LAB16
### ***Aim*** : Trees
### ***Algorithm*** :

1. Node Insertion Algorithm:

Objective: Add a new number to the tree while maintaining the order.

Steps:

If the tree is empty, create a new node with the given number and make it the root.
If the number is smaller than the current node's number, go to the left subtree and repeat step 1.
If the number is larger, go to the right subtree and repeat step 1.
Return the modified tree.

2. Tree Traversal Algorithms:

a. Inorder Traversal:

Objective: Visit all nodes in ascending order.

Steps:

Go to the left subtree and repeat the process.
Visit the current node.
Go to the right subtree and repeat the process.

b. Preorder Traversal:

Objective: Visit the current node before its children.

Steps:

Visit the current node.
Go to the left subtree and repeat the process.
Go to the right subtree and repeat the process.

c. Postorder Traversal:

Objective: Visit the current node after its children.

Steps:

Go to the left subtree and repeat the process.
Go to the right subtree and repeat the process.
Visit the current node.

3. Node Deletion Algorithm:

Objective: Remove a number from the tree.

Steps:

If the tree is empty, do nothing.
If the number is smaller than the current node's number, go to the left subtree and repeat the process.
If the number is larger, go to the right subtree and repeat the process.

If the number is found:

a. If the node has no children (leaf node), delete it.
b. If the node has one child, replace it with its child.
c. If the node has two children, find the smallest node in the right subtree, replace the current node's data with it, and repeat the process for the right subtree.

4. Menu-Driven Interface:

Objective: Provide a user-friendly way to interact with the tree operations.

Steps:

Display a menu with options to insert, traverse, delete, or exit.
Based on the user's choice:
Insert a number into the tree.
Display the tree using different traversal methods.
Delete a node from the tree.
Exit the program.

This menu-driven interface allows users to perform various operations on the Binary Search Tree interactively.

### ***Explanation*** :

1. Node Insertion:
   
What it does: Imagine you have a list of numbers. This algorithm helps you add a new number to the list in a way that keeps the numbers in order.

How it works:

If the list is empty, just put the new number there.
If the new number is smaller than the current number, put it to the left.
If the new number is larger, put it to the right.
Keep doing this until you find the right spot for the new number.

2. Tree Traversal:
   
What it does: It helps you go through the list of numbers in a specific order.

a. Inorder Traversal:

How it works:

First, look at all the smaller numbers on the left.
Then, look at the current number.
Finally, look at all the larger numbers on the right.

b. Preorder Traversal:

How it works:

First, look at the current number.
Then, look at all the smaller numbers on the left.
Finally, look at all the larger numbers on the right.

c. Postorder Traversal:

How it works:

First, look at all the smaller numbers on the left.
Then, look at all the larger numbers on the right.
Finally, look at the current number.

3. Node Deletion:
   
What it does: If you want to remove a number from the list, this algorithm helps you do it properly.

How it works:

If the number isn't in the list, do nothing.
If the number is smaller, look on the left.
If the number is larger, look on the right.
If you find the number:
If it has no kids (it's alone), just remove it.
If it has one kid, replace it with the kid.
If it has two kids, find the smallest number on the right, swap it with the current number, and then go and remove that number on the right.

4. Menu-Driven Interface:
   
What it does: It's like a menu in a restaurant, but for your list of numbers. You can choose what you want to do with the list.

How it works:

It shows you a menu with options like add a number, look at the list in different ways, remove a number, or leave.
Depending on what you choose:
Add a number to the list.
Look at the list in order, or starting from the top, or starting from the bottom.
Remove a number from the list.
If you're done, leave the restaurant (or the program in this case).

### ***Output Screenshot*** :

Code:

https://github.com/anikethmehta/LAB15/blob/main/code1.png

https://github.com/anikethmehta/LAB15/blob/main/code2.png

https://github.com/anikethmehta/LAB15/blob/main/code3.png

https://github.com/anikethmehta/LAB15/blob/main/code4.png

https://github.com/anikethmehta/LAB15/blob/main/code5.png

https://github.com/anikethmehta/LAB15/blob/main/code6.png

https://github.com/anikethmehta/LAB15/blob/main/code7.png

https://github.com/anikethmehta/LAB15/blob/main/code8.png

https://github.com/anikethmehta/LAB15/blob/main/code9.png

Output:

https://github.com/anikethmehta/LAB15/blob/main/output1.png

https://github.com/anikethmehta/LAB15/blob/main/output2.png

https://github.com/anikethmehta/LAB15/blob/main/output3.png

https://github.com/anikethmehta/LAB15/blob/main/output4.png

https://github.com/anikethmehta/LAB15/blob/main/output5.png

