# Ex.08 Design of a Standard Calculator
## Date:

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <center>
    <h1>Calculator</h1>

    <h5>SANJEEV RAJ.S (212223220096)</h5>
    
    <form action=""name="calculator">
        <table border="4">
            <tr>
                <td colspan="4"><input type="text" id="display" disabled></td>
                
            </tr>
            <tr>
                <td><input type="button" value="1"
                onclick="calculator.display.value+='1'"></td>
                <td><input type="button" value="2"
                onclick="calculator.display.value+='2'"></td>
                <td><input type="button" value="3"
                onclick="calculator.display.value+='3'"></td>
                <td><input type="button" value="+"
                onclick="calculator.display.value+='+'"></td>
            </tr>
            <tr>
                <td><input type="button" value="4"
                onclick="calculator.display.value+='4'"></td>
                <td><input type="button" value="5"
                onclick="calculator.display.value+='5'"></td>
                <td><input type="button" value="6"
                onclick="calculator.display.value+='6'"></td>
                <td><input type="button" value="-"
                onclick="calculator.display.value+='-'"></td>
            </tr>
            <tr>
                <td><input type="button" value="7"
                onclick="calculator.display.value+='7'"></td>
                <td><input type="button" value="8"
                onclick="calculator.display.value+='8'"></td>
                <td><input type="button" value="9"
                onclick="calculator.display.value+='9'"></td>
                <td><input type="button" value="*"
                onclick="calculator.display.value+='*'"></td>
            </tr>
            <tr>
                <td><input type="button" value="c"
                onclick="calculator.display.value+='c'"></td>
                <td><input type="button" value="0"
                onclick="calculator.display.value+='0'"></td>
                <td><input type="button" value="="
                onclick="calculator.display.value =eval(calculator.display.value)"></td>
                <td><input type="button" value="/"
                onclick="calculator.display.value+='/'"></td>
            </tr>
        </table>
    </form>
</center>
</body>
</html>

```
## OUTPUT:

![image](https://github.com/sanjeevrajshanmugam/Calc/assets/151383137/8513b333-2843-4ee7-8bd8-efac2beccb18)

![image](https://github.com/sanjeevrajshanmugam/Calc/assets/151383137/72af4cb4-e866-4136-a32c-dcd8ad411c4b)


## RESULT:
The program for designing a standard calculator using HTML and CSS is executed successfully.
