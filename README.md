# Ex03 Time Table
## Date:13-03-2025

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
        <meta charset="utf-8">
        <title>TimeTable</title>
        <style>
            body{
                font-family: Arial, Helvetica, sans-serif;
                text-align: center;
                margin: 20px;
                background:linear-gradient(to right, #fde52f, #f5f1c2);
            }
            .logo{
                width: 700px;
                margin-bottom: 20px;
                height : 100px;
            }
            table{
                width: 90%;
                margin: auto;
                border-radius: 15px;
                overflow: hidden;
                border-collapse: separate;
                border-spacing: 0;
                border: none;
            }
            th, td {
                
            padding: 10px;
            text-align: center;
            background-color: antiquewhite;
            border: 1px solid #f4b400;
            }
            th {
            background-color: #f7f4f4;
            color: rgb(15, 0, 0);
            }
            #table_head{
                background-color: #f4b400;
                color: white;
                font-size: 20px;
            }
            .Days{
                background-color: #f7f4f4;
                color: black;
                font-weight: bold;
            }
        </style>
    </head>

    <body>
        <img src="/static/logo.png" alt="logo" class="logo">
        <h1>March Time Table</h1>
        <table>
            <tr>
                <th colspan="4" id="table_head">Web Development and Fundamentals of AI Batch</th>
            </tr>
            <tr class="Days">
                <th></th>
                <th>8-10 AM</th>
                <th>10-12 AM</th>
                <th>1-3 PM</th>
            </tr>
            <tr>
                <td class="Days">MONDAY</td>
                <td>WEB DEVELOPMENT</td>
                <td>TASK ASSIGNMENT</td>
                <td>FUNDAMENTALS OF AI</td>
            </tr>
            <tr>
                <td class="Days">TUESDAY</td>
                <td>TASK COMPLETION</td>
                <td>WEB DEVELOPMENT</td>
                <td>MODULE COMPLETION</td>
            </tr>
            <tr>
                <td class="Days">WEDNESDAY</td>
                <td>ASSIGNMENT HOUR</td>
                <td>TASK PRESENTATION</td>
                <td>MENTOR MEET</td>
            </tr>
            <tr>
                <td class="Days">THURSDAY</td>
                <td>TASK PRESENTATION</td>
                <td>MODULE COMPLETION</td>
                <td>FUNDAMENTALS OF AI</td>
            </tr>
            <tr>
                <td class="Days">FRIDAY</td>
                <td>TASK COMPLETION</td>
                <td>WEB DEVELOPMENT</td>
                <td>TASK COMPLETION</td>
            </tr>
        </table>

    </body>

</html>
```

## OUTPUT

![alt text](<Screenshot (71).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
