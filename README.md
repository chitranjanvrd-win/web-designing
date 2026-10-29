# web-designing
#practical 1



<!DOCTYPE html>
<html>
<head>
    <title>Course Curriculum</title>
</head>
<body>
    <h1 align="center">Course Curriculum</h1>
    <h3 align="center"><u>Department of Computer Science</u></h3>
    <h2>Introduction</h2>
    <p>
        Welcome to the <b>course curriculum</b>. This page demonstrate
        the use of HTML and specialcharacter such as copyright
        &copy;, &lt;, &gt;.
    </p>

 <h3>semester 1 subjects(ordered lists)</h3>
    <ol type="A">
        <li>Mathematics</li>
        <li>computer fundamentals</li>
        <li>programming in c++</li>
        <li>Electronics basics</li>
    </ol>

 <h2>Programming languages(unordered lists)</h2>
    <ul type="square">
        <li>Python</li>
        <li>Java</li>
        <li>C++</li>
        <li>JavaScript</li>
    </ul>

 <h2>Course description(description lists)</h2>
    <dl>
        <dt>C programming</dt>
        <dd>Learning the basics of c language
            loops,arrays,and function.</dd>
        <dt>Java</dt>
        <dd>Introduction to object-oriented programming concepts.</dd>
    </dl>

 <h2>Course Module(nested lists)</h2>
    <ol>
        <li>Module 1:basics
            <ul>
                <li>Introduction</li>
                <li>History of computers</li>
            </ul>
        </li>
        <li>Module 2:programming
            <ul>
                <li>C programming</li>
                <li>Java programming</li>
            </ul>
        </li>
    </ol>

 <h2>Project work</h2>
    <ul type="circle">
        <li>Web development
            <ol>
                <li>HTML</li>
                <li>CSS</li>
                <li>JavaScript</li>
            </ol>
        </li>
        <li>Data base
            <ol>
                <li>mySQL</li>
                <li>MongoDB</li>
            </ol>
        </li>
    </ul>
</body>
</html>


#practical3

<!DOCTYPE html>
<html>
<head>
    <title>College Timetable</title>
    <style>
        table {
        border-collapse: collapse;
            width: 100%;
     }
     th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: center;
        }
    </style>
</head>
<body>
<table>
    <caption><b>College Timetable - CSE Department</b></caption>

 <tr>
        <th>Day / Time</th>
        <th>9:00 - 10:00</th>
        <th>10:00 - 11:00</th>
        <th>11:00 - 12:00</th>
        <th>12:00 - 1:00</th>
        <th>1:00 - 2:00</th>
        <th>2:00 - 3:00</th>
        <th>3:00 - 4:00</th>
    </tr>

 <tr>
        <th>Monday</th>
        <td rowspan="2">Mathematics</td>
        <td>English</td>
        <td rowspan="3">Physics</td>
        <td>Break</td>
        <td colspan="2">Computer Lab</td>
        <td>Sports</td>
    </tr>

 <tr>
        <th>Tuesday</th>
        <td>C Programming</td>
        <td>Break</td>
        <td colspan="2">Electronics Lab</td>
        <td>Library</td>
    </tr>

<tr>
        <th>Wednesday</th>
        <td>Mathematics</td>
        <td>English</td>
        <td>Break</td>
        <td>Computer Networks</td>
        <td colspan="2">
            <table>
                <tr><th colspan="2">Lab Details</th></tr>
                <tr><td>Batch A</td><td>DBMS Lab</td></tr>
                <tr><td>Batch B</td><td>OS Lab</td></tr>
            </table>
        </td>
    </tr>

<tr>
        <th>Thursday</th>
        <td colspan="2">Workshop</td>
        <td>Physics</td>
        <td>Break</td>
        <td>Mathematics</td>
        <td>English</td>
        <td>Seminar</td>
    </tr>

 <tr>
        <th>Friday</th>
        <td>Computer Networks</td>
        <td>English</td>
        <td>Physics</td>
        <td>Break</td>
        <td colspan="3">Project Work</td>
    </tr>
</table>

</body>
</html>
