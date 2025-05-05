# cs336-homework-3-solved
**TO GET THIS SOLUTION VISIT:** [CS336 Homework 3 Solved](https://www.ankitcodinghub.com/product/cs336-homework-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98800&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS336 Homework 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Given the following tables:

<ul>
<li>􏰓 &nbsp;students(sid,name,age,gpa)</li>
<li>􏰓 &nbsp;courses(cid,deptid, name)</li>
<li>􏰓 &nbsp;professors(ssn,name,address,phone,deptid)</li>
<li>􏰓 &nbsp;enrollment(sid,cid,section,grade,

foreign key (sid) references students, foreign key (cid) references courses,

foreign key (cid,section) references teaches)</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
􏰓 teaches(cid,section

foreign key (cid) references courses, foreign key (ssn) references professors)

Domain

<ul>
<li>􏰓 &nbsp;cid is in {’198:11’,’640:151’,’198:112’,…}</li>
<li>􏰓 &nbsp;deptid is in {’cs’,’math’,’music’,…}</li>
<li>􏰓 &nbsp;grade is in {’A’,’B’,’C’,…}</li>
<li>􏰓 &nbsp;section, age, ssn are an integers</li>
<li>􏰓 &nbsp;address, phone, name are strings</li>
<li>􏰓 &nbsp;gpa is float
Provide SQL instructions for each of the following questions
</li>
</ul>
<ol>
<li>Create the database schema.</li>
<li>Find the name of professors that work for the cs department.</li>
<li>Find those students (sid) enrolled in courses in the cs department.</li>
<li>List ssn and name of professors that work for the cs department, but are not teaching any cs courses.</li>
<li>List the number of courses offered by each department. Just the number of courses (not sections).</li>
<li>List of those departments that offer more than 10 courses.</li>
<li>Produce a list of the name of those students whose professor’s name starts with an M. Your result must have no duplicates.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
,ssn,

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ol start="8">
<li>Assume that small sections have less than 30 students, medium sections have at least 30 students but less than 80, and large sections have at least 80 students.
Your result table should have the following rows and columns:

Each table entry must have the number of sections of a given size offered by each department.
</li>
<li>List of professors that work for departments with more than 20 faculty members and that offer more large sections than small and medium sections combined.</li>
<li>Assume grades are A, B, C, D, F where D and F are failing grades. For each course (section) find the percentage of students that failed the course.</li>
<li>Find the name of the professor with the maximum percentage of students that failed his course.</li>
<li>On average what percentage of students fail a course? (total number of students that failed a course / total number of enrolled students).</li>
<li>Find a list of courses (sections) where the percentage of students with D or F is greater than average.</li>
<li>Write a query that produces the following table:
Where SPS is the average number of students in each section and column %A has the per- centage of students that got an A, and so on, over all the courses offered by each department.
</li>
</ol>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
deptid

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
small

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
medium

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
large

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
cs

</div>
</div>
</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
math

</div>
</div>
</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
deptid

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
SPS

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
%A

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
%B

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
%C

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
%D

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
%F

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
cs

</div>
</div>
</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
math

</div>
</div>
</td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
<td></td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
…

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
