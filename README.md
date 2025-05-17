# Ex04 Places Around Me
## Date:17/05/2025

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

map.html

<!DOCTYPE html>
<html>
<head>
    <title>Document</title>
</head>
<body bgcolor="sky blue">
 <h1><center>SALEM</center></h1>
 <h2><center>Nithila 212224040224</center></h2>
<center><img src="map.png" usemap="#image-map"></center>

<map name="image-map">
    <area target="" alt="YERCAUD – THE JEWEL OF THE SHEVAROY HILLS" title="YERCAUD – THE JEWEL OF THE SHEVAROY HILLS" href="hills.html" coords="1252,599,140" shape="circle">
    <area target="" alt="1008 LINGAM TEMPLE" title="1008 LINGAM TEMPLE" href="temple.html" coords="1280,32,195" shape="circle">
    <area target="" alt="ATTUR FORT" title="ATTUR FORT" href="fort.html" coords="815,264,84" shape="circle">
    <area target="" alt="KURUMBAPATTI ZOOLOGICAL PARK" title="KURUMBAPATTI ZOOLOGICAL PARK" href="park.html" coords="1252,684,143" shape="circle">
    <area target="" alt="MOOKANERI LAKE" title="MOOKANERI LAKE" href="lake.html" coords="815,552,64" shape="circle">
</map>
</body>
</html>

hills.html

<!DOCTYPE html>
<html>
<head>
    <title>
        HILLS
    </title></head>
<body bgcolor="yellow">
    <h1><center> SALEM </center></h1>
    <h2><center> YERCAUD – THE JEWEL OF THE SHEVAROY HILLS </center></h2>
    <hr>
    <center><h3>Yercaud 🌄🌿, often lovingly called “The Jewel of the Shevaroy Hills” 💎🏞️, is a serene hill station nestled in the Eastern Ghats, just 22 kilometers from Salem. Resting at an altitude of 4,970 feet ⛰️, Yercaud is a refreshing escape where cool breezes, rolling green hills 🌳, and aromatic coffee plantations ☕️ create a tranquil paradise far from the heat and noise of the city. Its name, meaning “Lake Forest” 🌊🌲, beautifully reflects the calm centerpiece of the town — the tranquil Yercaud Lake — where visitors can enjoy peaceful boat rides 🚣‍♀️ while surrounded by lush greenery. From the stunning views at Lady’s Seat 🌅 to the cascading beauty of Kiliyur Falls 💧, every corner of Yercaud offers a postcard-perfect moment 📸. The Botanical Garden 🌸, exotic orchidarium 🌺, and the hilltop Servarayan Temple 🛕 add layers of charm, spirituality, and discovery. Whether you're a nature lover 🐦, adventure seeker 🎒, or someone looking for quiet reflection 🧘, Yercaud invites you to slow down, breathe deep, and embrace the magic of the hills 🌬️💚.
.</h3></center>
</body>
</html>

temple.html

<!DOCTYPE html>
<html>
<head>
    <title>
     TEMPLE   
    </title></head>
<body bgcolor="orange">
    <h1><center> SALEM </center></h1>
    <h2><center> 1008 LINGAM TEMPLE </center></h2>
    <hr>
    <center><h3>1008 Lingam Temple 🕯️🛕 is one of the most spiritually captivating places in Salem, located near Ariyanoor on the outskirts of the city. This unique temple is dedicated to Lord Shiva and is famous for housing exactly 1,008 Shiva Lingams, each beautifully arranged in concentric rows across a serene hillside. At the heart of the temple stands a majestic, larger-than-life Shiva Lingam with a towering Nandi (sacred bull) statue facing it — a powerful symbol of devotion and divine strength. Surrounded by a peaceful, green landscape 🌿, the temple offers a tranquil retreat where devotees and visitors alike can meditate, pray, or simply soak in the sacred atmosphere. As the sun sets and the temple lights begin to glow, the view of the lingams illuminated with soft candle-like lamps 🕯️ creates a truly magical and serene sight. It’s not just a place of worship, but also a symbol of spiritual alignment and architectural grace — perfect for those seeking peace, blessings, or a unique cultural experience in Salem.</h3></center>
</body>
</html>

fort.html

<!DOCTYPE html>
<html>
<head>
    <title>
        FORT
    </title></head>
<body bgcolor="grey">
    <h1><center> SALEM </center></h1>
    <h2><center>ATTUR FORT</center></h2>
    <hr>
    <center><h3>Attur Fort 🏰⛳, nestled on the banks of the Vashista River 🌊 in Salem district, is a stunning testament to Tamil Nadu’s rich historical legacy. Built in the 17th century by **Lakshmana Nayakan** under the patronage of the **Gatti Mudaliar dynasty**, this fort sprawls over 62 acres and is surrounded by thick walls towering over 30 feet 🧱 — once designed to resist invaders and time itself. The fort's unique architecture includes massive bastions at each corner 🛡️, a protective moat 🕳️ to the north, and secret passages that echo with the tales of valor, strategy, and legacy.

