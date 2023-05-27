# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
~~~
<html>
<head>
<title>Javascript program to display result of a student</title>
<script type="text/javascript">
function student()
{
var mark1,mark2,mark3,total,percentage;
mark1=parseInt(prompt("Enter Subject-1 Marks"))
mark2=parseInt(prompt("Enter Subject-2 Marks"))
mark3=parseInt(prompt("Enter Subject-3 Marks"))
mark4=parseInt(prompt("Enter Subject-4 Marks"))
mark5=parseInt(prompt("Enter Subject-5 Marks"))
total=mark1+mark2+mark3+mark4+mark5
percentage=total/5;
if((percentage>=91)&&(percentage<=100))
{
    alert("O Grade");
}
else if((percentage>=81)&&(percentage<=90))
{
    alert("A+ Grade");
}
else if((percentage>=71)&&(percentage<=80))
{
    alert("A Grade");
}
else if((percentage>=61)&&(percentage<=70))
{
    alert("B+ Grade");
}
else if((percentage>=51)&&(percentage<=60))
{
    alert("B Grade");
}
else
{
    alert("RA Grade");
}
}
</script>
</head>
<body>
<h1 onclick="student()">
Click me to Find Grade Result of a Student
</h1>
</body>
</html>
~~~
## OUTPUT
![mark 01](https://github.com/SrimathiJeyalakshmi/Ex06_Web-Design/assets/127816530/6182ecf2-081b-4a8d-9df0-d71007e32d78)
![mark 02](https://github.com/SrimathiJeyalakshmi/Ex06_Web-Design/assets/127816530/1ae71719-c6e2-4322-8d9e-8f4ee333541a)
![mark 03](https://github.com/SrimathiJeyalakshmi/Ex06_Web-Design/assets/127816530/769c66b3-18e6-4765-9d03-405f1be5d889)
![mark 04](https://github.com/SrimathiJeyalakshmi/Ex06_Web-Design/assets/127816530/bc353f94-0bae-4a25-88bb-3c99bb42a30e)
![mark 05](https://github.com/SrimathiJeyalakshmi/Ex06_Web-Design/assets/127816530/c5616f5d-1926-40f5-a135-f23f39bf1b9f)
![result](https://github.com/SrimathiJeyalakshmi/Ex06_Web-Design/assets/127816530/88dfc5d9-9ab4-4fbc-b579-b6b85d83d856)




## RESULT
  Student result using JavaScript is created successfully.
