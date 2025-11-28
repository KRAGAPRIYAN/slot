# Ex02 Time Table
## Date:25/11/2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```

slot.html

<html>
    <head>
        <title>Sample Page</title>
    </head>
    <body align="center">
        <img src="logo.png" width="750" height="150" title="SEC Logo">
        <br></br>
        <table border="6" cellspacing="1" align="center" width="750" height="200" bgcolor="cyan">
            <caption><b>SLOT TIME TABLE - K RAGAPRIYAN (25014706)</b></caption>
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
                <td>FREE SLOT</td>
                <td>PYTH</td>
                <td colspan="2">FREE SLOT</td>
                <td>FWAD</td>
                <td>FREE SLOT</td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">10-12</th>
                <td>FREE SLOT</td>
                <td>COM.ENG</td>
                <td>PYTH</td>
                <td>COM.ENG</td>
                <td colspan="2">FWAD</td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">12-1</th>
                <td align="center" colspan="6">L U N C H</td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">1-3</th>
                <td colspan="2">FWAD</td>
                <td>MENTOR</td>
                <td>COM.ENG</td>
                <td colspan="2">FREE SLOT</td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">3-5</th>
                <td>FREE SLOT</td>
                <td colspan="2">PYTH</td>
                <td>FREE SLOT</td>
                <td>PYTH</td>
                <td>COM.ENG</td>
            </tr>
        </table>
        <br></br>
        <table align="center" width="750" cellspacing="3" cellpadding="5" border="1" bgcolor="lightgreen">
        <caption><b>SUBJECTS</b></caption>
            <tr>
                <th>S.No</th>
                <th>Subject Code:</th>
                <th>Subject Name:</th>
            </tr>
            <tr align="center">
                <td>1</td>
                <td>19AI414</td>
                <td>Fundementals of Web Application Development(FWAD)</td>
            </tr>
            <tr align="center">
                <td>2</td>
                <td>19AI301</td>
                <td>Python Programming(PYTH)</td>
            </tr>
            <tr align="center">
                <td>3</td>
                <td>19EN101</td>
                <td>Communicative English(COM.ENG)</td>
            </tr>
        </table>
        </table>
    </body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2025-11-28 195529-2.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
