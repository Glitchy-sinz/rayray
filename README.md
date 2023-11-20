# rayray

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fitfinity</title>
    <link rel="stylesheet" href="ray2.css">
    <!-- Fontawesome Link for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css">
  </head>
  <body>
    <header>
      <nav class="navbar">
        <h2 class="logo"><a href="#">Fitfinity</a></h2>
        <input type="checkbox" id="menu-toggler">
        <label for="menu-toggler" id="hamburger-btn">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="white" width="24px" height="24px">
            <path d="M0 0h24v24H0z" fill="none"/>
            <path d="M3 18h18v-2H3v2zm0-5h18V11H3v2zm0-7v2h18V6H3z"/>
          </svg>
        </label>
        <ul class="all-links">
          <li><a href="#home">Home</a></li>
          <li><a href="#services">Importance of fitness</a></li>
          <li><a href="#portfolio">Our Services</a></li>
          <li><a href="#about"> About Us</a></li>
          <li><a href="#contact">Contact Us</a></li>
          <li><button onclick="document.getElementById('id01').style.display='block'" style="width:auto;">Login</button></li>
          <div id="id01" class="modal">
  
            <form class="modal-content animate" action="/action_page.php" method="post">
              <div class="imgcontainer">
                <span onclick="document.getElementById('id01').style.display='none'" class="close" title="Close Modal">&times;</span>
                <img src="img_avatar2.png" alt="Avatar" class="avatar">
              </div>
          
              <div class="container">
                <label for="uname"><b>Username</b></label>
                <input type="text" placeholder="Enter Username" name="uname" required>
          
                <label for="psw"><b>Password</b></label>
                <input type="password" placeholder="Enter Password" name="psw" required>
                  
                <button type="submit">Login</button>
                <label>
                  <input type="checkbox" checked="checked" name="remember"> Remember me
                </label>
              </div>
          
              <div class="container" style="background-color:#ffffff">
                <button type="button" onclick="document.getElementById('id01').style.display='none'" class="cancelbtn">Cancel</button>
                <span class="psw"><a href="#" style="color: black;">Forget password?</a></span>
              </div>
            </form>
          </div>
          
          <script>
          // Get the modal
          var modal = document.getElementById('id01');
          
          // When the user clicks anywhere outside of the modal, close it
          window.onclick = function(event) {
              if (event.target == modal) {
                  modal.style.display = "none";
              }
          }
          </script>
          
        </ul>
      </nav>
    </header>

    <section class="homepage" id="home">
      <div class="content">
        <div class="text">
            
          <h1>Fitfinity</h1>
          <P>Precision Training,Personalised Progress,Peak Performance</P>
        </div>
        <a href="#services">Let's begin !!</a>
      </div>
    </section>

    <section class="services" id="services">
      <h2>Learn more about fitness</h2>
      
      <ul class="cards">
        <li class="card">
        <!--  <img src="..." alt="img"> -->
          <h3>Physical Fitness</h3>
          <p>
            Fitness is a multifaceted concept encompassing physical, mental, and emotional well-being. It is the cornerstone of a healthy and fulfilling life. Physical fitness is perhaps the most visible aspect, focusing on strength, endurance, flexibility, and cardiovascular health. Regular exercise is essential for achieving and maintaining physical fitness. Activities like running, swimming, weightlifting, and yoga cater to different aspects of physical fitness.

            Exercise not only strengthens muscles and bones but also enhances mood and reduces the risk of chronic diseases like heart disease and diabetes. It fosters a sense of accomplishment and self-confidence.
          </p>
        </li>

        <li class="card">
        <!--  <img src="..." alt="img"> -->
        <h3>Mental Fitness</h3>
        <p>
            Mental fitness is equally important. Practices like meditation and mindfulness promote mental clarity and emotional stability. A healthy mind is more resilient to stress and better equipped to cope with life's challenges.

            Balancing physical and mental fitness is key to overall well-being. Setting fitness goals and tracking progress can be motivating. It's essential to find activities you enjoy to stay consistent. Nutrition plays a crucial role, providing the body with the fuel it needs to perform at its best.
        </p>
        </li>

        <li class="card">
        <!--  <img src="..." alt="img"> -->
        <h3>Importance of fitness</h3>
          <p>
            Additionally, social support is vital. Group fitness classes or workout buddies can provide motivation and accountability. Adequate sleep and stress management complete the equation for optimal fitness.

            In conclusion, fitness is a holistic concept, encompassing physical, mental, and emotional well-being. Regular exercise, proper nutrition, and mental wellness practices are all essential components of a fit and healthy life. Prioritizing fitness leads to increased vitality, longevity, and an improved overall quality of life.
          </p>
        </li>

      </ul>
    </section>

    <section class="portfolio" id="portfolio">
      <h2>Our Services</h2>
      <p>Explore our wide range of services.</p>
      <ul class="cards">
        <li class="card">
          <!--<img src="..." alt="img">-->
          
          <div class="omni-calculator" data-calculator="health/bmi" data-width="300" data-config='{}' data-currency="INR" data-show-row-controls="false" data-version="3" data-t="1696791718865">
            <div class="omni-calculator-header">BMI Calculator – Body Mass Index</div>
            <div class="omni-calculator-footer">
              <a href="https://www.omnicalculator.com/health/bmi" target="_blank"></a>
            </div>
          </div>
          <script async src="https://cdn.omnicalculator.com/sdk.js"></script>
        </li>



        <li class="card">
            <!--<img src="..." alt="img">-->
            
            <div class="omni-calculator" data-calculator="sports/running-calorie" data-width="300" data-config='{}' data-currency="INR" data-show-row-controls="false" data-version="3" data-t="1696795684036">
                <div class="omni-calculator-header">Running Calorie Calculator – Calories Burned Running</div>
                <div class="omni-calculator-footer">
                  <a href="https://www.omnicalculator.com/sports/running-calorie" target="_blank"></a>
                </div>
              </div>
              <script async src="https://cdn.omnicalculator.com/sdk.js"></script>
          </li>


          
          <li class="card">
            <!--<img src="..." alt="img">-->
            <div class="omni-calculator" data-calculator="health/ideal-weight" data-width="300" data-config='{}' data-currency="INR" data-show-row-controls="false" data-version="3" data-t="1696795909661">
                <div class="omni-calculator-header">Ideal Weight Calculator</div>
                <div class="omni-calculator-footer">
                  <a href="https://www.omnicalculator.com/health/ideal-weight" target="_blank"></a>
                </div>
              </div>
              <script async src="https://cdn.omnicalculator.com/sdk.js"></script>
          </li>



          <li class="card">
            <!--<img src="..." alt="img">-->
            <div class="omni-calculator" data-calculator="health/calorie" data-width="300" data-config='{}' data-currency="INR" data-show-row-controls="false" data-version="3" data-t="1696796064290">
                <div class="omni-calculator-header">Calorie Calculator</div>
                <div class="omni-calculator-footer">
                  <a href="https://www.omnicalculator.com/health/calorie" target="_blank"></a>
                </div>
              </div>
              <script async src="https://cdn.omnicalculator.com/sdk.js"></script>
          </li>



          <li class="card">
            <!--<img src="..." alt="img">-->
            <div class="omni-calculator" data-calculator="health/sleep" data-width="300" data-config='{}' data-currency="INR" data-show-row-controls="false" data-version="3" data-t="1696796146963">
                <div class="omni-calculator-header">Sleep Calculator</div>
                <div class="omni-calculator-footer">
                  <a href="https://www.omnicalculator.com/health/sleep" target="_blank"></a>
                </div>
              </div>
              <script async src="https://cdn.omnicalculator.com/sdk.js"></script>
          </li>



          <li class="card">
            <!--<img src="..." alt="img">-->
            <div class="omni-calculator" data-calculator="health/waist-height-ratio" data-width="300" data-config='{}' data-currency="INR" data-show-row-controls="false" data-version="3" data-t="1696796280834">
  <div class="omni-calculator-header">Waist to Height Ratio Calculator</div>
  <div class="omni-calculator-footer">
    <a href="https://www.omnicalculator.com/health/waist-height-ratio" target="_blank"></a>
  </div>
