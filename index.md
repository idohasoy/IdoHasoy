---
layout: default
title: "Welcome to My Portfolio"
---

<style>
    .site-title {
    display: none !important;
    visibility: hidden;
    height: 0;
}



    body {
        font-family: 'Inter', sans-serif;
        background-color: #0f172a;
        margin: 0;
        padding: 0;
        color: #e0e0e0;
    }
    .container {
        width: 90%;
        max-width: 1200px;
        margin: auto;
        padding: 40px 20px;
        text-align: center;
    }
    h1, h2 {
        color: #38bdf8;
    }
    .section {
        background: #1e293b;
        padding: 30px;
        margin: 30px 0;
        border-radius: 12px;
        box-shadow: 0 4px 10px rgba(255, 255, 255, 0.1);
        color: #e0e0e0;
        text-align: center;
    }
    .btn {
        display: inline-block;
        padding: 12px 25px;
        color: #ffffff;
        background-color: #38bdf8;
        text-decoration: none;
        border-radius: 6px;
        margin: 15px;
        font-weight: bold;
        font-size: 1.2em;
        transition: background 0.3s ease-in-out, transform 0.2s ease;
    }
    .btn:hover {
        background-color: #0ea5e9;
        transform: scale(1.05);
    }
    .navbar {
        background: #1e293b;
        padding: 15px;
        text-align: center;
        position: fixed;
        width: 100%;
        top: 0;
        left: 0;
        box-shadow: 0 2px 10px rgba(255, 255, 255, 0.1);
    }
    .navbar a {
        color: #38bdf8;
        text-decoration: none;
        margin: 0 20px;
        font-size: 1.2em;
        font-weight: bold;
        cursor: pointer;
    }
    .hero {
        padding: 100px 20px;
        text-align: center;
        background: linear-gradient(135deg, #1e40af, #38bdf8);
        border-radius: 12px;
    }
    .sidebar {
        position: fixed;
        top: 50px;
        left: 0;
        width: 220px;
        height: 100%;
        background: #1e293b;
        padding: 20px;
        box-shadow: 2px 0 10px rgba(255, 255, 255, 0.1);
    }
    .sidebar a {
        display: block;
        color: #38bdf8;
        text-decoration: none;
        padding: 10px 0;
        font-size: 1.1em;
        transition: color 0.3s ease-in-out;
        cursor: pointer;
    }
    .sidebar a:hover {
        color: #e0e0e0;
    }
    .content {
        margin-left: 240px;
        padding: 20px;
    }
    .project {
        background: #1e293b;
        padding: 20px;
        border-radius: 8px;
        margin: 15px 0;
        box-shadow: 0 2px 8px rgba(255, 255, 255, 0.1);
    }
    .project a {
        color: #ffffff;
        text-decoration: none;
        font-weight: bold;
    }
    .project a:hover {
        color: #0ea5e9;
    }
</style>

<div class="sidebar">
    <a href="#home">Home</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
</div>

<div class="content">
    <div id="home" class="hero">
        <h1>Welcome to My Portfolio</h1>
        <p>Hi, I'm <strong>Ido Hasoy</strong>, an Industrial Engineering and Management student specializing in <strong>Data Analytics and Product Development</strong>. Passionate about optimizing processes, developing data-driven solutions, and leveraging intelligent systems for business improvement.</p>
    </div>
    
    <div class="section">
        <h2>👨‍💼 About Me</h2>
        <p>Currently pursuing a degree in Industrial Engineering and Management at Ben-Gurion University, I have a strong foundation in data analytics, machine learning, and business strategy. With hands-on experience in SQL, Power BI, and Python, I enjoy solving complex problems and creating impactful solutions. My background as a combat officer has honed my leadership and decision-making skills, enabling me to thrive in high-pressure environments.</p>
    </div>
    
    <div id="projects" class="section">
        <h2>📂 Projects</h2>
        
        <h3>Intelligent Systems</h3>
        <div class="project">
            <h3>Decision Tree Classifier with Data Preprocessing</h3>
            <p>A Python-based decision tree classifier that includes custom data preprocessing, entropy-based feature selection, and chi-squared pruning.</p>
            <a class="btn" href="decision_tree_project.zip" download>Download Project</a>
        </div>
        <div class="project">
            <h3>Word Transformation Search Algorithms</h3>
            <p>A project implementing multiple search algorithms to find optimal word transformations.</p>
            <a class="btn" href="project2.zip" download>Download Project</a>
        </div>
        
        <h3>SQL and Power BI</h3>
        <div class="project">
            <h3>Company Performance & Operations Report</h3>
            <p>A Power BI-based analytics project with SQL data processing.</p>
            <a class="btn" href="Part3.sql" download>Download SQL Script</a>
            <a class="btn" href="Part3-Company-Performance.pbix" download>Download Company Performance Report</a>
            <a class="btn" href="Part3-Operation-Report.pbix" download>Download Operations Report</a>
        </div>
    </div>
    
    <div id="contact" class="section">
        <h2>📞 Contact Me</h2>
        <p>💎 <strong>Email:</strong> <a href="mailto:ido.hasoy10@gmail.com">ido.hasoy10@gmail.com</a></p>
        <p>🌟 <strong>LinkedIn:</strong> <a href="https://linkedin.com/in/ido-hasoy" target="_blank">linkedin.com/in/ido-hasoy</a></p>
    </div>
</div>
