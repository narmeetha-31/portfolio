<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Narmeetha Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #f8f8f8;
            color: #333;
            scroll-behavior: smooth;
        }
        header {
            background: url('header-image.jpg') no-repeat center center/cover;
            color: rgb(60, 46, 46);
            padding: 80px 0;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            background: rgba(0, 0, 0, 0.8);
        }
        nav ul li {
            margin: 10px 20px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            transition: 0.3s;
        }
        nav ul li a:hover {
            color: #ff6600;
        }
        section {
            padding: 50px;
            text-align: center;
            transition: all 0.5s ease-in-out;
        }
        #about, #skills, #portfolio, #education, #contact {
            margin-bottom: 20px;
            background: rgb(251, 236, 205);
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
        }
        #about img {
            width: 150px;
            border-radius: 50%;
            margin-bottom: 20px;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        a {
            color: #ff6600;
            text-decoration: none;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <header>
        <h1>Narmeetha P</h1>
        <h2>Software Developer</h2>
    </header>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#portfolio">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section id="about">
        <img src="profile.jpg" alt="Profile Picture">
        <p>Highly motivated and adaptable individual with a foundation in Python,
            HTML, and Java, complemented by proficiency in MS Office. Possesses
            a unique blend of technical aptitude and creative flair, demonstrated
            through hobbies in painting and clay art, and co-curricular involvement
            in dance and photography. Eager to contribute a diverse skill set and
            enthusiastic perspective to a dynamic team</p>
    </section>
    <section id="education">
        <h2>Education</h2>
        <p><strong>B.Sc. Computer Science</strong> -Sri Balaji Arts & Science College(2023-2026)</p>
        <p><strong>Higher Secondary</strong> - MBN Govt Girls HSS (2021-2023)</p>
    </section>
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Python</li>
            <li>Java</li>
            <li>MS Office</li>
            <li>HTML, CSS, JavaScript</li>
            <li>Analytical Thinking</li>
            <li>Problem Solving</li>
            <li>Teamwork</li>
        </ul>
    </section>
    <section id="portfolio">
        <h2>Projects</h2>
        <p>Check out my project:</p>
        <a href="https://sv-engineers.netlify.app/" target="_blank">SV Engineers Website</a>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>Phone:9092915814</p>
        <p>Email: <a href="mailto:narmeetha31@gmail.com">narmeetha31@gmail.com</a></p>
        <p>Location: Perungalathur, Chennai</p>
    </section>
    <script>
        document.querySelectorAll('nav ul li a').forEach(anchor => {
            anchor.addEventListener('click', function(event) {
                event.preventDefault();
                const section = document.querySelector(this.getAttribute('href'));
                section.scrollIntoView({ behavior: 'smooth' });
            });
        });
    </script>
</body>
</html>
# portfolio
