
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="icon" href="ConsoleLogo.png">
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <title>Yankee Majumder</title>
    <style>
        * {
            box-sizing: border-box;
            padding: 0;
            margin: 0;
        }
        
        body {
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            font-family: 'Roboto', sans-serif;
            color: #ffffff;
            scroll-behavior: smooth;
        }
        
        .navbar {
            padding: 10px 20px;
            background-color: rgba(0, 0, 0, 0.8);
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
        }
        
        .navbar .logo {
            font-size: 24px;
            font-weight: bold;
            color: #00d4ff;
            font-family: 'Orbitron', sans-serif;
        }
        
        .navbar .main-nav {
            list-style-type: none;
            display: flex;
        }
        
        .navbar .main-nav li {
            margin-left: 20px;
        }
        
        .navbar .main-nav a {
            text-decoration: none;
            color: #00d4ff;
            font-size: 18px;
            padding: 10px;
            transition: background-color 0.3s;
        }
        
        .navbar .main-nav a:hover {
            background-color: rgba(0, 212, 255, 0.2);
            border-radius: 5px;
        }
        
        .section {
            padding: 100px 20px;
            text-align: center;
        }
        
        .section h1 {
            font-size: 2.5em;
            color: #00d4ff;
            margin-bottom: 20px;
            font-family: 'Orbitron', sans-serif;
        }
        
        .section p {
            font-size: 1.2em;
            color: #ffffff;
            max-width: 800px;
            margin: 0 auto;
        }
        
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            text-align: left;
        }
        
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #00d4ff;
            border-radius: 5px;
            background-color: rgba(0, 0, 0, 0.8);
            color: #ffffff;
        }
        
        .contact-form button {
            padding: 10px 20px;
            background-color: #00d4ff;
            color: #000000;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        
        .contact-form button:hover {
            background-color: #00a3cc;
        }
    </style>
</head>
<body>
    <nav class="navbar">
        <div class="logo">Yankee Majumder</div>
        <ul class="main-nav">
            <li><a href="#home">Home</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#certification">Certification</a></li>
            <li><a href="#experience">Experience</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a href="#Resume" class="nav-links" style="background-color: rgb(177, 247, 214,0.5);"><i class="fa fa-download"></i>&nbsp;&nbsp; Resume</a></li>
        </ul>
    </nav>
    <div style="text-align:center">
        <div style="display:inline-block; padding-top: 100px; margin-right: 40px; margin-left: 40px;">
            <div class="image" style="display:inline-block;">
                <div class="subimage">
                    <img src="yankee.PNG" width="300px" style="margin-left: auto; margin-right: auto; display: block; margin-top:100px;">
                    <p style="text-align:center;padding-top:20px; font-size:0.95em;color:#001C55; padding-right: 70px; padding-left: 70px; max-width:500px">EXCLUSIVE</p>
                </div>
            </div>
        </div>
    </div>
    <div id="home" class="section">
        <h1>Welcome to My Portfolio</h1>
        <p>Hello everyone, I am a Senior System Engineer with over 6 years of experience in IT, currently working at Cognizant.
           Equipped with a deep understanding of IAM technology and privilege access management. Experienced Senior System Engineer with a track record of architecting and deploying EUC solutions, including VDI and application virtualization, Device Management. Proficient in troubleshooting complex EUC issues and skilled in technologies such as End user support, Active Directory, Nexthink, and Microsoft Endpoint Manager.</p><br>
    </div>
    <div id="contact" style="width:100%; text-align:center; padding-top:75px; margin-top:-30px; margin-bottom:0px; min-width:600px; color:#00d9ff;">
        <h1 style="font-size:2.3em; text-align: center;">Contact Me</h1><br>
        <p style="font-size:1.1em; margin-bottom:15px;">Feel free to send a message on LinkedIn...<br> or send me an email at majumderyankee8@gmail.com.</p>
        <div class="tooltip">
            <div style="z-index: 0; text-align:center; display: inline-block; position:relative; width: 50px; height: 50px; padding:10px; cursor: pointer; font-size: 50px; margin-right:10px;" onmouseover="shadow('giticon')" onmouseout="unshadow('giticon')" onclick="window.open('https://github.com/yankeeDamn','_blank')">
                <i id="giticon" class="fa fa-github" style="color:#88adb6; border-radius: 110px; width: 50px;"></i>
            </div>
            <span class="tooltiptext" style="margin-bottom:-15px;">GitHub</span>
        </div>
        <div class="tooltip">
            <div style="z-index: 0; text-align:center; display: inline-block; position:relative; width:50px; height: 50px; padding:10px; cursor: pointer; font-size: 50px; margin-right:10px;" onmouseover="shadow('linkedinicon')" onmouseout="unshadow('linkedinicon')" onclick="window.open('https://www.linkedin.com/in/yankee-majumder-6870ba134/','_blank')">
                <i id="linkedinicon" class="fa fa-linkedin-square" style="color:#001C55; width:50px; border-radius: 100px;"></i>
            </div>
            <span class="tooltiptext" style="margin-bottom:-15px;">LinkedIn</span>
        </div>
        <div class="tooltip">
            <div style="z-index: 0; text-align:center; display: inline-block; position:relative; width:50px; height: 60px; padding:10px; cursor: pointer; font-size: 50px; margin-right:10px;" onmouseover="shadow('emailicon')" onmouseout="unshadow('emailicon')" onclick="window.open('majumderyankee8@gmail.com')">
                <i id="emailicon" class="fa fa-envelope" style="color:#001C55; cursor:pointer; width:50px; border-radius: 100px;"></i>
            </div>
            <span class="tooltiptext" style="margin-bottom:-15px;">Email</span>
        </div>
    </div>
    <div id="education" class="section">
        <h1>Education</h1>
        <p>Bachelor of Technology in Information Technology from West Bengal University of Technology, 2016.</p>
    </div>
    <div id="skills" class="section">
        <h1>Skills</h1>
        <p>Languages: Bash (Linux), PowerShell (Windows). Skills: VMware Workspace ONE<p>
            </div>
            <div id="Projects" class="section">
            <h1>Projects</h1>

