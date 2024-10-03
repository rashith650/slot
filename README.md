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
    <head>
        <style>
            
        </style>
    </head>
    <body>
        <center>
            <img src="sec.png" width="800px">
            <h1 style="color:red;font-family:'Times New Roman', Times, serif;" > SLOT TIMETABLE ODD 2024-2025(212223040240)</h1>
            <table border="1" cellpadding="10" bgcolor="yellow" >
                <TR style="color:red" bgcolor="violet">
                    <TH>DAYS</TH><TH>8-10</TH><TH>10-12</TH><th>12-1</th><TH>1-3</TH><TH>3-5</TH>
                </TR>
                <tr>
                    <td style="color:red" bgcolor="violet">MONDAY</td><td>   -</td><td style="color: blueviolet;">Digital Electronics</td><td rowspan="6" bgcolor="violet">LUNCH BREAK</td><td rowspan="2">-</td><td style="color:chocolate">Web Application</td>
                </tr>
                <tr>
                    <td style="color:red" bgcolor="violet">TUESDAY</td><td  style="color:crimson;">software Eng</td><td>-</td><td style="color:forestgreen;">Alegebra n number theory</td>
                </tr>
                <tr>
                    <td style="color:red" bgcolor="violet">WEDNESDAY</td><td style="color:violet;">Comp networks</td><td style="color:cornflowerblue;">Theory of Computation</td><td>Mentor Meet</td><td style="color:crimson;">Software Eng</td>
                </tr>
                <tr>
                    <td style="color:red" bgcolor="violet">THURSDAY</td><td rowspan="2">-</td><td  style="color:chocolate">Web Application</td><td style="color:forestgreen;">Alegebra n number theory</td><td>-</td>
                </tr>
                <tr>
                    <td style="color:red" bgcolor="violet">FRIDAY</td><td>-</td><td style="color:violet;">Comp networks</td><td style="color: blueviolet;">DigitalElectronics</td><td>-</td>
                </tr>
                <tr>
                    <td style="color:red" bgcolor="violet">SATURDAY</td><td  style="color:chocolate">Web Application</td><td style="color:cornflowerblue;">Theory of Computation</td><td>-</td><td style="color: teal;">Quantitative Ability</td>
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
                <td style="color:red">2.</td><td>19CS406</td><td>Computer Networks</td>
            </tr>
            <tr>
                <td style="color:red">3.</td><td>19CS407</td><td>Theory of computation</td>
            </tr>
            <tr>
                <td style="color:red">4.</td><td>19CS408</td><td>Software Engineering</td>
            </tr>
            <tr>
                <td style="color:red">5.</td><td>19EE404</td><td>Digital Electronics</td>
            </tr>
            <tr>
                <td style="color:red">6.</td><td>19EY710</td><td>Quantitative Ability</td>
            </tr>
            <tr>
                <td style="color:red">7.</td><td>19MA212</td><td>Alegebra and Number Theory</td>
            </tr>
            <tr>
                <td style="color:red">8.</td><td>ECA-M</td><td>Mentor Meet</td>
            </tr>


        </table>
        
    </body>
</html>



## OUTPUT

![Screenshot 2024-10-03 113418](https://github.com/user-attachments/assets/1a2ddf90-de1b-4d16-ae1f-f8f6792b6480)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
