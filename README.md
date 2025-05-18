# Ex09 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.
d
.v

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
Home page:

<div class="iphone-13-mini---1">
  <img class="image-1" src="https://placehold.co/364x73" />
  <div class="rectangle-1"></div>
  <div class="login"><span class="login_span"><br/>Login</span></div>
  <div class="event-registration"><span class="eventregistration_span">EVENT REGISTRATION</span></div>
  <img class="image-2" src="https://placehold.co/259x259" />
</div>

<style>
.image-1 {
  width: 364px;
  height: 73px;
  left: 6px;
  top: 4px;
  position: absolute;
  box-shadow: 0px 4px 4px rgba(17, 0, 0, 0.25);
}

.rectangle-1 {
  width: 216px;
  height: 68px;
  left: 80px;
  top: 606px;
  position: absolute;
  background: #FFFBFB;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 50px;
  border: 1px #BA4D4D solid;
}

.login_span {
  color: black;
  font-size: 25px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
}

.login {
  width: 75px;
  height: 53px;
  left: 151px;
  top: 595px;
  position: absolute;
}

.eventregistration_span {
  color: black;
  font-size: 30px;
  font-family: Inter;
  font-style: italic;
  font-weight: 800;
  word-wrap: break-word;
}

.event-registration {
  width: 254px;
  height: 165px;
  left: 54px;
  top: 123px;
  position: absolute;
  text-align: center;
}

.image-2 {
  width: 259px;
  height: 259px;
  left: 59px;
  top: 236px;
  position: absolute;
  border-radius: 142px;
}

