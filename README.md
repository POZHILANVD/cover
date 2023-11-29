# Ex.06 Book Front Cover Page Design
## Date:28.11.2023

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
book.html


<style>
    .bookpage{
        width: 400px;
        height: 530px;
        color:rgba(0, 246, 70, 0.986);
        margin-left: auto;
        margin-right: auto;
        padding: 40px;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        background-image: url(2.jpg);
        background-size: cover;
    }
        
    
    .insight{
        color: rgb(225, 69, 82);
    
    }
    
    
    .hrstyle{
        width:220px;
    }
    .author{
    
        display: inline;
        position: relative;
        color: rgb(242, 255, 0);
        top:280px;
        font-family:Georgia;
        font-size: medium;
    }
    .booktitle{
        font-family: 'Courier New', Courier, monospace;
        font-size: larger;
        text-align: center;
        position: relative;
        top: 40px;
    
    }
    .id {
        width:400px;
        position: relative;
        top:290px;
        
    }
    .pub{
        font-size: medium;
        position: relative;
        top:250px;
        left:330px;
    }
    .ed{
        color: rgb(255, 0, 242);
        font-size: medium;
        font-family: Verdana;
        position:relative;
        top:200px;
    
    }
    .subtitle{
        font-family:Tahoma;
        font-size: large;
        position: relative;
        top:60px;
    }
    .mypic{
        position: relative;
        top: 240px;
        left: 270px;
        width: 100px;
        height: 90px;
        background-size: cover;
    }
    </style>
    <title>Book Cover Page</title>
    </head>
    <body>
    <div class="bookpage">
        <div class="insight">
            DESIGN IN DREAM
        </div>
        <div class="hrstyle">
            <hr style="color: rgb(246, 255, 0);">
        </div>
        <div class="booktitle">
            <h1>WEB DEVELOPMENT</h1></div>
        <div class="subtitle">DEVELOP YOUR OWN WEB WORLD
             
        </div>
        <div class="mypic">
            <img src="1.jpg" width="130" height="145" alt="">
        </div>
        <div class="id">
            <hr style="color: rgb(218, 32, 32);">
        </div>
        <div class="author">
           <p><b>POZHILAN.V.D</b></p>
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            <b>LEARN WITH</b>
        </div>
    </div>
    </body>


```

## OUTPUT:
![Alt text](<Screenshot (100).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
