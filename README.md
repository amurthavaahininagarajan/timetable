# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag
### STEP 2
Add header row using th tag
### STEP 3
Add your timetable
### STEP 4
Execute the program

# CODE
```python
<!DOCTYPE html>
<html lang="en">
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/images/logo.jpg" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - AMURTHA VAAHINI KN (22009070)</b></caption>
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
<td colspan="3">FREE SLOT</td>
<td>FREE SLOT</td>
<td>SS</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>FWAD</td>
<td> MATHS</td>
<td>LAL</td>
<td>EDM</td>
<td>PYTHON</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td > FREE SLOT </td>
<td>FWAD</td>
<td>FWAD</td>
<td>E.MECH</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td colspan="2"> FREE SLOT </td>
<td>E.MECH</td>
<td>MATHS</td>
<td>EDM</td>
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
<td align="center">19AI301</td>
<td>Python Program(PYTHON)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19MA220</td>
<td>Maths for AI(MATHS)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19MA221</td>
<td>Linear Algebra Lab(LAL)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19AI302</td>
<td>Engineering Design And Modelling(EDM)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19AI303</td>
<td>Engineering Mechanics And Product Development</td>
</tr>
<tr>

<td align="center">7.</td>
<td align="center">19EY701</td>
<td>Soft Skills (SS)</td>
</tr>
</table>
</body>
</html>
```

# OUPUT
![](out.png)

# HTML VALIDATION
![](valid.png)

# RESULT
The program for creating slot time table is completed sucessfully.
