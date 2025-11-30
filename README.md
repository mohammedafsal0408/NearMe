# Ex03 Places Around Me
## Date:30/11/2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
<html>
<head>
    <title>My City</title>
</head>
<body>
    <h2 align="center" textcolor="blue">CUDDALORE-OT CITY</h2>
    <br></br>
    <h4 align="center" textcolor="maroon">MOHAMMED AFSAL S (25012989)</h4>
    <br>
    <img src="Screenshot 2025-11-28 112721.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Reliance Digital" title="Reliance Digital" href="reliance.html" coords="567,541,740,570" shape="rect">
    <area target="" alt="St.David FORT" title="St.David FORT" href="David.html" coords="912,743,89" shape="circle">
    <area target="" alt="CK College of Engineering" title="CK College of Engineering" href="ck.html" coords="667,811,850,865" shape="rect">
    <area target="" alt="Ramraj Cotton" title="Ramraj Cotton" href="ramraj.html" coords="504,619,584,614,579,665,511,672" shape="poly">
    <area target="" alt="Thazhanguda Beach" title="Thazhanguda Beach" href="thazhanguda.html" coords="1139,252,47" shape="circle">
</map>
</body>

<html>
<head>
<title>ST.DAVID FORT</title>
</head>
<body bgcolor="maroon">
    <h2 align="center" textcolor="cyan">CUDDALORE-OT CITY</h2>
    <h4 align="center" textcolor="grey">ST.DAVID FORT</h4>
    <hr>
    <p>
        Fort St. David was a historic British fort near Cuddalore, Tamil Nadu, built in 1690 on the Coromandel Coast. It served as the British headquarters for South India, played a major role in colonial conflicts with the French, and was named after the patron saint of Wales by Governor Elihu Yale. Today, it exists as ruins situated near the town and the Silver Beach. 
    </p>
</body>
</html>

<html>
<head>
<title>CK ENGINEERING COLLEGE</title>
</head>
<body bgcolor="olive">
    <h2 align="center" textcolor="silver">CUDDALORE-OT CITY</h2>
    <h4 align="center" textcolor="maroon">CK ENGINEERING COLLEGE</h4>
    <hr>
    <p>
        C.K. College of Engineering & Technology (CKCET) is a private engineering college in Cuddalore, Tamil Nadu, founded in 2002 and affiliated with Anna University. Approved by the AICTE, the college provides undergraduate and postgraduate engineering programs, with a focus on quality education for students in a rural setting. It is known for having ISO 9001:2015 certification and NAAC accreditation. 
    </p>
</body>
</html>

<html>
<head>
<title>RELIANCE DIGITAL</title>
</head>
<body bgcolor="cyan">
    <h2 align="center" textcolor="brown">CUDDALORE-OT CITY</h2>
    <h4 align="center" textcolor="yellow">RELIANCE DIGITAL</h4>
    <hr>
    <p>
        Reliance Digital is a major Indian retailer that sells consumer electronics and appliances through its physical stores and online platform. It is a subsidiary of Reliance Retail, offering a wide range of products like personal devices, home appliances, and entertainment systems from over 200 brands. The company focuses on providing a multi-channel shopping experience, including expert advice, product experience zones, and post-sales support services through its arm, ResQ. 
    </p>
</body>
</html>

<html>
<head>
<title>THAZHUNGUDA BEACH</title>
</head>
<body bgcolor="silver">
    <h2 align="center" textcolor="olive">CUDDALORE-OT CITY</h2>
    <h4 align="center" textcolor="cyan">THAZHUNGUDA BEACH</h4>
    <hr>
    <p>
        Thazhanguda Beach is a coastal area in Cuddalore, Tamil Nadu, known for being a tranquil and natural spot with coconut trees providing shade. It is less developed than other beaches, offering a simpler experience with limited food options and no commercial rides or facilities. The beach is open 24 hours and serves as a point of interest in the Manjakkuppam area of Cuddalore. 
    </p>
</body>
</html>

<html>
<head>
<title>RAMRAJ COTTON</title>
</head>
<body bgcolor="coral">
    <h2 align="center" textcolor="teal">CUDDALORE-OT CITY</h2>
    <h4 align="center" textcolor="yellow">RAMRAJ COTTON</h4>
    <hr>
    <p>
        Ramraj Cotton is an Indian ethnic wear brand founded in 1983 by K.R. Nagarajan in Tirupur, Tamil Nadu, that specializes in high-quality men's cotton and silk garments, particularly dhotis. The company is known for pioneering the branding of dhotis, introducing a wide range of varieties, and using innovative marketing strategies to popularize traditional Indian wear.
    </p>
</body>
</html>

```

## OUTPUT
![alt text](<Screenshot (30).png>)
![alt text](<Screenshot (31).png>)
![alt text](<Screenshot (33).png>)
![alt text](<Screenshot (34).png>)
![alt text](<Screenshot (35).png>)
![alt text](<Screenshot (32).png>)






## RESULT
The program for implementing image maps using HTML is executed successfully.
