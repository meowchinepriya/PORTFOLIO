# PORTFOLIO
All about my projects and work experience
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Priya Ojha - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            display: flex;
            background-color: #f4f4f9;
            font-family: Arial, sans-serif;
            color: #333;
            margin: 0;
        }
        .sidebar {
            width: 250px;
            background-color: #000;
            color: white;
            height: 100vh;
            padding: 20px;
            position: fixed;
        }
        .sidebar a {
            display: block;
            color: white;
            padding: 10px;
            text-decoration: none;
        }
        .sidebar a:hover {
            background-color: #444;
        }
        .content {
            margin-left: 270px;
            padding: 20px;
            flex-grow: 1;
        }
        header {
            text-align: center;
            background-color: grey;
            color: white;
            padding: 20px;
            border-radius: 10px;
        }
        section {
            background-color: white;
            padding: 20px;
            margin: 20px auto;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            max-width: 800px;
        }
    </style>
</head>
<body>
    <div class="sidebar">
        <h2>Navigation</h2>
        <a href="#education">Education</a>
        <a href="#skills">Technical Skills</a>
        <a href="#experience">Work Experience</a>
        <a href="#projects">Projects</a>
        <a href="#achievements">Achievements</a>
        <a href="#leadership">Leadership</a>
        <a href="#soft-skills">Soft Skills</a>
        <a href="#coursework">Course Work</a>
        <a href="#query">Query</a>
        <a href="#feedback">Feedback</a>
        <a href="#collaboration">Collaboration</a>
    </div>
    
    <div class="content">
        <header>
            <h1>Priya Ojha</h1>
            <p>
                <a href="#">LinkedIn</a> | 
                <a href="#">Twitter</a> | 
                <a href="#">Email</a> | 
                <a href="#">GitHub</a> | 
                9899069027
            </p>
        </header>
        
        <section id="query">
            <h2>Have a Query?</h2>
            <form>
                <label for="query-text">Enter your query:</label>
                <textarea id="query-text" rows="4" cols="50"></textarea>
                <br>
                <button type="submit">Submit</button>
            </form>
        </section>
        
        <section id="feedback">
            <h2>Feedback</h2>
            <form>
                <label for="feedback-text">Share your feedback:</label>
                <textarea id="feedback-text" rows="4" cols="50"></textarea>
                <br>
                <button type="submit">Submit</button>
            </form>
        </section>
        
        <section id="collaboration">
            <h2>Collaborate With Me</h2>
            <p>Want to contribute to my projects and gain credits? Fill out the form below:</p>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name">
                <br>
                <label for="email">Email:</label>
                <input type="email" id="email">
                <br>
                <label for="skills">Your Skills:</label>
                <input type="text" id="skills">
                <br>
                <button type="submit">Join</button>
            </form>
        </section>
    </div>
</body>
</html>

