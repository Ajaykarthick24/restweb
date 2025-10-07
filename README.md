# Ex.07 Restaurant Website
## Date:07/10/25

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
home.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Quick Bites | Home</title>
  <link rel="stylesheet" href="home.css">
</head>
<body>
  <header>
    <h1>Quick Bites</h1>
    <p class="tagline">"Tasty and Modern"</p>

    
    <nav>
      <ul>
        <li><a href="home.html" class="active">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="home">
    
    <h2></color>Welcome to The Quick Bites</h2>
    <p>"Bite-sized joy" and "Savor every moment, one bite at a time".</p>
    <img src=Res.jpeg>
  </section>

  <footer>
    <p>© 2025 Quick Bites  | Designed by <strong>Ajay Karthick M (25010418)</strong></p>
  </footer>
</body>
</html>

home.css

body {
  background-image: url('back.jpeg');
  font-family: Arial, sans-serif;
  background-color: black;
  color: white;
  margin: 0;
  text-align: center;
}

header {
  background-color: darkorchid;
  padding: 20px;
  border-bottom: 3px solid greenyellow;
}
.tagline {
    position: relative;
  color: khaki;
  font-size: 16px;
  margin-top: 5px;
  font-style: heart;
  letter-spacing: 1px;
  right:30%;
}

h1 {
    position:relative;
  color: greenyellow;
  right:30%;
  top:20%;
}

nav ul {
  list-style: none;
  padding: 0;
  margin-top: 10px;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
  position: relative;
  left:30%;
  
}

nav a.active,
nav a:hover {
  color: greenyellow;
  position: relative;
  left:30%;
}


.home {
  padding: 40px;
}

.home img {
  width: 300px;
  border-radius: 10px;
  margin-top: 20px;
  border: 3px solid greenyellow;
}

footer {
  background-color: whitesmoke;
  color: gray;
  padding: 15px;
  border-top: 2px solid greenyellow;
}

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu | awesome  Dishes</title>
  <link rel="stylesheet" href="menu.css">
</head>
<body>
  <header>
    <h1>OUR AWESOME MENU</h1>
    <nav>
      <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="menu.html" class="active">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="menu">
    <h2>Dishes</h2>
    <div class="menu-items">
      <div class="item"><img src="ChickenBiryani.jpeg"><p>Chicken Biriyani - Rs.180</p></div>
      <div class="item"><img src="CrispyChicken.jpeg"><p>Crispy Chicken- Rs.399</p></div>
      <div class="item"><img src="Dumpling__Momo.jpeg"><p>momos- Rs.100</p></div>
      <div class="item"><img src="Fish_roll.jpeg "><p>Fish Roll - Rs.80</p></div>
      <div class="item"><img src="Hot_ramen_noodles 🍜.jpeg"><p>Ramen Noodles - Rs.250</p></div>
      <div class="item"><img src="sandwich 🍔.jpeg"><p>Sandwich- Rs.80</p></div>
    </div>
  </section>

  <footer>
    <p>© Quick Bites | Designed By <strong>Ajay Karthick (25010418)<strong></p>
  </footer> 
</body>
</html>

menu.css

body {
  font-family: Arial, sans-serif;
  background-color: #111;
  color: white;
  margin: 0;
  text-align: center;
}

header {
  background-color: black;
  padding: 20px;
  border-bottom: 3px solid royalblue;
}

h1 {
  color: royalblue;
  margin: 0;
}

