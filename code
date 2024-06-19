<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
            background: linear-gradient(to right, #6a11cb, #2575fc);
            color: #333;
        }

        header {
            background: rgba(10, 10, 10, 0.7);
            color: rgb(240, 234, 234);
            padding: 20px 0;
            text-align: center;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        header nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }

        header nav ul li {
            margin: 0 15px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        header nav ul li a:hover {
            color: #ff6f61;
        }

        .menu-toggle {
            display: none;
        }

        section {
            padding: 100px 20px 40px;
            margin: 20px;
            border-bottom: 1px solid #ddd;
            background: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            text-align: center;
            color: #6a11cb;
        }

        #about img {
            display: block;
            max-width: 150px;
            margin: 20px auto;
            border-radius: 50%;
            border: 3px solid #6a11cb;
        }

        .project {
            background: linear-gradient(to right, #ff6f61, #ff9966);
            padding: 20px;
            border-radius: 10px;
            color: white;
            margin-bottom: 20px;
            transition: transform 0.3s, box-shadow 0.3s;
            display: flex;
            align-items: center;
        }

        .project img {
            max-width: 100px;
            margin-right: 20px;
            border-radius: 10px;
        }

        .project:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }

        footer {
            background-color: rgba(0, 0, 0, 0.7);
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        form {
            display: flex;
            flex-direction: column;
        }

        form label {
            margin: 10px 0 5px;
        }

        form input, form textarea, form button {
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1em;
        }

        form button {
            background: #6a11cb;
            color: white;
            border: none;
            cursor: pointer;
            transition: background 0.3s;
        }

        form button:hover {
            background: #2575fc;
        }

        /* Modal styles */
        .modal {
            display: none;
            position: fixed;
            z-index: 1001;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            overflow: auto;
            background-color: rgba(0, 0, 0, 0.5);
            padding-top: 60px;
        }

        .modal-content {
            background-color: white;
            margin: 5% auto;
            padding: 20px;
            border: 1px solid #888;
            width: 80%;
            max-width: 600px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .close {
            color: #aaa;
            float: right;
            font-size: 28px;
            font-weight: bold;
        }

        .close:hover,
        .close:focus {
            color: black;
            text-decoration: none;
            cursor: pointer;
        }

        @media (max-width: 768px) {
            header nav ul {
                flex-direction: column;
                display: none;
            }

            header nav ul.show {
                display: flex;
            }

            header nav ul li {
                margin: 10px 0;
            }

            .menu-toggle {
                display: block;
                cursor: pointer;
                color: white;
                font-size: 24px;
                position: absolute;
                right: 20px;
                top: 20px;
            }
        }

        @media (min-width: 769px) {
            .menu-toggle {
                display: none;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Keshav Upadhyay</h1>
        <div class="menu-toggle">☰ Menu</div>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <img src="https://via.placeholder.com/150" alt="Profile Picture">
        <p>Hello! Experienced Python and Django developer proficient in creating scalable web applications with a strong focus on efficiency and reliability..</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project" id="project1">
            <img src="https://via.placeholder.com/100" alt="Project One">
            <div>
                <h3>Project One</h3>
                <p>This is a description of my first project.</p>
            </div>
        </div>
        <div class="project" id="project2">
            <img src="https://via.placeholder.com/100" alt="Project Two">
            <div>
                <h3>Project Two</h3>
                <p>This is a description of my second project.</p>
            </div>
        </div>
        <!-- Add more projects as needed -->
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <form id="contactForm">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 My Portfolio</p>
    </footer>

    <!-- Project Modals -->
    <div id="modal1" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal1')">&times;</span>
            <h2>Project One Details</h2>
            <p>More information about Project One.</p>
        </div>
    </div>

    <div id="modal2" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('modal2')">&times;</span>
            <h2>Project Two Details</h2>
            <p>More information about Project Two.</p>
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const form = document.getElementById('contactForm');

            form.addEventListener('submit', (event) => {
                event.preventDefault();
                
                const name = document.getElementById('name').value;
                const email = document.getElementById('email').value;
                const message = document.getElementById('message').value;
                
                if (!name || !email || !message) {
                    alert('All fields are required.');
                    return;
                }

                alert(`Thank you, ${name}! Your message has been sent.`);
                
                // Reset the form
                form.reset();
            });

            // Project modal handling
            const project1 = document.getElementById('project1');
            const project2 = document.getElementById('project2');

            project1.addEventListener('click', () => {
                openModal('modal1');
            });

            project2.addEventListener('click', () => {
                openModal('modal2');
            });

            // Menu toggle for mobile
            const menuToggle = document.querySelector('.menu-toggle');
            const nav = document.querySelector('nav ul');

            menuToggle.addEventListener('click', () => {
                nav.classList.toggle('show');
            });
        });

        function openModal(modalId) {
            document.getElementById(modalId).style.display = 'block';
        }

        function closeModal(modalId) {
            document.getElementById(modalId).style.display = 'none';
        }

        window.onclick = function(event) {
            if (event.target.classList.contains('modal')) {
                event.target.style.display = 'none';
            }
        }
    </script>
</body>
</html>
