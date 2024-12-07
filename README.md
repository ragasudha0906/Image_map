# Ex04 Places Around Me
# Date:02-11-2024
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places Around Me</title>
</head>
<body>
    <header>
        <h1>Places Around Me</h1>
    </header>
    <main>
        <img src="C:\Users\admin\Pictures\screenshot13.png" title="map places" usemap="#places-map" >
        <map name="places-map">
            <area shape="rect" coords="856,358,901,389" href="C:\Users\admin\Desktop\quartus\murugan temple.html"  title="murugan temple" />
            <area shape="rect" coords="720,262,771,290" href="C:\Users\admin\Desktop\quartus\school.html" title="school" />
            <area shape="rect" coords="741,109,785,143" href="C:\Users\admin\Desktop\quartus\garden.html" title="garden" />
            <area shape="rect" coords="206,140,247,146" href="C:\Users\admin\Desktop\quartus\clothing store.html" title="clothing store" />
            <area shape="rect" coords="270,391,314,434" href="C:\Users\admin\Desktop\quartus\showroom.html" title="showroom" />
        </map>
    
</body>
</html>
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places around my house</title>
    <style>
        .centreImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            margin-bottom: auto;
        }
        body{
            background-color: antiquewhite;
        }
        h1{
            text-decoration-color: black; text-decoration: underline; font-style: italic;
        }
        p{
            font-size: x-large; font-family: Arial; text-decoration: aliceblue;
            margin-left: 50px;
        }
        a:link {color: green;
            background-color: transparent;
            text-decoration: none;
        }

        a:visited {
            color: rgb(3, 3, 214);
            background-color: transparent;
            text-decoration: none;
        }

        a:hover {
        color: red;
        background-color: transparent;
        text-decoration: underline;
        }

        a:active {
        color: yellow;
        background-color: transparent;
        text-decoration: underline;
        }
        table{
            border: 5px solid black;
            border-collapse: collapse;
        }
        tr,th,td{
            border: 2px dashed black;
            border-collapse: collapse;
            text-align: center;
        }
    </style>
</head>
<body>
    <header style="background-color: rgb(87, 156, 87); height: 80px;">
        <h1 style="text-align:center; font-size: xxx-large; font-family: 'Lucida Grande';margin-top: 10px;">Temple</h1>
    </header>
    <main>
        <img src="C:\Users\admin\Desktop\quartus\index.html\murugan temple.png" title="murugan temple"  usemap="#places-map" class="centreImage" width="600px" height="450px">
        <map name="places-map">
            <area shape="default"   href="https://maps.app.goo.gl/R2tKhr8kBBU1jqwG6" title="murugan temple" />
        </map>
    </main>
    <h1></h1>
    <a href="https://panpolikumaran.hrce.tn.gov.in/" title="Visit SDA"> MURUGAN TEMPLE</a><p> The lord Murugan in this temples shrine is called 'Thirumalai kumarasamy' or 'Thirumalai murugan'. This temple is the nakshatra temple of people born under Vishaka star. Because of the lords name most of the people in this region have the name 'thirumalai'. There is one more goddess temple within this temple, called 'Thirumalai Kaali amman'></p> 
    <p>"Thirumalai Kovil is a Murugan temple situated at Panpoli,[1] Sengottai in the Tenkasi district of Tamil Nadu, South India. It is about 100 km from Thiruvananthapuram. The temple is situated on a small hill surrounded by the Western Ghats near the border with Kerala."></p>
 !DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places around my house</title>
    <style>
        .centreImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            margin-bottom: auto;
        }
        body{
            background-color: antiquewhite;
        }
        h1{
            text-decoration-color: black; text-decoration: underline; font-style: italic;
        }
        p{
            font-size: x-large; font-family: Arial; text-decoration: aliceblue;
            margin-left: 50px;
        }
        a:link {color: green;
            background-color: transparent;
            text-decoration: none;
        }

        a:visited {
            color: rgb(3, 3, 214);
            background-color: transparent;
            text-decoration: none;
        }

        a:hover {
        color: red;
        background-color: transparent;
        text-decoration: underline;
        }

        a:active {
        color: yellow;
        background-color: transparent;
        text-decoration: underline;
        }
        table{
            border: 5px solid black;
            border-collapse: collapse;
        }
        tr,th,td{
            border: 2px dashed black;
            border-collapse: collapse;
            text-align: center;
        }
    </style>