Inside the fort, visitors can explore ruins of ancient palaces 👑, royal treasuries 💰, and majestic temples 🛕 dedicated to Lord Shiva, Lord Vishnu, and Muniyappan — the guardian spirit of the fort. A bombproof chamber, a water gate leading to the river, and a pleasure house used by royal families add to its mystique and grandeur. Over centuries, it has seen many rulers — from the Gatti Mudaliars to the Mysore kings like **Hyder Ali** and **Tipu Sultan**, and later the British 🇬🇧 who used it as a military outpost.

Though time has weathered parts of the fort, the echoes of its glorious past still linger in every stone, making **Attur Fort** a captivating destination for history lovers 🕰️, architecture enthusiasts 🏛️, and curious travelers alike.
</h3></center>
</body>
</html>

park.html

<!DOCTYPE html>
<html>
<head>
    <title>
        PARK
    </title></head>
<body bgcolor="pink">
    <h1><center> SALEM </center></h1>
    <h2><center>KURUMBAPATTI ZOOLOGICAL PARK</center></h2>
    <hr>
    <center><h3> Kurumbapatti Zoological Park 🐅🌿 is a hidden gem located at the foothills of the Shevaroy Hills, just about 10 km from Salem city. Spanning around **170 acres**, this tranquil zoo is one of the largest in Tamil Nadu and offers a peaceful escape into the wild for nature lovers and families alike. Surrounded by thick forests and rolling hills ⛰️🌳, the park is home to a variety of animals including spotted deer 🦌, peacocks 🦚, monkeys 🐒, crocodiles 🐊, and an array of colorful birds 🐦 that make it a perfect spot for both learning and leisure.

What sets Kurumbapatti apart is its natural setting — unlike typical urban zoos, the enclosures here blend with the environment, giving animals a more open and spacious habitat 🏞️. There are well-maintained walking trails 🚶‍♂️, shaded resting spots 🌤️, and even a small museum and educational displays for kids and curious visitors 📘👧. The zoo’s peaceful ambiance, with the sound of chirping birds and rustling leaves, makes it an ideal place for picnics, photography 📸, and quiet nature walks.

Whether you're visiting with children, exploring as a couple, or enjoying a solo retreat into nature, **Kurumbapatti Zoological Park** offers a calm, educational, and enriching experience that brings you closer to the beauty of wildlife and the serenity of the hills 🌿🕊️.
</h3></center>
</body>
</html>

lake.html

<!DOCTYPE html>
<html>
<head>
    <title>
        LAKE
    </title></head>
<body bgcolor="cyan">
    <h1><center> SALEM </center></h1>
    <h2><center>MOOKANERI LAKE</center></h2>
    <hr>
    <center><h3>Mookaneri Lake🌊🕊️, also known as **Kannankurichi Lake**, is one of Salem’s most beautiful and eco-rich landmarks. Located on the outskirts of the city, this rejuvenated lake has transformed into a peaceful haven for birdwatchers, nature lovers, and morning walkers alike. Spread across 58 acres, the lake is dotted with **47 small man-made islands** 🏝️ — each planted with trees and greenery 🌿 — creating a scenic and almost magical atmosphere, especially at sunrise or sunset 🌅.

What makes Mookaneri Lake truly special is its role as a **bird sanctuary** 🐦. It attracts over **169 species** of birds throughout the year, including migratory species like herons, painted storks, and even flamingos 🦩 during certain seasons. It’s not just a place to walk or relax — it’s a living, breathing ecosystem teeming with life and beauty.

The lake area also features a walking and jogging track 🚶‍♀️, benches, eco-park-style landscaping 🌼, and shaded spots for quiet reflection or casual chats. It’s especially popular with photographers 📸, fitness enthusiasts, and families looking for a calm outing in nature.

**Mookaneri Lake** is a shining example of successful urban eco-restoration 💧🌱 — turning a once-neglected waterbody into a vibrant green lung of Salem. Whether you're watching birds glide across the water, enjoying a quiet stroll, or simply soaking in the fresh air, the lake offers peace, beauty, and a touch of wild charm right in the city.
</h3></center>
</body>
</html>







## OUTPUT
![alt text](<Screenshot (6).png>)
![alt text](<Screenshot (7).png>)
![alt text](<Screenshot (9).png>)
![alt text](<Screenshot (10).png>)
![alt text](<Screenshot (11).png>)
![alt text](<Screenshot (12).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
