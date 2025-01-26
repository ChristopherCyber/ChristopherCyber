<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cybersecurity Portfolio</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/js/all.min.js"></script>
    <style>
        :root {
            --primary: #1a1a1a;
            --secondary: #2d2d2d;
            --accent: #00ff00;
            --text: #ffffff;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text);
            background: var(--primary);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header */
        header {
            background: var(--secondary);
            padding: 2rem 0;
            margin-bottom: 2rem;
        }

        .header-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .profile {
            display: flex;
            align-items: center;
            gap: 2rem;
        }

        .profile img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 3px solid var(--accent);
        }

        /* Navigation */
        nav {
            background: var(--secondary);
            padding: 1rem 0;
            margin-bottom: 2rem;
        }

        nav ul {
            display: flex;
            justify-content: center;
            gap: 2rem;
            list-style: none;
        }

        nav a {
            color: var(--text);
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }

        nav a:hover {
            color: var(--accent);
        }

        /* Sections */
        section {
            margin-bottom: 3rem;
            padding: 2rem;
            background: var(--secondary);
            border-radius: 8px;
        }

        h1, h2, h3 {
            color: var(--accent);
            margin-bottom: 1rem;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1rem;
        }

        .skill-card {
            background: var(--primary);
            padding: 1rem;
            border-radius: 4px;
        }

        .cert-progress {
            background: var(--primary);
            padding: 1rem;
            border-radius: 4px;
            margin-bottom: 1rem;
        }

        .cert-progress .progress {
            width: 100%;
            background: #444;
            height: 20px;
            border-radius: 10px;
            overflow: hidden;
            margin-top: 0.5rem;
        }

        .cert-progress .progress-bar {
            height: 100%;
            background: var(--accent);
            width: 60%;
        }

        .project {
            background: var(--primary);
            padding: 1rem;
            border-radius: 4px;
            margin-bottom: 1rem;
        }

        .project h3 {
            color: var(--accent);
        }

        footer {
            text-align: center;
            padding: 2rem 0;
            background: var(--secondary);
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin-top: 1rem;
        }

        .social-links a {
            color: var(--text);
            font-size: 1.5rem;
            transition: color 0.3s;
        }

        .social-links a:hover {
            color: var(--accent);
        }
    </style>
</head>
<body>
    <header>
        <div class="container header-content">
            <div class="profile">
                <img src="/api/placeholder/150/150" alt="Profile Picture">
                <div>
                    <h1>Cybersecurity Analyst</h1>
                    <p>ServiceNow Solution Consultant | Computer Science Graduate</p>
                </div>
            </div>
        </div>
    </header>

    <nav>
        <div class="container">
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#certifications">Certifications</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <main class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>Computer Science graduate from University of Wollongong (2023) with a major in Cybersecurity. Currently working as a ServiceNow Solution Consultant with 2 years of experience in implementing secure enterprise solutions. Passionate about cybersecurity, threat detection, and incident response.</p>
        </section>

        <section id="skills">
            <h2>Technical Skills</h2>
            <div class="skills-grid">
                <div class="skill-card">
                    <h3>Security Tools</h3>
                    <ul>
                        <li>Wireshark</li>
                        <li>Nmap</li>
                        <li>Metasploit</li>
                        <li>Burp Suite</li>
                    </ul>
                </div>
                <div class="skill-card">
                    <h3>Technologies</h3>
                    <ul>
                        <li>ServiceNow</li>
                        <li>SIEM Tools</li>
                        <li>Firewall Configuration</li>
                        <li>IDS/IPS Systems</li>
                    </ul>
                </div>
                <div class="skill-card">
                    <h3>Core Competencies</h3>
                    <ul>
                        <li>Threat Analysis</li>
                        <li>Incident Response</li>
                        <li>Risk Assessment</li>
                        <li>Security Auditing</li>
                    </ul>
                </div>
            </div>
        </section>

        <section id="certifications">
            <h2>Certifications In Progress</h2>
            <div class="cert-progress">
                <h3>CompTIA Security+</h3>
                <div class="progress">
                    <div class="progress-bar"></div>
                </div>
            </div>
            <div class="cert-progress">
                <h3>Google Cybersecurity Professional Certificate</h3>
                <div class="progress">
                    <div class="progress-bar"></div>
                </div>
            </div>
            <div class="cert-progress">
                <h3>CompTIA Network+</h3>
                <div class="progress">
                    <div class="progress-bar"></div>
                </div>
            </div>
        </section>

        <section id="projects">
            <h2>Security Projects</h2>
            <div class="project">
                <h3>Network Security Assessment Tool</h3>
                <p>Developed a Python-based tool for automated network vulnerability scanning and reporting.</p>
                <p>Technologies: Python, Nmap, SQLite, Docker</p>
            </div>
            <div class="project">
                <h3>ServiceNow Security Operations Implementation</h3>
                <p>Led the implementation of ServiceNow SecOps module for a Fortune 500 client, streamlining incident response processes.</p>
                <p>Technologies: ServiceNow, ITIL, REST APIs</p>
            </div>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Feel free to reach out for cybersecurity consultations or opportunities.</p>
            <div class="social-links">
                <a href="#"><i class="fab fa-github"></i></a>
                <a href="#"><i class="fab fa-linkedin"></i></a>
                <a href="#"><i class="fas fa-envelope"></i></a>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>© 2024 Cybersecurity Portfolio. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
