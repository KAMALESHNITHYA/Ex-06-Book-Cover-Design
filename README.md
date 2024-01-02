# Ex-06-Book-Cover-Design]
## NAME : KAMALESH R
## REF NO : 23001711
## AIM:
To develop a website to display the cover page design of a book

Design Steps:
## Step 1:
Create a new Django project and app.

## Step 2:
Create a static file directory and mention the changes in settings.

## Step 3:
Make a new folder templates inside your app and create a html and map them using views and url.

S## tep 4:
Write down the code for book cover using HTML and CSS.

## Step 5:
Add images and other contents using CSS record a screenshot of it.

## Code:
```
<html>
     <head>
          <meta name="viewport"
          content="width=device-width, initial-scale=1.0">
          <style>
         


         .bookpage{
              width: 400px;
              height: 600px;
              color:white;
              margin-left: auto;
              margin-right: auto;
              padding: 20px;

              font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
              background-image: url(g.jpg);
              background-size: cover;
              }
             .insight{
                color:black;
              }

             .hrstyle{
             width:100px;
             }
             .author{
             display: inline;
             position: relative;
             top:190px;

             font-family:Georgia;
             font-size: medium;
             }
             .booktitle{
             font-family: 'Courier New',Courier,monospace;
             font-size: larger;
             text-align: center;
             position: relative;
color:black;
             top: 30px;
             }
             .id {
             width:400px;
             position: relative;
             top:180px;
             }
             .pub{
             font-size: medium;
             position: relative;
             top:155px;
             left:330px;
color:black;
             }
             .ed{
             color: black;
             font-size: medium;
             font-family: Verdana;
             position:relative;
             top:85px;
             }
             .subtitle{
             font-family:Tahoma;
             font-size: large;
             position: relative;
             top:40px;
color:black;
             }
             .mypic{
             position: relative;
             top: 135px;
             left: 260px;
             width: 100px;
             height: 100px;
             background-size: cover;
             }
             </style>
             <title>Book Cover Page</title>
             </head>
             <body>
             <div class="bookpage">
             <div class="insight">
                EXPERT INSIGHT
             </div>
             <div class="hrstyle">
                <hr style="color: yellow;">
             </div>
             <div class="booktitle">
             <h1>RESPONSIVE WEB DESIGN WITH HTML5 AND CSS</h1>
             </div>
             <div class="subtitle">
             Develop future-proof responsive websites using the latest HTML5 and css techniques
             </div>
             <div class ="mypic">
               <img src="KAMALESH .jpg" width="130" height="145" alt="">
             </div>
             <div class="id">
             <hr style="color: yellow;">
             </div>
             <div class="author">
             <p><b>Mr.KAMALESH</b></p>
             </div>
             <div class="pub">
                Packt>
             </div>
             <div class="ed">
             <b>Extended edition</b>
          </div>
     </body>
</html>
```
## OUTPUT

![Screenshot (57)](https://github.com/KAMALESHNITHYA/Ex-06-Book-Cover-Design/assets/145743119/792a10c7-2384-4303-b6e1-8ad88aae0d85)

## RESULT 

The Program is executed successfully.
