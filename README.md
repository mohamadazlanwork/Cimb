<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>CIMB HR Portfolio – Mohamad Azlan</title>
<style>
*{margin:0;padding:0;box-sizing:border-box;}
html,body{width:100%;height:100%;font-family:'Inter','Helvetica Neue',sans-serif;background-color:#050505;color:#fff;}
body{overflow-x:hidden;}

/* ---------- BACKGROUND ---------- */
.gradient-background{position:fixed;top:0;left:0;width:100%;height:100%;z-index:1;overflow:hidden;}
.gradient-sphere{position:absolute;border-radius:50%;filter:blur(60px);}
.sphere-1{width:40vw;height:40vw;background:linear-gradient(40deg,rgba(255,0,128,.8),rgba(255,102,0,.4));top:-10%;left:-10%;animation:float-1 15s ease-in-out infinite alternate;}
.sphere-2{width:45vw;height:45vw;background:linear-gradient(240deg,rgba(72,0,255,.8),rgba(0,183,255,.4));bottom:-20%;right:-10%;animation:float-2 18s ease-in-out infinite alternate;}
.sphere-3{width:30vw;height:30vw;background:linear-gradient(120deg,rgba(133,89,255,.5),rgba(98,216,249,.3));top:60%;left:20%;animation:float-3 20s ease-in-out infinite alternate;}
@keyframes float-1{0%{transform:translate(0,0)scale(1);}100%{transform:translate(10%,10%)scale(1.1);}}
@keyframes float-2{0%{transform:translate(0,0)scale(1);}100%{transform:translate(-10%,-5%)scale(1.15);}}
@keyframes float-3{0%{transform:translate(0,0)scale(1);opacity:.3;}100%{transform:translate(-5%,10%)scale(1.05);opacity:.6;}}
.glow{position:absolute;width:40vw;height:40vh;background:radial-gradient(circle,rgba(72,0,255,.15),transparent 70%);top:50%;left:50%;transform:translate(-50%,-50%);animation:pulse 8s infinite alternate;filter:blur(30px);}
@keyframes pulse{0%{opacity:.3;transform:translate(-50%,-50%)scale(.9);}100%{opacity:.7;transform:translate(-50%,-50%)scale(1.1);}}
.grid-overlay{position:absolute;top:0;left:0;width:100%;height:100%;background-size:40px 40px;background-image:linear-gradient(to right,rgba(255,255,255,.03) 1px,transparent 1px),linear-gradient(to bottom,rgba(255,255,255,.03) 1px,transparent 1px);}
.noise-overlay{position:absolute;top:0;left:0;width:100%;height:100%;opacity:.05;background-image:url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.65' numOctaves='3'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)'/%3E%3C/svg%3E");}

/* ---------- PARTICLES ---------- */
.particles-container{position:fixed;top:0;left:0;width:100%;height:100%;z-index:2;pointer-events:none;}
.particle{position:absolute;background:white;border-radius:50%;opacity:0;pointer-events:none;}

/* ---------- CONTENT ---------- */
.content-container{position:relative;z-index:10;max-width:950px;margin:auto;padding:3rem 2rem;text-align:center;}
section{background:rgba(255,255,255,.1);border-radius:12px;padding:2rem 1.5rem;margin-bottom:2rem;box-shadow:0 4px 20px rgba(0,0,0,.3);}
h1,h2,h3{color:#fff;margin-bottom:1rem;transition:transform .3s ease;}
h1:hover,h2:hover,h3:hover{transform:scale(1.04);}
p,li{color:rgba(255,255,255,.9);margin-bottom:.8rem;}
table{width:100%;border-collapse:collapse;background:rgba(255,255,255,.1);border-radius:10px;overflow:hidden;margin-top:1rem;}
th,td{padding:.8rem 1rem;text-align:left;border-bottom:1px solid rgba(255,255,255,.1);}
tr:hover{background:rgba(255,255,255,.15);}
img{border-radius:10px;box-shadow:0 2px 12px rgba(0,0,0,.4);margin:10px;transition:transform .4s ease;}
img:hover{transform:scale(1.05);}
a{color:#ff3a82;text-decoration:none;}
a:hover{text-decoration:underline;}
.btn{background:linear-gradient(90deg,#ff3a82,#5233ff);color:#fff;font-weight:600;padding:.8rem 2rem;border:none;border-radius:50px;cursor:pointer;transition:all .3s ease;box-shadow:0 4px 20px rgba(255,58,130,.3);}
.btn:hover{transform:translateY(-3px);box-shadow:0 6px 25px rgba(255,58,130,.45);}
</style>
</head>
<body>

<!-- Background Layers -->
<div class="gradient-background">
  <div class="gradient-sphere sphere-1"></div>
  <div class="gradient-sphere sphere-2"></div>
  <div class="gradient-sphere sphere-3"></div>
  <div class="glow"></div>
  <div class="grid-overlay"></div>
  <div class="noise-overlay"></div>
  <div class="particles-container" id="particles-container"></div>
</div>

<!-- Main Content -->
<div class="content-container">

  <section>
    <h1>🏢 CIMB HR Portfolio</h1>
    <p><b>Showcasing my journey at CIMB — driving employer branding, HR operations and recruitment analytics through innovation and teamwork.</b></p>
  </section>

  <section>
    <h2>🎯 Overview</h2>
    <p>This portfolio documents my career highlights and HR achievements during my tenure at CIMB Group, one of Asia’s leading financial institutions. It captures hands-on experience in:</p>
    <ul>
      <li>Employer Branding &amp; HRBP Collaboration</li>
      <li>Recruitment Operations &amp; Walk-In Interviews</li>
      <li>Leadership Exposure &amp; Employee Engagement</li>
      <li>Event Management &amp; Talent Development Initiatives</li>
    </ul>
  </section>

  <section>
    <h2>🌍 Key Achievements at CIMB</h2>
    <table>
      <tr><th>🎉 Highlight</th><th>💡 Description</th></tr>
      <tr><td>🏆 Employer Branding (MCTF Career Fair)</td><td>Represented the HR team at the Malaysia Career &amp; Training Fair, engaging 5,000+ attendees and promoting CIMB as a top employer.</td></tr>
      <tr><td>💼 Recruitment Drive (Walk-In Interviews)</td><td>Executed a high-volume hiring event, closing 40+ positions within a week.</td></tr>
      <tr><td>🏢 CIMB Hub Grand Launch</td><td>Supported planning and HR presence for the grand opening attended by senior management and media partners.</td></tr>
      <tr><td>👥 CEO Engagement</td><td>Met Dato’ Abdul Rahman, CEO of CIMB, in recognition of HRBP team contributions.</td></tr>
      <tr><td>🌿 Employee Wellness (Chill Out Session)</td><td>Organized HRBP team sessions to boost morale and team culture.</td></tr>
      <tr><td>🏅 CIMB HR Asia Award</td><td>Contributed to CIMB winning Best Company to Work For in Asia 2022.</td></tr>
    </table>
  </section>

  <section>
    <h2>🖼️ Career Highlights Gallery</h2>
    <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/Employer%20Branding%20(MCTF%20Career%20Fair).jpg?raw=true" width="360" alt="Employer Branding at MCTF Career Fair">
    <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/MCTF%20career%20fair%20second%20picture.jpg?raw=true" width="360" alt="Career Fair second picture">
    <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/CEO%20Engagement.jpg?raw=true" width="360" alt="CEO Engagement">
    <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/Recruitment%20Drive%20(Walk-In%20Interviews).jpg?raw=true" width="360" alt="Walk-In Interview">
    <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/Potluck.jpg?raw=true" width="360" alt="Potluck Session">
    <p><i>✨ Each image reflects the people, passion, and purpose behind every milestone achieved with #teamCIMB.</i></p>
  </section>

  <section>
    <h2>📊 Supporting Project — Power BI HR Dashboard</h2>
    <p>Built Power BI dashboards for data-driven HR insights visualizing:</p>
    <ul>
      <li>Placement performance &amp; FACT Index trends</li>
      <li>Specialist efficiency &amp; recruitment outcomes</li>
    </ul>
    <p>
      📎 <a href="https://github.com/mohamadazlanwork/Powerbi_Dashboard" target="_blank">View Repository</a><br/>
      📊 <a href="https://mohamadazlanwork.github.io/Powerbi_Dashboard/" target="_blank">View Live Dashboard</a>
    </p>
  </section>

  <section>
    <h3>⚙️ Tools &amp; Skills</h3>
    <p>Power BI · Zoho Recruit · Excel · Employer Branding · Data Analytics · HRBP Collaboration</p>
    <br/>
    <a href="https://github.com/mohamadazlanwork/Cimb" target="_blank"><button class="btn">Open GitHub Project</button></a>
  </section>

  <p style="margin-top:1rem;">💡 <i>“Bridging HR and Analytics to empower data-driven talent transformation.”</i></p>
</div>

<script>
/* --- particles --- */
const pc=document.getElementById('particles-container');const count=80;for(let i=0;i<count;i++)makeP();
function makeP(){const p=document.createElement('div');p.className='particle';const s=Math.random()*3+1;p.style.width=`${s}px`;p.style.height=`${s}px`;reset(p);pc.appendChild(p);move(p);}
function reset(p){const x=Math.random()*100,y=Math.random()*100;p.style.left=`${x}%`;p.style.top=`${y}%`;p.style.opacity='0';return{x,y};}
function move(p){const pos=reset(p);const dur=Math.random()*10+10,del=Math.random()*5;setTimeout(()=>{p.style.transition=`all ${dur}s linear`;p.style.opacity=Math.random()*0.3+0.1;const mx=pos.x+(Math.random()*20-10),my=pos.y-Math.random()*30;p.style.left=`${mx}%`;p.style.top=`${my}%`;setTimeout(()=>move(p),dur*1000);},del*1000);}
document.addEventListener('mousemove',e=>{const x=(e.clientX/window.innerWidth)*100,y=(e.clientY/window.innerHeight)*100;const p=document.createElement('div');p.className='particle';const s=Math.random()*4+2;p.style.width=`${s}px`;p.style.height=`${s}px`;p.style.left=`${x}%`;p.style.top=`${y}%`;p.style.opacity='0.6';pc.appendChild(p);setTimeout(()=>{p.style.transition='all 2s ease-out';p.style.left=`${x+(Math.random()*10-5)}%`;p.style.top=`${y+(Math.random()*10-5)}%`;p.style.opacity='0';setTimeout(()=>p.remove(),2000);},10);});
</script>
</body>
</html>
