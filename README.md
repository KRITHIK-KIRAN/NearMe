# Ex04 Places Around Me
## Date: 28/9/2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
map.html

<img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="thiruvalluvar apartment" title="thiruvalluvar apartment" href="apartment.html" coords="717,262,582,233" shape="rect">
    <area target="" alt="ayappakam park" title="ayappakam park" href="park.html" coords="674,133,744,129,738,218,680,221,655,191,659,167" shape="poly">
    <area target="" alt="ice berg" title="ice berg" href="ice.html" coords="1070,338,50" shape="circle">
    <area target="" alt="ganesh party hall" title="ganesh party hall" href="hall.html" coords="243,524,382,547" shape="rect">
    <area target="" alt="virutcham hospital" title="virutcham hospital" href="hospital.html" coords="645,101,652,78,799,81,796,103,721,103"  shape="poly">
</map>
park.html
<html>
<head>
<title>ayappakam park</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
    <font color="red"><b>My Home Town</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>ayappakam park</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The ayappakam park super looking park that are upgrade for playing for kids and the walking for older people.
</font>
</p>
</body>
</html>

ice.html

<html>
<head>
<title>ice berg</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
    <font color="red"><b>My Home Town</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>ice berg</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The ice berg is a canteen . It is juice store . It working time is 8 to 8
</font>
</p>
</body>
</html>

hospital.html
<html>
<head>
<title>virutcham hospital</title>
</head>
<body bgcolor="orange">
<h1 align="center">
    <font color="red"><b>My Home Town</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>virutcham hospital</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The virutcham hospital is 24/7 working hospitali. It is super hospital . It as a good infrastruture
</font>
</p>
</body>
</html>

hall.html
<html>
<head>
<title>ganesh party hall</title>
</head>
<body bgcolor="green">
<h1 align="center">
    <font color="red"><b>My Home Town</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>ganesh party hall</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The ganesh hall is marriage hall or used for function making.  
</font>
</p>
</body>
</html>

apartment.html
<html>
<head>
<title>thiruvalluvar apartment</title>
</head>
<body bgcolor="purple">
<h1 align="center">
    <font color="red"><b>My Home Town</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>thiruvalluvar apartment</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Thiruvalluvar apartment is a goverment given apartment given to people at low cost.
</font>
</p>
</body>
</html>
```

## OUTPUT








## RESULT
The program for implementing image maps using HTML is executed successfully.
