![saugat](https://github.com/user-attachments/assets/5c66800f-705c-4dce-b0f8-4330bdd8f485)# Digital-Resume-Website[<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Saugat Baral | Digital Resume</title>
  <link rel="stylesheet" href="style.css" />
  <script src="script.js" defer></script>
  <!-- Font Awesome CDN -->
<link
  rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"
  integrity="sha512-p0N+K71hUqgxu/VXCMj2U4vhWxZ1xtkg7AQaHa0sy5V+QqhtdQAYmK8T1dRvPgOdtXcgb7SAOMKK1RY+4UC6+g=="
  crossorigin="anonymous"
  referrerpolicy="no-referrer"
/>

</head>
<body>

  <header>
    <img src="saugat.jpg" alt="Saugat Baral" class="profile-img" />
    <h1>Saugat Baral</h1>
    <p>Bachelor of IT Student | Tech Enthusiast</p>
  </header>

  <nav>
    <ul>
      <li><a href="#about">About Me</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#education">Education & Experience</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm Saugat Baral from Pokhara, Nepal, currently studying BIT at SHEA in Australia. Passionate about technology, software development, and creating interactive digital experiences.</p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <div class="skill-container">
      <div class="skill">HTML</div>
      <div class="skill">CSS</div>
      <div class="skill">JavaScript</div>
      <div class="skill">Python</div>
      <div class="skill">Communication</div>
      <div class="skill">Teamwork</div>
    </div>
  </section>

  <section id="education">
    <h2>Education & Experience</h2>
    <div class="timeline">
      <div class="entry">
        <h3>SHEA (Skyline Higher Education Australia)</h3>
        <p>Bachelor of IT – 2023–Present</p>
      </div>
      <div class="entry">
        <h3>Skyline International College</h3>
        <p>Diploma of IT – Completed</p>
      </div>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Student Performance Dashboard</h3>
      <p>Analyzed student scores using Python and visualized data insights with Matplotlib.</p>
      <a href="https://github.com/saugatbrl4/student-dashboard" target="_blank">View on GitHub</a>
    </div>
    <div class="project">
      <h3>Personal Portfolio Website</h3>
      <p>Created a fully responsive website using HTML, CSS, and JavaScript.</p>
      <a href="https://github.com/saugatbrl4/portfolio" target="_blank">View on GitHub</a>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form onsubmit="return validateForm()">
      <input type="text" id="name" placeholder="Your Name" required />
      <input type="email" id="email" placeholder="Your Email" required />
      <textarea id="message" placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
    <p>Email: <a href="mailto:saggubrl@gmail.com">saggubrl@gmail.com</a></p>
    <p><a href="https://www.facebook.com/saugatbrl4" target="_blank">Facebook</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Saugat Baral | Digital Resume</p>
  </footer>

</body>
</html>
<p>
  <a href="https://www.facebook.com/saugatbrl4" target="_blank" class="social-link facebook">Facebook</a> |
  <a href="https://www.linkedin.com/in/your-linkedin-id" target="_blank" class="social-link linkedin">LinkedIn</a>
</p>
<a href="resume/Saugat_Baral_Resume.pdf" download class="download-btn">Download My Resume</a>



function validateForm() {
  alert("Thank you! Your message has been sent.");
  return false; // Prevent actual form submission
}

/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  background-color: #fefde6; /* Pale yellowish white */
  color: #222;
  line-height: 1.6;
}

header {
  text-align: center;
  padding: 2rem;
  background-color: #fffcd5;
}

.profile-img {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 1rem;
}

nav ul {
  display: flex;
  justify-content: center;
  background: #ffd95a;
  list-style: none;
  padding: 1rem 0;
  flex-wrap: wrap;
}

nav ul li {
  margin: 0 15px;
}

nav ul li a {
  text-decoration: none;
  color: #333;
  font-weight: bold;
  transition: color 0.3s ease;
}

nav ul li a:hover {
  color: #b47d00;
}

section {
  padding: 2rem;
}

.skill-container {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  justify-content: center;
}

.skill {
  background-color: #ffeda0;
  padding: 10px 15px;
  border-radius: 20px;
  box-shadow: 1px 1px 3px #ccc;
  transition: transform 0.2s;
}

.skill:hover {
  transform: scale(1.05);
}

.timeline .entry {
  margin-bottom: 1rem;
  border-left: 3px solid #ffc107;
  padding-left: 1rem;
}

