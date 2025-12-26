# Ex.07 Restaurant Website
# Date:9/12/2025
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
home.html
<!DOCTYPE html>
<html>
    <head>
        <title>Homepage</title>
        <link href="home.css" rel="stylesheet">
    </head>

    <body>
        <nav>
            <div class="pages">
                <a href="home.html">Home</a>
                <a href="menu.html">Menu</a>
                <a href="admin.html">Admin</a>
                <a href="cont.html">Contact Us</a>
            </div>
        </nav>

        <div class="name">
            <h1>Zaffran Rajputana</h1>
        </div>

        <div class="about">
            “Zaffran — where royal flavors meet timeless tradition.”
        </div>

        <div class="quote">
            “Zaffran — where royal flavors meet timeless tradition.”Zaffran Restaurant offers a royal dining experience inspired by rich Rajasthani flavors and timeless Indian spices. Every dish is crafted to reflect heritage, elegance, and authentic taste.
        </div>

        <img src="download (3).jpg" class="resto">
        <img src="1135 AD at Amer Fort, Jaipur, Rajasthan, India.jpg" class="resto2">
        
        <footer>
            Copyright &copy HIMADRI (25011498)
        </footer>
    </body>
</html>


home.css
body
{
    background: url('download (4).jpg') no-repeat top / cover;
    background-color: rgb(159, 206, 202);
}
nav 
{
    background-color:rgb(9, 28, 36);
    padding: 10px 90px;
    position:fixed;
    left:0;
    top:0;
    width:100%;
}
nav a 
{
    color:white;
    text-decoration: none;
    margin:20px;
    font-size:22px;
}
nav a:hover 
{
    color: rgb(193, 148, 45);
}

.name
{
    font-size:45px;
    color:rgb(9, 28, 36);
    position:absolute;
    left:100px;
    top:20px;
    text-decoration: underline rgb(193, 148, 45);

}

.about
{
   font-style: italic;
   position:absolute;
   color:rgb(214, 166, 53);
   background-color:rgb(9, 28, 36) ;
   text-align: center;
   width:500px;
   font-size:26;
   left:190px;
   top:190px; 
}

.quote
{
   position:absolute;
   color:rgb(9, 28, 36);
   text-decoration:overline underline rgb(9, 28, 36) 4px;
   text-align:left;
   font-size:25;
   font-weight: bold;
   left:70px;
   top:290px; 
   width:660px;
}

.resto
{
    border: solid 7px rgb(9, 28, 36);
    border-radius: 3px;
    width:450px;
    height:280px;
    position:absolute;
    left:70px;
    bottom:70px;
}
.resto2 
{
    border: solid 7px rgb(9, 28, 36);
    border-radius: 3px;
    width:300px;
    height: 280px;
    position:absolute;
    left: 550px;
    bottom:70px;
}

footer
{
    left:0;
    bottom:0;
    position:fixed;
    background:rgb(9, 28, 36);
    color:white;
    width:100%;
    font-size:18;
    text-align:center;
}
```
```
menu.html
<html>
    <head>
        <title>Menu</title>
        <link href="menu.css" rel="stylesheet">
    </head>
    <body>
        <div class="about">
            <h1>Our Menu</h1>
            <p>Enjoy the wide variety of dishes offered</p>
        </div>

        <nav>
            <div class="pages">
                <a href="home.html">Home</a>
                <a href="menu.html">Menu</a>
                <a href="admin.html">Admin</a>
                <a href="cont.html">Contact Us</a>
            </div>
        </nav>

        <div class="container">
            <div class="menu">
                <div class="item">
                    <img src="download (5).jpg">
                    <div class="desc">
                        <h3>Daal baati churma</h3>
                        <p>crispy, ghee-rich baati with mildly spiced dal, paired with sweet, crumbly churma.</p>
                        <p class="price">Rs.1500</p>
                    </div>
                </div>


                <div class="item">
                    <img src="Shahi Tukda With Rabdi - Aarti Madan.jpg">
                    <div class="desc">
                        <h3>Malupa</h3>
                        <p>Sweet, soft, and rich with a ghee-soaked, melt-in-the-mouth taste.</p>
                        <p class="price">Rs.459</p>
                    </div>
                </div>

            
                <div class="item">
                    <img src="ghevar.jpg">
                    <div class="desc">
                        <h3>malai ghevar</h3>
                        <p>Malai Ghevar has a rich, melt-in-the-mouth taste with a perfect blend of crisp honeycomb texture, creamy malai, and delicate sweetness</p>
                        <p class="price">Rs.1000</p>
                    </div>
                </div>

            
                <div class="item">
                    <img src="Mirchi Bajji Recipe_ The Ultimate Street Snack from South India - Binjal's VEG Kitchen.jpg">
                    <div class="desc">
                        <h3>Mirchi vada</h3>
                        <p>Spicy, crispy, and flavorful with a perfect balance of heat and crunch.</p>
                        <p class="price">Rs.159</p>
                    </div>
                </div>
            </div>
        </div>
        
        <footer>
            Copyright &copy Himadri S (25011498)
        </footer>
    </body>
