
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NotSavage - Portfolio</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            color: white;
            background-color: black;
            background-image: url('background.jpg'); /* Add your background image here */
            background-size: cover;
            background-repeat: no-repeat;
        }
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 20px;
            background-color: rgba(0, 0, 0, 0.8);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }
        .navbar .logo {
            font-size: 24px;
            font-weight: bold;
        }
        .navbar .tabs {
            display: flex;
            gap: 20px;
        }
        .navbar .tabs a {
            text-decoration: none;
            color: white;
            font-size: 18px;
        }
        .navbar .tabs a:hover {
            text-decoration: underline;
        }
        .section {
            padding: 100px 20px;
            min-height: 100vh;
            text-align: center;
        }
        .main-page {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .main-page h1 {
            font-size: 36px;
        }
        .experience ul {
            list-style-type: none;
            padding: 0;
            font-size: 20px;
            text-align: left;
            margin: auto;
            max-width: 800px;
        }
        .clients img {
            max-width: 300px;
            margin: 20px auto;
        }
    </style>
</head>
<body>
    <div class="navbar">
        <div class="logo">NotSavage</div>
        <div class="tabs">
            <a href="#main">Main Page</a>
            <a href="#experience">Experience</a>
            <a href="#socials">Socials</a>
            <a href="#clients">Clients</a>
        </div>
    </div>

    <div id="main" class="section main-page">
        <h1>Hi, I am NotSavage, a developer and experienced coder.</h1>
    </div>

    <div id="experience" class="section experience">
        <h2>Experience</h2>
        <ul>
            <li>Skilled video editor (can manage Server's YouTube channel if needed).</li>
            <li>Experienced in finding and fixing Minecraft server crashes/dupes, including lag machines.</li>
            <li>Plugin management (installing and working with the latest ones prevents dupes as previous ones might have more).</li>
            <li>Map creation (one of my favorite tasks).</li>
            <li>Experienced coder on my way to becoming a software engineer (can help with server codes, crates, themes, etc. when I fully become one or can try before if needed).</li>
        </ul>
    </div>

    <div id="socials" class="section">
        <h2>Socials</h2>
        <p>Links to social media platforms will go here.</p>
    </div>

    <div id="clients" class="section clients">
        <h2>Clients</h2>
        <a href="https://pika-network.net/" target="_blank">
            <img src="logo.png" alt="Pika Network Logo">
        </a>
    </div>
</body>
</html>
