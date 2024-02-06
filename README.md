# gym_website
An website for fitness venture, aiming to attract potential clients and enhance online visibility. Featuring services, training and the goal of it isto boost membership of gym. HTML, CSS and JS is used to design this website and PHP alongside with SQL is used for backend database.
# step to run this website -
- firstly you have to download the zip file named web_d.zip
- extract that zip file
- install XAMPP a local sever host
- now copy the web_d folder and paste inside C:\xampp\htdocs this path (copy it in htdocs folder of XAMPP)
- now open the folder name web_d on any editor and you will get the code
- then open xampp, start Apache and MySql then open php my adin on chrome make data base with the help of given contraints in connection.php file
- the open the website on search engine by typing local host/web_d
- then, finall test the website.


.......................................................................................home.html.................................................................................................


<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>INSHAPE FITNESS</title>
  </head>
  <link rel="stylesheet" href="css/style.css" />
  <style>
    body {
      font-family: "Roboto Mono", monospace;
      font-family: "Rubik", sans-serif;
      margin: 0px;
      padding: 0px;
      background: url("img/bg.jpg");
    }
    #page-container {
  position: relative;
  min-height: 160%;
}

#content-wrap {
  min-height: 160%;   /* Footer height */
}
#footer .fb {
background-color: rgba(26, 25, 25, 0.87);
color: blanchedalmond;
height: 30px;
text-align: center;
position: absolute;
bottom: 0px;
left: 0px;
padding-top: 20px;
width: 100%;
}
.h3 {
  background-color: #6a6b1bf2;;
    color: blanchedalmond;
    text-align: center;
    position: absolute;
    top: 160px;
    left: 112px;
    width: 85%;
    height: 11%;
    font-size: 61px;
    behavior: alternate;
    direction: left;
}
  </style>
  <body>
    <header class="header">
      <!-- left for logo -->
      <div class="left">
        <img
          src="https://inshape.net/wp-content/uploads/2019/04/cropped-logo-1-142x100.png"
          alt=""
        />
        <div><b> INSHAPE FITNESS</b></div>
      </div>
      <!-- mid for nav -->
      <div class="mid">
        <ul class="navbar">
          <li><a href="home.html">Home</a></li>
          <li><a href="about us.html">About us</a></li>
          <li><a href="register.html">Register</a></li>
        </ul>
      </div>
      <!-- right for buttons -->
      <div class="right">
        <a class="btn" href="#popup1">Contact Us</a>
      </div>
      <div id="popup1" class="overlay">
        <div class="popup">
          <h2>CONTACT US THROUGH</h2>
          <a class="close" href="#">&times;</a>
          <div class="content">
            <ul>
              <li><b>CONTACT NUMBER</b> - 2390506000</li>
              <li><b>EMIAL ID</b> - abc@gmail.com</li>
              <li>
                <b>OR Visit</b> <br />
                Address - xyz road,near railway station Dehradoon
              </li>
            </ul>
          </div>
        </div>
      </div>
    </header>
    <h3 class="h3">
      <marquee behavior="alternate" direction="left">
        WELCOME TO INSHAPE FITNESS
      </marquee>
    </h3>
    <div class="paragraph">
        <img
          src="https://www.bodybuilding.com/images/2021/march/what-is-the-best-5-day-workout-split-header-960x540.jpg"
          alt=""
          align="right"
        />
        <p>
          <b>
            Unmatched service of a security-access key is available at Inshape
            Fitness. You can exercise any time from early morning to midnight
            using your own security-access key. Convenient parking is available at
            the fitness center. Their gym facilities include private restrooms,
            private showers, personal trainers, classes, HD TVs, functional unit,
            rock climbing, and treadmills. Cardio equipment including elliptical,
            exercise cycles, stair climbers, free weights, racks, plate loaded
            etc. are exclusively available here. It offers interesting membership
            plans as well.
          </b>
        </p>
      </div>
      <div id="page-container">
        <div id="content-wrap">
          <!-- all other page content -->
        </div>
        <footer id="footer">
          <div class="fb">
            &copy; Inshape Fitness (designed by amitesh)
            </div>
        </footer>
        </div>
    </body>
    </html>


.......................................................................................about.html.................................................................................................


