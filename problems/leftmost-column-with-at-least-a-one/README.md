<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../perform-string-shifts "Perform String Shifts")
　　　　　　　　　　　　　　　　
[Next >](../first-unique-number "First Unique Number")

## [1428. Leftmost Column with at Least a One (Medium)](https://leetcode.com/problems/leftmost-column-with-at-least-a-one "")



### Related Topics
  [[Array](../../tag/array/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
1. (Binary Search) For each row do a binary search to find the leftmost one on that row and update the answer.
</details>

<details>
<summary>Hint 2</summary>
2. (Optimal Approach) Imagine there is a pointer p(x, y) starting from top right corner. p can only move left or down. If the value at p is 0, move down. If the value at p is 1, move left. Try to figure out the correctness and time complexity of this algorithm.
</details>
