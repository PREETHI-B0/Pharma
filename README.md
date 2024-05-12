# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Home -Pharmaceutical Company </title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
  
</head>
<body style="background-color: rgb(121, 172, 92);">
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Pharmaceutical Company</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="web.html" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">HOME <span class="sr-only" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">ABOUT</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">PRODUCTS</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">CONTACT</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">LOGIN</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">REGISTER</a>
        </li>
      </ul>
    </div>
  </nav>
  <div class="container mt-4">
    <div class="row">
      <div class="col-md-8">
        <h1 style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Welcome to Pharmaceutical Company</h1>
        <p style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Welcome to Pharmaceutical Company, your trusted source for high-quality pharmaceutical products. We are dedicated to improving the health and well-being of our customers by providing safe and effective medications.</p>
        <p style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">At Pharmaceutical Company, we offer a wide range of prescription and over-the-counter medications to meet your healthcare needs. Whether you're managing a chronic condition or simply looking for relief from minor ailments, we have the products you need.</p>
        <p style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">In addition to medications, we also carry a variety of healthcare products and accessories, including vitamins, supplements, first aid supplies, and more. Our knowledgeable staff is here to assist you with any questions you may have and to ensure you find the right products for your needs.</p>
        <p style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Thank you for choosing Pharmaceutical Company for your healthcare needs. We look forward to serving you and helping you live a healthier life.</p>
      </div>
      <div class="col-md-4">
        <img src="image/b.jpg" class="img-fluid" alt="Pharmacy Image">
      </div>
    </div>
  </div>
  <body >
  <footer class="bg-dark text-white text-center py-4 mt-5">
    <p style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">&copy; 2024 Pharmaceutical Company. All rights reserved. BY PREETHI B(212221220040)</p>
  </footer>
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">ABOUT Pharmaceutical Company</title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Pharmaceutical Company</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="web.html" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">HOME</a>
        </li>
        <li class="nav-item dropdown active">
          <a class="nav-link dropdown-toggle" href="about.html" id="navbarDropdownAbout" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">
            ABOUT
          </a>
          <div class="dropdown-menu" aria-labelledby="navbarDropdownAbout">
            <a class="dropdown-item" href="#vision" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Vision</a>
            <a class="dropdown-item" href="#mission" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Mission</a>
            <a class="dropdown-item" href="#values" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Values</a>
          </div>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">PRODUCTS</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">CONTACT</a>
        </li>
      </ul>
    </div>
  </nav>
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1 style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">ABOUT Pharmaceutical Company</h1>
        <div id="vision">
          <h2 style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Vision</h2>
          <p style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Our vision is to be a leading provider of innovative healthcare solutions that improve the quality of life for people around the world.</p>
        </div>
        <div id="mission">
          <h2 style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Mission</h2>
          <p style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Our mission is to develop and deliver safe, effective, and affordable medications that address the healthcare needs of our customers.</p>
        </div>
        <div id="values">
          <h2 style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Values</h2>
          <ul style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">
            <li>-> Quality: We are committed to maintaining the highest standards of quality in everything we do.</li>
            <li>-> Integrity: We conduct our business with honesty, transparency, and ethical behavior.</li>
            <li>-> Innovation: We strive to continuously innovate and improve our products and services to better serve our customers.</li>
            <li>-> Customer Focus: We are dedicated to understanding and meeting the needs of our customers.</li>
            <li>-> Teamwork: We work together as a team to achieve our goals and deliver exceptional results.</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
  <body background="image/a.jpg" style="background-repeat: no-repeat; background-size: cover;">
  <footer class="bg-dark text-white text-center py-2 mt-2">

  <body background="a.png" style="background-repeat: no-repeat; background-size: cover;">
    <p style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">&copy; 2024 Pharmaceutical Company. All rights reserved.  BY PREETHI B (212221220040)</p>
  </footer>
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html >
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Products - Pharmaceutical Company</title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Pharmaceutical Company</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="web.html" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">HOME</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">ABOUT</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="product.html" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">PRODUCTS <span class="sr-only" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="contact.html" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">CONTACT</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="#" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">LOGIN</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">REGISTER</a>
        </li>
      </ul>
    </div>
  </nav>
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-12">
        <h1 style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">OUR PRODUCTS</h1>
        <div class="card-deck">
          <div class="card">
            <img src="image/Products1.jpg" class="card-img-top" alt="Product 1" width="100" height="150">
            <div class="card-body">
              <h5 class="card-title" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">PRODUCT 1</h5>
              <p class="card-text" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Missionpharma - Generic pharmaceuticals and medical consumables.</p>
              <a href="#" class="btn btn-primary" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="image/images1.jpg" class="card-img-top" alt="Product 2" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">PRODUCT 2</h5>
              <p class="card-text" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Thiamine Tablets Benztrophine Mesylate Tablets Pyridoxine Tablets.</p>
              <a href="#" class="btn btn-primary" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Buy Now</a>
            </div>
          </div>
          <div class="card">
            <img src="image/pro.webp" class="card-img-top" alt="Product 3" width="200" height="200">
            <div class="card-body">
              <h5 class="card-title" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">PRODUCT 3</h5>
              <p class="card-text" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Enteric coated rabeprazole sodium levosulpiride sr capsules.</p>
              <a href="#" class="btn btn-primary" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Buy Now</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <footer class="bg-dark text-white text-center py-2 mt-2">
    <p style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">&copy; 2024 Pharmaceutical Company. All rights reserved.  BY PREETHI B (212221220040)</p>
  </footer>
  <body background="a.png" style="background-repeat: no-repeat; background-size: cover;">
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Contact Us - Pharmaceutical Company </title>
  <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
    <a class="navbar-brand" href="#" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Pharmaceutical Company</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="web.html" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">HOME</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="about.html" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">ABOUT</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="product.html" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">PRODUCTS</a>
        </li>
        <li class="nav-item active">
          <a class="nav-link" href="contact.html" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">CONTACT <span class="sr-only" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">(current)</span></a>
        </li>
      </ul>
    </div>
  </nav>
  <div class="container mt-5">
    <div class="row">
      <div class="col-md-8">
        <h1 style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">CONTACT US</h1>
        <p style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">For any inquiries or feedback, please fill out the form below and we will get back to you as soon as possible.</p>
        <form>
          <div class="form-group">
            <label for="name" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">YOUR NAME</label>
            <input type="text" class="form-control" id="name" placeholder="Enter your name">
          </div>
          <div class="form-group">
            <label for="email" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">YOUR EMAIL</label>
            <input type="email" class="form-control" id="email" placeholder="Enter your email">
          </div>
          <div class="form-group">
            <label for="message" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">MESSAGE</label>
            <textarea class="form-control" id="message" rows="5" placeholder="Enter your message"></textarea>
          </div>
          <button type="submit" class="btn btn-primary" style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">SUBMIT</button>
        </form>
      </div>
      <div class="col-md-4">
        <h2 style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Pharmaceutical Company </h2>
        <address>
          <strong style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Address:</strong><br>
          Saveetha Nagar,Thandalam,Kancheepuram.<br><br>
          <strong style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Email:</strong><br>
          info@Pharmaceutical Company .com<br><br>
          <strong style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">Phone:</strong><br>
          +9894359852
        </address>
      </div>
    </div>
  </div>
  <body background="image/a.jpg" style="background-repeat: no-repeat; background-size: cover;">
  <footer class="bg-dark text-white text-center py-2 mt-2">
    <p style="font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;">&copy; 2024 Pharmaceutical Company. All rights reserved.  BY PREETHI B (212221220040)</p>
  </footer>
  <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html>

## OUTPUT:
![alt text](<Screenshot 2024-05-12 131447.png>)
![alt text](<Screenshot 2024-05-12 131512.png>)
![alt text](<Screenshot 2024-05-12 131530.png>)
![alt text](<Screenshot 2024-05-12 131649.png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
