<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Foodixo - Restaurant</title>
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  
  <!-- Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

<!-- Google Fonts: Great Vibes for chef name -->
<link href="https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap" rel="stylesheet">


</head>


  

<body>
  <!-- Navbar -->
  <header class="navbar">
    <div class="logo">foodixo</div>
    
     <!-- Hamburger icon -->
  <div class="hamburger" onclick="toggleMenu()">
    <i class="fas fa-bars"></i>
  </div>

  <!-- Navigation Links -->
  <nav id="navLinks" class="nav-links">
      <a href="index.html">Home</a>
      <a href="about.html">About</a>
     
      <a href="Blog.html">Blog</a>
  
      <div class="dropdown">
        <a href="" class="dropdown-toggle">Pages ▾</a>  
        <div class="dropdown-menu"> 
          <a href="reservation.html">Reservation</a>
          <a href="Services.html">Services</a>
          <a href="Menu.html">Menu</a>
        </div>
      </div>
      
      
  
      <a href="Contact.html">Contact</a>
 
    <div class="contact">
      <span class="phone">+1 800 637 81 94</span>
      <a href="Reservation.html"><button class="btn">Book A Table</button></a>
    </div>

  </nav>
  </header>


  

  <!-- Hero Slider Section -->
  <section class="slider">
    <div class="slides">
      <div class="slide active">
        <img src="Section1/homepage.jpg" alt="Slide 1">
        <div class="slide-content">
          <p class="subheading">List of Types of Seafood</p>
          <h1>DAILY FRESH<br>MEAT FOOD</h1>
          <a href="Reservation.html"><button class="btn">Book A Table</button></a>
        </div>
      </div>
  
      <div class="slide">
        <img src="Section1/homepage1.jpg" alt="Slide 2">
        <div class="slide-content">
          <p class="subheading">Taste Our New Dishes</p>
          <h1>THE BEST<br>FOOD EXPERIENCE</h1>
          <a href="Reservation.html"><button class="btn">Book A Table</button></a>
        </div>
      </div>
    </div>
  
  </section>
  


    <!--Section 2-->
    <section class="restaurant-section">
      <div class="container">
        <div class="left-column">
          <h4 class="subtitle">Welcome Our Restaurant</h4>
          <h1 class="main-title">Come to Our Restaurant, Taste Food</h1>
          <p class="description">
            Integer aliquam nisi sit amet magna suscipit, fermentum mattis erat rutrum. 
            Suscipit libero lectus, at ullamcorper erat feugiat eu. Nam posuere ultrices 
            nibh ut sagittis. Etiam arcu turpis, elementum ac nulla tristique cursus libero.
          </p>
          <img src="Section 2/Chef.jpg" alt="Chef Cooking" class="chef-image">
        </div>
  
        <div class="right-column">
          <div class="mission-box">
            <h3>Our Mission</h3>
            <p class="description2">Our Restaurant is the best as like delicious food nutrition food in world-wide.</p>
            <div class="schedule-box">
              <img src="Section 2/hipon.jpg" alt="Shrimp Dish" class="schedule-img">
              <div class="timing">
                <p><strong>BF:</strong> 6am – 9:30am</p>
              <p><strong>Lunch:</strong> 10:30am – 1pm</p>
              <p><strong>Dinner:</strong> 5pm – 11pm</p>
              </div>
            </div>
          </div>
  
          <div class="food-container">
            <div class="food-item">
              <img src="Section2 4pics/manok.png" alt="Sea Food" class="zoomable" onclick="zoomContent(this)">
              <p>Sea Food</p>
            </div>
            <div class="food-item">
              <img src="Section2 4pics/palabok.png" alt="Sea Food" class="zoomable" onclick="zoomContent(this)">
              <p>Sea Food</p>
            </div>
            <div class="food-item">
              <img src="Section2 4pics/pancit hipon.png" alt="Meat" class="zoomable" onclick="zoomContent(this)">
              <p>Meat</p>
            </div>
            <div class="food-item">
              <img src="Section2 4pics/Vegetable.png" alt="Thai Soup" class="zoomable" onclick="zoomContent(this)">
              <p>Thai Soup</p>
            </div>
          </div>
    
    </section>




    <!--Menu Section 3-->

    <section class="menu-section">
      <h2>BEST FOOD AT THE <br> BEST PRICE</h2>

      <div class="menu-item" onclick="zoomContent(this)">
          <img src="Section 4/menu-01.jpg" alt="Raw Marbled Meat Steak">
          <div class="menu-details">
              <h4>Raw Marbled Meat Steak</h4>
              <p>Free range eggs (poached, scrambled or fried) with bacon, chorizo, roasted roma tomatoes, mushrooms & spinach</p>
          </div>
          <div class="menu-price">$7.50</div>
      </div>

      <div class="menu-item" onclick="zoomContent(this)">
          <img src="Section 4/menu-02.jpg" alt="Awesome Raw Marbled Meat Steak">
          <div class="menu-details">
              <h4>Awesome Raw Marbled Meat Steak</h4>
              <p>Free range eggs (poached, scrambled or fried) with bacon, chorizo, roasted roma tomatoes, mushrooms & spinach</p>
          </div>
          <div class="menu-price">$7.50</div>
      </div>

      <div class="menu-item" onclick="zoomContent(this)">
          <img src="Section 4/menu-03.jpg" alt="Raw Meat With Spices">
          <div class="menu-details">
              <h4>Raw Meat With Spices</h4>
              <p>Free range eggs (poached, scrambled or fried) with bacon, chorizo, roasted roma tomatoes, mushrooms & spinach</p>
          </div>
          <div class="menu-price">$7.50</div>
      </div>
  </section>

    
    
    <!--Meals Section 4-->
    <section class="meals-section">
      <div class="meals-images">
        <img src="Section 5/PIC1.png" alt="Rotating Image">
      </div>
  
      
      <div class="meals-content">
        <h2>We Always <br> Prepare The Meals For You</h2>
        <p>
          Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old.
        </p>
        <a href="Blog.html"><button class="btn">Read More</button></a>
      </div>
    </section>


    <!--Section 5 -->
    <section class="testimonial-section">
      <div class="testimonial-content">
        <h2>OUR CLIENT</h2>
        <p>
          It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout.
        </p>
        <div class="quote">“</div>
        <div class="client-name">Smith M.</div>
      </div>
  
      <div class="testimonial-image">
        <img src="Section 2/Chef.jpg" alt="Sketch of Restaurant">
      </div>
    </section>



    <!--Section 6-->
    <section class="blog-section">
      <h2 class="section-title">🍽️ LATEST UPDATE AND NEWS</h2>
      <p class="section-subtitle">Fresh stories, updates, and happenings from our restaurant</p>
    
      <div class="blog-container">
        <div class="blog-card" onclick="openModal(0)">
          <div class="blog-image">
            <img src="Section 7/pic1.jpg" alt="Blog 1">
            <span class="blog-date">29 Dec, 2023</span>
          </div>
          <div class="blog-content">
            <h3>🎉 Memorable Events</h3>
            <p>Experience the magic of gourmet evenings with live music, themed nights, and amazing food!</p>
          </div>
        </div>
    
        <div class="blog-card" onclick="openModal(1)">
          <div class="blog-image">
            <img src="Section 7/pic2.jpg" alt="Blog 2">
            <span class="blog-date">29 Dec, 2023</span>
          </div>
          <div class="blog-content">
            <h3>🛋️ Interior Makeover</h3>
            <p>We revamped our restaurant’s look with cozy lighting, vintage decor, and elegant vibes.</p>
          </div>
        </div>
    
        <div class="blog-card" onclick="openModal(2)">
          <div class="blog-image">
            <img src="Section 7/pic3.jpg" alt="Blog 3">
            <span class="blog-date">29 Dec, 2023</span>
          </div>
          <div class="blog-content">
            <h3>🇮🇹 Authentic Italian</h3>
            <p>Discover our chef’s favorite Italian dishes inspired by tradition and local ingredients.</p>
          </div>
        </div>
      </div>
    </section>
    
    <!-- Modal -->
    <div id="blogModal" class="modal">
      <div class="modal-content">
        <span class="close" onclick="closeModal()">&times;</span>
        <h2 id="modalTitle"></h2>
        <img id="modalImage" src="" alt="Blog Image">
        <p id="modalText"></p>
      </div>
    </div>
    


  

    <!-- Reservation Form Section 7 -->
  <section class="reservation-section">
    <div class="reservation-box">
      <h2>MAKE A RESERVATION</h2>
      <p class="desc">Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old.</p>

      <form class="reservation-form">
        <input type="text" placeholder="Full Name" required>
        <input type="tel" placeholder="Phone" required>

        <div class="form-row">
          <select>
            <option>1 Person</option>
            <option>2 Persons</option>
            <option>3 Persons</option>
            <option>4+ Persons</option>
          </select>
          <input type="date" required>
        </div>

        <input type="time" required>

        <button type="submit" class="book-btn">Book A Table</button>
      </form>
    </div>
  </section>

    <!--Section 8 Footer-->
    <footer class="footer">
      <div class="footer-container">
    
        <div class="footer-column newsletter">
          <h4>Sign Up Newsletter</h4>
          <div class="newsletter-form">
            <input type="email" placeholder="Enter your email">
            <button><span>&rarr;</span></button>
          </div>
        </div>
    
        <div class="footer-column">
          <h4>Contacts</h4>
          <p>Purple Sunset Avenue</p>
          <p>Brooklyn Sweden</p>
          <p>Info@Support.Com</p>
        </div>
    
        <div class="footer-column">
          <h4>Menu</h4>
          <ul>

            <li><a href="index.html">Home</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="Menu.html">Menu</a></li>
            <li><a href="Blog.html">Blog</a></li>
            <li><a href="pages.html">Pages ▾</a></li>
            <li><a href="Contact.html">Contact</a></li>
           
          </ul>
        </div>
    
        <div class="footer-column">
          <h4>Working Hours</h4>
          <p>Monday – Sunday: 2pm – 2pm</p>
          <p>Lunch: 12pm – 2pm</p>
          <p>Dinner: 6pm – 10pm</p>
          <p>Happy Hours: 4pm – 6pm</p>
        </div>
      </div>
    
      <div class="footer-bottom">
        <div class="footer-logo">foodixo</div>
        <div class="footer-copy">&copy; 2025 - WordPress Theme by Code4rest</div>
        <button id="backToTopBtn" title="Go to top">↑</button>
      </div>
    </footer>
    
    
            
    





     <!-- Slider Section 1-->
    <button class="prev" onclick="prevSlide()">❮</button>
    <button class="next" onclick="nextSlide()">❯</button>

  <script src="script.js"></script>
  <script src="Blog.js"></script>
  <script src="BTT.js"></script>
 
  
  
  
  <script>
    function toggleMenu() {
      const nav = document.getElementById("navLinks");
      nav.classList.toggle("active");
    }
  </script>
  

