<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:-apple-system,'Segoe UI',sans-serif;background:#0d1117;color:#c9d1d9;font-size:14px}
.wrap{max-width:880px;margin:0 auto;padding-bottom:40px}
.sec{padding:20px 20px 0}
.sec-title{font-size:13px;font-weight:700;color:#00C4FF;text-transform:uppercase;letter-spacing:1.2px;padding-bottom:8px;border-bottom:1px solid #1a3a6b;margin-bottom:14px}

/* HERO */
.hero{background:linear-gradient(135deg,#0a1628,#0d2040,#0a1628);padding:30px;text-align:center;border-radius:10px}
.hero h1{font-size:2rem;color:#fff}
.hero h1 span{color:#00C4FF}
.hero .sub{color:#9fbad6;font-size:.85rem;margin-top:5px}
.typing{color:#00C4FF;font-family:monospace;font-size:.9rem;margin:10px 0}

/* BADGES */
.badge-row{display:flex;gap:7px;justify-content:center;flex-wrap:wrap;margin-top:10px}
.badge{padding:5px 10px;border-radius:15px;font-size:.7rem;border:1px solid #30363d}

/* FLEX FIX */
.about-grid{display:flex;flex-wrap:wrap;gap:14px}

/* CODE BLOCK */
.code-blk{
  flex:1;
  min-width:280px;
  background:#161b22;
  border:1px solid #21262d;
  border-radius:10px;
  padding:14px;
  font-family:monospace;
  font-size:.72rem;
  overflow-x:auto;
}

/* RIGHT SIDE */
.right-col{
  flex:1;
  min-width:220px;
  display:flex;
  flex-direction:column;
  align-items:center;
  gap:10px;
}

/* STATS */
.stat-pill{
  background:#161b22;
  border:1px solid #21262d;
  border-radius:8px;
  padding:8px;
  text-align:center;
  width:100%;
}
.num{color:#00C4FF;font-weight:800}
.lbl{font-size:.7rem;color:#8b949e}

/* SIMPLE CARDS */
.card{
  background:#161b22;
  border:1px solid #21262d;
  border-radius:8px;
  padding:10px;
  margin-bottom:10px;
}

.quote{
  background:#161b22;
  border-left:3px solid #00C4FF;
  padding:10px;
  margin-top:20px;
  font-style:italic;
  color:#9fbad6;
  border-radius:0 8px 8px 0;
}

.footer{text-align:center;margin-top:20px;color:#8b949e;font-size:.8rem}
</style>

<div class="wrap">

<!-- HERO -->
<div class="hero">
  <h1><span>Mano Shruthi S</span></h1>
  <div class="sub">AI & Data Science Engineer · GenAI Builder</div>
  <div class="typing">Building AI that solves real problems 🤖</div>

  <div class="badge-row">
    <span class="badge">IIT Kharagpur Intern</span>
    <span class="badge">Oracle GenAI Certified</span>
    <span class="badge">NPTEL Top 5%</span>
    <span class="badge">4 Internships</span>
  </div>
</div>

<!-- ABOUT -->
<div class="sec">
  <div class="sec-title">🧠 About Me</div>

  <div class="about-grid">

    <div class="code-blk">
<pre>
class ManoShruthiS:
  degree = "B.E AI & Data Science"
  year = "3rd Year"
  cgpa = "7.85"
  location = "India"

  def skills(self):
    return [
      "AI & ML",
      "Data Science",
      "Cybersecurity",
      "Full Stack"
    ]

  def mindset(self):
    return "Build. Execute. Improve."
</pre>
    </div>

    <div class="right-col">
      <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="220">

      <div class="stat-pill">
        <div class="num">4</div>
        <div class="lbl">Internships</div>
      </div>

      <div class="stat-pill">
        <div class="num">2</div>
        <div class="lbl">Projects</div>
      </div>

      <div class="stat-pill">
        <div class="num">Top 5%</div>
        <div class="lbl">NPTEL Rank</div>
      </div>

    </div>

  </div>
</div>

<!-- EXPERIENCE -->
<div class="sec">
  <div class="sec-title">💼 Experience</div>

  <div class="card">Generative AI Intern — Sure Trust</div>
  <div class="card">Research Intern — IIT Kharagpur</div>
  <div class="card">Cybersecurity Intern — Edu Tantr</div>
  <div class="card">Data Science Intern — Techvolt</div>
</div>

<!-- PROJECTS -->
<div class="sec">
  <div class="sec-title">🚀 Projects</div>

  <div class="card"><b>VeriIntern AI</b> — Internship fraud detection system</div>
  <div class="card"><b>ExecuStra</b> — Goal execution system</div>
</div>

<!-- SKILLS -->
<div class="sec">
  <div class="sec-title">🛠️ Skills</div>

  <div class="card">Python · ML · NLP · SQL · React · Flask · Cybersecurity</div>
</div>

<!-- QUOTE -->
<div class="quote">
"Don't just learn it. Build it. Prove it."
</div>

<div class="footer">
AI · Data · Discipline
</div>

</div>
