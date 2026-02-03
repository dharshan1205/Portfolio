# Ex01 Portfolio
## Date: 02/02/2026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
## index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dharshan Portfolio</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&family=Montserrat:wght@800;900&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Header -->
     <link rel="stylesheet" href="style.css">
    <header>
        <div class="container nav-container">
            <div class="logo">PORTFOLIO</div>
            <nav class="nav-links">
                <a href="#home">Home</a>
                <a href="#skills">Skills</a>
                <a href="#projects">Projects</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="container hero-content">
            <div class="hero-text">
                <h1>Creative Designer & Web Developer</h1>
                <h2>Dharshan R</h2>
                <p>I'm a passionate designer and web developer specializing in creating visually stunning and functional digital experiences. With expertise in modern web technologies and a keen eye for detail, I bring ideas to life with creative solutions.</p>
                <a href="#contact" class="btn">Get In Touch</a>
            </div>
            <div class="profile-card">
                <div class="profile-image">
                    <!-- Replace with your image -->
                    <img src="dharshan.png.jpeg" alt="Dharshan R">
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section class="skills" id="skills">
        <div class="container">
            <h2 class="section-title">My Skills</h2>
            <div class="skills-container">
                <div class="skill-item">
                    <div class="skill-icon">
                        <i class="fas fa-code"></i>
                    </div>
                    <h3>Web Development</h3>
                    <p>HTML5, CSS3, JavaScript and modern frameworks</p>
                </div>
                <div class="skill-item">
                    <div class="skill-icon">
                        <i class="fas fa-paint-brush"></i>
                    </div>
                    <h3>UI/UX Design</h3>
                    <p>User-centered design, wireframing, prototyping, and responsive design</p>
                </div>
                <div class="skill-item">
                    <div class="skill-icon">
                        <i class="fas fa-cube"></i>
                    </div>
                    <h3>3D Design</h3>
                    <p>3D modeling, animation, and interactive 3D web experiences</p>
                </div>
                <div class="skill-item">
                    <div class="skill-icon">
                        <i class="fas fa-mobile-alt"></i>
                    </div>
                    <h3>Mobile Design</h3>
                    <p>Responsive design, and progressive web applications</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section class="projects" id="projects">
        <div class="container">
            <h2 class="section-title">My Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <div class="project-image">
                        <img src="https://images.unsplash.com/photo-1551650975-87deedd944c3?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1674&q=80" alt="Project 1">
                    </div>
                    <div class="project-content">
                        <h3>Web Development</h3>
                        <p>An immersive experience with interactive product visualization website creating.</p>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-image">
                        <img src="https://images.unsplash.com/photo-1558618666-fcd25c85cd64?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1674&q=80" alt="Project 2">
                    </div>
                    <div class="project-content">
                        <h3>Interactive Portfolio</h3>
                        <p>A creative portfolio website with 3D animations and interactive elements.</p>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-image">
                        <img src="https://images.unsplash.com/photo-1618005198919-d3d4b5a92ead?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1674&q=80" alt="Project 3">
                    </div>
                    <div class="project-content">
                        <h3>E commerce website</h3>
                        <p>Making a attractive and your own requirment website.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <div class="container">
            <h2 class="section-title">Get In Touch</h2>
            <div class="contact-container">
                <div class="contact-info">
                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="fas fa-envelope"></i>
                        </div>
                        <div>
                            <h3>Email</h3>
                            <p>dharshan1205@icloud.com/p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="fas fa-phone"></i>
                        </div>
                        <div>
                            <h3>Phone</h3>
                            <p>+91 7358759007</p>
                        </div>
                    </div>
                    <div class="contact-item">
                        <div class="contact-icon">
                            <i class="fas fa-map-marker-alt"></i>
                        </div>
                        <div>
                            <h3>Location</h3>
                            <p>Saveetha engineering college</p>
                        </div>
                    </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container">
            <div class="social-links">
                <a href="https://www.linkedin.com/in/dharshan-r-aa7aa3390/" class="social-link">
                    <i class="fab fa-linkedin-in"></i>
                </a>
                <a href="https://github.com/dharshan1205" class="social-link">
                    <i class="fab fa-github"></i>
                </a>
    </footer>

    <script src="slider.js"></script>
