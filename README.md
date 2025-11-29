<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Note Nexus - Flutter Note Taking App</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 40px 20px;
            color: #333;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        
        .header {
            background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
            padding: 50px 40px;
            text-align: center;
            color: white;
        }
        
        .app-icon {
            font-size: 4rem;
            margin-bottom: 20px;
        }
        
        h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            font-weight: 700;
        }
        
        .tagline {
            font-size: 1.4rem;
            opacity: 0.9;
            font-weight: 300;
        }
        
        .content {
            padding: 50px 40px;
        }
        
        .section {
            margin-bottom: 40px;
        }
        
        h2 {
            color: #4facfe;
            font-size: 1.8rem;
            margin-bottom: 20px;
            border-left: 5px solid #4facfe;
            padding-left: 15px;
        }
        
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin: 30px 0;
        }
        
        .feature-card {
            background: #f8f9fa;
            padding: 25px;
            border-radius: 15px;
            text-align: center;
            transition: transform 0.3s ease;
            border: 1px solid #e9ecef;
        }
        
        .feature-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
        }
        
        .feature-icon {
            font-size: 2.5rem;
            color: #4facfe;
            margin-bottom: 15px;
        }
        
        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin: 20px 0;
        }
        
        .tech-tag {
            background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
            color: white;
            padding: 10px 20px;
            border-radius: 25px;
            font-weight: 600;
            font-size: 0.9rem;
        }
        
        .footer {
            background: #f8f9fa;
            padding: 30px 40px;
            text-align: center;
            border-top: 1px solid #e9ecef;
        }
        
        .button {
            display: inline-block;
            background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
            color: white;
            padding: 15px 30px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: 600;
            margin: 10px;
            transition: transform 0.3s ease;
        }
        
        .button:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
        }
        
        @media (max-width: 768px) {
            h1 { font-size: 2.2rem; }
            .tagline { font-size: 1.1rem; }
            .content { padding: 30px 20px; }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <div class="app-icon">📝</div>
            <h1>Note Nexus</h1>
            <p class="tagline">Simple & Powerful Note-Taking App</p>
        </div>
        
        <div class="content">
            <div class="section">
                <h2>About The Project</h2>
                <p>A lightweight and efficient Flutter note-taking application that allows users to seamlessly create, view, and delete personal notes. Built with a focus on simplicity and reliability, ensuring your notes are always accessible even offline.</p>
            </div>
            
            <div class="section">
                <h2>✨ Features</h2>
                <div class="features-grid">
                    <div class="feature-card">
                        <div class="feature-icon">✏️</div>
                        <h3>Create Notes</h3>
                        <p>Easily write and save your thoughts</p>
                    </div>
                    <div class="feature-card">
                        <div class="feature-icon">👀</div>
                        <h3>View Notes</h3>
                        <p>Quickly access all your saved notes</p>
                    </div>
                    <div class="feature-card">
                        <div class="feature-icon">🗑️</div>
                        <h3>Delete Notes</h3>
                        <p>Remove notes you no longer need</p>
                    </div>
                    <div class="feature-card">
                        <div class="feature-icon">📱</div>
                        <h3>Offline Storage</h3>
                        <p>Works completely offline</p>
                    </div>
                </div>
            </div>
            
            <div class="section">
                <h2>🛠️ Tech Stack</h2>
                <div class="tech-stack">
                    <span class="tech-tag">Flutter</span>
                    <span class="tech-tag">Dart</span>
                    <span class="tech-tag">SQFLite</span>
                    <span class="tech-tag">MVC Architecture</span>
                    <span class="tech-tag">Local Storage</span>
                </div>
            </div>
            
            <div class="section">
                <h2>🎯 Project Goals</h2>
                <p>This project was developed to master local data persistence in Flutter using SQFLite and implement clean architecture patterns with MVC for maintainable and scalable code.</p>
            </div>
        </div>
        
        <div class="footer">
            <a href="#" class="button">View Source Code</a>
            <a href="#" class="button" style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);">Download APK</a>
        </div>
    </div>
</body>
</html>