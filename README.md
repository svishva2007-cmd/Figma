# Ex09 Event Registration Web Application
## Date:24.12.2025
## Register number:25006451

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
FIRST PAGE:
INDEX.HTML:
~~~
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-compact">
      <img class="logo" src="img/logo-1.png" />
      <div class="text-wrapper">developed by s.vishvabala</div>
      <div class="div">Chess event</div>
      <div class="rectangle"></div>
      <div class="text-wrapper-2">See details</div>
    </div>
  </body>
</html>
~~~
GLOBAL.CSS:
~~~
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
~~~
STYLE.CSS:
~~~
.android-compact {
  background: linear-gradient(
    163deg,
    rgba(106, 222, 245, 1) 36%,
    rgba(79, 228, 126, 1) 74%
  );
  width: 100%;
  min-width: 1080px;
  min-height: 1980px;
  position: relative;
}

.android-compact .logo {
  position: absolute;
  top: 55px;
  left: 0;
  width: 1075px;
  height: 162px;
  aspect-ratio: 6.65;
  object-fit: cover;
}

.android-compact .text-wrapper {
  position: absolute;
  top: 1860px;
  left: 226px;
  font-family: "Times New Roman-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .div {
  position: absolute;
  top: 379px;
  left: 327px;
  width: 459px;
  font-family: "Timmana-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .rectangle {
  position: absolute;
  top: 1094px;
  left: 285px;
  width: 516px;
  height: 127px;
  border-radius: var(--shape-corner-extra-large);
  box-shadow: 0px 16px 30px #00000040;
  background: linear-gradient(
    90deg,
    rgba(75, 240, 130, 1) 35%,
    rgba(23, 195, 221, 1) 100%
  );
}

.android-compact .text-wrapper-2 {
  position: absolute;
  top: 1117px;
  left: 400px;
  font-family: "Timmana-Regular", Helvetica;
  font-weight: 400;
  color: #f6f5f5;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}
~~~
STYLEGUIDE.CSS:
~~~
:root {
  --shape-corner-extra-large: 28px;
}
~~~
SECOND PAGE:
INDEX.HTML:
~~~
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-compact">
      <img class="image" src="img/image-1.png" />
      <p class="chess-is-a-two">
        Chess is a two-player strategy board game played on an 8x8 grid, where players command 16 unique pieces (King,
        Queen, Rooks, Bishops, Knights, Pawns) with different moves, aiming to checkmate (trap) the opponent&#39;s King,
        originating from ancient India (chaturanga) and evolving into its modern form by the 19th century, governed by
        FIDE rules for international play, involving strategic positioning, tactics, and a blend of offense and defense.
      </p>
      <img class="vector" src="img/vector.svg" />
      <div class="text-wrapper">Register now</div>
    </div>
  </body>
</html>
~~~
GLOBAL.CSS:
~~~
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
~~~
STYLE.CSS:
~~~
.android-compact {
  background-color: #ffffff;
  width: 100%;
  min-width: 1080px;
  min-height: 1980px;
  position: relative;
}

.android-compact .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 1080px;
  height: 1980px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.android-compact .chess-is-a-two {
  position: absolute;
  top: 605px;
  left: 250px;
  width: 658px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 48px;
  letter-spacing: 0;
  line-height: normal;
}

.android-compact .vector {
  position: absolute;
  top: 1679px;
  left: 248px;
  width: 584px;
  height: 203px;
}

.android-compact .text-wrapper {
  position: absolute;
  top: 1718px;
  left: 369px;
  width: 376px;
  font-family: "Times New Roman-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}
~~~
THIRD PAGE:
INDEX.HTML:
~~~
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="styleguide.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-compact">
      <div class="rectangle"></div>
      <div class="text-wrapper">ENTER YOUR NAME</div>
      <div class="div"></div>
      <div class="text-wrapper-2">D.O.B</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-3">GENDER</div>
      <img class="img" src="img/rectangle-4.png" />
      <div class="text-wrapper-4">submit</div>
    </div>
  </body>
</html>
~~~
GLOBAL.CSS:
~~~
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
~~~
STYLE.CSS:
~~~
.android-compact {
  background: linear-gradient(
    164deg,
    rgba(102, 233, 247, 1) 0%,
    rgba(29, 198, 71, 1) 100%
  );
  width: 100%;
  min-width: 1080px;
  min-height: 1980px;
  position: relative;
}

.android-compact .rectangle {
  position: absolute;
  top: 400px;
  left: 103px;
  width: 868px;
  height: 119px;
  background-color: #fff9f9;
  border-radius: var(--shape-corner-large);
  box-shadow: 0px 16px 30px #00000040;
}

.android-compact .text-wrapper {
  position: absolute;
  top: 421px;
  left: 237px;
  width: 644px;
  font-family: "Times New Roman-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .div {
  position: absolute;
  top: 621px;
  left: 115px;
  width: 856px;
  height: 128px;
  background-color: #fffdfd;
  border-radius: var(--shape-corner-large);
  box-shadow: 0px 16px 30px #00000040;
}

.android-compact .text-wrapper-2 {
  position: absolute;
  top: 648px;
  left: 453px;
  font-family: "Times New Roman-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .rectangle-2 {
  position: absolute;
  top: 851px;
  left: 115px;
  width: 856px;
  height: 128px;
  background-color: #f9f6f6;
  border-radius: var(--shape-corner-medium);
  box-shadow: 0px 16px 30px #00000040;
}

.android-compact .text-wrapper-3 {
  position: absolute;
  top: 885px;
  left: 407px;
  font-family: "Times New Roman-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.android-compact .img {
  position: absolute;
  top: 1684px;
  left: 358px;
  width: 404px;
  height: 188px;
}

.android-compact .text-wrapper-4 {
  position: absolute;
  top: 1722px;
  left: 481px;
  font-family: "Timmana-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 64px;
  letter-spacing: 0;
  line-height: normal;
}
~~~
STYLEGUIDE.CSS:
~~~
:root {
  --shape-corner-large: 16px;
  --shape-corner-medium: 12px;
}
~~~
FOURTH PAGE:
INDEX.HTML:
~~~
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-compact"><p class="text-wrapper">Thank you for your registration</p></div>
  </body>
</html>
~~~
GLOBAL.CSS:
~~~
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
~~~
STYLE.CSS:
~~~
.android-compact {
  background-color: #090808;
  width: 100%;
  min-width: 1100px;
  min-height: 1980px;
  display: flex;
}

.android-compact .text-wrapper {
  margin-top: 252px;
  width: 794px;
  height: 567px;
  margin-left: 140px;
  font-family: "Jacques Francois Shadow-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 128px;
  letter-spacing: 0;
  line-height: normal;
}
~~~


## OUTPUT:
<img width="1919" height="1079" alt="Screenshot 2025-12-24 084550" src="https://github.com/user-attachments/assets/28ca9102-117e-49c7-aa86-7f20b9fe4078" />



## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
