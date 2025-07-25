<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Zeroin Academy - Cake Baking Classes</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #fffaf5;
    }
    .navbar {
      background-color: #fff0e6;
    }
    .navbar-brand img {
      height: 50px;
    }
    .hero {
      background: linear-gradient(rgba(255, 235, 220, 0.6), rgba(255, 235, 220, 0.8)), url('https://images.unsplash.com/photo-1589308078054-832232d7eac5') center/cover no-repeat;
      height: 90vh;
      color: #4e342e;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }
    .hero h1 {
      font-size: 4rem;
      font-weight: bold;
    }
    .hero p {
      font-size: 1.5rem;
    }
    .section-title {
      font-weight: bold;
      text-align: center;
      margin-bottom: 2rem;
      color: #8e44ad;
    }
    .card {
      background-color: #fff0f5;
      border: none;
      border-radius: 12px;
    }
    .card-title {
      color: #6a1b9a;
      font-weight: 600;
    }
    .card-text {
      color: #5d4037;
    }
    .filter-gallery img {
      width: 100%;
      border-radius: 10px;
      transition: transform 0.3s ease;
    }
    .filter-gallery img:hover {
      transform: scale(1.05);
    }
    .social-icons a {
      color: #e91e63;
      margin: 0 10px;
      font-size: 1.8rem;
    }
    footer {
      background-color: #fff0e6;
      text-align: center;
      padding: 1.5rem 0;
      color: #6d4c41;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-light">
    <div class="container">
      <a class="navbar-brand" href="#">
        <img src="https://via.placeholder.com/150x50?text=Zeroin+Logo" alt="Zeroin Logo">
      </a>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero">
    <div class="container">
      <h1>Welcome to Zeroin Academy</h1>
      <p>Master the art of baking with our expert-led cake and pastry classes</p>
      <a href="#courses" class="btn btn-lg btn-warning mt-4">Explore Courses</a>
    </div>
  </section>

  <!-- About Section -->
  <section class="py-5" id="about">
    <div class="container">
      <h2 class="section-title">About Us</h2>
      <div class="row align-items-center">
        <div class="col-md-6">
          <p>Zeroin Academy is a premier destination for cake and pastry enthusiasts. With over <strong>10 years of experience</strong>, we have trained more than <strong>10,000 professional bakers</strong> who have gone on to build successful baking businesses. Whether you're beginning your baking journey or refining your craft, Zeroin is your gateway to excellence.</p>
        </div>
        <div class="col-md-6">
          <img src="https://images.unsplash.com/photo-1549576490-b0b4831ef60a" alt="Baking" class="img-fluid rounded">
        </div>
      </div>
    </div>
  </section>

  <!-- Courses Section -->
  <section class="py-5 bg-light" id="courses">
    <div class="container">
      <h2 class="section-title">Our Courses</h2>
      <div class="row">
        <div class="col-md-6 mb-4">
          <div class="card h-100 shadow-sm p-3">
            <div class="card-body">
              <h5 class="card-title">Diploma In Professional Bakery And Patisserie</h5>
              <p class="card-text">A complete professional course covering all facets of baking and patisserie. Ideal for serious bakers looking to pursue bakery as a career.</p>
            </div>
          </div>
        </div>
        <div class="col-md-6 mb-4">
          <div class="card h-100 shadow-sm p-3">
            <div class="card-body">
              <h5 class="card-title">8 Weeks Master Baker Course</h5>
              <p class="card-text">Our signature program to take your baking skills to the next level with 8 weeks of intensive, hands-on training in bakery techniques and recipes.</p>
            </div>
          </div>
        </div>
        <div class="col-md-6 mb-4">
          <div class="card h-100 shadow-sm p-3">
            <div class="card-body">
              <h5 class="card-title">4 Weeks Professional Bakery and Confectionery Course</h5>
              <p class="card-text">Perfect for pastry lovers, this course teaches both sweet and savory essentials in a focused and interactive environment.</p>
            </div>
          </div>
        </div>
        <div class="col-md-6 mb-4">
          <div class="card h-100 shadow-sm p-3">
            <div class="card-body">
              <h5 class="card-title">6 Days Extensive Baking Course</h5>
              <p class="card-text">Short on time? This intensive 6-day course introduces you to the basics of cake baking, decoration, and bakery best practices.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

</body>
</html>
