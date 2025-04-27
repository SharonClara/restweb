# Ex.07 Restaurant Website
## Date:28/04/2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
main.html
```
<!DOCTYPE html>
 <html lang="en">
 <head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
 <title>RESTAURANT</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-image: url(bg.jpg);
      margin: 0;
      padding: 0;
      background-color: #12e9ed;
    }
    header {
      background-color: rgb(224, 224, 152);;
      padding: 20px;
      font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
      font-size: 30px;
      text-align: center;
      border-bottom: 2px solid #ccc;
    }
    header img {
      height: 50px;
      vertical-align: middle;
    }
    header h1 {
      display: inline;
      margin-left: 10px;
      font-size: 24px;
      color: #333;
    }
    nav {
      background-color: #333;
      overflow: hidden;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;   
      display: block;
      float:left;
      
    }
    nav a:hover {
      background-color: #575757;
    }
    .content {
      display: flex;
      justify-content: space-around;
      padding: 20px;
    }
    .content div {
      background-color: #f8f8f8;
      padding: 20px;
      margin: 10px;
      flex: 1;
      text-align: center;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }
    footer {
      text-align: center;
      padding: 10px;
      background-color: #333;
      color: white;
      position: absolute;
      bottom: 0;
      width: 100%;
    }
  </style>
 </head>
 <body>
  <header>
    JOSHARAN RESTAURANT
  </header>
  <nav>
    <a href="index.html" >Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>
  <div class="content">
    <div>
      <h3>Our New Menu</h3>
      <img src="open pic.jpg" alt="Menu img 1" height="200" width="200">
      <p>Discover our latest dishes with unique flavors!</p>
      <a href="menu.html">See our menu</a>
    </div>
    <div>
      <h3>Book a Table</h3>
      <img src="table.jpg" alt="Menu img 1" height="200" width="200">
      <p>Reserve your spot to enjoy a delightful dining experience.</p>
      <a href="contact.html">Book now</a>
    </div>
    <div>
      <h3>Opening Hours</h3>
      <img src="open close.jpg" alt="Menu img 1" height="200" width="200">
      <p>Mon: 11pm-10pm<br>   to    <br>Sat: 11pm-10pm</p>
    </div>
  </div>
  <footer>
    Designed   By   SHARON CLARA
  </footer>
 </body>
 </html>
```
admin.html
```
<html>
<head>
    <title>Menu</title>
    <style>
        body {
            width: 100%;    
            background-image: url(bg.jpg);
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
            margin:0; 
            overflow-y: scroll;
        }
        .top{
            align-items: center;
            display: flex;
            justify-content: flex-start;
            flex-direction: column;
            background-color: rgb(224, 224, 152);
            width: 100%;
            
        }
       

        .main {
            
            display: flex; 
            flex-direction: column; 
            align-items: center; 
            justify-content: flex-start;
            position: relative; 
            top: 10px; 
            width: 100%; 
            
        }

        .image {
            width: 200px;
            height: auto; 
        }
        
        .logo {
            font-family: Arial, Helvetica, sans-serif;
            font-size: 150PX;
            color: rgba(25, 19, 85, 0.667); 
            text-align: left;
            margin: 10px 0; 
        }
        .hr{
            width: 100%;
        }
        
        .sub{
            font-family: Arial, Helvetica, sans-serif;
            font-size: 30px;
            margin: auto;
            align-items: center;
            
        }
        .box2{
            font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: aliceblue;
            border: 4px solid rgb(255, 255, 255); 
            padding: 10px;          
            width: 300;
            height: 550px;  
            border-radius: 20px;         
            text-align: justify;
            background-color: rgba(0, 0, 0, 0.522);
            
            
        }
        .box2 a{
            color: aliceblue;
            
        }
        .lowerbox{
            display: flex;
            flex-direction: row;
            justify-content: flex-start;
            padding: 5%;
            gap: 40px;
        }
        .i{
            height:200;
            width: 300;
        }
        .lowerbox2{
            display: flex;
            flex-direction: row;
            justify-content: flex-start;
            gap:40px;
        }
        .i1{
            height: 300px;
            width: 300px;
        }
        
        .start{
            color: aliceblue;
            font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-size: 30px;
            padding: 1px;
            position: absolute;
            top: 30px;
        }
        footer {
      text-align: center;
      padding: 10px;
      background-color: #333;
      color: white;
      position: absolute;
      bottom: 0;
      width: 100%;
    }
        
        
    </style>
</head>
<body>
    <div class="main">
        <div class="top">
            <h2 class="sub">JOSHARAN RESTAURANT</h2>
            <hr class="hr">
        </div>
        <p class="start">Our Team</p>
        <div class="lowerbox">
            
            <div class="box2"> 
                
                <h2>Chef Koushik</h2>
                <p>(Executive Chef)<br></p>
                <img src="CHEF Koushik.jpg" class="i">
                
                <p><br>The Executive Chef is the creative genius 
                    behind the menu. With years of experience in world-class kitchens,
                     they craft dishes that tantalize the taste buds and delight the soul.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Mathampatty Rangaraj</h2>
                <p>(Restaurant Manager)<br></p>
                <img src="chef mathan.jpg" class="i1">
                
                <p><br>As the driving force behind this premium restaurant,Mathampatty Rangaraj  ensures
                     the finest dining experience for guests. </p>
                
            </div>   
            <div class="box2"> 
                
                <h2>Madhampatty Iswarya</h2>
                <p>(Restaurant Supervisor)<br></p>
                <img src="chef iswarya.jpg" class="i">
                
                <p><br>The Restaurant Supervisor is the backbone of daily operations,
                     ensuring the highest standards of service and ambiance. From
                      coordinating staff schedules to maintaining a welcoming environment,
                       they ensure every detail is perfect, reflecting the restaurant's
                        premium reputation.</p>
                
            </div>
                
         </div>
       
        
        
    </div>
    <footer>
        Designed    By     SHARON CLARA
      </footer>
</body>
</html>
```
menu.html
```
<html>
<head>
    <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=0.6">

    <title>Menu</title>
    <style>
        body {
            transform: scale(0.6);
      transform-origin:  center;

            width: 100%;    
            background-image: url(bg.jpg);
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
            margin:0; 
            overflow-y: scroll;
            
        }
        .top{
            align-items: center;
            display: flex;
            justify-content: flex-start;
            flex-direction: column;
            background-color: rgb(224, 224, 152);
            width: 100%;
            
        }
       

        .main {
            
            display: flex; 
            flex-direction: column; 
            align-items: center; 
            justify-content: flex-start; 
            position: relative; 
            top: 10px; 
            width: 100%; 
            
        }

        .image {
            width: 150px; 
            height: auto; 
        }
        
        .logo {
            font-family: Arial, Helvetica, sans-serif;
            font-size: 2rem; 
            color: rgba(25, 19, 85, 0.667); 
            text-align: center;
            margin: 10px 0; 
        }
        .hr{
            width: 500%;
        }
        
        .sub{
            font-family: Arial, Helvetica, sans-serif;
            font-size: 30px;
            margin: auto;
            align-items: center;
            
        }
        .box2{
            font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: aliceblue;
            border: 4px solid rgb(255, 255, 255);
            padding: 10px;         
            width: 300;
            height: 390px;  
            border-radius: 20px;         
            text-align: justify;
            background-color: rgba(0, 0, 0, 0.522);
            
            
        }
        .box2 a{
            color: aliceblue;
            
        }
        .lowerbox{
            display: flex;
            flex-direction: row;
            justify-content: flex-start;
            padding: 5%;
            gap: 40px;
        }
        .i{
            height:200;
            width: 300;
        }
        .lowerbox2{
            display: flex;
            flex-direction: row;
            justify-content: flex-start;
            gap:40px;
        }
        .i1{
            height: 300px;
            width: 300px;
        }
        
        .start{
            color: aliceblue;
            font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-size: 30px;
            padding: 1px;
            position: absolute;
            top:30px;
        }
        footer {
      text-align: center;
      padding: 10px;
      background-color: #333;
      color: white;
      position: absolute;
      bottom: -60px;
      width: 100%;
    }
        
        
    </style>
</head>
<body>
    <div class="main">
        <div class="top">
            <h3 class="sub">JOSHARAN RESTAURANT</h3>
            
            <hr class="hr">
        </div>
        <p class="start">Our Signature Dish</p>
        <div class="lowerbox">
            
            <div class="box2"> 
                
                <h2>Mutton Biriyani</h2>
                
                <img src="biriyani.jpg" class="i">
                
                <p><br>Fragrant basmati rice layered with spiced meat or vegetables.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Prawn Gravy</h2>
               
                <img src="prawn.jpg" class="i">
                
                <p><br>Prawn Curry is an aromatic and flavorful gravy made by cooking prawns with onion, tomato, coconut, herbs and spices.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Bun Parotta</h2>
               
                <img src="parotta.jpg" class="i">
                
                <p><br>Bun Paratha is a beloved South Indian dish that combines the softness of a bun with the flakiness of a paratha to create a unique and indulgent treat.</p>
                
            </div>
        </div>   
        <div class="lowerbox2">
            <div class="box2"> 
                
                <h2>Fish Fry</h2>
                
                <img src="fish.jpg" class="i">
                
                <p><br>Marinated fish is fried in coconut oil and gets a smoky charred flavour from the frying. </p>
                
            </div>
            <div class="box2"> 
                
                <h2>Chicken Pasta</h2>
               
                <img src="pasta.jpg" class="i">
                
                <p><br>Chicken Pasta is made by cooking macaroni pasta with chicken, tempered with spices and loaded with Indian masala flavors. .</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Rasmalai</h2>
                
                <img src="rasa.jpg" class="i">
                
                <p><br>Rasmalai is  made with milk, a curdling agent, sugar, nuts, saffron and cardamoms. .</p>
                
            </div>
         
            
        </div>
        
    </div>
    <footer>
        Designed   By    SHARON CLARA
      </footer>
</body>
</html>
```
contact.html
```
<html>
<head>
    <title>Restaurant</title>
    <style>
        body {
            width: 100%;    
            background-image: url(bg.jpg);
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
            margin:0; 
            overflow-y: scroll;
        }
        .top{
            align-items: center;
            display: flex;
            justify-content: flex-start;
            flex-direction: column;
            background-color: rgb(224, 224, 152);
            width: 100%;
            
        }
        .bottom{
            align-items: center;
            display: flex;
            justify-content: flex-start;
            flex-direction: column;
            background-color: rgba(216, 216, 197, 0.928);
            width: 100%;
        }

        .main {
            
            display: flex; 
            flex-direction: column; 
            align-items: center; 
            justify-content: flex-start; 
            position: relative; 
            top: 10px; 
            width: 100%;
        }

        .image {
            width: 200px; 
            height: auto;
        }
        
        .logo {
            font-family: Arial, Helvetica, sans-serif;
            font-size: 2rem;
            color: rgba(25, 19, 85, 0.667);
            text-align: center; 
            margin: 10px 0;
        }
        .hr{
            width: 100%;
        }
        
        .sub{
            font-family: Arial, Helvetica, sans-serif;
            font-size: 30px;
            margin: auto;
            align-items: center;
            
        }
        .root{
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: rgba(21, 21, 21, 0.47);
            height: 500;
            width: 800;
            font-size: 20;
        }
        footer {
      text-align: center;
      padding: 10px;
      background-color: #333;
      color: white;
      position: absolute;
      bottom: 0;
      width: 100%;
    }
        
        
        
        
    </style>
</head>
<body>
    <div class="main">
        <div class="top">
            <h3 class="sub">JOSHARAN RESTAURANT</h3>
            <hr class="hr">
            
        </div>
    
        <br>
        <br>
        <div class="root">
            <font color="white">
            <p>
                Contact Us<br>
                <br>
                JOSHARAN  RESTAURANT<br>
                <ul><li>Address: 100-E Amirtham Street,Pattukottai-614601</li>
                    <li>Phone: +916379707031</li>
                    <li>Email: contact@josharan.com</li>
                    <li>Website: www.josharan.com</li>
                </ul>
                
                We are here to assist you with reservations, inquiries, and feedback.<br> Feel 
                free to reach out to us during our business hours, and we'll be delighted to 
                serve you.<br> Your satisfaction is our priority!</p>
            </font>
        </div>
        
    </div>
    <footer>
        Designed    By    SHARON CLARA
      </footer>
</body>
</html>

```

## OUTPUT:
![alt text](<Rest 1.jpg>)
![alt text](<Rest 2.jpg>)
![alt text](<Rest 3.jpg>)
![alt text](<Rest 4.jpg>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
