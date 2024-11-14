<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>4K Wallpaper Gallery</title>
  <style>
    /* Basic Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      line-height: 1.6;
      color: #333;
    }

    header {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 20px;
    }

    nav {
      background-color: #24495e;
      display: flex;
      justify-content: center;
    }

    nav a {
      color: white;
      padding: 15px;
      text-decoration: none;
      text-align: center;
      font-size: 19px;
    }

    nav a:hover {
      background-color: #1abc9c;
    }

    .main-content {
      padding: 20px;
    }

    .section-title {
      font-size: 30px;
      margin-bottom: 15px;
      color: #2c3e50;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .wallpaper-item {
      position: relative;
      overflow: hidden;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      background-color: #fff;
    }

    .wallpaper-item img {
      width: 100%;
      height: auto;
      transition: transform 0.3s ease;
    }

    .wallpaper-item:hover img {
      transform: scale(1.1);
    }

    .wallpaper-item h3 {
      position: absolute;
      top: 10px;
      left: 10px;
      background-color: rgba(0, 0, 0, 0.5);
      color: white;
      padding: 10px;
      border-radius: 5px;
    }

    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ddd;
      border-radius: 5px;
    }

    .contact-form button {
      background-color: #1abc9c;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    .contact-form button:hover {
      background-color: #16a085;
    }

    footer {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 10px;
    }

    /* Responsive Styles */
    @media (max-width: 768px) {
      nav {
        flex-direction: column;
      }
      nav a {
        padding: 12px;
      }
    }
  </style>
</head>
<body>

  <!-- Header Section -->
  <header>
    <h1>4K Wallpaper Gallery</h1>
    <p>Your source for high-quality 4K Wallpapers</p>
  </header>

  <!-- Navigation Menu -->
  <nav>
    <a href="#home">Home</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- Main Content Section -->
  <div class="main-content">
    
    <!-- Gallery Section -->
    <section class="section" id="gallery">
      <h2 class="section-title">4K Wallpaper Gallery</h2>
      
      <div class="gallery">
        <!-- Wallpaper 1 -->
        <div class="wallpaper-item">
          <img src="https://via.placeholder.com/1200x800/000000/FFFFFF/?text=4K+Wallpaper+1" alt="Wallpaper 1">
          <h3>Nature in 4K</h3>
        </div>
        
        <!-- Wallpaper 2 -->
        <div class="wallpaper-item">
          <img src="https://via.placeholder.com/1200x800/000000/FFFFFF/?text=4K+Wallpaper+2" alt="Wallpaper 2">
          <h3>Cityscape in 4K</h3>
        </div>
        
        <!-- Wallpaper 3 -->
        <div class="wallpaper-item">
          <img src="https://via.placeholder.com/1200x800/000000/FFFFFF/?text=4K+Wallpaper+3" alt="Wallpaper 3">
          <h3>Space in 4K</h3>
        </div>

        <!-- Wallpaper 4 -->
        <div class="wallpaper-item">
          <img src="https://via.placeholder.com/1200x800/000000/FFFFFF/?text=4K+Wallpaper+4" alt="Wallpaper 4">
          <h3>Forest in 4K</h3>
        </div>

        <!-- Add more wallpapers as needed -->
      </div>
    </section>
    </div>
 <!-- Footer Section -->
  <footer>
    <p>&copy; 

  <!-- JavaScript for Form Validation -->
  <script>
    function validateForm() {
      var name = document.getElementById("name").value;
      var email = document.getElementById("email").value;
      var message = document.getElementById("message").value;

      if (name == "" || email == "" || message == "") {
        alert("Please fill out all fields.");
        return false;
      }

      alert("Message sent! We will get back to you soon.");
      return true;
    }
  </script>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  </title>
  <style>
    /* Basic Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      line-height: 1.6;
      color: #333;
    }

    header {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 20px;
    }

    nav {
      background-color: #34495e;
      display: flex;
      justify-content: center;
    }

    nav a {
      color: white;
      padding: 15px;
      text-decoration: none;
      text-align: center;
      font-size: 18px;
    }

    nav a:hover {
      background-color: #1abc9c;
    }

    .main-content {
      padding: 20px;
    }

    .section-title {
      font-size: 30px;
      margin-bottom: 15px;
      color: #2c3e50;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .wallpaper-item {
      position: relative;
      overflow: hidden;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      background-color: #fff;
    }

    .wallpaper-item img {
      width: 100%;
      height: auto;
      transition: transform 0.3s ease;
    }

    .wallpaper-item:hover img {
      transform: scale(1.1);
    }

    .wallpaper-item h3 {
      position: absolute;
      top: 10px;
      left: 10px;
      background-color: rgba(0, 0, 0, 0.5);
      color: white;
      padding: 10px;
      border-radius: 5px;
    }

    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ddd;
      border-radius: 5px;
    }

    .contact-form button {
      background-color: #1abc9c;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    .contact-form button:hover {
      background-color: #16a085;
    }

    footer {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 10px;
    }

    /* Responsive Styles */
    @media
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>4K Wallpaper Gallery - 100 Photos</title>
  <style>
    /* Basic Reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      line-height: 1.6;
      color: #333;
    }

    header {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 20px;
    }

    nav {
      background-color: #34495e;
      display: flex;
      justify-content: center;
    }

    nav a {
      color: white;
      padding: 15px;
      text-decoration: none;
      text-align: center;
      font-size: 18px;
    }

    nav a:hover {
      background-color: #1abc9c;
    }

    .main-content {
      padding: 20px;
    }

    .section-title {
      font-size: 30px;
      margin-bottom: 15px;
      color: #2c3e50;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .wallpaper-item {
      position: relative;
      overflow: hidden;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      background-color: #fff;
    }

    .wallpaper-item img {
      width: 100%;
      height: auto;
      transition: transform 0.3s ease;
    }

    .wallpaper-item:hover img {
      transform: scale(1.1);
    }

    .wallpaper-item h3 {
      position: absolute;
      top: 10px;
      left: 10px;
      background-color: rgba(0, 0, 0, 0.5);
      color: white;
      padding: 10px;
      border-radius: 5px;
    }

    footer {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 10px;
    }

    /* Responsive Styles */
    @media (max-width: 768px) {
      nav {
        flex-direction: column;
      }
      nav a {
        padding: 12px;
      }
    }
  </style>
