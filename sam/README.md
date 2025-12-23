# Ex.06 Restaurant Website
## Date:23.12.2025

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
```

Restaurant.html:
<html>
<head>
    <title>PG RESTAURANT</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
<header>
    <h1>PG RESTAURANT</h1>
</header>

<nav>
    <a href="restaurant.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <img src="rest banner.jpg" alt="Restaurant Banner" style="width:80%; max-width:850px; border-radius:14px;">
    <h2>Welcome to PG RESTAURANT</h2>
    <p>authentic south indian cuisine,you can enjoy your food as much</p>
</section>

<footer>
    © created by saigokul.k
</footer>
</body>
</html>

menu.html:
menu.html
<html>
<head>

    <title>PG RESTAURANT - Menu</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
<header>
    <h1>PG RESTAURANT</h1>
</header>

<nav>
    <a href="restaurant.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <h2>Menu</h2>
    <div class="menu-grid">
        <div class="card"><img src="briyani.jpg"><p>chicken briyani-$120</p></div>
        <div class="card"><img src="chicken rice.jpg"><p>chicken rice-$110</p></div>
        <div class="card"><img src="chicken 65.jpg"><p>chicken 65-$150</p></div>
        <div class="card"><img src="meals.jpg"><p>meals-$130</p></div>
        <div class="card"><img src="japan chicken.jpg"><p>japan chicken-$270</p></div>
        <div class="card"><img src="falooda.jpg"><p>falooda-$80</p></div>
        <div class="card"><img src="rasamalai.jpg"><p>rasamalai-$40</p></div>
        
    </div>
</section>

<footer>
    © created by saigokul.k
</footer>
</body>
</html>

admin.hhtml:
<html>
<head>
    <title>PG RESTAURANT - Admin</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
<header>
    <h1>PG RESTAURANT</h1>
</header>

<nav>
    <a href="restaurant.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <h2>our respective admins</h2>
    <div class="team-grid">
        <div class="card"><img src="img 1.png.jpeg"><p> Saigokul - owner</p></div>
        <div class="card"><img src="carlos.jpg"><p>Roberto Carlos - ceo</p></div>
        <div class="card"><img src="db.png"><P>David Beckam - manager</P></div>
        <div class="card"><img src="ney.png"><P>Neymar jr - managing director</P></div>
        <div class="card"><img src="ronaldo.png"><P>cristiano ronaldo - incharge</P></div>
        <div class="card"><img src="messi.png"><P>lionel messi - visitors incharge</P></div>
    </div>
</section>

<footer>
    © created by saigokul.k
</footer>
</body>
</html>

contact.html:
<html>
<head>

    <title>PG RESTAURANT - contact us for queries</title>
    <link rel="stylesheet" href="style.css">
    
        
        
</head>
<body>

<header>
    <h1>PG RESTAURANT</h1>
</header>

<nav>
    <a href="restaurant.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <div class="container">
        <h2>Contact us for queries</h2>
        <p><b>Address:</b> No.777,Anna Road, kanchipuram,Tamil Nadu 600002</p>
        <p><b>Phone:</b> +91 9578040217</p>
        <p><b>Email:</b> contact:nalinisaigokul@gmail.com</p>
        <p><b>Opening Hours:</b> Mon-Sun: 9:00 AM - 11:00 PM</p>
    </div>
</section>

<footer>
    <div class="foot">
    <p>© created by saigokul.k</p>
    </div>
</footer>

</body>
</html>

style.css:
body {
    font-family: italic, serif;
    margin: 0;
    background-color: lightcyan;
    color: red;
    background-image: url(background.png);
    background-size: cover;
    
}
header {
    background-color: cornsilk;
    color: blue;
    padding: 25px;
    text-align: center;
}
nav {
    background-color: palegreen;
    text-align: center;
}
nav a {
    color: white;
    text-decoration: none;
    margin: 0 17px;
    padding: 9px;
    display: inline-block;
}
nav a:hover {
    background-color: ghostwhite;
    color: darkcyan;
}
section {
    padding: 30px;
    text-align: center;
}
h2 {
    color: white;
    font-style:oblique;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    
}
.menu-grid, .team-grid {
    display: grid;
    grid-template-columns: repeat(3, 2fr);
    gap: 22px;
    max-width: 1010px;
    margin: 24px auto;
    text-align: center;
}
.card {
    background-color: lavender;
    padding: 17px;
    border-radius: 12px;
    box-shadow: 0 5px 10px rgba(0,0,0,0.1);
    font-style: arial;
    color: fuchsia;
    text-shadow: rosybrown;
}
.card img {
    width: 70px;
    height: 105px;
    object-fit: cover;
    border-radius: 28px;
    align-items: center;
    border: deeppink;    
    
}
footer {
    background-color: yellow ;
    color: black;
    
    text-align: center;
    padding: 17px;
    
}
footer p {
    margin-bottom: 2px;
    margin-top: 4px;
    padding-bottom: 0%;


}
.container {
            height: max-content;
            max-width: 809px;
            margin: 0 auto;
            text-align: left;
            padding: 22px;
            background-color: lightgreen;
            border-radius: 16px;
            box-shadow: 0 3px 6px rgba(0,0,0,0.1);
        }
        .container h2 {
            text-align: center;
            color: darkorchid;
        }
        .container p {
            font-size: 19px;
            margin: 12px 0;
        }
        .contact b {
            color: bisque;
        }

 ```       




## OUTPUT:
![alt text](<Screenshot (44).png>)
![alt text](<Screenshot (45).png>)
![alt text](<Screenshot (46).png>)
![alt text](<Screenshot (47).png>) 
![alt text](<Screenshot (48).png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
