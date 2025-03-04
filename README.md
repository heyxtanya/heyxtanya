<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tanya Zhao - GitHub Profile</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(120deg, #f6f8fa, #e9ecef);
            color: #24292e;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }
        
        .header {
            text-align: center;
            margin-bottom: 20px;
            animation: fadeIn 1.5s ease;
        }
        
        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            animation: slideInDown 1s ease-out;
        }
        
        .wave-emoji {
            display: inline-block;
            animation: wave 2.5s infinite;
            transform-origin: 70% 70%;
        }
        
        .bio {
            text-align: center;
            background: white;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
            animation: fadeInUp 1s ease-out;
        }
        
        .section {
            background: white;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            margin-bottom: 30px;
            animation: fadeInUp 1.2s ease-out;
        }
        
        .section-title {
            text-align: center;
            font-size: 1.5rem;
            margin-bottom: 20px;
            position: relative;
        }
        
        .section-title:after {
            content: '';
            width: 70px;
            height: 3px;
            background: linear-gradient(90deg, #0077B5, #2ecc71);
            position: absolute;
            bottom: -5px;
            left: 50%;
            transform: translateX(-50%);
            animation: expandWidth 2s ease-out;
        }
        
        .connect {
            display: flex;
            justify-content: center;
            gap: 15px;
            flex-wrap: wrap;
        }
        
        .connect a {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border-radius: 5px;
            overflow: hidden;
            display: block;
        }
        
        .connect a:hover {
            transform: translateY(-5px) scale(1.05);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }
        
        .skills {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
        }
        
        .skill-icon {
            width: 50px;
            height: 50px;
            margin: 5px;
            transition: all 0.3s ease;
            animation: fadeIn 1.5s ease, float 3s ease-in-out infinite;
            animation-delay: calc(0.1s * var(--i));
        }
        
        .skill-icon:hover {
            transform: translateY(-10px) scale(1.2);
        }
        
        .footer {
            text-align: center;
            padding: 20px;
            animation: fadeIn 2s ease;
        }
        
        .footer .star {
            display: inline-block;
            animation: pulse 2s infinite;
        }
        
        @keyframes wave {
            0% { transform: rotate(0deg); }
            10% { transform: rotate(14deg); }
            20% { transform: rotate(-8deg); }
            30% { transform: rotate(14deg); }
            40% { transform: rotate(-4deg); }
            50% { transform: rotate(10deg); }
            60% { transform: rotate(0deg); }
            100% { transform: rotate(0deg); }
        }
        
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        @keyframes slideInDown {
            from {
                opacity: 0;
                transform: translateY(-30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        @keyframes expandWidth {
            from { width: 0; }
            to { width: 70px; }
        }
        
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }
        
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
        
        /* Typing animation */
        .typing-container {
            display: flex;
            justify-content: center;
            margin: 20px 0;
        }
        
        .typing-text {
            border-right: 3px solid;
            width: 0;
            white-space: nowrap;
            overflow: hidden;
            animation: typing 4s steps(40) infinite, blink 0.5s step-end infinite alternate;
        }
        
        @keyframes typing {
            0% { width: 0 }
            50% { width: 100% }
            70% { width: 100% }
            100% { width: 0 }
        }
        
        @keyframes blink {
            50% { border-color: transparent }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Hi, I'm Tanya Zhao! <span class="wave-emoji">👋</span></h1>
        </div>
        
        <div class="typing-container">
            <div class="typing-text">Backend Developer | Cloud Computing Enthusiast | CS Student</div>
        </div>
        
        <div class="bio">
            <p>🎓 Master's Student in Computer Science at <strong>Northeastern University</strong></p>
            <p>💼 Actively seeking <strong>2025 Software Engineering Co-op or Internship</strong> opportunities</p>
            <p>🌍 Passionate about Backend Development, Distributed Systems & Cloud Computing</p>
        </div>
        
        <div class="section">
            <h2 class="section-title">📫 Connect with Me</h2>
            <div class="connect">
                <a href="https://linkedin.com/in/yourprofile" target="_blank">
                    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
                </a>
                <a href="https://www.instagram.com/your_instagram" target="_blank">
                    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">
                </a>
            </div>
        </div>
        
        <div class="section">
            <h2 class="section-title">🛠 Languages & Tools</h2>
            <div class="skills">
                <img class="skill-icon" style="--i:1" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg">
                <img class="skill-icon" style="--i:2" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg">
                <img class="skill-icon" style="--i:3" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg">
                <img class="skill-icon" style="--i:4" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg">
                <img class="skill-icon" style="--i:5" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg">
                <img class="skill-icon" style="--i:6" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg">
                <img class="skill-icon" style="--i:7" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg">
                <img class="skill-icon" style="--i:8" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kotlin/kotlin-original.svg">
                <img class="skill-icon" style="--i:9" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/go/go-original.svg">
                <img class="skill-icon" style="--i:10" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/scala/scala-original.svg">
                <img class="skill-icon" style="--i:11" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matlab/matlab-original.svg">
                <img class="skill-icon" style="--i:12" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg">
                <img class="skill-icon" style="--i:13" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg">
                <img class="skill-icon" style="--i:14" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg">
                <img class="skill-icon" style="--i:15" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg">
                <img class="skill-icon" style="--i:16" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg">
                <img class="skill-icon" style="--i:17" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg">
                <img class="skill-icon" style="--i:18" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg">
                <img class="skill-icon" style="--i:19" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg">
                <img class="skill-icon" style="--i:20" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain.svg">
                <img class="skill-icon" style="--i:21" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg">
                <img class="skill-icon" style="--i:22" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg">
                <img class="skill-icon" style="--i:23" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg">
                <img class="skill-icon" style="--i:24" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg">
                <img class="skill-icon" style="--i:25" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg">
                <img class="skill-icon" style="--i:26" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg">
            </div>
        </div>
        
        <div class="footer">
            <p><span class="star">⭐</span> Thanks for visiting my GitHub profile! Feel free to connect! 😊</p>
        </div>
    </div>
</body>
</html>
