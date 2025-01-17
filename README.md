# Ex03 Time Table
## Date: 20/11/2024

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
<title>Slot Timetable</title> 
</head> 
<body> 
<center> 
<img src="logo.png" width="548">
</center> 
<br> 
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan"> 
<caption><b>SLOT TIME TABLE - VISWAJITH LALITHRAM R.V (24000985)</b></caption> 
<tr align="center"> 
<th bgcolor="yellow">Day/Time</th> 
<th bgcolor="yellow">Monday</th> 
<th bgcolor="yellow">Tuesday</th> 
<th bgcolor="yellow">Wednesday</th> 
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th> 
<th bgcolor="yellow">Saturday</th>
</tr> 
<tr align="center"> 
<th bgcolor="yellow">8-10</th> 
<td>                   </td> 
<td>                   </td> 
<td>DIGITAL ELECTRONICS</td> 
<td>                   </td> 
<td>                   </td>
<td>      STATISTICS   </td>
</tr> 
<tr align="center"> 
<th bgcolor="yellow">10-12</th> 
<td> WEB APPLICATION DEVELOPMENT</td> 
<td>        STATISTICS          </td> 
<td> WEB APPLICATION DEVELOPMENT</td> 
<td>                            </td> 
<td>      QUANTUM COMPUTING     </td>
<td>      C PROGRAMMING         </td> 
</tr> 
<tr> 
<th bgcolor="yellow">12-1</th>
<td colspan="6" align="center">LUNCH</td> 
</tr> 
<tr align="center"> 
<th bgcolor="yellow">1-3</th> 
<td>                            </td> 
<td>    DIGITAL ELECTRONICS     </td> 
<td>    MENTOR MEET             </td> 
<td>                            </td> 
<td>    C PROGRAMMING           </td> 
<td> WEB APPLICATION DEVELOPMENT</td>
</tr> 
</table> 






<center>
<table class="SUBJECT-TABLE" border="4" cellpadding="4" bgcolor="white">
    <tr>
        <th>S. No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
    </tr>
    <tr>
        <td>1.</td>
        <td>19A1414</td>
        <td>Fundamentals of Web Application Development (FWAD)</td>
    </tr>
    <tr>
        <td>2.</td>
        <td>19AI304</td>
        <td>Fundamentals of C programming (FCP)</td>
    </tr>
    <tr>
        <td>3.</td>
        <td>19EE404</td>
        <td>Digital Electronics (DE)</td>
    </tr>
    <tr>
        <td>4.</td>
        <td>ECA-M-SCOFT</td>
        <td>Mentor Meet</td>
    </tr>
    <tr>
        <td>5.</td>
        <td>19MA211</td>
        <td>Statitics  and Numerical Methods (SNM)</td>
    </tr>
    <tr>
        <td>6.</td>
        <td>SH3214</td>
        <td>Physics for Quantum Computing (PQC)</td>
    </tr>
</table>
</center>



</body>
</html>


```

## OUTPUT


![alt text](<Screenshot (15).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