</body>
</html>

with new navbar responsive for mobile and tablet

{

  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Georgia', serif;
}


/* Navbar */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 80px;
  position: absolute;
  width: 100%;
  top: 0;
  z-index: 100;
  background: transparent;
  border-bottom: 1px solid white;
}

.logo {
  font-size: 30px;
  font-weight: bold;
  color: #fff;
}

/* Contact Number Navbar */
.phone {
  color: white;
  font-weight: bold;
  padding-left: 50px;
}

.nav-links {
  color:white;
  display: flex;
  gap: 1.5rem;
  align-items: center;
}  

.nav-links a {
  margin: 0 20px;
  text-decoration: none;
  color: white;
  font-size: 16px;
 
}

.nav-links a:hover {
  color: #f9a825;
}

.dropdown {
  position: relative;
}

/* box- color */
.dropdown-menu {
  display: none;
  position: absolute;
  top: 100%;
  left: 0;
  background: black;
  padding: 10px 0;
  min-width: 160px;
  border-radius: 6px;
  z-index: 10;
  box-shadow: 0 4px 8px rgba(255, 238, 238, 0.1);
  flex-direction: column;
}

/* word color */
.dropdown-menu a { 
  display: block;
  padding: 10px 20px;
  color: white;
  white-space: nowrap;
  text-decoration: none;
  transition: background 0.3s ease;
}