</head>
<body>
    <header style="background-color: rgb(116, 142, 80); height: 80px;">
        <h1 style="text-align:center; font-size: xxx-large; font-family: 'Lucida Grande';margin-top: 10px;">School</h1>
    </header>
    <main>
        <img src="C:\Users\admin\Desktop\quartus\index.html\school.png" title="School"  usemap="#places-map" class="centreImage" width="600px" height="450px">
        <map name="places-map">
            <area shape="default"   href="https://maps.app.goo.gl/6FozX9j3cLBfeP436" title="School" />
        </map>
    </main>
    <h1></h1>
    <a href="https://www.stjohnsschoolmdu.org/" title="Visit SDA"> st.john Matriculation Higher Secondary School </a> 
    <p style="color: black;"> <st class=St.John educational system is the second-largest Christian school system in the world, after the Roman Catholic system.It has a total of 7,804 educational institutions operating in over 100 countries around the world with over 1.5 million students world-wide.The denominationally-based school system began in the 1870s. The church supports holistic education:</p>
    <p>The Education Department team is responsible for the coordination, promotion, training, and quality of the global Seventh-day Adventist educational system, which includes 7,804 schools, colleges and universities, with 84,997 teachers and 1,673,828 students. Working in close cooperation with the Education Department directors in the 13 world divisions, the staff offers services to boards, administrators, and faculty of Adventist colleges and universities worldwide.</p>
    <br>
    <br>
    <table style="background-color: azure; width: 100%; height: 200px; ">
        <tr>
            <th>About SDA</th>
            <th>Infrastructure</th>
            <th>Academics</th>
            <th>Reach us</th>
        </tr>
        <tr>
            <td><a href="https://www.stjohnsschoolmdu.org/">ENGLISH</a></td>
            <td><a href="https://www.stjohnsschoolmdu.org/">PHYSICS</a></td>
            <td><a href="https://www.stjohnsschoolmdu.org/">COMPUTER</a></td>
            <td rowspan="4">The Principal,<br>Seventh-Day Adventist <br>Higher Secondary School<br>Arts College Road,<br>Vellore-632002,Tamil Nadu<br><strong>Contact Us:<br>91 416 2261100, 91 416 2262393</strong></td>
            

        </tr>
        <tr>
            <td><a href="https://www.stjohnsschoolmdu.org/">HINDI</a></td>
            <td><a href="https://www.stjohnsschoolmdu.org/">BIOLOGY</a></td>
            <td><a href="https://www.stjohnsschoolmdu.org/">CHEMISTRY</a></td>
        </tr>
        <tr>
            <td><a href="https://www.stjohnsschoolmdu.org/">CHEMISTRY LAB</a></td>
            <td><a href="https://www.stjohnsschoolmdu.org/">PHYSICS LAB</a></td>
            <td><a href="https://www.stjohnsschoolmdu.org/">TAMIL</a></td>
        </tr>
        <tr>
            <td><br></td>
            <td><a href="https://www.stjohnsschoolmdu.org/">ENGLISH</a></td>
        </tr>

    </table>
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places around my house</title>
    <style>
        .centreImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            margin-bottom: auto;
        }
        body{
            background-color: antiquewhite;
        }
        h1{
            text-decoration-color: black; text-decoration: underline; font-style: italic;
        }
        p{
            font-size: x-large; font-family: Arial; text-decoration: aliceblue;
            margin-left: 50px;
        }
        a:link {color: green;
            background-color: transparent;
            text-decoration: none;
        }

        a:visited {
            color: rgb(3, 3, 214);
            background-color: transparent;
            text-decoration: none;
        }

        a:hover {
        color: red;
        background-color: transparent;
        text-decoration: underline;
        }

        a:active {
        color: yellow;
        background-color: transparent;
        text-decoration: underline;
        }
        table{
            border: 5px solid black;
            border-collapse: collapse;
        }
        tr,th,td{
            border: 2px dashed black;
            border-collapse: collapse;
            text-align: center;
        }
    </style>
