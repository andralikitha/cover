# Ex.06 Book Front Cover Page Design
## Date:24-04-2024
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
<html>
<style>
    .bookpage{
        width: 400px;
        height: 600px;
        color:rgb(117, 117, 216);
        margin-left: auto;
        margin-right: auto;
        padding: 20px;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;background-size: cover;
    }
        
    
    .insight{
        color: rgb(101, 198, 198);
    
    }
    
    
    .hrstyle{
        width:100px;
    }
    .author{
    
        display: inline;
        position: relative;
        color: rgb(220, 166, 111);
        top:160px;
        
        font-family:Georgia;
        font-size: medium;
    }
    .booktitle{
        font-family: 'Courier New', Courier, monospace;
        font-size: larger;
        text-align: center;
        position: relative;
        top: 60px;
    
    }
    .id {
        width:400px;
        position: relative;
        top:175px;
        
    }
    .pub{
        font-size: medium;
        position: relative;
        top:135px;
        left:330px;
    }
    .ed{
        color: red;
        font-size: medium;
        font-family: Verdana;
        position:relative;
        top:80px;
    
    }
    .subtitle{
        font-family:Tahoma;
        font-size: large;
        position: relative;
        top:70px;
    }
    .mypic{
        position: relative;
        top: 210px;
        left: 300px;
        width: 100px;
        height: 150px;
        background-size: cover;
    }
    </style>
    <title>Book Cover Page</title>
    </head>
    <body>
    <div class="bookpage">
        <div class="insight">
            INSIGHT EXPERIENCE
        </div>
        <div class="hrstyle">
            <hr style="color: yellow;">
        </div>
        <div class="booktitle">
            <h1>THE COMPLETE ETHICAL HACKING BOOK</h1></div>
        <div class="subtitle">
            A Comprehensive Beginner's Guide to Learn and Master in Ethical Hacking
        </div>
        <div class="mypic">
            <img src="c:\Users\likit\OneDrive\Pictures\likitha resume photo 01.jpg" width="100" height="125" alt="">
        </div>
        <div class="id">
            <hr style="color: rgb(233, 194, 97);">
        </div>
        <div class="author">
           <p><b>ANDRA LIKITHA</b></p>
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            <b>Limited Edition</b>
        </div>
    </div>
    </body>
## OUTPUT:
![Screenshot 2024-05-11 190850](https://github.com/andralikitha/cover/assets/131592130/d3977c7e-1c7a-427f-8a02-d16e1a9abd39)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