.dropdown-menu a:hover {
  background: #333;
  color: #f9a825;
}

.dropdown:hover .dropdown-menu {
  display: flex;
}

/* Hamburger icon */
.hamburger {
  display: none;
  font-size: 24px;
  cursor: pointer;
  color: white;
}








/* Responsive Styles for Navbar and Slider */

/* Tablet and smaller devices (≤ 768px) */
@media (max-width: 768px) {
  /* Navbar adjustments */
  .navbar {
    flex-direction: row;
    padding: 15px 30px;
    background: rgba(0, 0, 0, 0.85); /* Make it visible on scroll */
    border-bottom: none;
  }

  .hamburger {
    display: block;
    font-size: 26px;
    cursor: pointer;
    color: white;
  }

  .nav-links {
    display: none;
    flex-direction: column;
    background: #111;
    position: absolute;
    top: 60px;
    left: 0;
    width: 100%;
    padding: 20px;
    z-index: 99;
  }

  .nav-links.active {
    display: flex;
  }

  .nav-links a {
    margin: 10px 0;
    font-size: 16px;
  }

  .contact {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 10px;
  }

  .phone {
    padding-left: 0;
  }

  .btn {
    padding: 8px 16px;
    font-size: 14px;
  }

  /* Slider adjustments */
  .slide img {
    width: 100vw;
    height: 100vh;
    object-fit: cover;
  }

  .slide-content {
    top: 20%;
    left: 5%;
    padding-right: 5%;
  }

  .slide-content h1 {
    font-size: 34px;
    line-height: 1.3;
  }
}

/* Mobile devices (≤ 425px) */
@media (max-width: 425px) {
  .slide-content h1 {
    font-size: 24px;
  }

  .btn {
    padding: 6px 12px;
    font-size: 13px;
  }

  .slide-content {
    top: 18%;
  }

  .hamburger {
    font-size: 24px;
  }
}

















