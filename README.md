<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Black Hydra - Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Rajdhani:wght@600&family=JetBrains+Mono:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            background: #0f0f0f;
            color: #ffffff;
            font-family: 'JetBrains Mono', monospace;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden;
        }
        .container {
            max-width: 800px;
            padding: 40px;
            background: linear-gradient(145deg, #1b1b1b, #2c2c2c);
            border-radius: 15px;
            box-shadow: 10px 10px 30px #0a0a0a, -10px -10px 30px #383838;
            text-align: center;
        }
        h1 {
            font-family: 'Rajdhani', sans-serif;
            font-size: 50px;
            color: #00ffb0;
            text-transform: uppercase;
            letter-spacing: 5px;
            margin-bottom: 20px;
            text-shadow: 0 0 10px #00ffb0;
        }
        p {
            font-size: 18px;
            line-height: 1.8;
            margin-bottom: 25px;
            text-align: justify;
            padding: 15px;
            background-color: rgba(255, 255, 255, 0.05);
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 255, 176, 0.2);
        }
        .highlight {
            color: #00ffb0;
            font-weight: bold;
        }
        .skills {
            margin-top: 30px;
        }
        .skills h3 {
            font-size: 24px;
            color: #00ffb0;
            text-transform: uppercase;
            letter-spacing: 3px;
            margin-bottom: 15px;
        }
        .skills span {
            display: inline-block;
            margin: 5px;
            padding: 10px 20px;
            background-color: #00ffb0;
            color: #0f0f0f;
            font-weight: bold;
            border-radius: 5px;
            text-shadow: none;
            transition: 0.3s ease;
            box-shadow: 0 0 15px rgba(0, 255, 176, 0.5);
        }
        .skills span:hover {
            background-color: #00d4a0;
            transform: translateY(-5px);
            box-shadow: 0 0 25px rgba(0, 255, 176, 0.7);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Black Hydra</h1>
        <p>
            Hello! I'm <span class="highlight">Amir</span>, also known as <span class="highlight">Black Hydra</span>. Since childhood, I have been passionate about electronics, starting with electronic components when I was just 5 years old. For several years now, I've been professionally involved in this field, working on various projects like reverse engineering, designing industrial and electronic boards, and creating hacking and security gadgets.
        </p>
        <p>
            My expertise includes working with programming languages such as <span class="highlight">C, C++, MicroPython, Arduino, Ducky Script</span>, and <span class="highlight">Pine Script</span>. I have a strong interest in fields like <span class="highlight">Robotics, IT, IoT</span>, and <span class="highlight">AI</span>, and I am continuously learning and evolving, especially in machine learning.
        </p>
        <p>
            Additionally, I specialize in <span class="highlight">PCB design</span> and hardware/software repairs for mobile devices, laptops, and other gadgets. I'm also focused on <span class="highlight">security and networking</span>, currently studying courses like <span class="highlight">CS50</span>. I'm always looking for new challenges and projects, hoping to inspire others through my work.
        </p>
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