<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Inshape Fitness</title>
  </head>
  <link rel="stylesheet" href="css/style.css" />
  <link rel="stylesheet" href="start.html">
  <style>
        body {
      font-family: "Roboto Mono", monospace;
      font-family: "Rubik", sans-serif;
      margin: 0px;
      padding: 0px;
      background: rgb(3, 96, 112);
      height: 160%;
    }
    .aboutus {
    margin: 190px 0px;
    padding: 200px 0px;
    background-color: rgba(34, 30, 30, 0.911);
    height: 795px;
}
.aboutus .h1 {
  font-size: 52px;
    color: #06D85F;
    font-family: "Apple Chancery", cursive;
    margin: -205px 0px;
    padding: 25px 0px;
    width: 100%;
    text-align: center;
    height: 100px;
}
.about1 img {
  height: 247px;
    padding: -1px 10px;
    margin: 242px -18px;
}
.about1 p {
  height: 209px;
    text-align: left;
    padding: -5px 358px;
    margin: -475px 504px;
    width: 46%;
    font-size: 22px;
    font-style: italic;
    background-color: rgba(243, 116, 42, 0.712);
}
.about2 img {
  height: 311px;
    padding: -81px 0px;
    margin: -24px 0px;
}
.about2 p {
  height: 256px;
    text-align: left;
    padding: 3px 10px;
    margin: 570px 61px;
    width: 55%;
    font-size: 22px;
    font-style: italic;
    background-color: rgba(240, 255, 240, 0.671);
}
.about3 img {
  height: 311px;
    padding: 7px 0px;
    margin: -51px 0px;
}
.about3 p {
  height: 232px;
    text-align: left;
    padding: 3px 0px;
    margin: -451px 526px;
    width: 48%;
    font-size: 22px;
    font-style: italic;
    background-color: rgba(59, 202, 23, 0.671);
}
#page-container {
  position: relative;
  min-height: 160%;
}

#content-wrap {
  min-height: 160%;   /* Footer height */
}

#footer {
  position: absolute;
  background-color: black;
  bottom: 0;
  width: 100%;
  height: 40%           /* Footer height */
}
#footer .fb {
background-color: rgba(26, 25, 25, 0.87);
color: blanchedalmond;
height: 30px;
text-align: center;
position: absolute;
bottom: 0px;
left: 0px;
padding-top: 20px;
width: 100%;
}
.h2 {
  background-color: rgba(26, 25, 25, 0.87);
    color: blanchedalmond;
    text-align: center;
    position: absolute;
    bottom: 377px;
    left: 0px;
    width: 100%;
    height: 16%;
    font-size: 61px;
}
.slideshow {
  position: absolute;
    bottom: 362px;
    left: 377px;
    width: 580px;
    height: 12%;
}
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
  background-color: blue;
}
.dotcls {
  position: absolute;
    bottom: 62px;
    left: 560px;
}
.dot {
  height: 17px;
  width: 17px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}
