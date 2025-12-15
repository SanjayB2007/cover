# Ex.05 Book Cover Page Design
## Date:15-12-2025

## AIM:
To design a book back cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
cover.html
html>
<head>
    <title>Book Cover</title>
    <link href="styles.css" rel="stylesheet">
</head>

<body>

<div class="box">
    <h2>About the Book</h2>
    <hr>

    <p>
        
       This book <b> The Internet of Things (IoT)</b> to a network of physical objects that are embedded with sensors, software, and network connectivity, allowing them to collect and share data. This interconnectedness enables devices to communicate with each other and with humans, transforming industries and daily life. IoT devices can range from simple smart home appliances to complex industrial machinery, and they are used in various applications, including health monitoring, transportation, and manufacturing. 
ITS The Education Group

    </p>

    <div class="quote">
       "The IoT is not a concept; it is a network, the true technology-enabled network of all networks."
    </div>

    
    <div class="author">
        <img src="img3.jpg" alt="Author Photo">

        <p>
            <b>SANJAY BABU (25003400))</b><br>
            <br>
             a student of Saveetha Engineering College and studying B.E in CSE department 1st year.
            

        </p>
    </div>

    <div class="footer">
        <div>Saveetha Publishers<br>Printed in India</div>
        <div><b>Price: Rs.999</b></div>
    </div>

</div>

</body>
</html>

style.css
body
{
    font-size: Arial;
    background:linear-gradient(to bottom,rgb(255, 179, 98),rgb(249, 159, 254));
}
b{
    color: aquamarine;
}
.box {
    height: 700px;
    width: 500px;
    background-image:url(img2.jpg);
    background-size: cover;
    color:white;
    padding: 20px;
    margin: 30px auto;
    border: 2px solid rgb(84, 0, 0);
    border-radius: 10px;
    }
.quote {
        background: rgba(7, 105, 103, 0.292);
        padding: 10px;
        border-left: 4px solid blue;
        margin: 20px 0;
        font-style: italic;
        text-align: center;
        border-end-end-radius: 10px;
        }
.author {
        display: flex;
        gap: 15px;
        background:rgb(167, 30, 123);
        padding: 10px;
        border-start-end-radius: 8px;
        }
.author b{
        color:rgba(30, 219, 96, 0.575);
        }
.author img {
        width: 100px;
        height: 100px;
        border-radius: 5px;
        }
.footer {
        background: grey;
        color: rgb(255, 0, 0);
        padding: 10px;
        display: flex;
        justify-content: space-between;
        margin-top: 150px;
        border-end-end-radius: 5px;
        }
```

## OUTPUT:
![alt text](<Screenshot (24).png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
