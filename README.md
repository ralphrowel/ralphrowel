<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dela Rosa Profile</title>    
    <link rel="stylesheet" href="profile.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
</head>
<body>
    <header>
        <header>
            <div class="headeritems">
                <a href="https://github.com" target="_blank"><i class="fab fa-github"></i> GitHub</a>
                <a href="https://facebook.com" target="_blank"><i class="fab fa-facebook"></i> Facebook</a>
                <a href="https://instagram.com" target="_blank"><i class="fab fa-instagram"></i> Instagram</a>
                <a href="https://stackoverflow.com" target="_blank"><i class="fab fa-stack-overflow"></i> Stack Overflow</a>
            </div>
        </header>
    </header>
<!-- FIRST SECTION -------------------------------------------------- -->
    <section class="sectionone">
        <div class="container">
            <span class="dot"></span>
            <div class="avatar">
                <img src="avatar.png" alt="" class="avatarpic">
            </div>
        </div>
        <div class="containerleft">
            <h1 class="name">Hey I'm Ralph</h1>
            <h1 class="description">
                Web Developer • Frontend & Backend        
            </h1>

  <div class="chatbutton">
                <a href="#chat"><i class="fas fa-comments"></i>&nbsp;Chat</a>
            </div>
        </div>
    </section>
<!-- SECOND SECTION -------------------------------------------------- -->
    <section class="sectiontwo">
        <div class="title">
            <h1>About Me</h1>
            <p>
                I'm a passionate and curious web developer just starting my freelancing journey. 
                While I may not have professional experience yet, I'm confident in my skills and eager to take on new challenges. 
                I specialize in both front-end design and back-end development, 
                and I’m committed to delivering clean, efficient, and user-friendly web solutions. 
                I’m always learning and ready to give my best to every project I take on.
            </p>
        </div>
        <section class="skills-section">
            <div class="skill-card">
                <div class="icon">
                    <img src="frontendicon.png" alt="Frontend Icon" />
            </div>
                <h2>Front-End</h2>
                <p>I design and develop user-friendly interfaces using modern web technologies. I value clean design patterns and intuitive interactions.</p>
                <h4>Technologies I Use:</h4>
                <ul>
                    <li>HTML, CSS, JavaScript</li>
                    <li>Bootstrap, Tailwind</li>
                    <li>React</li>
                    <li>Figma for UI Design</li>
                </ul>
            </div>

  <div class="skill-card">
                <div class="icon">
                    <img src="backendicon.png" alt="Backend Icon" />
                </div>
                    <h2>Back-End</h2>
                    <p>I build robust and scalable server-side systems that handle data, authentication, and APIs securely and efficiently.</p>
                    <h4>Technologies I Use:</h4>
                    <ul>
                        <li>PHP, Node.js, Java</li>
                        <li>MySQL, MongoDB</li>
                        <li>RESTful APIs</li>
                        <li>Git & Netlify</li>
                    </ul>
                </div>
        </section>

  </section>

<style>
    body {
    background-color: rgb(38, 38, 38);
    margin: 0;
    font-family: Arial, sans-serif;
}

header {
    padding: 15px 30px;
}

.headeritems {
    color: white;
    display: flex;
    justify-content: center;
    gap: 200px;
    
}

.headeritems a {
    color: white;
    font-weight: bold;
    font-size: 20px;
    text-decoration: none;
    transition: color 0.3s;
}

.headeritems a:hover {
    color: #00aced;
}
.sectionone{
    position: sticky;
    top: 0;
    height: 76vh;
    z-index: 1;

}
.sectiontwo{
    position: relative;
    height: 130vh;
    z-index: 2;
    background-color: rgb(29, 29, 29);


}
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 700px;
}

.dot {
    position: relative;
    height: 550px;
    width: 550px;
    background-color: white;
    border-radius: 50%;
    display: inline-block;
}
.avatar{
    position: absolute;
}
.avatarpic{
    width: 600px;
}
.name{
    color: white;
    position: absolute;
    font-family: "monaco" , monospace;
    top: 300px;
    padding-left: 180px;
    width: 400px;
}
.description{
    color: white;
    position: absolute;
    font-family: "monaco" , monospace;
    top: 300px;
    width: 400px;
    right: 30px;
}
.chatbutton {
    position: absolute;
    top: 400px;
    left: 160px;
}

.chatbutton a {
    display: inline-block;
    background-color: transparent;
    color: white;
    font-family: "monaco", monospace;
    text-decoration: none;
    border: 2px solid white;
    padding: 10px 20px;
    border-radius: 20px;
    transition: all 0.3s ease;
}

.chatbutton a:hover {
    background-color: #00aced;
    color: black;
    border-color: #00aced;
}
.title {
    color: white;
    font-family: "monaco", monospace;
    font-size: 20px;
    max-width: 1000px;
    margin: 100px auto;
    text-align: center;
    padding-top: 10px;
}

.skills-section {
  display: flex;
  justify-content: center;
  gap: 40px;
  padding: 80px 20px;
  border-radius: 20px 20px 0 0;
  margin-top: -50px;
  z-index: 10;
  position: relative;
  flex-wrap: wrap;
}

.skill-card {
  background-color: #ffffff;
  border-radius: 12px;
  padding: 30px;
  width: 350px;
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.08);
  text-align: center;
}

.skill-card .icon img {
  width: 60px;
  height: 60px;
  margin-bottom: 15px;
}

.skill-card h2 {
  font-size: 24px;
  margin-bottom: 10px;
  color: #111;
}

.skill-card p {
  font-size: 16px;
  color: #444;
  margin-bottom: 15px;
}

.skill-card h4 {
  font-size: 18px;
  margin-bottom: 8px;   
  color: #555;
}

.skill-card ul {
  list-style: none;
  padding: 0;
  color: #333;
  font-size: 15px;
}

.skill-card ul li {
  margin-bottom: 5px;
}

@media (max-width: 768px) {
    /* Header */
    .headeritems {
        gap: 20px;
        flex-wrap: wrap;
        font-size: 16px;
    }
    .headeritems a {
        font-size: 16px;
    }

    /* Intro text */
    .name {
        font-size: 20px;
        position: static;
        padding: 0;
        text-align: center;
        margin-top: 10px;
    }
    .description {
        font-size: 14px;
        position: static;
        padding: 0 10px;
        text-align: center;
        margin-top: 5px;
    }

    /* Chat button alignment */
    .chatbutton {
        position: static;
        margin-top: 10px;
        text-align: center;
    }

    /* Avatar & dot adjustments to prevent overflow */
    .container {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        overflow: hidden; /* prevents horizontal scroll */
    }
    .dot {
        width: 80vw; /* scale relative to screen width */
        max-width: 300px;
        height: 80vw;
        max-height: 300px;
    }
    .avatarpic {
        width: 60vw; /* scale relative to screen width */
        max-width: 200px;
        height: auto;
    }
}


</style>
</body>
</html>
