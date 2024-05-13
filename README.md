# Ex.06 Book Front Cover Page Design
## Date: 10.05.2024

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
    <title>Book Cover Design</title>
    <style> 
        .wrapper {
            background-color: rgb(5, 188, 255);
            height:100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .bookpage{
            width: 400px;
            height: 600px;
            color: black;
            padding: 30px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image:url(back.jpg) ;
            background-size: cover;
        }
            
        
        .insight{
            color: rgb(0, 5, 10);
        
        }
        
        
        .hrstyle{
            width: 100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(231, 129, 12);
            top: 270px;
            font-family: Georgia;
            font-size: medium;
            padding-bottom: 20px;
        }
        .booktitle{
            color: rgb(251, 50, 0);
            font-family: 'Courier New', Courier, monospace, bold;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width: 400px;
            position: relative;
            top: 280px;
            
        }
        .pub{
            color: rgb(0, 10, 3);
            font-size: medium;
            position: relative;
            top: 235px;
            left: 330px;
        }
        .ed{
            color: rgb(240, 12, 232);
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 190px;
        
        }
        .subtitle{
            color:gold(24, 38, 78);
            font-family: unicorn;
            font-size: larger;
            position: relative;
            top: 15px;
        }
        .subtitle2{
            color: rgb(243, 243, 6);
            font-family: Arial, Helvetica, sans-serif;
            font-size: small;
            position: relative;
            top: 250px;
        }
        .mypic{
            position: relative;
            top: 250px;
            left: 300px;
            width: 90px;
            height: 80px;
            background-size: contain;
        }
    </style>
</head>
<body>
    <div class="wrapper">
        <div class="bookpage">
            <div class="insight">
                <b>WEB APPLICATION DEVELOPMENT</b>
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(218, 246, 9)">
            </div>
            <div class="booktitle">
                <h1><b>WEB APPLICATION DEVELOPMENT</b></h1></div>
            <div class="subtitle">
                 <b>Streamlining Web Development</b> 
            <div class="subtitle2">
                <b>>> If you think math is hard, try web design</b><br>
                <b>>> Web Design Helps Convey Your Brand with True Impact</b><br>
            </div>     
            </div>
            <div class="mypic">
                <img src="c:\Users\admin\Downloads\WhatsApp Image 2024-05-13 at 08.39.37_d988eef3.jpg" width="100" height="90" >
            </div>
            <div class="id">
                <hr style="color:rgb(1, 0, 8)">
            </div>
            <div class="author">
               <p><b>Dilip Sanjay M(212223240032)</b></p>
            </div>
            <div class="pub">
                SEC 27'
            </div>
        </div>
    </div>
</body>
</html>
    </html>    

```

## OUTPUT:
![image](https://github.com/dilipsanjay/cover/assets/155506948/aecd9548-1fed-4190-bae6-5259a3acf540)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
