# Ex04 Places Around Me
## Date: 

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
nearme.html
```

<!DOCTYPE html>
<html>
<head>
<title>POONAMALLEE Map</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
<h2>Arakkonam Map</h2>
<p>Click any marked spot on the map to know about the place.</p>
<!-- Lock the image size -->
<img src="c:\Users\admin\Desktop\poonamap.png" alt="POONAMALLEE Map" usemap="#map" width="1500" height="700" style="border:2px solid black;">

<map name="map">
   

 <area href="GRT.html" coords="700,100,737,51" shape="rect">
  <area shape="rect" coords="670,279,517,217" href="temple.html" alt="temple">
  <area shape="rect" coords="674,385,850,285" href="arbindho.html" alt="arbindho school">
  

 
</map>

</body>
</html>
```

GRT.html
```

<html>
<head>
    <title>grt</title>
    <meta name= "viewport" content="width=device-width, initial-scale=1.0">
     <style>
    body {
        text-align: center; /* centers everything */
        font-family: Arial, sans-serif;
        margin: 50px;
    }
    img {
        width: 70%;      /* image takes 90% of screen width */
        max-width: 1200px; /* optional max width */
        height: auto;     /* keeps aspect ratio */
        border: 2px solid black;
    }
    p {
        margin-top: 20px;
        font-size: 18px;
    }
</style>
</head>
<body>
    <h2>grt</h2>
    <img src="c:\Users\admin\Desktop\grt.png" alt="grt">
    <p>
       GRT Jewellers, Poonamallee, a place where jewellers are bought,in the hot spot of the city.
    </p>
</body>
</html>
```
temple.html
```


<html>
<head>
    <title>temple</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <style>
    body {
        text-align: center; /* centers everything */
        font-family: Arial, sans-serif;
        margin: 50px;
    }
    img {
        width: 70%;      /* image takes 90% of screen width */
        max-width: 1200px; /* optional max width */
        height: auto;     /* keeps aspect ratio */
        border: 2px solid black;
    }
    p {
        margin-top: 20px;
        font-size: 18px;
    }
</style>
</head>
<body>
    <h2>Varadharaja temple</h2>
    <img src="c:\Users\admin\Desktop\varadarajatemple.png" alt="temple">
    <p>
        Poondhamalli Varadaraja Perumal Temple A Serene Divine Abode
Located in the centre of the busy town of Poovrindavalli (now known as Poondhamalli) in Tiruvallur District, Tamil Nadu,
 this majestic and tranquil temple is dedicated to Lord Varadaraja Perumal. 
    </p>
</body>
</html>
```
arbindho.html
```
<!DOCTYPE html>
<html>
<head>
    <title>arbindhoschool</title>
    <meta name= "viewport" content="width=device-width, initial-scale=1.0">
     <style>
    body {
        text-align: center; /* centers everything */
        font-family: Arial, sans-serif;
        margin: 50px;
    }
    img {
        width: 70%;      /* image takes 90% of screen width */
        max-width: 1200px; /* optional max width */
        height: auto;     /* keeps aspect ratio */
        border: 2px solid black;
    }
    p {
        margin-top: 20px;
        font-size: 18px;
    }
</style>
</head>
<body>
    <h2>arbindhoschool</h2>
    <img src="c:\Users\admin\Desktop\arbindhoschool.png" alt="arbindho">
    <p>
      This co-educational English medium School, established in 2012,
       was named after Aurobando Group of Institutions whose welfare measures for their workforce.
    </p>
</body>
</html>



```


## OUTPUT


<img width="1919" height="1185" alt="Screenshot 2025-10-30 112937" src="https://github.com/user-attachments/assets/4ba96a1f-ed00-475b-8448-11e9e927ff75" />

<img width="1278" height="973" alt="Screenshot 2025-10-30 105726" src="https://github.com/user-attachments/assets/b7677e2b-7631-4fb2-92c7-682fcb93f5dd" />

<img width="1275" height="981" alt="Screenshot 2025-10-30 105649" src="https://github.com/user-attachments/assets/f84ca745-cc5b-476a-a7ba-f104cd751622" />

<img width="1257" height="1088" alt="Screenshot 2025-10-30 113129" src="https://github.com/user-attachments/assets/fba06ee5-7122-483d-a8cf-07ef8e28084e" />


## RESULT
The program for implementing image maps using HTML is executed successfully.
