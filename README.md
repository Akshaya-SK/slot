# Ex03 Time Table
## Date:

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
```<html>
    <head>
        <title> Time Table </title>
    </head>
    <body>
        <img src = "c:\Users\admin\Pictures\Screenshots\Screenshot 2024-10-24 104012.png" 
        style ="display: block; margin-left: auto; margin-right: auto">
        <p align = "center", style="font-size: larger; color: blueviolet;"><b>TIMETABLE</b></p>
        <p align = "center", style="font-size: larger; color: darkmagenta;"><i>AKSHAYA S K - 212223040011</i></p>
        <br>
        <table border = "1" style = "border-collapse:collapse" align = "center">
            <tr style="background-color: rgb(217, 68, 135); color: aliceblue;" >
                <td>DAY/TIME</td>
                <td>MONDAY</td>
                <td>TUESDAY</td>
                <td>WEDNESDAY</td>
                <td>THURSDAY</td>
                <td>FRIDAY</td>
                <td>SATURDAY</td>
            </tr>
            <tr style="background-color: rgb(66, 178, 229); color: aliceblue;">
                <td style="background-color: rgb(217, 68, 135); color: aliceblue;">08:00am - 10:00am</td>
                <td></td>
                <td>19CS304 - Computer Network</td>
                <td>19MA212 - Logic and Combinatronics</td>
                <td>19EE305 - Basic Electrical Electorics and Mesurement Engineering</td>
                <td>19MA212 - Logic and Combinatronics</td>
                <td>19AI414 - Fundamentals of Web Development</td>
            </tr>
            <tr style="background-color: rgb(66, 178, 229); color: aliceblue;">
                <td style="background-color: rgb(217, 68, 135); color: aliceblue;">10:00am - 12:00pm</td>
                <td>19AI301 - Python Programming</td>
                <td>19CS409 - Compiler Design</td>
                <td>19CS405 - Operating System</td>
                <td>19AI414 - Fundamentals of Web Development</td>
                <td>19AI301 - Python Programming</td>
                <td></td>
            </tr>
            <tr style="background-color: rgb(66, 178, 229); color: aliceblue;">
                <td style="background-color: rgb(217, 68, 135); color: aliceblue;">12:00pm - 01:00pm</td>
                <td colspan = "6", align = "center"><b>LUNCH</b></td>
            </tr>
            
            <tr style="background-color: rgb(66, 178, 229); color: aliceblue;">
                <td style="background-color: rgb(217, 68, 135); color: aliceblue;">01:00pm - 03:00pm</td>        
                <td></td>
                <td></td>
                <td>MENTOR MEET</td>
                <td>19CS409 - Compiler Design</td>
                <td>19EE305 - Basic Electrical Electorics and Mesurement Engineering</td>
                <td>19CS304 - Computer Network</td>
            </tr>
            <tr style="background-color: rgb(66, 178, 229); color: aliceblue;">
                <td style="background-color: rgb(217, 68, 135); color: aliceblue;">03:00pm - 05:00pm</td>
                <td>19AI414 - Fundamentals of Web Development</td>
                <td></td>
                <td></td>
                <td>19EY710 - Quantative Ability - I</td>
                <td>19CS405 - Operating System</td>
                <td></td>
                
                
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT

![image](https://github.com/user-attachments/assets/d3cedd74-fcbc-48cf-863a-0400e3c28dce)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
