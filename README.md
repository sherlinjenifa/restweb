# Ex.06 Complex Problem: Restaurant Website
## Date:02-04-2026

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
Publish the website in Localhost.

## PROGRAM:
```
home.html


<html>
    <head>
        <title>Contact</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <style>
        body{
            background-color: brown;
            background-size:cover;
            background-position:center;
            color:white;
            padding:fixed;
            margin:0;
            bottom:0;
            box-sizing:border-box;
            font-family:Arial;
        }
        .type{
            width: 1510px;
            margin-left: 0%;
            padding:20px;
            background-color:rgb(226, 218, 218);
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            position: relative;
            font-weight: bold;
            word-spacing: 80px;
            text-decoration: none;
        }
        footer{
            text-align:center;
            padding:10px;
            background: white;
            color: black;
            position:fixed;
            bottom:0;
            width:100%;
        }
        
    </style>
    <body>
        <nav>
        <div class="type">
            <a href="home.html" title="HOME" target="_blank">HOME</a>
            <a href="admin.html" title="ADMIN" target="_blank">ADMIN</a>
            <a href="contact.html" title="CONTACT" target="_blank">CONTACT</a>
        </div>
        </nav>
        <h1 class="main-title">CONTACT</h1>
        <div class="contact-box">
            <h2>Opens</h2>
            <p>
                PLATE AND EAT RESTAURANT
                <br>
                Kanniyakumari
                <br>
                Pincode : 629153
                <br>
                India
            </p>
            <br>
            <h2>Phone:</h2>
            <p>+91 0090090909</p>
            <br>
            <h2>Email ID:</h2>
            <p>sherlinjenifa@gmail.com</p>
        </div>
        <footer>Designed by SHERLIN JENIFA VS (25017634)1</footer>
    </body>
</html>

admin.html

<html>
    <head>
        <title>Admin</title>
     <link rel="stylesheet" href="admin.html">
    </head>

    <style>
        .restbg{
            background-color: brown;
            width: 1550px;
            height: 735px;
            background-size: cover;
        }
        .type{
            width: 1510px;
            margin-left: 0%;
            padding:20px;
            background-color:rgb(226, 218, 218);
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            position: relative;
            font-weight: bold;
            word-spacing: 80px;
            text-decoration: none;
        }
        .title{
            color:black;
            background-color: rgb(226, 218, 218);
            width: 41cm;
            font-family:Georgia, 'Times New Roman', Times, serif;
            text-align:center;
            position: relative;
            font-size:300%;
            margin-top:0.5cm;
            border-radius: 30px 0px 30px 0px;
        }
        .grid{
            display: grid ;
            grid-template-columns: repeat(auto-fit, minmax(10px, 1fr));
            gap: 20px;
            justify-items: center;
            padding: 20px;
            margin-top: 1cm;
        }
        .admin{
            background-color:rgb(226, 218, 218);
            border-radius: 30px;
            text-align: center;
            padding: 20px;
            width: 70%;
        }
        .admin img{
            border-radius: 15px;
            width: 100%;
            height: 300px;
            object-fit: cover;
        }
        h2{
            font-size:x-large;
            color: black;
            margin-top:0.2cm;
        }
        h1 {
            font-size:medium;
            color: black;
            margin-top: 10px;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        p {
            color: black;
            margin-top:0.01cm;
            font-size: x-small;
        }
        footer{
            width: 1550px;
            height: 40px;
            background-color:rgb(226, 218, 218);
            text-align: center;
            margin-top:2cm;
            position: relative
        }
    </style>
    
    
     <body>
        <div class="restbg">
            <div class="type">
                <a href="home.html" title="HOME" target="_blank">HOME</a>
                <a href="admin.html" title="ADMIN" target="_blank">ADMIN</a>
                <a href="contact.html" title="CONTACT" target="_blank">CONTACT</a>
            </div>
            <div class="title">ADMINISTRATION GUIDES</div>
        <div class="grid">
            <div class="admin">
                <img src="bheem.png">
                <h2>Chota bheem</h2>
                <h1>Coordiator</h1>
            </div>
            <div class="admin">
                <img src="chutki.png">
                <h2>Chutki</h2>
                <h1>Quality Analyzer</h1>
            </div>
            <div class="admin">
                <img src="raju.png">
                <h2>Raju</h2>
                <h1>Manager</h1>
            </div>
            <div class="admin">
                <img src="jaggu.png">
                <h2>Jaggu</h2>
                <h1>Head</h1>
            </div>
             <div class="admin">
                <img src="me.png">
                <h2>Sherlin Jenifa VS</h2>
                <h1>Founder</h1>
        </div>
         </div>
         <footer>Designed by SHERLIN JENIFA VS (25017634)</footer>
        </div>

     </body>
     
</html>

contact.html


<html>
    <head>
        <title>Contact</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <style>
        body{
            background-color: brown;
            background-size:cover;
            background-position:center;
            color:white;
            padding:fixed;
            margin:0;
            bottom:0;
            box-sizing:border-box;
            font-family:Arial;
        }
        .type{
            width: 1510px;
            margin-left: 0%;
            padding:20px;
            background-color:rgb(226, 218, 218);
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            position: relative;
            font-weight: bold;
            word-spacing: 80px;
            text-decoration: none;
        }
        footer{
            text-align:center;
            padding:10px;
            background: white;
            color: black;
            position:fixed;
            bottom:0;
            width:100%;
        }
        
    </style>
    <body>
        <nav>
        <div class="type">
            <a href="home.html" title="HOME" target="_blank">HOME</a>
            <a href="admin.html" title="ADMIN" target="_blank">ADMIN</a>
            <a href="contact.html" title="CONTACT" target="_blank">CONTACT</a>
        </div>
        </nav>
        <h1 class="main-title">CONTACT</h1>
        <div class="contact-box">
            <h2>Opens</h2>
            <p>
                PLATE AND EAT RESTAURANT
                <br>
                Kanniyakumari
                <br>
                Pincode : 629153
                <br>
                India
            </p>
            <br>
            <h2>Phone:</h2>
            <p>+91 0090090909</p>
            <br>
            <h2>Email ID:</h2>
            <p>sherlinjenifa@gmail.com</p>
        </div>
        <footer>Designed by SHERLIN JENIFA VS (25017634)1</footer>
    </body>
</html>


```


## OUTPUT:

![alt text](<Screenshot (101).png>)
![alt text](<Screenshot (102).png>)
![alt text](<Screenshot (103).png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
