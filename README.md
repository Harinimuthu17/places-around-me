# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:
### Step 1:
Write your own steps here.

### Step 2:
Create a new Django project.

### Step 3:
Write the needed HTML code.

### Step 4:
Run the Django server and execute the HTML files.

## CODE:
```

Map.html:

<!DOCTYPE html>
<html lang="en">
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b> M.Harini  (212222240035) </b></font>
</h3>
<center>
<img src="/static/images/map.png" usemap="#MyCity" height="550" width="1100">
<map name="MyCity">
<area shape="circle" coords="190,50,20" href="/static/html/college.html" title="College">
<area shape="rectangle" coords="230,30,260,60" href="/static/html/fort.html" title="Fort">
<area shape="circle" coords="400,350,50" href="/static/html/temple.html" title="Temple">
<area shape="circle" coords="400,200,75" href="/static/html/hospital.html" title="Hospital">
<area shape="rectangle" coords="490,150,870,320" href="/static/html/hills.html" title="Hills">
</map>
</center>
</body>



College.html:

<!DOCTYPE html>
<html lang="en">
<head>
<title>College</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="red"><b> Vellore </b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Thanthai Periyar Government College</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Permanentmarker" size="5">
<b>
The Thanthai Periyar Government Institute of Technology is a government engineering institution located at Bagayam, Vellore. It was established in July 1990 and is one of the six government engineering colleges fully governed by the Directorate of Technical Education of the Government of Tamil Nadu.
</b>
</font>
</p>
</body>
</html>



Fort.html:

<!DOCTYPE html>
<html lang="en">
<head>
<title>Fort</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Vellore Fort</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Permanentmarker" size="5">
<b>
Vellore Fort is a large 16th-century fort situated in heart of the Vellore city, in the state of Tamil Nadu, India built by Vijayanagara kings.The fort was at one time the headquarters of the Aravidu Dynasty of the Vijayanagara Empire. The fort is known for its grand ramparts, wide moat and robust masonry. 
</b>
</font>
</p>
</body>
</html>



Temple.html:

<!DOCTYPE html>
<html lang="en">
<head>
<title>Fort</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="red"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Sri Narayani Golden Temple</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Permanentmarker" size="5">
<b>
Golden Temple Vellore complex inside the Thirupuram spiritual park is situated at the foot of a small range of green hills at Thirumalaikodi Vellore in Tamil Nadu, India. It is 120 km from Tirupati, 145 km from Chennai, 160 km from Pondicherry and 200 km from Bengaluru.
</b>
</font>
</p>
</body>
</html>



Hospital.html:

<!DOCTYPE html>
<html lang="en">
<head>
<title>CMC Hospital </title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Christian Medical College (CMC)</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="PermanentMarker" size="5">
<b>
Christian Medical College, Vellore, widely known as CMC, Vellore, is a private, Christian community-run medical school, hospital and research institute.One of the top-ranked educational, healthcare and research institutes in the country. This Institute includes a network of primary, secondary and tertiary care hospitals in and around Vellore,Tamil Nadu, India.
</b>
</font>
</p>
</body>
</html>



Hills.html

<!DOCTYPE html>
<html lang="en">
<head>
<title>Hills</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Vellore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Palamathi Hills</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="PermanentMarker" size="5">
<b>
The Palamathi Hills are an extension of the Eastern Ghats spread across southeastern parts of Vellore City in Tamil Nadu. The Palamathi Hill range, the nearby Palamathi Reserve Forest, the Otteri lake is collectively referred to as Palamathi Hills. The area is a thriving hotspot for various birds and various flora.
</b>
</font>
</p>
</body>
</html>

```
## OUTPUT:

![Screenshot (201)](https://github.com/Harinimuthu17/places-around-me/assets/130278614/8d2db78a-585e-4b95-bc31-326d72c61103)

![Screenshot (202)](https://github.com/Harinimuthu17/places-around-me/assets/130278614/660f0884-4b17-41b4-8903-f4aa6ed6d1ad)

![Screenshot (203)](https://github.com/Harinimuthu17/places-around-me/assets/130278614/a74967aa-5188-4c6f-b1d7-b7519e7d638c)

![Screenshot (205)](https://github.com/Harinimuthu17/places-around-me/assets/130278614/2ee355d9-31fd-4e20-b5b0-f839916b2527)

![Screenshot (204)](https://github.com/Harinimuthu17/places-around-me/assets/130278614/5a2e8be9-57fe-4752-95e2-31af8872cbdc)

![Screenshot (206)](https://github.com/Harinimuthu17/places-around-me/assets/130278614/62bebcc7-a24c-4757-8a90-e7a66cb43293)

![Screenshot (207)](https://github.com/Harinimuthu17/places-around-me/assets/130278614/23bcd51a-4672-4f5c-9131-a4273ba5f62e)

![Screenshot (208)](https://github.com/Harinimuthu17/places-around-me/assets/130278614/ab602897-d51f-4236-887f-af32d0651898)


## RESULT:
Thus A website to display details about the places in map is successfully executed and displayed.



