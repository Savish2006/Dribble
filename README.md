# Project Responsive Web Design using Bootstrap
## Date:26.12.2024

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


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
```
dribble.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Bootstrap Web Page</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">MyWebsite</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
          <li class="nav-item"><a class="nav-link" href="#">About</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Services</a></li>
          <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <div class="bg-primary text-white text-center py-5">
    <div class="container">
      <h1>Welcome to My Website</h1>
      <p class="lead">Your one-stop solution for amazing web design</p>
      <a href="#services" class="btn btn-light btn-lg">Learn More</a>
    </div>
  </div>

  <!-- Content Section -->
  <div class="container my-5">
    <h2 class="text-center mb-4" id="services">Our Services</h2>
    <div class="row">
      <div class="col-lg-4">
          <img src="watch.jpg" class="img-thumbnail rounded" alt="Service 1">
          <div class="card-body">
            <h5 class="card-title">Service 1</h5>
            <p class="card-text">We offer the best service for your needs.</p>
            <a href="#" class="btn btn-primary">Learn More</a>
          
        </div>
      </div>
      <div class="col-lg-4">
          <img src="iphone 16.jpg" class="img-thumbnail rounded " alt="Service 2">
          <div class="card-body">
            <h5 class="card-title">Service 2</h5>
            <p class="card-text">Exceptional quality at your fingertips.</p>
            <a href="#" class="btn btn-primary">Learn More</a>
          
        </div>
      </div>
      <div class="col-lg-4">
          <img src="all product.jpg" class="img-thumbnail rounded " alt="Service 3">
          <div class="card-body">
            <h5 class="card-title">Service 3</h5>
            <p class="card-text">Reliable and affordable solutions.</p>
            <a href="#" class="btn btn-primary">Learn More</a>
          
        </div>
      </div>
    </div>

    <div class="row">
        <div class="col-lg-4">
            <img src="buds 2.jpg" class="img-thumbnail rounded" alt="Service 1">
            <div class="card-body">
              <h5 class="card-title">Service 1</h5>
              <p class="card-text">We offer the best service for your needs.</p>
              <a href="#" class="btn btn-primary">Learn More</a>
            
          </div>
        </div>
        <div class="col-lg-4">
            <img src="laptop 2.jpg" class="img-thumbnail rounded " alt="Service 2">
            <div class="card-body">
              <h5 class="card-title">Service 2</h5>
              <p class="card-text">Exceptional quality at your fingertips.</p> <br> <br>
              <a href="#" class="btn btn-primary">Learn More</a>
            
          </div>
        </div>
        <div class="col-lg-4">
            <img src="laptop.jpg" class="img-thumbnail rounded " alt="Service 3">
            <div class="card-body">
              <h5 class="card-title">Service 3</h5>
              <p class="card-text">Reliable and affordable solutions.</p>
              <a href="#" class="btn btn-primary">Learn More</a>
            
          </div>
        </div>
      </div>
  </div>

  <!-- Footer -->
  <footer class="bg-dark text-white text-center py-3">
    <div class="container">
      <p> Designed Savish R &copy;</p>
    </div>
  </footer>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>



```

## OUTPUT:
![alt text](<Screenshot (87).png>)
![alt text](<Screenshot (88).png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
