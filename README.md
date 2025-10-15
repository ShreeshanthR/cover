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
    <title>Book Cover</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: black background-size: cover;
            background-position: center;
            color: black;
            background-color: rgb(28, 114, 171);
        }

        .cover {
            width: 625px;
            height: 875px;
            margin: 40px auto;
            padding: 40px;
            position: relative;
            background: rgba(255, 250, 240, 0.9);
            background-image: url(abc.jpg);
            /* faded parchment feel */
            border: 5px solid black;
            /* dark brown vintage border */
            border-radius: 6%;
        }

        .top {
            font-size: 22px;
            font-weight: bold;
            color: rgb(112, 109, 109);
            text-align: left;
            letter-spacing: 2px;
        }

        .title {
            font-size: 38px;
            font-weight: bold;
            text-align: center;
            margin-top: 120px;
            color: rgb(28, 114, 171);
            font-family: 'Times New Roman', serif;
        }

        .subtitle {
            font-size: 20px;
            text-align: center;
            margin-top: 30px;
            font-style: italic;
            color: rgb(28, 114, 171);
        }

        .special {
            font-size: 22px;
            font-weight: bold;
            margin-top: 400px;
            color: rgb(28, 114, 171);
            text-align: left;
        }

        .author {
            font-size: 20px;
            font-weight: bold;
            color: black;
            margin-top: 20px;
            text-align: left;
        }

        .sec {
            position: absolute;
            bottom: 30px;
            right: 20px;
            font-size: 18px;
            color: black;
        }

        .photo {
            width: 100px;
            height: 120px;
            position: absolute;
            bottom: 60px;
            right: 100px;
            border-radius: 8px;
            border: 2px solid rgb(28, 114, 171);
            box-shadow: 0 0 10px black
        }
    </style>
</head>

<body>
    <div class="cover">
        <div class="top">SEC Insights</div>

        <div class="title">
            FROM IDEAS TO REALITY<br>
            TECHNOLOGY MAKES IT POSSIBLE
        </div>

        <div class="subtitle">
            Inspiring minds to shape <br>
            the digital world
        </div>

        <div class="special">SPECIAL EDITION</div>

        <img src="photo.jpg" class="photo" alt="Author Photo">

        <div class="author">Shreeshanth R</div>
        <div class="sec">SEC</div>
    </div>
</body>

</html>

```

## OUTPUT:
![alt text](<Screenshot (45).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
