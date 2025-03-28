<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amen-Abrham Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@300;400;700&family=Open+Sans:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-brown: #5D4037;
            --light-brown: #A1887F;
            --dark-brown: #3E2723;
            --cream: #EFEBE9;
            --text-color: #212121;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Open Sans', sans-serif;
            line-height: 1.6;
            background-color: var(--cream);
            color: var(--text-color);
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }

        .container {
            background-color: white;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            border-radius: 10px;
            padding: 40px;
        }

        header {
            background-color: var(--primary-brown);
            color: var(--cream);
            text-align: center;
            padding: 30px;
            border-radius: 10px 10px 0 0;
        }

        .name {
            font-family: 'Merriweather', serif;
            font-size: 3em;
            font-weight: 700;
            margin-bottom: 10px;
            letter-spacing: -1px;
        }

        h2 {
            font-family: 'Merriweather', serif;
            color: var(--primary-brown);
            border-bottom: 3px solid var(--light-brown);
            padding-bottom: 10px;
            margin: 30px 0 20px;
            font-weight: 700;
        }

        h3 {
            color: var(--dark-brown);
            margin-bottom: 10px;
        }

        .section {
            margin-bottom: 30px;
        }

        .skills-container {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
        }

        .skills-section {
            background-color: var(--cream);
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        ul {
            list-style-type: none;
        }

        li {
            padding: 5px 0;
            position: relative;
            padding-left: 20px;
        }

        li::before {
            content: '•';
            color: var(--primary-brown);
            position: absolute;
            left: 0;
            font-weight: bold;
        }

        .experience-section {
            background-color: var(--cream);
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: var(--primary-brown);
            color: var(--cream);
            border-radius: 0 0 10px 10px;
        }

        @media (max-width: 768px) {
            .skills-container {
                grid-template-columns: 1fr;
            }
            .container {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="name">Amen-Abrham Portfolio</div>
        </header>

        <section class="section">
            <h2>Summary of Qualifications</h2>
            <p>Experienced professional with over 2 years in customer service and administrative support. Skilled in delivering high-quality service and enhancing operational efficiency. Proficient in Agile and Scrum methodologies with tools like Trello, effective in managing office tasks and scheduling. Strong computer literacy, data analysis skills with Excel and IBM Cognos Analytics, and foundational knowledge of Java. Adept at cleaning and transforming data, resolving conflicts, and collaborating efficiently, ensuring smooth operations and data integrity.</p>
        </section>

        <section class="section">
            <h2>Education & Certifications</h2>
            <div class="experience-section">
                <ul>
                    <li>York University, BA Information Technology (Honours)</li>
                    <li>George Brown, Foundation of Administration</li>
                    <li>AAU, BS Engineering (Partial completion)</li>
                    <li>Microsoft Azure AI Fundamentals Professional Certificate</li>
                    <li>IBM Data Analyst Professional Certificate</li>
                    <li>Java Computer Programming Skills Certificate</li>
                </ul>
            </div>
        </section>

        <section class="section">
            <h2>Skills</h2>
            <div class="skills-container">
                <div class="skills-section">
                    <h3>Technical Skills</h3>
                    <ul>
                        <li>Operating Systems: Windows 10, ChromeOS, iOS & Android</li>
                        <li>Applications & Tools: Google Workspace, RDBMS, IBM Cognos Analytics, Jupyter, SQLite, Azure Sandbox, MS Office, Zoom</li>
                        <li>Project Management Fundamentals: Agile, Waterfall, Scrum, Kanban, Trello</li>
                        <li>Programming Languages: SQL, Python, Java</li>
                    </ul>
                </div>
                <div class="skills-section">
                    <h3>Professional Skills</h3>
                    <ul>
                        <li>Time management and multitasking</li>
                        <li>Event Management</li>
                        <li>Problem solving</li>
                        <li>Communication</li>
                        <li>Leadership and good judgment</li>
                        <li>Proficient in English and Amharic</li>
                        <li>Critical thinking, team player, attention to detail, organizational skills, results-oriented</li>
                    </ul>
                </div>
            </div>
        </section>

        <section class="section">
            <h2>Professional Experience</h2>
            <div class="experience-section">
                <h3>Customer Service Representative | City of Brampton</h3>
                <p>Nov 2024 - Present</p>
                <ul>
                    <li>Delivered outstanding front-line customer service, engaging customers and providing program information</li>
                    <li>Professionally handled calls and processed room, court, and arena rentals. As well as program registration</li>
                    <li>Balanced daily revenue, completed administrative tasks, and supported the Facility Clerk</li>
                    <li>Filled out accident and incident reports, maintained a tidy workspace, and sent and received mail</li>
                </ul>
            </div>
        </section>

        <footer>
            <p>© 2025 Amen Abrham. All Rights Reserved.</p>
        </footer>
    </div>
</body>
</html>
