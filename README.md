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
<head>
    <title>Course Schedule</title>
</head>
<body>
    <img src="logo.jpg" height="100" width="540" alt="Logo">
    <br>
    <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
        <caption><b>SCHEDULE OF ALL COURSES</b></caption>
        <tr align="center">
            <th bgcolor="yellow">Day/Time</th>
            <th bgcolor="yellow">Monday</th>
            <th bgcolor="yellow">Tuesday</th>
            <th bgcolor="yellow">Wednesday</th>
            <th bgcolor="yellow">Thursday</th>
            <th bgcolor="yellow">Friday</th>
        </tr>
        <tr align="center">
            <th bgcolor="yellow">8-10</th>
            <td>C PROGRAMMING</td>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>PHYSICS</td>
            <td>NUMERICAL METHODS</td>
            <td>ADVANCED C PROGRAMMING</td>
        </tr>
        <tr align="center">
            <th bgcolor="yellow">10-12</th>
            <td>FREE SLOT</td>
            <td>FUNDAMENTALS OF WEB</td>
            <td>PRINCIPLES OF CHEMISTRY</td>
            <td>FREE SLOT</td>
            <td>NUMERICAL METHODS</td>
        </tr>
        <tr align="center">
            <th bgcolor="yellow">12-1</th>
            <td colspan="5">LUNCH</td>
        </tr>
        <tr align="center">
            <th bgcolor="yellow">1-3</th>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>COMMUNICATIVE ENGLISH</td>
            <td>FUNDAMENTALS OF WEB</td>
            <td>SOFT SKILLS</td>
        </tr>
        <tr align="center">
            <th bgcolor="yellow">3-5</th>
            <td>NUMERICAL METHODS</td>
            <td>FREE SLOT</td>
            <td>FUNDAMENTALS OF WEB</td>
            <td>PHYSICS</td>
            <td>PRINCIPLES OF CHEMISTRY</td>
        </tr>
    </table>
    <br>
    <table align="center" cellspacing="2" cellpadding="4" border="2">
        <tr align="center">
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr align="center">
            <td>1.</td>
            <td>19AI414</td>
            <td>FUNDAMENTALS OF WEB (FWAD)</td>
        </tr>
        <tr align="center">
            <td>2.</td>
            <td>19AI304</td>
            <td>C PROGRAMMING (C PROGRAM)</td>
        </tr>
        <tr align="center">
            <td>3.</td>
            <td>19PH325</td>
            <td>PHYSICS (PHY)</td>
        </tr>
        <tr align="center">
            <td>4.</td>
            <td>19CY205</td>
            <td>PRINCIPLES OF CHEMISTRY (CHE)</td>
        </tr>
        <tr align="center">
            <td>5.</td>
            <td>19MA211</td>
            <td>NUMERICAL METHODS (MAT)</td>
        </tr>
        <tr align="center">
            <td>6.</td>
            <td>19EY701</td>
            <td>SOFT SKILLS (SS)</td>
        </tr>
    </table>
</body>
</html>
```



## OUTPUT

![image](https://github.com/user-attachments/assets/605e99e6-b939-46f3-a8e6-1cecd22f43b2)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