</body>
</html>
```
## Style.css
```
* {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --primary: #6c63ff;
            --secondary: #ff6584;
            --dark: #1a1a2e;
            --light: #f5f5f7;
            --accent: #36d1dc;
            --shadow: 0 20px 40px rgba(0, 0, 0, 0.2);
        }

        body {
            font-family: 'Poppins', sans-serif;
            background-color: var(--dark);
            color: var(--light);
            overflow-x: hidden;
            perspective: 1000px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header & Navigation */
        header {
            position: fixed;
            top: 0;
            width: 100%;
            padding: 25px 0;
            z-index: 1000;
            background: rgba(26, 26, 46, 0.9);
            backdrop-filter: blur(10px);
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }

        .nav-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-weight: 900;
            font-size: 28px;
            background: linear-gradient(to right, var(--primary), var(--accent));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            letter-spacing: 1px;
        }

        .nav-links {
            display: flex;
            gap: 40px;
        }

        .nav-links a {
            color: var(--light);
            text-decoration: none;
            font-weight: 500;
            position: relative;
            padding: 5px 0;
            transition: color 0.3s;
        }

        .nav-links a:hover {
            color: var(--primary);
        }

        .nav-links a::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 0;
            height: 2px;
            background: linear-gradient(to right, var(--primary), var(--accent));
            transition: width 0.3s;
        }

        .nav-links a:hover::after {
            width: 100%;
        }

        /* Hero Section */
        .hero {
            padding: 180px 0 120px;
            position: relative;
        }

        .hero-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 60px;
            align-items: center;
        }

        .hero-text h1 {
            font-size: 3.5rem;
            line-height: 1.2;
            margin-bottom: 20px;
            background: linear-gradient(to right, var(--light), var(--primary));
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }

        .hero-text h2 {
            font-size: 1.8rem;
            font-weight: 400;
            margin-bottom: 30px;
            color: var(--secondary);
        }

        .hero-text p {
            font-size: 1.1rem;
            line-height: 1.8;
            margin-bottom: 40px;
            opacity: 0.9;
        }

        .btn {
            display: inline-block;
            padding: 15px 35px;
            background: linear-gradient(to right, var(--primary), var(--accent));
            color: white;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 600;
            letter-spacing: 1px;
            text-transform: uppercase;
            transition: transform 0.3s, box-shadow 0.3s;
            box-shadow: var(--shadow);
            border: none;
            cursor: pointer;
        }

        .btn:hover {
            transform: translateY(-5px);
            box-shadow: 0 25px 50px rgba(108, 99, 255, 0.3);
        }

        /* 3D Profile Card */
        .profile-card {
            position: relative;
            transform-style: preserve-3d;
            transition: transform 0.8s;
            width: 350px;
            height: 450px;
            margin: 0 auto;
        }

        .profile-card:hover {
            transform: rotateY(10deg) rotateX(5deg);
        }

        .profile-image {
            width: 100%;
            height: 100%;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: var(--shadow);
            transform: translateZ(30px);
            border: 5px solid rgba(255, 255, 255, 0.1);
        }

        .profile-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.8s;
        }

        .profile-card:hover .profile-image img {
            transform: scale(1.05);
        }

        .profile-card::before {
            content: '';
            position: absolute;
            top: 20px;
            left: -20px;
            width: 100%;
            height: 100%;
            background: linear-gradient(45deg, var(--primary), var(--secondary));
            border-radius: 20px;
            transform: translateZ(-30px);
            opacity: 0.7;
        }

        .profile-card::after {
            content: '';
            position: absolute;
            top: 40px;
            left: -40px;
            width: 100%;
            height: 100%;
            background: linear-gradient(45deg, var(--accent), transparent);
            border-radius: 20px;
            transform: translateZ(-60px);
            opacity: 0.4;
        }

        /* Skills Section */
        .skills {
            padding: 100px 0;
            background: rgba(0, 0, 0, 0.2);
        }

        .section-title {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 60px;
            position: relative;
        }

        .section-title::after {
            content: '';
            position: absolute;
            bottom: -15px;
            left: 50%;
            transform: translateX(-50%);
            width: 80px;
            height: 4px;
            background: linear-gradient(to right, var(--primary), var(--accent));
            border-radius: 2px;
        }

        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 30px;
        }

        .skill-item {
            background: rgba(255, 255, 255, 0.05);
            border-radius: 15px;
            padding: 30px;
            text-align: center;
            transition: transform 0.5s, background 0.5s;
            border: 1px solid rgba(255, 255, 255, 0.1);
            transform-style: preserve-3d;
        }

        .skill-item:hover {
            transform: translateY(-15px) translateZ(20px);
            background: rgba(108, 99, 255, 0.1);
        }

        .skill-icon {
            font-size: 3rem;
            margin-bottom: 20px;
            color: var(--primary);
        }

        .skill-item h3 {
            font-size: 1.5rem;
            margin-bottom: 15px;
        }

        /* Projects Section */
        .projects {
            padding: 100px 0;
        }

        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 30px;
        }

        .project-card {
            border-radius: 15px;
            overflow: hidden;
            box-shadow: var(--shadow);
            transform-style: preserve-3d;
            transition: transform 0.5s;
            background: rgba(255, 255, 255, 0.05);
        }

        .project-card:hover {
            transform: translateY(-15px) rotateX(5deg);
        }

        .project-image {
            height: 200px;
            overflow: hidden;
        }

        .project-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.8s;
        }

        .project-card:hover .project-image img {
            transform: scale(1.1);
        }

        .project-content {
            padding: 25px;
        }

        .project-content h3 {
            font-size: 1.4rem;
            margin-bottom: 10px;
        }

        /* Contact Section */
        .contact {
            padding: 100px 0;
            background: rgba(0, 0, 0, 0.2);
        }

        .contact-container {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 60px;
        }

        .contact-info {
            display: flex;
            flex-direction: column;
            gap: 25px;
        }

        .contact-item {
            display: flex;
            padding-left: 450px;
            align-items: center;
            gap: 15px;
        }

        .contact-icon {
            width: 50px;
            height: 50px;
            background: linear-gradient(to right, var(--primary), var(--accent));
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.2rem;
        }

        /* Footer */
        footer {
            padding: 40px 0;
            text-align: center;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-bottom: 30px;
        }

        .social-link {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.05);
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--light);
            font-size: 1.3rem;
            transition: all 0.3s;
        }

        .social-link:hover {
            background: linear-gradient(to right, var(--primary), var(--accent));
            transform: translateY(-5px);
        }

        /* Responsive */
        @media (max-width: 992px) {
            .hero-content {
                grid-template-columns: 1fr;
                text-align: center;
            }
            
            .profile-card {
                order: -1;
                margin-bottom: 40px;
            }
            
            .contact-container {
                grid-template-columns: 1fr;
            }
        }

        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }
            
            .hero-text h1 {
                font-size: 2.5rem;
            }
            
            .profile-card {
                width: 280px;
                height: 380px;
            }
        }
