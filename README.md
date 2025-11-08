<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=1280, height=720, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
<title>CIMB HR Portfolio – Mohamad Azlan</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet" />

<style>
/* ===== GLOBAL ===== */
*{margin:0;padding:0;box-sizing:border-box;}
body{
  font-family:'Poppins',sans-serif;
  background:linear-gradient(135deg,#A50034,#33000d);
  color:#fff;
  width:1280px;height:720px;
  overflow:hidden;position:relative;
}
h1{
  color:#FFD700;
  font-size:2rem;
  margin-bottom:1rem;
  text-shadow:0 0 15px rgba(255,215,0,.6);
}
p,li{
  font-size:1.05rem;
  line-height:1.7;
  color:#f1f1f1;
  text-align:justify;
}
ul{margin-top:1rem;margin-left:2rem;}
li{margin-bottom:6px;}

/* ===== NAVBAR ===== */
nav{
  position:absolute;top:20px;right:30px;
  display:flex;align-items:center;gap:22px;
  background:rgba(255,255,255,0.05);
  padding:10px 20px;border-radius:40px;
  backdrop-filter:blur(6px);
  box-shadow:0 0 15px rgba(255,215,0,0.1);
  z-index:10;
}
nav a{
  color:#fff;text-decoration:none;
  font-weight:500;font-size:0.95rem;
  transition:color .3s,text-shadow .3s;
}
nav a:hover{color:#FFD700;text-shadow:0 0 10px #FFD700;}
#filterBtn{
  padding:8px 18px;
  background:#FFD700;color:#000;
  border:none;border-radius:25px;
  font-weight:600;cursor:pointer;
  transition:transform .3s;
}
#filterBtn:hover{transform:scale(1.05);}

/* ===== SECTIONS ===== */
section{
  position:absolute;top:0;left:0;
  width:100%;height:100%;
  display:flex;flex-direction:column;
  align-items:center;justify-content:center;
  opacity:0;transform:scale(.98);
  transition:opacity .8s ease,transform .8s ease;
  padding:2rem 3rem;text-align:justify;
}
section.active{opacity:1;transform:scale(1);}
.section-content{
  max-width:900px;
  background:rgba(255,255,255,0.05);
  padding:2rem;border-radius:12px;
  box-shadow:0 0 25px rgba(255,215,0,0.1);
}

/* ===== GALLERY ===== */
.gallery{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  grid-template-rows:repeat(2,1fr);
  gap:14px;
  width:900px;height:400px;
}
.gallery img{
  width:100%;height:100%;
  object-fit:cover;border-radius:10px;
  box-shadow:0 0 12px rgba(255,215,0,.25);
  cursor:pointer;
  transition:transform .5s ease,box-shadow .5s ease,filter .5s ease;
}
.gallery img:hover{
  transform:scale(1.1);
  filter:brightness(1.1);
  box-shadow:0 0 25px rgba(255,215,0,.7);
}

/* ===== LIGHTBOX ===== */
#lightbox{
  position:fixed;top:0;left:0;width:100%;height:100%;
  background:rgba(0,0,0,0.9);
  display:flex;align-items:center;justify-content:center;
  visibility:hidden;opacity:0;
  transition:opacity .4s ease,visibility .4s ease;
  z-index:999;
}
#lightbox.active{visibility:visible;opacity:1;}
#lightbox img{
  max-width:90%;max-height:90%;
  border:3px solid #FFD700;border-radius:12px;
  box-shadow:0 0 40px rgba(255,215,0,.8);
  animation:zoomIn .4s ease;
}
@keyframes zoomIn{from{transform:scale(.6);opacity:0;}to{transform:scale(1);opacity:1;}}
#lightbox::after{
  content:"×";
  position:absolute;top:20px;right:40px;
  font-size:2rem;color:#FFD700;cursor:pointer;
}