</html>


menu.css
body
{
    background: url('menu.png') no-repeat top / contain;
    background-color: rgb(38, 75, 75);
}
nav 
{
    background-color:rgb(9, 28, 36);
    padding: 10px 90px;
    position:fixed;
    left:0;
    top:0;
    width:100%;
}
nav a 
{
    color:white;
    text-decoration: none;
    margin:20px;
    font-size:22px;
}
nav a:hover 
{
    color: rgb(193, 148, 45);
}

.about h1
{
    position:absolute;
    color: rgb(214, 186, 29);
    text-decoration: overline underline rgb(192, 168, 35);
    top:70px;
    left:680px;
    font-size: 40px;
    background-color:rgb(9, 28, 36) ;
}
.about p
{
    position: relative;
    color:rgb(192, 168, 35);
    top:150px;
    font-size:24px;
    font-weight: bold;
    background-color: rgb(9, 28, 36);
    width:max-content;
    left: 550px;
    justify-content: center;
}

.container 
{
    position: relative;
    margin: 20px 115px;
    padding: 20px;
    top: 140px;
}
.menu
{
    display: flex;
    gap:30px;
}
.item 
{
    background-color: rgb(231, 217, 158);
    border-radius:10px;
    width:290px;
    border:solid transparent 3px;
}
.item:hover 
{
    border:solid rgb(199, 148, 30) 3px;
    outline:solid rgb(9, 28, 36) 5px;
}
.item img 
{
    width: 100%;
    height: 200px;
    object-fit:cover;
    border-radius: 8px;
}
.desc 
{
    padding:15px;
    text-align: center;
}
.desc h3 
{
    margin: 10px 0;
    font-size:24px;
    color: rgb(9, 28, 36);
}
.desc p 
{
    margin: 5px 0;
    font-size: 17.5px;
    color: rgb(15, 43, 55);
}
.desc .price 
{
    font-size: 22px;
    color: rgb(181, 2, 2);
    font-weight:bold;
}

footer
{
    left:0;
    bottom:0;
    position:fixed;
    background:rgb(9, 28, 36);
    color:white;
    width:100%;
    font-size:18;
    text-align:center; 
}
```
```
admin.html
<html>
    <head>
        <title>Administration</title>
        <link href="admin.css" rel="stylesheet">
    </head>
    <body>
        <div class="about">
            <h1>Administration team</h1>
        </div>
        <nav>
            <div class="pages">
                <a href="home.html">Home</a>
                <a href="menu.html">Menu</a>
                <a href="admin.html">Admin</a>
                <a href="cont.html">Contact Us</a>
            </div>
        </nav>

        <div class="container">
            <div class="team">
                <div class="staff">
                    <img src="madhav ji.jpg">
                    <div class="desc">
                        <h3>madhav singh</h3>
                        <p class="post">Owner</p>
                    </div>
                </div>

                <div class="staff">
                    <img src="padman singh ji.jpg">
                    <div class="desc">
                        <h3>padmanabh singh </h3>
                        <p class="post">General Manager</p>
                    </div>
                </div>

                <div class="staff">
                    <img src="ishaan khatter.webp">
                    <div class="desc">
                        <h3>ishaa khatter</h3>
                        <p class="post">Head chef</p>
                    </div>
                </div>

                <div class="staff">
                    <img src="shahid kapoor.jpg">
                    <div class="desc">
                        <h3>shahid kapoor</h3>
                        <p class="post">Sous Chef</p>
                    </div>
                </div>

            
                <div class="staff">
                    <img src="ranveer singh.webp">
                    <div class="desc">
                        <h3>ranveer singh</h3>
                        <p class="post">Head Server</p>
                    </div>
                </div>

            
                <div class="staff">
                    <img src="lakshaysingh.jpg">
                    <div class="desc">
                        <h3>lakshayraj singh</h3>
                        <p class="post">HR Manager</p>
                    </div>
                </div>
            </div>
        </div>

        <footer>
            Copyright &copy Himadri S (25011498)
        </footer>
    </body>
</html>


admin.css
body
{
    background: url('rename.png') no-repeat top / contain;
    background-color: rgb(38, 75, 75);
}
nav 
{
    background-color:rgb(9, 28, 36);
    padding: 10px 90px;
    position:fixed;
    left:0;
    top:0;
    width:100%;
}
nav a 
{
    color:white;
    text-decoration: none;
    margin:20px;
    font-size:22px;
}
nav a:hover 
{
    color: rgb(193, 148, 45);
}

