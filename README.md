
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css" />
    <link rel="stylesheet" href="mediaqueries.css" />
    <link
            rel="icon"
            href=
"./assets/arrow.png"
            type="image/x-icon"
        />
  </head>
  
  <body>
    <nav id="desktop-nav">
      <div class="logo"><b><b>Ashri Aulia Azzahra</b></b></div>
      <div>
        <ul class="nav-links">
          <li><a href="#about">About</a></li>
          <li><a href="#experience">Experience</a></li>
          <li><a href="#projects">Projects</a></li>
          <li><a href="Project1-article/index.html">Blog</a></li>
          <li><a href="#contact">Contact</a></li>
         
        </ul>
      </div>
    </nav>
    <nav id="hamburger-nav">
      <div class="logo">Ashri Aulia Azzahra</div>
      <div class="hamburger-menu">
        <div class="hamburger-icon" onclick="toggleMenu()">
          <span></span>
          <span></span>
          <span></span>
        </div>
        <div class="menu-links">
          <li><a href="#about" onclick="toggleMenu()">About</a></li>
          <li><a href="#experience" onclick="toggleMenu()">Experience</a></li>
          <li><a href="#projects" onclick="toggleMenu()">Projects</a></li>
          <li><a href="Project1-article/index.html" onclick="toggleMenu()">Blog</a></li>
          <li><a href="#contact" onclick="toggleMenu()">Contact</a></li>
         
          
        </div>
      </div>
    </nav>
    <section id="profile">
      <div class="section__pic-container">
        <img src="./assets/about-pic.png" alt="Ashri profile picture" class="about-pic" />
      </div>
      <div class="section__text">
        <p class="section__text__p1">Hello, It's Me,</p>
        <h1 class="title">Ashri Aulia Azzahra</h1>
        <p class="section__text__p2">Interested in computer technology and data</p>
        <div class="btn-container">
          <button
            class="btn btn-color-2"
            onclick="window.open('./assets/resume-example.pdf')"
          >
            Download CV
          </button>
          <button class="btn btn-color-1" onclick="location.href='./#contact'">
            Contact Info
          </button>
        </div>
        <div id="socials-container">
          <img
            src="./assets/linkedin.png"
            alt="My LinkedIn profile"
            class="icon"
            onclick="location.href='https://www.linkedin.com/in/ashriazzr/'"
          />
          <img
            src="./assets/github.png"
            alt="My Github profile"
            class="icon"
            onclick="location.href='https://github.com/ashriazzr/'"
          />
        </div>
      </div>
    </section>
    <section id="about">
      <p class="section__text__p1">Get To Know More</p>
      <h1 class="title">About Me</h1>
      <div class="section-container">
        <div class="section__pic-container">
          <img
            src="./assets/profile-pic.gif"
            alt="Profile picture"
            class="profile-pic"
          />
        </div>
        <div class="about-details-container">
          <div class="about-containers" >
            <div class="details-container">
              <img
                src="./assets/experience.png"
                alt="Experience icon"
                class="icon"
              />
              
              <h3>Experience</h3>
              <div>
              <p  style="font-size: 12px;">2+ years Programming</p>
        
              <p style="font-size: 12px;">1+ years Data Entry</p>
            </div>
            </div>
            <div class="details-container" >
              <img
                src="./assets/education.png"
                alt="Education icon"
                class="icon"
              />
             <div style="font-size: 12px;">
              <h3 style="width: 300px;">Education</h3>

              <p><b>2018 - 2021</b> Armaniyah Vocational High School <br/> Computer and Network Technology Department</p>
            </div>
            </div>
          </div>
          <div class="text-container">
            <p>
              I have a focused interest in <b>Data-Managing</b> and <b>Programming</b>. Be an enthusiastic