</div>
<script async src="https://cdn.omnicalculator.com/sdk.js"></script>
          </li>
      </ul>
    </section>

    <section class="about" id="about">
      <h2>About Us</h2>
      <p>Discover our story </p>
      <div class="row company-info">
        <h3>Our Story</h3>
        <p>Our fitness tracker app began with a shared passion for health and well-being. A group of like-minded individuals, dedicated to making a positive impact on people's lives, came together to create a platform that would inspire and empower users on their fitness journeys. Our story is one of innovation, dedication, and a commitment to providing users with the tools and motivation they need to achieve their fitness goals. With a focus on user-friendly design, accurate tracking, and personalized guidance, we aim to make fitness accessible to all and help individuals lead healthier, happier lives. Our journey is just beginning, and we're excited to be a part of yours as you strive for a healthier, more active lifestyle.</p>
      </div>
      <div class="row mission-vision">
        <h3>Our Mission</h3>
        <p>Our mission is to transform lives through fitness by providing a comprehensive and intuitive tracking experience. We're dedicated to making fitness a seamless and enjoyable part of everyday life, regardless of your fitness level or goals. Our app is designed to empower individuals to take control of their health, set and achieve meaningful fitness milestones, and ultimately, lead healthier and happier lives. With data-driven insights, personalized guidance, and a supportive community, our mission is to inspire and guide you on your journey to becoming the best version of yourself, one step at a time.</p>
        <h3>Our Vision</h3>
        <p>Our vision is to create a world where everyone is motivated and equipped to live their healthiest lives. We envision a future where our fitness tracker app becomes an integral part of people's daily routines, seamlessly integrating with their lifestyles. We aim to lead the way in technological innovation, constantly evolving our platform to deliver the most accurate data, insightful analytics, and personalized recommendations. In this vision, we see a global community of individuals supporting and motivating each other, transcending boundaries and inspiring fitness journeys that transcend generations. Our ultimate goal is to foster a healthier, happier, and more active world, where fitness is accessible, enjoyable, and achievable for all.</p>
      </div>
      <div class="row team">
        <h3>Our Team</h3>
        <ul>
          <li>Shreya BIN LADEN - Founder and CEO</li>
          <li>Sidarth Jain - Weapons Specialist</li>
          <li>Shubham Jindal - Customer Representative</li>
            </ul>
      </div>
           
    </section>

    
    <section class="contact" id="contact">
        <h2>Contact Us</h2>
        <p>Reach out to us for any inquiries or feedback.</p>
        <div class="row">
          <div class="col information">
            <div class="contact-details">
              <p><i class="fas fa-map-marker-alt"></i> 123 Campsite Avenue, Wilderness, CA 98765</p>
              <p><i class="fas fa-envelope"></i> rayray101@gmail.com</p>
              <p><i class="fas fa-phone"></i> (123) 456-7890</p>
              <p><i class="fas fa-clock"></i> Monday - Friday: 9:00 AM - 5:00 PM</p>
              <p><i class="fas fa-clock"></i> Saturday: 10:00 AM - 3:00 PM</p>
              <p><i class="fas fa-clock"></i> Sunday: Closed</p>
              <p><i class="fas fa-globe"></i> www..com</p>
            </div>          
          </div>
          <div class="col form">
            <form>
              <input type="text" placeholder="Name*" required>
              <input type="email" placeholder="Email*" required>
              <textarea placeholder="Message*" required></textarea>
              <button id="submit" type="submit">Send Message</button>
            </form>
          </div>
        </div>
      </section>
    
    <footer>
      <div>
        <span>Copyright © 2023 All Rights Reserved</span>
        <span class="link">
            <a href="#">Home</a>
        </span>
      </div>
    </footer>

  </body>
</html>
