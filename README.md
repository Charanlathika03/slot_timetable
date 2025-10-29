# Ex03 Time Table
## Date:29/10/25

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
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Time Table: M Charan lathika</title>
</head>
<body align="center" bgcolor="#E8F0FE">
  <img src="/static/logo.png" alt="Logo" width="650" height="100">

  <table border="3" align="center" bgcolor="#FFFFFF" cellpadding="10" cellspacing="0">
    <caption><font color="#1565C0" size="5"><b>Time Table - M Charan lathika</b></font></caption>
    <tr bgcolor="#1E88E5">
      <th><font color="white">Day/Time</font></th>
      <th><font color="white">8-10</font></th>
      <th><font color="white">10-12</font></th>
      <th><font color="white">1-3</font></th>
      <th><font color="white">3-5</font></th>
    </tr>
    <tr bgcolor="#BBDEFB">
      <th bgcolor="#90CAF9">Monday</th>
      <td>FREE SLOT</td>
      <td>GER</td>
      <td>FREE SLOT</td>
      <td>FREE SLOT</td>
    </tr>
    <tr bgcolor="#E3F2FD">
      <th bgcolor="#90CAF9">Tuesday</th>
      <td>GER</td>
      <td>FREE SLOT</td>
      <td>MAT</td>
      <td>FREE SLOT</td>
    </tr>
    <tr bgcolor="#BBDEFB">
      <th bgcolor="#90CAF9">Wednesday</th>
      <td>PHY</td>
      <td>FREE SLOT</td>
      <td>FWAD</td>
      <td>GER</td>
    </tr>
    <tr bgcolor="#E3F2FD">
      <th bgcolor="#90CAF9">Thursday</th>
      <td>PHY</td>
      <td>FWAD</td>
      <td>FWAD</td>
      <td>CHE</td>
    </tr>
    <tr bgcolor="#BBDEFB">
      <th bgcolor="#90CAF9">Friday</th>
      <td>CHE</td>
      <td>FWAD</td>
      <td>SS</td>
      <td>GER</td>
    </tr>
  </table>

  <br>

  <table border="3" align="center" bgcolor="#FFFFFF" cellpadding="10" cellspacing="0">
    <caption><font color="#1565C0" size="5"><b>Subject Codes</b></font></caption>
    <tr bgcolor="#1E88E5">
      <th><font color="white">S. No.</font></th>
      <th><font color="white">Subject Code</font></th>
      <th><font color="white">Subject Name</font></th>
    </tr>
    <tr bgcolor="#E3F2FD">
      <td>1</td>
      <td>19AI414</td>
      <td>Fundamentals of Web Application Development (FWAD)</td>
    </tr>
    <tr bgcolor="#BBDEFB">
      <td>2</td>
      <td>19EN612</td>
      <td>German Basic (GER)</td>
    </tr>
    <tr bgcolor="#E3F2FD">
      <td>3</td>
      <td>19PH206</td>
      <td>Physics for Information Technology (PHY)</td>
    </tr>
    <tr bgcolor="#BBDEFB">
      <td>4</td>
      <td>19CY205</td>
      <td>Principles of Chemistry in Engineering (CHE)</td>
    </tr>
    <tr bgcolor="#E3F2FD">
      <td>5</td>
      <td>19MA201</td>
      <td>Calculus and Matrix Algebra (MAT)</td>
    </tr>
    <tr bgcolor="#BBDEFB">
      <td>6</td>
      <td>19ET701</td>
      <td>Soft Skills (SS)</td>
    </tr>
  </table>
</body>
</html>
```

## OUTPUT
<img width="1919" height="1199" alt="Screenshot 2025-10-29 213742" src="https://github.com/user-attachments/assets/27a79e06-ecf8-4684-bc38-c6e93154f1ae" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
