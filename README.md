<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diyar Kheari Hussain - Professional CV</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #f4f7fa, #e0e7f0);
            color: #333;
            line-height: 1.6;
        }

        /* Navigation Bar */
        nav {
            position: sticky;
            top: 0;
            background: linear-gradient(135deg, #0077b6, #00b4d8);
            padding: 10px 20px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            z-index: 1000;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 1.1em;
            padding: 5px 10px;
            border-radius: 5px;
            transition: background-color 0.3s ease, transform 0.3s ease;
        }

        nav ul li a:hover {
            background-color: rgba(255, 255, 255, 0.2);
            transform: translateY(-2px);
        }

        /* Container */
        .container {
            max-width: 900px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            animation: fadeIn 1s ease-in-out;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(-20px);
            }

            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Header */
        header {
            text-align: center;
            margin-bottom: 30px;
            animation: slideIn 1s ease-in-out;
        }

        @keyframes slideIn {
            from {
                opacity: 0;
                transform: translateX(-100%);
            }

            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
            color: #0077b6;
            background: linear-gradient(135deg, #0077b6, #00b4d8);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: colorChange 3s infinite alternate;
        }

        @keyframes colorChange {
            0% {
                background-position: 0% 50%;
            }

            100% {
                background-position: 100% 50%;
            }
        }

        header p {
            font-size: 1.2em;
            margin-top: 5px;
            color: #666;
        }

        .contact-info {
            font-size: 1.1em;
            color: #0077b6;
        }

        .contact-info a {
            text-decoration: none;
            color: #0077b6;
            transition: color 0.3s ease;
        }

        .contact-info a:hover {
            color: #00b4d8;
        }

        /* Sections */
        .section {
            margin-bottom: 30px;
            padding: 20px;
            background: linear-gradient(135deg, #f0f4f8, #e0e7f0);
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            animation: fadeInSection 1s ease-in-out;
        }

        @keyframes fadeInSection {
            from {
                opacity: 0;
                transform: translateY(20px);
            }

            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .section h2 {
            font-size: 1.6em;
            color: #0077b6;
            border-bottom: 2px solid #0077b6;
            padding-bottom: 5px;
            margin-bottom: 15px;
            transition: all 0.3s ease;
        }

        .section h2:hover {
            color: #00b4d8;
            border-bottom-color: #00b4d8;
        }

        .section p,
        .section ul {
            font-size: 1.1em;
            line-height: 1.6;
            margin-bottom: 10px;
        }

        .section ul {
            list-style-type: none;
            padding-left: 0;
        }

        .section ul li {
            margin-bottom: 10px;
            padding-left: 20px;
            position: relative;
            transition: transform 0.3s ease;
        }

        .section ul li::before {
            content: '•';
            color: #0077b6;
            position: absolute;
            left: 0;
            font-size: 1.2em;
        }

        .section ul li:hover {
            transform: translateX(10px);
        }

        /* Footer */
        footer {
            text-align: center;
            font-size: 1.1em;
            margin-top: 30px;
            color: #666;
            animation: fadeIn 1s ease-in-out;
        }

        /* Button Styles */
        .btn {
            display: inline-block;
            padding: 10px 20px;
            font-size: 1em;
            color: white;
            background: linear-gradient(135deg, #0077b6, #00b4d8);
            border-radius: 5px;
            text-decoration: none;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>

<body>

    <!-- Navigation Bar -->
    <nav>
        <ul>
            <li><a href="#career-objective">Career Objective</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <div class="container">
        <header>
            <h1>Diyar Kheari Hussain</h1>
            <p class="contact-info">
                <strong>Phone:</strong> 07507341907 |
                <strong>Email:</strong> <a href="mailto:fvv@gmail.com">fvv@gmail.com</a> |
                <strong>Location:</strong> Duhok, Iraq
            </p>
        </header>

        <!-- Career Objective -->
        <div id="career-objective" class="section">
            <h2>Career Objective</h2>
            <p>Aspiring entrepreneur and computer science student with a passion for innovation and problem-solving. My
                goal is to build a successful tech-based business and lead as a CEO, creating impactful solutions that
                address real-world challenges.</p>
        </div>

        <!-- Education -->
        <div id="education" class="section">
            <h2>Education</h2>
            <p><strong>Bachelor’s in Computer Science</strong><br>
                University of Duhok (Currently a student)<br>
                <em>Relevant Courses:</em> Web Development, Data Structures, Algorithms, Software Engineering
            </p>
        </div>

        <!-- Key Skills -->
        <div id="skills" class="section">
            <h2>Key Skills</h2>
            <ul>
                <li><strong>Front-end Development:</strong> HTML, CSS, JavaScript, React</li>
                <li><strong>Soft Skills:</strong> Fast Typing, Problem-Solving, Team Collaboration</li>
                <li><strong>Languages:</strong> Fluent in Arabic, Kurdish, and German</li>
            </ul>
        </div>

        <!-- Projects -->
        <div id="projects" class="section">
            <h2>Projects</h2>
            <ul>
                <li><strong>Personal Portfolio Website:</strong> Designed and developed a responsive portfolio website
                    using HTML, CSS, and JavaScript.</li>
                <li><strong>React To-Do List App:</strong> Built a dynamic to-do list application using React to manage
                    tasks efficiently.</li>
            </ul>
        </div>

        <!-- Footer -->
        <footer id="contact">
            <p>© 2025 Diyar Kheari Hussain | All rights reserved</p>
            <a href="#" class="btn">Download CV</a>
        </footer>
    </div>

</body>

</html>