.services-section {
  padding: 80px 20px;
  background: linear-gradient(to right, #fffaf5, #fff1e0);
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  text-align: center;
}

.section-title {
  font-size: 42px;
  margin-bottom: 10px;
  font-weight: 700;
  color: #222;
}

.section-subtitle {
  font-size: 18px;
  color: #666;
  margin-bottom: 50px;
}

.services-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 30px;
}

.service-card {
  background-color: #fff;
  border-radius: 16px;
  overflow: hidden;
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.08);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.service-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 16px 32px rgba(0, 0, 0, 0.15);
}

.service-img img {
  width: 100%;
  height: 200px;
  object-fit: cover;
  transition: transform 0.4s ease;
}

.service-card:hover .service-img img {
  transform: scale(1.05);
}

.service-card h3 {
  font-size: 22px;
  margin: 20px 0 10px;
  color: #222;
}

.service-card p {
  padding: 0 20px 20px;
  font-size: 15px;
  color: #555;
  line-height: 1.6;
}




.contact {
  color: white;
  display: flex;
  align-items: center;
  gap: 20px;
}

.btn {
  background-color: #a8742c;
  color: white;
  border: none;
  padding: 10px 18px;
  cursor: pointer;
  font-weight: bold;
}

.btn:hover {
  background-color: #ffcc00;
}

/* End Of Navbar */










  /* Slider Section */
  .slider {
    position: relative;
    width: 100%;
    height: 100vh;
    overflow: hidden;
  }

  .slides {
    display: flex;
    width: 200%; 
    transition: transform 0.5s ease;



  }

  .slide {
    width: 100%;
    flex-shrink: 0;
    position: relative;
  }

  .slide img {
    width: 220vh;
    height: 100vh;
    object-fit: cover;
  }


  .slide-content h1 {
    font-size: 60px;
    line-height: 1.2;
    font-weight: 400;
    margin-bottom: 20px;
  }

 
  .btn {
    display: inline-block;
    background: #c49b6e;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 10px;
    transition: background 0.3s;
  }
  
  .btn:hover {
    background: #8C6239;
  }
  

  .slide-content {
    position: absolute;
    top: 30%;
    left: 5%;
    color: white;
    z-index: 2;
    opacity: 0;
    transform: translateY(20px);
    animation: fadeSlide 2s ease-in-out forwards;
  }
  

  /* Animation keyframes */
  @keyframes fadeSlide {
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }


  
 
  
 
 /* Responsive style Mobile */
 @media (max-width: 375px){
   .slide img{
    
   }
 }
  
  @media (max-width: 768px) {
    
    
  }
  

  



/* list of types of seafood alignment */
.subheading {
  font-size: 16px;
  margin-bottom: 10px;
}


.prev,
.next {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  font-size: 30px;
  background-color: darkgoldenrod;
  color:white;
  border: none;
  padding: 10px 20px;
  cursor: pointer;
  border-radius: 50%; /* Circle buttons */
  z-index: 5;
}

.prev {
  left: 15px;
}

.next {
  right: 15px;
}

/* END OF SECTION 1 */




/* SECTION 2*/
.restaurant-section {
  background-color:white;
  padding: 60px 30px;
}

.container {
  display: flex;
  flex-wrap: wrap;
  gap: 40px;
  justify-content: center;
  max-width: 1200px;
  margin: auto;
}

.left-column, .right-column {
  flex: 1 1 450px;
}

.subtitle {
  text-align: left;
  color: #ff5c00;
  font-style: italic;
  margin-bottom: 10px;
}

.main-title {
  text-align: left;
  color:black;
  font-size: 2.5rem;
  margin-bottom: 20px;
}

.description {
  text-align: left;
  margin-bottom: 30px;
  color: black;
}

.chef-image {
  width: 100%;
  max-width: 500px;
  border-radius: 12px;
  margin-top: 20px;
}



.mission-box h3 {
  text-align: left;
  color:black;
  margin-bottom: 10px;
  font-size: 1.5rem;
}

.description2{
  text-align: left;
  color: black; 
}



.schedule-box {
  display: flex;
  align-items: center;
  max-width: 500px;
  height: 40vh;
  margin-top: 50px;
  gap: 20px;
  background-color: #1d1d3c;
  padding: 15px;
  border-radius: 12px;
  color: #fff;
}

.schedule-img {
  width: 100%;
  max-width: 300px;
  height: 35vh;
  object-fit: cover;
  border-radius: 50%;
}

.timing p {
  margin-bottom: 5px;
  font-size: 0.95rem;
}

