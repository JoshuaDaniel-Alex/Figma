# Ex09 Event Registration Web Application
## Date:13.10.2025

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
page 1 html:
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="text-on-a-path" src="img/text-on-a-path.svg" />
      <img class="basketball-sport" src="img/badminton-sport-competition-poster-background-1.png" />
      <img class="saveetha" src="img/saveetha-1.png" />
      <img class="saveethalogo" src="img/saveethalogo-1.png" />
      <div class="rectangle"></div>
      <div class="text-wrapper">LOGIN</div>
      <div class="div"></div>
      <div class="text-wrapper-2">REGISTER</div>
      <div class="text-wrapper-3">BADMINTON TOURNAMENT</div>
    </div>
  </body>
</html>




page 1 global.css:
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




page 1 style.css:
.android-medium {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 393px;
  min-height: 852px;
  position: relative;
}

.android-medium .text-on-a-path {
  position: absolute;
  top: 395px;
  left: -114px;
  width: 245px;
  height: 33px;
}

.android-medium .basketball-sport {
  position: absolute;
  top: 0;
  left: 0;
  width: 393px;
  height: 852px;
  aspect-ratio: 0.66;
  object-fit: cover;
}

.android-medium .saveetha {
  position: absolute;
  top: 63px;
  left: 8px;
  width: 378px;
  height: 76px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.android-medium .saveethalogo {
  position: absolute;
  top: 139px;
  left: 101px;
  width: 191px;
  height: 183px;
  aspect-ratio: 1.04;
  object-fit: cover;
}

.android-medium .rectangle {
  top: 428px;
  left: 111px;
  width: 172px;
  height: 48px;
  background-color: #b1b1b1;
  box-shadow: 2px 9px 6px 5px #ffffffbd;
  position: absolute;
  border: 1px solid;
  border-color: #ffffff;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 436px;
  left: 157px;
  width: 110px;
  -webkit-text-stroke: 1px #000000;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .div {
  top: 515px;
  left: 108px;
  width: 175px;
  height: 49px;
  background-color: #9c9c9c;
  box-shadow: 8px 6px 4px 6px #ffffff8c;
  position: absolute;
  border: 1px solid;
  border-color: #ffffff;
}

.android-medium .text-wrapper-2 {
  position: absolute;
  top: 524px;
  left: 138px;
  -webkit-text-stroke: 1px #000000;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.android-medium .text-wrapper-3 {
  position: absolute;
  top: 364px;
  left: 73px;
  text-shadow: 0px 4px 4px #0000007d;
  -webkit-text-stroke: 1px #000000;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

page 2 html:
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
      <img class="element-page" src="img/2nd-page-1.png" />
      <div class="text-wrapper">SPORTS DAY EVENTS</div>
      <img class="star" src="img/star-1.svg" />
      <div class="div">CRICKET</div>
      <div class="text-wrapper-2">BADMINTON</div>
      <div class="text-wrapper-3">Mens singles</div>
      <div class="text-wrapper-4">Mens doubles</div>
      <div class="text-wrapper-5">Girls singles</div>
      <div class="text-wrapper-6">Girls doubles</div>
      <div class="text-wrapper-7">Mixed doubles</div>
      <img class="img" src="img/star-2.svg" />
      <img class="star-2" src="img/star-3.svg" />
      <img class="star-3" src="img/star-4.svg" />
      <img class="star-4" src="img/star-5.svg" />
      <img class="star-5" src="img/star-6.svg" />
      <img class="star-6" src="img/star-7.svg" />
    </div>
  </body>
</html>


page 2 global.css:
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


page 2 style.css:
.frame {
  background-color: #ffffff;
  width: 100%;
  min-width: 393px;
  min-height: 852px;
  position: relative;
}

.frame .element-page {
  position: absolute;
  top: 0;
  left: 0;
  width: 393px;
  height: 852px;
  aspect-ratio: 0.56;
  object-fit: cover;
}

.frame .text-wrapper {
  position: absolute;
  top: 164px;
  left: 125px;
  text-shadow: 0px 4px 4px #ffffff80;
  -webkit-text-stroke: 1px #ffffff;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .star {
  top: 285px;
  position: absolute;
  left: 75px;
  width: 22px;
  height: 21px;
}

.frame .div {
  position: absolute;
  top: 281px;
  left: 106px;
  width: 108px;
  text-shadow: 0px 4px 4px #ffffff82;
  -webkit-text-stroke: 1px #ffffff;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .text-wrapper-2 {
  position: absolute;
  top: 326px;
  left: 106px;
  width: 181px;
  text-shadow: 0px 4px 4px #ffffff82;
  -webkit-text-stroke: 1px #ffffff;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-3 {
  position: absolute;
  top: 368px;
  left: 105px;
  width: 181px;
  text-shadow: 0px 4px 4px #ffffff82;
  -webkit-text-stroke: 1px #ffffff;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-4 {
  position: absolute;
  top: 413px;
  left: 105px;
  width: 181px;
  text-shadow: 0px 4px 4px #ffffff82;
  -webkit-text-stroke: 1px #ffffff;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-5 {
  position: absolute;
  top: 458px;
  left: 106px;
  width: 181px;
  text-shadow: 0px 4px 4px #ffffff82;
  -webkit-text-stroke: 1px #ffffff;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-6 {
  position: absolute;
  top: 496px;
  left: 105px;
  width: 181px;
  text-shadow: 0px 4px 4px #ffffff82;
  -webkit-text-stroke: 1px #ffffff;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-7 {
  position: absolute;
  top: 542px;
  left: 105px;
  width: 181px;
  text-shadow: 0px 4px 4px #ffffff82;
  -webkit-text-stroke: 1px #ffffff;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .img {
  top: 327px;
  position: absolute;
  left: 75px;
  width: 22px;
  height: 21px;
}

.frame .star-2 {
  top: 369px;
  position: absolute;
  left: 75px;
  width: 22px;
  height: 21px;
}

.frame .star-3 {
  top: 414px;
  position: absolute;
  left: 75px;
  width: 22px;
  height: 21px;
}

.frame .star-4 {
  top: 459px;
  position: absolute;
  left: 75px;
  width: 22px;
  height: 21px;
}

.frame .star-5 {
  top: 501px;
  position: absolute;
  left: 75px;
  width: 22px;
  height: 21px;
}

.frame .star-6 {
  top: 543px;
  position: absolute;
  left: 75px;
  width: 22px;
  height: 21px;
}

page 3 html:
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
      <img class="element" src="img/948ab10c-809f-4029-a93f-e51fe0742cc9-1.png" />
      <div class="text-wrapper">TOURNAMENT REGISTRATION FORM</div>
      <div class="div">Fill the details</div>
      <div class="rectangle"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="rectangle-7"></div>
      <div class="rectangle-8"></div>
      <div class="text-wrapper-2">Full Name :</div>
      <div class="text-wrapper-3">Gender :</div>
      <div class="text-wrapper-4">Age :</div>
      <div class="text-wrapper-5">Register number :</div>
      <div class="text-wrapper-6">Department :</div>
      <div class="text-wrapper-7">Mobile no. :</div>
      <div class="text-wrapper-8">Email :</div>
      <div class="text-wrapper-9">Event to register :</div>
      <div class="rectangle-9"></div>
      <div class="text-wrapper-10">REGISTER!</div>
    </div>
  </body>
</html>


page 3 global.css:
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


page 3 style.css:
.frame {
  background-color: #ffffff;
  width: 100%;
  min-width: 393px;
  min-height: 852px;
  position: relative;
}

.frame .element {
  position: absolute;
  top: 0;
  left: 0;
  width: 393px;
  height: 852px;
  aspect-ratio: 0.46;
  object-fit: cover;
}

.frame .text-wrapper {
  position: absolute;
  top: 59px;
  left: 41px;
  text-shadow: 0px 4px 4px #00000078;
  -webkit-text-stroke: 1px #1d00fff2;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #0c00ff;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}

.frame .div {
  position: absolute;
  top: 97px;
  left: 42px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .rectangle {
  position: absolute;
  top: 207px;
  left: 32px;
  width: 316px;
  height: 27px;
  background-color: #cccccc;
}

.frame .rectangle-2 {
  position: absolute;
  top: 252px;
  left: 32px;
  width: 316px;
  height: 27px;
  background-color: #cccccc;
}

.frame .rectangle-3 {
  position: absolute;
  top: 293px;
  left: 32px;
  width: 316px;
  height: 27px;
  background-color: #cccccc;
}

.frame .rectangle-4 {
  position: absolute;
  top: 334px;
  left: 32px;
  width: 316px;
  height: 27px;
  background-color: #cccccc;
}

.frame .rectangle-5 {
  position: absolute;
  top: 373px;
  left: 32px;
  width: 316px;
  height: 27px;
  background-color: #cccccc;
}

.frame .rectangle-6 {
  position: absolute;
  top: 505px;
  left: 32px;
  width: 316px;
  height: 27px;
  background-color: #cccccc;
}

.frame .rectangle-7 {
  position: absolute;
  top: 544px;
  left: 32px;
  width: 316px;
  height: 27px;
  background-color: #cccccc;
}

.frame .rectangle-8 {
  position: absolute;
  top: 579px;
  left: 32px;
  width: 316px;
  height: 27px;
  background-color: #cccccc;
}

.frame .text-wrapper-2 {
  position: absolute;
  top: 216px;
  left: 42px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-3 {
  position: absolute;
  top: 257px;
  left: 42px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-4 {
  position: absolute;
  top: 298px;
  left: 42px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-5 {
  position: absolute;
  top: 339px;
  left: 40px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-6 {
  position: absolute;
  top: 378px;
  left: 42px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-7 {
  position: absolute;
  top: 510px;
  left: 42px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-8 {
  position: absolute;
  top: 548px;
  left: 42px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .text-wrapper-9 {
  position: absolute;
  top: 583px;
  left: 42px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.frame .rectangle-9 {
  position: absolute;
  top: 653px;
  left: 121px;
  width: 135px;
  height: 39px;
  background-color: #0004ff;
  border: 1px solid;
  border-color: #1500ff;
  box-shadow: 0px 4px 4px #000000;
}

.frame .text-wrapper-10 {
  position: absolute;
  top: 658px;
  left: 123px;
  width: 145px;
  -webkit-text-stroke: 1px #00000061;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  letter-spacing: 0;
  line-height: normal;
}
```

## OUTPUT:
![alt text](<Screenshot (76).png>)
![alt text](<Screenshot (77).png>)
![alt text](<Screenshot (78).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
