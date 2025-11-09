<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CIMB HR Highlights (2022–2023) – Mohamad Azlan</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;}
body{
  font-family:'Poppins',sans-serif;
  background:linear-gradient(135deg,#A50034,#33000d);
  color:#fff;
  overflow-y:auto;
  padding:40px 60px;
}
h1{
  color:#FFD700;
  font-size:2.3rem;
  text-shadow:0 0 15px rgba(255,215,0,.6);
  margin-bottom:15px;
  text-align:center;
}
h2{
  color:#ffedb3;
  font-size:1.3rem;
  margin-top:20px;
  margin-bottom:8px;
  text-shadow:0 0 10px rgba(255,215,0,.4);
}
p,li{
  font-size:1rem;
  line-height:1.7;
  color:#f5f5f5;
}
ul{margin-top:8px;margin-left:1.2rem;}
li{margin-bottom:6px;}

/* ===== GALLERY ===== */
.gallery{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  grid-template-rows:repeat(2,1fr);
  gap:14px;
  width:100%;
  height:auto;
  margin-bottom:25px;
}
.gallery img{
  width:100%;
  height:280px;
  object-fit:cover;
  border-radius:10px;
  box-shadow:0 0 14px rgba(255,215,0,.3);
  cursor:pointer;
  transition:transform .4s ease,box-shadow .4s ease;
}
.gallery img:hover{
  transform:scale(1.05);
  box-shadow:0 0 25px rgba(255,215,0,.7);
}

/* ===== LIGHTBOX ===== */
#lightbox{
  position:fixed;top:0;left:0;width:100%;height:100%;
  background:rgba(0,0,0,0.9);
  display:flex;align-items:center;justify-content:center;
  visibility:hidden;opacity:0;
  transition:opacity .4s ease;
  z-index:9999;
}
#lightbox.active{visibility:visible;opacity:1;}
#lightbox img{
  max-width:90%;max-height:90%;
  border:3px solid #FFD700;border-radius:12px;
  box-shadow:0 0 35px rgba(255,215,0,.8);
  animation:zoomIn .4s ease;
}
#lightbox::after{
  content:"×";
  position:absolute;
  top:20px;right:40px;
  font-size:2.5rem;
  color:#FFD700;
  cursor:pointer;
}
@keyframes zoomIn{
  from{transform:scale(.7);opacity:0;}
  to{transform:scale(1);opacity:1;}
}

/* ===== FOOTER ===== */
footer{
  text-align:center;
  margin-top:50px;
  font-size:.9rem;
  color:#ddd;
  text-shadow:0 0 5px rgba(255,215,0,.3);
  padding-bottom:20px;
}
</style>
</head>

<body>
<h1>CIMB HR Portfolio – Mohamad Azlan</h1>

<h2>Career Highlights Gallery</h2>
<div class="gallery">
  <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/Employer%20Branding%20(MCTF%20Career%20Fair).jpg?raw=true" alt="Employer Branding">
  <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/MCTF%20career%20fair%20second%20picture.jpg?raw=true" alt="MCTF Career Fair">
  <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/CEO%20Engagement.jpg?raw=true" alt="CEO Engagement">
  <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/Recruitment%20Drive%20(Walk-In%20Interviews).jpg?raw=true" alt="Recruitment Drive">
  <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/Potluck.jpg?raw=true" alt="Potluck Event">
  <img src="https://github.com/mohamadazlanwork/Cimb/blob/main/CIMB/CIMB%20Grand%20Launching.jpeg?raw=true" alt="CIMB Grand Launch">
</div>

<h2>📋 Brief Overview</h2>
<p>During my tenure with <strong>CIMB Group</strong> (2022–2023) as an HR Business Partner under Group Operations, I contributed to impactful HR initiatives that enhanced recruitment efficiency, employee engagement, and employer branding. My role spanned leadership engagement, wellness programs, and operational excellence within HR.</p>

<h2>🏆 Key Contributions</h2>
<ul>
  <li><strong>Employer Branding:</strong> Represented CIMB at the Malaysia Career & Training Fair (MCTF), engaging over 5,000 visitors to promote CIMB as a top employer.</li>
  <li><strong>Walk-In Recruitment Drive:</strong> Coordinated large-scale interviews, achieving over 40 successful hires in a single week.</li>
  <li><strong>Leadership Engagement:</strong> Supported CEO and leadership participation in HR events, strengthening internal visibility and collaboration.</li>
  <li><strong>Employee Culture & Wellness:</strong> Organized Chill-Out sessions, potluck gatherings, and well-being activities to foster a strong workplace culture.</li>
  <li><strong>CIMB Hub Grand Launch:</strong> Represented HR at the official HQ opening event alongside the executive team and media partners.</li>
  <li><strong>Recognition:</strong> Contributed to CIMB winning the “Best Company to Work For in Asia 2022” award by HR Asia.</li>
</ul>

<h2>🧭 Reflection</h2>
<p>My experience at CIMB was transformative — balancing strategic HR execution with meaningful human connection. I learned to align people initiatives with measurable business impact while fostering a culture of collaboration and well-being.</p>

<footer>© 2025 HR Portfolio | Mohamad Azlan | CIMB Group</footer>

<div id="lightbox"></div>

<script>
const images=document.querySelectorAll('.gallery img');
const lightbox=document.getElementById('lightbox');
images.forEach(img=>{
  img.addEventListener('click',()=>{
    lightbox.innerHTML=`<img src="${img.src}" alt="">`;
    lightbox.classList.add('active');
  });
});
lightbox.addEventListener('click',()=>lightbox.classList.remove('active'));
</script>
</body>
</html>
