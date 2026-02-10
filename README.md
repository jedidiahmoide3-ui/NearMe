# Ex03 Places Around Me
## Date: 10.02.2026

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
map.html

<html>
    <head>
        <title>My Map</title>

    </head>
    <body>
        <h1>KORATTUR</h1>
        <h2>JEDIDIAH 25012775</h2>
        <img src="Screenshot 2026-02-09 105729.png" usemap="#image-map">
    
        <map name="image-map">
        <area target="_blank" alt="Home" title="Home" href="home.html" coords="1177,396,50" shape="circle">
        <area target="_blank" alt="Green Cinema" title="Green Cinema" href="green cinemas.html" coords="537,663,760,724" shape="rect">
        <area target="_blank" alt="Saravana Stores" title="Saravana Stores" href="saravana store.html" coords="1552,575,1697,589,1689,651,1524,633,1550,573,1524,631,1524,633" shape="poly">
        <area target="_blank" alt="Pothiys" title="Pothiys" href="pothys.html" coords="1311,584,1450,626" shape="rect">
        <area target="_blank" alt="Shivan Temple" title="Shivan Temple" href="temple.html" coords="904,388,89" shape="circle">
        </map>
    </body>
</html>

home.html

html>
    <head>
        <title>Home</title>

    </head>
    <body bgcolor="Pink">
        <h1 align="center">CHENNAI</h1>
        <h2 align="center">Home</h2>
        <p>My Home is my comfort zone, only there im free to do whatever i want. My house is located in Korattur Chennai 2nd Street</p>
    </body>
</html>

green cinemas.html

<html>
    <head>
        <title>Theatre</title>

    </head>
    <body bgcolor="Green">
        <h1 align="center">CHENNAI</h1>
        <h2 align="center">Green Cinema</h2>
        <p>Green Cinemas, located on Railway Station Road in Padi, Chennai, is a popular local multiplex known for offering a modern cinematic experience at affordable prices. It was rebranded and renovated from the former Radha Padi Cinemas (established in 1972) by K.E. Gnanavel Raja, the owner of the Studio Green production house. 
</p>
    </body>
</html>

pothys.html

<html>
    <head>
        <title>Pothys</title>

    </head>
    <body bgcolor="Lime">
        <h1 align="center">CHENNAI</h1>
        <h2 align="center">Pothys</h2>
        <p>Pothys Padi, inaugurated on December 14, 2025, is currently recognized as India’s largest retail showroom, spanning a massive 5 lakh square feet. Located on M.T.H. Road, it is designed as a "one-stop destination" for families. </p>
    </body>
</html>

saravana store.html

<html>
    <head>
        <title>Saravana Stores</title>

    </head>
    <body bgcolor="Orange">
        <h1 align="center">CHENNAI</h1>
        <h2 align="center">Saravana Stores</h2>
        <p>The Legend Saravana Stores is a major retail chain in Tamil Nadu, particularly iconic in Chennai for its "all-in-one" shopping experience and affordable luxury.</p>
    </body>
</html>

temple.html

<html>
    <head>
        <title>Temple</title>

    </head>
    <body bgcolor="Grey">
        <h1 align="center">CHENNAI</h1>
        <h2 align="center">Shivan Temple</h2>
        <p>The primary Shiva temple in Korattur is the Sri Jambukeswarar Temple (also known as the Jambukeswarar Shivan Temple), an ancient shrine with roots dating back over 1,000 years to the Chola and Pallava eras. </p>
    </body>
</html>

```

## OUTPUT
![alt text](<Screenshot (30).png>) ![alt text](<Screenshot (29).png>) ![alt text](<Screenshot (28).png>) ![alt text](<Screenshot (27).png>) ![alt text](<Screenshot (26).png>) ![alt text](<Screenshot (31).png>)






## RESULT
The program for implementing image maps using HTML is executed successfully.
