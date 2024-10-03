# Ex03 Time Table
## Date:03.10.2024

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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Time Table - RUDESH KANNA R</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            text-align: center;
            padding: 10px;
        }
        th {
            background-color: rgb(229, 255, 0);
        }
        .free-slot {
            background-color: lightblue;
        }
        .subject-code {
            background-color: rgb(12, 109, 227);
        }
        .lunch {
            text-align: center;
        }
    </style>
</head>
<body>

    <h2 style="text-align: center;">SAVEETHA  AUTONOMOUS  ENGINEERING  COLLEGE</h2>
    <h3 style="text-align: center;">TNEA CODE 1216</h3>
    <h3 style="text-align: center;">SLOT TIME TABLE - RUDESH KANNA R (24900303)</h3>

    <table>
        <tr>
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>saturaday</th>
        </tr>
        <tr>
            <td>8-10</td>
            <td class="free-slot">FREE SLOT</td>
            <td>PLA</td>
            <td>FOC</td>
            <td class="free-slot">FREE SLOT</td>
            <td class="free-slot">FREE SLOT</td>
            <td>FWAD</td>
        </tr>
        <tr>
            <td>10-12</td>
            <td>FOC</td>
            <td class="free-slot">FREE SLOT</td>
            <td class="free-slot">FREE SLOT</td>
            <td>FWAD</td>
            <td>IDS</td>
            <td class="free-slot">FREE SLOT</td>
        </tr>
        <tr>
            <td>12-1</td>
            <td colspan="6" class="lunch">L U N C H</td>
        </tr>
        <tr>
            <td>1-3</td>
            <td class="free-slot">FREE SLOT</td>
            <td>IDS</td>
            <td>MENTOR MEET</td>
            <td class="free-slot">FREE SLOT</td>
            <td class="free-slot">FREE SLOT</td>
            <td class="free-slot">FREE SLOT</td>
        </tr>
        <tr>
            <td>3-5</td>
            <td>FWAD</td>
            <td>PLA</td>
            <td>PLA</td>
            <td class="free-slot">FREE SLOT</td>
            <td class="free-slot">FREE SLOT</td>
            <td>CDS</td>
        </tr>
    </table>

    <h3>Subject Codes</h3>
    <table>
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI301C</td>
            <td>PYTHON AND LINEAR ALGEBRA (PLA)</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19AI304</td>
            <td>FUNDAMENTALS OF C PROGRAMMING (FOC)</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19AI414</td>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT (FWAD)</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19EY708</td>
            <td>CAREER DEVELOPMENT SKILLS (CDS)</td>
        </tr>
        <tr>
            <td>5</td>
            <td>ECA-M</td>
            <td>MENTOR MEET </td>
        </tr>
        <tr>
            <td>6</td>
            <td>19AI403</td>
            <td>INTRODUCTION TO DATA SCIENCE (IDS)</td>
        </tr>
    </table>

</body>
</html>

```

## OUTPUT

![image](https://github.com/user-attachments/assets/8ee9a0f0-1d08-41f4-a66e-58e032fdad90)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
