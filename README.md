# portfolio
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" 
          content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" 
          href=
"https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css"
          integrity=
"sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA=="
             crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="portfolio2.css">
    <link rel="stylesheet" href="responsive.css">
</head>

<body>
    <!-- Navbar header section -->
    <header class="header">
        <nav class="navbar">
            <div class="logo">
                <h2 class="logo-heading">Prashant Tyagi</h2>
            </div>
            <div class="hamburger" id="hamburger">
                <i class="fas fa-bars hamburger-icon"></i>
                <i class="fas fa-times cross-icon"></i>
            </div>
            <div class="menu">
                <ul class="menu-list">
                    <li class="menu-list-items">
                        <a class="links" href="#home">
                              Home
                          </a>
                        </li>
                    <li class="menu-list-items">
                        <a class="links" href="#about">
                              About
                          </a>
                    </li>
                    <li class="menu-list-items">
                        <a class="links" href="#services">
                              Skills
                          </a>
                    </li>
                    <li class="menu-list-items">
                        <a class="links" href="#contact">
                              Contact Me
                          </a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- Main hero banner -->
    <section id="home" class="hero">
        <div class="intro">
            <div class="headings">
                <h3 class="greet-heading">Hello, I'm</h3>
                <h1 class="my-heading">Prashant Tyagi</h1>
                <h4 class="sub-heading">
                    A Student of Computer Application and Computer Science with 3 years of Experience.
                </h4>
            </div>
            <div class="intro-buttons">
                <button class="btn common-btn">Hire Me</button>
                <button class="btn ghost-btn" onclick="document.location ='https://github.com/Prashanttyagi2004/Resume'">Get Resume</button>
            </div>
        </div>
    </section>
