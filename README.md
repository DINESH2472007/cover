# Ex.06 Book Front Cover Page Design
## Date:08/12/2024

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
    <title>CSE</title>
    <style>
        .bookpage{
            width: 400px;
            height: 600px;
            color:rgb(44, 77, 107);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image: url(BOOK\ COVER.jpg);
            background-size: cover;
        }
       
        .author{
        
            display: inline;
            position: relative;
            color:rgb(255, 255, 255);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:azure;
            font-family: Roquen;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
          
        }

        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        
        .ed{
            color:azure;
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top:145px;
        
        }
        
        .mypic{
            position: relative;
            top: 180px;
            left: 300px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="booktitle">
                <h1> <FONT color="red">THE DISASTER OF WORLD</h1></div></FONT>
                <br>
            <div class="subtitle">
                <center><font color="white"> TRUTH BEHIND 2050</center></font>
            </div>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
           
        
            <div class="mypic">
                <right><img src="ME.jpg" width="90" height="70" ></right>
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="ed">
                <b>DINESH S</b>
            </div>
        </div>
        </body>
        
</html>

```

## OUTPUT:
![alt text](<Screenshot (14).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
