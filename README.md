# Ex09 Event Registration Web Application
## Date:26-04-24

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
home page
```
<div style="width: 393px; height: 852px; position: relative; background: white">
  <img style="width: 428px; height: 852px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/428x852" />
  <img style="width: 359px; height: 200px; left: 16px; top: 205px; position: absolute" src="https://via.placeholder.com/359x200" />
  <div style="width: 321px; height: 96px; left: 71px; top: 59px; position: absolute; color: #0E267D; font-size: 36px; font-family: Inter; font-style: italic; font-weight: 500; word-wrap: break-word">ALUMNI MEET</div>
  <div style="width: 290px; height: 50px; left: 51px; top: 130px; position: absolute; color: #212697; font-size: 36px; font-family: Inter; font-style: italic; font-weight: 500; word-wrap: break-word">!CELEBRATION!</div>
  <div style="width: 231px; height: 46px; left: 90px; top: 417px; position: absolute; background: #1C5F8F"></div>
  <div style="width: 231px; height: 48px; left: 90px; top: 502px; position: absolute; background: #1C5F8F"></div>
  <div style="width: 180px; height: 26px; left: 141px; top: 426px; position: absolute; color: white; font-size: 36px; font-family: Inter; font-style: italic; font-weight: 500; word-wrap: break-word">LOGIN</div>
  <div style="width: 237px; height: 28px; left: 118px; top: 508px; position: absolute; color: white; font-size: 36px; font-family: Inter; font-style: italic; font-weight: 500; word-wrap: break-word">REGISTER</div>
</div>
```
event organised 
```
<div style="width: 393px; height: 852px; position: relative; background: white">
  <img style="width: 405px; height: 942px; left: -12px; top: -61px; position: absolute" src="https://via.placeholder.com/405x942" />
  <img style="width: 187px; height: 200px; left: 97px; top: 174px; position: absolute" src="https://via.placeholder.com/187x200" />
  <div style="width: 521px; height: 877px; left: -31px; top: 0px; position: absolute; background: white">
    <img style="width: 444px; height: 938px; left: 0px; top: 0px; position: absolute" src="https://via.placeholder.com/444x938" />
    <div style="width: 376px; height: 69px; left: 41px; top: 48px; position: absolute"><span style="color: black; font-size: 48px; font-family: Inter; font-style: italic; font-weight: 600; word-wrap: break-word"> </span><span style="color: #4D1299; font-size: 48px; font-family: Inter; font-style: italic; font-weight: 600; word-wrap: break-word">ALUMNI MEET!</span></div>
    <div style="width: 323px; height: 47px; left: 68px; top: 208px; position: absolute; color: #4D1299; font-size: 32px; font-family: Inter; font-style: italic; font-weight: 600; word-wrap: break-word">Welcome Address</div>
    <div style="width: 297px; height: 42px; left: 60px; top: 272px; position: absolute; color: #4D1299; font-size: 32px; font-family: Inter; font-style: italic; font-weight: 600; word-wrap: break-word">Lamp Assemble </div>
    <div style="width: 296px; height: 42px; left: 61px; top: 337px; position: absolute; color: #4D1299; font-size: 32px; font-family: Inter; font-style: italic; font-weight: 600; word-wrap: break-word">Medal Cop-up</div>
    <div style="width: 286px; height: 33px; left: 63px; top: 396px; position: absolute; color: #4D1299; font-size: 32px; font-family: Inter; font-style: italic; font-weight: 600; word-wrap: break-word">Dinner</div>
    <div style="width: 317px; height: 39px; left: 66px; top: 463px; position: absolute; color: #4D1299; font-size: 32px; font-family: Inter; font-style: italic; font-weight: 600; word-wrap: break-word">DJ / Fun Activites</div>
  </div>
</div>
```
details
```
<div style="width: 393px; height: 843px; background: white; flex-direction: column; justify-content: flex-end; align-items: center; display: inline-flex">
  <div style="width: 404px; height: 895px; position: relative; background: white; flex-direction: column; justify-content: flex-start; align-items: flex-start; display: flex">
    <img style="width: 545px; height: 938px" src="https://via.placeholder.com/545x938" />
    <div style="width: 495px; height: 89px; color: #520F4B; font-size: 40px; font-family: Inter; font-weight: 800; word-wrap: break-word">REGISTRATION FORM</div>
    <div style="width: 339px; height: 47px; background: white"></div>
    <div style="width: 337px; height: 53px; color: black; font-size: 24px; font-family: Inter; font-weight: 800; word-wrap: break-word">Full Name*</div>
    <div style="width: 339px; height: 52px; background: white"></div>
    <div style="width: 319px; height: 29px; color: black; font-size: 24px; font-family: Inter; font-weight: 800; word-wrap: break-word">Department*</div>
    <div style="width: 337px; height: 57px; background: white"></div>
    <div style="width: 378px; height: 39px; color: black; font-size: 24px; font-family: Inter; font-weight: 800; word-wrap: break-word">Email ID*</div>
    <div style="width: 337px; height: 50px; background: white"></div>
    <div style="width: 339px; height: 41px; color: black; font-size: 24px; font-family: Inter; font-weight: 800; word-wrap: break-word">Mobile Number*</div>
    <div style="width: 182px; height: 40px; background: #73B871"></div>
    <div style="width: 180px; height: 40px; color: white; font-size: 32px; font-family: Inter; font-weight: 800; word-wrap: break-word">REGISTER</div>
    <div style="width: 508px; height: 155px; color: black; font-size: 40px; font-family: Inter; font-weight: 800; word-wrap: break-word">“Come and Spead your left out love!”</div>
  </div>
</div>
```
end page
```
<div style="width: 393px; height: 852px; background: white; flex-direction: column; justify-content: center; align-items: center; display: inline-flex">
  <div style="width: 502px; height: 938px; position: relative; background: white; flex-direction: column; justify-content: flex-start; align-items: flex-start; display: flex">
    <div style="width: 550px; height: 938px; background: #D9D9D9"></div>
    <img style="width: 550px; height: 951px" src="https://via.placeholder.com/550x951" />
    <div style="width: 441px; height: 132px; color: #CE0D8C; font-size: 48px; font-family: Inter; font-weight: 800; word-wrap: break-word">Thank You!</div>
    <div style="width: 509px; height: 170px; color: #520F4B; font-size: 40px; font-family: Inter; font-weight: 800; word-wrap: break-word">we are eagerly waiting for your presence!</div>
    <div style="width: 439px; height: 77px; color: #520F4B; font-size: 40px; font-family: Inter; font-weight: 800; word-wrap: break-word">~~ALUMNI MEET~~</div>
  </div>
</div>
```

## OUTPUT:

![Screenshot 2024-04-25 202946](https://github.com/aswethaashok/Figma/assets/149987410/ddbdf2d4-7915-430a-bb74-cb5de112b7f5)

![Screenshot 2024-04-25 203004](https://github.com/aswethaashok/Figma/assets/149987410/6b81e433-897b-4b2c-b6e0-06b543d15533)

![Screenshot 2024-04-25 203032](https://github.com/aswethaashok/Figma/assets/149987410/2035e66d-77b6-4cfe-a41a-63a1fcc6e8c7)

![Screenshot 2024-04-25 203550](https://github.com/aswethaashok/Figma/assets/149987410/ab5c0021-5070-4b49-8685-87df0a67a7a9)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
