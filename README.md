# Ex03 Time Table
## Date:23-04-2025

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
<!DOCTYPE html>
<html>
<head>
    <title>Timetable | 2024-2025 EVEN</title>
</head>
<body>
    <img src="logo.png"alt="" height="150" width = "600">
<h2>KISHORE S (24900831)</h2>

<table border="1" cellpadding="10">
    <tr bgcolor=yellow>
        <th>Time/Day</th>
        <th>Monday<br></th>
        <th>Tuesday<br></th>
        <th>Wednesday<br></th>
        <th>Thursday<br></th>
        <th>Friday<br></th>
        <th>Saturday<br></th>
    </tr>
    <tr>
        <td><strong>10am - 11am</strong></td>
        <td rowspan="2">Reasoning Ability (6683)</td>
        <td rowspan="2">Engineering Mechanics and Product Design</td>
        <td rowspan="2">Fundamentals of Web Application</td>
        <td rowspan="2">Advanced C Programming (6402)</td>
        <td rowspan="2">Advanced C Programming (2604)</td>
        <td rowspan="2">Programming Microcontrollers</td>
    </tr>
    <tr><td><strong>11am - 12pm</strong></td></tr>

    <tr>
        <td><strong>1pm - 2pm</strong></td>
        <td></td>
        <td rowspan="2">Probability and Queueing Models</td>
        <td rowspan="2">Mentor Meet (2871)</td>
        <td rowspan="2">Engineering Mechanics and Product Design</td>
        <td rowspan="2">Probability and Queueing Models</td>
        <td rowspan="2">Principles of Chemistry in Engineering</td>
    </tr>
    <tr><td><strong>2pm - 3pm</strong></td><td></td></tr>

    <tr>
        <td><strong>3pm - 4pm</strong></td>
        <td rowspan="2">Principles of Chemistry in Engineering</td>
        <td></td>
        <td rowspan="2">Programming Microcontrollers</td>
        <td></td>
        <td rowspan="2">Fundamentals of Web Application</td>
        <td></td>
    </tr>
    <tr><td><strong>4pm - 5pm</strong></td><td></td><td></td><td></td></tr>

</table>

</body>
</html>

<br>
    
    <table border="1">
    
    <tr>
        <th>S.No</th>
        <th>Course Code</th>
        <th>Course Name</th>
    </tr>
    <tr>
        <td>1</td>
        <td>19AI414</td>
        <td>Fundamentals of Web Application and Development[FWAD]</td>
    </tr>
    
    <tr>
        <td>2</td>
        <td>19AI304</td>
        <td>Fundamentals of C Programming[C Pro]</td>
    </tr>
    
    <tr>
        <td>3</td>
        <td>19EE404</td>
        <td>Digital Electronics[Digital Electronics]</td>
    </tr>
    
    <tr>
        <td>4</td>
        <td>SH3214</td>
        <td>Physics for Quantum Computing[Physics]</td>
    </tr>
    
    
    <tr>
        <td>5</td>
        <td>19EY708</td>
        <td>Career Development and Skills [CDS]</td>
    </tr>
    
    <tr>
        <td>6</td>
        <td>19MA211</td>
        <td>Statistics and Numerical Methods[Maths]</td>
    </tr>
    
    <tr>
        <td>7</td>
        <td>ECA-M-SCOFT</td>
        <td>Mentor Meet[Mentor]</td>
    </tr>
```


## OUTPUT
![image](https://github.com/user-attachments/assets/7f33ea6c-0d56-4d59-80f7-b9784f64f613)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
