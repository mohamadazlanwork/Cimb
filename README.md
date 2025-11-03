<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>CIMB HR Portfolio – Mohamad Azlan</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet" />
<style>
/* ===== GLOBAL ===== */
*{margin:0;padding:0;box-sizing:border-box;}
body{
  font-family:'Poppins',sans-serif;
  background:#0a0a0a;
  color:#fff;
  overflow-x:hidden;
  scroll-behavior:smooth;
}
:root{--cimb-red:#A50034;--cimb-dark:#33000d;--cimb-gold:#FFD700;--cimb-light:#ff3355;}
body::before{
  content:"";position:fixed;inset:0;
  background:radial-gradient(circle at 25% 25%,rgba(165,0,52,.4),transparent 70%),radial-gradient(circle at 75% 75%,rgba(255,0,64,.3),transparent 80%),linear-gradient(135deg,#0a0a0a 10%,#180000 60%,#000);
  z-index:-2;
}
body::after{
  content:"";position:fixed;inset:0;
  background-image:repeating-linear-gradient(0deg,rgba(255,255,255,.05) 0 1px,transparent 1px 80px),repeating-linear-gradient(90deg,rgba(255,255,255,.05) 0 1px,transparent 1px 80px);
  opacity:.15;z-index:-1;
}
section{transition:opacity 1s ease, transform 1s ease;}

/* ===== LANDING ===== */
#landing{
  min-height:100vh;
  display:flex;
  flex-direction:column;
  align-items:center;
  justify-content:center;
  text-align:center;
  line-height:1.7;
}
#landing h1{
  font-size:3rem;
  color:var(--cimb-gold);
  text-shadow:0 0 20px rgba(255,215,0,.6);
  animation:fadeIn 2s ease forwards;
}
#landing p{
  font-size:1.2rem;
  color:#ddd;
  margin-top:1rem;
  opacity:0;
  animation:fadeIn 2s 1s forwards;
}
@keyframes fadeIn{0%{opacity:0;transform:translateY(30px);}100%{opacity:1;transform:translateY(0);}}
#viewBtn{
  margin-top:3rem;
  padding:1rem 2.8rem;
  font-size:1rem;
  color:#fff;
  border:none;
  border-radius:50px;
  background:linear-gradient(90deg,var(--cimb-red),var(--cimb-dark));
  cursor:pointer;
  box-shadow:0 0 25px rgba(165,0,52,.4);
  transition:.3s;
  opacity:0;
  animation:fadeIn 2s 2s forwards;
}
#viewBtn:hover{
  transform:scale(1.05);
  box-shadow:0 0 35px rgba(255,215,0,.6);
  background:linear-gradient(90deg,var(--cimb-gold),var(--cimb-red));
  color:#000;
}
.fadeOut{animation:fadeOut 1s forwards;}
@keyframes fadeOut{to{opacity:0;transform:scale(1.05);}}

/* ===== PAGE 2 ===== */
#highlights{opacity:0;pointer-events:none;transform:translateY(40px);}
#highlights.active{opacity:1;pointer-events:auto;transform:translateY(0);transition:opacity 1.2s ease,transform 1.2s ease;}

