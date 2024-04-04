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

## CODE:
## map.html
```
<html>
    <title>Mycity</title>
    <body bgcolor="white">
        <h1 align="center"><font color="black">VELACHERY</font></h1>
        <h3 align="center">
            <font color="red">RAJARAMAN V(212223110038)</font></h3>
        <center>
            <img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="amul ice cream" title="amul ice cream" href="ice cream.html" coords="715,41,954,129" shape="rect">
    <area target="" alt="guru nanak" title="guru nanak" href="college.html" coords="1411,116,1612,224" shape="rect">
    <area target="" alt="smoke hub" title="smoke hub" href="smokehub.html" coords="1280,509,1438,639" shape="rect">
    <area target="" alt="luxe cinemas" title="luxe cinemas" href="cinema.html" coords="566,453,786,550" shape="rect">
    <area target="" alt="phoenix mall" title="phoenix mall" href="mall.html" coords="918,176,1104,235" shape="rect">
</map>
        </center>

    </body>
</html>
```
## cinema.html
```
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">VELACHERY</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="red" size="5.5">Luxe Cinemas</font>
    </h3>
    <body bgcolor="cyan" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Luxe Cinemas Velachery is a premier multiplex cinema located in the heart of Velachery, Chennai. Renowned for its luxurious amenities and state-of-the-art facilities, Luxe Cinemas offers an unparalleled movie-watching experience. With its plush seating, advanced sound systems, and cutting-edge projection technology, it caters to cinema enthusiasts seeking top-notch entertainment. The cinema complex features a diverse range of films, from the latest blockbusters to indie gems, ensuring there's something for every moviegoer. Additionally, Luxe Cinemas Velachery provides a variety of dining options and convenient parking facilities, making it a favorite destination for film lovers in the area.
        </font>
        </p
    </body>
</html>
```
## college.html
```
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">VELACHERY</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="red" size="5.5">Guru Nanak college</font>
    </h3>
    <body bgcolor="yellow" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Guru Nanak Velachery is a prominent Sikh Gurudwara located in the bustling neighborhood of Velachery, Chennai. It serves as a spiritual and cultural hub for the Sikh community in the area, offering a place for worship, meditation, and community gatherings. The Gurudwara is known for its serene atmosphere, where visitors can experience the teachings of Guru Nanak Dev Ji and engage in charitable activities such as langar (community kitchen). It plays a vital role in promoting peace, harmony, and social welfare in the locality, welcoming people of all backgrounds to come together and embrace the values of Sikhism.
        </font>
        </p
    </body>
</html>
```
## icecream.html
```
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">VELACHERY</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="red" size="5.5">AMUL ICE CREAM</font>
    </h3>
    <body bgcolor="pink" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            The Amul Ice Cream Parlour in Namma Velachery offers a delightful array of ice cream flavors and treats, catering to the sweet cravings of locals and visitors alike. Located in the heart of Velachery, Chennai, this parlour provides a cozy ambiance for customers to enjoy their favorite frozen desserts. From classic flavors like chocolate and vanilla to innovative creations, there's something to satisfy every palate. Renowned for its quality and freshness, Amul Ice Cream Parlour at Namma Velachery is a go-to destination for those seeking a delicious indulgence in the bustling neighborhood.
        </font>
        </p
    </body>
</html>
```
## mall.html
```
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">VELACHERY</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="red" size="5.5">Phoenix Mall</font>
    </h3>
    <body bgcolor="orange" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Phoenix Marketcity Velachery is a vibrant shopping and entertainment destination situated in the bustling neighborhood of Velachery, Chennai. Boasting a vast array of retail outlets, dining options, and entertainment facilities, the mall offers a comprehensive shopping experience for visitors of all ages. From renowned international brands to popular local boutiques, shoppers can find everything they need under one roof. Additionally, Phoenix Marketcity Velachery features a multiplex cinema, gaming zones, and a food court with diverse culinary offerings, ensuring there's something for everyone to enjoy. With its modern architecture and lively atmosphere, the mall continues to be a go-to destination for leisure and recreation in the city.
        </font>
        </p
    </body>
</html>
```
## smokehub.html
```
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">VELACHERY</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="black" size="5.5">Smoke Hub</font>
    </h3>
    <body bgcolor="red" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            SMOKE HUB BARBEQUE in Velachery is a popular dining destination known for its delicious barbecue offerings and inviting ambiance. Located in the heart of Velachery, Chennai, it offers a unique dining experience where customers can grill their favorite meats and vegetables right at their table. The restaurant boasts a diverse menu featuring a variety of marinated meats, seafood, and vegetarian options, all prepared to perfection on the grill. With its cozy seating and attentive service, SMOKE HUB BARBEQUE is a favorite spot for both casual gatherings and special occasions, drawing in patrons seeking flavorful and interactive dining experiences in the area.
        </font>
        </p
    </body>
</html>
```

## OUTPUT
![Screenshot 2024-04-04 103547](https://github.com/Rajaraman77/NearMe/assets/150319383/00a78db9-4011-486b-8c1d-767b39e2a40f)
![Screenshot 2024-04-04 144841](https://github.com/Rajaraman77/NearMe/assets/150319383/19674e77-57f7-4249-956c-434a77cf5771)
![Screenshot 2024-04-04 144757](https://github.com/Rajaraman77/NearMe/assets/150319383/2e1c811b-0b74-47a5-a46d-ebd0d0a4131b)
![Screenshot 2024-04-04 144733](https://github.com/Rajaraman77/NearMe/assets/150319383/254b4796-8ec3-4436-9922-21b8421ff896)
![Screenshot 2024-04-04 144746](https://github.com/Rajaraman77/NearMe/assets/150319383/6fa53d6d-3782-49c6-84ae-95910899e96e)
![Screenshot 2024-04-04 144828](https://github.com/Rajaraman77/NearMe/assets/150319383/6b4c2135-0f30-4bd5-8ac5-40b11cc4aec0)

## RESULT
The program for implementing image maps using HTML is executed successfully.