```
## Script.js
```
 // 3D effect for the profile card on mouse move
        document.addEventListener('DOMContentLoaded', function() {
            const profileCard = document.querySelector('.profile-card');
            
            document.addEventListener('mousemove', (e) => {
                const xAxis = (window.innerWidth / 2 - e.pageX) / 25;
                const yAxis = (window.innerHeight / 2 - e.pageY) / 25;
                
                profileCard.style.transform = `rotateY(${xAxis}deg) rotateX(${yAxis}deg)`;
            });
            
            // Return to original position when mouse leaves
            document.addEventListener('mouseleave', () => {
                profileCard.style.transform = 'rotateY(0deg) rotateX(0deg)';
            });
            
            // Smooth scrolling for navigation links
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function (e) {
                    e.preventDefault();
                    
                    const targetId = this.getAttribute('href');
                    if(targetId === '#') return;
                    
                    const targetElement = document.querySelector(targetId);
                    if(targetElement) {
                        window.scrollTo({
                            top: targetElement.offsetTop - 80,
                            behavior: 'smooth'
                        });
                    }
                });
            });
            
            // Form submission
            const contactForm = document.querySelector('.contact-form');
            contactForm.addEventListener('submit', function(e) {
                e.preventDefault();
                alert('Thank you for your message! I will get back to you soon.');
                contactForm.reset();
            });
        });
```

## OUTPUT
<img width="1896" height="1023" alt="1" src="https://github.com/user-attachments/assets/d91cfdd7-6ab9-41af-8a17-ece30c48a413" />
<img width="1893" height="774" alt="2" src="https://github.com/user-attachments/assets/43e94d9c-55f5-401a-a8cb-5130e85b706b" />
<img width="1852" height="774" alt="3" src="https://github.com/user-attachments/assets/c1c4919f-fc19-4838-b234-b9102a862531" />
<img width="1897" height="868" alt="4" src="https://github.com/user-attachments/assets/9c8edf92-7e6d-4cd3-8cf0-64c037a761fd" />

## Output Link:
file:///C:/portfolio.htmk/index.html#contact

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
