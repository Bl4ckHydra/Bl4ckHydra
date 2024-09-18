<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Black Hydra - Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@700&family=Roboto+Mono:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Orbitron', sans-serif;
            background-color: #0d0d0d;
            background-image: radial-gradient(circle at top left, #2e2e2e, #0d0d0d);
            color: #f5f5f5;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
        }

        .container {
            max-width: 800px;
            background: #1a1a1a;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 0 25px rgba(0, 255, 106, 0.8), 0 0 50px rgba(0, 255, 106, 0.5);
            text-align: center;
        }

        h1 {
            font-size: 60px;
            color: #00ff6a;
            text-shadow: 0 0 20px rgba(0, 255, 106, 1), 0 0 40px rgba(0, 255, 106, 0.8);
            letter-spacing: 3px;
            animation: glow 1.5s ease-in-out infinite alternate;
        }

        @keyframes glow {
            from {
                text-shadow: 0 0 10px #00ff6a, 0 0 20px #00ff6a, 0 0 30px #00ff6a;
            }
            to {
                text-shadow: 0 0 20px #00ff6a, 0 0 40px #00ff6a, 0 0 60px #00ff6a;
            }
        }

        p {
            font-family: 'Roboto Mono', monospace;
            font-size: 18px;
            line-height: 1.8;
            margin-bottom: 20px;
            text-align: justify;
            background-color: rgba(255, 255, 255, 0.05);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 255, 106, 0.1);
        }

        .highlight {
            color: #00ff6a;
            font-weight: bold;
            text-shadow: 0 0 5px rgba(0, 255, 106, 0.7);
        }

        .skills {
            margin-top: 30px;
        }

        .skills h3 {
            font-size: 28px;
            color: #00ff6a;
            text-transform: uppercase;
            margin-bottom: 20px;
            text-shadow: 0 0 10px rgba(0, 255, 106, 1);
        }

        .skills span {
            background: rgba(0, 255, 106, 0.3);
            color: #0d0d0d;
            padding: 10px 15px;
            margin: 5px;
            display: inline-block;
            border-radius: 5px;
            font-weight: bold;
            font-size: 14px;
            transition: all 0.3s ease;
            box-shadow: 0 0 15px rgba(0, 255, 106, 0.4);
        }

        .skills span:hover {
            background-color: #00ff6a;
            color: #0d0d0d;
            box-shadow: 0 0 20px rgba(0, 255, 106, 0.8);
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Black Hydra</h1>
        <p>Hello! I'm <span class="highlight">Amir</span>, also known as <span class="highlight">Black Hydra</span>. From a young age, I have been passionate about electronics, starting to work with electronic components at the age of 5. I have been working professionally in this field for several years, engaging in projects such as reverse engineering, designing industrial and electronic boards, and creating hacking and security gadgets.</p>

        <p>My expertise spans across languages like <span class="highlight">C, C++, MicroPython, Arduino, Ducky Script</span>, and <span class="highlight">Pine Script</span>. I am also deeply interested in fields such as <span class="highlight">Robotics, IT, IoT</span>, and <span class="highlight">AI</span> (currently focusing on machine learning). I am continually learning and evolving in these areas to stay on the cutting edge.</p>

        <p>Additionally, I specialize in <span class="highlight">PCB design</span> and hardware and software repairs for mobile devices, laptops, and other gadgets. I am also focused on <span class="highlight">security and networking</span>, and currently pursuing courses like <span class="highlight">CS50</span>. I am always seeking new challenges and projects, hoping to inspire others through my work!</p>

        <div class="skills">
            <h3>Skills</h3>
            <span>C</span>
            <span>C++</span>
            <span>MicroPython</span>
            <span>Arduino</span>
            <span>Ducky Script</span>
            <span>Pine Script</span>
            <span>Robotics</span>
            <span>IT</span>
            <span>IoT</span>
            <span>AI</span>
            <span>PCB Design</span>
            <span>Security</span>
            <span>Networking</span>
        </div>
    </div>
</body>
</html>
