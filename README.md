# Ex.06 Book Front Cover Page Design
## Date: 15-04-2024

## AIM:
To design a book front cover page using HTML and CSS.

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
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <style type="text/css">
            .bookcover {
                width: 400px;
                height: 640px;
                color: rgb(255, 255, 255);   
                margin-left: auto;
                margin-right: auto;
                padding: 18px;
                font-family:Georgia, 'Times New Roman', Times, serif, sans-serif;
                background-image: url(bookcover.jpg);
                background-size: cover;
            }
            .insight {
                color: (221, 39, 39);
            }
            .hr1 {
                width: 130px;
            }
            .h1 {
                font-size: larger;
                font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
                text-align: center;
                position: relative;
                top: 30px;
            }
            .para {
                font-size: medium;
                font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
                position: relative;
                top: 40px;  
            }
            .edition {
                font-size: large;
                font-family: Arial, Helvetica, sans-serif;
                color:rgb(227, 232, 82);
                top: 90px;
                position: relative;
            }
            .pic {
                position: relative;
                top: 120px;
                left: 250px;
                width: 90px;
                height: 80px;
                background-size: cover;
            }
            .hr2 {
                position: relative;
                width: 400px;
                top: 200px;
            }
            .name {
                font-size: medium;
                font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
                display: inline;
                position: relative;
                color:black(94, 218, 32);
                top: 200px;
            }
            .pub {
                font-size: large;
                position: relative;
                top: 165px;
                left: 330px;
            }
        </style>
        <title> Book Front Cover Page  </title>
    </head>
    <body>
        <div class="bookcover">
            <div class="insight">
                EXPERT INSIGHT
            </div>
            <div class="hr1">
                <hr>
            </div>
            <div class="h1">
                <h1> ARTIFICIAL INTELLIGENCE:  A MODERN APPROACH </h1>
            </div>
            <div class="para">
                <p>The most comprehensive, up-to-date introduction to the theory and practice of artificial intelligence</p>
            </div>
            <br>
            <br>
            <br>
            <div class="pic">
                <img src="23013417_page-0001.jpg" width="130" height="145" alt="">
            </div>
            <div class="hr2">
                <hr>
            </div>
            <div class="name">
                <p><b>HARSSHITHA LAKSHMANAN</b></p>
            </div>
            <div class="pub">
                <b> SEC </b>
            </div>
            <div class="edition">
                <b> First Edition </b>
            </div>
        </div>
    </body>
</html>

```

## OUTPUT:

![alt text](<Screenshot 2024-04-16 222428.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