.project {
  margin-bottom: 1.5rem;
}

.project a {
  display: inline-block;
  margin-top: 0.5rem;
  text-decoration: none;
  color: #0077cc;
}

form {
  max-width: 500px;
  margin: auto;
  display: flex;
  flex-direction: column;
}

form input,
form textarea {
  padding: 0.75rem;
  margin-bottom: 1rem;
  border: 1px solid #ccc;
  border-radius: 8px;
}

form button {
  padding: 0.75rem;
  border: none;
  background: #ffd95a;
  color: #333;
  font-weight: bold;
  border-radius: 8px;
  cursor: pointer;
  transition: background 0.3s ease;
}

form button:hover {
  background: #ffcc00;
}

footer {
  text-align: center;
  padding: 1rem;
  background-color: #fffcd5;
  margin-top: 2rem;
}

/* Responsive Design */
@media (max-width: 768px) {
  nav ul {
    flex-direction: column;
  }

  .skill-container {
    justify-content: flex-start;
  }
}
.social-link {
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s ease, transform 0.2s;
}

.social-link.facebook:hover {
  color: #d60909; /* Facebook blue */
  transform: scale(1.05);
}


.social-link.linkedin:hover {
  color: #e00b0b; /* LinkedIn blue */
  transform: scale(1.05);
}
.download-btn {
  display: inline-block;
  margin-top: 1rem;
  padding: 10px 20px;
  background-color: #411ce4; /* LinkedIn blue */
  color: rgb(198, 199, 204);
  text-decoration: none;
  border-radius: 8px;
  font-weight: bold;
  transition: background 0.3s ease, transform 0.2s;
}

.download-btn:hover {
  background-color: #eee8e1;
  transform: scale(1.05);
}
body {
  margin: 0;
  background-color: #fdfdea; /* Pale yellowish-white */
  font-family: Arial, sans-serif;
}

.social-icons {
  position: fixed;
  top: 20px;
  left: 20px;
  display: flex;
  gap: 15px;
  z-index: 999;
}

.social-icons a {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 45px;
  height: 45px;
  border-radius: 50%;
  text-decoration: none;
  color: white;
  font-size: 20px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}


Uploading resume…]()

[Uploading<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Saugat Baral | Digital Resume</title>
  <link rel="stylesheet" href="style.css" />
  <script src="script.js" defer></script>
  <!-- Font Awesome CDN -->
<link
  rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"
  integrity="sha512-p0N+K71hUqgxu/VXCMj2U4vhWxZ1xtkg7AQaHa0sy5V+QqhtdQAYmK8T1dRvPgOdtXcgb7SAOMKK1RY+4UC6+g=="
  crossorigin="anonymous"
  referrerpolicy="no-referrer"
/>

</head>
<body>

  <header>
    <img src="saugat.jpg" alt="Saugat Baral" class="profile-img" />
    <h1>Saugat Baral</h1>
    <p>Bachelor of IT Student | Tech Enthusiast</p>
  </header>

  <nav>
    <ul>
      <li><a href="#about">About Me</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#education">Education & Experience</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm Saugat Baral from Pokhara, Nepal, currently studying BIT at SHEA in Australia. Passionate about technology, software development, and creating interactive digital experiences.</p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <div class="skill-container">
      <div class="skill">HTML</div>
      <div class="skill">CSS</div>
      <div class="skill">JavaScript</div>
      <div class="skill">Python</div>
      <div class="skill">Communication</div>
      <div class="skill">Teamwork</div>
    </div>
  </section>

  <section id="education">
    <h2>Education & Experience</h2>
    <div class="timeline">
      <div class="entry">
        <h3>SHEA (Skyline Higher Education Australia)</h3>
        <p>Bachelor of IT – 2023–Present</p>
      </div>
      <div class="entry">
        <h3>Skyline International College</h3>
        <p>Diploma of IT – Completed</p>
      </div>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Student Performance Dashboard</h3>
      <p>Analyzed student scores using Python and visualized data insights with Matplotlib.</p>
      <a href="https://github.com/saugatbrl4/student-dashboard" target="_blank">View on GitHub</a>
    </div>
    <div class="project">
      <h3>Personal Portfolio Website</h3>
      <p>Created a fully responsive website using HTML, CSS, and JavaScript.</p>
      <a href="https://github.com/saugatbrl4/portfolio" target="_blank">View on GitHub</a>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form onsubmit="return validateForm()">
      <input type="text" id="name" placeholder="Your Name" required />
      <input type="email" id="email" placeholder="Your Email" required />
      <textarea id="message" placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
    <p>Email: <a href="mailto:saggubrl@gmail.com">saggubrl@gmail.com</a></p>
    <p><a href="https://www.facebook.com/saugatbrl4" target="_blank">Facebook</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Saugat Baral | Digital Resume</p>
  </footer>

</body>
</html>
<p>
  <a href="https://www.facebook.com/saugatbrl4" target="_blank" class="social-link facebook">Facebook</a> |
  <a href="https://www.linkedin.com/in/your-linkedin-id" target="_blank" class="social-link linkedin">LinkedIn</a>
</p>
<a href="resume/Saugat_Baral_Resume.pdf" download class="download-btn">Download My Resume</a>



function validateForm() {
  alert("Thank you! Your message has been sent.");
  return false; // Prevent actual form submission
}

/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  background-color: #fefde6; /* Pale yellowish white */
  color: #222;
  line-height: 1.6;
}

