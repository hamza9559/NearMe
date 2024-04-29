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
```
DEVELOPED BY: HAMZA FAROOQUE
REG.NO: 212223040054
##map.html
<html>
    <title>Mycity</title>
    <body bgcolor="white">
        <h1 align="center"><font color="black">CHENNAI</font></h1>
        <h3 align="center">
            <font color="red">HAMZA FAROOQUE (212223040054)</font></h3>
        <center>
            <img src="map.png" usemap="#image-map">

            <map name="image-map">
                <area target="" alt="royapettah" title="royapettah" href="royapettah.html" coords="1202,465,1451,590" shape="rect">
                <area target="" alt="marina" title="marina" href="marina.html" coords="1735,632,1553,545" shape="rect">
                <area target="" alt="chepauk" title="chepauk" href="chepauk.html" coords="1684,216,1459,344" shape="rect">
                <area target="" alt="museum" title="museum" href="govtmuseum.html" coords="1191,23,1020,141" shape="rect">
                <area target="" alt="poonga" title="poonga" href="poonga.html" coords="1044,537,916,633" shape="rect">
            </map>
        </center>

    </body>
</html>

##marina.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">CHENNAI</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="red" size="5.5">MARINA BEACH</font>
    </h3>
    <body bgcolor="cyan" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Marina Beach, located in Chennai, is one of the longest urban beaches in the world, stretching along the Bay of Bengal for 
            approximately 13 kilometers. It's a bustling hub of activity, offering a picturesque backdrop for leisurely strolls, kite flying, 
            and beach sports. The beach is dotted with iconic landmarks such as the lighthouse and the Anna Memorial, adding to its charm. 
            Marina Beach is a popular spot for locals and tourists alike, especially during festivals like Pongal and New Year's Eve. 
            Its golden sands and stunning sunsets make it an ideal destination for relaxation and recreation in the heart of the city.
        </font>
        </p
    </body>
</html>

##chepauk.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">CHENNAI</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="black" size="5.5">M.A. Chidambaram Stadium</font>
    </h3>
    <body bgcolor="red" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            The M.A. Chidambaram Stadium, affectionately known as the Chepauk Stadium, is a historic cricket ground situated in Chennai, Tamil Nadu. 
            It has a rich legacy, hosting numerous memorable cricket matches, including both domestic and international games. 
            The stadium is renowned for its electrifying atmosphere and passionate cricket fans, who fervently support their teams during matches. 
            With a seating capacity of around 38,000 spectators, it provides an immersive experience for cricket enthusiasts. 
            The stadium has witnessed iconic moments in cricket history, including Sachin Tendulkar's record-breaking century against England in 2008. 
            Its picturesque setting and iconic pavilion add to the allure of watching cricket at this legendary venue.
            It is also the home ground for CSK(Chennai Super Kings) in IPL(Indian Premier League)...
        </font>
        </p
    </body>
</html>

##royapettah.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">CHENNAI</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="red" size="5.5">Royapettah</font>
    </h3>
    <body bgcolor="peach" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Royapettah, a bustling locality in Chennai, is renowned for its vibrant atmosphere and rich cultural heritage. 
            It houses a diverse mix of residential, commercial, and educational institutions, including the historic Royapettah Clock Tower. 
            The area is known for its vibrant street markets, offering everything from textiles to traditional South Indian cuisine. 
            Royapettah is also home to prominent healthcare facilities like the Government Royapettah Hospital. 
            Its central location and well-connected transportation make it a hub for commerce and everyday life in Chennai. 
            With its blend of tradition and modernity, Royapettah remains a vibrant and integral part of the city's landscape.
        </font>
        </p
    </body>
</html>

##govtmuseum.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">CHENNAI</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="red" size="5.5">Government Museum,Egmore</font>
    </h3>
    <body bgcolor="green" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            The Government Museum, Egmore, located in Chennai, is a treasure trove of art, history, and culture, tracing the rich heritage of 
            Tamil Nadu and beyond. Established in 1851, it is one of the oldest museums in India and houses a diverse collection of artifacts 
            spanning various periods and civilizations. The museum's expansive galleries showcase everything from ancient sculptures and artifacts 
            to numismatics, ethnology, and natural history exhibits. Notable highlights include the Bronze Gallery, which features exquisite 
            Chola bronze sculptures, and the Amaravati Gallery, showcasing intricate stone carvings from the Amaravati Stupa. 
            With its comprehensive displays and educational programs, the Government Museum offers visitors a captivating journey through the 
            cultural tapestry of South India and beyond.
        </font>
        </p
    </body>
</html>

##poonga.html
<html>
    <h1 align="center">
        <font face="Times New Roman" color="black" size="6">CHENNAI</font>
    </h1>
    <h3 align="center">
        <font face="Times New Roman" color="red" size="5.5">Semmozhi Poonga</font>
    </h3>
    <body bgcolor="orange" align="center">
        <hr size="4" color="white">
        <p align="center">
        <font face="Times New Roman" size="5">
            Semmozhi Poonga, located in the heart of Chennai, is a lush botanical garden that offers a tranquil escape from the bustling city life. 
            Opened in 2010, it spans over 20 acres and showcases a diverse collection of indigenous and exotic plant species, meticulously landscaped
            to create a serene and picturesque environment. The garden's name, "Semmozhi Poonga," translates to "Classical Language Park," 
            reflecting its thematic dedication to promoting the rich linguistic and cultural heritage of Tamil Nadu. Visitors can explore themed 
            gardens, including medicinal plants, aromatic herbs, and rare flora, while meandering through winding pathways and serene water features. 
            With its verdant landscapes and educational exhibits, Semmozhi Poonga provides a rejuvenating oasis for nature enthusiasts and urban 
            dwellers alike, offering a serene respite amidst the urban landscape of Chennai.
        </font>
        </p
    </body>
</html>

```


## OUTPUT


![Screenshot 2024-04-25 132227](https://github.com/hamza9559/NearMe/assets/154586530/25081c6e-1cd6-498d-baa1-aa6f4c8e03c7)

![Screenshot 2024-04-25 132239](https://github.com/hamza9559/NearMe/assets/154586530/865ffceb-e371-4871-8752-87b3bc49ee14)


![Screenshot 2024-04-25 132255](https://github.com/hamza9559/NearMe/assets/154586530/726d71fc-4424-414d-bce8-95dcfcf777d0)

![Screenshot 2024-04-25 132308](https://github.com/hamza9559/NearMe/assets/154586530/51878190-c970-44a7-9bff-0b338c74f5fd)


![Screenshot 2024-04-25 132327](https://github.com/hamza9559/NearMe/assets/154586530/3e6b9966-d023-4046-adbf-d9feac575117)


![Screenshot 2024-04-25 132342](https://github.com/hamza9559/NearMe/assets/154586530/9550360f-c081-4b83-83b1-386d3fc6150c)



## RESULT
The program for implementing image maps using HTML is executed successfully.
