# algorithmicThinking15probs
These are probing questions to 15 medium difficulty problems from Leetcode

All Clarifying and probing questions will be saved in this README file.  I will also describe how I would use the I.D.E.A.L. Problem-solving approach and Duke's 7-step approach to answer each question.

### Q2. Add Two Numbers
url: https://leetcode.com/problems/add-two-numbers/
> You are given two non-empty linked lists representing two non-negative integers. The digits are stored in reverse order and each of their nodes contain a single digit. Add the two numbers and return it as a linked list.
>
> You may assume the two numbers do not contain any leading zero, except the number 0 itself.
>
> Example:
>
> Input: (2 -> 4 -> 3) + (5 -> 6 -> 4)
> Output: 7 -> 0 -> 8
> Explanation: 342 + 465 = 807.
#### How to use IDEAL & Duke's
I would first draw out a few examples, drawing nodes and then using my fingers to point to active nodes.  This would help with the 1-4 parts of IDEAL.  

#### Clarifying questions:
* Is the linked list doubly linked?
* Will the linked lists be of the same size?
* Should the answer also be in reverse order?
#### Probing questions:
* How should we deal with leading zeros?
* Should we do calculations in place? To reduce memory usage.
* How should we handle overflows? Like is there a limit to the number of nodes in the answer?

### Q542. 01 Matrix
url: https://leetcode.com/problems/01-matrix/
>Given a matrix consists of 0 and 1, find the distance of the nearest 0 for each cell.
>
>The distance between two adjacent cells is 1.
>Example 1: 
>Input:
>    {{0 0 0},
>     {0 1 0},
>     {0 0 0}}
> Output:
>    {{0 0 0},
>     {0 1 0},
>     {0 0 0}}

### Q456. 132 Pattern
url: https://leetcode.com/problems/132-pattern/
>Given a sequence of n integers a1, a2, ..., an, a 132 pattern is a subsequence ai, aj, ak such that i < j < k and ai < ak < aj. Design >an algorithm that takes a list of n numbers as input and checks whether there is a 132 pattern in the list.
>
>Note: n will be less than 15,000.
>
>Example 1:
>Input: [1, 2, 3, 4]
>
>Output: False
>
>Explanation: There is no 132 pattern in the sequence.
#### How to use IDEAL & Duke's
In the "Identify the problem" of IDEAL I would wannt to rephrase the question in plain english. So that I know what examples and what steps to take in Duke's approach.
#### Clarifying questions:
* I would want to first clearly define what is meant by "i", "j", "k" verses "ai", "aj", "ak"
* When we say "list" are we talking about a linked list?
* Is the linked list, singly- or doubly-linked?
#### Probing questions:
* What if we're given a sequence that is less than three integers?
* Would there be a situation of having negative numbers in the list?
* Why do they explicitly make a point of saying "n will be less than 15,000?

### Q650. 2 Keys Keyboard
url: https://leetcode.com/problems/2-keys-keyboard/
>Initially on a notepad only one character 'A' is present. You can perform two operations on this notepad for each step:
>Copy All: You can copy all the characters present on the notepad (partial copy is not allowed).
>Paste: You can paste the characters which are copied last time.
>Given a number n. You have to get exactly n 'A' on the notepad by performing the minimum number of steps permitted. Output the minimum
number of steps to get n 'A'.
>
>Example 1:
>Input: 3
>Output: 3
>
>Explanation:
>Intitally, we have one character 'A'.
>In step 1, we use Copy All operation.
>In step 2, we use Paste operation to get 'AA'.
>In step 3, we use Paste operation to get 'AAA'.
>
>Note:
>The n will be in the range [1, 1000].

### Q15. 3Sum
url: https://leetcode.com/problems/3sum/
>Given an array nums of n integers, are there elements a, b, c in nums such that a + b + c = 0? Find all unique triplets in the array which gives the sum of zero.
>
>Note:
>
>The solution set must not contain duplicate triplets.
>
>Example:
>
>Given array nums = [-1, 0, 1, 2, -1, -4],
>
>A solution set is:
>[
>  [-1, 0, 1],
>  [-1, -1, 2]
>]