header {
  text-align: center;
  padding: 2rem;
  background-color: #fffcd5;
}

.profile-img {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 1rem;
}

nav ul {
  display: flex;
  justify-content: center;
  background: #ffd95a;
  list-style: none;
  padding: 1rem 0;
  flex-wrap: wrap;
}

nav ul li {
  margin: 0 15px;
}

nav ul li a {
  text-decoration: none;
  color: #333;
  font-weight: bold;
  transition: color 0.3s ease;
}

nav ul li a:hover {
  color: #b47d00;
}

section {
  padding: 2rem;
}

.skill-container {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  justify-content: center;
}

.skill {
  background-color: #ffeda0;
  padding: 10px 15px;
  border-radius: 20px;
  box-shadow: 1px 1px 3px #ccc;
  transition: transform 0.2s;
}

.skill:hover {
  transform: scale(1.05);
}

.timeline .entry {
  margin-bottom: 1rem;
  border-left: 3px solid #ffc107;
  padding-left: 1rem;
}

.project {
  margin-bottom: 1.5rem;
}

.project a {
  display: inline-block;
  margin-top: 0.5rem;
  text-decoration: none;
  color: #0077cc;
}

form {
  max-width: 500px;
  margin: auto;
  display: flex;
  flex-direction: column;
}

form input,
form textarea {
  padding: 0.75rem;
  margin-bottom: 1rem;
  border: 1px solid #ccc;
  border-radius: 8px;
}

form button {
  padding: 0.75rem;
  border: none;
  background: #ffd95a;
  color: #333;
  font-weight: bold;
  border-radius: 8px;
  cursor: pointer;
  transition: background 0.3s ease;
}

form button:hover {
  background: #ffcc00;
}

footer {
  text-align: center;
  padding: 1rem;
  background-color: #fffcd5;
  margin-top: 2rem;
}

/* Responsive Design */
@media (max-width: 768px) {
  nav ul {
    flex-direction: column;
  }

  .skill-container {
    justify-content: flex-start;
  }
}
.social-link {
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s ease, transform 0.2s;
}

.social-link.facebook:hover {
  color: #d60909; /* Facebook blue */
  transform: scale(1.05);
}


.social-link.linkedin:hover {
  color: #e00b0b; /* LinkedIn blue */
  transform: scale(1.05);
}
.download-btn {
  display: inline-block;
  margin-top: 1rem;
  padding: 10px 20px;
  background-color: #411ce4; /* LinkedIn blue */
  color: rgb(198, 199, 204);
  text-decoration: none;
  border-radius: 8px;
  font-weight: bold;
  transition: background 0.3s ease, transform 0.2s;
}

.download-btn:hover {
  background-color: #eee8e1;
  transform: scale(1.05);
}
body {
  margin: 0;
  background-color: #fdfdea; /* Pale yellowish-white */
  font-family: Arial, sans-serif;
}

.social-icons {
  position: fixed;
  top: 20px;
  left: 20px;
  display: flex;
  gap: 15px;
  z-index: 999;
}

.social-icons a {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 45px;
  height: 45px;
  border-radius: 50%;
  text-decoration: none;
  color: white;
  font-size: 20px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}


 index.html…]()

 ![Uploading[Uploading script.js…]() saugat.jpg…]()

 

