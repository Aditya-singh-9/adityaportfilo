<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <title>Aditya's Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        h1 {
            margin: 0;
            font-size: 30px;
        }

        nav {
            background-color: #666;
            color: #fff;
            padding: 10px;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline-block;
            margin-right: 10px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            padding: 5px 10px;
        }

        main {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        footer {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>
  <header>
    <img id="javast1" src="portfolio.jpg" alt="Your Name" height="50px">
    <h1 id="javast">Aditya Singh</h1>
    <p>Web Developer</p>
</header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <main>
      <section id="about">
        <h2>About Me</h2>
        <p>I am Aditya Singh, a 2nd-year B.Tech student with a passion for coding and technology. I am enthusiastic about exploring the world of web development and software engineering. My goal is to become a skilled professional in the tech industry and contribute to innovative projects.</p>
        <p>During my studies, I have gained a strong foundation in programming languages such as HTML, CSS, and JavaScript. I enjoy creating visually appealing and interactive websites. I also have experience working with Java, C++, and database management.</p>
        <p>As a student, I am constantly seeking opportunities to expand my knowledge and enhance my skills. I am proactive in participating in coding competitions, attending tech conferences, and exploring new technologies.</p>
        <p>I am excited to leverage my skills and contribute to real-world projects. I believe that technology has the power to transform the world, and I am committed to being a part of that change. If you have any opportunities or would like to connect, please feel free to reach out to me.</p>
    </section>
    

    <section id="skills">
      <h2>Skills</h2>
      <p>Here are some of the skills I have developed during my journey as a student and aspiring developer:</p>
      <ul>
          <li>
              <strong>HTML5 & CSS3:</strong> Proficient in creating well-structured HTML markup and applying CSS styling to build visually appealing and responsive web pages.
          </li>
          <li id="javascript-skill" class="hover:cousior-pointer">
              <strong>JavaScript:</strong> Experienced in using JavaScript to enhance interactivity and functionality on websites, and comfortable working with popular libraries and frameworks such as jQuery and React.
          </li>
          <li>
              <strong>Java & C++:</strong> Skilled in object-oriented programming languages, with a solid foundation in Java and C++ for building robust and efficient applications.
          </li>
          <li>
              <strong>Database Management:</strong> Familiar with SQL and database concepts, enabling me to design and interact with databases efficiently for data storage and retrieval.
          </li>
          <li>
              <strong>Problem Solving:</strong> Adept at breaking down complex problems and employing logical thinking and analytical skills to develop effective solutions.
          </li>
      </ul>
  </section>
  
  
  <section id="projects">
      <h2>Projects</h2>
      <ul>
          <li>
              <h3>Responsive Portfolio Website</h3>
              <p>A fully responsive portfolio website built using HTML, CSS, and JavaScript. The website showcases my skills, projects, and contact information.</p>
          </li>
          <li>
              <h3>E-commerce Website</h3>
              <p>An e-commerce website developed using Java and MySQL. The website allows users to browse products, add items to the cart, and complete the checkout process.</p>
          </li>
          <li>
              <h3>Student Management System</h3>
              <p>A student management system created using C++ and file handling. The system enables administrators to add, delete, and update student records.</p>
          </li>
      </ul>
  </section>
  

  <section id="contact">
    <h2>Contact Me</h2>
    <p>If you would like to discuss a project or have any questions, feel free to reach out to me:</p>
    <ul>
        <li>Email: singhark94@gmail.com</li>
        <li>Phone: +91 77158 16304</li>
        <li><a href="https://www.linkedin.com/in/adityasingh/" target="_blank">LinkedIn</a></li>
        <li><a href="https://www.facebook.com/profile.php?id=100017965650623" target="_blank">Facebook</a></li>
        <li><a href="https://github.com/adityasingh" target="_blank">GitHub</a></li>
    </ul>
</section>

    </main>

    <footer>
        &copy; 2023 Aditya's Portfolio. All rights reserved.
    </footer>
      
      <script>
      // JavaScript code here
      const javascriptSkill = document.getElementById('javast');
      javascriptSkill.addEventListener('click', function() {
          alert("Thank you for visiting my website! I'm thrilled to have you here.");
      });
      const scriptSkill = document.getElementById('javast1');
      scriptSkill.addEventListener('click', function() {
          alert("Thank you for visiting my website! I'm thrilled to have you here.");
      });
  </script>
</body>

</html>