.active {
  background-color: red;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;


@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .text {font-size: 11px}
}
}
</style>
  <body>
    <header class="header">
      <!-- left for logo -->
      <div class="left">
        <img
          src="https://inshape.net/wp-content/uploads/2019/04/cropped-logo-1-142x100.png"
          alt=""
        />
        <div><b> INSHAPE FITNESS</b></div>
      </div>
      <!-- mid for nav -->
      <div class="mid">
        <ul class="navbar">
          <li><a href="home.html">Home</a></li>
          <li><a href="about us.html">About us</a></li>
          <li><a href="register.html">Register</a></li>
        </ul>
      </div>
      <!-- right for buttons -->
      <div class="right">
        <a class="btn" href="#popup1">Contact Us</a>
      </div>
      <div id="popup1" class="overlay">
        <div class="popup">
          <h2>CONTACT US THROUGH</h2>
          <a class="close" href="#">&times;</a>
          <div class="content">
            <ul>
              <li><b>CONTACT NUMBER</b> - 2390506000</li>
              <li><b>EMIAL ID</b> - abc@gmail.com</li>
              <li>
                <b>OR Visit</b> <br />
                Address - xyz road,near railway station Dehradoon
              </li>
            </ul>
          </div>
        </div>
      </div>
    </header>
    <div class="aboutus">
      <h1 class="h1">
        ABOUT US
      </h1>
    <div class="about1">
      <img src="img/gbbb.jpg" alt="" />
      <p> <b>What we do -</b> <br>
        We want to help you live a fit and healthy lifestyle! We do this by helping you find the most suitable equipment for your home gym, studio or commercial gym, keeping your budget, lifestyle and fitness goals in mind. We stock a wide range of gym equipment, with strength equipment, cardio, cross training and so much more. Our awesome team is always keen to help, so please call us to discuss your needs.</p>
    </div>
 <div class="about2">
   <img src="img/gb.jpg" alt="" align="right">
   <p><b> Our Customer Service -</b><br>
    At Gym and Fitness, customers are at the centre of what we do and why we do it! We have a team of knowledgeable sales representatives who are ready to assist you with your gym equipment needs. Our crew will be able to answer your questions from honest product information to the best way to integrate a piece of equipment into your workout routine. We work hard to ensure we have strong relationships with our suppliers, bringing you the best possible prices in the industry. In fact, if you find a better price on one of our core range of products, we will match it as a part of our brand promises.
   </p>
 </div>
 <div class="about3">
  <img src="img/bagg.jpg" alt="" align="left">
  <p><b>Our Gym Culture -</b><br>
    At Gym and Fitness, we believe that building a positive culture is incredibly important. The business is underpinned by six core values which speak of our commitment to our customers, staff, the industry and our business as a whole. We believe in encouraging, supporting, challenging, learning and growing to be the best. At Gym and Fitness, every morsel of feedback is a nugget of shiny gold because it gives us the opportunity to provide the best customer experience.
  </p>
</div>
<div id="page-container">
  <div id="content-wrap">
    <!-- all other page content -->
  </div>
  <footer id="footer">
    <div class="fc">
      <h2 class="h2">
        IMAGE GALLERY
      </h2>
      <div class="slideshow">
        <div class="mySlides fade">
          <div class="numbertext">1 / 10</div>
          <img src="https://i.pinimg.com/originals/bb/e6/8f/bbe68fac212892b1b9488f70ffe6e457.jpg" style="width:100%">
        </div>
        
        <div class="mySlides fade">
          <div class="numbertext">2 / 10</div>
          <img src="https://gymequipmentcenter.com/wp-content/uploads/guide/Elliptical-Machine.jpg" style="width:100%">
        </div>
        
        <div class="mySlides fade">
          <div class="numbertext">3 / 10</div>
          <img src="https://i.pinimg.com/originals/86/76/66/8676664769ea50039efac13a33ec1f3d.jpg" style="width:100%">
        </div>

        <div class="mySlides fade">
          <div class="numbertext">4 / 10</div>
          <img src="https://gymequipmentcenter.com/wp-content/uploads/guide/Treadmill.jpg" style="width:100%">
        </div>
        
        <div class="mySlides fade">
          <div class="numbertext">5 / 10</div>
          <img src="https://gymequipmentcenter.com/wp-content/uploads/guide/Dumb-Bells.jpg" style="width:100%">
        </div>

        <div class="mySlides fade">
          <div class="numbertext">6 / 10</div>
          <img src="https://www.muscleandfitness.com/wp-content/uploads/2018/11/Group-Fitness-Class-Performing-A-Variety-Of-Exercises-1.jpg?quality=86&strip=all" style="width:100%">
        </div>

        <div class="mySlides fade">
          <div class="numbertext">7 / 10</div>
          <img src="http://leisureopportunities.co.uk/images/imagesX/HIGH343934_43898_497850.jpg" style="width:100%">
        </div>

        <div class="mySlides fade">
          <div class="numbertext">8 / 10</div>
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRelcpmLDDDkEw4lpE-gMpAsYXysA3atl3qPEJH8hJOadh7q1lMLqN5oqlyRClkJ_TT_ok&usqp=CAU" style="width:100%">
        </div>

        <div class="mySlides fade">
          <div class="numbertext">9 / 10</div>
          <img src="https://c.files.bbci.co.uk/3250/production/_114908821_gyms201.jpg" style="width:100%">
        </div>

        <div class="mySlides fade">
          <div class="numbertext">10 / 10</div>
          <img src="https://images.indianexpress.com/2020/01/tips-for-gym-beginners_759.jpg" style="width:100%">
        </div>

      </div>
        <br>
        
        <div class="dotcls">
          <span class="dot"></span> 
          <span class="dot"></span> 
          <span class="dot"></span> 
          <span class="dot"></span> 
          <span class="dot"></span> 
          <span class="dot"></span> 
          <span class="dot"></span> 
          <span class="dot"></span> 
          <span class="dot"></span> 
          <span class="dot"></span> 
        </div>
    </div>
        <div class="fb">
        &copy; Inshape Fitness (designed by amitesh)
        </div>
