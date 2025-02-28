---
layout: default
title: "Welcome to My Portfolio"
---

<style>
    body {
        font-family: 'Poppins', sans-serif;
        background-color: #2D1B69;
        margin: 0;
        padding: 0;
        color: white;
    }
    .container {
        width: 90%;
        max-width: 1200px;
        margin: auto;
        padding: 40px 20px;
        text-align: center;
    }
    h1 {
        color: #FFFFFF;
        font-size: 3em;
        font-weight: bold;
    }
    .section {
        background: white;
        padding: 30px;
        margin: 30px 0;
        border-radius: 12px;
        box-shadow: 0 4px 10px rgba(255, 255, 255, 0.2);
        color: #2D1B69;
        text-align: center;
    }
    .btn {
        display: inline-block;
        padding: 12px 25px;
        color: white;
        background-color: #8A2BE2;
        text-decoration: none;
        border-radius: 6px;
        margin: 15px;
        font-weight: bold;
        font-size: 1.2em;
        transition: background 0.3s ease-in-out, transform 0.2s ease;
    }
    .btn:hover {
        background-color: #6A0DAD;
        transform: scale(1.05);
    }
    .navbar {
        background: rgba(255, 255, 255, 0.1);
        padding: 15px;
        text-align: center;
    }
    .navbar a {
        color: white;
        text-decoration: none;
        margin: 0 20px;
        font-size: 1.2em;
        font-weight: bold;
    }
    .hero {
        padding: 80px 20px;
        text-align: center;
        background: linear-gradient(135deg, #8A2BE2, #4B0082);
        border-radius: 12px;
    }
</style>

<div class="container">
    <div class="navbar">
        <a href="index.html">Home</a>
        <a href="projects.html">Projects</a>
        <a href="contact.html">Contact</a>
    </div>

    <div class="hero">
        <h1>Welcome to My Portfolio</h1>
        <p>Hi, I'm <strong>Ido Hasoy</strong>, an Industrial Engineering and Management student specializing in <strong>Data Analytics and Product Development</strong>. Passionate about optimizing processes, developing data-driven solutions, and leveraging intelligent systems for business improvement.</p>
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
