Download Link: https://assignmentchef.com/product/solved-eso207-data-structures-and-algorithms-programming-assignment-2
<br>






<strong>Question 1 </strong> <strong>Another minimum sum</strong>

<strong>Description:</strong>

Given an array <em>A </em>consisting of <em>N </em>elements, find the smallest sum of contiguous elements that is strictly greater than <em>K</em>.

<strong>Input:</strong>

First line will contain a single number <em>N</em>, denoting the number of elements in the array <em>A</em>.

Second line will contain the <em>N </em>elements of the array. Third line will contain the integer <em>K</em>.

<strong>Output:</strong>

Output a single integer <em>S</em>, the minimum sum of contiguous elements that is strictly greater than <em>K</em>. If no sum exists that is strictly greater <em>K</em>, then output −1.

<strong>Constraints:</strong>

1 ≤ <em>N </em>≤ 10<sup>5</sup>

− 10<sup>6 </sup>≤ <em>A</em>[<em>i</em>] ≤ 10<sup>6 </sup>1 ≤ <em>k </em>≤ 10<sup>6</sup>

<strong>Example:</strong>

<strong>Sample Input:</strong>

5

1      -5     3     -7     8

3

<strong>Sample Output: </strong>4

<strong>Explanation:</strong>

The contiguous sequence 3     -7       8 has the smallest sum strictly greater 3 i.e. 4.

Note: the sum of the sequence -5      3      -7 is -9 but its not strictly greater 3

<strong>Question 2</strong> <strong>Finding products</strong>

<strong>Description:</strong>

Given two sorted (in non decreasing order) arrays of positive integers <em>A </em>and <em>B </em>having sizes <em>M </em>and <em>N </em>respectively, and an integer <em>K</em>, find the <em>K</em>th smallest product <em>A</em>[<em>i</em>] · <em>B</em>[<em>j</em>], where 0 ≤ <em>i </em>≤ <em>M </em>− 1 and

<ul>

 <li>≤ <em>j </em>≤ <em>N </em>− 1.</li>

</ul>

<strong>Input:</strong>

First line contains two integers, <em>M </em>and <em>N</em>, denoting the sizes of the two arrays <em>A </em>and <em>B </em>respectively.

Next line contains <em>M </em>positive integers in non decreasing order, the elements of <em>A</em>

Next line contains <em>N </em>positive integers in non decreasing order, the elements of <em>B</em>

Last line contains the integer <em>K</em>

<strong>Output:</strong>

Output a single integer P that is the Kth smallest product <em>A</em>[<em>i</em>] · <em>B</em>[<em>j</em>]

<strong>Constraints:</strong>

<ul>

 <li>≤ <em>N,M </em>≤ 100000</li>

</ul>

1 ≤ <em>A</em>[<em>i</em>]<em>,B</em>[<em>i</em>] ≤ 10000

1 ≤ <em>k </em>≤ <em>N </em>∗ <em>M</em>

<strong>Example:</strong>

<strong>Sample Input:</strong>

3    4

<ul>

 <li>3 4</li>

 <li>4 6               8</li>

</ul>

5

<strong>Sample Output: </strong>8

<strong>Explanation:</strong>

The products <em>A</em>[<em>i</em>] · <em>B</em>[<em>j</em>] after sorting in non-decreasing order are as follows

2    4    6    6    8     8    12    16    18    24    24    32

The 5th smallest element in the above list is 8.

<strong>Question 3 </strong>(30 points) <strong>Greater to the left</strong>

<strong>Description:</strong>

Given an array <em>A </em>of <em>N </em>elements, Find for each element <em>A</em>[<em>i</em>], how many elements <em>A</em>[<em>j</em>] are greater than or equal to <em>A</em>[<em>i</em>] such that j<em>&lt;</em>i

<strong>Input:</strong>

First line contains an integer <em>N</em>, the number of elements in the array <em>A</em>. Second line contains <em>N </em>elements, the contents of the array <em>A</em>.

<strong>Output:</strong>

Print <em>N </em>elements, where the ith element represents the number of elements <em>A</em>[<em>j</em>] greater than or equal to <em>A</em>[<em>i</em>]

<strong>Constraints:</strong>

1 ≤ <em>N </em>≤ 500000 1 ≤ <em>A</em>[<em>i</em>] ≤ 100000

<strong>Example:</strong>

<strong>Sample Input:</strong>

4

5    4    2    5

<strong>Sample Output:</strong>

0 1 2 1

<strong>Explanation:</strong>

There are 0 elements ≥ 5 to its left

There is 1 element ≥ 4 to its left i.e 5

There are 2 elements ≥ 2 to its left i.e. 5 and 4

There is 1 element ≥ 5 to its left i.e. 5

<strong>Question 4 </strong><strong>Sonic and coins</strong>

<strong>Description:</strong>

Sonic is busy collecting coins. He is traveling through a binary search tree having <em>N </em>nodes, where every node in the tree has one coin. When he travels from the node <em>p </em>to <em>q </em>he will collect all the coins in the path from <em>p </em>to <em>q </em>(including the coins in the nodes <em>p </em>and <em>q</em>).

Given <em>K </em>queries, where each query will have two numbers, <em>p </em>and <em>q</em>. Print one number, denoting the total number of coins Sonic will collect when traveling from the node <em>p </em>to <em>q</em>.

<strong>Input:</strong>

First line will contain <em>N </em>and <em>K</em>, denoting the number of nodes in the tree and number of queries respectively.

Next line will contain <em>N </em>integers, denoting the pre-order traversal of the nodes of the tree (all <em>N </em>numbers will be unique).

Next <em>K </em>lines will denote two integers <em>p,q </em>each, denoting the start and end node of the path that sonic will travel.

<strong>Output:</strong>

Print <em>K </em>numbers, where each number represents the number of coins Sonic will collect.




<strong>Constraints:</strong>

1 ≤ <em>N </em>≤ 100000 1 ≤ <em>K </em>≤ 100000

<strong>Example:</strong>

<strong>Sample Input:</strong>

5      2

3      1    0     2     4

2      3

0      4

<strong>Sample Output:</strong>

3

4

<strong>Explanation:</strong>

<ul>

 <li>Sonic’s first run, collects 3 coins.</li>

</ul>




<ul>

 <li>Sonic’s second run, collects 4 coins.</li>

</ul>