# Ex09 Event Registration Web Application
## Date:18.05.2025
## NAME: A.Rafshaan ahmed
## REG NO: 212224230214
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
register page

html

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-16-1-1">
<img src="images/node-2.png" class="node-2" alt="whatsapp-image-2025-05-15-at-09-15-52_4e6b9445-1" />
<p class="text-3"><span class="text-rgb-154-51-51">EVENT DAY 2025</span></p>
<div class="mask-group-4">
<img src="images/union-5.svg" class="union-5" alt="union" />
</div>
<img src="images/polygon-1-6.svg" class="polygon-1-6" alt="polygon-1" />
<img src="images/star-1-7.svg" class="star-1-7" alt="star-1" />
<div class="rectangle-1-8"></div>
<div class="rectangle-4-9"></div>
<p class="text-10"><span class="text-black">Register here</span></p>
</div>

</body>
</html>

css


/* Add font files for Jaldi */
@font-face {
  font-family: 'Jaldi';
  src: url('fonts/jaldi.woff2') format('woff2'),
       url('fonts/jaldi.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-jaldi: 'Jaldi', sans-serif;
  --font-family-inter: 'Inter', sans-serif;
  --text-rgb-154-51-51: rgba(154, 51, 51, 0.55);
  --text-black: rgba(0, 0, 0, 1);
}

.text-rgb-154-51-51 {
  color: var(--text-rgb-154-51-51);
}

.text-black {
  color: var(--text-black);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.node-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.text-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-jaldi);
  font-weight: normal;
  font-size: 36px;
  line-height: 50px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-154-51-51);
}

.union-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.4300000071525574;
  fill: rgba(255, 255, 255, 1);
  border: none;
  outline: none;
}

.mask-group-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.polygon-1-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.5;
  fill: rgba(255, 255, 255, 1);
  border: none;
  outline: none;
}

.star-1-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 10px;
  opacity: 0.5099999904632568;
  fill: rgba(255, 255, 255, 1);
  border: none;
  outline: none;
}

.rectangle-1-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(233, 134, 134, 1);
}

.rectangle-4-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.text-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.iphone-16-1-1 {
@media (max-width: 1440px) {
  .iphone-16-1-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-16-1-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(159, 255, 247, 1);
}

list of events

html code


<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-16-1-1">
<img src="images/node-2.png" class="node-2" alt="whatsapp-image-2025-05-15-at-09-15-52_4e6b9445-1" />
<p class="text-3"><span class="text-rgb-154-51-51">EVENT DAY 2025</span></p>
<div class="mask-group-4">
<img src="images/union-5.svg" class="union-5" alt="union" />
</div>
<img src="images/polygon-1-6.svg" class="polygon-1-6" alt="polygon-1" />
<img src="images/star-1-7.svg" class="star-1-7" alt="star-1" />
<div class="rectangle-1-8"></div>
<div class="rectangle-4-9"></div>
<p class="text-10"><span class="text-black">Register here</span></p>
</div>

</body>
</html>

css


/* Add font files for Jaldi */
@font-face {
  font-family: 'Jaldi';
  src: url('fonts/jaldi.woff2') format('woff2'),
       url('fonts/jaldi.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-jaldi: 'Jaldi', sans-serif;
  --font-family-inter: 'Inter', sans-serif;
  --text-rgb-154-51-51: rgba(154, 51, 51, 0.55);
  --text-black: rgba(0, 0, 0, 1);
}

.text-rgb-154-51-51 {
  color: var(--text-rgb-154-51-51);
}

.text-black {
  color: var(--text-black);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.node-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.text-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-jaldi);
  font-weight: normal;
  font-size: 36px;
  line-height: 50px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-154-51-51);
}

.union-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.4300000071525574;
  fill: rgba(255, 255, 255, 1);
  border: none;
  outline: none;
}

.mask-group-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
}

.polygon-1-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.5;
  fill: rgba(255, 255, 255, 1);
  border: none;
  outline: none;
}

.star-1-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 10px;
  opacity: 0.5099999904632568;
  fill: rgba(255, 255, 255, 1);
  border: none;
  outline: none;
}

.rectangle-1-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(233, 134, 134, 1);
}

.rectangle-4-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
}

.text-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.iphone-16-1-1 {
@media (max-width: 1440px) {
  .iphone-16-1-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-16-1-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(159, 255, 247, 1);
}

End page

html code


<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<img src="images/iphone-16-3-1.png" class="iphone-16-3-1" alt="iphone-16-3" />

</body>
</html>

css

:root {
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.iphone-16-3-1 {
@media (max-width: 1440px) {
  .iphone-16-3-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-16-3-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

```
## OUTPUT:
![image](https://github.com/user-attachments/assets/1c0662c7-b91a-4cb8-91c0-8b8dfa37f37a)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
