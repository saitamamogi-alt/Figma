# Ex08 Event Registration Web Application
## Date:25.03.2026

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
home page:1

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-SE">
      <div class="rectangle"></div>
      <div class="div"></div>
      <img class="element" src="img/1123x712-1.png" />
      <div class="text-wrapper">SPORTS DAY EVENTS</div>
      <div class="text-wrapper-2">LOGIN</div>
      <div class="text-wrapper-3">REGISTER</div>
      <img class="logo" src="img/logo.png" />
      <div class="text-wrapper-4">Moogeth Shivan GG-25018268</div>
    </div>
  </body>
</html>

page 2:

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-SE">
      <div class="rectangle"></div>
      <div class="text-wrapper">EVENT REGISTRATION FORM</div>
      <img class="element" src="img/1123x712-1.png" />
      <div class="div"></div>
      <div class="rectangle-2"></div>
      <div class="rectangle-3"></div>
      <div class="rectangle-4"></div>
      <div class="rectangle-5"></div>
      <div class="rectangle-6"></div>
      <div class="rectangle-7"></div>
      <div class="text-wrapper-2">NAME</div>
      <div class="text-wrapper-3">GENDER</div>
      <div class="text-wrapper-4">AGE</div>
      <div class="text-wrapper-5">REG NO</div>
      <div class="text-wrapper-6">MOBILE</div>
      <div class="text-wrapper-7">EVENTS TO REGISTER</div>
      <div class="text-wrapper-8">REGISTER</div>
      <div class="text-wrapper-9">Moogeth Shivan GG-25018268</div>
    </div>
  </body>
</html>

page 3:

<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-SE">
      <img class="images" src="img/images-1.png" />
      <div class="THANK-YOU">THANK YOU</div>
      <div class="rectangle"></div>
      <div class="for-support-contact">For Support <br />Contact</div>
      <div class="div"></div>
      <div class="secsportsevent">secsportsevent2025@gmail.com<br />Phone:9876543210</div>
      <div class="text-wrapper">Moogeth Shivan GG-25018268</div>
    </div>
  </body>
</html>

style.css
page 1:

.iphone-SE {
  background-color: #dfa4a4;
  overflow: hidden;
  width: 100%;
  min-width: 320px;
  min-height: 568px;
  position: relative;
}

.iphone-SE .rectangle {
  top: 345px;
  position: absolute;
  left: 87px;
  width: 146px;
  height: 44px;
  background-color: #b49595;
}

.iphone-SE .div {
  top: 262px;
  position: absolute;
  left: 87px;
  width: 146px;
  height: 44px;
  background-color: #b49595;
}

.iphone-SE .element {
  position: absolute;
  top: 406px;
  left: 19px;
  width: 281px;
  height: 162px;
  aspect-ratio: 1.58;
  object-fit: cover;
}