function validateForm() {
  alert("Thank you! Your message has been sent.");
  return false; // Prevent actual form submission
}

/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  background-color: #fefde6; /* Pale yellowish white */
  color: #222;
  line-height: 1.6;
}

header {
  text-align: center;
  padding: 2rem;
  background-color: #fffcd5;
}

.profile-img {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 1rem;
}

nav ul {
  display: flex;
  justify-content: center;
  background: #ffd95a;
  list-style: none;
  padding: 1rem 0;
  flex-wrap: wrap;
}

nav ul li {
  margin: 0 15px;
}

nav ul li a {
  text-decoration: none;
  color: #333;
  font-weight: bold;
  transition: color 0.3s ease;
}

nav ul li a:hover {
  color: #b47d00;
}

section {
  padding: 2rem;
}

.skill-container {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  justify-content: center;
}

.skill {
  background-color: #ffeda0;
  padding: 10px 15px;
  border-radius: 20px;
  box-shadow: 1px 1px 3px #ccc;
  transition: transform 0.2s;
}

.skill:hover {
  transform: scale(1.05);
}

.timeline .entry {
  margin-bottom: 1rem;
  border-left: 3px solid #ffc107;
  padding-left: 1rem;
}

.project {
  margin-bottom: 1.5rem;
}

.project a {
  display: inline-block;
  margin-top: 0.5rem;
  text-decoration: none;
  color: #0077cc;
}

form {
  max-width: 500px;
  margin: auto;
  display: flex;
  flex-direction: column;
}

form input,
form textarea {
  padding: 0.75rem;
  margin-bottom: 1rem;
  border: 1px solid #ccc;
  border-radius: 8px;
}

form button {
  padding: 0.75rem;
  border: none;
  background: #ffd95a;
  color: #333;
  font-weight: bold;
  border-radius: 8px;
  cursor: pointer;
  transition: background 0.3s ease;
}

form button:hover {
  background: #ffcc00;
}

footer {
  text-align: center;
  padding: 1rem;
  background-color: #fffcd5;
  margin-top: 2rem;
}

/* Responsive Design */
@media (max-width: 768px) {
  nav ul {
    flex-direction: column;
  }

  .skill-container {
    justify-content: flex-start;
  }
}
.social-link {
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s ease, transform 0.2s;
}

.social-link.facebook:hover {
  color: #d60909; /* Facebook blue */
  transform: scale(1.05);
}


.social-link.linkedin:hover {
  color: #e00b0b; /* LinkedIn blue */
  transform: scale(1.05);
}
.download-btn {
  display: inline-block;
  margin-top: 1rem;
  padding: 10px 20px;
  background-color: #411ce4; /* LinkedIn blue */
  color: rgb(198, 199, 204);
  text-decoration: none;
  border-radius: 8px;
  font-weight: bold;
  transition: background 0.3s ease, transform 0.2s;
}

.download-btn:hover {
  background-color: #eee8e1;
  transform: scale(1.05);
}
body {
  margin: 0;
  background-color: #fdfdea; /* Pale yellowish-white */
  font-family: Arial, sans-serif;
}

.social-icons {
  position: fixed;
  top: 20px;
  left: 20px;
  display: flex;
  gap: 15px;
  z-index: 999;
}

.social-icons a {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 45px;
  height: 45px;
  border-radius: 50%;
  text-decoration: none;
  color: white;
  font-size: 20px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}



<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Saugat Baral | Digital Resume</title>
  <link rel="stylesheet" href="style.css" />
  <script src="script.js" defer></script>
  <!-- Font Awesome CDN -->
<link
  rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"
  integrity="sha512-p0N+K71hUqgxu/VXCMj2U4vhWxZ1xtkg7AQaHa0sy5V+QqhtdQAYmK8T1dRvPgOdtXcgb7SAOMKK1RY+4UC6+g=="
  crossorigin="anonymous"
  referrerpolicy="no-referrer"
/>

