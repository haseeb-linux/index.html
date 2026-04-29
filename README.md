<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Muhammad Haseeb | IT Student Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Segoe UI', Arial, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 40px 20px;
        }
        .container {
            max-width: 1000px;
            margin: auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.2);
            overflow: hidden;
        }
        .header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 40px;
            text-align: center;
        }
        .header h1 {
            font-size: 42px;
            margin-bottom: 10px;
        }
        .badge {
            display: inline-block;
            background: rgba(255,255,255,0.2);
            padding: 8px 16px;
            border-radius: 30px;
            font-size: 14px;
            margin-top: 15px;
        }
        .content {
            padding: 40px;
        }
        h2 {
            color: #667eea;
            border-bottom: 3px solid #667eea;
            padding-bottom: 10px;
            margin-bottom: 20px;
            margin-top: 10px;
        }
        h3 {
            color: #333;
            margin: 15px 0 10px 0;
        }
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 15px 0;
        }
        .skill-tag {
            background: #667eea;
            color: white;
            padding: 6px 14px;
            border-radius: 20px;
            font-size: 13px;
        }
        .skill-tag-light {
            background: #e0e0e0;
            color: #333;
            padding: 6px 14px;
            border-radius: 20px;
            font-size: 13px;
        }
        .project-box {
            background: #f8f9fa;
            padding: 15px;
            border-radius: 10px;
            margin: 15px 0;
            border-left: 4px solid #667eea;
        }
        .info-grid {
            display: grid;
            grid-template-columns: auto 1fr;
            gap: 12px;
            margin: 20px 0;
        }
        .info-label {
            font-weight: bold;
            color: #667eea;
        }
        hr {
            margin: 25px 0;
            border: none;
            height: 1px;
            background: #e0e0e0;
        }
        .footer {
            background: #2d3748;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 14px;
        }
        .footer a {
            color: #a0aec0;
            text-decoration: none;
        }
        .footer a:hover {
            color: white;
        }
        @media (max-width: 600px) {
            .header h1 { font-size: 28px; }
            .content { padding: 20px; }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Muhammad Haseeb</h1>
            <p>🎓 IT Student | Networking Enthusiast | Linux Learner</p>
            <div class="badge">GitHub Education Student</div>
        </div>

        <div class="content">
            <!-- About Section -->
            <h2>📌 About Me</h2>
            <p>I am an <strong>IT student</strong> at the <strong>Virtual University of Pakistan</strong> with a passion for <strong>Linux, networking, and system administration</strong>. Currently, I am expanding my skills in <strong>Kali Linux, ethical hacking concepts, and web technologies</strong>.</p>

            <div class="info-grid">
                <span class="info-label">🎓 Program:</span>
                <span>BS Information Technology</span>
                <span class="info-label">📍 University:</span>
                <span>Virtual University of Pakistan</span>
                <span class="info-label">📧 Email:</span>
                <span>haseebarif112234@gmail.com</span>
                <span class="info-label">🐙 GitHub:</span>
                <span><a href="https://github.com/haseeb-linux" target="_blank">github.com/haseeb-linux</a></span>
            </div>

            <!-- Tech Skills -->
            <h2>💻 Technical Skills</h2>
            <div class="skills">
                <span class="skill-tag">🐧 Linux (Kali)</span>
                <span class="skill-tag">🌐 Networking Basics</span>
                <span class="skill-tag">⚙️ C++ Programming</span>
                <span class="skill-tag">🐍 Python (Learning)</span>
                <span class="skill-tag">📄 HTML/CSS</span>
                <span class="skill-tag">🛠️ Git & GitHub</span>
                <span class="skill-tag">💻 VS Code</span>
                <span class="skill-tag">⚡ VirtualBox</span>
            </div>

            <!-- Currently Learning -->
            <h2>🚀 Currently Learning</h2>
            <div class="skills">
                <span class="skill-tag-light">Kali Linux (Hands-on)</span>
                <span class="skill-tag-light">Networking (CCNA path)</span>
                <span class="skill-tag-light">C++ (Data Structures)</span>
                <span class="skill-tag-light">Web Development</span>
            </div>

            <!-- Portfolio Projects -->
            <h2>🖥️ Portfolio Highlights</h2>
            <div class="project-box">
                <strong>🌐 GitHub Portfolio</strong>
                <p>This very website is my first GitHub Pages project. It showcases my journey as an IT student.</p>
            </div>
            <div class="project-box">
                <strong>🐧 Linux Learning Journal</strong>
                <p>Documenting my Kali Linux commands, tools, and ethical hacking practice in a GitHub repository.</p>
            </div>
            <div class="project-box">
                <strong>📡 Networking Basics</strong>
                <p>Hands-on practice with Cisco Packet Tracer and understanding network models, IP addressing, and protocols.</p>
            </div>

            <!-- Goals -->
            <h2>🎯 My Goals</h2>
            <ul style="margin-left: 20px; line-height: 1.8;">
                <li>✅ Master Linux system administration</li>
                <li>✅ Complete CCNA certification</li>
                <li>✅ Build real-world networking projects</li>
                <li>✅ Contribute to open-source on GitHub</li>
            </ul>

            <hr>

            <p style="text-align: center; color: #666;">
                <em>"Currently sharpening my skills — IT student, Linux lover, and future network engineer."</em>
            </p>
        </div>

        <div class="footer">
            <p>Muhammad Haseeb | IT Student | Virtual University of Pakistan</p>
            <p>📧 haseebarif112234@gmail.com | 🐙 <a href="https://github.com/haseeb-linux" target="_blank">github.com/haseeb-linux</a></p>
            <p style="margin-top: 10px; font-size: 12px;">✨ Built with GitHub Pages ✨</p>
        </div>
    </div>
</body>
</html>
