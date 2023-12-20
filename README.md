# Ex.08 Design of a Standard Calculator
## Date: 20-12-2023

## AIM:
To design a web application for a standard calculator with minimum five operations.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for creating attractive colors.

### Step 4:
Write JavaScript program for implementing five different operations.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
calc.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Personal Digital Assistant</title>
        <title>Divya P</title>
        <title>(23002600)</title>
        
        <style>
        table{
            border: 20px solid rgb(255, 0, 157);
            margin-left: auto;
            margin-right: auto;
            font-family: Georgia, 'Times New Roman', Times, serif;
            width: 20%;
        }
        input[type="text"]{
            border: 5px solid rgb(91, 177, 72);
            padding: 30px 30px;
            font-size: 30px;
            font-weight: bold;
            border-radius: 8px;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }


        input[type="button"]{
            width: 100%;
            padding: 20px 40px;
            background-color: rgb(186, 144, 238);
            border-radius: 2px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-size: x-large;
        }
        </style>
    </head>
    <body>
        <form name="form1" onload="result.value=''">
            <h1 style="text-align: center;color:rgb(15, 14, 14);">Personal Digital Assistant</h1>
            <h2 style="text-align: center;color:rgb(177, 12, 12);font-family: 'Times New Roman', Times, serif;">Divya P</h2>
            <h3 style="text-align: center;color:rgb(177, 12, 12);font-size: x-large;">(23002600)</h3>
            
        <table id="calc">
            <tr>
                <td colspan="4">
                    <input type="text" id="result">
                </td>
            </tr>
            <tr>
                <td><input type="button" value="1" onclick="result.value+='1'"></td>
                <td><input type="button" value="2" onclick="result.value+='2'"></td>
                <td><input type="button" value="3" onclick="result.value+='3'"></td>
                <td><input type="button" value="+" onclick="result.value+='+'"></td>
            </tr>
            <tr>
                <td><input type="button" value="4" onclick="result.value+='4'"></td>
                <td><input type="button" value="5" onclick="result.value+='5'"></td>
                <td><input type="button" value="6" onclick="result.value+='6'"></td>
                <td><input type="button" value="-" onclick="result.value+='-'"></td>
            </tr>
            <tr>
                <td><input type="button" value="7" onclick="result.value+='7'"></td>
                <td><input type="button" value="8" onclick="result.value+='8'"></td>
                <td><input type="button" value="9" onclick="result.value+='9'"></td>
                <td><input type="button" value="*" onclick="result.value+=''"></td>
            </tr>
            <tr>
                <td><input type="button" value="/" onclick="result.value+='/'"></td>
                <td><input type="button" value="0" onclick="result.value+='0'"></td>
                <td><input type="button" value="." onclick="result.value+='.'"></td>
                <td><input type="button" value="=" onclick="result.value=eval(result.value)"></td>
            </tr>
            <tr>
                <td colspan="4">
                    <input type="button" value="C" id="clear" onclick="result.value=''">
                </td>
            </tr>
        </table>
        </form>
    </body>
</html>

```
## OUTPUT:
![Alt text](<Screenshot (48).png>)
![Alt text](<Screenshot (49).png>)

## RESULT:
The program for designing a standard calculator using HTML and CSS is executed successfully.