</head>
<body>

  <header>
    <img src="saugat.jpg" alt="Saugat Baral" class="profile-img" />
    <h1>Saugat Baral</h1>
    <p>Bachelor of IT Student | Tech Enthusiast</p>
  </header>

  <nav>
    <ul>
      <li><a href="#about">About Me</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#education">Education & Experience</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm Saugat Baral from Pokhara, Nepal, currently studying BIT at SHEA in Australia. Passionate about technology, software development, and creating interactive digital experiences.</p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <div class="skill-container">
      <div class="skill">HTML</div>
      <div class="skill">CSS</div>
      <div class="skill">JavaScript</div>
      <div class="skill">Python</div>
      <div class="skill">Communication</div>
      <div class="skill">Teamwork</div>
    </div>
  </section>

  <section id="education">
    <h2>Education & Experience</h2>
    <div class="timeline">
      <div class="entry">
        <h3>SHEA (Skyline Higher Education Australia)</h3>
        <p>Bachelor of IT – 2023–Present</p>
      </div>
      <div class="entry">
        <h3>Skyline International College</h3>
        <p>Diploma of IT – Completed</p>
      </div>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Student Performance Dashboard</h3>
      <p>Analyzed student scores using Python and visualized data insights with Matplotlib.</p>
      <a href="https://github.com/saugatbrl4/student-dashboard" target="_blank">View on GitHub</a>
    </div>
    <div class="project">
      <h3>Personal Portfolio Website</h3>
      <p>Created a fully responsive website using HTML, CSS, and JavaScript.</p>
      <a href="https://github.com/saugatbrl4/portfolio" target="_blank">View on GitHub</a>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form onsubmit="return validateForm()">
      <input type="text" id="name" placeholder="Your Name" required />
      <input type="email" id="email" placeholder="Your Email" required />
      <textarea id="message" placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
    <p>Email: <a href="mailto:saggubrl@gmail.com">saggubrl@gmail.com</a></p>
    <p><a href="https://www.facebook.com/saugatbrl4" target="_blank">Facebook</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Saugat Baral | Digital Resume</p>
  </footer>

</body>
</html>
<p>
  <a href="https://www.facebook.com/saugatbrl4" target="_blank" class="social-link facebook">Facebook</a> |
  <a href="https://www.linkedin.com/in/your-linkedin-id" target="_blank" class="social-link linkedin">LinkedIn</a>
</p>
<a href="resume/Saugat_Baral_Resume.pdf" download class="download-btn">Download My Resume</a>


[Uploa/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  background-color: #fefde6; /* Pale yellowish white */
  color: #222;
  line-height: 1.6;
}

header {
  text-align: center;
  padding: 2rem;
  background-color: #fffcd5;
}

.profile-img {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 1rem;
}

nav ul {
  display: flex;
  justify-content: center;
  background: #ffd95a;
  list-style: none;
  padding: 1rem 0;
  flex-wrap: wrap;
}

nav ul li {
  margin: 0 15px;
}

nav ul li a {
  text-decoration: none;
  color: #333;
  font-weight: bold;
  transition: color 0.3s ease;
}

nav ul li a:hover {
  color: #b47d00;
}

section {
  padding: 2rem;
}

.skill-container {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  justify-content: center;
}

.skill {
  background-color: #ffeda0;
  padding: 10px 15px;
  border-radius: 20px;
  box-shadow: 1px 1px 3px #ccc;
  transition: transform 0.2s;
}

.skill:hover {
  transform: scale(1.05);
}

.timeline .entry {
  margin-bottom: 1rem;
  border-left: 3px solid #ffc107;
  padding-left: 1rem;
}

.project {
  margin-bottom: 1.5rem;
}

.project a {
  display: inline-block;
  margin-top: 0.5rem;
  text-decoration: none;
  color: #0077cc;
}

form {
  max-width: 500px;
  margin: auto;
  display: flex;
  flex-direction: column;
}

form input,
form textarea {
  padding: 0.75rem;
  margin-bottom: 1rem;
  border: 1px solid #ccc;
  border-radius: 8px;
}

form button {
  padding: 0.75rem;
  border: none;
  background: #ffd95a;
  color: #333;
  font-weight: bold;
  border-radius: 8px;
  cursor: pointer;
  transition: background 0.3s ease;
}

form button:hover {
  background: #ffcc00;
}

footer {
  text-align: center;
  padding: 1rem;
  background-color: #fffcd5;
  margin-top: 2rem;
}

/* Responsive Design */
@media (max-width: 768px) {
  nav ul {
    flex-direction: column;
  }

  .skill-container {
    justify-content: flex-start;
  }
}
.social-link {
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s ease, transform 0.2s;
}

