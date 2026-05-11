以下是图片中的文本内容：

Question

当前选择的编程语言是 Java。注意要提交完全正确的代码，而不是部分正确但有效的代码。提交后，便无法再检查该题。可以使用 System.out.println() 调试代码。出现语法/运行时错误时，System.out.println() 可能不起作用。使用的 JDK 版本是 Java 8

The University of Squareland has invited N alumni for a dinner. The dinner table is circular in shape. Each alumnus, assigned with an invitation ID from 1 to N, likes exactly one fellow alumnus and will attend the dinner only if seated next to the person he likes.

You are asked to plan this seating arrangement. Write an algorithm to find the maximum number of alumni who can attend the dinner.

Input
The first line of the input consists of an integer N, representing the number of alumni.
The second line consists of N space-separated integers representing the ID of the person whom the i^{th} alumnus likes.

Output
Print an integer representing the maximum number of alumni who can attend the dinner.

Note
One alumnus can be liked by more than one alumni.

Constraints
1 ≤ N ≤ 10^5
1 ≤ i ≤ N

Example
Input:
4
2 3 4 1

Output:
4

Explanation:
1st alumnus likes the person whose ID is 2
2nd likes the person whose ID is 3
3rd likes the person whose ID is 4
4th likes the person whose ID is 1
A maximum of 4 alumni can be seated around the circular table in the following manner:
1-2-3-4
