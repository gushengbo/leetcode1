# leetcode1
一、字符串
1.翻转字符串里的单词
解法：使用两个指针索引，索引单词的第一个词跟最后一个词的下一个空格。只需要N时间复杂度的循环遍历
![image](https://github.com/gushengbo/leetcode1/assets/122679046/53e7df3f-c916-458f-86c0-dbc751797842)

2.最长回文子串
解法：回文子串分为奇数跟偶数。因为奇数可以一次遍历，遍历的每个数作为中间数，向两边拓展，若遇到不是回文字符串，可以立即停止。不浪费时间。偶数也是同样的道理，可以将遍历到的数定为索引是string.size()/2的值。向两边拓展。
![image](https://github.com/gushengbo/leetcode1/assets/122679046/3d5b0403-27c3-44a0-a2c8-ee571e12b3f4)

