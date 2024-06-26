# Ex03 Time Table
## Date:3.4.2024

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
~~~
<!DOCTYPE html>
<html lang="en">
<head>
<title>SLOT TIMETABLE</title>
</head>
<body>
<center>
<img src="logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="lavender">
<caption><b>SLOT TIME TABLE DIVYA R V (23014030)</b></caption>
<tr align="center">
<th bgcolor="emarald">Day/Time</th>
<th bgcolor="emarald">Monday</th> 
<th bgcolor="emarald">Tuesday</th>
<th bgcolor="emarald">Wednesday</th>
<th bgcolor="emarald">Thursday</th>
<th bgcolor="emarald">Friday</th>
<th bgcolor="emarald">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="orange">8-10</th>
<td >DIGITAL ELECTRONICS</td>
<td>FREE SLOT</td>
<td>BEEE</td> 
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="orange">10-12</th> 
<td>SOFTWARE ENGINEERING</td>
<td>FUNDAMENTALS OF C PROGRAMMING </td>
<td>SOFTWARE ENGINEERING</td>
<td>FUNDAMENTALS OF C PROGRAMMING </td>
<td>CREATIVE SKILLS</td>
<td>OPERATING SYSTEM</td>
</tr>
<tr align="center">
    <th bgcolor="orange">1-3</th> 
    
    <td>BEEE</td>
    <td>FREE SLOT</td>
    <td>STATISTICS</td>
    <td>FREE SLOT</td>
    <td>FREE SLOT</td>
    <td>STATISTICS</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
    <tr align="center">
        <th>S. No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
        </tr>
        <tr>
        <td align="center">1.</td>
        <td align="center">19AI414</td>
        <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
        <td align="center">2.</td>
        <td align="center">19AI304</td>
        <td>Fundamentals Of C Programming</td>
        </tr>
        <tr>
        <td align="center">3.</td>
        <td align="center">19MA211</td>
        <td>Statistics</td>
        </tr>
        <tr>
        <td align="center">4.</td>
        <td align="center">19EE404</td>
        <td>Digital electronics</td>
        </tr>
        <tr>
        <td align="center">5.</td>
        <td align="center">19CS408</td>
        <td>Software Engineering</td>      
    
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EE305</td>
<td>BEEE</td>
</tr>
<tr>
    <td align="center">7.</td>
    <td align="center">19CS405</td>
    <td>Operating System</td>
    </tr>
    <tr>
         <td align="center">8.</td>
        <td align="center">19EY702</td>
        <td>Creative skills</td>
        </tr>
</table>
</body>
</html>
~~~

## OUTPUT
![alt text](<Screenshot 2024-04-04 090709.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
