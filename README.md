<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>CRAFT WORLD</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #fdf6f0;
        }

        header {
            background-image: url('Head2.jpg');
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            position: relative;
            padding: 180px 40px;
            text-align: center;
            font-size: 40px;
            font-weight: bold;
            color: #FFB782;  /* soft cream */
            font-family: 'Georgia', serif;
            text-shadow: 2px 2px 5px rgba(0,0,0,0.4);
        }

        header::before {
            content: "";
            position: absolute;
            top: 0; left: 0; right: 0; bottom: 0;
            background: rgba(0, 0, 0, 0.3);  /* overlay for text readability */
            z-index: 2;
        }

        header h1,
        header p {
            position: relative;
            z-index: 2; /* text above overlay */
            margin: 0;
        }
        header h1 {
    margin-bottom: 22px; /* adds space below the headline */
         }
        header p {
    margin-top: 0;
    font-size: 25px;
    font-weight: bold;
    color: #FFC0B3;
    letter-spacing: 1.5px;  /* optional: slightly space out letters */
    text-align: center;
       }

        nav {
            background-color: #8b5e3c;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .banner {
    background-image: url("Head5.jpg");
    background-size: cover;
    background-position: center;
    height: 600px;

    /* center the text */
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 20;
    

    /* text style */
    font-size: 70px;           /* increase font size */
    font-weight: bold;          /* make it bold */
    color: #FFDD88;            /* soft cream color - looks elegant */
    font-family: 'Georgia', serif; /* classy font style */
    text-shadow: 2px 2px 5px rgba(0,0,0,0.4); /* optional shadow for better visibility */
}
        .container {
            padding: 30px;
        }

        h2 {
            text-align: center;
            color: #8b5e3c;
            font-size: 30;
            
        }

        .crafts {
            display: flex;
            gap: 20px;
            justify-content: center;
            flex-wrap: wrap;
        }

        .card {
            background-color: white;
            width: 250px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
            text-align: center;
            padding: 15px;
        }

        .card img {
            width: 100%;
            border-radius: 10px;
        }

        footer {
            background-color: #8b5e3c;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }
    </style>
</head>
<body>

<header>
    <h1>HEAVEN OF CRAFTS</h1>
    <p>•Beautiful  •Creative  •Curious  •Aesthetic</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Crafts</a>
    <a href="#">Contact</a>
</nav>

<!-- HOME -->
<section id="home">
    <h2>Welcome</h2>
    <p style="text-align:center;">
                   Craft World is a creative platform that presents handmade learning models
        and artistic crafts. 
                  These creations combine creativity with education,
        helping learners to understand concepts visually and practically.
    </p>
</section>

<!-- ABOUT -->
<section id="about">
    <h2>About Us</h2>
    <p style="text-align:center;">
        Heaven of Crafts promotes creativity through handmade educational models
        and decorative crafts that support learning through art and imagination.
    </p>
</section>

<div class="banner">
    HANDMADE WITH LOVE
</div>

<div class="container">


    <!-- CRAFT IMAGES SECTION -->
    <h2>LEARNING MODELS</h2>

    <div class="crafts">

   <div class="card">
    <img src="craft1.jpg" alt="Scalar Chain Model">
    <h3>SCALAR CHAIN</h3>
    <p>Connecting the Peak to the Foundation.</p>
</div>

        <div class="card">
            <img src="craft2.jpg" alt="Business Environment Model">
            <h3>BUSINESS ENVIRONMENT</h3>
            <p>Navigating the External Forces Shaping Business.</p>
        </div>
        
        

        <video controls style="width:75%; max-width:700px;">
            <source src="video1.mp4" type="video/mp4">
       </video>

        <div class="card">
            <img src="craft3.jpg" alt="Planning Model">
            <h3>PLANNING</h3>
            <p>Bridging the Gap: From Where We Are to Where We Want to Be.</p>
        </div>

        <div class="card">
            <img src="craft4.jpg" alt="Divisional Structure Model">
            <h3>DIVISIONAL STRUCTURE</h3>
            <p>Organizing for Efficiency through Specialized Business Units.</p>
        </div>
 
         <div class="card">
            <img src="craft5.jpg" alt="Elements of Delegation Model">
            <h3>ELEMENTS OF DELEGATION</h3>
            <p>y Empowering Teams through Authority, Responsibility, and Accountability.</p>
        </div>

         <div class="card">
            <img src="craft6.jpg" alt="Motivation Model">
            <h3>NEED HIERARCHY THEORY</h3>
            <p>Understanding What Drives Us: From Survival to Self-Actualization.</p>
        </div>
        
        <div class="card">
            <img src="craft7.jpg" alt="Banking Model">
            <h3>ACCEPTING DEPOSITS</h3>
            <p>Mobilizing Savings: The Foundation of Commercial Banking.</p>
        </div>
        
        <div class="card">
            <img src="craft8.jpg" alt="Banking Model">
            <h3>LENDING OF MONEY</h3>
            <p>Advancing Credit to Fuel Economic Growth.</p>
        </div>
        
        <video controls style="width:75%; max-width:700px;">
            <source src="video2.mp4" type="video/mp4">
       </video>
         
         <div class="card">
            <img src="craft9.jpg" alt="E Banking Model">
            <h3>E BANKING</h3>
            <p>Digital Solutions for Seamless 24/7 Banking.</p>
        </div>
        
        <div class="card">
            <img src="craft10.jpg" alt="Insurance Principles Model">
            <h3>PRINCIPLES OF INSURANCE</h3>
            <p>The Fundamental Pillars of Risk Protection..</p>
        </div>
        
        <div class="card">
            <img src="craft11.jpg" alt="Transportation Model">
            <h3>MODES OF TRANSPORTATION</h3>
            <p>Connecting Markets through Land, Air, and Water.</p>
        </div>

    </div>
</div>

<!-- CONTACT -->
<section id="contact">
    <h2>Contact Us</h2>
    <p style="text-align:center;">
              Phone: 7034089300
     </p>
     <p style="text-align:center;">
             Email: heavenofcrafts@email.com
      </p>
      <p style="text-align:center;">
              Kerala, India
      </p>
</section>

<footer>
    <p>© 2026 HEAVEN OF CRAFTS| All Rights Reserved</p>
</footer>

</body>
</html>
