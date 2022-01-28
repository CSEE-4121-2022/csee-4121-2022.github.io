---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home
menu: main
---

CSEE4121 - Computer Systems for Data Science 
{: style="color:black; font-size: 190%; font-weight:700; text-align: center; padding-top: 15px;"}
Spring '22, Columbia University
{: style="color:black; font-size: 130%; text-align: center; padding-bottom: 30px;"}
----

## Course Overview
Data scientists and engineers increasingly have access to a powerful and broad range of systems
they use to conduct big data analysis and machine learning at scale: from databases, large-scale
analytics to distributed machine learning frameworks. \\
\\
The goal of this class is to provide data scientists and engineers that work with big data a better
understanding of the foundations of how the systems they will be using are built. It will also
give them a better understanding of the real-world performance, availability and scalability
challenges when using and deploying these systems at scale. In the course we will cover
foundational ideas in designing these systems, while focusing on specific popular systems that
students are likely to encounter at work or when doing research. The class will include some
written homework and programming assignments. One of the programming assignments will be
done in pairs, and the rest will be done individually.
In this course we will answer the following questions:
<ul>
  <li>How are popular big data systems designed and architected?</li>
  <li>How to think about performance, scale and reliability of big data systems?</li>
  <li>How do they remain available and not lose data despite frequent server and
hardware failures?</li>
  <li>How to reason about issues like security, privacy and data quality when
conducting analysis on large data sets?</li>
</ul>
{: .text-justify}

## Instructors
 Asaf Cidon and Sambit Sahu\\
OH: By appointment only

## Location and Time
Asaf Cidon - Fridays 10:10 AM - 12:40 PM | 417 International Affairs Building \\
Sambit Sahu - Thursdays 7:00 PM - 9:30 PM | 402 Chandler

## TAs
<table>
  <tr>
    <td>Rahul Chaudhari</td>
    <td>Shantanu Jain</td>
  </tr>
  <tr>
    <td>Wei Hao</td>
    <td>Koushik Roy</td>
  </tr>
  <tr>
    <td>Aashish Arora</td>
    <td>Manisha Rajkumar</td>
  </tr>
  <tr>
    <td>Harshitha Malireddi</td>
    <td>Ruchika Goel</td>
  </tr>
  <tr>
    <td>Joy Parikh</td>
    <td>Suvansh Dutta</td>
  </tr>
  <tr>
    <td>Sai Karthik Ammanamanchi</td>
    <td>Zhejian Jin</td>
  </tr>
    <tr>
    <td>Gaurav Sinha</td>
  </tr>
</table> 

## Piazza
TBD

## Prerequisites
Students are expected to have solid programming experience in Python or with an equivalent programming language. This class is intended to be accessible for data scientists who do not necessarily have a background in databases, operating systems or distributed systems.

## Syllabus
<a href="https://www.dropbox.com/s/aukg1i77k75dz3n/Syllabus%20for%20Computer%20Systems%20for%20Data%20Science.pdf?dl=0">Syllabus Link</a>

## Schedule (this is a work in progress, and is likely to change)
<table>
<colgroup>
<col width="33%" />
<col width="45%" />
<col width="22%" />
</colgroup>
<thead>
<tr class="header">
<th>Week</th>
<th>Topic</th>
<th>Homework</th>
</tr>
</thead>
<tbody>
<tr>
<td markdown="span">1</td>
<td markdown="span">Introduction (<a href="https://www.dropbox.com/s/evzk4lv8hh9sxt5/Topic%201%20-%20intro%20and%20rules%20of%20thumb.pdf?dl=0">Slides</a>)</td>
<th></th>
</tr>
<tr>
<td markdown="span">2</td>
<td markdown="span">Relational Data Model (<a href="https://www.dropbox.com/s/z1vvm34hhwq1csj/Topic%202%20-%20relational%20model.pdf?dl=0">Slides</a>)</td>
<th markdown="1">Programming Homework 1 released</th>
</tr>
<tr>
<td markdown="span">3</td>
<td markdown="span">Relational Data Model</td>
<th></th>
</tr>
<tr>
<td markdown="span">4</td>
<td markdown="span">Transactions and Logging</td>
<th markdown="1">Written Homework 1 released</th>
</tr>
<tr>
<td markdown="span">5</td>
<td markdown="span">Storage/memory hierarchy and key value stores</td>
<th markdown="1">Programming Homework 1 due</th>
</tr>
<tr>
<td markdown="span">6</td>
<td markdown="span"> Distributed databases and file systems</td>
<th markdown="1">Written Homework 1 due</th>
</tr>
<tr>
<td markdown="span">7</td>
<td markdown="span">Midterm (all material up to, not including distributed databases)</td>
<th></th>
</tr>
<tr>
<td markdown="span">8</td>
<td markdown="span">Challenges in scaling</td>
<th markdown="1">Programming Homework 2 released</th>
</tr>
<tr>
<td markdown="span">9</td>
<td markdown="span">Spring Break</td>
<th></th>
</tr>
<tr>
<td markdown="span">10</td>
<td markdown="span">MapReduce and stragglers</td>
<th></th>
</tr>
<tr>
<td markdown="span">11</td>
<td markdown="span">Spark and distributed analytics</td>
<th></th>
</tr>
<tr>
<td markdown="span">12</td>
<td markdown="span">Caching</td>
<th markdown="1">Programming Homework 2 due, Written Homework 2 out</th>
</tr>
<tr>
<td markdown="span">13</td>
<td markdown="span">Security and privacy</td>
<th></th>
</tr>
<tr>
<td markdown="span">14</td>
<td markdown="span">Data quality</td>
<th></th>
</tr>
<tr>
<td markdown="span">15</td>
<td markdown="span">Review</td>
<th markdown="1">Written Homework 2 due</th>
</tr>
<tr>
<td markdown="span">16</td>
<td markdown="span">Final Exam</td>
<th></th>
</tr>
</tbody>
</table>

## Grade Breakdown
20% Programming Homework 1 \\
10% Written Homework 1 \\
20% Programming Homework 2 \\
10% Written Homework 2 \\
15% Midterm \\
25% Final

## Late Submission Policy
Each student will have a total of 3 late days for the entire semester. After all late days are used, there will be a 5% penalty for submission within 24 hrs of the deadline, 10% penalty for submission within 48hrs of the deadline and 20% penalty for submission within 72 hrs of the deadline. No submissions will be accepted after 72 hrs from the deadline.

## Collaboration/Copying Policy
Programming assignment 1 and the written assignments will be done alone. Programming assignment 2 will be done in pairs. You may not copy answers and code. We will enforce this policy when checking the assignments (we use a code similarity system).

## Course Materials
No textbook.
