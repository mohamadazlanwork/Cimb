<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>CIMB HR Portfolio – Mohamad Azlan</title>
<p style="text-align:center;font-size:0.9rem;color:#ccc;margin-top:10px;">
⚠️ All visuals in this portfolio are infographic representations only and contain no confidential or proprietary CIMB data.
</p>

<style>
/* ====== RESET ====== */
*{margin:0;padding:0;box-sizing:border-box;}
body{
  font-family:'Poppins',sans-serif;
  background:#0a0a0a;
  color:#fff;
  line-height:1.8;
  overflow-x:hidden;
}

/* ====== BRAND COLORS ====== */
:root{
  --cimb-red:#A50034;
  --cimb-light:#ff3355;
  --cimb-dark:#33000d;
}

/* ====== BACKGROUND GRID & LIGHT ====== */
body::before{
  content:"";
  position:fixed;inset:0;
  background:
    radial-gradient(circle at 25% 25%,rgba(165,0,52,0.4),transparent 70%),
    radial-gradient(circle at 75% 75%,rgba(255,0,64,0.3),transparent 80%),
    linear-gradient(135deg,#0a0a0a 10%,#180000 60%,#000);
  z-index:-3;
}
body::after{
  content:"";
  position:fixed;inset:0;
  background-image:
    repeating-linear-gradient(0deg,rgba(255,255,255,.05) 0 1px,transparent 1px 80px),
    repeating-linear-gradient(90deg,rgba(255,255,255,.05) 0 1px,transparent 1px 80px);
  opacity:.2;
  z-index:-2;
}

/* animated beam */
@keyframes beam {
  0% {transform:translateY(-400px) translateX(-250px);}
  100% {transform:translateY(120vh) translateX(250px);}
}
.lightbeam{
  position:fixed;
  top:-300px;left:50%;
  width:3px;height:400px;
  background:linear-gradient(to bottom,rgba(255,0,64,0.6),transparent);
  animation:beam 4s linear infinite;
  z-index:-1;
}

/* ====== HEADER ====== */
header{
  background:linear-gradient(90deg,var(--cimb-red),var(--cimb-dark));
  color:#fff;
  text-align:center;
  padding:3rem 1rem 2rem 1rem;
  box-shadow:0 0 30px rgba(255,0,64,0.3);
  position:relative;
}
header h1{
  font-size:2.8rem;
  text-shadow:0 0 10px rgba(255,0,64,0.5);
}
header p{
  margin-top:.5rem;
  font-size:1.1rem;
  opacity:.9;
  letter-spacing:0.5px;
}

/* ====== SECTION BOXES ====== */
section{
  background:rgba(255,255,255,0.05);
  border:1px solid rgba(255,0,64,0.2);
  border-radius:14px;
  padding:2rem;
  margin:2rem auto;
  max-width:1000px;
  box-shadow:0 0 25px rgba(255,0,64,0.15);
  backdrop-filter:blur(8px);
}
h2{
  color:var(--cimb-light);
  border-left:4px solid var(--cimb-red);
  padding-left:12px;
  margin-bottom:1rem;
  font-size:1.4rem;
  text-shadow:0 0 8px rgba(255,0,64,0.4);
}
p,li,td,th{color:#f5f5f5;}
ul{margin-left:1.5rem;margin-top:.5rem;}
li{margin-bottom:.5rem;}

/* ====== TABLE ====== */
table{
  width:100%;
  border-collapse:collapse;
  margin-top:1rem;
  border-radius:8px;
  overflow:hidden;
}
th,td{
  padding:0.9rem 1rem;
  border-bottom:1px solid rgba(255,255,255,0.1);
}
th{
  background:rgba(255,255,255,0.1);
  color:var(--cimb-light);
  text-align:left;
}
tr:hover{
  background:rgba(255,0,64,0.15);
  transition:0.3s ease;
}

/* ====== GALLERY ====== */
.gallery{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
  gap:18px;
  margin-top:1rem;
}
.gallery img{
  width:100%;
  border-radius:10px;
  box-shadow:0 0 12px rgba(255,0,64,0.3);
  transition:transform .3s, box-shadow .3s;
}
.gallery img:hover{
  transform:scale(1.06);
  box-shadow:0 0 25px rgba(255,0,64,0.6);
}

/* ====== SIDE INFO ====== */
.side-info{
  background:rgba(255,255,255,0.06);
  border-left:5px solid var(--cimb-red);
  padding:1.5rem;
  border-radius:10px;
  margin-top:1.2rem;
  box-shadow:0 0 10px rgba(255,0,64,0.1);
}
.side-info h3{
  color:var(--cimb-light);
  margin-bottom:0.5rem;
  text-shadow:0 0 6px rgba(255,0,64,0.4);
}
.side-info p{font-size:0.95rem;}

/* ====== FOOTER ====== */
footer{
  text-align:center;
  padding:2rem;
  color:#bbb;
  font-size:0.9rem;
  border-top:1px solid rgba(255,0,64,0.2);
}
footer a{
  color:var(--cimb-light);
  text-decoration:none;
}
footer a:hover{text-decoration:underline;}

/* ====== HOVER GLOW EFFECT ====== */
section, .side-info, img, table, header{
  transition:box-shadow .4s ease, transform .4s ease;
}
section:hover, .side-info:hover{
  box-shadow:0 0 35px rgba(255,0,64,0.3);
}
</style>
</head>

<body>
<div class="lightbeam"></div>

<header>
  <h1>CIMB HR Highlights & Achievements</h1>
  <p>Human Resources · Employer Branding · Recruitment Analytics</p>
</header>

<section>
  <h2>🎯 Overview</h2>
  <p>
    This portfolio reflects my journey at <strong>CIMB Group</strong> (2022–2023) as part of the HR team in Kuala Lumpur.  
    My focus areas included <em>Employer Branding</em>, <em>Talent Acquisition</em>, <em>HRBP Support</em>, and <em>Employee Engagement</em>.  
    Through collaboration and innovation, I contributed to projects that strengthened CIMB’s culture, visibility, and operational excellence.
  </p>
  <ul>
    <li>Human Resources Business Partner (Group Operations)</li>
    <li>Recruitment Operations & Walk-In Interviews</li>
    <li>Leadership Engagement & Employer Branding</li>
    <li>Employee Wellness & Culture Building</li>
  </ul>
</section>

<section>
  <h2>🌟 Key Achievements</h2>
  <table>
    <tr><th>Highlight</th><th>Description</th></tr>
    <tr><td>🏆 Employer Branding (MCTF Career Fair)</td><td>Represented HR at Malaysia Career & Training Fair engaging 5,000+ visitors and positioning CIMB as a preferred employer.</td></tr>
    <tr><td>💼 Group Operations Walk-In Interview</td><td>Executed a large-scale hiring event; collaborated with HRBPs and hiring managers to close 40+ positions in one week.</td></tr>
    <tr><td>🏢 Grand Launch of CIMB Hub</td><td>Supported HR presence during the new headquarters opening attended by senior leadership and media partners.</td></tr>
    <tr><td>👥 CEO Engagement</td><td>Interacted with Dato’ Abdul Rahman Ahmad (CEO) recognizing HRBP team contributions to employer branding initiatives.</td></tr>
    <tr><td>🌿 Chill-Out Sessions</td><td>Organized wellness activities and team potluck events to foster connection and morale.</td></tr>
    <tr><td>🏅 HR Asia Award 2022</td><td>Contributed inputs for CIMB’s recognition as “Best Company to Work For in Asia”.</td></tr>
  </table>
</section>

<section>
  <h2>🖼️ Career Highlights Gallery</h2>
  <div class="gallery">
    <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/Employer%20Branding%20(MCTF%20Career%20Fair).jpg?raw=true" alt="MCTF Career Fair">
    <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/MCTF%20career%20fair%20second%20picture.jpg?raw=true" alt="Career Fair">
    <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/CEO%20Engagement.jpg?raw=true" alt="CEO Engagement">
    <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/Recruitment%20Drive%20(Walk-In%20Interviews).jpg?raw=true" alt="Walk-In Interview">
    <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/Potluck.jpg?raw=true" alt="Potluck Session">
    <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/CIMB%20Grand%20Launching.jpeg?raw=true" alt="CIMB Grand Launching">

  </div>
  <p style="margin-top:1rem;"><i>✨ Each photo captures the energy and collaboration within #teamCIMB — from branding events to HR celebrations.</i></p>
</section>

<section>
  <h2>💬 Side Stories & Experiences</h2>
  <div class="side-info">
    <h3>📢 Featured on CIMB LinkedIn</h3>
    <p>Thrilled to be featured on CIMB’s official LinkedIn page, representing HR during the MCTF Career Fair and highlighting employer branding initiatives.</p>
  </div>
  <div class="side-info">
    <h3>🎉 EPICC Roadshow Participation</h3>
    <p>Supported CIMB’s EPICC innovation program by collaborating across departments and promoting team culture through interactive booths and merchandise distribution.</p>
  </div>
  <div class="side-info">
    <h3>💐 Farewell Celebrations & Team Bonding</h3>
    <p>Coordinated farewell gatherings and breakfast sessions to strengthen relationships and foster a positive HR workplace environment.</p>
  </div>
</section>

<section>
  <h2>🧭 Reflection & Key Learning</h2>
  <p>
    My time at CIMB was transformative — blending corporate discipline with human connection.  
    Through hands-on projects in recruitment and branding, I learned to bridge strategic HR initiatives with data-driven decision-making.
  </p>
  <p><strong>Tagline:</strong> “Bridging HR and Analytics to empower data-driven talent transformation.”</p>
</section>

<footer>
  <p>© 2022 Mohamad Azlan | <a href="#">Back to Top</a></p>
</footer>

</body>
</html>
