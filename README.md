# Resume Landing Page 🌟

A sleek, responsive, and professional **resume landing page** built using **React** and **Bootstrap** to showcase skills, experience, and projects interactively.

## 🚀 Features

- **Responsive Design:** Works flawlessly across all devices.
- **Dark-Themed Aesthetics:** Professional and modern look.
- **Bootstrap Components:** Ensuring a clean, polished UI.
- **React Modular Structure:** Easily customizable and scalable.
- **Smooth Animations:** Enhancing user experience with subtle transitions.

## 🛠️ Technologies Used

- **React.js**
- **Bootstrap 5**
- **JavaScript (ES6+)**
- **CSS (custom styling)**
- **GitHub Pages (Deployment)**

## 🔧 Installation & Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/ankit01mishra01/resume-landing-page.git
   cd resume-landing-page




# Resume-Landing-Page
🚀 Landing Page Resume A clean and professional HTML &amp; CSS landing page showcasing my resume, skills, and projects. Designed with responsive styling for an elegant user experience. Tech Stack: HTML, CSS, 

HTML CODE -
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ankit Mishra - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1><br>ANKIT MISHRA<br></h1>
        <nav>
            <ul>
                <li>ankit.forwork09@gmail.com</li>
                <li>6263491402</li>
                <li><a href="https://www.linkedin.com/in/ankit-mishra09/">Linkedin</a></li>
                <li><a href="https://github.com/Ankit01mishra01">Github</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About me</h2>
        <p>"I am a B.Tech Computer Science student From Vellore Institue Of Technology Bhopal Passionate about building efficient, real-world tech solutions, I enjoy exploring full-stack development and continuously enhancing my problem-solving skills."</p>
    </section>

    <section id="skills">
        <h2>Skills </h2>
        <ul>
            <li>Programming Language: Java,Java Script</li>
            <li>Programming Concepts: DSA, Object-Oriented Programming</li>
            <li>DataBases: My SQL, MongoDb</li>
            <li>Tools/Platform: GitHub , Git, VS Code,intellij IDEA</li>
            <li>Language:English , Hindi</li>
        </ul>
    </section>

    <section id="projects">
        <h2>ACADEMIC PROJECT</h2>
        <div class="project">
            <h3>Amazon Clone (Tech stack : Html,Css)</h3>
            <p>Developed an Amazon clone using HTML and CSS replicating core UI features like homepage layout, product listings, cart functionality, and responsive design to enhance user experience."</p>
            <a href="https://amazon-clone-ten-flax.vercel.app" target="_blank">View Project</a>
        </div>

        <div class="project">
            <h3>Trip Expense (Tech stack: React.Js, Node.Js, MongoDB, Express.Js)</h3>
            <p>Developed a full-stack trip management web app using React.js, Node.js, Express.js, and MongoDB, allowing users to split expenses in real-time, automate calculations, and store trip data securely with optimized database performance.</p>
        </div>
        <div class="project">
            <h3>Car Rental (Tech stack: React.Js, Node.Js, MongoDB, Express.Js )</h3>
            <p>Created a full-stack car rental web application using the MERN stack (MongoDB, Express.js, React.js, Node.js), featuring an intuitive UI with car filters, smooth booking flows, and RESTful APIs for fast, reliable transactions and efficient data management</p>
        </div>
    </section>
    <section>
        <div class="education">
            <h3>EDUCATION</h3>
            <p>Vellore Institue Of Technology<br>
                 Bachelor of Technology, Computer Science, CGPA-7.12</p>

            <p>The Eminent Hr Sr School,Vidisha <br>
                Class- 12th, Percentage- 66.2%</p>

            <p>Saket MGM Sr Sec School,Vidisha <br>
            Class- 10th, Percentage- 68.9%</p>
        </div>
    </section>

    <section>
        <div class="certications">
            <h3>CERTIFICATIONS</h3>
            <p> Iamneo High Performance Coding(DSA using Java)</p>
            <p> Google Cloud Certified Cloud Digital Leader</p>
        </div>
    </section>
</body>
</html>



CSS CODE -
/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', Tahoma, sans-serif;
  background-color: #f9fafb;
  color: #2d3748;
  line-height: 1.7;
  padding: 20px;
  max-width: 1000px;
  margin: auto;
}

/* Header */
header {
  text-align: center;
  background-color: #1e293b; /* Navy */
  color: #ffffff;
  padding: 50px 20px;
  border-radius: 10px;
  margin-bottom: 40px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.08);
}

header h1 {
  font-size: 2.8rem;
  margin-bottom: 10px;
  letter-spacing: 1px;
}

nav ul {
  list-style: none;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  margin-top: 15px;
}

nav ul li {
  font-size: 1rem;
  color: #cbd5e1;
}

nav a {
  color: #60a5fa;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.3s ease;
}

nav a:hover {
  color: #ffffff;
}

/* Sections */
section {
  background-color: #ffffff;
  border-radius: 8px;
  padding: 30px;
  margin-bottom: 30px;
  box-shadow: 0 2px 10px rgba(0,0,0,0.04);
}

h2, h3 {
  color: #1e293b;
  margin-bottom: 16px;
  font-size: 1.5rem;
  border-left: 4px solid #60a5fa;
  padding-left: 12px;
}

p {
  font-size: 1.05rem;
  margin-bottom: 12px;
}

/* Skills */
#skills ul {
  list-style: disc;
  padding-left: 20px;
}

#skills li {
  margin-bottom: 8px;
}

/* Projects */
.project {
  margin-bottom: 25px;
}

.project a {
  display: inline-block;
  margin-top: 10px;
  padding: 8px 14px;
  background-color: #1e293b;
  color: #ffffff;
  border-radius: 5px;
  text-decoration: none;
  transition: background-color 0.3s ease;
}

.project a:hover {
  background-color: #60a5fa;
  color: #1e293b;
}

/* Education & Certifications */
.education p,
.certications p {
  margin-bottom: 10px;
}

/* Responsive */
@media (max-width: 768px) {
  header h1 {
    font-size: 2rem;
  }

  nav ul {
    flex-direction: column;
    gap: 10px;
  }

  section {
    padding: 20px;
  }
}