</footer>
</div>
  
<script>
  var slideIndex = 0;
  showSlides();
  
  function showSlides() {
    var i;
    var slides = document.getElementsByClassName("mySlides");
    var dots = document.getElementsByClassName("dot");
    for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
    }
    slideIndex++;
    if (slideIndex > slides.length) {slideIndex = 1}    
    for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
    }
    slides[slideIndex-1].style.display = "block";  
    dots[slideIndex-1].className += " active";
    setTimeout(showSlides, 2000); // Change image every 2 seconds
  }
  </script>
  </body>
  </html>


.......................................................................................payment.html.................................................................................................


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PayUbiz</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<style>
body {
  font-family: "Roboto Mono", monospace;
  font-family: "Rubik", sans-serif;
  font-family: Arial;
  font-size: 17px;
  padding: 8px;
}

* {
  box-sizing: border-box;
}

.row {
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
  margin: 0 -16px;
}
.col-50 {
  -ms-flex: 50%; /* IE10 */
  flex: 50%;
}
.col-50 {
  padding: 0 16px;
}
input[type=text] {
  width: 100%;
  margin-bottom: 20px;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 3px;
}

label {
  margin-bottom: 10px;
  display: block;
}

.icon-container {
  margin-bottom: 20px;
  padding: 7px 0;
  font-size: 24px;
}

.btn {
  background-color: #04AA6D;
  color: white;
  padding: 12px;
  margin: 10px 0;
  border: none;
  width: 100%;
  border-radius: 3px;
  cursor: pointer;
  font-size: 17px;
}

.btn:hover {
  background-color: #45a049;
}
@media (max-width: 800px) {
  .row {
    flex-direction: column-reverse;
  }
}
</style>
<body>
    <div class="col-50">
        <h1>Pay Now</h1>
        <label for="fname">Accepted Cards</label>
        <div class="icon-container">
          <i class="fa fa-cc-visa" style="color:navy;"></i>
          <i class="fa fa-cc-amex" style="color:blue;"></i>
          <i class="fa fa-cc-mastercard" style="color:red;"></i>
          <i class="fa fa-cc-discover" style="color:orange;"></i>
        </div>
        <label for="cname">Name on Card</label>
        <input type="text" id="cname" name="cardname" placeholder="ABC XYZ">
        <label for="ccnum">Credit card number</label>
        <input type="text" id="ccnum" name="cardnumber" placeholder="1111-2222-3333-4444">
        <label for="expmonth">Exp Month</label>
        <input type="text" id="expmonth" name="expmonth" placeholder="JULY">
        <div class="row">
          <div class="col-50">
            <label for="expyear">Exp Year</label>
            <input type="text" id="expyear" name="expyear" placeholder="2018">
          </div>
          <div class="col-50">
            <label for="cvv">CVV</label>
            <input type="text" id="cvv" name="cvv" placeholder="352">
          </div>
        </div>
    <input type="submit" value="PAY" class="btn">
</div>
</body>


.......................................................................................register.html.................................................................................................


