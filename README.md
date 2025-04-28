# Ex03 Time Table
## Date:

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
    <img src="logo.png" height="150" width="900">
    <table border="2" cellspacing="2" cellpading ="2">
    <caption>SLOT TIMETABLE - JEYAPRIYA.J 24004150 </caption> 
    <tr bgcolor="blue">
        <th>day</th>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
        <th>Saturday</th>
    </tr>
    <tr>
        <td> 8 to 10 </td>
        <td>Communicative english</td>
        <td>Data structure</td>
        <td>Data structure</td>
        <td>Fundamentals of web application development</td>
        <td>free slot</td>
        <td>free slot</td>
    </tr>
    <tr>
        <td> 10 to 12</td>
        <td>Fundamentals of c programming</td>
        <td>German language A2</td>
        <td>German language A2</td>
        <td>Engineerin mechanics and product development</td>
        <td>Engineering mechanics and product development </td>
        <td>Fundamentals of web application development</td>
    </tr>
    <tr>
        <td> 12 to 1</td>
        <td colspan="6">lunch</td>
    </tr>
    <tr>
        <td> 1 to 3</td>
        <td>Basic electric,electronics and measurement engineering</td>
        <td>career development skills</td>
        <td>Mentor MEET</td>
        <td>Communicative english </td>
        <td>Fundamentals of c programming</td>
        <td>Principles of chemistry in engineering</td>

    </tr>
    <tr>
        <td> 3 to 5</td>
        <td>Principles of chemistry in engineering</td>
        <td>German language A2</td>
        <td>Basic electrical,electronics and measurement engineering</td>
        <td>free slot</td>
        <td>free slot</td>
        <td>free slot</td>
</table>
<br>
<table border="2" cellspacing="2" cellpadding="6">
    <tr>
        <th>S.NO</th>
        <th>COURSE CODE</th>
        <th>COURSE NAME</th>
    </tr>
    <tr>
        <td>01</td>
        <td>19Al414</td>
        <td>Fundamentals of web application development</td>
    </tr>
    <tr>
        <td>02</td>
        <td>19Al304</td>
        <td>Fundamentals of c programming</td>
    </tr>
    <tr>
        <td>03</td>
        <td>19EN101</td>
        <td>Communicative english</td>
    </tr>
    <tr>
        <td>04</td>
        <td>19AI408</td>
        <td>Data structure</td>
    </tr>
    <tr>
        <td>05</td>
        <td>19TD606</td>
        <td>German language A2</td>
    </tr>
    <tr>
        <td>06</td>
        <td>19AI303</td>
        <td>Engineering mechanics and product development</td>
    </tr>
    <tr>
        <td>07</td>
        <td>19EE305</td>
        <td>Basic electrical,electronics and measurement engineering</td>
    </tr>
    <tr>
        <td>08</td>
        <td>19EY708</td>
        <td>Career development skills</td>
    </tr>
    <tr>
        <td>09</td>
        <td>SH7101</td>
        <td>Principles of chemistry in engineering</td>
    </tr>

</table>

</html>
```
## OUTPUT

![Screenshot 2025-04-28 222051](https://github.com/user-attachments/assets/f14e645d-dbf2-43fd-819a-4bf908b5d6c3)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
