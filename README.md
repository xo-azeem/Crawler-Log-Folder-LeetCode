# Crawler Log Folder

LeetCode Q # 1598.

The Leetcode file system keeps a log each time some user performs a change folder operation.

The operations are described below:

- "../" : Move to the parent folder of the current folder. (If you are already in the main folder, remain in the same folder).</br>
- "./" : Remain in the same folder.</br>
- "x/" : Move to the child folder named x (This folder is guaranteed to always exist).</br>
You are given a list of strings logs where logs[i] is the operation performed by the user at the ith step.

The file system starts in the main folder, then the operations in logs are performed.

Return the minimum number of operations needed to go back to the main folder after the change folder operations.

Example 1:

<div align = "center">

  ![image](https://github.com/xo-azeem/Crawler-Log-Folder-LeetCode/assets/171427226/4eec8420-1fa7-40cc-b7c6-6198be518f97)

</div>

> Input: logs = ["d1/","d2/","../","d21/","./"]</br>
> Output: 2</br>
> Explanation: Use this change folder operation "../" 2 times and go back to the main folder.

Example 2:

<div align = "center">

  ![image](https://github.com/xo-azeem/Crawler-Log-Folder-LeetCode/assets/171427226/3e27c7ac-c065-4a54-9d5d-bbfdb8b86a3c)

</div>

> Input: logs = ["d1/","d2/","./","d3/","../","d31/"]</br>
> Output: 3

Example 3:

> Input: logs = ["d1/","../","../","../"]</br>
> Output: 0

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/xo-azeem/Crawler-Log-Folder-LeetCode/assets/171427226/bfa173a6-211c-41dd-a628-9d83c34ec8aa)

  Time complexity: O(n).</br>Space complexity: O(1).
</div>