<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Inshape Fitness</title>
  </head>
  <link rel="stylesheet" href="css/style.css" />
  <link rel="stylesheet" href="connection.php">
  <style>
    body {
      font-family: "Roboto Mono", monospace;
      font-family: "Rubik", sans-serif;
      margin: 0px;
      padding: 0px;
      background: url("img/formbg.jpg");
    }
    .container {
      padding: 124px 83px;
      margin: 14px 52px;
      width: 80%;
      border-radius: 20px;
      color: #32dcad;
      font-size: 20px;
    }
    .container h1 {
      text-align: center;
    }

    .submit {
      font-size: 30px;
      background-color: rgb(4, 54, 49);
      border: 2px solid red;
      width: 30%;
      color: white;
      margin: 29px 430px;
      padding: 12px 19px;
      border-radius: 10px;
      cursor: pointer;
    }
    .submit:hover {
      text-decoration: underline;
      background-color: brown;
    }
    #page-container {
      position: relative;
      min-height: 160%;
    }

    #content-wrap {
      min-height: 160%; /* Footer height */
    }
    #footer .fb {
      background-color: rgba(26, 25, 25, 0.87);
      color: blanchedalmond;
      height: 30px;
      text-align: center;
      position: absolute;
      bottom: 0px;
      left: 0px;
      padding-top: 20px;
      width: 100%;
    }
  </style>
  <body>
    <header class="header">
      <!-- left for logo -->
      <div class="left">
        <img
          src="https://inshape.net/wp-content/uploads/2019/04/cropped-logo-1-142x100.png"
          alt=""
        />
        <div><b> INSHAPE FITNESS</b></div>
      </div>
      <!-- mid for nav -->
      <div class="mid">
        <ul class="navbar">
          <li><a href="home.html">Home</a></li>
          <li><a href="about us.html">About us</a></li>
          <li><a href="register.html">Register</a></li>
        </ul>
      </div>
      <!-- right for buttons -->
      <div class="right">
        <a class="btn" href="#popup1">Contact Us</a>
      </div>
      <div id="popup1" class="overlay">
        <div class="popup">
          <h2>CONTACT US THROUGH</h2>
          <a class="close" href="#">&times;</a>
          <div class="content">
            <ul>
              <li><b>CONTACT NUMBER</b> - 2390506000</li>
              <li><b>EMIAL ID</b> - abc@gmail.com</li>
              <li>
                <b>OR Visit</b> <br />
                Address - xyz road,near railway station Dehradoon
              </li>
            </ul>
          </div>
        </div>
      </div>
    </header>
    <div class="container">
      <h1><u> Fill form to join us </u></h1>
      <form action="connection.php" method="POST">
        <div class="form group">
          <label for="fname">First name:</label><br />
          <input
            type="text"
            id="fname"
            name="FirstName"
            placeholder="enter your first name"
          /><br />
          <label for="lname">Last name:</label><br />
          <input
            type="text"
            id="lname"
            name="LastName"
            placeholder="enter your last name"
          /><br />
          <label for="phone">CONTACT NUMBER:</label><br />
            <input
            type="tel"
            id="phone"
            name="ContactNumber"
            placeholder="Contact number"
          /><br />
          <label for="E-id">Email id:</label><br />
          <input
            type="email"
            id="email"
            name="EMAIL"
            placeholder="enter your email"
          /><br />
          <label for="bday">Birthday:</label><br />
          <input
            type="date"
            id="birthday"
            name="BIRTHDAY"
            placeholder="enter dob"
          /><br />
          <label for="hgt">Height:</label><br />
          <input
            type="centimeter"
            id="height"
            name="HEIGHT"
            placeholder="height in cm"
          /><br />
          <label for="wgt">Weight:</label><br />
          <input
            type="kilogram"
            id="weight"
            name="WEIGHT"
            placeholder="weight in kg"
          /><br />
          <label for="Gender">Gender:</label><br />
          <input type="radio" id="male" name="GENDER" value="M" />
          <label for="male">Male</label><br />
          <input type="radio" id="female" name="GENDER" value="F />
          <label for="female">Female</label><br />
          <input type="radio" id="other" name="GENDER" value="O" />
          <label for="other">Other</label><br /><br />
          <button class="1">Submit</button>
          <button class="1">Reset></button>
        </div>
      </form>
      <div>
        <a href="payment.html">
          <button class="submit">PROCEED TO PAY</button>
        </a>
      </div>
    </div>
    <div id="page-container">
      <div id="content-wrap">
        <!-- all other page content -->
      </div>
      <footer id="footer">
        <div class="fb">&copy; Inshape Fitness (designed by amitesh)</div>
      </footer>
    </div>
  </body>
</html>


.......................................................................................style.css....................................................................................................


