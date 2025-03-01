---
layout: custom
title: "Welcome to My Portfolio"
---

<link rel="stylesheet" href="style.css">

<div class="header-container">
    <!-- Sidebar Navigation -->
    <div class="sidebar">
        <a href="#home">Home</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </div>

    <!-- Title Section Next to Sidebar -->
    <header class="site-title">
        <h1>Ido Hasoy</h1>
        <h2>Industrial Engineering | Data Analytics | Product Development</h2>
    </header>
</div>

<!-- Main Content -->
<div class="content">
    <div id="home" class="hero">
        <h2>👨‍💼 About Me</h2>
        <p>
            Industrial Engineering and Management student at <strong>Ben-Gurion University</strong>, specializing in <strong>intelligent systems</strong>. 
            Passionate about <strong>data analytics, product development, and process optimization</strong>.
        </p>
        <p>
            Skilled in <strong>SQL, Power BI, and Python</strong>, with proven leadership experience as a former <strong>combat officer</strong>. 
        </p>
        <p>
            Seeking opportunities in <strong>data analysis or product management</strong> to leverage my skills and make an impact.
        </p>
    </div>
     /* About Me Section */
        .hero {
            padding: 100px 20px;
            text-align: left; /* Align text to the left */
            background: linear-gradient(135deg, #1e40af, #38bdf8);
            border-radius: 12px;
            max-width: 800px; /* Adjust width for better readability */
            margin: auto; /* Center the box while keeping text left-aligned */
        }
        
        .hero p {
            text-align: left; /* Ensure all paragraphs are aligned left */
            margin-bottom: 10px;
            font-size: 1.1em;
        }
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