.iphone-SE .text-wrapper {
  position: absolute;
  top: 126px;
  left: calc(50.00% - 99px);
  width: 198px;
  font-family: "Lexend Peta-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

.iphone-SE .text-wrapper-2 {
  position: absolute;
  top: 267px;
  left: 89px;
  width: 144px;
  font-family: "Lexend Peta-Regular", Helvetica;
  font-weight: 400;
  color: #d72323;
  font-size: 24px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .text-wrapper-3 {
  position: absolute;
  top: 351px;
  left: 94px;
  width: 139px;
  font-family: "Lexend Peta-Regular", Helvetica;
  font-weight: 400;
  color: #d31313;
  font-size: 20px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .logo {
  position: absolute;
  top: 47px;
  left: 39px;
  width: 241px;
  height: 48px;
  aspect-ratio: 5.01;
  object-fit: cover;
}

.iphone-SE .text-wrapper-4 {
  position: absolute;
  top: 550px;
  left: 61px;
  width: 301px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ea1212;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

page 2:
.iphone-SE {
  background-color: #a28f8f;
  width: 100%;
  min-width: 320px;
  min-height: 568px;
  position: relative;
}

.iphone-SE .rectangle {
  position: absolute;
  top: 28px;
  left: 20px;
  width: 279px;
  height: 46px;
  background-color: #ff1e1e;
}

.iphone-SE .text-wrapper {
  position: absolute;
  top: 43px;
  left: 32px;
  width: 256px;
  font-family: "Lexend Peta-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 13px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .element {
  position: absolute;
  top: 425px;
  left: 38px;
  width: 244px;
  height: 143px;
  aspect-ratio: 1.58;
  object-fit: cover;
}

.iphone-SE .div {
  position: absolute;
  top: 138px;
  left: 16px;
  width: 168px;
  height: 35px;
  background-color: #d9d9d9;
}

.iphone-SE .rectangle-2 {
  position: absolute;
  top: 180px;
  left: 16px;
  width: 168px;
  height: 35px;
  background-color: #d9d9d9;
}

.iphone-SE .rectangle-3 {
  position: absolute;
  top: 222px;
  left: 16px;
  width: 168px;
  height: 35px;
  background-color: #d9d9d9;
}

.iphone-SE .rectangle-4 {
  position: absolute;
  top: 264px;
  left: 16px;
  width: 168px;
  height: 35px;
  background-color: #d9d9d9;
}

.iphone-SE .rectangle-5 {
  position: absolute;
  top: 306px;
  left: 16px;
  width: 168px;
  height: 35px;
  background-color: #d9d9d9;
}

.iphone-SE .rectangle-6 {
  position: absolute;
  top: 364px;
  left: 91px;
  width: 137px;
  height: 33px;
  background-color: #ff1414;
}

.iphone-SE .rectangle-7 {
  position: absolute;
  top: 97px;
  left: 16px;
  width: 168px;
  height: 35px;
  background-color: #d9d9d9;
}

.iphone-SE .text-wrapper-2 {
  position: absolute;
  top: 106px;
  left: 22px;
  width: 156px;
  font-family: "Lato-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 13px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .text-wrapper-3 {
  position: absolute;
  top: 145px;
  left: 22px;
  width: 158px;
  font-family: "Lato-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 13px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .text-wrapper-4 {
  position: absolute;
  top: 187px;
  left: 22px;
  width: 154px;
  font-family: "Lato-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 13px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .text-wrapper-5 {
  position: absolute;
  top: 227px;
  left: 20px;
  width: 131px;
  font-family: "Lato-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 13px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .text-wrapper-6 {
  top: 269px;
  left: 20px;
  width: 147px;
  font-size: 13px;
  position: absolute;
  font-family: "Lato-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .text-wrapper-7 {
  position: absolute;
  top: 314px;
  left: 20px;
  width: 149px;
  font-family: "Lato-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 13px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .text-wrapper-8 {
  top: 365px;
  left: 102px;
  width: 133px;
  font-size: 24px;
  position: absolute;
  font-family: "Lato-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .text-wrapper-9 {
  position: absolute;
  top: 547px;
  left: 70px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ea1212;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

page 3:
.iphone-SE {
  background-color: #d4baba;
  width: 100%;
  min-width: 320px;
  min-height: 568px;
  position: relative;
}

.iphone-SE .images {
  position: absolute;
  top: 77px;
  left: 56px;
  width: 208px;
  height: 207px;
  aspect-ratio: 1;
  object-fit: cover;
}

.iphone-SE .THANK-YOU {
  position: absolute;
  top: 316px;
  left: 73px;
  width: 174px;
  font-family: "Lateef-Medium", Helvetica;
  font-weight: 500;
  color: #000000;
  font-size: 20px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .rectangle {
  position: absolute;
  top: 391px;
  left: 37px;
  width: 239px;
  height: 120px;
  background-color: #5d5858;
}

.iphone-SE .for-support-contact {
  position: absolute;
  top: 406px;
  left: 55px;
  width: 204px;
  font-family: "Lao Muang Don-Regular", Helvetica;
  font-weight: 400;
  color: #ece8e8;
  font-size: 20px;
  text-align: center;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .div {
  position: absolute;
  top: 465px;
  left: 59px;
  width: 210px;
  height: 28px;
  background-color: #5d5959;
}

.iphone-SE .secsportsevent {
  position: absolute;
  top: 464px;
  left: 47px;
  width: 213px;
  font-family: "Lao Muang Don-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 13px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-SE .text-wrapper {
  position: absolute;
  top: 543px;
  left: 59px;
  font-family: "Inter-Regular", Helvetica;
  font-weight: 400;
  color: #ea1212;
  font-size: 15px;
  letter-spacing: 0;
  line-height: normal;
  white-space: nowrap;
}

```


## OUTPUT:
![alt text](<home page.jpg>)
![alt text](<second page.jpg>)
![alt text](<image 3.jpg>)
## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
