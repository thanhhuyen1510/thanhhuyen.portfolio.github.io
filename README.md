<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Thanh Huyen | Business Analyst Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background-color: #f4f6f9;
            color: #333;
            line-height: 1.6;
        }

        header {
            background: #1f2937;
            color: white;
            padding: 40px 20px;
            text-align: center;
        }

        header h1 {
            font-size: 40px;
            font-weight: 600;
        }

        header p {
            font-size: 18px;
            margin-top: 10px;
            opacity: 0.8;
        }

        nav {
            background: #111827;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: 500;
        }

        nav a:hover {
            color: #60a5fa;
        }

        section {
            padding: 60px 10%;
        }

        h2 {
            margin-bottom: 20px;
            color: #1f2937;
        }

        .card {
            background: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.05);
        }

        .skills span {
            display: inline-block;
            background: #e0e7ff;
            padding: 8px 15px;
            border-radius: 20px;
            margin: 5px 5px 5px 0;
            font-size: 14px;
        }

        footer {
            background: #1f2937;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }

        .btn {
            display: inline-block;
            padding: 10px 20px;
            background: #2563eb;
            color: white;
            text-decoration: none;
            border-radius: 6px;
            margin-top: 10px;
        }

        .btn:hover {
            background: #1d4ed8;
        }
    </style>
</head>
<body>

<header>
    <h1>Vũ Thị Thanh Huyền</h1>
    <p>Aspiring Business Analyst | Data Enthusiast | External Economics Student</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About Me</h2>
    <div class="card">
        <p>
            I am a motivated Business Analyst student with strong analytical thinking,
            problem-solving skills, and attention to detail. 
            Passionate about data analysis, financial modeling, and digital transformation.
        </p>
    </div>
</section>

<section id="skills">
    <h2>Skills</h2>
    <div class="card skills">
        <span>SQL</span>
        <span>Excel</span>
        <span>Power BI</span>
        <span>Python (Basic)</span>
        <span>Data Analysis</span>
        <span>Financial Analysis</span>
        <span>Business Process Modeling</span>
    </div>
</section>

<section id="projects">
    <h2>Projects</h2>

    <div class="card">
        <h3>Metaverse Banking Research</h3>
        <p>
            Conducted research on financial integration in virtual environments.
            Analyzed business models and user adoption trends.
        </p>
        <a href="#" class="btn">View Project</a>
    </div>

    <div class="card">
        <h3>Sales Data Analysis (SQL Project)</h3>
        <p>
            Used AdventureWorks dataset to analyze sales trends,
            customer segmentation, and revenue performance.
        </p>
        <a href="#" class="btn">View GitHub</a>
    </div>

</section>

<section id="contact">
    <h2>Contact</h2>
    <div class="card">
        <p>Email: your-email@example.com</p>
        <p>LinkedIn: linkedin.com/in/your-link</p>
        <p>GitHub: github.com/your-username</p>
    </div>
</section>

<footer>
    © 2026 Thanh Huyen | Business Analyst Portfolio
</footer>

</body>
</html>
