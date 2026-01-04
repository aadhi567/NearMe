# Ex03 Places Around Me
## Date: 25-09-2025
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
### Map HTML 
```html
<html>
<head>
    <title>My City</title>
</head>
<body> 
    <h1 align="center"><font color="Black"><b>MANNADY</b></font></h1>
    <h2 align="center"><font color="Black"><b>AADHITHAN B (212224040001)</b></font></h2>
    <center>
        <img src="map.png" usemap="#MyCity" height="610" width="1243">

        <map name="MyCity">
        <area shape="rect" coords="1000,250,900,900" href="beachstation.html" title="beachstation">
        <area shape="rect" coords="750,290,800,800" href="home.html" title="my home">
        <area shape="rect" coords="500,700,400,300" href="flowermarket.html" title="flowermarket">
        <area shape="rect" coords="600,250,700,200" href="metrostation.html" title="metro station">
        

        </map>
    </center>
</body>
</html>
```
### IT park HTML
```html
<html>
    <head>
        <title>IT park</title>
    </head>
    <body bgcolor="white" align="center">
        <h2 align="center">
            <font color="black"><b>Spectrum Mall</b></font>
        </h2>
        <hr size="3" color="black">
        <img src="itpark.jpg" usemap="#IT park" width="900" height="500" >
        <p align="justify" style="line-height: 1.5;">
            <font face="Georgia" size="5"> 
                Ambattur IT Park (Ambit IT Park) is a Grade-A tech campus in Ambattur Industrial Estate, Chennai. It delivers 1+ million sq. ft. of workspace, backed by multi-level parking, 24×7 power, and strong transport connectivity. It’s a cost-efficient alternative to OMR, attracting IT, ITES, and data-center players looking for scalable, no-nonsense infrastructure.
        </p>
    </body>

```
### Bus HTML
```html
<html>
    <head>
        <title>
            My Home Town
        </title>
    </head>
    <body bgcolor="white" align="center">
        <h2 align="center">
            <font color="black"><b>Ambattur Bus Stand</b></font>
        </h2>
        <hr size="3" color="black">
        <img src="bus.jpg" usemap="#My Home Town" width="900" height="500" >
        <p align="justify" style="line-height: 1.5;">
            <font face="Georgia" size="5"> 
            Ambattur Bus Stand is a high-traffic mobility node that streamlines connectivity across Chennai with consistent, high-frequency bus operations. It’s a go-to access point for daily riders, students, and local shoppers, enabling seamless movement to key corridors like Ayanavaram, Periyar Nagar, and Purasaiwalkam. The hub stays active throughout the day and supports core commuter needs with essential passenger amenities. Its strategic location and strong route density position it as a critical enabler of hassle-free, community-wide transit flow.
        </p>
    </body>
</html>
```
### Rail HTML 
```html
<html>
    <head>
        <title>
            My Home Town
        </title>
    </head>
    <body bgcolor="white" align="center">
        <h2 align="center">
            <font color="black"><b>Perambur Railway Station</b></font>
        </h2>
        <hr size="3" color="black">
        <img src="rail.jpg" usemap="#My Home Town" width="900" height="500" >
        <p align="justify" style="line-height: 1.5;">
            <font face="Georgia" size="5"> 
            Ambattur Railway Station is a key suburban node in Chennai’s rail network, positioned on the Chennai Central–Arakkonam line and catering to a heavy daily commuter base. The station drives strong intra-city and inter-city connectivity with its wide platforms, steady train frequency, and streamlined passenger flow. Its location near major residential and industrial zones amplifies its utility, making it a critical mobility gateway for the Ambattur region.    
        </p>
    </body>
</html> 
```
### Land Html
```html
<html>
    <head>
        <title>My Home Town</title>
    </head>
    <body bgcolor="white" align="center">
        <h2 align="center">
            <font color="black"><b>MY HOME</b></font>
        </h2>
        <hr size="3" color="black">
        <img src="land.jpg" alt="My Home" width="1100" height="500">
        <p align="justify" style="line-height: 1.5;">
            <font face="Georgia" size="5" color="black">
                Rakki Cinemas, Ambattur, is a high-footfall entertainment hub positioned as a flagship neighborhood multiplex. It delivers a streamlined movie-going experience with modern projection, optimized seating, and crowd-responsive service ops. The venue anchors local weekend traffic and consistently drives strong consumer engagement across Ambattur and the surrounding micro-markets.
            </font>
        </p>
    </body>
</html>
```

## OUTPUT

<img width="1856" height="999" alt="image" src="https://github.com/user-attachments/assets/f513bae4-41bb-4637-91c4-05c798c01e2d" />

<img width="1853" height="993" alt="image" src="https://github.com/user-attachments/assets/8c85777b-d220-4d7d-bc80-cab8b7187a6c" />

<img width="1858" height="1000" alt="image" src="https://github.com/user-attachments/assets/cc8af013-1390-4a15-b8e3-51ff3fdc5896" />

<img width="1855" height="1008" alt="image" src="https://github.com/user-attachments/assets/ffa2ba76-c9da-4958-8df6-e22270718eea" />











## RESULT
The program for implementing image maps using HTML is executed successfully.
