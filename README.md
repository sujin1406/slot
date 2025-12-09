# Ex03 Time Table
## Date:11-12-2025

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
        <title>TIME TABLE</title>
    </head>
    <body>
        <center>
            <img src="/static/sec-logo-01as-2048x412.png" height="100" width="540">
        </center>
        <br>
        <table align="center" width="750" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
            <caption><b>SLOT TIME TABLE - SUJIN M L (25014892)</b></caption>
            <tr align="center">
                <th bgcolor="yellow">Day/Time</th>
                <th bgcolor="yellow">MONDAY</th>
                <th bgcolor="yellow">TUESDAY</th>
                <th bgcolor="yellow">WEDNESDAY</th>
                <th bgcolor="yellow">THURSDAY</th>
                <th bgcolor="yellow">FRIDAY</th>
                <th bgcolor="yellow">SATURDAY</th>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">8-10</th>
                <td>NULL</td>
                <td>WEB</td>
                <td>WEB</td>
                <td>C(LANG)</td>
                <td>C(LANG)</td>
                <td>NULL</td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">10-12</th>
                <td>ENG</td>
                <td>Null</td>
                <td>C(LANG)</td>
                <td>WEB</td>
                <td>ENG</td>
                <td>ENG</td>
            </tr>
            <tr>
                <th bgcolor="yellow">12-1</th>
                <td colspan="6" align="center">LUNCH</td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">1-3</th>
                <td>WEB</td>
                <td>NULL</td>
                <td>MENTOR</td>
                <td>NULL</td>
                <td>C(LANG)</td>
                <td>ENG</td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">3-5</th>
                <td>C(LANG)</td>
                <td>WEB</td>
                <td>NULL</td>
                <td>NULL</td>
                <td>NULL</td>
                <td>NULL</td>
            </tr>
        </table>
        <br>
        <table align="center" width="750" border="5" cellspacing="2" cellpadding="4" >
            <tr align="center">
                <th>S.NO></th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</th>
            </tr>
            <tr align="center">
                <td>1</td>
                <td>19AI304</td>
                <td align="left">Fundamentals Of C Programming</td>
            </tr>
            <tr align="center">
                <td>2</td>
                <td>19AI414</td>
                <td align="left">Fundamentals Of Web Application Development</td>
            </tr>
            <tr align="center">
                <td>3</td>
                <td>19EN101</td>
                <td align="left">Communicative English</td>
            </tr>
            <tr align="center">
                <td>4</td>
                <td>ECA-M</td>
                <td align="left">Mentor Meet</td>
            </tr>
        </table>

    </body>
</html>
```

## OUTPUT
<img width="1099" height="729" alt="Screenshot 2025-12-10 011142" src="https://github.com/user-attachments/assets/96bec3e4-0857-4649-b4cb-1d57a6f59eb0" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
