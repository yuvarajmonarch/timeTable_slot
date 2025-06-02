# Ex03 Time Table
## Date : 02-04-2024
## Name : YUVARAJ B
## Reg No : 212222040186

# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM

## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html>
<head>
    <title>Slot Timetable</title>
</head>
<body>
    <center>
        <img src="/static/logo.png.jpg" height="100" width="540">
    </center>
    <br>

    <table align="center" width="540" cellspacing="2" cellpadding="5" border="7" bgcolor="cyan">
        <caption><b>SLOT TIME TABLE - AASHIKA JAIN.G (212224110001)</b></caption>
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
            <td>PHY</td>
            <td>CHE</td>
        </tr>
        <tr align="center">
            <th bgcolor="yellow">10-12</th>
            <td>GER</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>FWAD</td>
            <td>PHY</td>
        </tr>
        <tr align="center">
            <th bgcolor="yellow">12-1</th>
            <td colspan="5" align="center">L U N C H</td>
        </tr>
        <tr align="center">
            <th bgcolor="yellow">1-3</th>
            <td colspan="2">FREE SLOT</td>
            <td>MAT</td>
            <td>MAT</td>
            <td>SS</td>
        </tr>
        <tr align="center">
            <th bgcolor="yellow">3-5</th>
            <td colspan="2">FREE SLOT</td>
            <td>GER</td>
            <td>CHE</td>
            <td>FWAD</td>
        </tr>
    </table>
    <br>

    <table align="center" cellspacing="3" cellpadding="4" border="2">
        <tr align="center">
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr align="center">
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr align="center">
            <td>2.</td>
            <td>19EN612</td>
            <td>German Basic (GER)</td>
        </tr>
        <tr align="center">
            <td>3.</td>
            <td>19PH206</td>
            <td>Physics for Information Technology (PHY)</td>
        </tr>
        <tr align="center">
            <td>4.</td>
            <td>19CY205</td>
            <td>Principles of Chemistry in Engineering (CHE)</td>
        </tr>
        <tr align="center">
            <td>5.</td>
            <td>19MA201</td>
            <td>Calculus and Matrix Algebra (MAT)</td>
        </tr>
        <tr align="center">
            <td>6.</td>
            <td>19EY701</td>
            <td>Soft Skills (SS)</td>
        </tr>
    </table>
</body>
</html>
```
# OUTPUT

![timetable](https://github.com/user-attachments/assets/7a49ec80-f368-434e-91e9-0a3d50278cd0)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