nav ul {
  list-style: none;
  padding: 0;
  margin-top: 10px;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav a {
  color: blanchedalmond;
  text-decoration: none;
  font-weight: bold;
}

nav a.active,
nav a:hover {
  color: royalblue;
}

.menu {
  padding: 40px;
}

.menu-items {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 20px;
}

.item {
  background-color: indianred;
  border: 2px solid royalblue;
  border-radius: 10px;
  padding: 10px;
  width: 200px;
}

.item img {
  width: 100%;
  border-radius: 8px;
}

footer {
  background-color: olive;
  color: lawngreen;
  padding: 15px;
  border-top: 2px solid royalblue;
}

admin.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Administration Team</title>
    <link rel="stylesheet" href="admin.css">
</head>
<body>
    <header>
        <h1>Our Administration Team</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="admin.html" class="active">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <h2>Meet Our Team</h2>

        <div class="team">
            <div class="member">
                <img src="ajay.jpg" alt="Ajay Karthick M">
                <h3>Ajay Karthick M</h3>
                <p>CEO</p>
            </div>

            <div class="member">
                <img src="man1.jpeg" alt="sam">
                <h3>Sam</h3>
                <p>COO</p>
            </div>

            <div class="member">
                <img src="man2.jpeg" alt="Vignesh">
                <h3>Vignesh</h3>
                <p>Executive Manager</p>
            </div>

            <div class="member">
                <img src="man5.jpeg" alt="Ramesh">
                <h3>Ramesh</h3>
                <p>HR Manager</p>
            </div>

            <div class="member">
                <img src="man4.jpeg" alt="Arivu">
                <h3>Arivu</h3>
                <p>Executive Chef</p>
            </div>

            <div class="member">
                <img src="man3.jpeg" alt="Peter">
                <h3>Peter</h3>
                <p>Customer Service Manager</p>
            </div>
        </div>
    </main>

    <footer>
        <p>© 2025 Quick Bites | Designed by <strong>Ajay Karthick M (25010418)</strong></p>
    </footer>
</body>
</html>


admin.css
 body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background-color: #fff;
}

/* Header */
header {
    background-color: orangered;
    color: palegreen;
    text-align: center;
    padding: 20px 0;
}

header h1 {
    margin: 0;
    font-size: 2em;
    font-weight: bold;
}

nav ul {
    list-style-type: none;
    padding: 0;
    margin: 10px 0 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: firebrick;
    font-weight: 600;
}

nav ul li a.active {
    text-decoration: underline;
}

/* Main Section */
main {
    text-align: center;
    padding: 40px 20px;
}

main h2 {
    color: sandybrown;
    font-size: 1.8em;
    margin-bottom: 40px;
}

/* Team Cards */
.team {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 25px;
}

.member {
    background-color: gold;
    color: silver;
    border-radius: 12px;
    width: 150px;
    padding: 20px;
    transition: transform 0.3s;
}

.member:hover {
    transform: translateY(-8px);
}

.member img {
    width: 80%;
    height: 230px;
    object-fit: cover;
    border-radius: 50%;
    border: 4px solid hotpink;
}

.member h3 {
    margin-top: 15px;
    color: skyblue;
    font-size: 1.2em;
}

.member p {
    color: black;
    font-weight: 500;
}

/* Footer */
footer {
    background-color: olive;
    color: white;
    text-align: center;
    padding: 10px;
    font-size: 0.9em;
}

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact | Quick Bites </title>
  <link rel="stylesheet" href="contact.css">
</head>
<body>
  <header>
    <h1>CONTACT US</h1>
    <nav>
      <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html" class="active">Contact Us</a></li>
      </ul>
    </nav>
  </header>
  
   
  <section class="contact">
    <h2>Contact Us</h2>
    <p>📍 North 2nd street,Pudukkottai,Tamil Nadu, India</p>
    <p>📞 7272454545 </p>
    <p>✉️ quickbites@gmail.com</p>
  </section>

  <footer>
    <p>© Quick Bites Feal the taste of bites <strong>Ajay karthick (25010418)</strong></p>
  </footer>
</body>
</html>

contact.css

body {
  font-family: Arial, sans-serif;
  background-color: darkblue;
  color: bisque;
  margin: 0;
  text-align: center;
}

header {
  background-color: darkblue;
  padding: 20px;
  border-bottom: 3px solid orchid;
}

h1 {
  color: orchid;
  margin: 0;
}

nav ul {
  list-style: none;
  padding: 0;
  margin-top: 10px;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

nav a.active,
nav a:hover {
  color: orchid;
}

.contact {
  padding: 50px;
}


footer {
  background-color: darkblue;
  color: #aaa;
  padding: 15px;
  border-top: 2px solid orchid;
}


```


## OUTPUT:

![alt text](<Screenshot 2025-10-07 223838.png>)
![alt text](<Screenshot 2025-10-07 223859.png>)
![alt text](<Screenshot 2025-10-07 223911.png>)
![alt text](<Screenshot 2025-10-07 223927.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