.about h1
{
    position:absolute;
    color: rgb(214, 186, 29);
    text-decoration: overline underline rgb(192, 168, 35);
    top:70px;
    left:590px;
    font-size: 40px;
    background-color:rgb(9, 28, 36);
    width:fit-content;
}

.container 
{
    position: relative;
    margin: 20px 90px;
    padding: 20px;
    top: 140px;
}
.team
{
    display: flex;
    gap:30px;
}
.staff 
{
    background-color: rgb(231, 217, 158);
    border-radius:10px;
    width:290px;
    border:solid transparent 3px;
}
.staff:hover 
{
    border:solid rgb(199, 148, 30) 3px;
    outline:solid rgb(9, 28, 36) 5px;
}
.staff img 
{
    width: 100%;
    height: 250px;
    object-fit:cover;
    border-radius: 8px;
}
.desc 
{
    padding:10px;
    text-align: center;
}
.desc h3 
{
    margin: 10px 0;
    font-size:24px;
    color: rgb(9, 28, 36);
}
.desc p 
{
    margin: 5px 0;
    font-size: 17.5px;
    color: rgb(15, 43, 55);
}
.desc .post
{
    font-size: 22px;
    color: rgb(181, 2, 2);
    font-weight:bold;
}

footer
{
    left:0;
    bottom:0;
    position:fixed;
    background:rgb(9, 28, 36);
    color:white;
    width:100%;
    font-size:18;
    text-align:center; 
}
```
```
conatact.html
<html>
    <head>
        <title>Contact page</title>
        <link href="contact.css" rel="stylesheet">
    </head>
    <body>
        <nav>
            <div class="pages">
                <a href="home.html">Home</a>
                <a href="menu.html">Menu</a>
                <a href="admin.html">Admin</a>
                <a href="cont.html">Contact Us</a>
            </div>
        </nav>

        <div class="contact">
            <h1>CONTACT US</h1>
        </div>

        <div class="visit">
            <h3>Visit Us:</h3>
            <h4>
                Zaffran rajputana,<br>
                123,udaipur Town,<br>
                rajasthan-6001,<br>
                India
            </h4>
        </div>

        <div class="reach">
            <h3>Reach out at:</h3>
            <h4>Phone: +91 xxx xxx xxxx</h2>
            <h4>Email: Zaffran@gmail.com</h4>

        </div>
        
        <div class="about">
            Feel free to contact us about your reservations and other queries!
        </div>

        <footer>
            Copyright &copy Himadri s (25011498)
        </footer>
    </body>
</html>


contact.css
ody
{
    background: url('zafran-new-logo.webp') no-repeat top / cover;
    background-color: rgb(22, 70, 73);
}
nav 
{
    background-color:rgb(9, 28, 36);
    padding: 10px 90px;
    position:fixed;
    left:0;
    top:0;
    width:100%;
}
nav a 
{
    color:white;
    text-decoration: none;
    margin:20px;
    font-size:22px;
}
nav a:hover 
{
    color: rgb(193, 148, 45);
}

.contact
{
    font-size:40px;
    color:rgb(9, 28, 36);
    position:absolute;
    left:500px;
    top:20px;
    text-decoration:overline underline rgb(9, 28, 36);
}
.visit
{
    position:absolute;
    margin:180px auto;
    padding:5px;
    left:450px;
    right:780px;
    background-color: rgba(159, 206, 202, 0.701);
    border-radius: 50px;
    text-align: center;
    border:outset rgb(146, 38, 30) 7px;
    bottom:70px;
    top:5px;

}
h3
{
    font-size: 40px;
    text-decoration:underline rgb(193, 148, 45);
}
h4
{
    font-size: 24px;
    color:rgb(193, 148, 45);
    background-color: rgb(9, 28, 36);
    border-radius: 100px;
}
.reach
{
    position:absolute;
    margin:180px auto;
    padding:5px;
    right:450px;
    left:780px;
    background-color: rgb(159, 206, 202, 0.701);
    border-radius: 50px;
    text-align: center;
    border:outset rgb(146, 38, 30) 7px;
    bottom:70px;
    top:5px;
}
.about
{
    font-size:24px;
    color:rgb(193, 148, 45);
    position:absolute;
    left:425px;
    bottom:180px;
    font-weight: bold;
    text-decoration:underline rgb(193, 148, 45);
    background-color:  rgb(9, 28, 36);
    border:solid  rgb(9, 28, 36) 10px;
    border-radius: 30px;
}

footer
{
    left:0;
    bottom:0;
    position:fixed;
    background:rgb(9, 28, 36);
    color:white;
    width:100%;
    font-size:18;
    text-align:center; 
}
```

# OUTPUT:
![alt text](<Screenshot 2025-12-26 163147.png>)
![alt text](<Screenshot 2025-12-26 163207.png>)
![alt text](<Screenshot 2025-12-26 163711.png>)
![alt text](<Screenshot 2025-12-26 163619.png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
