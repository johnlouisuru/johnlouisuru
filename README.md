<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PHP Developer Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: #fff;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }

        .container {
            max-width: 900px;
            width: 100%;
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            padding: 60px 40px;
            box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
            border: 1px solid rgba(255, 255, 255, 0.18);
        }

        h1 {
            font-size: 3em;
            margin-bottom: 10px;
            font-weight: 700;
        }

        .tagline {
            font-size: 1.3em;
            margin-bottom: 40px;
            opacity: 0.9;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 40px;
        }

        .skill-card {
            background: rgba(255, 255, 255, 0.15);
            padding: 25px;
            border-radius: 15px;
            transition: transform 0.3s ease, background 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        .skill-card:hover {
            transform: translateY(-5px);
            background: rgba(255, 255, 255, 0.25);
        }

        .skill-title {
            font-size: 1.1em;
            font-weight: 600;
            margin-bottom: 8px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .skill-years {
            font-size: 0.85em;
            opacity: 0.8;
            background: rgba(255, 255, 255, 0.2);
            padding: 4px 12px;
            border-radius: 20px;
            display: inline-block;
        }

        .highlight {
            background: rgba(255, 255, 255, 0.2);
            padding: 30px;
            border-radius: 15px;
            margin-top: 30px;
            border-left: 4px solid #fff;
        }

        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 15px;
        }

        .tech-tag {
            background: rgba(255, 255, 255, 0.25);
            padding: 8px 16px;
            border-radius: 20px;
            font-size: 0.9em;
            border: 1px solid rgba(255, 255, 255, 0.3);
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2em;
            }
            
            .tagline {
                font-size: 1.1em;
            }
            
            .container {
                padding: 40px 25px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>👋 Full-Stack PHP Developer</h1>
        <p class="tagline">Building robust web applications with 7+ years of core PHP expertise</p>

        <div class="highlight">
            <strong>💡 Specialization:</strong> Core/Vanilla PHP development with modern JavaScript, RESTful APIs, and automated deployment pipelines
        </div>

        <div class="skills-grid">
            <div class="skill-card">
                <div class="skill-title">
                    🔧 Core Stack
                    <span class="skill-years">7 years</span>
                </div>
                <div class="tech-stack">
                    <span class="tech-tag">PHP</span>
                    <span class="tech-tag">MySQL</span>
                    <span class="tech-tag">JavaScript</span>
                    <span class="tech-tag">Ajax</span>
                    <span class="tech-tag">jQuery</span>
                    <span class="tech-tag">Async/Await</span>
                    <span class="tech-tag">Fetch API</span>
                </div>
            </div>

            <div class="skill-card">
                <div class="skill-title">
                    🚀 DevOps & Deployment
                </div>
                <div class="tech-stack">
                    <span class="tech-tag">Git/GitHub <small>3yr</small></span>
                    <span class="tech-tag">GitHub Actions <small>2yr</small></span>
                    <span class="tech-tag">Docker <small>2yr</small></span>
                    <span class="tech-tag">CI/CD</span>
                </div>
            </div>

            <div class="skill-card">
                <div class="skill-title">
                    ☁️ Cloud & Infrastructure
                </div>
                <div class="tech-stack">
                    <span class="tech-tag">cPanel <small>5yr</small></span>
                    <span class="tech-tag">AWS EC2 <small>1yr</small></span>
                    <span class="tech-tag">AWS S3 <small>1yr</small></span>
                </div>
            </div>

            <div class="skill-card">
                <div class="skill-title">
                    🛠️ Frameworks & Tools
                </div>
                <div class="tech-stack">
                    <span class="tech-tag">Laravel <small>1yr</small></span>
                    <span class="tech-tag">RESTful APIs</span>
                    <span class="tech-tag">N8N <small>1yr</small></span>
                    <span class="tech-tag">Make <small>1yr</small></span>
                </div>
            </div>

            <div class="skill-card">
                <div class="skill-title">
                    🔒 Security & Best Practices
                </div>
                <div class="tech-stack">
                    <span class="tech-tag">Secure Coding</span>
                    <span class="tech-tag">SQL Injection Prevention</span>
                    <span class="tech-tag">XSS Protection</span>
                    <span class="tech-tag">Authentication</span>
                </div>
            </div>

            <div class="skill-card">
                <div class="skill-title">
                    ⚡ Automation
                </div>
                <div class="tech-stack">
                    <span class="tech-tag">Workflow Automation</span>
                    <span class="tech-tag">N8N Workflows</span>
                    <span class="tech-tag">Make Scenarios</span>
                    <span class="tech-tag">API Integration</span>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
