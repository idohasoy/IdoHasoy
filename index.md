/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body Layout */
body {
    font-family: 'Inter', sans-serif;
    background-color: #0f172a;
    color: #e0e0e0;
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

/* Header and Sidebar Container (Row Layout) */
.header-container {
    display: flex;
    width: 100%;
    align-items: center;
    background: linear-gradient(135deg, #1e40af, #38bdf8);
    padding: 20px;
}

/* Sidebar - Fixed on Left */
.sidebar {
    width: 220px;
    background: #1e293b;
    padding: 20px;
    height: 100vh; /* Full height */
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    position: fixed;
    left: 0;
    top: 0;
}

/* Sidebar Links */
.sidebar a {
    display: block;
    color: #38bdf8;
    text-decoration: none;
    padding: 12px 0;
    font-size: 1.1em;
    transition: color 0.3s ease-in-out;
}

.sidebar a:hover {
    color: #e0e0e0;
}

/* Title Section - Next to Sidebar */
.site-title {
    flex-grow: 1;
    text-align: center;
    padding: 40px 20px;
    color: white;
}

.site-title h1 {
    font-size: 2.5em;
    font-weight: 700;
    margin-bottom: 5px;
}

.site-title h2 {
    font-size: 1.2em;
    font-weight: 400;
    opacity: 0.9;
}

/* Content Layout */
.content {
    margin-left: 240px; /* Adjust to match sidebar width */
    padding: 40px;
}

/* Sections */
.section {
    background: #1e293b;
    padding: 30px;
    margin: 30px 0;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(255, 255, 255, 0.1);
    text-align: center;
}

/* Hero Section */
.hero {
    padding: 100px 20px;
    text-align: center;
    background: linear-gradient(135deg, #1e40af, #38bdf8);
    border-radius: 12px;
}

/* Buttons */
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

/* Projects */
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

/* Adjust Content Spacing */
h1, h2 {
    color: #38bdf8;
}

/* Responsive Adjustments */
@media (max-width: 1024px) {
    .header-container {
        flex-direction: column;
        align-items: center;
    }

    .sidebar {
        width: 100%;
        height: auto;
        position: relative;
        text-align: center;
        padding: 10px 0;
    }

    .sidebar a {
        display: inline-block;
        margin: 10px;
    }

    .site-title {
        text-align: center;
        padding: 20px;
    }

    .content {
        margin-left: 0;
        padding: 20px;
    }
}