</head>
<body>
    <header style="background-color: rgb(106, 157, 106); height: 80px;">
        <h1 style="text-align:center; font-size: xxx-large; font-family: 'Lucida Grande';margin-top: 10px;">Garden</h1>
    </header>
    <main>
        <img src="C:\Users\admin\Desktop\quartus\index.html\garden.png" title="Garden"  usemap="#places-map" class="centreImage" width="600px" height="450px">
        <map name="places-map">
            <area shape="default"   href="https://maps.app.goo.gl/XoEN4LZHdy6hvEb59" title="garden" />
        </map>
    </main>
    <h1></h1>
    <a href="http://www.jayantigardens.com/" title="Visit SDA"> garden </a><p>Jayanti Botanical Gardens was founded by late J. Udayan and Smt. Mahishree Udayan in 1991. Sri J. Udayan came from a long line of horticulturists and a family of nursery men. He was the fifth generation to pursue the business. After almost 20 years of co-owning a nursery with his brother, he branched out to develop his own business with a vision of a growing Bangalore in mind.
    </p>
    <p>Sri J. Udayan envisioned a need for readymade gardens and began producing and growing specimen plants that would add immediate effect to any new landscape. Over the years Smt. Mahishree Udayan has developed on this and established one of the leading nurseries in the country.
    </p>
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places around my house</title>
    <style>
        .centreImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            margin-bottom: auto;
        }
        body{
            background-color: antiquewhite;
        }
        h1{
            text-decoration-color: black; text-decoration: underline; font-style: italic;
        }
        p{
            font-size: x-large; font-family: Arial; text-decoration: aliceblue;
            margin-left: 50px;
        }
        a:link {color: green;
            background-color: transparent;
            text-decoration: none;
        }

        a:visited {
            color: rgb(3, 3, 214);
            background-color: transparent;
            text-decoration: none;
        }

        a:hover {
        color: red;
        background-color: transparent;
        text-decoration: underline;
        }

        a:active {
        color: yellow;
        background-color: transparent;
        text-decoration: underline;
        }
        table{
            border: 5px solid black;
            border-collapse: collapse;
        }
        tr,th,td{
            border: 2px dashed black;
            border-collapse: collapse;
            text-align: center;
        }
    </style>