@media (max-width: 768px) {
  .left-column{
    padding-right: 30px;
  }
  .subtitle{
    padding-left: 30px;
  }
  .main-title{
    padding-left: 25px;
  }
  .description{
    padding-left: 25px;
  }
  .chef-image{
    height: 40vh;
    width:600vh;
  }
  .mission-box h3{
   text-align: left;
   padding-right:50px;
  }

  .description2{
   text-align: left;
  }

  .right-column{
   padding-left: 30px;
 
  }

  .mission-box{
   padding-left: 70px
  }
  .schedule-img{
    height:40vh;
    width:600vh;
  }
  .food-container{
  padding-right:20px;
  }
}




/* FOOD CATEGORIES */
.food-container {
  display: flex;
  justify-content: center;
  gap: 30px;
  margin-top: 50px;
}

.food-item {
  text-align: center;

  position:relative;
}

.food-item p{
  color:white;
}

.food-item img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  border: 5px solid transparent;
  transition: transform 0.1s ease-in-out;
  cursor: pointer;
}

.food-item img:hover {
  border-color: white;
}

.zoomed {
  transform: scale(2);
  z-index: 100;
}

/* END OF SECTION2 */










/*Section 3 1st page */
.hero {
  background: url('Reservation\ bg.jpg');
  height: 50vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  position: relative;
  color: white;
}

.hero-overlay {
  background: rgba(0, 0, 0, 0.5);
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}

.hero h1 {
  font-size: 2.5rem;
  font-weight: bold;
}











/* Services Section */
.container {
  width: 80%;
  margin: auto;
  padding: 50px 0;
}

.service-item {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-bottom: 50px;
}

.text-content {
  width: 50%;
  padding: 20px;
}

.text-content h2 {
  font-size: 1.8rem;
  color: #000;
}

.text-content h3 {
  font-size: 1.2rem;
  color: #A67B5B;
  margin-bottom: 10px;
}

.text-content p {
  font-size: 1rem;
  line-height: 1.6;
}

.text-content ul {
  list-style: none;
  padding: 0;
}

.text-content ul li {
  font-size: 1rem;
  padding-left: 20px;
  position: relative;
}

.text-content ul li::before {
  content: "✔";
  color: #A67B5B;
  font-weight: bold;
  position: absolute;
  left: 0;
}

.image-content {
  width: 45%;
}

.image-content img {
  width: 100%;
  border-radius: 10px;
}

/* Button */
.btn {
  display: inline-block;
  background: #c49b6e;
  color: white;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 5px;
  margin-top: 10px;
  transition: background 0.3s;
}

.btn:hover {
  background: #8C6239;
}

/* Reverse Layout for Second Item */
.reverse {
  flex-direction: row-reverse;
}

/* Responsive */
@media (max-width: 768px) {
  .service-item {
      flex-direction: column;
      text-align: center;
  }

  .text-content, .image-content {
      width: 100%;
  }

  .reverse {
      flex-direction: column;
  }
}










/* SECTION 3 All Dishes*/
.container {
  width: 90%;
  max-width: 1300px;
  margin: 40px auto;
}

.section-title {
  color:black;
  text-align: center;
  font-size: 2.2rem;
  font-weight: bold;
  font-family: 'Georgia', serif;
  margin: 40px 0 20px;  
}

.card-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 50px;
  margin-bottom: 40px;
}

.card {
  border: 2px solid lightgrey;
  background-color:white;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.08);
  width: 220px;
  padding: 10px;
  text-align: center;
  transition: 0.3s ease;
}

.dish-card {
  padding: 20px;
  position: relative;
  background: #fff;
  border: 2px solid lightgrey;
  border-radius: 10px;
  width: 220px;
  text-align: center;
  box-shadow: 0 2px 10px rgba(0,0,0,0.05);
  transition: transform 0.3s ease;
}


.card:hover {
  transform: translateY(-5px);
  background-color: lightcoral;
  box-shadow: 0 8px 20px rgba(0,0,0,0.1);
}

.card img {
  width: 150px;
  height:150px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 10px;
}

.stars {
  text-align: left;
  color: gold;
  font-size: 20px;
  
}



.dish-title {
  font-size: 0.95rem;
  font-weight: 500;
  text-align: left;
  margin: 8px 0;
  color: black;
}

.price {
  text-align: left;
  color: #f26c00;
  font-size: 1rem;
  font-weight: bold;
}






/* Section 4 Menu */
.menu-section {
  padding: 40px;
}

h2 {
  font-size: 28px;
  margin-bottom: 20px;
  text-align: center;
}

.menu-item {
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 60%;
  margin: 10px auto;
  padding: 15px;
  background: white;
  border-radius: 10px;
  box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
  cursor: pointer;
  transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
}

