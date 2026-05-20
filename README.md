# Ex02 Time Table
# Name:- V.B.Laksha
# Reg.No:- 212224220051
# Date: 20/5/2026
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
    <style>
    img 
    {
        width: 500px;
        height: auto;
    }
    </style>
    <center>
        <img src="https://saveetha.ac.in/wp-content/uploads/2024/03/sec-logo-01as.png">
    </center>
    <head>
        <title>Time Table </title>
        <style>
            table,th,td
            {
                text-align: center;
                border: 3px ;
            }
        </style>
    </head>
    <body>
        <center>
            <h2 style="text-align: center;"> TIME TABLE - V.B.LAKSHA</h2>
            <table style="background-color:aqua">
                <th>DAYS</th>
                <th>8-10</th>
                <th>10-12</th>
                <th>12-1</th>
                <th>1-3</th>
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color:aqua">MONDAY</th>
                <td> Cloud computing</td>
                <td> Python Programming</td>
                <td rowspan="6"> L<br>U<br>N<br>C<br>H<br></td>
                <td> Free Slot</td>
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color: aqua">TUESDAY</th>
                <td>Fundamentals of Web Application Development</td>
                <td>Cloud computing</td>
                <td>Python programming</td>
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color: aqua">WEDNESDAY</th>
                <td>Fundamentals of Web Application Development</td>
                <td>Python programming</td>
                <td>Mentor Meet</td>
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color: aqua">THURSDAY</th>
                <td>Cloud Computing</td>
                <td>Python Programming</td>
                <td>Free Slot</td>
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color: aqua">FRIDAY</th>
                <td>Fundamentals of Web Application Development</td>
                <td> Free Slot</td>
                <td>Cloud Computing</td>
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color: aqua">SATURDAY</th>
                <td>Fundamentals of Web Application Development</td>
                <td> Free Slot</td>
                
                <td> Free SLot</td>
            </tr>
        </table>
        </center>
    </body>
</html>
 <br>
 <br>
 <center>
    <table bgcolor="Black">
        <tr bgcolor="plum">
            <th>S.no</th>
            <th>SUBJECT CODE</th>
            <th>SUBJECT NAME</th>
        </tr>
        <tr>
<td bgcolor="plum">1.</td>
            <td bgcolor="plum">19AI414</td>
            <td bgcolor="plum">Fundamentals of Web Application Development</td>
        </tr>
        <tr>
            <td bgcolor="plum">2.</td>
            <td bgcolor="plum">19AI301</td>
            <td bgcolor="plum">Python programming</td>
        </tr>
        <tr>
        <td bgcolor='plum'>3.</td>
            <td bgcolor="plum">19AI541</td>
            <td bgcolor="plum">Cloud Computing</td>
        </tr>
    </table>
</center>
```
# OUTPUT
<img width="1919" height="1089" alt="Screenshot 2026-05-20 084457" src="https://github.com/user-attachments/assets/ce1fca12-4984-4b93-8dad-de411f835745" />

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