.iphone-13-mini---1 {
  width: 375px;
  height: 812px;
  position: relative;
  overflow: hidden;
  background-image: url(https://placehold.co/375x812);
}
</style>
```

```
Login Page:

<div class="iphone-13-mini---2">
  <img class="image-1" src="https://placehold.co/364x73" />
  <div class="rectangle-4"></div>
  <div class="submit"><span class="submit_span">Submit</span></div>
  <div class="rectangle-2"></div>
  <img class="rectangle-3178158-1" src="https://placehold.co/51x51" />
  <div class="rectangle-3"></div>
  <img class="images-1" src="https://placehold.co/55x55" />
  <div class="login"><span class="login_span">LOGIN</span></div>
</div>

<style>
.image-1 {
  width: 364px;
  height: 73px;
  left: 6px;
  top: 4px;
  position: absolute;
  box-shadow: 0px 4px 4px rgba(17, 0, 0, 0.25);
}

.rectangle-4 {
  width: 207px;
  height: 59px;
  left: 78px;
  top: 606px;
  position: absolute;
  background: #3FEA1D;
  border-radius: 50px;
}

.submit_span {
  color: #0E1414;
  font-size: 25px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
}

.submit {
  left: 138px;
  top: 620px;
  position: absolute;
  text-align: center;
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.rectangle-2 {
  width: 344px;
  height: 59px;
  left: 15px;
  top: 241px;
  position: absolute;
  background: white;
}

.rectangle-3178158-1 {
  width: 51px;
  height: 51px;
  left: 21px;
  top: 245px;
  position: absolute;
  opacity: 0.50;
}

.rectangle-3 {
  width: 344px;
  height: 59px;
  left: 15px;
  top: 370px;
  position: absolute;
  background: white;
}

.images-1 {
  width: 55px;
  height: 55px;
  left: 26px;
  top: 371px;
  position: absolute;
  opacity: 0.50;
  border-radius: 100px;
}

.login_span {
  color: black;
  font-size: 36px;
  font-family: Inter;
  font-style: italic;
  font-weight: 800;
  word-wrap: break-word;
}

.login {
  width: 180px;
  height: 81px;
  left: 93px;
  top: 105px;
  position: absolute;
  text-align: center;
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.iphone-13-mini---2 {
  width: 375px;
  height: 812px;
  position: relative;
  overflow: hidden;
  background-image: url(https://placehold.co/375x812);
}
</style>
```

```
Event type page:
<div class="iphone-13-mini---3">
  <img class="image-1" src="https://placehold.co/364x73" />
  <div class="rectangle-2"></div>
  <div class="technical"><span class="technical_span">TECHNICAL</span></div>
  <div class="rectangle-2_01"></div>
  <div class="technical_01"><span class="technical_01_span">TECHNICAL</span></div>
  <div class="rectangle-2_02"></div>
  <div class="technical_02"><span class="technical_02_span">TECHNICAL</span></div>
  <div class="rectangle-2_03"></div>
  <div class="non-technical"><span class="non-technical_span">NON-TECHNICAL</span></div>
  <div class="events"><span class="events_span">EVENTS</span></div>
  <img class="whatsapp-image-2025-05-16-at-104722_4eb8c831-1" src="https://placehold.co/234x214" />
</div>

<style>
.image-1 {
  width: 364px;
  height: 73px;
  left: 6px;
  top: 4px;
  position: absolute;
  box-shadow: 0px 4px 4px rgba(17, 0, 0, 0.25);
}

.rectangle-2 {
  width: 275px;
  height: 59px;
  left: 49px;
  top: 259px;
  position: absolute;
  background: linear-gradient(90deg, white 17%, #999999 88%);
  border-radius: 50px;
}

.technical_span {
  color: #080707;
  font-size: 25px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
}

.technical {
  left: 114px;
  top: 274px;
  position: absolute;
  text-align: center;
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.rectangle-2_01 {
  width: 275px;
  height: 59px;
  left: 49px;
  top: 259px;
  position: absolute;
  background: linear-gradient(90deg, white 17%, #999999 88%);
  border-radius: 50px;
}

.technical_01_span {
  color: #080707;
  font-size: 25px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
}

.technical_01 {
  left: 114px;
  top: 274px;
  position: absolute;
  text-align: center;
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.rectangle-2_02 {
  width: 275px;
  height: 59px;
  left: 49px;
  top: 259px;
  position: absolute;
  background: linear-gradient(90deg, white 17%, #999999 88%);
  border-radius: 50px;
}

.technical_02_span {
  color: #080707;
  font-size: 25px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
}

.technical_02 {
  left: 114px;
  top: 274px;
  position: absolute;
  text-align: center;
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.rectangle-2_03 {
  width: 275px;
  height: 59px;
  left: 47px;
  top: 600px;
  position: absolute;
  background: linear-gradient(90deg, white 0%, #F3F3F3 12%, #A9A9A9 84%, #999999 100%);
  border-radius: 50px;
}

.non-technical_span {
  color: #080707;
  font-size: 25px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
}

.non-technical {
  left: 78px;
  top: 615px;
  position: absolute;
  text-align: center;
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.events_span {
  color: black;
  font-size: 36px;
  font-family: Inter;
  font-style: italic;
  font-weight: 800;
  word-wrap: break-word;
}

.events {
  width: 180px;
  height: 81px;
  left: 93px;
  top: 105px;
  position: absolute;
  text-align: center;
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.whatsapp-image-2025-05-16-at-104722_4eb8c831-1 {
  width: 234px;
  height: 214px;
  left: 66px;
  top: 352px;
  position: absolute;
  border-radius: 50px;
}

.iphone-13-mini---3 {
  width: 375px;
  height: 812px;
  position: relative;
  overflow: hidden;
  background-image: url(https://placehold.co/375x812);
}
</style>

```
```
Technical events page:

<div class="iphone-13-mini---4">
  <img class="image-1" src="https://placehold.co/364x73" />
  <div class="rectangle-2"></div>
  <div class="technical-events"><span class="technicalevents_span">TECHNICAL EVENTS</span></div>
  <div class="rectangle-5"></div>
  <div class="rectangle-8"></div>
  <div class="rectangle-7"></div>
  <div class="rectangle-8_01"></div>
  <div class="register"><span class="register_span">REGISTER</span></div>
</div>

<style>
.image-1 {
  width: 364px;
  height: 73px;
  left: 6px;
  top: 4px;
  position: absolute;
  box-shadow: 0px 4px 4px rgba(17, 0, 0, 0.25);
}

.rectangle-2 {
  width: 275px;
  height: 59px;
  left: 50px;
  top: 89px;
  position: absolute;
  background: linear-gradient(90deg, #F22222 17%, #FF5A94 88%, #FF5A94 93%);
  border-radius: 50px;
}

.technicalevents_span {
  color: #080707;
  font-size: 25px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
}

.technical-events {
  left: 62px;
  top: 104px;
  position: absolute;
  text-align: center;
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.rectangle-5 {
  width: 320px;
  height: 133px;
  left: 29px;
  top: 209px;
  position: absolute;
  background: #FFBE26;
  border-radius: 100px;
  outline: 5px #210404 solid;
  outline-offset: -2.50px;
}

.rectangle-8 {
  width: 320px;
  height: 133px;
  left: 29px;
  top: 386px;
  position: absolute;
  background: #FFBE26;
  border-radius: 100px;
  outline: 5px black solid;
  outline-offset: -2.50px;
}

.rectangle-7 {
  width: 320px;
  height: 133px;
  left: 30px;
  top: 565px;
  position: absolute;
  background: #FFBE26;
  border-radius: 100px;
  outline: 5px black solid;
  outline-offset: -2.50px;
}

.rectangle-8_01 {
  width: 171px;
  height: 55px;
  left: 110px;
  top: 634px;
  position: absolute;
  background: linear-gradient(90deg, #1AE0EE 0%, #18D3E1 13%, #18CEDB 19%, #60DDE6 52%, #1FF952 100%);
  border-radius: 50px;
  outline: 1px black solid;
  outline-offset: -0.50px;
}

.register_span {
  color: #190202;
  font-size: 25px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
}

.register {
  left: 134px;
  top: 647px;
  position: absolute;
  text-align: center;
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.iphone-13-mini---4 {
  width: 375px;
  height: 812px;
  position: relative;
  overflow: hidden;
  background-image: url(https://placehold.co/375x812);
}
</style>

```

```
Non-technical Events page:

<div class="iphone-13-mini---5">
  <img class="image-1" src="https://placehold.co/364x73" />
  <div class="rectangle-2"></div>
  <div class="non-technical-events"><span class="non-technicalevents_span">NON-TECHNICAL EVENTS</span></div>
  <div class="rectangle-6"></div>
  <div class="rectangle-8"></div>
  <div class="register"><span class="register_span">REGISTER</span></div>
  <div class="rectangle-5"></div>
  <div class="art-fiesta-id101"><span class="artfiestaid101_span_01">Art Fiesta<br/></span><span class="artfiestaid101_span_02">(ID:101)</span></div>
  <div class="rectangle-8_01"></div>
  <div class="register_01"><span class="register_01_span">REGISTER</span></div>
  <div class="shutter-stories-id102"><span class="shutterstoriesid102_span_01">Shutter Stories<br/></span><span class="shutterstoriesid102_span_02">(ID:102)</span></div>
  <div class="rectangle-7"></div>
  <div class="rectangle-8_02"></div>
  <div class="register_02"><span class="register_02_span">REGISTER</span></div>
  <div class="verbal-velocity-challenge-id103"><span class="verbalvelocitychallengeid103_span_01">Verbal Velocity Challenge<br/></span><span class="verbalvelocitychallengeid103_span_02">(ID:103)</span></div>
</div>

<style>
.image-1 {
  width: 364px;
  height: 73px;
  left: 6px;
  top: 4px;
  position: absolute;
  box-shadow: 0px 4px 4px rgba(17, 0, 0, 0.25);
}

.rectangle-2 {
  width: 364px;
  height: 61px;
  left: 6px;
  top: 89px;
  position: absolute;
  background: linear-gradient(90deg, #F22222 17%, #FF5A94 88%, #FF5A94 93%);
  border-radius: 50px;
}

.non-technicalevents_span {
  color: #080707;
  font-size: 25px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
}

.non-technical-events {
  left: 28px;
  top: 104px;
  position: absolute;
  text-align: center;
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.rectangle-6 {
  width: 320px;
  height: 134px;
  left: 36px;
  top: 387px;
  position: absolute;
  background: #FFBE26;
  border-radius: 100px;
  outline: 5px black solid;
  outline-offset: -2.50px;
}

.rectangle-8 {
  width: 171px;
  height: 55px;
  left: 110px;
  top: 454px;
  position: absolute;
  background: linear-gradient(90deg, #1AE0EE 0%, #18D3E1 13%, #18CEDB 19%, #60DDE6 52%, #1FF952 100%);
  border-radius: 50px;
  outline: 1px black solid;
  outline-offset: -0.50px;
}

.register_span {
  color: #190202;
  font-size: 25px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
}

.register {
  left: 134px;
  top: 467px;
  position: absolute;
  text-align: center;
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.rectangle-5 {
  width: 320px;
  height: 133px;
  left: 29px;
  top: 209px;
  position: absolute;
  background: #FFBE26;
  border-radius: 100px;
  outline: 5px black solid;
  outline-offset: -2.50px;
}

.artfiestaid101_span_01 {
  color: #050000;
  font-size: 20px;
  font-family: Inter;
  font-weight: 400;
  word-wrap: break-word;
}

.artfiestaid101_span_02 {
  color: #050000;
  font-size: 20px;
  font-family: Inter;
  font-style: italic;
  font-weight: 600;
  word-wrap: break-word;
}

.art-fiesta-id101 {
  width: 221px;
  height: 71px;
  left: 77px;
  top: 211px;
  position: absolute;
  text-align: center;
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.rectangle-8_01 {
  width: 171px;
  height: 55px;
  left: 110px;
  top: 274px;
  position: absolute;
  background: linear-gradient(90deg, #1AE0EE 0%, #18D3E1 13%, #18CEDB 19%, #60DDE6 52%, #1FF952 100%);
  border-radius: 50px;
  outline: 1px black solid;
  outline-offset: -0.50px;
}

.register_01_span {
  color: #190202;
  font-size: 25px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
}

.register_01 {
  left: 134px;
  top: 287px;
  position: absolute;
  text-align: center;
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.shutterstoriesid102_span_01 {
  color: #050000;
  font-size: 20px;
  font-family: Inter;
  font-weight: 400;
  word-wrap: break-word;
}

.shutterstoriesid102_span_02 {
  color: #050000;
  font-size: 20px;
  font-family: Inter;
  font-style: italic;
  font-weight: 600;
  word-wrap: break-word;
}

.shutter-stories-id102 {
  width: 221px;
  height: 71px;
  left: 85px;
  top: 383px;
  position: absolute;
  text-align: center;
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.rectangle-7 {
  width: 320px;
  height: 133px;
  left: 30px;
  top: 565px;
  position: absolute;
  background: #FFBE26;
  border-radius: 100px;
  outline: 5px black solid;
}

.rectangle-8_02 {
  width: 171px;
  height: 55px;
  left: 110px;
  top: 636px;
  position: absolute;
  background: linear-gradient(90deg, #1AE0EE 0%, #18D3E1 13%, #18CEDB 19%, #60DDE6 52%, #1FF952 100%);
  border-radius: 50px;
  outline: 1px black solid;
  outline-offset: -0.50px;
}

.register_02_span {
  color: #190202;
  font-size: 25px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
}

.register_02 {
  left: 134px;
  top: 649px;
  position: absolute;
  text-align: center;
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.verbalvelocitychallengeid103_span_01 {
  color: #050000;
  font-size: 20px;
  font-family: Inter;
  font-weight: 400;
  word-wrap: break-word;
}

.verbalvelocitychallengeid103_span_02 {
  color: #050000;
  font-size: 20px;
  font-family: Inter;
  font-style: italic;
  font-weight: 600;
  word-wrap: break-word;
}

.verbal-velocity-challenge-id103 {
  width: 221px;
  height: 71px;
  left: 85px;
  top: 565px;
  position: absolute;
  text-align: center;
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.iphone-13-mini---5 {
  width: 375px;
  height: 812px;
  position: relative;
  overflow: hidden;
  background-image: url(https://placehold.co/375x812);
}
</style>
```

```
Final Page:

<div class="iphone-13-mini---6">
  <div class="congratulations-you-have-successfully-registered"><span class="congratulationsyouhavesuccessfullyregistered_span">CONGRATULATIONS !!<br/>YOU HAVE SUCCESSFULLY REGISTERED</span></div>
  <img class="image-2" src="https://placehold.co/364x73" />
  <img class="image-3" src="https://placehold.co/259x259" />
</div>

<style>
.congratulationsyouhavesuccessfullyregistered_span {
  color: #FB1919;
  font-size: 25px;
  font-family: Inter;
  font-weight: 800;
  word-wrap: break-word;
}

.congratulations-you-have-successfully-registered {
  width: 259px;
  height: 334px;
  left: 58px;
  top: 351px;
  position: absolute;
  text-align: center;
  justify-content: center;
  display: flex;
  flex-direction: column;
}

.image-2 {
  width: 364px;
  height: 73px;
  left: 6px;
  top: 0px;
  position: absolute;
  box-shadow: 0px 4px 4px rgba(17, 0, 0, 0.25);
}

.image-3 {
  width: 259px;
  height: 259px;
  left: 51px;
  top: 106px;
  position: absolute;
  border-radius: 142px;
}

.iphone-13-mini---6 {
  width: 375px;
  height: 812px;
  position: relative;
  overflow: hidden;
  background-image: url(https://placehold.co/375x812);
}
</style>
```

## OUTPUT:
![alt text](<Screenshot (15).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