.menu-item img {
  width: 100px;
  height: 100px;
  border-radius: 10px;
  transition: transform 0.3s ease-in-out;
}

.menu-details {
  flex-grow: 1;
  text-align: left;
  margin-left: 15px;
}

.menu-price {
  font-weight: bold;
  color: orange;
}

/* Zoom effect */
.zoomed {
  transform: scale(1.2);
  box-shadow: 4px 4px 20px rgba(0, 0, 0, 0.2);
}

@media (max-width: 768px) {
  .menu-item {
    flex-direction: column;
    align-items: flex-start;
  }
  .menu-price {
    margin-left: 0;
    margin-top: 10px;
  }
}






/*Meals Section 5 */
.meals-section {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 60px;
  padding: 80px 60px;
  flex-wrap: wrap;
}


.meals-content {
  max-width: 500px;
}

.meals-content h2 {
  text-align: left;
  font-size: 35px;
  font-weight: 600;
  line-height: 1.3;
  margin-bottom: 20px;
  color: black;
}

.meals-content p {
  font-size: 14px;
  color: #444;
  margin-bottom: 30px;
  line-height: 1.6;
}










/* Meals Image Rotating Section */
.meals-images {
  width: 400px;
  height: 400px;
}
.meals-images img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 50%;
  animation: rotate 15s linear infinite;
}
@keyframes rotate {
  from {
      transform: rotate(0deg);
  }
  to {
      transform: rotate(360deg);
  }
}





/* Meals Button */
.meals-content .read-more-btn {
  padding: 12px 28px;
  background-color: #9a6b2f;
  color: #fff;
  border: none;
  font-size: 15px;
  border-radius: 4px;
  cursor: pointer;
  transition: background 0.3s ease;
}

.meals-content .read-more-btn:hover {
  background-color: #7c501a;
}

@media (max-width: 768px) {
  .meals-section {
    flex-direction: column;
    text-align: center;
  }

  .meals-content h2 {
    font-size: 32px;
  }

}











/*Section 6 */
.testimonial-section {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 80px 60px;
  background-color: #fdf7f0;
  flex-wrap: wrap;
}

.testimonial-content {
  max-width: 500px;
}

.testimonial-content h2 {
  color:black;
  padding-left: 160px;
  font-size: 40px;
  font-weight: 600;
  margin-bottom: 20px;
}

.testimonial-content p {
  padding-left: 160px;
  color: #333;
  left: 10px;
  line-height: 1.7;
  margin-bottom: 20px;
}

.testimonial-content .quote {
  padding-left: 160px;
  font-size: 40px;
  color: #b38b4d;
  margin-bottom: 5px;
}

.testimonial-content .client-name {
  padding-left:160px;
  font-size: 16px;
  font-weight: bold;
  color: #000;
}

.testimonial-image {
  max-width: 450px;
}

.testimonial-image img {
  width: 100%;
  height: auto;
}

@media (max-width: 768px) {
  .testimonial-section {
    flex-direction: column;
    text-align: center;
  }

  .testimonial-image {
    margin-top: 40px;
  }
}

  .testimonial-content h2{
    padding-left: 20px;
  }
  
  .testimonial-content p{
    padding-left: 20px;
  }

  .testimonial-content .quote{
    padding-left: 20px;
  }

  .testimonial-content .client-name{
    padding-left: 20px;
  }










/*Section 7 Our Blog */
.blog-section {
  padding: 40px;
}

h2 {
  font-size: 28px;
  margin-bottom: 20px;
}

.blog-container {
  display: flex;
  justify-content: center;
  gap: 20px;
  flex-wrap: wrap;
}

.blog-item {
  position: relative;
  width: 300px;
  border-radius: 10px;
  overflow: hidden;
  cursor: pointer;
  background: white;
  box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease-in-out;
}

.blog-item:hover {
  transform: scale(1.05);
}

.blog-item img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

.blog-date {
  position: absolute;
  top: 10px;
  left: 10px;
  background: orange;
  color: white;
  padding: 5px 10px;
  font-size: 12px;
  border-radius: 5px;
}

.blog-details {
  padding: 15px;
  text-align: left;
}

.blog-details h4 {
  margin: 0;
  font-size: 18px;
}

.blog-details p {
  font-size: 14px;
  color: #555;
}

/* Hidden Content */
.blog-content {
  display: none;
  margin-top: 20px;
  padding: 20px;
  background: white;
  box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
  border-radius: 10px;
  text-align: left;
  width: 60%;
  margin: auto;
}

.close-btn {
  background: red;
  color: white;
  border: none;
  padding: 10px;
  margin-top: 10px;
  cursor: pointer;
  border-radius: 5px;
}
@media (max-width: 1000px) {
  .news-cards {
    flex-direction: column;
    align-items: center;
  }
}
/* End Of Section 7 */










