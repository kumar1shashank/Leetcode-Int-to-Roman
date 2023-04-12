Leetcode-Int-to-Roman
Problem Statement
Roman numerals are represented by seven different symbols: I, V, X, L, C, D, and M.


<h1>Leetcode-Int-to-Roman</h1>

<h2>Problem Statement</h2>
<p>Roman numerals are represented by seven different symbols: I, V, X, L, C, D, and M.</p>

<table>
  <tr>
    <th>Symbol</th>
    <th>Value</th>
  </tr>
  <tr>
    <td>I</td>
    <td>1</td>
  </tr>
  <tr>
    <td>V</td>
    <td>5</td>
  </tr>
  <tr>
    <td>X</td>
    <td>10</td>
  </tr>
  <tr>
    <td>L</td>
    <td>50</td>
  </tr>
  <tr>
    <td>C</td>
    <td>100</td>
  </tr>
  <tr>
    <td>D</td>
    <td>500</td>
  </tr>
  <tr>
    <td>M</td>
    <td>1000</td>
  </tr>
</table>

<p>For example, 2 is written as II in Roman numerals, which is simply two ones added together. 12 is written as XII, which is simply X + II. The number 27 is written as XXVII, which is XX + V + II.</p>

<p>Roman numerals are usually written from left to right in descending order of value, with the largest symbols placed before the smaller symbols. However, there are some special cases where a smaller symbol is placed before a larger symbol to represent subtraction. These cases are:</p>

<ul>
  <li>I can be placed before V (5) and X (10) to make 4 and 9.</li>
  <li>X can be placed before L (50) and C (100) to make 40 and 90.</li>
  <li>C can be placed before D (500) and M (1000) to make 400 and 900.</li>
</ul>

<p>Given an integer, convert it to a Roman numeral.</p>

<h2>Example</h2>

<p>Input: num = 3<br>
Output: "III"<br>
Explanation: 3 is represented as 3 ones.</p>

<p>Input: num = 58<br>
Output: "LVIII"<br>
Explanation: L = 50, V = 5, III = 3.</p>

<p>Input: num = 1994<br>
Output: "MCMXCIV"<br>
Explanation: M = 1000, CM = 900, XC = 90, and IV = 4.</p>

<h2>Constraints</h2>

<p>1 &lt;= num &lt;= 3999</p>