header{
  background:linear-gradient(90deg,var(--cimb-red),var(--cimb-dark));
  color:#fff;text-align:center;padding:3rem 1rem 2rem 1rem;
  box-shadow:0 0 30px rgba(255,0,64,.3);
}
header h1{font-size:2.6rem;text-shadow:0 0 10px rgba(255,0,64,.5);}
header p{margin-top:.5rem;font-size:1.1rem;opacity:.9;}
header a{
  display:inline-block;margin-top:1rem;padding:10px 20px;
  border-radius:30px;background:linear-gradient(90deg,#FFD700,#A50034);
  color:#000;text-decoration:none;font-weight:600;box-shadow:0 0 15px rgba(255,215,0,.4);
}
header a:hover{filter:brightness(1.2);}
.disclaimer{text-align:center;font-size:.9rem;color:#f3f3f3;background:rgba(255,255,255,0.08);border:1px solid rgba(255,255,255,0.1);border-radius:8px;width:fit-content;margin:1rem auto;padding:8px 16px;backdrop-filter:blur(4px);}
section.inner{
  background:rgba(255,255,255,0.05);
  border:1px solid rgba(255,0,64,0.2);
  border-radius:14px;
  padding:2rem;
  margin:2rem auto;
  max-width:1000px;
  box-shadow:0 0 25px rgba(255,0,64,0.15);
  backdrop-filter:blur(8px);
}
h2{color:var(--cimb-light);border-left:4px solid var(--cimb-red);padding-left:12px;margin-bottom:1rem;font-size:1.4rem;text-shadow:0 0 8px rgba(255,0,64,0.4);}
ul{margin-left:1.5rem;margin-top:.5rem;}li{margin-bottom:.5rem;}
.gallery{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
  gap:18px;margin-top:1rem;
}
.gallery img{width:100%;border-radius:10px;box-shadow:0 0 12px rgba(255,0,64,.3);transition:transform .3s, box-shadow .3s;}
.gallery img:hover{transform:scale(1.06);box-shadow:0 0 25px rgba(255,0,64,.6);}
.side-info{
  background:rgba(255,255,255,0.06);
  border-left:5px solid var(--cimb-red);
  padding:1.5rem;border-radius:10px;
  margin-top:1.2rem;box-shadow:0 0 10px rgba(255,0,64,.1);
}
.side-info h3{color:var(--cimb-light);margin-bottom:.5rem;}
footer{text-align:center;padding:2rem;color:#bbb;font-size:.9rem;border-top:1px solid rgba(255,0,64,.2);}
footer a{color:var(--cimb-light);text-decoration:none;}
footer a:hover{text-decoration:underline;}
</style>
</head>
<body>

<!-- ========== PAGE 1 ========== -->
<section id="landing">
  <h1>CIMB HR Portfolio</h1>
  <p>Employer Branding · Recruitment Analytics · Engagement</p>
  <button id="viewBtn">View Highlights →</button>
</section>

<!-- ========== PAGE 2 ========== -->
<section id="highlights">
  <header>
    <h1>CIMB HR Highlights & Achievements</h1>
    <p>Human Resources · Employer Branding · Recruitment Analytics</p>
    <a href="#landing" id="backBtn">← Back to Top</a>
  </header>

  <p class="disclaimer">⚠️ All visuals are infographic representations only and contain no confidential CIMB data.</p>

  <section class="inner">
    <h2>🎯 Overview</h2>
    <p>This portfolio reflects my journey at <strong>CIMB Group</strong> (2022–2023) — focusing on Employer Branding, Talent Acquisition, HRBP Support, and Employee Engagement.</p>
    <ul>
      <li>HR Business Partner (Group Operations)</li>
      <li>Recruitment Operations & Walk-In Interviews</li>
      <li>Leadership Engagement & Employer Branding</li>
      <li>Employee Wellness & Culture Building</li>
    </ul>
  </section>

  <section class="inner">
    <h2>🌟 Key Achievements</h2>
    <div style="background:#fff;color:#000;padding:1.5rem 2rem;border-radius:12px;box-shadow:0 0 25px rgba(165,0,52,.25);font-weight:500;line-height:1.7;">
      <p>🏆 <strong>Employer Branding (MCTF Career Fair)</strong><br>Represented HR engaging 5 000+ visitors and positioning CIMB as a preferred employer.</p><br>
      <p>💼 <strong>Group Operations Walk-In Interview</strong><br>Executed large-scale hiring, closing 40+ positions in one week.</p><br>
      <p>🏢 <strong>Grand Launch of CIMB Hub</strong><br>Supported HR presence during the HQ opening with senior leadership and media partners.</p><br>
      <p>👥 <strong>CEO Engagement</strong><br>Interacted with Dato’ Abdul Rahman Ahmad (CEO) recognizing HRBP contributions.</p><br>
      <p>🌿 <strong>Chill-Out Sessions</strong><br>Organized wellness and team events to boost morale.</p><br>
      <p>🏅 <strong>HR Asia Award 2022</strong><br>Contributed to CIMB’s recognition as “Best Company to Work For in Asia”.</p>
    </div>
  </section>

  <section class="inner">
    <h2>🖼️ Career Highlights Gallery</h2>
    <div class="gallery">
      <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/Employer%20Branding%20(MCTF%20Career%20Fair).jpg?raw=true" alt="MCTF Career Fair">
      <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/MCTF%20career%20fair%20second%20picture.jpg?raw=true" alt="Career Fair 2">
      <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/CEO%20Engagement.jpg?raw=true" alt="CEO Engagement">
      <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/Recruitment%20Drive%20(Walk-In%20Interviews).jpg?raw=true" alt="Walk-In Interview">
      <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/Potluck.jpg?raw=true" alt="Potluck Session">
      <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/CIMB%20Grand%20Launching.jpeg?raw=true" alt="CIMB Grand Launch">
    </div>
    <p style="margin-top:1rem;"><i>✨ Each photo captures the energy and collaboration within #teamCIMB — from branding events to HR celebrations.</i></p>
  </section>

  <section class="inner">
    <h2>💬 Side Stories & Experiences</h2>
    <div class="side-info"><h3>📢 Featured on CIMB LinkedIn</h3><p>Featured representing HR during MCTF Career Fair highlighting employer branding initiatives.</p></div>
    <div class="side-info"><h3>🎉 EPICC Roadshow Participation</h3><p>Supported CIMB’s EPICC innovation program promoting team culture through booths & merchandise.</p></div>
    <div class="side-info"><h3>💐 Farewell Celebrations & Team Bonding</h3><p>Coordinated farewell & breakfast sessions fostering a positive HR environment.</p></div>
  </section>

  <section class="inner">
    <h2>🧭 Reflection & Key Learning</h2>
    <p>My time at CIMB was transformative — blending corporate discipline with human connection.  
       Through projects in recruitment and branding, I learned to bridge strategic HR initiatives with data-driven decision-making.</p>
    <p><strong>Tagline:</strong> “Bridging HR and Analytics to empower data-driven talent transformation.”</p>
  </section>

  <footer><p>© 2022 Mohamad Azlan | <a href="#landing">Back to Top</a></p></footer>
</section>

<script>
const btn=document.getElementById("viewBtn");
const landing=document.getElementById("landing");
const highlights=document.getElementById("highlights");
btn.addEventListener("click",()=>{
  landing.classList.add("fadeOut");
  setTimeout(()=>{
    landing.style.display="none";
    highlights.classList.add("active");
    window.scrollTo({top:0,behavior:"instant"});
  },900);
});
document.getElementById("backBtn").addEventListener("click",()=>{
  highlights.classList.remove("active");
  landing.style.display="flex";
  setTimeout(()=>landing.classList.remove("fadeOut"),50);
});
</script>
</body>
</html>
