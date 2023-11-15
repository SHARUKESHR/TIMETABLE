# Ex03 Time Table
## Date:30.10.2023

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
<title>SEC SLOT TIMETABLE</title>
<BODY>
	<IMG src="logo.png" 
	height="100" width="600" align="center" border="2">
</BODY>

<table>
    <table border="4" width="600" cellspacing='4' cellpaddling='4'>

<h1>SLOT TIMETABLE-SHARUKESH(23012910)</h1>
<tr>
    <th align="center" bgcolor="yellow">Day/Time</th>
    <th align="center" bgcolor="red">Monday</th>
    <th align="center" bgcolor="red">Tuesday</th>
    <th align="center" bgcolor="red">Wednesday</th>
    <th align="center" bgcolor="red">Thursday</th>
    <th align="center" bgcolor="red">Friday</th>
</tr>
<tr>
    
    <th align="center" bgcolor="yellow">8-10</th>
    <td align="center" bgcolor="cyan">ENG</td>
    <td align="center" bgcolor="cyan">ENG</td>
    <td align="center" bgcolor="cyan">FWAD</td>
    <td align="center" bgcolor="cyan">FCP</td>
    <td align="center" bgcolor="cyan">FREE SLOT</td>
   
</tr>

<tr>
    
    <th align="center" bgcolor="yellow">10-12</th>
    <td align="center" bgcolor="cyan">FREE SLOT</td>
    <td align="center" bgcolor="cyan">CHE</td>
    <td align="center" bgcolor="cyan">CA</td>
    <td align="center" bgcolor="cyan">FWAD</td>
    <td align="center" bgcolor="cyan">CA</td>
</tr>
<tr>
   
    <th align="center" bgcolor="yellow">1-3</th>
    <td align="center" bgcolor="cyan">CHE</td>
    <td align="center" bgcolor="cyan">FREE SLOT</td>
    <td align="center" bgcolor="cyan">FCP</td>
    <td align="center" bgcolor="cyan">FREE SLOT</td>
    <td align="center" bgcolor="cyan">FWAD</td>
</tr>

<tr>
    <th align="center" bgcolor="yellow">3-5</th>
    <td align="center" bgcolor="cyan">PHY</td>
    <td align="center" bgcolor="cyan">FREE SLOT</td>
    <td align="center" bgcolor="cyan">PLA</td>
    <td align="center" bgcolor="cyan" colspan="2">FREE SLOT</td>
</tr>
</table>

<table border="4" width="600" cellspacing='4' cellpaddling='4'>

<tr>
    <th align="center">S.NO</th>
    <th align="center">SUBJECT CODE</th> 
    <th align="center">SUBJECT NAME</th>
</tr>

<tr>
    <td align="center">1</td>
    <td align="center">19A1414</td>
    <td align="centre">Fundamentals of Web Application Devlopment(FWAD)</td>
</tr>

<tr>
    <td align="center">2</td>
    <td align="center">19EN612</td>
    <td align="centre">Communicative English(ENG)</td>
</tr>

<tr>
    <td align="center">3</td>
    <td align="center">19PH206</td>
    <td align="centre">Physics for Quatum Computing(PHY)</td>
</tr>

<tr>
    <td align="center">4</td> 
    <td align="center">19CY205</td>
    <td align="centre">Principles of Chemistry in Engineering(CHE)</td>
</tr>

<tr>
    <td align="center">5</td>
    <td align="center">19MA201</td>
    <td align="centre">Fundamentals of C Programming (FCP)</td>
</tr>

<tr>
    <td align="center">6</td>
    <td align="center">19EY701</td>
    <td align="center">soft skills(SS)</td>
</tr>

<tr>
    <td align="center">7</td>
    <td align="center">19CS305</td>
    <td align="center">Computer Architectue(CA)</td>
</tr>
</table>
```

## OUTPUT
![Screenshot 2023-11-15 091559](https://github.com/SHARUKESHR/TIMETABLE/assets/144870484/6b1bf427-f575-4044-a6b5-bb1e5be8015f)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
