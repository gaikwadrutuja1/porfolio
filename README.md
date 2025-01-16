
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - Portfolio</title>
<style>
  {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 2.6;
    background-color: #e49eda;
    color: #333;
}

nav {
    background: #423b3b;
    color: white;
    padding: 1rem;
    text-align: center;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

/* Home Section */
.home {
    background: #b77ba5;
    color: rgb(2, 31, 13);
    padding: 50px;
    text-align: center;
}

.home h1 {
    font-size: 2.5rem;
    color: rgb(11, 67, 120);
}

.home button {
    background: #ece7eb;
    color: rgb(19, 17, 17);
    padding: 10px 20px;
    border: none;
    cursor: pointer;
    border-radius: 5px;
}

.home button a {
    color: rgb(17, 18, 19);
    text-decoration: none;
}

/* About Section */
.about {
    padding: 40px;
    background: #be9696;
    text-align: center;
}

.about img {
    width: 400px;
    height: 400px;
    object-fit: cover; 
     border-radius: 0; 
}

/* Projects Section */
.projects {
    padding: 40px;
    background: rgb(227, 160, 160);
}

.projects h2 {
    text-align: center;
    margin-bottom: 30px;
}

.project {
    margin-bottom: 20px;
}

.project h3 {
    font-size: 1.8rem;
    color: #007BFF;
}

.project a {
    color: #a82d79;
    text-decoration: none;
}

/* Contact Section */
.contact {
    padding: 40px;
    background: #c8e3b6;
}

.contact form {
    max-width: 600px;
    margin: 0 auto;
}

.contact label {
    display: block;
    margin-bottom: 10px;
}

.contact input, .contact textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.contact button {
    background: #513c6b;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
    border-radius: 5px;
    width: 100%;
}

/* Footer */
footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}

</style></head>
<body>
    <!-- Navigation -->
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Home Section -->
    <section id="home" class="home">
        <h1>Hi, I'm Ashish</h1>
        <p>A Commerce Student | Lawyer | Passionate</p>
        <button><a href="tel:+17666544133"><b>Contact Me</b></a></button>
    </section>

    <section id="about" class="about">
        <h2><b>About Me</b></h2>
        <p>I’m Ashish, an aspiring lawyer passionate about justice and advocating for clients’ rights. Currently studying law at [University Name], I specialize in [specific areas of law]. My focus is on developing strong legal research, writing, and advocacy skills. I’m committed to using the law to create positive change and help those in need. I look forward to a career where I can make a meaningful impact in the legal field.

            ...</p>
        <img src="ashish.jpg" alt="Your Photo" />
    </section>

    <!-- Projects Section -->
    <section id="projects" class="projects">
        <h2>My Projects</h2>
        <div class="project">
            <h3><b><u>Tic Tac Toe</u></b></h3>
            <p>Tic Tac Toe is a simple two-player game where players take turns marking spaces on a 3x3 grid with either an "X" or an "O." The goal is to be the first to align three of their marks horizontally, vertically, or diagonally....</p>
            <a href="https://gaikwadrutuja1.github.io/Tic-Tac-Toe/" target="_blank"><i>click to Take a look of Interesting Game</i></a>
        </div>
        <div class="project">
            <h3><b><u>Simple Meme generator</u></b></h3>
            <p>A meme generator is a tool that allows users to create custom memes by adding text to popular images or templates. It provides an easy and fun way to create and share humorous or relatable content...</p>
            <a href="https://gaikwadrutuja1.github.io/meme/" target="_blank"><i>Click to Laugh by seeing meme</i></a>
        </div>
        <!-- Add more projects here -->
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Me</h2>
        <form action="rutujagaikwad062003@gmail.com" method="post" enctype="text/plain">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
       
    </section>
    

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Your Name. All Rights Reserved.</p>
    </footer>

    <script>
    // Smooth scrolling when clicking on navigation links
document.querySelectorAll('nav ul li a').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
        });
    });
});

    </script>
</body>
</html>
