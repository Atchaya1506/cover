# Ex.06 Book Front Cover Page Design
## Date:3/12/2024

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
<!DOCTYPE html>
<html>

<head>
    <title>Book cover</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image: url("BG 2.jpg");
            background-size: cover;
        }
            
        
        .insight{
            color:rgb(24, 234, 234);
            font-family: Trebuchet MS;
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(31, 175, 223);
            top:170px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(19, 222, 222);
            font-family: 'Times New Roman', Times, serif;
            font-size: larger;
            text-align: left;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            color:rgb(21, 226, 226);
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:rgb(4, 147, 95);
            font-size: medium;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            position:relative;
            bottom:200px;
        
        }
        .subtitle{
            color:rgb(14, 220, 220);
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .sub{
            color:rgb(25, 245, 245);
            font-family:Arial, Helvetica, sans-serif;
            font-size: large;
            position: relative;
            top:340px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        .lpic{
            position: relative;
            bottom: 100px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                THE WEBBERS!
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(71, 88, 93)">
            </div>
            <div class="booktitle">
                <h1 style="font-family: 'Times New Roman', Times, serif; color:rgb(189, 229, 126);">WEB WITH HTML AND CSS</h1></div>
            <div class="subtitle" style="text-align: left;color: rgb(189, 229, 126);">
                 EASY STEPS TO BUILT YOUR OWN WEBSITE
            </div>
            <div class="subtitle" style="color: rgb(106, 225, 21);text-align: left;">
                 CREATE YOUR OWN DESIGN

            </div>
            <div class="sub" style="color: rgb(8, 144, 56);text-align: left;">
                IF YOU THINK MATH IS HARD TRY WEB DESIGN
           </div>

            <div class="mypic">
                <img src="pic.jpg" width="100" height="100" >
            </div>
            <div class="id">
                <hr style="color:rgb(255, 211, 205)">
            </div>
            <div class="author">
               <p><b>ATCHAYA B</b></p>
            </div>
            <div class="ed">
                <b>REVISED EDITION 3</b>
            </div>
        </div>
        </body>    

</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-12-03 084747-1.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