.left {
  color: seashell;
  position: absolute;
  left: 40px;
  top: -8px;
  display: inline-block;
  position: fixed;
}
.left img {
  width: 96px;
  padding: 9px 36px;
}
.left div {
  line-height: 0;
  font-size: 22px;
  color: white
}
.left div:hover {
  background-color: rgb(29, 3, 29);
  text-decoration: underline;
}
.mid {
  color: seashell;
  display: block;
  width: 40%;
  height: 89px;
  left: 394px;
  right: 70px;
  top: 0px;
  background-color: #f50808b8;
  position: fixed;
}
.right {
  color: seashell;
  position: absolute;
  right: -10px;
  top: 25px;
  display: inline-block;
  position: fixed;
}
.btn {
  font-family: "Roboto Mono", monospace;
  font-family: "Rubik", sans-serif;
  font-size: 30px;
  background-color: #f50808b8;
  color: white;
  margin: 100px 57px;
  padding: 12px 11px;
  border-radius: 35px;
  cursor: pointer;
}
.btn:hover {
  text-decoration: underline;
  background-color: rgba(63, 8, 63, 0.753);
}
.overlay {
  position: fixed;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  background: rgba(0, 0, 0, 0.7);
  transition: opacity 500ms;
  visibility: hidden;
  opacity: 0;
}
.overlay:target {
  visibility: visible;
  opacity: 1;
}

.popup {
  margin: 60px 961px;
    padding: 20px;
    background: rgba(255, 255, 255, 0.651);
    border-radius: 5px;
    width: 25%;
    position: relative;
    transition: all 5s ease-in-out;
}

.popup h2 {
  margin-top: 0;
  color: #333;
  font-family: Tahoma, Arial, sans-serif;
}
.popup .close {
  position: absolute;
  top: 20px;
  right: 30px;
  transition: all 200ms;
  font-size: 30px;
  font-weight: bold;
  text-decoration: none;
  color: #333;
}
.popup .close:hover {
  color: #06D85F;
}
.popup .content {
  max-height: 30%;
  overflow: auto;
}

@media screen and (max-width: 700px){
  .box{
    width: 70%;
  }
  .popup{
    width: 70%;
  }
}
.navbar {
  display: inline-block;
}
.navbar li {
  font-size: 30px;
  padding: 11px 0px;
  display: inline-block;
}
.navbar li a {
  color: seashell;
  padding: 33px 23px;
  text-decoration: none;
}
.navbar li a:hover,
.navbar li a.active {
  text-decoration: underline;
  color: slategrey;
}
.navbar li a.active {
  color: slategrey;
}
.aboutus .h1{
  font-size: 30px;
  color: #06D85F;
  position: relative;
  margin-top: 0px;
  margin-right: 0px;
}
.paragraph {
  font-size: 25px;
  font-style: normal;
  color: rgb(200, 255, 0);
  background-color: rgb(3 4 2 / 79%);
  padding: 40px 135px;
  margin: 348px 0px;
  width: 80%;
}
.paragraph img {
  height: 570px;
  width: 103%;
  padding: 0px 0px;
}
.paragraph p {
  text-align: center;
  line-height: 34px;
}


.......................................................................................connection.php................................................................................................


<?php
$FirstName = $_POST['FirstName'];
$LastName = $_POST['LastName'];
$ContactNumber= $_POST['ContactNumber'];
$EMAIL= $_POST['EMAIL'];
$BIRTHDAY = $_POST['BIRTHDAY'];
$HEIGHT = $_POST['HEIGHT'];
$WEIGHT= $_POST['WEIGHT'];
$GENDER= $_POST['GENDER'];

//DATABASE CONNECTION
$conn = new mysqli('localhost','root','','gym_website');
if($conn->connect_error){
    die('Connection Failed : '.$conn->connect_error);
}else{
    $stmt = $conn->prepare("insert into registration_db(FirstName, LastName, ContactNumber, EMAIL, BIRTHDAY, HEIGHT, WEIGHT, GENDER) values(?, ?, ?, ?, ?, ?, ?, ?)");
    $stmt ->bind_param("ssisssss",$FirstName, $LastName, $ContactNumber, $EMAIL, $BIRTHDAY, $HEIGHT, $WEIGHT, $GENDER);
    $stmt->execute();
    echo "registration successfull";
    $stmt ->close();
    $conn ->close();
}

?>



