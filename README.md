# Portfolio-Website
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dharanidharan B | Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#0B1120;
color:#F8FAFC;
}

nav{
position:fixed;
top:0;
left:0;
width:100%;
background:rgba(11,17,32,0.95);
backdrop-filter:blur(10px);
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 8%;
z-index:1000;
border-bottom:1px solid rgba(255,255,255,0.1);
}

.logo{
font-size:28px;
font-weight:700;
color:#38BDF8;
}

nav ul{
display:flex;
list-style:none;
gap:25px;
}

nav ul li a{
text-decoration:none;
color:white;
font-weight:500;
transition:.3s;
}

nav ul li a:hover{
color:#38BDF8;
}

.hero{
height:100vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
background:linear-gradient(to right,#0B1120,#111827);
}

.hero-content{
max-width:900px;
}

.hero-content h1{
font-size:70px;
color:#38BDF8;
margin-bottom:15px;
}

.hero-content h2{
font-size:28px;
font-weight:400;
margin-bottom:20px;
}

.hero-content p{
font-size:18px;
line-height:1.8;
color:#CBD5E1;
margin-bottom:30px;
}

.btn{
display:inline-block;
padding:14px 28px;
background:#38BDF8;
color:#000;
text-decoration:none;
font-weight:600;
border-radius:10px;
transition:.3s;
}

.btn:hover{
transform:translateY(-4px);
}

section{
padding:100px 8%;
}

.section-title{
text-align:center;
font-size:42px;
color:#38BDF8;
margin-bottom:50px;
}

.stats{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:25px;
}

.stat{
background:#1E293B;
padding:35px;
border-radius:15px;
text-align:center;
}

.stat h2{
font-size:45px;
color:#38BDF8;
margin-bottom:10px;
}

.about{
display:grid;
grid-template-columns:1fr 1fr;
gap:30px;
}

.card{
background:#1E293B;
padding:30px;
border-radius:15px;
transition:.3s;
}

.card:hover{
transform:translateY(-5px);
}

.skills{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
gap:20px;
}

.skill{
background:#1E293B;
padding:20px;
text-align:center;
border-radius:12px;
font-weight:500;
}

.timeline{
border-left:4px solid #38BDF8;
padding-left:25px;
}

.timeline-item{
margin-bottom:35px;
}

.timeline-item h3{
color:#38BDF8;
margin-bottom:8px;
}

.projects{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:25px;
}

.project{
background:#1E293B;
padding:25px;
border-radius:15px;
transition:.3s;
}

.project:hover{
transform:translateY(-8px);
}

.project h3{
color:#38BDF8;
margin-bottom:10px;
}

.contact{
text-align:center;
}

.contact p{
margin:15px 0;
font-size:18px;
}

footer{
background:#020617;
padding:25px;
text-align:center;
margin-top:40px;
}

footer p{
color:#94A3B8;
}

@media(max-width:768px){

.hero-content h1{
font-size:45px;
}

.hero-content h2{
font-size:22px;
}

.about{
grid-template-columns:1fr;
}

nav{
flex-direction:column;
gap:15px;
}

nav ul{
flex-wrap:wrap;
justify-content:center;
}

}

</style>
</head>

<body>

<nav>
<div class="logo">DB</div>

<ul>
<li><a href="#about">About</a></li>
<li><a href="#skills">Skills</a></li>
<li><a href="#experience">Experience</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>

<section class="hero">
<div class="hero-content">

<h1>Dharanidharan B</h1>

<h2>Software Engineer | Full Stack Developer | Embedded Systems Enthusiast</h2>

<p>
Passionate Electronics and Communication Engineering student with strong interests in Full Stack Development, Embedded Systems, IoT and AI Technologies. Experienced in building innovative software and hardware solutions that solve real-world problems.
</p>

<a href="#projects" class="btn">View Projects</a>

</div>
</section>

<section>

<h2 class="section-title">My Statistics</h2>

<div class="stats">

<div class="stat">
<h2>4+</h2>
<p>Internships</p>
</div>

<div class="stat">
<h2>10+</h2>
<p>Projects</p>
</div>

<div class="stat">
<h2>8.09</h2>
<p>CGPA</p>
</div>

<div class="stat">
<h2>5+</h2>
<p>Certifications</p>
</div>

</div>

</section>

<section id="about">

<h2 class="section-title">About Me</h2>

<div class="about">

<div class="card">
<h3>Education</h3>
<br>
<p><strong>B.E Electronics and Communication Engineering</strong></p>
<p>SNS College of Technology</p>
<p>CGPA: 8.09</p>
<p>2023 - 2027</p>
</div>

<div class="card">
<h3>Career Objective</h3>
<br>
<p>
Aspiring Software Engineer with expertise in Web Development, Embedded Systems and IoT. Passionate about developing scalable applications and intelligent embedded solutions while continuously learning emerging technologies.
</p>
</div>

</div>

</section>

<section id="skills">

<h2 class="section-title">Technical Skills</h2>

<div class="skills">

<div class="skill">JavaScript</div>
<div class="skill">React.js</div>
<div class="skill">Node.js</div>
<div class="skill">Python</div>
<div class="skill">HTML5</div>
<div class="skill">CSS3</div>
<div class="skill">MySQL</div>
<div class="skill">Git & GitHub</div>
<div class="skill">REST APIs</div>
<div class="skill">Arduino</div>
<div class="skill">IoT</div>
<div class="skill">Embedded Systems</div>

</div>

</section>

<section id="experience">

<h2 class="section-title">Experience</h2>

<div class="timeline">

<div class="timeline-item">
<h3>KT Telematic Solutions</h3>
<p>Web Development Intern</p>
</div>

<div class="timeline-item">
<h3>Vault of Codes</h3>
<p>Web Development Intern</p>
</div>

<div class="timeline-item">
<h3>IRCTC Signal & Telecommunication Workshop</h3>
<p>Industrial Training</p>
</div>

<div class="timeline-item">
<h3>Fenzo Power Systems</h3>
<p>Industrial Internship</p>
</div>

</div>

</section>

<section id="projects">

<h2 class="section-title">Featured Projects</h2>

<div class="projects">

<div class="project">
<h3>Vehicle Tracking Dashboard</h3>
<p>Real-time vehicle monitoring dashboard with tracking analytics and responsive UI.</p>
</div>

<div class="project">
<h3>Intelligent Vehicle Collision Avoidance System</h3>
<p>Sensor-based obstacle detection system designed to improve road safety.</p>
</div>

<div class="project">
<h3>CNG Gas Leakage Detection System</h3>
<p>Detects gas leakage and instantly alerts users through alarm systems.</p>
</div>

<div class="project">
<h3>Arduino Solar Panel Positioning System</h3>
<p>Automatic solar tracking system using LDR sensors for maximum efficiency.</p>
</div>

</div>

</section>

<section>

<h2 class="section-title">Certifications</h2>

<div class="projects">

<div class="project">
<h3>OCI AI Foundations Associate</h3>
</div>

<div class="project">
<h3>NPTEL Cloud Computing</h3>
</div>

<div class="project">
<h3>NPTEL Optical Wireless Communications</h3>
</div>

<div class="project">
<h3>DRDO Conference Paper Presentation</h3>
</div>

</div>

</section>

<section id="contact">

<h2 class="section-title">Contact Me</h2>

<div class="card contact">

<p>📧 iamdharanidharan005@gmail.com</p>

<p>🐙 github.com/dharanidharanbktt</p>

<p>📍 Coimbatore, Tamil Nadu, India</p>

<p>🎓 SNS College of Technology</p>

</div>

</section>

<footer>
<p>© 2026 Dharanidharan B | All Rights Reserved</p>
</footer>

</body>
</html>
