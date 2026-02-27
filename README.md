<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Bhukya Venu | Electrical Engineer Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

:root{
--accent:#00d9ff;
--bg:#0a2731;
--card:#ffffff10;
--border:#ffffff20;
}

*{margin:0;padding:0;box-sizing:border-box;}

body{
font-family:'Poppins',sans-serif;
background:var(--bg);
color:white;
scroll-behavior:smooth;
}

nav{
position:fixed;
top:0;
width:100%;
background:rgba(0,0,0,0.6);
backdrop-filter:blur(10px);
display:flex;
justify-content:center;
gap:30px;
padding:15px;
z-index:1000;
}

nav a{
color:#ddd;
text-decoration:none;
font-weight:500;
transition:.3s;
}

nav a:hover{
color:var(--accent);
}

section{
min-height:100vh;
display:flex;
align-items:center;
justify-content:center;
padding:100px 20px;
}

.container{
max-width:1100px;
width:100%;
text-align:center;
}

h1,h2{
margin-bottom:20px;
}

ul{
text-align:left;
max-width:800px;
margin:20px auto;
line-height:1.8;
}

.profile-pic{
width:200px;
height:200px;
border-radius:50%;
object-fit:cover;
border:4px solid var(--accent);
margin-bottom:20px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:30px;
margin-top:30px;
}

.card{
background:var(--card);
border:1px solid var(--border);
padding:25px;
border-radius:15px;
transition:.3s;
}

.card:hover{
transform:translateY(-8px);
}

button{
margin-top:15px;
padding:8px 18px;
border:none;
border-radius:20px;
background:var(--accent);
color:black;
font-weight:600;
cursor:pointer;
}

.contact a{
color:var(--accent);
text-decoration:none;
}

footer{
text-align:center;
padding:20px;
background:#00000040;
}

</style>
</head>
<body>

<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#education">Education</a>
<a href="#internship">Internship</a>
<a href="#projects">Projects</a>
<a href="#certifications">Certifications</a>
<a href="#contact">Contact</a>
</nav>

<!-- HOME -->
<section id="home">
<div class="container">
<img src="profile.jpg" class="profile-pic">
<h1>Bhukya Venu</h1>
<p>B.Tech Electrical & Electronics Engineering</p>
<p>Lovely Professional University</p>
</div>
</section>

<!-- ABOUT -->
<section id="about">
<div class="container">
<h2>About Me</h2>
<ul>
<li>B.Tech student in Electrical and Electronics Engineering with strong technical foundation from Diploma in EEE.</li>
<li>Hands-on experience in Power System Distribution and Electrical Maintenance.</li>
<li>Skilled in Embedded Systems, IoT applications, and AutoCAD electrical design.</li>
<li>Strong problem-solving abilities with adaptability to emerging green technologies.</li>
<li>Focused on sustainable energy systems and power distribution networks.</li>
</ul>
</div>
</section>

<!-- SKILLS -->
<section id="skills">
<div class="container">
<h2>Skills</h2>

<h3>Technical Skills</h3>
<ul>
<li>C (Basics)</li>
<li>C++ (Basics)</li>
<li>MATLAB</li>
<li>AutoCAD</li>
<li>Arduino IDE</li>
<li>Oracle Basics (OCI & Data Platform Fundamentals)</li>
<li>Embedded Systems</li>
<li>Internet of Things (IoT)</li>
<li>Power Systems</li>
<li>Electrical Maintenance</li>
</ul>

<h3>Soft Skills</h3>
<ul>
<li>Communication</li>
<li>Time Management</li>
<li>Teamwork & Collaboration</li>
<li>Problem-Solving</li>
<li>Adaptability</li>
</ul>

</div>
</section>

<!-- EDUCATION -->
<section id="education">
<div class="container">
<h2>Education</h2>
<ul>
<li><strong>Bachelor of Technology (EEE)</strong> – Lovely Professional University (2026 – Present)</li>
<li><strong>Diploma in EEE</strong> – Anurag Engineering College | CGPA: 6.93</li>
<li><strong>Matriculation</strong> – Nirmala High School | CGPA: 10.0</li>
</ul>
</div>
</section>

<!-- INTERNSHIP -->
<section id="internship">
<div class="container">
<h2>Internship Experience</h2>
<ul>
<li><strong>HN Techfo (May 2025 – July 2025)</strong> – Worked on Power System Distribution, load management, and preventive maintenance.</li>
<li><strong>Samar Tech Training & Software Solutions (Dec 2023 – June 2024)</strong> – AutoCAD design, Panel Board Testing, House Wiring, and E-Vehicle Repair & Maintenance.</li>
</ul>
</div>
</section>

<!-- PROJECTS -->
<section id="projects">
<div class="container">
<h2>Projects</h2>

<div class="grid">

<div class="card">
<h3>Battery Level Indicator</h3>
<p>Designed an LED-based battery charge indicator circuit with protection against overcharging and voltage drop.</p>
</div>

<div class="card">
<h3>Water pH Checking Indicator</h3>
<p>Developed a pH measurement system to classify water acidity and alkalinity levels with visual indication.</p>
</div>

</div>
</div>
</section>

<!-- CERTIFICATIONS -->
<section id="certifications">
<div class="container">
<h2>Certifications</h2>
<ul>
<li>Workshop on Designing Solar PV Systems – Anurag Engineering College</li>
<li>Oracle Certified Foundations Associate – AI Foundations</li>
<li>Oracle Certified Professional – Data Science</li>
</ul>
</div>
</section>

<!-- CONTACT -->
<section id="contact">
<div class="container contact">
<h2>Contact</h2>
<p>Email: <a href="mailto:venurathod111@gmail.com">venurathod111@gmail.com</a></p>
<p>Mobile: +91 9110308169</p>
<p>LinkedIn: <a href="http://linkedin.com/in/bhukya-venu-a80ab6350" target="_blank">View Profile</a></p>
</div>
</section>

<footer>
©️ 2026 Bhukya Venu | Electrical Engineer Portfolio
</footer>

</body>
</html>
