Daisy's_portfolio_project
[mycv1.pdf](https://github.com/user-attachments/files/21559039/mycv1.pdf)
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <titles>Daisy's</titles> Portfolio</title>
  <style>
    :root {
      --primary: #0D1B2A; /* Dark blue header */
      --secondary: #F4F4F9; /* Soft background */
      --accent: #1B98E0; /* Bright accent color */
      --card-bg: #ffffff; /* White card background */
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background-color: var(--secondary);
      color: var(--primary);
      padding: 20px;
    }

    .container {
      max-width: 960px;
      margin: auto;
      padding: 20px;
      background-color: var(--card-bg);
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      border-radius: 10px;
    }

    header {
      text-align: center;
      background-color: var(--primary);
      color: white;
      padding: 40px 20px;
      border-radius: 10px 10px 0 0;
    }

    .profile-pic {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 4px solid white;
      object-fit: cover;
      margin-bottom: 15px;
    }

    h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }

    .intro {
      font-style: italic;
      color: #ddd;
      margin-bottom: 15px;
    }

    .card {
      background: var(--card-bg);
      padding: 20px;
      border-radius: 8px;
      margin-bottom: 20px;
      transition: all 0.3s ease;
    }

    .card:hover {
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.12);
      transform: translateY(-4px);
    }

    h2 {
      margin-bottom: 10px;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    ul {
      list-style-type: disc;
      margin-left: 20px;
    }

    a {
      color: var(--accent);
      text-decoration: none;
    }

    blockquote {
      font-style: italic;
      color: #444;
      margin-top: 10px;
    }

    .download-btn {
      display: inline-block;
      padding: 8px 15px;
      background-color: var(--accent);
      color: white;
      border-radius: 5px;
      text-decoration: none;
      margin-left: auto;
    }

    form input,
    form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border-radius: 5px;
      border: 1px solid #ccc;
    }

    form button {
      background-color: var(--accent);
      color: white;
      padding: 10px 15px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    @media (max-width: 768px) {
      .container {
        padding: 10px;
      }
      .card {
        padding: 15px;
      }
      h1 {
        font-size: 2em;
      }
    }
  </style>
</head>
<body>
  <div class="container">
   <!-- headings--> 
    <header>
      <h1>Learning,Building,Innovating.</h1>
      <p class="intro">Aspiring tech innovator with a passion to create impactful solutions not only to solve real world problems but also shape a smarter and inclusive future.</p>
    </header>

    <div class="card">
      <h2>📧 Personal Information</h2>
      <p><strong>Email:</strong> daisycee8677@gmail.com</p>
      <p><strong>Phone:</strong> +254 727736801</p>
      <p><strong>Location:</strong> Nairobi, Kenya</p>
    </div>

    <div class="card">
      <h2>🙋 About Me</h2>
      <p>I am a motivated and passionate professional transitioning into tech industry with a strong interest and passion for technology, innovation, continous learning and creative problem solving. I am eager to build solutions that make a real world impact.</p>
    </div>

    <div class="card">
      <h2>🎓 Education <a href="Daisy_cv.pdf" class="download-btn" download>Download My CV</a></h2>
      <ul>
        <li>Bachelor of Education Science – Kenyatta University</li>
        <li>Certificate in cloud engineering – AWS </li>
        <li>Certificate in Software engineering,Web development among others – Power Learn Project </li>
      </ul>
    </div>

    <div class="card">
      <h2>🛠️ Skills</h2>
      <!-- unordered lists-->
      <ul>
        <li>HTML, CSS </li>
        <li>Python</li>
        <li>Linux</li>
        <li>Cybersecurity Fundamentals</li>
      </ul>
    </div>

    <div class="card">
      <h2>💻 Projects</h2>
      <ul>
        <li><strong><a href="#">My Portfolio Website</a></strong> – Clean and mobile-responsive portfolio site built using HTML & CSS.</li>
        <li><strong><a href="#">Python_cloud9</a></strong> – Entries involving python,from Hello world  to calculating netcharge of insulin and also working with conditionals and loops.</li>
      </ul>
    </div>

    <div class="card">
      <h2>🎯 Interests</h2>
      <ul>
        <li>Data analysis</li>
        <li>Programming</li>
        <li>Artificial Intelligence</li>
        <li>Mentorship & Community Involvement</li>
      </ul>
    </div>

    <div class="card">
      <h2>💬 Quote</h2>
      <blockquote>“The best way to predict the future is to create it.” – Peter Drucker</blockquote>
    </div>

    <div class="card">
      <h2>📨 Contact Me</h2>
      <form action="#" method="post">
        <input type="text" name="name" placeholder= "Name"required>
        <input type="email" name="email" placeholder="Email" required>
        <textarea name="message" rows="5" placeholder="Message" required></textarea>
        <button type="submit ">Send Message</button>
      </form>
    </div>
  </div>
</body>
</html>
