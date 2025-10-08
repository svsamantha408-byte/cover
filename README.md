# Ex.06 Book Front Cover Page Design
## Date:08.10.2025

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
        <title>
            Book cover
        </title>
        <link rel="stylesheet" href="style.css">
        <body>
        <div class="cover">
            
                <h3 class="top">
                    SEC insight
                </h3>
                <h1>FUNDAMENTALS OF <BR>
                    WEB APPLICATION <BR>
                        DEVELOPMENT <br>
                </h1>
                <p class="sub">Deep dive in HTML,CSS,JS basics
                    <br>FROM BEGINNERS TO LEGEND</p>
                    <div class="bottom">
                        <div class="left">
                            <h4>SUPER DUPER EDITION</h4>
                            <hr color="yellow">
                            <h3>Samantha Shree.S.V</h3>
                        </div>
                        <div class="right">
                            <img src="author.jpg" alt="Author photo" align="left">
                            <p>SEC</p>

                        </div>
                    </div>
            </div>
        
        
    </body>
</html>

<style>
            body{
                background-color:bisque;
                display:flex;
                justify-content:center;
                align-items:center;
                height:100vh;
        

             }.cover{
                width: 200px;
                height: 550px;
                background: url(bookcover.png);
                background-size: cover;
                background-position: center;
            
                color:whitesmoke;
                position: relative;
                text-align: center;
                font-family: Arial, Helvetica, sans-serif;
                box-shadow: 0 0 10px rgba(0,0,0,0.3);
             }
             
             
            .top{
                text-align: left;
                font-size: 16px;
                margin-bottom: 20px;
                border-bottom:1px solid coral; 
                display: inline-block;
                bottom: 15px;
                right: 100px;
            }
            h1{
                font-size:24px;
                margin-top: 30px;
                font-weight: bold;
               
            }
            .sub{
                font-size: 14px;
                margin-top: 20px;
                text-align: left;
            }
            .bottom{
                position: absolute;
                bottom: 30px;
                left: 30px;
                right: 30px;
                display: flex;
                justify-content:space-between;
                align-items: center;
            }
            .left h4{
                font-size:14px;
                font-weight: bold;
            }
            .left p{
                font-size: 14px;
            }
             img{
              
                width: 70px;
                height: 70px;
                border: 2px solid white;
            }
            .right p{
                margin-top: 5px;
            font-weight: bold;}
```

## OUTPUT:
![alt text](<cover/bookapp/static/Screenshot (49).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
