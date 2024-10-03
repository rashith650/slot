# Ex03 Time Table
## Date:03-10-2024

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
<html>
</style>
</head>
<body>
    <center>
        <img src="C:\Users\admin\Desktop\new html\Screenshot 2024-10-03 171846.png" width="800px">
        <h1 style="color:red;font-family:'Times New Roman', Times, serif;" > SLOT TIMETABLE ODD 2024-2025(24001082)</h1>
        <table border="1" cellpadding="10" bgcolor="yellow" >
            <TR style="color:red" bgcolor="violet">
                <TH>DAYS</TH><TH>8-10</TH><TH>10-12</TH><th>12-1</th><TH>1-3</TH><TH>3-5</TH>
            </TR>
            <tr>
                <td style="color:red" bgcolor="violet">MONDAY</td><td>   -</td><td style="color: blueviolet;">Fundamentals of c programming</td><td rowspan="6" bgcolor="violet">LUNCH BREAK</td><td rowspan="2">-</td><td style="color:chocolate">Web Application</td>
            </tr>
            <tr>
                <td style="color:red" bgcolor="violet">TUESDAY</td><td  style="color:crimson;">Python and Linear Algebra</td><td>Introduction to Data science</td><td style="color:forestgreen;">python and linear Algebra</td>
            </tr>
            <tr>
                <td style="color:red" bgcolor="violet">WEDNESDAY</td><td style="color:violet;">Fundamentals of c programming</td><td style="color:cornflowerblue;">Introduction to data science</td><td>Mentor Meet</td><td style="color:crimson;">python and linear Algebra</td>
            </tr>
            <tr>
                <td style="color:red" bgcolor="violet">THURSDAY</td><td rowspan="2">-</td><td  style="color:chocolate">Web Application</td><td style="color:forestgreen;"></td><td>-</td>
            </tr>
            <tr>
                <td style="color:red" bgcolor="violet">FRIDAY</td><td>-</td><td style="color:violet;"></td><td style="color: blueviolet;">Career development</td>
            </tr>
            <tr>
                <td style="color:red" bgcolor="violet">SATURDAY</td><td  style="color:chocolate">Web Application</td><td style="color:cornflowerblue;"></td><td>Python and linear Algebra</td><td style="color: teal;"></td>
            </tr>
            
        </center>
    </table>
    <table border="1">
        <tr style="color:red">
            <th>S.no</th><th>SUBJECT CODE</th><th>SUBJECT NAME</th>
        </tr>
        <tr>
            <td style="color:red">1.</td><td>19AI414</td><td>Fundamentals of web application development</td>
        </tr>
        <tr>
            <td style="color:red">2.</td><td>19AI301C</td><td>Python and Linear Algebra</td>
        </tr>
        <tr>
            <td style="color:red">3.</td><td>19AI403</td><td>Introduction to Data science</td>
        </tr>
        <tr>
            <td style="color:red">4.</td><td>19AI304</td><td>Fundamentals OF C programming</td>
        </tr>
        <tr>
            <td style="color:red">5.</td><td>19EY708</td><td>CAREER development SKILLS</td>
        </tr>
        <tr>
            <td style="color:red">8.</td><td>ECA-M</td><td>Mentor Meet</td>
        </tr>


    </table>
    
</body>
</html>

# OUTPUT
![Screenshot 2024-10-03 173314](https://github.com/user-attachments/assets/185fef7a-ce3b-4fad-89cb-31bf1c895d36)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.