/* Reservation Section 8 */
/* Blog Section */

.hero {
  background-color: black;
  background-size: cover;
  background-position: center;
  height: 300px;
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
}

.hero-overlay {
  text-align: center;
  padding: 30px;
  width: 100%;
}

.hero h1 {
  font-size: 48px;
  color: white;
  letter-spacing: 2px;
}

.hero p {
  margin-top: 10px;
  color: #ccc;
  font-size: 16px;
}

.hero p a {
  color: #fff;
  text-decoration: none;
  align-items: center;
  text-align: center;
  justify-content: center;
  flex-direction: column;
  margin-bottom: 0;
}


.home-icon {
  font-size: 40px; 
  color: white;
  text-decoration: none;
  margin-bottom: 10px;
  display: inline-block;
}
  


.hero p a:hover {
  text-decoration: underline;
}










/* Reservation Form */
.reservation-section {
  background-color: white;
  justify-content: center;
  padding: 60px 20px;
  display: flex;
  
}



.reservation-box {
  background-color: black;
  color:black;
  max-width: 700px;
  width: 100%;
  padding: 40px;
  text-align: center;
}

.reservation-box h2 {
  color:white;
  font-size: 36px;
  margin-bottom: 15px;
}

.reservation-box .desc {
  font-size: 14px;
  color:white;
  margin-bottom: 30px;
}

.reservation-form input,
.reservation-form select {
  width: 100%;
  padding: 14px;
  margin-bottom: 20px;
  border: 1px solid #ddd;
  outline: none;
  font-size: 16px;
}

.form-row {
  display: flex;
  gap: 15px;
}

.form-row select,
.form-row input {
  flex: 1;
}

.book-btn {
  background: #c49b6e;
  color: white;
  padding: 14px 28px;
  border-radius: 10px;
  cursor: pointer;
  font-size: 16px;
  transition: background 0.3s;
}

.book-btn:hover {
  background: #8C6239;
}


/* End Of Section 8 */










/*Contact Section */
.contact-info, .contact-form, .map {
  color: black;
  flex: 1;
  min-width: 300px;
  padding: 20px;
  box-sizing: border-box;
  margin: 10px;
}

.contact-info h2 {

  text-align: left;
  font-size: 2em;
 
}

.contact-info p {
  font-size: 1.1em;
  margin-bottom: 20px;
}

.contact-info ul {
  list-style-type: none;
  padding: 0;
}

.contact-info ul li {
  font-size: 1.1em;
  margin-bottom: 10px;
}

.contact-form h3 {
  font-size: 1.8em;
  margin-bottom: 20px;
}

.contact-form label {
  font-size: 1.1em;
  margin-bottom: 10px;
  display: block;
}

.contact-form input, .contact-form textarea {
  width: 100%;
  padding: 10px;
  margin-bottom: 20px;
  border: 1px solid #ccc;
  border-radius: 4px;
  font-size: 1em;
}

.contact-form button {
  background-color: #ff6347;
  color: white;
  border: none;
  padding: 12px 20px;
  font-size: 1.1em;
  cursor: pointer;
  border-radius: 4px;
}

.contact-form button:hover {
  background-color: #ff4500;
}

.map iframe {
  width: 100%;
  border-radius: 8px;
  margin-top: 20px;
}










/* Section 9 Footer */
.footer {
  background-color: #111;
  color: white;
  padding: 60px 20px 20px;
  font-family: 'Segoe UI', sans-serif;
}

.footer-container {
  padding-top: 50px;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 40px;
  max-width: 1200px;
  margin: 0 auto 40px;
}

.footer h4 {
  font-size: 16px;
  font-weight: 600;
  margin-bottom: 15px;
}

.footer-column p,
.footer-column a {
  font-size: 14px;
  color: #ccc;
  margin-bottom: 8px;
  text-decoration: none;
}

.footer-column a:hover {
  color: #fff;
}

.newsletter-form {
  display: flex;
  align-items: center;
  gap: 10px;
  border-bottom: 1px solid #ccc;
  padding-bottom: 5px;
}

.newsletter-form input {
  background: transparent;
  border: none;
  outline: none;
  color: #fff;
  font-size: 14px;
  width: 100%;
}

.newsletter-form button {
  background: none;
  border: none;
  color: #fff;
  font-size: 18px;
  cursor: pointer;
  padding: 0;
}

.footer-bottom {
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-top: 1px solid #222;
  padding-top: 20px;
  max-width: 1200px;
  margin: 0 auto;
  flex-wrap: wrap;
  gap: 10px;
}

.footer-logo {
  font-size: 30px;
  font-family: 'Georgia', serif;
  font-weight: bold;
  font-style: normal;
  color: #fff;
}

