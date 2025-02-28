---
layout: default
title: "Welcome to My Portfolio"
---

<style>
    body {
        font-family: 'Poppins', sans-serif;
        background-color: #121212;
        margin: 0;
        padding: 0;
        color: #E0E0E0;
    }
    .container {
        width: 90%;
        max-width: 1200px;
        margin: auto;
        padding: 40px 20px;
        text-align: center;
    }
    h1, h2 {
        color: #BB86FC;
    }
    .section {
        background: #1E1E1E;
        padding: 30px;
        margin: 30px 0;
        border-radius: 12px;
        box-shadow: 0 4px 10px rgba(255, 255, 255, 0.1);
        color: #E0E0E0;
        text-align: center;
    }
    .btn {
        display: inline-block;
        padding: 12px 25px;
        color: #121212;
        background-color: #BB86FC;
        text-decoration: none;
        border-radius: 6px;
        margin: 15px;
        font-weight: bold;
        font-size: 1.2em;
        transition: background 0.3s ease-in-out, transform 0.2s ease;
    }
    .btn:hover {
        background-color: #985EFF;
        transform: scale(1.05);
    }
    .navbar {
        background: #1E1E1E;
        padding: 15px;
        text-align: center;
        position: fixed;
        width: 100%;
        top: 0;
        left: 0;
        box-shadow: 0 2px 10px rgba(255, 255, 255, 0.1);
    }
    .navbar a {
        color: #BB86FC;
        text-decoration: none;
        margin: 0 20px;
        font-size: 1.2em;
        font-weight: bold;
    }
    .hero {
        padding: 100px 20px;
        text-align: center;
        background: linear-gradient(135deg, #3700B3, #BB86FC);
        border-radius: 12px;
    }
    .sidebar {
        position: fixed;
        top: 50px;
        left: 0;
        width: 220px;
        height: 100%;
        background: #1E1E1E;
        padding: 20px;
        box-shadow: 2px 0 10px rgba(255, 255, 255, 0.1);
    }
    .sidebar a {
        display: block;
        color: #BB86FC;
        text-decoration: none;
        padding: 10px 0;
        font-size: 1.1em;
    }
    .content {
        margin-left: 240px;
        padding: 20px;
    }
</style>

<div class="sidebar">
    <a href="index.html">Home</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>

<div class="content">
    <div class="hero">
        <h1>Welcome to My Portfolio</h1>
        <p>Hi, I'm <strong>Ido Hasoy</strong>, an Industrial Engineering and Management student specializing in <strong>Data Analytics and Product Development</strong>. Passionate about optimizing processes, developing data-driven solutions, and leveraging intelligent systems for business improvement.</p>
    </div>
    
    <div class="section">
        <h2>👨‍💼 About Me</h2>
        <p>Currently pursuing a degree in Industrial Engineering and Management at Ben-Gurion University, I have a strong foundation in data analytics, machine learning, and business strategy. With hands-on experience in SQL, Power BI, and Python, I enjoy solving complex problems and creating impactful solutions. My background as a combat officer has honed my leadership and decision-making skills, enabling me to thrive in high-pressure environments.</p>
    </div>
    
    <div class="section">
        <h2>📂 Projects</h2>
        <p>Explore my key projects involving data analytics, machine learning, and software development.</p>
        <a class="btn" href="projects.html">View My Projects</a>
    </div>
    
    <div class="section">
        <h2>🔗 Connect</h2>
        <p>Let's connect and collaborate!</p>
        <a class="btn" href="https://linkedin.com/in/ido-hasoy" target="_blank">LinkedIn</a>
        <a class="btn" href="https://github.com/IdoHasoy" target="_blank">GitHub</a>
        <a class="btn" href="mailto:ido.hasoy10@gmail.com">Email Me</a>
    </div>
</div>