</head>
<body>
    <header style="background-color: rgb(109, 163, 109); height: 80px;">
        <h1 style="text-align:center; font-size: xxx-large; font-family: 'Lucida Grande';margin-top: 10px;">Clothing Store</h1>
    </header>
    <main>
        <img src="C:\Users\admin\Desktop\quartus\index.html\clothing store.png" title="Clothing Store"  usemap="#places-map" class="centreImage" width="600px" height="450px">
        <map name="places-map">
            <area shape="default"   href="https://maps.app.goo.gl/ETWiXBnNKr5soByQ6" title="clothing store" />
        </map>
    </main>
    <h1></h1>
    <a href="https://www.ottostore.com/?gad_source=1&gclid=CjwKCAjw1NK4BhAwEiwAVUHPUN12HT6ydNhIZS927vZuOPCSm7SQJgz6PWlAiGlTeu-5xzVBm4Q5ixoC6g0QAvD_BwE" title="Visit SDA"> clothing store</a><p> Shop from our wide range of shirts, jeans, cargos, jackets and other apparels. Stay comfortable and fashionable in our must-have denim clothing. Free Shipping. Wide Range Of Apparels. Made In India. COD Available. Types: Boxers, Co-ords, Sweatshirts, Track Pants.</p> 
    <p>Shop Online from the comfort of your home, OTTO online store, Free shipping across India. Try the new OTTO online store, Showroom experience now at the comfort of your home. Premium shirts for men. Free shipping over Rs.899. Online Shopping. Styles: Shirts for Men, Formal Shirts, Party Wear Shirts, Formal Plain Shirts.
        Kollam - Thirumangalam Road, Tenkasi</p>
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Places around my house</title>
    <style>
        .centreImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
            margin-top: 10px;
            margin-bottom: auto;
        }
        body{
            background-color: antiquewhite;
        }
        h1{
            text-decoration-color: black; text-decoration: underline; font-style: italic;
        }
        p{
            font-size: x-large; font-family: Arial; text-decoration: aliceblue;
            margin-left: 50px;
        }
        a:link {color: green;
            background-color: transparent;
            text-decoration: none;
        }

        a:visited {
            color: rgb(3, 3, 214);
            background-color: transparent;
            text-decoration: none;
        }

        a:hover {
        color: red;
        background-color: transparent;
        text-decoration: underline;
        }

        a:active {
        color: yellow;
        background-color: transparent;
        text-decoration: underline;
        }
        table{
            border: 5px solid black;
            border-collapse: collapse;
        }
        tr,th,td{
            border: 2px dashed black;
            border-collapse: collapse;
            text-align: center;
        }
    </style>
</head>
<body>
    <header style="background-color: rgb(154, 158, 108); height: 80px;">
        <h1 style="text-align:center; font-size: xxx-large; font-family: 'Lucida Grande';margin-top: 10px;">Showroom</h1>
    </header>
    <main>
        <img src="C:\Users\admin\Desktop\quartus\index.html\showroom.png" title="Showroom"  usemap="#places-map" class="centreImage" width="600px" height="450px">
        <map name="places-map">
            <area shape="default"   href="https://maps.app.goo.gl/R2tKhr8kBBU1jqwG6" title="showroom" />
        </map>
    </main>
    <h1></h1>
    <a href="https://panpolikumaran.hrce.tn.gov.in/" title="Visit SDA"> showroom</a><p> The lord Murugan in this temples shrine is called 'Thirumalai kumarasamy' or 'Thirumalai murugan'. This temple is the nakshatra temple of people born under Vishaka star. Because of the lords name most of the people in this region have the name 'thirumalai'. There is one more goddess temple within this temple, called 'Thirumalai Kaali amman'></p> 
    <p>"Thirumalai Kovil is a Murugan temple situated at Panpoli,[1] Sengottai in the Tenkasi district of Tamil Nadu, South India. It is about 100 km from Thiruvananthapuram. The temple is situated on a small hill surrounded by the Western Ghats near the border with Kerala."></p>
 ```   
# OUTPUT

![Screenshot 2024-12-07 234151](https://github.com/user-attachments/assets/1fe63268-2a38-46f4-96d0-4d78d50c88b6)
![Screenshot (35)](https://github.com/user-attachments/assets/e3dd7c56-2960-42b7-b317-e3fdd87169f4)
![Screenshot (37)](https://github.com/user-attachments/assets/6ea98bbe-b71a-46ba-9aa4-8a3b681a9f7b)
![Screenshot (38)](https://github.com/user-attachments/assets/67c839e6-5248-4a2a-9b61-e2f1cefa39cc)
![Screenshot (39)](https://github.com/user-attachments/assets/6fd7fde3-3db9-4c73-8ded-bbb567c37e48)
![Screenshot (40)](https://github.com/user-attachments/assets/b5f13746-f181-4d03-9c42-4ad363a42a4c)

# RESULT
The program for implementing image maps using HTML is executed successfully.
