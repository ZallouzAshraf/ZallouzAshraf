<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ashraf Zallouz - CV</title>
  <style>
    /* General Styles */
    body {
      font-family: 'Arial', sans-serif;
      background: linear-gradient(135deg, #f5f7fa, #c3cfe2);
      color: #333;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }

    .container {
      max-width: 800px;
      margin: 50px auto;
      padding: 20px;
      background: white;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      animation: fadeIn 1.5s ease-in-out;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    h1, h2, h3 {
      color: #2c3e50;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
      animation: slideInLeft 1s ease-in-out;
    }

    h2 {
      font-size: 1.8rem;
      margin-top: 20px;
      animation: slideInRight 1s ease-in-out;
    }

    p, li {
      font-size: 1rem;
      animation: fadeIn 2s ease-in-out;
    }

    a {
      color: #3498db;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    /* Header Section */
    .header {
      text-align: center;
      padding: 20px 0;
      background: linear-gradient(135deg, #3498db, #2c3e50);
      color: white;
      border-radius: 10px;
      margin-bottom: 20px;
      animation: slideInTop 1s ease-in-out;
    }

    @keyframes slideInTop {
      from { opacity: 0; transform: translateY(-50px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    .header p {
      margin: 5px 0;
      font-size: 1.2rem;
    }

    /* Sections */
    .section {
      margin-bottom: 30px;
      padding: 20px;
      background: #f9f9f9;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      animation: fadeInUp 1s ease-in-out;
    }

    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .section h2 {
      border-bottom: 2px solid #3498db;
      padding-bottom: 10px;
      margin-bottom: 15px;
    }

    .section ul {
      list-style-type: none;
      padding: 0;
    }

    .section ul li {
      margin-bottom: 10px;
    }

    /* Skills Section */
    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
    }

    .skill {
      background: #3498db;
      color: white;
      padding: 5px 10px;
      border-radius: 5px;
      font-size: 0.9rem;
      animation: fadeIn 1s ease-in-out;
    }

    /* Footer */
    .footer {
      text-align: center;
      padding: 20px;
      background: #2c3e50;
      color: white;
      border-radius: 10px;
      margin-top: 20px;
      animation: slideInBottom 1s ease-in-out;
    }

    @keyframes slideInBottom {
      from { opacity: 0; transform: translateY(50px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Header -->
    <div class="header">
      <h1>Ashraf Zallouz</h1>
      <p>Software Engineering Student | Full-Stack Developer</p>
      <p>📍 Tunisia | 📧 ashrafzaliouz@gmail.com | 📞 (+216) 52504887</p>
      <p>
        <a href="https://linkedin.com/in/ashrafzaliouz" target="_blank">LinkedIn</a> | 
        <a href="https://github.com/ashrafzaliouz" target="_blank">GitHub</a>
      </p>
    </div>

    <!-- About Me -->
    <div class="section">
      <h2>About Me</h2>
      <p>
        A passionate software engineering student specializing in systems and IT architecture. I love creating innovative solutions and have a strong understanding of programming concepts and web development. Seeking a 6-month end-of-study internship to contribute to impactful projects.
      </p>
    </div>

    <!-- Work Experience -->
    <div class="section">
      <h2>Work Experience</h2>
      <ul>
        <li>
          <strong>Full Stack Internship</strong> - KerTechnologie (Jul 2024 – Sep 2024)
          <ul>
            <li>Developed a restaurant menu management platform using Next.js and Tailwind CSS.</li>
            <li>Integrated Firebase for user authentication and role-based access.</li>
          </ul>
        </li>
        <li>
          <strong>Web Developer</strong> - BS TEAM (Jul 2021 – Sep 2021)
          <ul>
            <li>Designed and maintained websites with a focus on performance optimization.</li>
          </ul>
        </li>
      </ul>
    </div>

    <!-- Projects -->
    <div class="section">
      <h2>Projects</h2>
      <ul>
        <li>
          <strong>Professional Appointment Platform</strong> - Built with MERN stack and Tailwind CSS.
        </li>
        <li>
          <strong>Car Maintenance Scheduling App</strong> - Integrated Google Maps for locating agencies.
        </li>
      </ul>
    </div>

    <!-- Skills -->
    <div class="section">
      <h2>Technical Skills</h2>
      <div class="skills">
        <div class="skill">React</div>
        <div class="skill">Node.js</div>
        <div class="skill">MongoDB</div>
        <div class="skill">Tailwind CSS</div>
        <div class="skill">JavaScript</div>
        <div class="skill">Java</div>
      </div>
    </div>

    <!-- Footer -->
    <div class="footer">
      <p>© 2023 Ashraf Zallouz | Designed with ❤️</p>
    </div>
  </div>
</body>
</html>
