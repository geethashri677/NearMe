# Ex04 Places Around Me
## Date: 26-09-2025

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

<html>
    <head>
        <title>geetha</title>
    </head>
    <body>
        <h1 align="center">CHENNAI MAP-25018001</h1>
<img src="Screenshot 2025-09-20 141852.png" usemap="#image-map" height="680px" width="1450px">

<map name="image-map">
    <area target="" alt="Chennai Park" title="Chennai Park" href="park.html" coords="794,540,70" shape="circle">
    <area target="" alt="Kandhakottam Temple" title="Kandhakottam Temple" href="temple.html" coords="1088,251,1341,320" shape="rect">
    <area target="" alt="Jawaharlal Nehru Stadium" title="Jawaharlal Nehru Stadium" href="stadium.html" coords="741,313,85" shape="circle">
    <area target="" alt="Super Saravana Stores" title="Super Saravana Stores" href="stores.html" coords="-2,237,223,353" shape="rect">
    <area target="" alt="Secretariat park" title="Secretariat park" href="secretariat.html" coords="1569,485,1429,568,1459,657,1653,652,1697,556" shape="poly">
</map>

</body>
</html>

secretariat.html

<html>
    <head>
        <title>secretariat park</title>
   </head>
   <body bgcolor="yellow">
    <b><h1 align="center">SECRETARIAT PARK</h1></b>
    <hr>
   <b><p>Secretariat Park in Chennai is an urban green space situated opposite Fort St. George and near the Chennai Port, offering a tranquil retreat with walking paths, a central fountain, a tree court with benches, and a sunken children's play area. 
        Inaugurated in 2009, this 18.5-acre park features accessible walkways, artistic murals, and granite plazas, making it a popular spot for relaxation, picnics, and community gatherings amidst the city's vibrant environment.
   </b>  
    </p>
   </body>
</html>

stores.html

<html>
    <head>
    <title>stores</title>
    </head>
    <body bgcolor="aqua">
        <b><h1 align="center">SARAVANA STORE</h1></b>
        <hr>
        <b><p>Saravana Store (specifically Saravana Selvarathnam Ultimate Store) in Pallavaram is a prominent retail outlet known for its diverse range of products, from household goods to clothing and electronics, all offered at affordable prices.
             This well-established business has built a loyal customer base by prioritizing customer satisfaction and providing a wide selection of quality items in a comfortable, air-conditioned environment. 
             Located on Pallavaram Thuraipakkam Road in Ganapathipuram, it serves as a convenient, one-stop shopping destination for locals and visitors alike.
        </b>
             </p>
    </body>
</html>

stadium.html

<html>
    <head>
        <title>stadium</title>
    </head>
    <body bgcolor="red">
       <b><h1 align="center">JAWAHARLAL NEHRU STADIUM</h1></b>
       <hr>
        <b><p>The Jawaharlal Nehru Stadium in Chennai is a large, multi-purpose sports complex, also known as the Marina Arena, with a capacity of 40,000 for football and athletics, and an 8,000-seat indoor stadium for various indoor games, concerts, and events. 
            Named after India's first Prime Minister, it hosts the Indian Super League football team Chennaiyin FC, the Tamil Nadu football team, and the Pro Kabaddi League team Tamil Thalaivas, making it a vital sports and event venue in the city.
        </b>  
</p>
    </body>
</html>

park.html

<html>
    <head>
        <title>park</title>
    </head>
    <body bgcolor="hotpink">
        <b><h1 align="center">CHENNAI PARK</h1></b>
        <hr>
       <b><p>Chennai has several notable parks, including the unique urban national park, Guindy National Park, known for its wildlife and blackbuck population, and the historic People's Park, which dates back to the mid-19th century. 
            Other parks like Anna Nagar Tower Park offer recreational facilities and architectural features, while newer developments like Kalaignar Centenary Park aim to provide diverse urban green spaces for relaxation and activities.
             The city's parks, from expansive urban forests to well-maintained community spaces, serve as vital ecological and recreational areas within the metropolitan landscape.
       </b> 
        </p>  

    </body>
</html>

temple.html

<html>
    <head>
        <title>Temple</title>
    </head>
    <body bgcolor="cyan">
        <b><h1 align="center">TEMPLE</h1></b>
        <hr>
       <b><p>Kandaswami Temple, also known as Kandhakottam, is a prominent Hindu temple in Chennai's George Town neighborhood dedicated to Lord Murugan.
             This historical and architectural marvel features traditional Dravidian style and houses the presiding deity, Mutthu Kumāra Swāmi, along with his consorts Valli and Deivayanai. 
             The temple is managed by the Tamil Nadu Hindu Religious and Charitable Endowments Department and is a significant cultural site known for its musical and dance institutions and the temple tank, Saravana Poigai.
       </b>  
</p>

    </body>
</html>


```

## OUTPUT

![alt text](<Screenshot 2025-09-24 113711.png>)

![alt text](<Screenshot 2025-09-24 114138.png>)

![alt text](<Screenshot 2025-09-24 114034.png>)

![alt text](<Screenshot 2025-09-24 114104.png>)

![alt text](<Screenshot 2025-09-24 113754.png>)

![alt text](<Screenshot 2025-09-24 113943.png>)
 





## RESULT
The program for implementing image maps using HTML is executed successfully.
