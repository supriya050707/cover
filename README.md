# Ex.06 Book Front Cover Page Design
## Date:9/5/2025

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
            height: 650px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image:"cover.jpeg";
            background-size: cover;
        }
            
        
        
        
        .id{
            width: 395px;
            position:relative;
            top:100px;
            left:-0px;


        }
        .insight{
            color:rgb(76, 169, 127)
        }
        
        
    
        
        .author{
        
            display: inline;
            position:relative;
            color:purple;
            top:350px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(199, 22, 22);
            font-family: Roquen;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        
        .pub{
            color:rgb(118, 179, 5);
            font-size: medium;
            position: relative;
            top:155px;
            left:33px;
        }
        .ed{
            color:rgb(11, 100, 100);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:70px;
        
        }
        .subtitle{
            color:rgb(16, 228, 228);
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:60px;
        }
        .mypic{
            position: relative;
            top: 230px;
            left: 290px;
            width: 80px;
            height: 70px;
            background-size:contain;
        }
        body {
            background-image: url('bakground.png');
            background:size=800px;
            background-position:center;
            background-repeat: no-repeat;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
            <div class="bookpage">
            <div  class="insight">
                
            </div>

        
            <div class="booktitle">
                <h1 style="font-family: cursive; color:rgb(16, 13, 5);">NATURE</h1></div>
            <div class="subtitle" style="text-align: center;color:blueviolet">
                 THE BEAUTY OF NATURE 
            </div>
            <div class="subtitle" style="color: rgb(10, 4, 60);text-align: center;">
                  Popular Book
            </div>

            <div class="mypic">
                <img src="photo.jpg" width="100" height="100" >
            </div>
            <div class="author">
              <center><p><b>SUPRIYA</b></p></center> 
            </div>
            <div class="id">
                <hr style ="color:rgb(238,17,68)">
            </div>
        
            <div class="ed">
                <center><b>SPECIAL EDITION</b></center>
                
            </div>
        </div>
        </body>
        

</html>
```
## OUTPUT:
![alt text](<Screenshot 2025-05-09 092233.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
