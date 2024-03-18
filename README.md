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
```html
<html>
<head>
     <title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width"550">
</center>
<br>
     <table align="center" width="550" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
     <caption><b>Time Table - vinnushkumar ls (23012349)</b></caption>
<tr align="center">
	<th bgcolor="plum">Day/Time</th>
	<th bgcolor="plum">Monday</th>
	<th bgcolor="plum">Tuesday</th>
	<th bgcolor="plum">Wednesday</th>
	<th bgcolor="plum">Thursday</th>
 	<th bgcolor="plum">Friday</th>
        <th bgcolor="plum">Saturday</th>
</tr>
<tr align="center">
	<th bgcolor="plum">8-10</th>
	<td>digital eletronics</td>
	<td>chemistry</td>
	<td>web devlopment</td>
	<td>statistics</td>
        <td>free</td>
        <td>chemistry</td>
</tr>
<tr align="center">
	<th bgcolor="plum">10-12</th>
	<td>Free slot</td>
	<td>web devlopment</td>
	<td>creative skills</td>
	<td>Free slot</td>
	<td>C programming</td>
        <td>EMPD
</tr>
<tr>
	<th bgcolor="plum">12-1</th>
	<td colspan="6" align="center">L U N C H</td>
</tr>
<tr align="center">
	<th bgcolor="plum">1-3</th>
	<td>web devlopment</td>
	<td>free slot</td>
	<td>communicative english</td>
	<td>EMPD</td>
	<td>digitial eletronics</td>
        <td>statistics</td>
</tr>
<tr align="center">
	<th bgcolor="plum">3-5</th>
	<td>C programming</td>
	<td colspan="3">Free slot</td>
        <td>communicative english</td>
        <td>Free slot</td>
        </tr>
</table>
</br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI303</td>
<td>EMPD</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI414</td>
<td>FWAD</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CY205</td>
<td>Principles of chemistry in Engineering</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19EN101</td>
<td>Communicative English</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA211</td>
<td>statistics</td>
</tr>

<tr>
<td align="center">6.</td>
<td align="center">19EE404</td>
<td>digital eletronic</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19EY702</td>
<td>creative skill</td>
</tr>
<tr>
<td align="center">8.</td>
<td align="center">19AI304</td>
<td>C programming</td>
</tr>
</table>
</body>
</html>
```

## OUTPUT
![out](https://github.com/vinnush147/slot/assets/147139234/7ef0f981-db9b-4419-b442-0e84ad8a1e79)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