>
    <section id="about" class="about">
        <div class="about-text">
            <h1 class="my-heading">About Me</h1>
            <p class="lead-para">
              I am Prashant Tyagi, currently pursuing a Bachelor of Computer Applications (BCA) at I.T.S Institute of Technology and Science in Mohan Nagar, Ghaziabad. With a strong foundation in web development, Java, C, and C++, I am passionate about software development and continually expanding my skill set in this field. My goal is to leverage my technical skills to contribute effectively as a software developer, and I am currently seeking internship opportunities to gain practical experience in the industry. Driven by curiosity and a commitment to learning, I am eager to explore innovative solutions and grow as a professional.
            </p>
            <p>
              I am particularly passionate about building robust and scalable software solutions, with a keen interest in problem-solving and innovation. Throughout my academic journey, I’ve worked on several projects that have helped me apply my theoretical knowledge to real-world problems, reinforcing my skills in both front-end and back-end development.
              My objective is to secure a software development internship where I can put my skills into practice, contribute to meaningful projects, and gain valuable industry experience. As someone who values continuous learning, I am enthusiastic about staying updated on the latest trends in technology and coding practices, which will enable me to make a positive impact in the professional world.
            </p>
        </div>
        <div class="about-image">
            <img src="profile-pic (3).png" alt="About Image">
        </div>
    </section>

    <!-- Services Section -->
    <section class="services" id="services">
        <div class="services-heading">
            <h1 class="my-heading text-center">My Skills</h1>
        </div>
        <div class="services-content">
            <div class="my-row">
                <div class="my-col">
                    <div class="my-card">
                        <div class="icon">
                            <i class="fas fa-paint-brush"></i>
                        </div>
                        <h3 class="greet-heading blue-text">Web Development</h3>
                        <p class="small-para">
                            Web development refers to the creating, 
                              building, and maintaining
                            of websites. 
                        </p>
                    </div>
                </div>
                <div class="my-col">
                    <div class="my-card">
                        <div class="icon">
                            <i class="fa-solid fa-code"></i>
                        </div>
                        <h3 class="greet-heading blue-text">
                              Java
                          </h3>
                        <p class="small-para">
                           basic understanding of java programming,
                           it helps to develop the backend also.
                        </p>
                    </div>
                </div>
                <div class="my-col">
                    <div class="my-card">
                        <div class="icon">
                            <i class="fas fa-chart-line"></i>
                        </div>
                        <h3 class="greet-heading blue-text">C/C++</h3>
                        <p class="small-para">
                            it is also a programming language,
                            which is used to develop Apps amd games;
                        </p>
                    </div>
                </div>
            </div>
            <div class="my-row">
                <div class="my-col">
                    <div class="my-card">
                        <div class="icon">
                            <i class="fas fa-quote-left"></i>
                        </div>
                        <h3 class="greet-heading blue-text">
                            Data Science
                          </h3>
                        <p class="small-para">
                            Data science skills are Machine learning, Decision tree and python libraries like matplotlib, numpy and pandas. 
                        </p>
                    </div>
                </div>
                <div class="my-col">
                    <div class="my-card">
                        <div class="icon">
                            <i class="fab fa-wordpress-simple"></i>
                        </div>
                        <h3 class="greet-heading blue-text">
                              React js / Node js
                          </h3>
                        <p class="small-para">
                            Basically React js is a framework of JavaScript it make the website more responsive and effective and  Node js is used for back-end part of the  websites.
                        </p>
                    </div>
                </div>
                <div class="my-col">
                    <div class="my-card">
                        <div class="icon">
                            <i class="fas fa-video"></i>
                        </div>
                        <h3 class="greet-heading blue-text">
                              Mysql /  Mongodb
                          </h3>
                        <p class="small-para">
                            Mysql and Mongodb is uesd for database.
                            It helps to store and arrange the data in a systematic way.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact me section -->
    <section class="contact" id="contact">
        <div class="contact-heading">
            <h1 class="my-heading text-center">Contact Me</h1>
        </div>
        <div class="contact-content">
            <div class="contact-form-container">
                <h1 class="greet-heading">Get In Touch</h1>
                <form class="contact-form">
                    <input class="form-controls" type="text" 
                           placeholder="Your Name">
                    <input class="form-controls" type="text" 
                           placeholder="Your Email">
                    <input class="form-controls" type="text" 
                           placeholder="Your Phone">
                    <textarea class="form-controls" 
                              placeholder="Write your message" 
                              name="message" id="" cols="30"
                              rows="10">
                      </textarea>
                    <input class="form-btn btn common-btn" 
                           type="submit" value="Send Message">
                </form>
            </div>
            <div class="contact-details">
                <h1 class="greet-heading">My Contact Details</h1>
                <div class="details">
                    <h5 class="contact-heading">EMAIL</h5>
                    <p class="contact-text">tyagi8979369888@gmail.com</p>
                </div>
                <div class="details">
                    <h5 class="contact-heading">PHONE</h5>
                    <p class="contact-text">+91 9368034259</p>
                </div>
                <div class="details">
                    <h5 class="contact-heading">FAX</h5>
                    <p class="contact-text">+91 7060060702</p>
                </div>
                <div class="details">
                    <h5 class="contact-heading">ADDRESS</h5>
                    <p class="contact-text">Uttar Pradesh, India</p>
                    <p>Muradnagar, Ghaziabad</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer section -->
    <footer class="footer">
        <div class="footer-content text-center">
            <h4>
                Copyright © 2024 All rights reserved |
                This portfolio website is created 
                  by Prashant Tyagi
            </h4>
            <div class="social-links">
                <div class="footer-menu">
                    <ul class="footer-menu-list">
                        <li class="footer-list-items">
                            <a class="footer-links" href="#">
                                <i class="fab fa-facebook-f"></i>
                            </a>
                        </li>
                        <li class="footer-list-items">
                            <a class="footer-links" href="#">
                                <i class="fab fa-twitter"></i>
                            </a>
                        </li>
                        <li class="footer-list-items">
                            <a class="footer-links" href="#">
                                <i class="fab fa-instagram"></i>
                            </a>
                        </li>
                        <li class="footer-list-items">
                            <a class="footer-links" href="#">
                                <i class="fab fa-linkedin-in"></i>
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>

    <script src=
"https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/js/all.min.js"
        integrity=
"sha512-uKQ39gEGiyUJl4AI6L+ekBdGKpGw4xJ55+xyJG7YFlJokPNYegn9KwQ3P8A7aFQAUtUsAQHep+d/lrGqrbPIDQ=="
        crossorigin="anonymous" referrerpolicy="no-referrer">
      </script>
    <script src="script2.js"></script>
</body>
</html>
