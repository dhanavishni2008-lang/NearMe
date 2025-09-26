# Ex04 Places Around Me
## Date: 22.09.2025

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
<html>
    <head>
        <title>sample page</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <h1>vellore city</h1>
        <h2>M.Dhanavishni(25016333)</h2>
        <img src="1.png" usemap="#image-map">

        <map name="image-map">
            <area target="" alt="ICICI Bank ATM" title="ICICI Bank ATM" href="ICICI.html" coords="602,414,779,492" shape="rect">
            <area target="" alt="Katpadi bus stand" title="Katpadi bus stand" href="bus stand.html" coords="908,506,57" shape="circle">
            <area target="" alt="Shri Mahalingeshwarar" title="Shri Mahalingeshwarar" href="thirukovil.html" coords="32,154,45,83,142,83,194,96,276,112,251,148,129,170" shape="poly">
            <area target="" alt="Sai baba temple" title="Sai baba temple" href="temple.html" coords="894,128,58" shape="circle">
            <area target="" alt="CSI Good shepherd church" title="CSI Good shepherd church" href="church.html" coords="400,5,611,57" shape="rect">
        </map>
    </body>
</html>

church.html
<html>
    <head>
        <title>
            CSI good shepherd church
        </title>
    </head>
    <body bgcolor="grey">
        <h1>vellore city</h1>
        <h2>vandranthangal</h2>
        <hr>
        <p>As there are several CSI Good Shepherd Churches, it is necessary to identify which one is in Vellore to provide precise information. The most probable location for a CSI Good Shepherd Church in Vellore, based on search results, is Devarishikuppam</p>
    </body>
</html>

thirukovil.html
<html>
    <head>
        <title>
            shri mahalingeswarar thirukovil
        </title>
    </head>
    <body bgcolor="orange">
        <h1>vellore city</h1>
        <h2>vandaranthangal road</h2>
        <hr>
        <p>The Shri Mahalingeshwara Temple near Vellore is located in Vandranthangal, a private property, and is noted for a meditation hall, a sacred tank, and distributing Annadhanam. The temple is dedicated to Lord Shiva and is a known landmark in the Katpadi area, offering devotees a place for prayer and religious functions, including weddings.</p>   
    </body>
</html>

ICICI.html
html>
    <head>
        <title>
        ICICI Bank
        </title>
    </head>
    <body bgcolor="green">
        <h1>vellore city</h1>
        <h2>gandhi nagar</h2>
        <hr>
        <p>ICICI Bank has multiple branches in and around Vellore, such as Krishna Nagar and Gandhi Nagar, offering a wide range of retail and corporate banking services, including loans, accounts, investments, and digital banking solutions. You can find branches on Officers Line, Krishnagiri Road, and other key locations, and the bank provides user-friendly digital services along with convenient branch access for managing your finances.</p>
    </body> 
</html>

bus stand.html

<html>
    <head>
        <title>
            katpadi bus stand
        </title>
    </head>
    <body bgcolor="yellow">
        <h1>vellore city</h1>
        <h2>vellore main road</h2>
        <hr>
        <p>Katpadi is a locality in northern Vellore, known for its prominent railway junction that acts as a key transportation hub.</p>
</html>

temple.html
<html>
    <head>
        <title>
            katpadi bus stand
        </title>
    </head>
    <body bgcolor="yellow">
        <h1>vellore city</h1>
        <h2>vellore main road</h2>
        <hr>
        <p>Katpadi is a locality in northern Vellore, known for its prominent railway junction that acts as a key transportation hub.</p>
</html>




```
## OUTPUT
![alt text](<Screenshot (20).png>)
![alt text](<Screenshot (21).png>)
![alt text](<Screenshot (22).png>)
![alt text](<Screenshot (23).png>)
![alt text](<Screenshot (24).png>)
![alt text](<Screenshot (25).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