### Q721. Accounts Merge
url: https://leetcode.com/problems/accounts-merge/
>Given a list accounts, each element accounts[i] is a list of strings, where the first element accounts[i][0] is a name, and the rest of the elements are emails representing emails of the account.
>
>Now, we would like to merge these accounts. Two accounts definitely belong to the same person if there is some email that is common to both accounts. Note that even if two accounts have the same name, they may belong to different people as people could have the same name. A person can have any number of accounts initially, but all of their accounts definitely have the same name.
>
>After merging the accounts, return the accounts in the following format: the first element of each account is the name, and the rest of the elements are emails in sorted order. The accounts themselves can be returned in any order.

### Q623. Add One Row to Tree
url: https://leetcode.com/problems/add-one-row-to-tree/
>Given the root of a binary tree, then value v and depth d, you need to add a row of nodes with value v at the given depth d. The root node is at depth 1.
>
>The adding rule is: given a positive integer depth d, for each NOT null tree nodes N in depth d-1, create two tree nodes with value v as N's left subtree root and right subtree root. And N's original left subtree should be the left subtree of the new left subtree root, its original right subtree should be the right subtree of the new right subtree root. If depth d is 1 that means there is no depth d-1 at all, then create a tree node with value v as the new root of the whole original tree, and the original tree is the new root's left subtree.

### Q797. All Paths From Source to Target
url: https://leetcode.com/problems/all-paths-from-source-to-target/
>Given a directed, acyclic graph of N nodes.  Find all possible paths from node 0 to node N-1, and return them in any order.
>
>The graph is given as follows:  the nodes are 0, 1, ..., graph.length - 1.  graph[i] is a list of all nodes j for which the edge (i, j) exists.

### Q870. Advantage Shuffle
url: https://leetcode.com/problems/advantage-shuffle/
>Given two arrays A and B of equal size, the advantage of A with respect to B is the number of indices i for which A[i] > B[i].
>
>Return any permutation of A that maximizes its advantage with respect to B.

### Q863. All Nodes Distance K in Binary Tree
url: https://leetcode.com/problems/all-nodes-distance-k-in-binary-tree/
>We are given a binary tree (with root node root), a target node, and an integer value K.
>
>Return a list of the values of all nodes that have a distance K from the target node.  The answer can be returned in any order.

### Q816. Ambiguous Coordinates
url: https://leetcode.com/problems/ambiguous-coordinates/
>We had some 2-dimensional coordinates, like "(1, 3)" or "(2, 0.5)".  Then, we removed all commas, decimal points, and spaces, and ended up with the string S.  Return a list of strings representing all possibilities for what our original coordinates could have been.
>
>Our original representation never had extraneous zeroes, so we never started with numbers like "00", "0.0", "0.00", "1.0", "001", "00.01", or any other number that can be represented with less digits.  Also, a decimal point within a number never occurs without at least one digit occuring before it, so we never started with numbers like ".1".
>
>The final answer list can be returned in any order.  Also note that all coordinates in the final answer have exactly one space between them (occurring after the comma.)

### Q227. Basic Calculator II
url: https://leetcode.com/problems/basic-calculator-ii/
>Implement a basic calculator to evaluate a simple expression string.
>
>The expression string contains only non-negative integers, +, -, *, / operators and empty spaces . The integer division should truncate toward zero.

### Q554. Brick Wall
url: https://leetcode.com/problems/brick-wall/
>There is a brick wall in front of you. The wall is rectangular and has several rows of bricks. The bricks have the same height but different width. You want to draw a vertical line from the top to the bottom and cross the least bricks.
>
>The brick wall is represented by a list of rows. Each row is a list of integers representing the width of each brick in this row from left to right.
>
>If your line go through the edge of a brick, then the brick is not considered as crossed. You need to find out how to draw the line to cross the least bricks and return the number of crossed bricks.
>
>**You cannot draw a line just along one of the two vertical edges of the wall, in which case the line will obviously cross no bricks.**

### Q739. Daily Temperatures
url: https://leetcode.com/problems/daily-temperatures/
>Given a list of daily temperatures T, return a list such that, for each day in the input, tells you how many days you would have to wait until a warmer temperature. If there is no future day for which this is possible, put 0 instead.
>
>For example, given the list of temperatures T = [73, 74, 75, 71, 69, 72, 76, 73], your output should be [1, 1, 4, 2, 1, 1, 0, 0].
>
>Note: The length of temperatures will be in the range [1, 30000]. Each temperature will be an integer in the range [30, 100].
