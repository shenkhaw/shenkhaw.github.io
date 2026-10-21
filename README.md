<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Shen Khaw</title>
<meta name="description" content="Shen Khaw: aspiring neurobiologist in Penang, Malaysia, working on gene editing, organoids and mechanobiology.">
<meta name="author" content="Shen Khaw">
<link rel="canonical" href="https://shenkhaw.com/">
<meta property="og:type" content="website">
<meta property="og:site_name" content="Shen Khaw">
<meta property="og:title" content="Shen Khaw">
<meta property="og:description" content="Aspiring neurobiologist in Penang, Malaysia, working on gene editing, organoids and mechanobiology.">
<meta property="og:url" content="https://shenkhaw.com/">
<!-- TODO: add your own image at /assets/og.png, then uncomment -->
<!-- <meta property="og:image" content="https://shenkhaw.com/assets/og.png"> -->
<meta name="twitter:card" content="summary">
<link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 16 16'%3E%3Crect width='16' height='16' fill='%2314202b'/%3E%3Cpath d='M8 3l4 2.5v5L8 13l-4-2.5v-5z' fill='none' stroke='%23fff' stroke-width='1.2'/%3E%3C/svg%3E">
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,500;12..96,700&family=Newsreader:ital,opsz,wght@0,6..72,400;0,6..72,500;1,6..72,400&display=swap">
<script>
(function () {
  try {
    var s = localStorage.getItem('theme');
    var p = matchMedia('(prefers-color-scheme: dark)').matches ? 'dark' : 'light';
    if ((s || p) === 'dark') document.documentElement.classList.add('dark');
  } catch (e) {}
})();
</script>
<style>
:root {
  --paper: #eef2f4; --ink: #14202b; --graphite: #546574; --rule: #cbd5dc;
  --accent: #2a4bd7; --card: #f8fafb;
  --display: "Bricolage Grotesque", "Helvetica Neue", Arial, sans-serif;
  --text: "Newsreader", Georgia, "Times New Roman", serif;
  box-sizing: border-box;
  padding-top: env(safe-area-inset-top, 0px);
  padding-bottom: env(safe-area-inset-bottom, 0px);
}
.dark { --paper: #0f161c; --ink: #e6edf2; --graphite: #93a4b2; --rule: #26343f; --accent: #8ea6ff; --card: #151f27; }
*, *::before, *::after { box-sizing: inherit; }
html { scroll-behavior: smooth; scroll-padding-top: 4.5rem; }
@media (prefers-reduced-motion: reduce) { html { scroll-behavior: auto; } }
body {
  margin: 0; background: var(--paper); color: var(--ink); font: 1.125rem/1.65 var(--text);
  background-image: linear-gradient(var(--rule) 1px, transparent 1px), linear-gradient(90deg, var(--rule) 1px, transparent 1px);
  background-size: 32px 32px; background-attachment: fixed;
}
body::before { content: ""; position: fixed; inset: 0; background: var(--paper); opacity: .82; z-index: -1; }
a { color: var(--accent); text-underline-offset: 3px; }
a:focus-visible, button:focus-visible { outline: 3px solid var(--accent); outline-offset: 3px; border-radius: 3px; }
.wrap { max-width: 44rem; margin: 0 auto; padding: 0 1.25rem; }

header.top { position: sticky; top: 0; z-index: 5; background: var(--paper); border-bottom: 1px solid var(--rule); }
header.top .wrap { display: flex; align-items: center; gap: 1.25rem; height: 3.25rem; }
header.top .brand { font: 700 1rem var(--display); color: var(--ink); text-decoration: none; margin-right: auto; }
header.top a.nav { font: 500 .95rem var(--display); color: var(--graphite); text-decoration: none; }
header.top a.nav:hover { color: var(--accent); }
#theme { font: 500 .85rem var(--display); background: none; border: 1px solid var(--rule); color: var(--ink); padding: .25rem .75rem; border-radius: 999px; cursor: pointer; }

.hero { padding: 4.5rem 0 2.5rem; position: relative; }
.hero svg { position: absolute; right: 0; top: 2.5rem; width: 9rem; height: auto; color: var(--accent); opacity: .9; }
h1.hero-name { display: block; max-width: 100%; white-space: nowrap; font: 700 clamp(2.6rem, 11vw, 5.5rem)/1 var(--display); letter-spacing: -.03em; margin: 0 0 1rem; cursor: default; }
h1.hero-name.is-chinese { font-family: "PingFang SC", "Noto Sans SC", "Microsoft YaHei", var(--display), sans-serif; letter-spacing: 0; }
.tag { font: 500 1.05rem var(--display); color: var(--graphite); margin: 0 0 1.5rem; max-width: 24rem; }
.links { display: flex; flex-wrap: wrap; gap: .5rem; padding: 0; margin: 0; list-style: none; }
.links a { display: inline-block; font: 500 .95rem var(--display); padding: .35rem .8rem; border: 1px solid var(--rule); border-radius: 999px; background: var(--card); color: var(--ink); text-decoration: none; }
.links a:hover { border-color: var(--accent); color: var(--accent); }

section { padding: 2.5rem 0; border-top: 1px solid var(--rule); }
h2 { font: 700 1.6rem/1.2 var(--display); letter-spacing: -.01em; margin: 0 0 1rem; }
p { margin: 0 0 1rem; max-width: 38rem; }

.timeline { list-style: none; margin: 0; padding: 0; }
.timeline li { display: grid; grid-template-columns: 6.5rem 1fr; gap: 1rem; padding: 1rem 0; border-top: 1px solid var(--rule); }
.timeline li:first-child { border-top: 0; padding-top: 0; }
.timeline time { font: 500 .95rem var(--display); color: var(--graphite); padding-top: .2rem; }
.timeline h3 { font: 700 1.1rem var(--display); margin: 0 0 .15rem; }
.timeline .where { color: var(--graphite); margin: 0 0 .4rem; }
.timeline ul { margin: 0; padding-left: 1.1rem; }
.timeline ul li { display: list-item; border: 0; padding: 0 0 .3rem; }
.timeline p { margin: 0; color: var(--graphite); }

.cards { display: grid; gap: 1rem; }
.card { background: var(--card); border: 1px solid var(--rule); border-radius: 6px; padding: 1.1rem 1.25rem; }
.card h3 { font: 700 1.15rem var(--display); margin: 0 0 .3rem; }
.card p { margin: 0 0 .6rem; color: var(--graphite); }
.card .meta { font: 500 .9rem var(--display); color: var(--graphite); display: flex; flex-wrap: wrap; gap: .25rem 1rem; }

footer { padding: 2rem 0 3rem; border-top: 1px solid var(--rule); color: var(--graphite); font-size: 1rem; }

@media (max-width: 560px) {
  .hero svg { position: static; display: block; width: 5.5rem; margin-bottom: 1rem; }
  .hero { padding-top: 2.5rem; }
  .timeline li { grid-template-columns: 1fr; gap: .15rem; }
  header.top a.nav.opt { display: none; }
}
</style>
</head>
<body>
<header class="top">
  <div class="wrap">
    <a class="brand" href="#top">Shen Khaw</a>
    <a class="nav" href="#about">About</a>
    <a class="nav" href="#experience">Experience</a>
    <a class="nav opt" href="#projects">Projects</a>
    <button id="theme" type="button">Dark</button>
  </div>
</header>

<main id="top">
  <div class="wrap">
    <div class="hero">
      <svg viewBox="0 0 100 100" fill="none" stroke="currentColor" stroke-width="3" stroke-linejoin="round" aria-hidden="true">
        <path d="M50 8 86 29v42L50 92 14 71V29z"/>
        <path d="M50 22 74 36v28L50 78 26 64V36z" stroke-width="2" stroke-dasharray="4 5"/>
      </svg>
      <h1 id="profile-title" class="hero-name" data-alt="sh3nkhaw" data-chinese="许晟">Shen Khaw</h1>
      <p class="tag">Aspiring neurobiologist in Penang, Malaysia. I work where gene editing, organoids and machine learning meet.</p>
      <ul class="links" aria-label="External links">
        <li><a href="https://github.com/shenkhaw" target="_blank" rel="noopener">GitHub</a></li>
        <li><a href="https://www.linkedin.com/in/khaws/" target="_blank" rel="noopener">LinkedIn</a></li>
        <li><a href="ShenkhawCV.pdf" target="_blank" rel="noopener">Resume</a></li>
        <li><a href="mailto:sh3nkhaw@gmail.com">Email</a></li>
      </ul>
    </div>

    <section id="about">
      <h2>About</h2>
      <p>I want to engineer a vascularized neuroimmune organoid that models sporadic Alzheimer’s disease. The hard parts are the “dead core” that forms when organoids grow without blood vessels, and getting microglia to mature properly. I’m interested in how wet-lab biology, mechanobiology and machine learning can work on both.</p>
      <p>I do remote research with a gene editing and organoid lab in China, and I write code for the analysis side. My longer-term goal is a PhD in regenerative neurobiology.</p>
    </section>

    <section id="experience">
      <h2>Experience</h2>
      <ol class="timeline">
        <li><time>Nov 2026</time><div><h3>Bavi Lab</h3><p class="where">Remote research intern, UNSW and UCLA</p><p>Starting work on the mechanobiology and structural biology of membrane proteins and ion channels.</p></div></li>
        <li><time>Sep 2026 to present</time><div><h3>Research Intern</h3><p class="where">Gene Editing and Organoid Laboratory, Institute of Modern Biology, <a href="https://www.nju.edu.cn/en/" target="_blank" rel="noopener">Nanjing University</a>. Remote, supervised by Peipei Qin.</p>
          <ul>
            <li>Mapping transcriptome-wide off-target analysis workflows for ADAR-mediated RNA editing.</li>
            <li>Studying how A-to-G editing events are identified, filtered and validated using RNA-seq data, to tell credible off-target sites from background noise.</li>
          </ul></div></li>
        <li><time>Jun to Aug 2026</time><div><h3>Student Intern</h3><p class="where"><a href="https://cemacs.usm.my/" target="_blank" rel="noopener">Centre for Marine and Coastal Studies (CEMACS)</a>, <a href="https://www.usm.my/" target="_blank" rel="noopener">Universiti Sains Malaysia</a>. Onsite, with Abe Woo’s research team.</p>
          <ul>
            <li>Maintained multiple aquatic organism tank systems used for experimental research.</li>
            <li>Entered data and prepared presentations for visitors.</li>
          </ul></div></li>
        <li><time>Sep 2026</time><div><h3>Top Talent Award, AYBO 2026</h3><p class="where">Asian Gifted Youth Association</p><p>Placed in the top 1.2 percentile of 2,000 participants.</p></div></li>
        <li><time>Aug 2026</time><div><h3>Financing Biotech Innovations</h3><p class="where">Certification from <a href="https://www.tum.de/en/" target="_blank" rel="noopener">Technical University of Munich</a> via <a href="https://www.coursera.org/" target="_blank" rel="noopener">Coursera</a></p><p>Awarded a competitive scholarship. Coursework covered financing and entrepreneurship, including how to pitch and secure investment.</p></div></li>
        <li><time>Jun 2026</time><div><h3>Applied Bioinformatics</h3><p class="where">Certification from <a href="https://ucsd.edu/" target="_blank" rel="noopener">UC San Diego</a> via <a href="https://www.coursera.org/" target="_blank" rel="noopener">Coursera</a></p><p>Awarded a competitive scholarship. Coursework covered genomic data analysis and viral sequence tracking of Covid-19.</p></div></li>
      </ol>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <div class="cards">
        <article class="card">
          <h3>Computational analysis of PA-GFP</h3>
          <p>In silico mutagenesis on PA-GFP using <a href="https://pymol.org/" target="_blank" rel="noopener">PyMOL</a>, analysing five structural metrics: cavity expansion, proton-wire geometry, packing loss, solvent access and chromophore planarity.</p>
          <span class="meta"><span>Jul to Aug 2026</span></span>
        </article>
        <article class="card">
          <h3>ADAR off-target analysis</h3>
          <p>Workflow mapping for transcriptome-wide off-target effects of ADAR-mediated RNA editing, using RNA-seq data. <!-- TODO: check with your supervisors what you can share publicly --></p>
          <span class="meta"><span>Nanjing University, 2026</span></span>
        </article>
        <article class="card">
          <h3>Field Notes</h3>
          <p>A revision platform for A Level students. <!-- TODO: describe what it does and what makes it different --></p>
          <span class="meta"><a href="#">Live site</a><a href="#">Source</a></span>
        </article>
      </div>
    </section>
  </div>
</main>

<footer>
  <div class="wrap">© 2026 Shen Khaw</div>
</footer>

<script>
(function () {
  var root = document.documentElement;
  var toggle = document.getElementById('theme');
  function label() { toggle.textContent = root.classList.contains('dark') ? 'Light' : 'Dark'; toggle.setAttribute('aria-label', 'Switch to ' + (root.classList.contains('dark') ? 'light' : 'dark') + ' mode'); }
  toggle.addEventListener('click', function () {
    root.classList.toggle('dark');
    try { localStorage.setItem('theme', root.classList.contains('dark') ? 'dark' : 'light'); } catch (e) {}
    label();
  });
  label();

  var heroName = document.getElementById('profile-title');
  function setupNameMorph(element) {
    var from = element.textContent;
    var to = element.getAttribute('data-alt');
    var chinese = element.getAttribute('data-chinese') || from;
    var pool = (from + to + chinese).replace(/ /g, '').split('');
    var span = Math.max(from.length, to.length, chinese.length);
    var timer = null, settleAt = 0, nextTarget = to, mobileTapIndex = 0, lastRunAt = 0, morphCooldown = 180;

    function measure(text) {
      var previous = element.textContent;
      element.style.width = '';
      element.textContent = text;
      var width = element.getBoundingClientRect().width;
      element.textContent = previous;
      return width;
    }
    function pinWidth() { element.style.width = Math.max(measure(from), measure(to)).toFixed(2) + 'px'; }
    function render(target) {
      var output = '';
      for (var i = 0; i < span; i += 1) {
        if (i < settleAt) output += target[i] || '';
        else if (i < from.length || i < target.length) output += pool[Math.floor(Math.random() * pool.length)];
      }
      element.textContent = output;
    }
    function run(target, stepDuration) {
      clearInterval(timer);
      element.classList.add('is-morphing');
      element.classList.toggle('is-chinese', target === chinese);
      if (window.matchMedia('(prefers-reduced-motion: reduce)').matches) {
        element.textContent = target;
        element.classList.remove('is-morphing');
        return;
      }
      settleAt = 0;
      var started = Date.now();
      timer = setInterval(function () {
        settleAt = Math.floor((Date.now() - started) / (stepDuration || 58));
        if (settleAt > span) {
          clearInterval(timer);
          element.textContent = target;
          element.classList.remove('is-morphing');
          return;
        }
        render(target);
      }, 65);
    }
    function runNext() {
      var now = Date.now();
      if (now - lastRunAt < morphCooldown) return;
      lastRunAt = now;
      var target = nextTarget;
      nextTarget = target === to ? chinese : to;
      run(target);
    }
    function runMobileTapCycle() {
      var targets = [to, chinese, from];
      var target = targets[mobileTapIndex];
      mobileTapIndex = (mobileTapIndex + 1) % targets.length;
      run(target);
    }

    pinWidth();
    if (document.fonts && document.fonts.ready) document.fonts.ready.then(pinWidth);
    window.addEventListener('resize', pinWidth);

    element.textContent = to;
    element.classList.add('is-morphing');
    window.setTimeout(function () { run(from, 180); }, 150);

    if (window.matchMedia('(hover: hover)').matches) {
      element.addEventListener('pointerenter', runNext);
      element.addEventListener('pointerleave', function () { run(from); });
    }
    element.addEventListener('click', function () {
      if (window.matchMedia('(max-width: 600px)').matches) runMobileTapCycle();
      else runNext();
    });

    var lastScrollY = window.scrollY, lastTriggerY = window.scrollY, resetTimer = null;
    window.addEventListener('scroll', function () {
      var currentScrollY = window.scrollY;
      if (window.matchMedia('(max-width: 600px)').matches) { lastScrollY = currentScrollY; return; }
      if (currentScrollY - lastTriggerY >= 5 && currentScrollY > lastScrollY) {
        lastTriggerY = currentScrollY;
        runNext();
        clearTimeout(resetTimer);
        resetTimer = window.setTimeout(function () { if (!element.matches(':hover')) run(from); }, 1000);
      }
      lastScrollY = currentScrollY;
    }, { passive: true });
  }
  if (heroName) setupNameMorph(heroName);
})();
</script>
</body>
</html>
