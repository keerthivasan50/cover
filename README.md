# Ex.06 Book Front Cover Page Design
## Date:15.04.2024

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
    <title>BOOK COVER</title>
    <style>
        .bookpage{

            width: 450px;
            height: 670px;
            color:rgb(15, 13, 13);
            margin-left: auto;
            margin-right: auto;
            padding: 26px;
            font-family: ' Arial, sans-serif';
            background-image: url("blue ocean.png");
            background-size: cover;
        }
            
        
        .insight{
            color:rgb(19, 22, 188);
            font-family: BOLD;
        }
        
        
        .hrstyle{
            width:128px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(22, 215, 144);
            top: 220px;
            font-family:BOLD;
            font-size: medium large;
        }
        .booktitle{
            color:rgb(24, 134, 134);
            font-family:bold;
            font-size: x-large;
            text-align: center;
            position: relative;
            top: 26px;
        
        }
        .id {
            width: 130px;
            color:rgb(0, 0, 0);
            position: relative;
            top: 240px;
            
        }
        .pub{
            color:rgb(157, 24, 35);
            font-size: large;
            font-family: bold;
            position: relative;
            top:190px;
            left:275px;
        }
        .ed{
            color:rgb(21, 1, 1);
            font-size: large;
            font-family:italic;
            position:relative;
            top: 90px;
            left:3px;
        
        }
        .subtitle{
            color:rgb(182, 182, 20);
            font-family:unicorn;
            font-size: large;
            position: relative;
            top: 10px;
        }
        .mypic{
            position: relative;
            top: 230px;
            left: 340px;
            width: 70px;
            height: 100px;
            border-radius: 500px;

        }
        </style>
        <title>Artificial Inteligence and Machine learning</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                FUTURE IS HERE!!
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>Artificial Inteligence and<br>Machine Learning</h1></div>
            <div class="subtitle">
                 LIMITED EDITION
            </div>
            <div class="subtitle">
                 
            </div>

            <div class="mypic">
                <img src="keerthivasan.jpg" width="90" height="130" >
            </div>
            <div class="id">
                <hr style="color:rgb(143, 177, 109)">
            </div>
            <div class="author">
               <br><b>S.KEERTHIVASAN<b>
               <br>212222040076</b></p>
            </div>
            <div class="pub">
                SEC PUBLICATIONS
            </div>
            <div class="ed">
                    <b>FUTURE</b> 
            </div>
            <div class="ed">
                     <b>TECHNOLOGY</b>
            </div>
        </body>
        

</html>
```


## OUTPUT:
![image](https://github.com/keerthivasan50/cover/assets/150429883/cae7dab4-27fe-4e6b-b5cb-fbaa1baaf236)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