.footer-copy {
  font-size: 13px;
  color: #aaa;
}

@media (max-width: 768px){
  .footer-copy{
  padding-left: 35%;
  }
}








/* Back to top button */
#backToTopBtn {
  display: none; 
  position: fixed;
  bottom: 30px;
  right: 30px;
  z-index: 99;
  background-color: #f9a825;
  color: black;
  border: none;
  padding: 12px 16px;
  font-size: 20px;
  border-radius: 50%;
  cursor: pointer;
  box-shadow: 0 4px 6px rgba(0,0,0,0.3);
  transition: opacity 0.3s ease, transform 0.3s ease;
}

#backToTopBtn:hover {
  background-color: #ffcc00;
  transform: scale(1.1);
}


@media (max-width: 768px){
  .footer-bottom{
    border-top: 1px solid white;
  }
  #backToTopBtn{
    position: sticky;
  }
}






/* Blog Section */
.blog-section {
  padding: 4rem 2rem;
  background: linear-gradient(to right, #cac1b8, #fff1e0);
  text-align: center;
}

.section-title {
  font-size: 2.5rem;
  margin-bottom: 0.5rem;
  font-weight: bold;
}

.section-subtitle {
  color: #555;
  margin-bottom: 2rem;
  font-size: 1rem;
}

.blog-container {
  display: flex;
  gap: 2rem;
  justify-content: center;
  flex-wrap: wrap;
}

.blog-card {
  background: white;
  border-radius: 15px;
  width: 300px;
  overflow: hidden;
  cursor: pointer;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
  transition: transform 0.3s ease;
}

.blog-card:hover {
  transform: translateY(-8px);
}

.blog-image {
  position: relative;
}

.blog-image img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

.blog-date {
  position: absolute;
  top: 10px;
  left: 10px;
  background: orange;
  color: white;
  padding: 5px 10px;
  font-size: 0.8rem;
  border-radius: 20px;
}

.blog-content {
  padding: 1rem;
  text-align: left;
}

.blog-content h3 {
  margin-bottom: 0.5rem;
}

.blog-content p {
  color: #666;
  font-size: 0.9rem;
}

/* Modal */
.modal {
  display: none;
  position: fixed;
  z-index: 1000;
  padding: 100px 20px;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  overflow-y: auto;
  background-color: rgba(0,0,0,0.6);
}

.modal-content {
  background: white;
  margin: auto;
  padding: 2rem;
  border-radius: 10px;
  max-width: 600px;
  position: relative;
  text-align: left;
}

.modal-content img {
  width: 100%;
  margin-top: 1rem;
  border-radius: 10px;
}

.close {
  position: absolute;
  top: 15px;
  right: 20px;
  font-size: 1.5rem;
  color: #333;
  cursor: pointer;
}





/* About Section */
.about-chef {
  background: linear-gradient(to right, #bababa, #fef3e7);
  padding: 6rem 2rem;
  font-family: 'Segoe UI', sans-serif;
}

.chef-container {
  display: flex;
  max-width: 1200px;
  margin: auto;
  align-items: center;
  flex-wrap: wrap;
  gap: 3rem;
}

.chef-image img {
  width: 100%;
  max-width: 450px;
  border-radius: 25px;
  box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
}

.chef-info {
  flex: 1;
  min-width: 300px;
}

.chef-info h2 {
  font-size: 2.7rem;
  font-weight: bold;
  margin-bottom: 1rem;
  color: #2c2c2c;
}

.chef-name {
  font-family: 'Great Vibes', cursive;
  font-size: 3rem;
  color: #e76f51;
}

.chef-info p {
  font-size: 1.1rem;
  color: #555;
  line-height: 1.7;
  margin-bottom: 2rem;
}

.chef-highlights {
  display: flex;
  gap: 1.5rem;
  flex-wrap: wrap;
  margin-bottom: 2rem;
}

.highlight-card {
  background: white;
  padding: 1.2rem 1.5rem;
  border-radius: 15px;
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08);
  text-align: center;
  flex: 1;
  min-width: 180px;
  transition: transform 0.3s ease;
}

.highlight-card:hover {
  transform: translateY(-8px);
}

.highlight-card i {
  font-size: 2rem;
  color: #e76f51;
  margin-bottom: 0.5rem;
}

.highlight-card h4 {
  font-size: 1rem;
  color: #333;
  margin: 0;
}

.chef-signature {
  text-align: left;
}

.chef-signature p {
  font-style: italic;
  color: #777;
  font-size: 1rem;
  margin-bottom: 0.5rem;
}

.chef-signature img {
  height: 40px;
}

@media (max-width: 768px){
  .chef-image img{
   height:40vh;
   max-width: 290px;
  }
  .chef-info h2{
   text-align: left;
  }
}