</head>
<body>
  <!-- Main Content Section -->
  <div class="main-content">
    
    <!-- Gallery Section -->
    <section class="section" id="gallery">
      <h2 class="section-title">4K Wallpaper Gallery</h2>
      
      <div class="gallery">
        <!-- Wallpaper 1 -->
        <div class="wallpaper-item">
          <img src="https://via.placeholder.com/1200x800/000000/FFFFFF/?text=4K+Wallpaper+1" alt="Wallpaper 1">
          <h3>Nature in 4K</h3>
        </div>

        <!-- Wallpaper 2 -->
        <div class="wallpaper-item">
          <img src="https://via.placeholder.com/1200x800/000000/FFFFFF/?text=4K+Wallpaper+2" alt="Wallpaper 2">
          <h3>Cityscape in 4K</h3>
        </div>

        <!-- Wallpaper 3 -->
        <div class="wallpaper-item">
          <img src="https://via.placeholder.com/1200x800/000000/FFFFFF/?text=4K+Wallpaper+3" alt="Wallpaper 3">
          <h3>Space in 4K</h3>
        </div>

        <!-- Wallpaper 4 -->
        <div class="wallpaper-item">
          <img src="https://via.placeholder.com/1200x800/000000/FFFFFF/?text=4K+Wallpaper+4" alt="Wallpaper 4">
          <h3>Forest in 4K</h3>
        </div>

        <!-- Add more wallpapers by continuing with the pattern above -->
        <div class="wallpaper-item">
          <img src="https://via.placeholder.com/1200x800/000000/FFFFFF/?text=4K+Wallpaper+5" alt="Wallpaper 5">
          <h3>Waterfalls in 4K</h3>
        </div>

        <!-- Example with 16a085 wallpapers. Repeat similar blocks up to 100. -->
        <div class="wallpaper-item">
          <img src="https://via.placeholder.com/1200x800/000000/FFFFFF/?text=4K+Wallpaper+100" alt="Wallpaper 100">
          <h3>Mountains in 4K</h3>
        </div>

        <!-- Repeat this structure for all 100 images -->
      </div>
    </section>
  </div>

  <!-- Footer Section -->
  <footer>
    <p>&copy; 2024 4K Wallpaper with harsh Contact hidubey20@gmail.com.</p>
  </footer>

</body>
</html>
<!-- Contact Section -->
    <section class="section" id="contact">
      <h2 class="section-title">Contact Us</h2>
      <p>If you have any questions or want to request specific wallpapers, feel free to contact us.</p>

      <form id="contactForm" class="contact-form" action="#" onsubmit="return validateForm()">
        <input type="text" id="name" name="name" placeholder="Your Name" required>
        <input type="email" id="email" name="email" placeholder="Your Email" required>
        <textarea id="message" name="message" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </section>
    <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>4K Wallpaper Gallery - Upload Photos</title>
  <style>
    /* Same styling as before */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      line-height: 1.6;
      color: #333;
    }

    header {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 20px;
    }

    .main-content {
      padding: 20px;
    }

    .section-title {
      font-size: 30px;
      margin-bottom: 15px;
      color: #2c3e50;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }

    .wallpaper-item {
      position: relative;
      overflow: hidden;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      background-color: #fff;
    }

    .wallpaper-item img {
      width: 100%;
      height: auto;
      transition: transform 0.3s ease;
    }

    .wallpaper-item:hover img {
      transform: scale(1.1);
    }

    footer {
      background-color: #2c3e50;
      color: white;
      text-align: center;
      padding: 10px;
    }

    /* Responsive Styles */
    @media (max-width: 768px) {
      nav {
        flex-direction: column;
      }
      nav a {
        padding: 12px;
      }
    }
  </style>
</head>
<body>

  <!-- Header Section -->
  <header>
    <h1>4K Wallpaper Gallery</h1>
    <p>Your source for high-quality 4K Wallpapers</p>
  </header>

  <!-- Main Content Section -->
  <div class="main-content">
    
    <!-- Upload Section -->
    <section id="upload">
      <h2 class="section-title">Upload Your Wallpaper</h2>
      <!-- File upload form -->
      <form action="upload.php" method="POST" enctype="multipart/form-data">
        <label for="fileUpload">Choose an image to upload:</label>
        <input type="file" name="wallpaper" id="fileUpload" required>
        <button type="submit" name="submit">Upload</button>
      </form>
    </section>

    <!-- Gallery Section -->
    <section class="section" id="gallery">
      <h2 class="section-title">4K Wallpaper Gallery</h2>
      
      <div class="gallery">
        <!-- Dynamic gallery items will be displayed here -->
        <!-- Example of a single image -->
        <div class="wallpaper-item">
          <img src="uploads/sample1.jpg" alt="Wallpaper 1">
          <h3>Sample Wallpaper</h3>
        </div>
      </div>
    </section>

  </div>

  <!-- Footer Section -->
  <footer>
    <p>&copy; 2024 4K Wallpaper Gallery. All Rights Reserved.</p>
  </footer>

</body>
</html>
<?php
// Check if the form was submitted
if(isset($_POST['submit'])) {
    // Set the target directory
    $target_dir = "uploads/";
    
    

