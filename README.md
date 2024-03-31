The potifolio is about my personal experiences and skills acquired during my  time as a technologist professional.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home Page</title>
    <style>
             
       body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-image: url("C:\Users\Admin\Pictures\sumsung a24\IMG_20230603_055402.jpg");
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .container {
            text-align: center;
            color: white;
        }

        h1 {
            font-size: 3rem;
            margin-bottom: 20px;
        }

        p {
            font-size: 1.5rem;
        }

        a {
            color: #fff;
            text-decoration: none;
            background-color: #007bff;
            padding: 10px 20px;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        a:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Welcome to Our Website</h1>
        <p>This is the home page of our website. Feel free to explore!</p>
        <a href="about.html">Learn More</a>
    </div>
    <section id="skills">
        <h2>Skills</h2>
        <ul>
          <li>HTML</li>
          <li>CSS</li>
          <li>JavaScript</li>
          <li>Python</li>
          <!-- Add more skills as needed -->
        </ul>
      </section>
      
      <section id="projects">
        <h2>Projects</h2>
        <div class="project">
           
            
               
          <h3>Project 1</h3>
          <p>The first project i did was about a login websit which was successful </p>
          <a href="#">View Project</a>
        </div>
        <div class="project">
          <h3>Project 2</h3>
          <p>Description of Project 2</p>
          <a href="#">View Project</a>
        </div>
        <!-- Add more projects as needed -->
      </section>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
    }
    
    .container {
      max-width: 600px;
      margin: 20px auto;
      padding: 20px;
      background-color: #fff;
      box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
      border-radius: 5px;
    }
    
    h1 {
      color: #333;
      text-align: center;
    }
    
    form {
      margin-top: 20px;
    }
    
    label {
      display: block;
      margin-bottom: 5px;
      color: #333;
    }
    
    input[type="text"],
    input[type="email"],
    textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #ccc;
      border-radius: 3px;
      box-sizing: border-box;
    }
    
    textarea {
      height: 150px;
    }
    
    button {
      background-color: #007bff;
      color: #fff;
      border: none;
      padding: 10px 20px;
      cursor: pointer;
      border-radius: 3px;
    }
    
    button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Contact Us</h1>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
      
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      
      <label for="message">Message:</label>
      <textarea id="message" name="message" required></textarea>
      
      <button type="submit">Send Message</button>
    </form>
  </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About Us</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: gold;
    }
    
    .container {
      max-width: 800px;
      margin: 150px auto;
      padding: 80px;
      background-color: #ffffff;
      box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
      border-radius: 10px;
    }
    
    h1, h2, h3 {
      color: #333333;
    }
    
    h1 {
      text-align: center;
    }
    
    p {
      color: #666;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>About Us</h1>
    <p>Our mission is HONESTY,ACHIEVING GOALS AND LOYALTY .</p>
    <p>I started to develop the website in 2015 and i have seen huge growth and support from my supporters.</p>
  </div>
</body>
</html>