individual and Team who likes to explore new things, showing enthusiasm to continue
learning and developing in the world of technology.
            </p>
          </div>
        </div>
      </div>
      <img
        src="./assets/arrow.png"
        alt="Arrow icon"
        class="icon arrow"
        onclick="location.href='./#experience'"
      />
    </section>
    <section id="experience">
      <p class="section__text__p1">Explore My</p>
      <h1 class="title">Experience</h1>
      <div class="experience-details-container">
        <div class="about-containers">
          <div class="details-container">
            <h2 class="experience-sub-title">Programming</h2>
            <div class="article-container">
              <article>
                <img
                  src="./assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>HTML</h3>
                  <p>Experienced</p>
                </div>
              </article>
              <article>
                <img
                  src="./assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>CSS</h3>
                  <p>Experienced</p>
                </div>
              </article>
              <article>
                <img
                  src="./assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>PHP</h3>
                  <p>Intermediate</p>
                </div>
              </article>
              <article>
                <img
                  src="./assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>JavaScript</h3>
                  <p>Intermediate</p>
                </div>
              </article>
              <article>
                <img
                  src="./assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>JAVA</h3>
                  <p>Experienced</p>
                </div>
              </article>
              <article>
                <img
                  src="./assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>Framework</h3>
                  <p>Experienced</p>
                </div>
              </article>
            </div>
          </div>
          <div class="details-container">
            <h2 class="experience-sub-title">Data Managing</h2>
            <div class="article-container">
              <article>
                <img
                  src="./assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>MySQL</h3>
                  <p>Intermediate</p>
                </div>
              </article>
              <article>
                <img
                  src="./assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>Excel</h3>
                  <p>Intermediate</p>
                </div>
              </article>
              <article>
                <img
                  src="./assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>Microsoft 365</h3>
                  <p>Intermediate</p>
                </div>
              </article>
              <article>
                <img
                  src="./assets/checkmark.png"
                  alt="Experience icon"
                  class="icon"
                />
                <div>
                  <h3>SAP</h3>
                  <p>Beginner</p>
                </div>
              </article>
            </div>
          </div>
        </div>
      </div>
      <div class="experience-details-container">
        <div class="about-containers">
          <div class="details-container">
            <h2 class="experience-sub-title">Other</h2>
            <div class="article-container">
            <article>
              <img
                src="./assets/checkmark.png"
                alt="Experience icon"
                class="icon"
              />
              <div>
                <h3>Figma</h3>
                <p>Experienced</p>
              </div>
            </article>
            <article>
              <img
                src="./assets/checkmark.png"
                alt="Experience icon"
                class="icon"
              />
              <div>
                <h3 >Adobe Ilustrator</h3>
                <p>Intermediate</p>
              </div>
            </article>
            <article>
              <img
                src="./assets/checkmark.png"
                alt="Experience icon"
                class="icon"
              />
              <div>
                <h3>Microsoft 365</h3>
                <p>Intermediate</p>
              </div>
            </article>
          </div>
          </div>
        </div>
      </div>
      <img
        src="./assets/arrow.png"
        alt="Arrow icon"
        class="icon arrow"
        onclick="location.href='./#projects'"
      />
    
    
    <section id="projects">
      <p class="section__text__p1">Browse My Recent</p>
      <h1 class="title">Projects</h1>
      <div class="experience-details-container">
        <div class="about-containers">
          <div class="details-container color-container">
            <div class="article-container">
              <img
                src="./assets/Bogu.png"
                alt="Project 1"
                class="project-img"
              />
            </div>
            <h2 class="experience-sub-title project-title">Figma</h2>
            <div class="btn-container">
              <button
                class="btn btn-color-2 project-btn"
                onclick="location.href='https://www.figma.com/@ashriazzr'"
              >
                Open
              </button>
              <!-- <button 
                class="btn btn-color-2 project-btn"
                onclick="location.href='https://github.com/'"
              >
                Live Demo
              </button> -->
            </div>
          </div>
          <div class="details-container color-container">
            <div class="article-container">
              <img
                src="./assets/project-2.png"
                alt="Project 2"
                class="project-img"
              />
            </div>
            <h2 class="experience-sub-title project-title">Blog</h2>
            <div class="btn-container">
              <button
                class="btn btn-color-2 project-btn"
                onclick="location.href=href='Project1-article/index.html'"
              >
                Open
              </button>
              <!-- <button
                class="btn btn-color-2 project-btn"
                onclick="location.href='https://github.com/'"
              >
                List
              </button> -->
            </div>
          </div>
          <div class="details-container color-container">
            <div class="article-container">
              <img
                src="./assets/project-2.png"
                alt="Project 3"
                class="project-img"
              />
            </div>
            <h2 class="experience-sub-title project-title">Mini Project </h2>
            <div class="btn-container">
              <button
                class="btn btn-color-2 project-btn"
                onclick="location.href='Project-Web/index.html'"
              >
                Open
              </button>
              
            </div>
          </div>
        </div>
      </div>
      
    </section>
    <section id="contact">
      <p class="section__text__p1">Get in Touch</p>
      <h1 class="title">Contact Me</h1>
      <div class="contact-info-upper-container">
        <div class="contact-info-container">
          <img
            src="./assets/email.png"
            alt="Email icon"
            class="icon contact-icon email-icon"
          />
          <p><a href="mailto:examplemail@gmail.com">ashriauliaazzahra01@gmail.com</a></p>
        </div>
        <div class="contact-info-container">
          <img
            src="./assets/linkedin.png"
            alt="LinkedIn icon"
            class="icon contact-icon"
          />
          <p><a href="https://www.linkedin.com/in/ashriazzr/">LinkedIn</a></p>
        </div>
        <div class="contact-info-container">
          <img
            src="./assets/instagram.jpeg"
            alt="Instagram icon"
            class="icon contact-icon"
          />
          <p><a href="https://www.instagram.com/bulbpeppa_sk/">Instagram</a></p>
        </div>
        <div class="contact-info-container">
          <img
            src="./assets/whatsapp.jpeg"
            alt="WhatsApp icon"
            class="icon contact-icon"
          />
          <p><a href="https://wa.me/6285176770503?text=Hallo">WhatsApp</a></p>
        </div>
      </div>
    </section>
    <footer>
      <nav>
        <div class="nav-links-container">
          <ul class="nav-links">
            <li><a href="#about">About</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="Project1-article/index.html">Blog</a></li>
            <li><a href="#contact">Contact</a></li>
           
          </ul>
        </div>
      </nav>
      <p>Copyright &#169; 2024 Ashri Aulia Azzahra. All Rights Reserved.</p>
    </footer>
    <script src="script.js"></script>
  </body>
</html>
