<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Profile</title>
    <link href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: #121212;
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
            text-align: center;
        }

        .container {
            max-width: 900px;
            width: 100%;
            animation: fadeIn 2s ease-in-out;
        }

        h1, h2, h3 {
            margin-bottom: 20px;
        }

        a {
            color: #61dafb;
            text-decoration: none;
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }

        .skill {
            font-size: 50px;
            animation: pop 1s ease-in-out;
        }

        .projects, .contact {
            margin-top: 40px;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes pop {
            0% { transform: scale(0.8); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🖥️ Welcome to My Modern GitHub Profile</h1>

        <h2>I am Sameer Sheikh Mansoori</h2>
        <a href="https://git.io/typing-svg">
            <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1&center=true&vCenter=true&random=true&width=435&lines=full+stack+developer;problem+solver;freelancer" alt="Typing SVG">
        </a>
        <p>A passionate software developer keen on web development and software technologies. Always striving to improve my skills and work on innovative projects. Welcome to my coding world!</p>

        <h2>💻 Technologies I Use</h2>
        <div class="skills">
            <i class="devicon-react-original skill"></i>
            <i class="devicon-typescript-original skill"></i>
            <i class="devicon-nextjs-original skill"></i>
            <i class="devicon-nodejs-plain skill"></i>
            <i class="devicon-express-original skill"></i>
            <i class="devicon-python-plain skill"></i>
        </div>

        <div class="projects">
            <h2>🖼️ Live Projects & Screenshots</h2>
            <ul>
                <li><a href="https://live-dating-application.onrender.com/" target="_blank">Live Dating Application</a></li>
                <li><a href="https://ekak-innovation-2.vercel.app/" target="_blank">Ekak Innovation</a></li>
                <li><a href="https://tubular-bavarois-a8c7fc.netlify.app/login" target="_blank">Login Portal</a></li>
            </ul>
            <img src="https://media.giphy.com/media/xT0xeJpnrWC4XWblEk/giphy.gif" alt="Project Demo">
        </div>

        <div class="contact">
            <h2>📫 Contact Me</h2>
            <p><strong>Email:</strong> sameersheikhmansoori@gmail.com</p>
            <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/sameer-sheikh-mansoori" target="_blank">LinkedIn Profile</a></p>
            <p><strong>Portfolio:</strong> <a href="https://showoffsameer.netlify.app/" target="_blank">Live Projects Showcase</a></p>
        </div>

        <h2>📈 My GitHub Stats</h2>
        <img src="https://raw.githubusercontent.com/7oSkaaa/7oSkaaa/main/Images/Statistics.gif" alt="Statistics">
        <img src="https://github-readme-stats.vercel.app/api?username=sameer1sheikh2mansoori3&show_icons=true&theme=radical" alt="GitHub Stats">

        <p>Thanks for visiting! Looking forward to collaborating on amazing projects. 🚀</p>
    </div>
</body>
</html>
