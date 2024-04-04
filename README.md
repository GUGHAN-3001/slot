# Ex03 Time Table
## Date: 04.04.24

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
</head>
<body align="center" bgcolor="skyblue" >
	 <center>
        <img src="logo.png" height="100" width="800">
     </center>
	<table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="red">
		<caption>SLOT TIME TABLE - GUGHAN S (212223240043) </caption>
        <br>
		<tr>
			<th bgcolor="lightgray"> Day/Time </th>
			<th bgcolor="lightgray"> Monday </th>
			<th bgcolor="lightgray"> Tuesday </th>
            <th bgcolor="lightgray"> Wednesday </th>
            <th bgcolor="lightgray"> Thursday </th>
            <th bgcolor="lightgray"> Friday </th>
            <th bgcolor="lightgray"> Saturday </th>
		</tr>
		<tr>
			<th bgcolor="sky blue"> 8-10 </td>
            <td> Creative Skills </td>
            <td> Free SLOT </td>
            <td> French </td>
            <td> WEB </td>
            <td> WEB </td>
            <td> PYTHON </td>
		</tr>
		<tr>
            <th bgcolor="sky blue"> 10-12 </th>
			<td> FREE SLOT </td>
            <td> LINEAR ALGEBRA </td>
            <td> FREE SLOT </td>
            <td> FREE SLOT </td>
            <td> FREE SLOT </td>
            <td> FREE SLOT </td>
		</tr>
		<tr>
            <th bgcolor="sky blue"> 12-1 </th>
            <td colspan="6" align="center"> LUNCH </td>
		</tr>
		<tr>
            <th bgcolor="sky blue"> 1-3 </th>
            <td> CHEM </td>
            <td> FRENCH </td>
            <td> ENGLISH </td>
            <td> FREE SLOT </td>
            <td> LINEAR ALGEBRA </td>
            <td> FREE SLOT </td>
		</tr>
		<tr>
            <th bgcolor="sky blue"> 3-5 </td>
            <td> Free SLOT </td>
            <td> WEB </td>
            <td> PYTHON </td>
            <td> FRENCH </td>
            <td> ENGLISH </td>
            <td> CHEM </td>
		</tr>
		</table>
        <br>
        <table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="orange">
            <br>
            <tr>
                <th align="center"> S.No </th>
                <th align="center"> Subject Code </th>
                <th align="center"> Subject Name </th>
            </tr>
            <tr>
                <th> 1. </td>
                <td align="center"> 19AI301C </td>
                <td align="center"> Python and Linear Algebra </td>
            </tr>
            <tr>
                <th align="center"> 2. </td>
                <td align="center"> 19AI414 </td>
                <td align="center"> Fundamentals of web applications  </td>
            </tr>
            <tr>
                <th align="center"> 3. </td>
                <td align="center"> 19CY205 </td>
                <td align="center"> Principles of Chemistry in Engineering </td>
            </tr>
            <tr>
                <th align="center"> 4. </td>
                <td align="center"> 19EN101 </td>
                <td align="center"> Communicative English </td>
            </tr>
            <tr>
                <th align="center"> 5. </td>
                <td align="center"> 19EN11C </td>
                <td align="center"> French Basic and Advanced </td>
            </tr>
            <tr>
                <th align="center"> 6. </td>
                <td align="center"> 19EY702 </td>
                <td align="center"> Creative skills for communication (CRT SKILLS) </td>
            </tr>
            
            </table>
</body>

```

## OUTPUT
![alt text](<Screenshot 2024-04-04 103306.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
