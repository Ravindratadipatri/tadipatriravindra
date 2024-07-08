<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ravindra Reddy - Engineer Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #1e3a5f; /* Blue background */
            color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: gold;
            padding: 1em 0;
            text-align: center;
            font-weight: bold;
        }

        nav ul {
            list-style: none;
            padding: 0;
            text-align: center;
            background-color: #444;
        }

        nav ul li {
            display: inline;
            margin: 0 1em;
        }

        nav ul li a {
            color: gold;
            text-decoration: none;
            font-weight: bold;
        }

        main {
            padding: 2em;
        }

        section {
            margin-bottom: 2em;
        }

        h2 {
            color: gold;
            font-weight: bold;
        }

        .project, .about, .contact, .skills, .education, .certifications, .activities, .accomplishments, .hobbies, .languages {
            background-color: white;
            color: #333;
            border: 1px solid #ccc;
            border-radius: 5px;
            padding: 1em;
            margin-bottom: 1em;
            font-weight: bold;
        }

        .project img, .about img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 0 auto 1em;
        }

        footer {
            background-color: #333;
            color: gold;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            width: 100%;
            bottom: 0;
            font-weight: bold;
        }

        label {
            display: block;
            margin: 0.5em 0 0.2em;
        }

        input, textarea {
            width: 100%;
            padding: 0.5em;
            margin-bottom: 1em;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        button {
            background-color: gold;
            color: #333;
            border: none;
            padding: 0.5em 1em;
            border-radius: 5px;
            font-weight: bold;
            cursor: pointer;
        }

        button:hover {
            background-color: #daa520;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ravindra Reddy</h1>
        <p>Engineer | Innovator | Problem Solver</p>
    </header>
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#certifications">Certifications</a></li>
            <li><a href="#activities">Activities</a></li>
            <li><a href="#accomplishments">Accomplishments</a></li>
            <li><a href="#hobbies">Hobbies</a></li>
            <li><a href="#languages">Languages</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <main>
        <section id="about" class="about">
            <h2>About Me</h2>
            <img src="_d2dccfd0-22c8-4f43-8716-dcedd6c57148.jpeg" alt="Ravindra Reddy">
            <p>Welcome! I'm Ravindra Reddy, a dedicated engineer with a passion for innovation and problem-solving. With a background in Computer Science and Information Technology, I specialize in developing robust solutions for complex challenges.</p>
        </section>
        <section id="projects">
            <h2>Projects</h2>
            <div class="project" id="project-template" style="display:none;">
                <img src="https://via.placeholder.com/300x200.png?text=Project+Image" alt="Project Image">
                <h3 class="project-title"></h3>
                <p class="project-description"></p>
            </div>
        </section>
        <section id="skills" class="skills">
            <h2>Skills</h2>
            <ul>
                <li>Python Programmer</li>
                <li>Graphic Designing</li>
                <li>Beginner Photoshop</li>
                <li>Video Editing</li>
                <li>Writing stories</li>
            </ul>
        </section>
        <section id="education" class="education">
            <h2>Education</h2>
            <p><strong>Marri Laxman Reddy Institute of Technology</strong><br>3rd Year in Computer Science and Information Technology Department<br>CGPA: 7.00 | 2025</p>
            <p><strong>Narayana Junior College, Nellore</strong><br>Intermediate (High School Equivalent)<br>GPA: 8.5 | 2019 - 2021</p>
            <p><strong>Sri Sai Vijetha High School, Tadipatri</strong><br>High School (SSC Equivalent)<br>GPA: 9.5 | 2019</p>
        </section>
        <section id="certifications" class="certifications">
            <h2>Certifications</h2>
            <ul>
                <li>C certificate from Hacker Rank</li>
                <li>C Essentials from Cisco</li>
                <li>Python Essentials from Cisco</li>
                <li>Data Management from TCS ion</li>
            </ul>
        </section>
        <section id="activities" class="activities">
            <h2>Activities and Honors</h2>
            <p>Volunteer at various NGO events, including Seva Bharathi and Run for a Girl Child</p>
            <p>Participated in various events organized by NGOs, contributing to community initiatives and social causes.</p>
            <p><strong>Leadership Experience:</strong><br>Organized and led numerous events as a member of College Club 64, fostering teamwork and collaboration among members.</p>
            <p><strong>Content Creation:</strong><br>Created engaging and informative content on ongoing issues and creating awareness on YouTube, building a subscriber base and engaging with viewers to promote discussion and learning.</p>
        </section>
        <section id="accomplishments" class="accomplishments">
            <h2>Accomplishments</h2>
            <p>Best Startup Idea Award at Illuminate 2023 Event, conducted by E-Cell IIT Bombay</p>
            <p>Winner of E-Fest conducted by college management, where participants learn how to sell a product</p>
        </section>
        <section id="hobbies" class="hobbies">
            <h2>Hobbies and Interests</h2>
            <ul>
                <li>Reading Books</li>
                <li>Listening to music</li>
                <li>Writing stories</li>
                <li>Editing</li>
            </ul>
        </section>
        <section id="languages" class="languages">
            <h2>Languages</h2>
            <ul>
                <li>Telugu</li>
                <li>English</li>
            </ul>
        </section>
        <section id="contact" class="contact">
            <h2>Contact</h2>
            <p>Email: ravindraoptional@gmail.com</p>
            <p>Phone: +91 7997555414</p>
            <p>Location: Hyderabad, Chandhanagar - 500050</p>
            <form id="contact-form">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit">Send</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Ravindra Reddy. All rights reserved.</p>
    </footer>
    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const projects = [
                { title: "Project 1", description: "Description of project 1.", imageUrl: "https://via.placeholder.com/300x200.png?text=Project+1" },
                { title: "Project 2", description: "Description of project 2.", imageUrl: "https://via.placeholder.com/300x200.png?text=Project+2" },
                { title: "Project 3", description: "Description of project 3.", imageUrl: "https://via.placeholder.com/300x200.png?text=Project+3" }
                // Add more projects as needed
            ];

            const projectContainer = document.getElementById('projects');

            projects.forEach(project => {
                const projectTemplate = document.getElementById('project-template').cloneNode(true);
                projectTemplate.style.display = 'block';
                projectTemplate.querySelector('.project-title').textContent = project.title;
                projectTemplate.querySelector('.project-description').textContent = project.description;
                projectTemplate.querySelector('img').src = project.imageUrl;
                projectContainer.appendChild(projectTemplate);
            });
        });
    </script>
</body>
</html>
****
