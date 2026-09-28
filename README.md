# KajalUdhani.com
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Kajal Udhani — Learning Experience Designer</title>
<meta name="description" content="Portfolio of Kajal Udhani — learning experience designer, educator and author.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,400;0,9..144,500;0,9..144,600;0,9..144,700;1,9..144,500&family=Literata:ital,opsz,wght@0,7..72,400;0,7..72,500;1,7..72,400&display=swap" rel="stylesheet">
<style>
  :root {
    --paper: #FAF7EF;
    --paper-2: #F1ECDD;
    --ink: #1E2118;
    --ink-soft: #565B4C;
    --moss: #33502B;
    --moss-tint: #E7EEDF;
    --ochre: #A9691F;
    --ochre-tint: #F3E4CE;
    --rust: #8C4A2F;
    --rust-tint: #F1E1D6;
    --blue: #2E4A5C;
    --blue-tint: #E1E9EC;
    --hair: #D8D0B8;
    --font-body: 'Literata', Georgia, serif;
    --font-display: 'Fraunces', Georgia, serif;
    box-sizing: border-box;
    padding-top: env(safe-area-inset-top, 0px);
    padding-bottom: env(safe-area-inset-bottom, 0px);
  }
  html { scroll-behavior: smooth; scroll-padding-top: env(safe-area-inset-top, 0px); }
  @media (prefers-color-scheme: dark) {
    :root:not([data-theme="light"]) {
      --paper: #17190F; --paper-2: #1E2115; --ink: #EDE8D6; --ink-soft: #B7B29B;
      --moss: #8FBF7C; --moss-tint: #202A1A; --ochre: #E0A85B; --ochre-tint: #2B2418; --rust: #D48F6E; --rust-tint: #2E2018;
      --blue: #8FB3C6; --blue-tint: #1B242A; --hair: #383726;
    }
  }
  :root[data-theme="dark"] {
    --paper: #17190F; --paper-2: #1E2115; --ink: #EDE8D6; --ink-soft: #B7B29B;
    --moss: #8FBF7C; --moss-tint: #202A1A; --ochre: #E0A85B; --ochre-tint: #2B2418; --rust: #D48F6E; --rust-tint: #2E2018;
    --blue: #8FB3C6; --blue-tint: #1B242A; --hair: #383726;
  }
  * { box-sizing: border-box; }
  body { margin: 0; background: var(--paper); color: var(--ink); font-family: var(--font-body); font-size: 17px; line-height: 1.64; }
  a { color: var(--ochre); }
  .wrap { display: flex; max-width: 1180px; margin: 0 auto; }

  nav.spine {
    position: sticky; top: env(safe-area-inset-top, 0px); align-self: flex-start;
    width: 210px; flex-shrink: 0; padding: 3rem 1.4rem 2rem 0; border-right: 1px solid var(--hair);
    height: 100vh; height: 100dvh; display: flex; flex-direction: column; justify-content: space-between;
  }
  .spine-top .mark { font-family: var(--font-display); font-weight: 700; font-size: 1.4rem; line-height: 1.1; }
  .spine-top .role { font-size: 0.8rem; color: var(--ink-soft); margin-top: 0.5rem; }
  .spine ol { list-style: none; margin: 2.2rem 0 0; padding: 0; }
  .spine ol li { margin-bottom: 0.85rem; }
  .spine ol a { text-decoration: none; color: var(--ink-soft); font-size: 0.93rem; display: flex; gap: 0.6rem; align-items: baseline; }
  .spine ol a .num { font-family: var(--font-display); font-style: italic; color: var(--hair); }
  .spine ol a:hover, .spine ol a:focus-visible { color: var(--ochre); }
  .spine ol a:hover .num { color: var(--ochre); }
  .spine-bottom { font-size: 0.78rem; color: var(--ink-soft); }
  .spine-bottom a { color: var(--ink-soft); }

  main { flex: 1; min-width: 0; padding: 0 0 5rem; }

  /* ---- Hero / cool intro ---- */
  .hero { padding: 3.4rem 2.4rem 3rem; border-bottom: 1px solid var(--hair); }
  .hero-top { display: flex; align-items: center; gap: 1rem; margin-bottom: 0.6rem; }
  .seal { width: 52px; height: 52px; color: var(--moss); flex-shrink: 0; }
  .hero .kicker { font-family: var(--font-display); font-style: italic; color: var(--moss); font-size: 1.05rem; }
  .hero h1 {
    font-family: var(--font-display); font-weight: 700; font-size: clamp(2.4rem, 6vw, 4rem);
    line-height: 1.02; margin: 0 0 1.1rem; max-width: 16ch; letter-spacing: -0.01em;
  }
  .hero p.deck { max-width: 58ch; font-size: 1.12rem; color: var(--ink-soft); margin: 0 0 1.6rem; }
  .hero .stats { display: flex; flex-wrap: wrap; gap: 1.8rem; margin-top: 1.6rem; }
  .hero .stats div b { display: block; font-family: var(--font-display); font-weight: 700; font-size: 1.5rem; color: var(--moss); }
  .hero .stats div span { font-size: 0.8rem; color: var(--ink-soft); }
  .hero .contact { margin-top: 1.8rem; font-size: 0.86rem; color: var(--ink-soft); }
  .hero .contact span { margin-right: 1.1rem; }

  section.chapter { max-width: 74ch; padding: 3rem 2.4rem 0; }
  section.chapter:last-of-type { padding-bottom: 3rem; }
  .chapter-head { display: flex; align-items: baseline; gap: 0.9rem; margin-bottom: 1.4rem; }
  .chapter-head .roman { font-family: var(--font-display); font-style: italic; font-weight: 500; font-size: 1.6rem; color: var(--hair); }
  .chapter-head h2 { font-family: var(--font-display); font-weight: 600; font-size: 1.55rem; margin: 0; }

  ul.credentials { list-style: none; margin: 0; padding: 0; }
  ul.credentials li { padding: 0.9rem 0; border-bottom: 1px dotted var(--hair); display: grid; grid-template-columns: 30px 1fr; gap: 0.8rem; align-items: baseline; }
  ul.credentials li:last-child { border-bottom: none; }
  ul.credentials .badge { width: 22px; height: 22px; border: 1.5px solid var(--ochre); border-radius: 50%; position: relative; top: 3px; }
  ul.credentials b { font-weight: 700; }

  /* experience + nested programmes */
  .role {
    margin: 2.6rem 0 3.4rem; padding: 2rem 1.7rem 1.7rem 1.9rem; position: relative;
    background-color: var(--paper);
    background-image: repeating-linear-gradient(135deg, var(--tab-tint) 0px, var(--tab-tint) 2px, transparent 2px, transparent 11px);
    border: 1px solid var(--hair); display: flex; gap: 1.6rem; align-items: flex-start; flex-wrap: wrap;
  }
  .role::before {
    content: attr(data-index); position: absolute; top: 0.5rem; right: 1.2rem;
    font-family: var(--font-display); font-weight: 700; font-size: 4rem; line-height: 1;
    color: var(--tab, var(--moss)); opacity: 0.12; pointer-events: none;
  }
  .role .folder-tab {
    position: absolute; top: -16px; left: 1.5rem; background: var(--tab, var(--moss)); color: var(--paper);
    font-family: var(--font-display); font-weight: 700; font-size: 0.78rem; letter-spacing: 0.02em;
    padding: 5px 16px 7px; clip-path: polygon(8% 0, 92% 0, 100% 100%, 0% 100%);
  }
  .role:nth-of-type(1) { --tab: var(--moss); --tab-tint: var(--moss-tint); }
  .role:nth-of-type(2) { --tab: var(--rust); --tab-tint: var(--rust-tint); }
  .role:nth-of-type(3) { --tab: var(--blue); --tab-tint: var(--blue-tint); }
  .role .role-main { flex: 1; min-width: 240px; }
  .role-head { display: flex; flex-wrap: wrap; align-items: baseline; justify-content: space-between; gap: 0.4rem 1rem; position: relative; }
  .role-head h3 { font-family: var(--font-display); font-size: 1.3rem; font-weight: 700; margin: 0; }
  .role-head .org { color: var(--tab, var(--moss)); font-size: 0.95rem; font-weight: 600; }
  .role-head .dates { font-size: 0.82rem; color: var(--ink-soft); white-space: nowrap; }
  .role ul.bullets { margin: 0.8rem 0 0; padding-left: 1.15rem; position: relative; }
  .role ul.bullets li { margin-bottom: 0.4rem; }

    position: absolute; inset: 0; display: flex; align-items: center; justify-content: center;
    opacity: 0; animation: slideFade 9s infinite;
  }

    aspect-ratio: 4/3; border: 1px solid var(--hair); display: flex; align-items: center; justify-content: center;
    margin-bottom: 0.65rem; color: var(--tab, var(--moss)); background: var(--paper-2);
  }

  .edu-item { margin-bottom: 1.1rem; }
  .edu-item h3 { font-family: var(--font-display); font-size: 1.05rem; font-weight: 600; margin: 0 0 0.15rem; }
  .edu-item .school { color: var(--moss); font-size: 0.92rem; }
  .edu-item .gpa { font-size: 0.82rem; color: var(--ink-soft); }
  .tags { display: flex; flex-wrap: wrap; gap: 0.6rem; margin-top: 0.8rem; }
  .tags span { border: 1px solid var(--hair); padding: 0.35rem 0.75rem; font-size: 0.85rem; color: var(--ink-soft); background: var(--paper-2); }

  footer.colophon { max-width: 74ch; margin-top: 1rem; padding: 2rem 2.4rem 3rem; border-top: 1px solid var(--hair); font-size: 0.85rem; color: var(--ink-soft); }
  footer.colophon a { color: var(--moss); }

  .mobile-nav { display: none; }
  @media (max-width: 860px) {
    nav.spine { display: none; }
    .mobile-nav {
      display: flex; gap: 1.1rem; overflow-x: auto; padding: 0.9rem 1.4rem; border-bottom: 1px solid var(--hair);
      position: sticky; top: env(safe-area-inset-top, 0px); background: var(--paper); z-index: 5; -webkit-overflow-scrolling: touch;
    }
    .mobile-nav a { font-size: 0.82rem; color: var(--ink-soft); text-decoration: none; white-space: nowrap; }
    .hero, section.chapter, footer.colophon { padding-left: 1.3rem; padding-right: 1.3rem; }
  }

  .hero-grid { display: flex; gap: 2.4rem; align-items: flex-start; flex-wrap: wrap; }
  .hero-text { flex: 1; min-width: 280px; }
  .portrait { width: 230px; flex-shrink: 0; padding: 10px 10px 30px; background: var(--paper-2); border: 1px solid var(--hair); box-shadow: 0 8px 18px rgba(0,0,0,.12); transform: rotate(2.5deg); position: relative; margin-top: .4rem; }
  .portrait::before { content: ""; position: absolute; top: -10px; left: 50%; width: 70px; height: 20px; transform: translateX(-50%) rotate(-3deg); background: var(--moss); opacity: .45; }
  .portrait img { width: 100%; aspect-ratio: 4/5; object-fit: cover; object-position: 30% 20%; display: block; }
  .portrait span { display: block; text-align: center; margin-top: 8px; font-family: var(--font-display); font-style: italic; font-size: .9rem; color: var(--ink-soft); }
  .words { display: flex; flex-wrap: wrap; gap: .5rem; margin: 0 0 1.2rem; }
  .words span { border: 1px solid var(--moss); color: var(--moss); padding: .2rem .8rem; border-radius: 99px; font-size: .85rem; }
  .certs { display: flex; gap: 1.2rem; flex-wrap: wrap; margin-top: 1.6rem; }
  .certs figure { margin: 0; flex: 1 1 200px; }
  .certs img { width: 100%; height: 190px; object-fit: contain; background: var(--paper-2); border: 1px solid var(--hair); padding: 6px; }
  .certs figcaption { font-size: .78rem; color: var(--ink-soft); margin-top: .35rem; }
  section.chapter.wide { max-width: 980px; }
  .role .role-main { flex: 1 1 300px; }
  .carousel { flex: 0 0 340px; max-width: 100%; position: relative; }
  .carousel .track { display: flex; overflow-x: auto; scroll-snap-type: x mandatory; scrollbar-width: none; border: 1px solid var(--hair); background: var(--paper-2); box-shadow: 0 6px 14px rgba(0,0,0,.1); }
  .carousel .track::-webkit-scrollbar { display: none; }
  .carousel figure { flex: 0 0 100%; margin: 0; scroll-snap-align: center; position: relative; aspect-ratio: 4/3; }
  .carousel img { width: 100%; height: 100%; object-fit: cover; display: block; }
  .carousel figcaption { position: absolute; left: 0; right: 0; bottom: 0; padding: 1.6rem .8rem .55rem; font-size: .78rem; color: #fff; background: linear-gradient(transparent, rgba(0,0,0,.72)); }
  .carousel .dots { display: flex; justify-content: center; gap: 6px; margin-top: .6rem; }
  .carousel .dots i { width: 6px; height: 6px; border-radius: 50%; background: var(--hair); transition: all .25s; }
  .carousel .dots i.on { background: var(--tab); width: 18px; border-radius: 4px; }
  .role h5 { font-family: var(--font-display); font-size: .95rem; margin: 1rem 0 .2rem; color: var(--tab); }
  .role p.prog { margin: 0; font-size: .88rem; color: var(--ink-soft); }
  @media (max-width: 760px) { .role { flex-direction: column-reverse; } .carousel { flex-basis: auto; width: 100%; } .portrait { transform: rotate(1.5deg); width: 190px; } }
</style>

<style>
  .certs { align-items: flex-start; }
  .cert-card { min-width: 200px; }
  .cert-placeholder {
    width: 100%; height: 190px; display: grid; place-items: center;
    text-align: center; font-family: var(--font-display); font-size: 1.25rem;
    color: var(--tab, var(--moss)); background: var(--paper-2);
    border: 1px solid var(--hair); padding: 1rem;
  }
  .spine a[aria-current="page"], .mobile-nav a[aria-current="page"] { color: var(--ochre); }
  .spine a[aria-current="page"] .num { color: var(--ochre); }
  @media (max-width: 760px) {
    .role { padding-top: 2.2rem; }
    .role-main { width: 100%; }
  }
</style>

</head>
<body>

<div class="mobile-nav">
  <a href="#intro">Intro</a>
  <a href="#credentials">Credentials</a>
  <a href="#experience">Experience</a>
  <a href="#education">Education</a>
  <a href="#contact">Contact</a>
</div>

<div class="wrap">
  <nav class="spine">
    <div class="spine-top">
      <div class="mark">Kajal<br>Udhani</div>
      <div class="role">Learning Experience Designer</div>
      <ol>
        <li><a href="#intro"><span class="num">I</span> Intro</a></li>
        <li><a href="#credentials"><span class="num">II</span> Credentials</a></li>
        <li><a href="#experience"><span class="num">III</span> Experience</a></li>
        <li><a href="#education"><span class="num">IV</span> Education</a></li>
        <li><a href="#contact"><span class="num">V</span> Contact</a></li>
      </ol>
    </div>
    <div class="spine-bottom">Ahmedabad, Gujarat<br><a href="https://www.linkedin.com/in/kajaludhani">LinkedIn ↗</a></div>
  </nav>

  <main>
    <section class="hero" id="intro">
      <div class="hero-grid">
        <div class="hero-text">
          <div class="hero-top"><div class="seal" aria-hidden="true"><svg viewBox="0 0 100 100"><circle cx="50" cy="50" r="46" fill="none" stroke="currentColor" stroke-width="1.5"/><circle cx="50" cy="50" r="38" fill="none" stroke="currentColor" stroke-width="1"/><text x="50" y="58" text-anchor="middle" font-family="Fraunces, serif" font-weight="700" font-size="30" fill="currentColor">KU</text></svg></div><div class="kicker">hello, I'm Kajal, learning experience designer and author</div></div>
          <h1>Curiosity, built into a curriculum.</h1>
          <div class="words"><span>Inclusive</span><span>Team player</span><span>Nurturing</span><span>Storyteller</span></div>
          <p class="deck">I design the experiences that sit between a syllabus and a student's real understanding of it: career festivals, entrepreneurship programmes, MUN partnerships, robotics electives. Trained as a zoologist, certified to teach Cambridge Biology, now building programmes for grades 7 to 12 across schools and foundations in Gujarat, Rajasthan and Maharashtra.</p>
          <div class="stats"><div><b>3,500+</b><span>students reached</span></div><div><b>27</b><span>experts, one Career Fest</span></div><div><b>130+</b><span>teacher observations</span></div><div><b>9th</b><span>globally, CENTA Biology Olympiad</span></div></div>
          <div class="contact"><span>Ahmedabad, Gujarat</span><span>kajaludhani7@gmail.com</span><span>+91 9824050995</span><span>@KajalUdhani</span></div>
        </div>
        <div class="portrait"><img src="data:image/jpeg;base64,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" alt="Kajal Udhani speaking"><span>Storyteller</span></div>
      </div>
    </section>

    <section class="chapter" id="credentials">
      <div class="chapter-head"><span class="roman">II</span><h2>Credentials</h2></div>
      <ul class="credentials">
        <li><span class="badge"></span><div><b>Ranked 9th globally</b> in Secondary School Biology, CENTA International Teaching Professionals' Olympiad</div></li>
        <li><span class="badge"></span><div><b>Winner</b>, Reliance Foundation Teacher Award, for excellence and impact in teaching and education</div></li>
        <li><span class="badge"></span><div><b>CTET Certified</b>, Central Teacher Eligibility Test, 2021</div></li>
        <li><span class="badge"></span><div><b>Published author</b>: two internationally published e-books and one traditionally published book in India</div></li>
      </ul>
      <div class="certs">
        <figure class="cert-card">
          <div class="cert-placeholder">Award<br>Certificate</div>
          <figcaption>CENTA International Teaching Professionals' Olympiad — Secondary School Biology</figcaption>
        </figure>
        <figure class="cert-card">
          <div class="cert-placeholder">Teacher<br>Award</div>
          <figcaption>Reliance Foundation Teacher Award</figcaption>
        </figure>
      </div>
    </section>

    <section class="chapter wide" id="experience">
      <div class="chapter-head"><span class="roman">III</span><h2>Experience</h2></div>

      <article class="role" data-index="01">
        <div class="folder-tab">LEARNING EXPERIENCE DESIGN</div>
        <div class="role-main">
          <div class="role-head">
            <h3>Curriculum &amp; Academic Programmes</h3>
            <span class="org">Redbricks Group of Schools</span>
            <span class="dates">2025 — present</span>
          </div>
          <ul class="bullets">
            <li>Designs and coordinates learning experiences across Grades 7–12, connecting curriculum with careers, leadership, entrepreneurship and real-world application.</li>
            <li>Pitched, designed, planned and implemented a Career Fest with <b>27 experts</b> across fields including ISRO, robotics, architecture and law; coordinated a team of <b>15</b>.</li>
            <li>Structured the Career Cell across Grades 7–12 through expert conversations, aptitude exploration, Ikigai, self-reflection and collaboration with the school counsellor.</li>
            <li>Designed a year-long Grade 7–8 Entrepreneurship &amp; Environment project using design thinking, bio-inspired products and brand reimagination.</li>
            <li>Coordinates MUN and debate programmes, facilitator meetings, culminating experiences and 21st-century skills assessment initiatives.</li>
          </ul>
          <h5>Also</h5>
          <p class="prog">Teacher observation and feedback · lesson-plan quality tracking · assessment coordination · resources · pedagogy workshops · community-service partnerships.</p>
        </div>
      </article>

      <article class="role" data-index="02">
        <div class="folder-tab">SCIENCE EDUCATION</div>
        <div class="role-main">
          <div class="role-head">
            <h3>Science Educator</h3>
            <span class="org">The Riverside School</span>
            <span class="dates">Earlier experience</span>
          </div>
          <ul class="bullets">
            <li>Taught Biology and Science for Grades 8–10 with project-based and inquiry-led approaches.</li>
            <li>Developed curriculum, learning resources and classroom experiences designed to move students beyond content recall.</li>
            <li>Supported microscopy, student projects and hands-on learning while coordinating academic routines and assessment preparation.</li>
          </ul>
        </div>
      </article>

      <article class="role" data-index="03">
        <div class="folder-tab">EDUCATION · INNOVATION</div>
        <div class="role-main">
          <div class="role-head">
            <h3>Educator, Author &amp; Learning Designer</h3>
            <span class="org">Independent / Collaborative Work</span>
            <span class="dates">Ongoing</span>
          </div>
          <ul class="bullets">
            <li>Built education programmes spanning STEM, robotics, AI, coding, career exploration, teacher development and student-led projects.</li>
            <li>Founded Swabotics to explore accessible robotics and maker-based learning for students and educators.</li>
            <li>Published two internationally released e-books and one traditionally published book in India.</li>
            <li>Judged robotics and coding competitions and contributed to teacher-training and educational innovation initiatives.</li>
          </ul>
        </div>
      </article>
    </section>

    <section class="chapter" id="education">
      <div class="chapter-head"><span class="roman">IV</span><h2>Education</h2></div>
      <div class="edu-item">
        <h3>M.Sc. / Zoology &amp; Life Sciences</h3>
        <div class="school">Academic foundation in biology, zoology and scientific inquiry</div>
      </div>
      <div class="edu-item">
        <h3>Cambridge Biology Educator</h3>
        <div class="school">Teaching and curriculum practice across school contexts</div>
      </div>
      <div class="edu-item">
        <h3>Central Teacher Eligibility Test</h3>
        <div class="school">CTET Certified · 2021</div>
      </div>
      <div class="tags">
        <span>Curriculum Design</span><span>Learning Experience Design</span><span>Project-Based Learning</span>
        <span>STEM</span><span>Career Education</span><span>Teacher Development</span><span>Biology</span>
      </div>
    </section>

    <footer class="colophon" id="contact">
      <strong>Let's build something students remember.</strong><br>
      Ahmedabad, Gujarat · <a href="mailto:kajaludhani7@gmail.com">kajaludhani7@gmail.com</a> ·
      <a href="https://www.linkedin.com/in/kajaludhani" target="_blank" rel="noopener">LinkedIn ↗</a>
      <br><br>
      <span>© 2026 Kajal Udhani</span>
    </footer>
  </main>
</div>

<script>
  // Small quality-of-life enhancements; the page remains fully usable without JavaScript.
  const sections = [...document.querySelectorAll('main section[id], footer[id]')];
  const navLinks = [...document.querySelectorAll('.spine a, .mobile-nav a')];

  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (!entry.isIntersecting) return;
      navLinks.forEach(a => a.removeAttribute('aria-current'));
      navLinks.filter(a => a.getAttribute('href') === '#' + entry.target.id)
        .forEach(a => a.setAttribute('aria-current', 'page'));
    });
  }, { rootMargin: '-35% 0px -55% 0px', threshold: 0 });

  sections.forEach(section => observer.observe(section));
</script>
</body>
</html>
