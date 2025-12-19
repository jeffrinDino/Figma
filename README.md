# Ex09 Event Registration Web Application
## Date:19-12-2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
Sheet 1
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <img class="download" src="img/download-1-1.png" />
      <img class="img" src="img/download-3.png" />
      <img class="saveetha-engineering" src="img/saveetha-engineering-college-kancheepuram-750x430-1.png" />
    </div>
  </body>
</html>

(Global Css)
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

Style.Css
.frame {
  background-color: #3a0739;
  width: 100%;
  min-width: 415px;
  min-height: 613px;
  display: flex;
  flex-direction: column;
}

.frame .download {
  margin-left: 8px;
  width: 390px;
  height: 50px;
  margin-top: 34px;
  aspect-ratio: 7.79;
  object-fit: cover;
}

.frame .img {
  margin-left: 301px;
  width: 79px;
  height: 79px;
  margin-top: 29px;
  aspect-ratio: 1;
  object-fit: cover;
}

.frame .saveetha-engineering {
  margin-left: 16px;
  width: 384px;
  height: 220px;
  margin-top: 30px;
  aspect-ratio: 1.74;
  object-fit: cover;
}

Sheet 2
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <img class="download" src="img/download-1.png" />
      <img class="img" src="img/download-2.png" />
      <img class="images" src="img/images-1.png" />
    </div>
  </body>
</html>

Global.Css
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

Style.Css
.frame {
  background-color: #621e65;
  width: 100%;
  min-width: 353px;
  min-height: 607px;
  display: flex;
  flex-direction: column;
}

.frame .download {
  margin-left: 16px;
  width: 321px;
  height: 64px;
  margin-top: 24px;
  aspect-ratio: 5.01;
  object-fit: cover;
}

.frame .img {
  margin-left: 241px;
  width: 75px;
  height: 75px;
  margin-top: 32px;
  aspect-ratio: 1;
  object-fit: cover;
}

.frame .images {
  margin-left: 13px;
  width: 324px;
  height: 215px;
  margin-top: 24px;
  aspect-ratio: 1.5;
  object-fit: cover;
}


Sheet 3
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="frame">
      <img class="whatsapp-image" src="img/whatsapp-image-2025-03-27-at-4-00-23-PM-1.png" />
      <img class="images" src="img/images-1-1.png" />
    </div>
  </body>
</html>

Global.css
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}


Style.Css
.frame {
  background-color: #7b2374;
  width: 100%;
  min-width: 336px;
  min-height: 607px;
  display: flex;
  flex-direction: column;
  gap: 77px;
}

.frame .whatsapp-image {
  margin-left: 6px;
  width: 324px;
  height: 216px;
  margin-top: 58px;
  aspect-ratio: 1.5;
  object-fit: cover;
}

.frame .images {
  margin-left: 6px;
  width: 324px;
  height: 215px;
  aspect-ratio: 1.5;
  object-fit: cover;
}
```

## OUTPUT:
![alt text](<Screenshot 2025-12-19 142846.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
