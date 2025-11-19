# Ex.06 Book Front Cover Page Design
## Date:

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
```python
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #000;
            font-family: 'Roboto', sans-serif;
        }

        .bookcover {
            width: 400px;
            height: 600px;
            margin: 50px auto;
            border: 5px solid #444;
            box-shadow: 0 12px 30px rgba(0,0,0,0.6);
            background: linear-gradient(rgba(0,0,0,0.3), rgba(0,0,0,0.3)), 
                        url('photo.jpeg');
            background-size: cover;
            background-position: center;
            position: relative;
            color: #fff;
            overflow: hidden;
            border-radius: 12px;
        }

        .title {
            text-align: center;
            font-family: 'Playfair Display', serif;
            font-size: 28px;
            font-weight: 700;
            color: #ffd700;
            margin-top: 40px;
            text-shadow: 2px 2px 6px #000;
        }

        .subtitle {
            text-align: center;
            font-size: 14px;
            color: #f0f0f0;
            margin-top: 10px;
            font-style: italic;
            text-shadow: 1px 1px 3px #000;
        }

        .author-photo {
            position: absolute;
            bottom: 80px;
            right: 30px;
            width: 90px;
            height: 100px;
            border-radius: 8px;
            border: 2px solid #fff;
            overflow: hidden;
        }

        .author-photo img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .authorname {
            position: absolute;
            bottom: 100px;
            right: 135px;
            font-size: 18px;
            font-weight: 500;
            color: #ffd700;
            text-shadow: 1px 1px 3px #000;
        }

        .edition {
            position: absolute;
            bottom: 40px;
            left: 20px;
            font-size: 14px;
            font-weight: bold;
            color: #ffd700;
            text-shadow: 1px 1px 2px #000;
        }

        .sec {
            position: absolute;
            bottom: 40px;
            right: 20px;
            font-size: 14px;
            font-weight: bold;
            color: #ffd700;
            text-shadow: 1px 1px 2px #000;
        }

        .line {
            width: 80%;
            margin: 20px auto 0 auto;
            border: 1px solid #fff;
            opacity: 0.7;
        }
    </style>
</head>
<body>
    <div class="bookcover">
        <div class="title">JOURNEY TO THE STARS</div>
        <div class="subtitle">Exploring the Universe Beyond Earth</div>

        <div class="author-photo">
            <img src="author.jpg" alt="Author Photo">
        </div>
        <div class="authorname">Harish R</div>

        <div class="line"></div>

        <div class="edition">SPECIAL EDITION</div>
        <div class="sec">SEC</div>
    </div>
</body>
</html>
```

## OUTPUT:


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
