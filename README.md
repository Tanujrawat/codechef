# codechef
solutions

Problem Statement:
Euron loves to arrange things in order. Euron sticks to his “Golden rule” that every set of numbers must be in ascending order.  Unfortunately, that is not always the case. Euron defines a “violation” as a situation when a smaller number comes after a larger number in the set, which violates the ascending order.
Given a set of integers, Euron needs to find out the total number of such violations.

Input:
The first line contains n, the number of integers.
The second line contains n space separated integers a0 … an-1

Output:
The output is an integer indicating the total number of violations. 

Constraints:
0 < n <= 105
0 < ai < 108

Example  :
Input:
5
4 5 6 7 1

Output :
4
Explanation :
4, 5, 6 and 7 are in order.
1 comes after 4, 5, 6, 7 on the list, but is smaller than all 4 of them. Hence 4 is the answer.

Input :
5
5 4 3 2 1
Output :
10

