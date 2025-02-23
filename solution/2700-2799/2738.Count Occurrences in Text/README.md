# [2738. Count Occurrences in Text](https://leetcode.cn/problems/count-occurrences-in-text)

[English Version](/solution/2700-2799/2738.Count%20Occurrences%20in%20Text/README_EN.md)

## 题目描述

<!-- 这里写题目描述 -->

<p>Table:<font face="monospace"> <code>Files</code></font></p>

<pre>
+-------------+---------+
| Column Name | Type    |
+-- ----------+---------+
| file_name   | varchar |
| content     | text    |
+-------------+---------+
file_name is the primary key of this table. 
Each row contains file_name and the content of that file.
</pre>

<p>Write an SQL query to find&nbsp;the number of occurrences of the words&nbsp;<strong>&#39;bull&#39;</strong> and <strong>&#39;bear&#39;</strong> as a <strong>standalone word</strong>, disregarding any instances where it appears as part of another word (e.g. &#39;bullet&#39; and &#39;bears&#39; will <strong>not</strong> be considered).</p>

<p>Return <em>the word &#39;bull&#39; and &#39;bear&#39; along with the corresponding number of occurrences in <strong>any order.</strong></em></p>

<p>The query result format is in the following example.</p>

<p>&nbsp;</p>
<p><strong class="example">Example 1:</strong></p>

<pre>
<strong>Input:</strong>&nbsp;
Files table:
+------------+----------------------------------------------------------------------------------+
| file_name  | contenet                                                                         | 
+------------+----------------------------------------------------------------------------------+
| draft1.txt | The stock exchange predicts a bull market which would make many investors happy. | 
| draft2.txt | The stock exchange predicts a bull market which would make many investors happy, |
|&nbsp;           | but analysts warn of possibility of too much optimism and that in fact we are    |
|&nbsp;           | awaiting a bear market.                                                          | 
| draft3.txt | The stock exchange predicts a bull market which would make many investors happy, |
|&nbsp;           | but analysts warn of possibility of too much optimism and that in fact we are    |
|&nbsp;           | awaiting a bear market. As always predicting the future market is an uncertain   |
|            | game and all investors should follow their instincts and best practices.         | 
+------------+----------------------------------------------------------------------------------+
<strong>Output:</strong>&nbsp;
+------+-------+
| word | count | &nbsp;
+------+-------+
| bull |&nbsp;3     |&nbsp;
| bear |&nbsp;2     | 
+------+-------+
<strong>Explanation:</strong>&nbsp;
- The word &quot;bull&quot; appears 1 time in &quot;draft1.txt&quot;, 1 time in &quot;draft2.txt&quot;, and 1 time in &quot;draft3.txt&quot;. Therefore, the total number of occurrences for the word &quot;bull&quot; is 3.
- The word &quot;bear&quot; appears 1 time in &quot;draft2.txt&quot;, and 1 time in &quot;draft3.txt&quot;. Therefore, the total number of occurrences for the word &quot;bear&quot; is 2.

</pre>

## 解法

<!-- 这里可写通用的实现逻辑 -->

<!-- tabs:start -->

### **SQL**

<!-- 这里可写当前语言的特殊实现逻辑 -->

```sql

```

<!-- tabs:end -->
