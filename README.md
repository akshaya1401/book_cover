# Ex.06 Book Front Cover Page Design
# Date:
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
{%load static %}
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Book Cover</title>
<style>
  body{margin:0;background:white;display:grid;place-items:center;min-height:100vh;font-family:Georgia,serif;}
  .cover{
    width:30%;      
    height:86%;   
    position: relative;      
    color:#fff;
    border:5px solid #161616ff;
   }
  .bg{width:100%; height:100%;}
  .content{
    position:absolute; inset:0;
    padding:28px;
    display:flex; flex-direction:column; justify-content:space-between;
  }
  .PUBLISHER_NOTE{font-size:14px;margin:8px;}
  h1{font-size:42px;}
  .DES{margin:10px; font-size:18px; max-width:90%;}
  .DETAILS{display:flex; align-items:flex-end; justify-content:space-between; margin-top:20px;}
  .AUTHORNAME{font-weight:bold; font-size:20px;}
  .publisher{font-size:16px;}
  .author{width:120px; height:120px;background:#fff;border:3px solid #fff;}
  .right{display:flex; flex-direction: column; align-items: end;}
</style>
</head>
<body>

<div class="cover">
  <img class="bg" src="{% static "bookney.png" %}" >
  <div class="content">
    <div>
      <p class="PUBLISHER_NOTE">SEC Insights</p>
      <h1> THE PRINCE</h1>
      <p class="DES">A SELF WRITTEN BIOGRAPHY OF THE FOOTBALL PRINCE NEYMAR JR</p>
    </div>

    <div class="DETAILS">
      <div>
        <P class="EDITION">SPECIAL EDITION</P>
        <p class="AUTHORNAME">NEYMAR</p>
      </div>
      <div class="right">
       
        <img class="author" src="{% static 'neymar.png' %}">
        <p class="publisher">SEC</p>

      </div>
      
    </div>
  </div>
</div>

</body>
</html>
```
# OUTPUT:
<img width="1038" height="551" alt="image" src="https://github.com/user-attachments/assets/623272e6-ccd4-43ec-926f-c2e2aee93348" />

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
