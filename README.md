<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>LearnHub - Online Learning</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      background: #f5f7fb;
      color: #1f2937;
    }

    header {
      background: white;
      padding: 18px 6%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      box-shadow: 0 2px 10px rgba(0,0,0,0.08);
    }

    .logo {
      font-size: 24px;
      font-weight: bold;
      color: #2563eb;
    }

    nav a {
      text-decoration: none;
      color: #374151;
      margin-left: 15px;
    }

    .hero {
      padding: 70px 6%;
      text-align: center;
      background: #eaf1ff;
    }

    .hero h1 {
      font-size: 42px;
      margin-bottom: 15px;
    }

    .hero p {
      font-size: 18px;
      margin-bottom: 25px;
      color: #4b5563;
    }

    .btn {
      display: inline-block;
      background: #2563eb;
      color: white;
      padding: 13px 24px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }

    .courses {
      padding: 50px 6%;
    }

    .courses h2 {
      text-align: center;
      margin-bottom: 30px;
    }

    .course-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }

    .course {
      background: white;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.08);
    }

    .course h3 {
      margin-bottom: 10px;
    }

    .course p {
      color: #6b7280;
      margin-bottom: 15px;
    }

    footer {
      text-align: center;
      padding: 25px;
      background: #111827;
      color: white;
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">LearnHub</div>

    <nav>
      <a href="#">Home</a>
      <a href="#courses">Courses</a>
      <a href="#">Login</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Learn Smarter. Learn Better.</h1>

    <p>
      Learn from great teachers and improve your skills online.
    </p>

    <a href="#courses" class="btn">
      Explore Courses
    </a>
  </section>

  <section class="courses" id="courses">

    <h2>Popular Courses</h2>

    <div class="course-grid">

      <div class="course">
        <h3>Mathematics</h3>
        <p>Learn mathematics step by step.</p>
        <a href="#" class="btn">View Course</a>
      </div>

      <div class="course">
        <h3>Physics</h3>
        <p>Understand physics with easy lessons.</p>
        <a href="#" class="btn">View Course</a>
      </div>

      <div class="course">
        <h3>English</h3>
        <p>Improve your English skills.</p>
        <a href="#" class="btn">View Course</a>
      </div>

    </div>

  </section>

  <footer>
    © 2026 LearnHub. All rights reserved.
  </footer>

</body>
</html>
