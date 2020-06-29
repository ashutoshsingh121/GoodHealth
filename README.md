<h1>GOOD HEALTH FRONTEND ASSIGNMENT</h1>

<b>Tools:</b>
<ul><li> HTML </li><li> CSS </li><li> JavaScript </li><li> Json</li> <li>Nodejs</li> <li>Materialize</li> <li>Jquery</li> <li>Twilio Api</li></ul>

<b>Requirement:</b>
<ol>
 <li>Nodejs</li>
 <li>Twilio Account</li>
 <ol>
  <li>serviceID</li>
  <li>accountSID</li>
  <li>authToken</li>
 </ol>
</ol>
and then put these key into <b>config.js</b>

<b>To run JavaScript Linter, type in terminal</b>
# npm run pretest

<b>To start Server, type</b>
# npm start

and then go to <a href="localhost:1999"><b>localhost:1999</b></a>

<b>Functionality: </b>
<ul><li>Add username, password, email and mobile into the table.</li><li>Password should be of minimum length 6.</li><li>Password will store in encrypted form into the database. </li><li> OTP is sent to the registered email id.</li><li>OTP verification is necessary to proceed onto next page. </li></ul>

<b>Usage Instructions: </b> <ul><li> Download the assignment from the given link. </li><li> User must have an account registered into database(json text file) to login, if not create it using registration form. </li><li> Registered user can login using email address and password.</li><li> After entering correct email address and password user will otp to their registered email.</li><li> Verify the otp and redirect to message page. </li></ul>

<b>Description: </b>
Username and email must be unique. In case, if username or email address contradict user will get a pop-up to either create a fresh account or can use registered email address and password to login.  </p>
<p>After entering correct email address and password user will be redirected to otp page where user must enter the same otp received into the registered email . In case, if user enter wrong otp, he/she will remain on the same page.</p> 
<p>After entering correct otp user will redirect to the message page where username and user email address will be displayed. User can also logout from the page. </p><br>


<b>Screenshots: </b>
 <img src="home page.jpeg">
  <p align="center"><b>Fig 1: Home Page</b></p><br>

  <img src="sign up page.jpeg">
  <p align="center"><b>Fig 2: Sign Up Page</b></p><br>

<img src="login page.jpeg">
<p align="center"><b>Fig 3: Login Page</b></p><br>
<img src="otp varification.jpeg">
<p align="center"><b>Fig 4: OTP Varification Page</b></p><br>
<img src="welcome message page.jpeg">
<p align="center"><b>Fig 5: Welcome Message Page</b></p>