/* ===== SIDE INFO ===== */
.side-info{
  background:rgba(255,255,255,0.08);
  border-left:4px solid #FFD700;
  border-radius:10px;
  margin:8px 0;padding:12px 16px;
  text-align:justify;max-width:800px;
}
.side-info h3{color:#FFD700;margin-bottom:4px;}
</style>
</head>

<body>
<!-- ===== NAVIGATION ===== -->
<nav>
  <a href="#" data-target="home">Home</a>
  <a href="#" data-target="overview">Overview</a>
  <a href="#" data-target="achievements">Key Achievements</a>
  <a href="#" data-target="gallery">Career Highlights Gallery</a>
  <a href="#" data-target="stories">Side Stories & Experiences</a>
  <a href="#" data-target="reflection">Reflection & Key Learning</a>
  <button id="filterBtn">Filter</button>
</nav>

<!-- ===== HOME ===== -->
<section id="home" class="active">
  <div class="section-content">
    <h1>CIMB HR Portfolio</h1>
    <p>Welcome to my HR portfolio at <strong>CIMB Group</strong> — a visual summary of initiatives, engagements, and key highlights that shaped my professional journey in Human Resources. Each section reflects my contribution to employer branding, recruitment excellence, and employee engagement.</p>
  </div>
</section>

<!-- ===== OVERVIEW ===== -->
<section id="overview">
  <div class="section-content">
    <h1>🎯 Overview</h1>
    <p>This portfolio reflects my journey at <strong>CIMB Group</strong> (2022–2023), where I supported the Group Operations division under HR Business Partnering. My responsibilities spanned employer branding, recruitment operations, leadership engagement, and employee well-being initiatives.</p>
    <ul>
      <li>HR Business Partner (Group Operations)</li>
      <li>Recruitment Operations & Walk-In Interviews</li>
      <li>Leadership Engagement & Employer Branding</li>
      <li>Employee Wellness & Culture Building</li>
    </ul>
  </div>
</section>

<!-- ===== ACHIEVEMENTS ===== -->
<section id="achievements">
  <div class="section-content">
    <h1>🌟 Key Achievements</h1>
    <p>Throughout my time at CIMB, I contributed to impactful HR programs that supported the company’s talent strategy and strengthened its position as a leading employer in Asia.</p>
    <ul>
      <li><strong>Employer Branding (MCTF Career Fair):</strong> Represented HR, engaging over 5,000 visitors and positioning CIMB as a preferred employer.</li>
      <li><strong>Group Operations Walk-In Interview:</strong> Executed large-scale hiring, closing more than 40 roles in a single week.</li>
      <li><strong>Grand Launch of CIMB Hub:</strong> Supported HR presence during the HQ opening event alongside senior leadership and media partners.</li>
      <li><strong>CEO Engagement:</strong> Interacted directly with Dato’ Abdul Rahman Ahmad, CEO of CIMB Group, recognizing HRBP efforts.</li>
      <li><strong>Chill-Out Sessions:</strong> Organized wellness and team activities to boost morale and strengthen workplace culture.</li>
      <li><strong>HR Asia Award 2022:</strong> Contributed to CIMB’s recognition as “Best Company to Work For in Asia.”</li>
    </ul>
  </div>
</section>

<!-- ===== GALLERY ===== -->
<section id="gallery">
  <h1>🖼️ Career Highlights Gallery</h1>
  <div class="gallery">
    <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/Employer%20Branding%20(MCTF%20Career%20Fair).jpg?raw=true" alt="">
    <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/MCTF%20career%20fair%20second%20picture.jpg?raw=true" alt="">
    <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/CEO%20Engagement.jpg?raw=true" alt="">
    <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/Recruitment%20Drive%20(Walk-In%20Interviews).jpg?raw=true" alt="">
    <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/Potluck.jpg?raw=true" alt="">
    <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/CIMB%20Grand%20Launching.jpeg?raw=true" alt="">
  </div>
</section>

<!-- ===== STORIES ===== -->
<section id="stories">
  <div class="section-content">
    <h1>💬 Side Stories & Experiences</h1>
    <div class="side-info">
      <h3>📢 Featured on CIMB LinkedIn</h3>
      <p>Represented HR during the Malaysia Career & Training Fair (MCTF), highlighting CIMB’s commitment to employer branding and talent development.</p>
    </div>
    <div class="side-info">
      <h3>🎉 EPICC Roadshow Participation</h3>
      <p>Supported CIMB’s EPICC program — a regional innovation initiative to foster engagement and collaboration among departments through interactive booths and cultural showcases.</p>
    </div>
    <div class="side-info">
      <h3>💐 Farewell Celebrations & Team Bonding</h3>
      <p>Coordinated farewell gatherings and breakfast sessions that built camaraderie, recognition, and belonging within the HR community.</p>
    </div>
  </div>
</section>

<!-- ===== REFLECTION ===== -->
<section id="reflection">
  <div class="section-content">
    <h1>🧭 Reflection & Key Learning</h1>
    <p>My time at CIMB was a transformative chapter where I learned to balance strategic HR execution with genuine human connection. Leading recruitment and branding efforts allowed me to align people-focused initiatives with measurable business impact.</p>
    <p><strong>Tagline:</strong> “Bridging HR and Analytics to empower data-driven talent transformation.”</p>
  </div>
</section>

<!-- ===== LIGHTBOX ===== -->
<div id="lightbox"></div>

<script>
/* ---- Navigation ---- */
const navLinks=document.querySelectorAll('nav a');
const sections=document.querySelectorAll('section');
navLinks.forEach(link=>{
  link.addEventListener('click',e=>{
    e.preventDefault();
    const target=link.dataset.target;
    if(!target)return;
    sections.forEach(sec=>sec.classList.remove('active'));
    document.getElementById(target).classList.add('active');
  });
});

/* ---- Lightbox ---- */
const galleryImages=document.querySelectorAll('.gallery img');
const lightbox=document.getElementById('lightbox');
galleryImages.forEach(img=>{
  img.addEventListener('click',()=>{
    lightbox.innerHTML=`<img src="${img.src}" alt="">`;
    lightbox.classList.add('active');
  });
});
lightbox.addEventListener('click',()=>lightbox.classList.remove('active'));
</script>
</body>
</html>
