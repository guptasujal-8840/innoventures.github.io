
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Simple HTML HomePage</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Sriracha&display=swap');

    body {
      margin: 0;
      box-sizing: border-box;
    }

    /* CSS for header */
    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #f5f5f5;
    }

    .header .logo {
      font-size: 25px;
      font-family: 'Sriracha', cursive;
      color: #000;
      text-decoration: none;
      margin-left: 30px;
    }

    .nav-items {
      display: flex;
      justify-content: space-around;
      align-items: center;
      background-color: #f5f5f5;
      margin-right: 20px;
    }

    .nav-items a {
      text-decoration: none;
      color: #000;
      padding: 35px 20px;
    }

    /* CSS for main element */
    .intro {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      width: 100%;
      height: 520px;
      background: linear-gradient(to bottom, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.5) 100%), url("https://images.unsplash.com/photo-1587620962725-abab7fe55159?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1031&q=80");
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
    }

    .intro h1 {
      font-family: sans-serif;
      font-size: 50px;
      color: #fff;
      font-weight: bold;
      text-transform: uppercase;
      margin: 0;
    }
	.intro h2 {
      font-family: sans-serif;
      font-size: 50px;
      color: #fff;
      font-weight: bold;
      text-transform: uppercase;
      margin: 0;
    }
	.intro h3 {
      font-family: sans-serif;
      font-size: 40px;
      color: #fff;
      font-weight: bold;
      text-transform: uppercase;
      margin: 0;
    }
	.intro h4 {
      font-family: sans-serif;
      font-size: 40px;
      color: #fff;
      font-weight: bold;
      text-transform: uppercase;
      margin: 0;
    }
	.intro h5 {
      font-family: sans-serif;
      font-size: 40px;
      color: #fff;
      font-weight: bold;
      text-transform: uppercase;
      margin: 0;
    }
	.intro p {
      font-size: 20px;
      color: #d1d1d1;
      text-transform: uppercase;
      margin: 20px 0;
    }

    .intro button {
      background-color: #5edaf0;
      color: #000;
      padding: 10px 25px;
      border: none;
      border-radius: 5px;
      font-size: 20px;
      font-weight: bold;
      cursor: pointer;
      box-shadow: 0px 0px 20px rgba(255, 255, 255, 0.4)
    }

    .achievements {
      display: flex;
      justify-content: space-around;
      align-items: center;
      padding: 40px 80px;
    }

    .achievements .work {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 0 40px;
    }

    .achievements .work i {
      width: fit-content;
      font-size: 50px;
      color: #333333;
      border-radius: 50%;
      border: 2px solid #333333;
      padding: 12px;
    }

    .achievements .work .work-heading {
      font-size: 20px;
      color: #333333;
      text-transform: uppercase;
      margin: 10px 0;
	font-weight: bold;
    }

    .achievements .work .work-text {
      font-size: 15px;
      color: #585858;
      margin: 10px 0;
    }

    .about-us {
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 40px 80px;
      border-top: 2px solid #eeeeee;
    }

    .about-us img {
      width: 500px;
      max-width: 100%;
      height: auto;
      border-radius: 10px;
    }

    .about-us-text h2 {
      font-size: 30px;
      color: #333333;
      text-transform: uppercase;
      margin: 0;
    }

    .about-us-text p {
      font-size: 15px;
      color: #585858;
      margin: 10px 0;
    }

    /* CSS for footer */
    .footer {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #302f49;
      padding: 40px 80px;
    }

    .footer .copy {
      color: #fff;
    }

    .bottom-links {
      display: flex;
      justify-content: space-around;
      align-items: center;
      padding: 40px 0;
    }

    .bottom-links .links {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 0 40px;
    }

    .bottom-links .links span {
      font-size: 20px;
      color: #fff;
      text-transform: uppercase;
      margin: 10px 0;
    }

    .bottom-links .links a {
      text-decoration: none;
      color: #a1a1a1;
      padding: 10px 20px;
    }
  </style>
</head>

<body>
  <header class="header">
    <a href="#" class="logo">MediConnect</a>
    <nav class="nav-items">
      <a href="">HOME</a>
      <a href="#">ABOUT</a>
	    <a href="#">SERVICE</a>
      <a href="#">CONTACT US</a>
      <a href="button.html">SIGN UP/LOGIN</a>
    </nav>
  </header>
  <main>
    <div class="intro">
      <h1>Best Healthcare</h1>
	<h2>Solution In Your City</h2>
	<h3>.</h3>
	<h4>Why choose</h4>
	<h5>MediConnect ?</h5>
      <p>.</p>
      <button>Learn More</button>
    </div>
    <div class="achievements">
      <div class="work">
        <i class="fas fa-plus"></i>
        <p class="work-heading">Emergency Care</p>
        <p class="work-text">Emergency Care is an essential part of the health system and serves as the first point of contact for many around the world.</p>
      </div>
      <div class="work">
        <i class="fas fa-stethoscope"></i>
        <p class="work-heading">Operations And Surgery</p>
        <p class="work-text">Hi-Tech rooms for operations and surgery with all the necessary equipments and the team of best doctors.</p>
      </div>
      <div class="work">
        <i class="fas fa-water droplet"></i>
        <p class="work-heading">Blood Testing</p>
        <p class="work-text">Blood testing rooms are available. Camps are organised for blood donation.</p>
      </div>
    </div>
    <div class="about-us">
      <div class="about-us-text">
        <h2>About us</h2>
        <p>At MediConnect , we offer treatment across all general specialties like all OPD services, mother and childcare, critical care, emergency, and Trauma, etc., and Super Specialty services which include Interventional Cardiology, Neurosurgery, Endocrinology, Gastroenterology, Spine Surgery, Neurology, Nephrology including Dialysis, Urology, Dermatology, Cosmetology, Plastic and Reconstructive Surgery, etc..</p>
      </div>
      <img src="https://images.unsplash.com/photo-1596495578065-6e0763fa1178?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=871&q=80" alt="me">
    </div>
  </main>
  <footer class="footer">
    <div class="copy">&copy; Developer Tanmay</div>
    <div class="bottom-links">
      <div class="links">
        <span>More Info</span>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
      </div>
      <div class="links">
        <span>Social Links</span>
        <a href="#"><i class="fab fa-facebook"></i></a>
        <a href="#"><i class="fab fa-twitter"></i></a>
        <a href="#"><i class="fab fa-instagram"></i></a>
      </div>
    </div>
  </footer>
</body>

</html># innoventures.github.io
