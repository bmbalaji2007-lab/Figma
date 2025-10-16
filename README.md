# Ex09 Event Registration Web Application
## Date:16-10-2025
## Name : B M BALAJI
## Ref No: 25016669

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
PAGE - 1

index.html

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
    <div class="android-medium">
      <img class="back" src="img/back-1.png" />
      <img class="logo" src="img/logo-1.png" />
      <img class="icon" src="img/icon-1.png" />
      <div class="rectangle"></div>
      <div class="rounded-rectangle"></div>
      <div class="text-wrapper">login</div>
      <div class="div">Register</div>
      <p class="p">✦ © 2025 Designed with passion by B M BALAJI ✦</p>
    </div>
  </body>
</html>

globals.css

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

style.css

.android-medium {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 653px;
  min-height: 915px;
  position: relative;
}

.android-medium .back {
  position: absolute;
  top: 0;
  left: 0;
  width: 653px;
  height: 915px;
  aspect-ratio: 0.87;
  object-fit: cover;
}

.android-medium .logo {
  position: absolute;
  top: 22px;
  left: calc(50.00% - 308px);
  width: 618px;
  height: 100px;
  aspect-ratio: 6.65;
  object-fit: cover;
}

.android-medium .icon {
  position: absolute;
  top: 123px;
  left: 22px;
  width: 174px;
  height: 166px;
  aspect-ratio: 1.05;
  object-fit: cover;
}

.android-medium .rectangle {
  position: absolute;
  top: 555px;
  left: 37px;
  width: 236px;
  height: 61px;
  background-color: #88998e;
}

.android-medium .rounded-rectangle {
  position: absolute;
  top: 643px;
  left: 37px;
  width: 330px;
  height: 68px;
  background-color: #7b9381;
  border-radius: 5px;
  border: 1px solid;
  border-color: #000000;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 555px;
  left: 100px;
  height: 58px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: var(--title-page-font-family);
  font-weight: var(--title-page-font-weight);
  color: #ffffff;
  font-size: var(--title-page-font-size);
  letter-spacing: var(--title-page-letter-spacing);
  line-height: var(--title-page-line-height);
  white-space: nowrap;
  font-style: var(--title-page-font-style);
}

.android-medium .div {
  position: absolute;
  top: 643px;
  left: 100px;
  height: 58px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: var(--title-page-font-family);
  font-weight: var(--title-page-font-weight);
  color: #ffffff;
  font-size: var(--title-page-font-size);
  letter-spacing: var(--title-page-letter-spacing);
  line-height: var(--title-page-line-height);
  white-space: nowrap;
  font-style: var(--title-page-font-style);
}

.android-medium .p {
  position: absolute;
  top: 815px;
  left: 16px;
  width: 702px;
  height: 160px;
  display: flex;
  align-items: center;
  justify-content: center;
  transform: rotate(0.08deg);
  font-family: var(--heading-font-family);
  font-weight: var(--heading-font-weight);
  color: #d3a2a2;
  font-size: var(--heading-font-size);
  letter-spacing: var(--heading-letter-spacing);
  line-height: var(--heading-line-height);
  font-style: var(--heading-font-style);
}

PAGE - 2

index.html
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
    <div class="frame">
      <img class="back" src="img/back-3-1.png" />
      <p class="text-wrapper">✦ © 2025 Designed with passion by B M BALAJI ✦</p>
      <p class="FREE-FIRE-BGMI-CALL">
        FREE FIRE<br />BGMI<br />CALL OF DUTY<br />KGF<br />SUBWAY SUFERS<br />MIINI MILITIA<br />CLASH OF CLANS
      </p>
      <div class="div">LIST OF GAMES....</div>
    </div>
  </body>
</html>

globals.css

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

style.css

.frame {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 683.81px;
  min-height: 915.0px;
  position: relative;
}

.frame .back {
  position: absolute;
  top: -1px;
  left: -2px;
  width: 684px;
  height: 915px;
  transform: rotate(-0.25deg);
  aspect-ratio: 0.63;
  object-fit: cover;
}

.frame .text-wrapper {
  position: absolute;
  top: 856px;
  left: 40px;
  height: 58px;
  display: flex;
  align-items: center;
  justify-content: center;
  transform: rotate(-0.25deg);
  font-family: var(--heading-font-family);
  font-weight: var(--heading-font-weight);
  color: #ffffff;
  font-size: var(--heading-font-size);
  letter-spacing: var(--heading-letter-spacing);
  line-height: var(--heading-line-height);
  font-style: var(--heading-font-style);
}

.frame .FREE-FIRE-BGMI-CALL {
  position: absolute;
  top: 282px;
  left: 44px;
  width: 604px;
  height: 536px;
  display: flex;
  align-items: center;
  justify-content: center;
  transform: rotate(-0.25deg);
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #2a2833;
  font-size: 48px;
  letter-spacing: -0.96px;
  line-height: 57.6px;
}

.frame .div {
  position: absolute;
  top: 84px;
  left: 83px;
  width: 707px;
  height: 159px;
  display: flex;
  align-items: center;
  justify-content: center;
  transform: rotate(-0.25deg);
  font-family: "Inter-Bold", Helvetica;
  font-weight: 700;
  color: #ffffff;
  font-size: 64px;
  letter-spacing: -1.28px;
  line-height: 76.8px;
}

styleguide.css

:root {
  --heading-font-family: "Inter", Helvetica;
  --heading-font-weight: 600;
  --heading-font-size: 24px;
  --heading-letter-spacing: -0.48px;
  --heading-line-height: 120.00000476837158%;
  --heading-font-style: normal;
}

PAGE - 3

index.html

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
    <div class="android-medium">
      <img class="registration" src="img/registration-1.png" />
      <p class="text-wrapper">✦ © 2025 Designed with passion by BALAJ BM</p>
    </div>
  </body>
</html>

globals.css

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

style.css

.android-medium {
  background-color: #ffffff;
  width: 100%;
  min-width: 659px;
  min-height: 923px;
  position: relative;
}

.android-medium .registration {
  position: absolute;
  top: 0;
  left: 0;
  width: 659px;
  height: 923px;
  aspect-ratio: 0.64;
  object-fit: cover;
}

.android-medium .text-wrapper {
  position: absolute;
  top: 877px;
  left: 44px;
  height: 29px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: var(--heading-font-family);
  font-weight: var(--heading-font-weight);
  color: #120a0a;
  font-size: var(--heading-font-size);
  letter-spacing: var(--heading-letter-spacing);
  line-height: var(--heading-line-height);
  white-space: nowrap;
  font-style: var(--heading-font-style);
}

styleguide.css

:root {
  --heading-font-family: "Inter", Helvetica;
  --heading-font-weight: 600;
  --heading-font-size: 24px;
  --heading-letter-spacing: -0.48px;
  --heading-line-height: 120.00000476837158%;
  --heading-font-style: normal;
}


```
## OUTPUT:
<img width="1218" height="540" alt="Screenshot 2025-10-16 135953" src="https://github.com/user-attachments/assets/b290d990-af39-4257-9d45-0a333c7693a7" />


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