.social-link.facebook:hover {
  color: #d60909; /* Facebook blue */
  transform: scale(1.05);
}


.social-link.linkedin:hover {
  color: #e00b0b; /* LinkedIn blue */
  transform: scale(1.05);
}
.download-btn {
  display: inline-block;
  margin-top: 1rem;
  padding: 10px 20px;
  background-color: #411ce4; /* LinkedIn blue */
  color: rgb(198, 199, 204);
  text-decoration: none;
  border-radius: 8px;
  font-weight: bold;
  transition: background 0.3s ease, transform 0.2s;
}

.download-btn:hover {
  background-color: #eee8e1;
  transform: scale(1.05);
}
body {
  margin: 0;
  background-color: #fdfdea; /* Pale yellowish-white */
  font-family: Arial, sans-serif;
}

.social-icons {
  position: fixed;
  top: 20px;
  left: 20px;
  display: flex;
  gap: 15px;
  z-index: 999;
}

.social-icons a {
  display: flex;
  align-items: center;
  justify-content: center;
  width: 45px;
  height: 45px;
  border-radius: 50%;
  text-decoration: none;
  color: white;
  font-size: 20px;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}



<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Saugat Baral | Digital Resume</title>
  <link rel="stylesheet" href="style.css" />
  <script src="script.js" defer></script>
  <!-- Font Awesome CDN -->
<link
  rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"
  integrity="sha512-p0N+K71hUqgxu/VXCMj2U4vhWxZ1xtkg7AQaHa0sy5V+QqhtdQAYmK8T1dRvPgOdtXcgb7SAOMKK1RY+4UC6+g=="
  crossorigin="anonymous"
  referrerpolicy="no-referrer"
/>

</head>
<body>

  <header>
    <img src="saugat.jpg" alt="Saugat Baral" class="profile-img" />
    <h1>Saugat Baral</h1>
    <p>Bachelor of IT Student | Tech Enthusiast</p>
  </header>

  <nav>
    <ul>
      <li><a href="#about">About Me</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#education">Education & Experience</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm Saugat Baral from Pokhara, Nepal, currently studying BIT at SHEA in Australia. Passionate about technology, software development, and creating interactive digital experiences.</p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <div class="skill-container">
      <div class="skill">HTML</div>
      <div class="skill">CSS</div>
      <div class="skill">JavaScript</div>
      <div class="skill">Python</div>
      <div class="skill">Communication</div>
      <div class="skill">Teamwork</div>
    </div>
  </section>

  <section id="education">
    <h2>Education & Experience</h2>
    <div class="timeline">
      <div class="entry">
        <h3>SHEA (Skyline Higher Education Australia)</h3>
        <p>Bachelor of IT – 2023–Present</p>
      </div>
      <div class="entry">
        <h3>Skyline International College</h3>
        <p>Diploma of IT – Completed</p>
      </div>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Student Performance Dashboard</h3>
      <p>Analyzed student scores using Python and visualized data insights with Matplotlib.</p>
      <a href="https://github.com/saugatbrl4/student-dashboard" target="_blank">View on GitHub</a>
    </div>
    <div class="project">
      <h3>Personal Portfolio Website</h3>
      <p>Created a fully responsive website using HTML, CSS, and JavaScript.</p>
      <a href="https://github.com/saugatbrl4/portfolio" target="_blank">View on GitHub</a>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form onsubmit="return validateForm()">
      <input type="text" id="name" placeholder="Your Name" required />
      <input type="email" id="email" placeholder="Your Email" required />
      <textarea id="message" placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
    <p>Email: <a href="mailto:saggubrl@gmail.com">saggubrl@gmail.com</a></p>
    <p><a href="https://www.facebook.com/saugatbrl4" target="_blank">Facebook</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Saugat Baral | Digital Resume</p>
  </footer>

</body>
</html>
<p>
  <a href="https://www.facebook.com/saugatbrl4" target="_blank" class="social-link facebook">Facebook</a> |
  <a href="https://www.linkedin.com/in/your-linkedin-id" target="_blank" class="social-link linkedin">LinkedIn</a>
</p>
<a href="resume/Saugat_Baral_Resume.pdf" download class="download-btn">Download My Resume</a>



function validateForm() {
  alert("Thank you! Your message has been sent.");
  return false; // Prevent actual form submission
}
ding style.css…]()


