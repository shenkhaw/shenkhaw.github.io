<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Shen Khaw</title>
<meta name="description" content="Shen Khaw is an aspiring neurobiologist in Penang, Malaysia, working on gene editing, organoids and mechanobiology.">
<meta name="author" content="Shen Khaw">
<link rel="canonical" href="https://shenkhaw.com/">
<meta property="og:type" content="website">
<meta property="og:site_name" content="Shen Khaw">
<meta property="og:title" content="Shen Khaw">
<meta property="og:description" content="Aspiring neurobiologist in Penang, Malaysia, working on gene editing, organoids and mechanobiology.">
<meta property="og:url" content="https://shenkhaw.com/">
<!-- Once the headshot is in place, add it as the share image: <meta property="og:image" content="https://shenkhaw.com/assets/headshot.jpg"> -->
<meta name="twitter:card" content="summary">
<link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='14' fill='%2314202b'/%3E%3Ctext x='32' y='43' font-family='Georgia,serif' font-size='30' font-weight='700' text-anchor='middle' fill='%23ffffff'%3ESK%3C/text%3E%3C/svg%3E">
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&family=Lora:wght@500;700&display=swap">
<script>
(function () {
  document.documentElement.classList.add('js');
  try {
    var s = localStorage.getItem('theme');
    var p = matchMedia('(prefers-color-scheme: dark)').matches ? 'dark' : 'light';
    if ((s || p) === 'dark') document.documentElement.classList.add('dark');
  } catch (e) {}
})();
</script>
<style>
:root {
  --paper: #f4f6f7; --ink: #14202b; --graphite: #566675; --rule: #d3dbe0;
  --accent: #2a4bd7; --card: #ffffff;
  --serif: "Lora", Georgia, "Times New Roman", serif;
  --sans: "Inter", "Helvetica Neue", Arial, sans-serif;
  box-sizing: border-box;
  padding-top: env(safe-area-inset-top, 0px);
  padding-bottom: env(safe-area-inset-bottom, 0px);
}
.dark { --paper: #0f161c; --ink: #e6edf2; --graphite: #98a8b5; --rule: #26343f; --accent: #8ea6ff; --card: #151f27; }
*, *::before, *::after { box-sizing: inherit; }
html { scroll-behavior: smooth; scroll-padding-top: 5rem; }
body { margin: 0; background: var(--paper); color: var(--ink); font: 1.0625rem/1.75 var(--sans); transition: background-color .4s ease, color .4s ease; }
a { color: var(--accent); text-underline-offset: 3px; }
a:focus-visible, button:focus-visible { outline: 3px solid var(--accent); outline-offset: 3px; border-radius: 3px; }
strong { font-weight: 600; }
.wrap { max-width: 46rem; margin: 0 auto; padding: 0 1.5rem; }

header.top { position: sticky; top: 0; z-index: 5; background: var(--paper); border-bottom: 1px solid var(--rule); transition: background-color .4s ease, border-color .4s ease; }
header.top .wrap { display: flex; align-items: center; gap: 1.5rem; height: 3.5rem; }
header.top .brand { font: 700 1.05rem var(--serif); color: var(--ink); text-decoration: none; margin-right: auto; }
header.top a.nav { font: 500 .9rem var(--sans); color: var(--graphite); text-decoration: none; }
header.top a.nav:hover { color: var(--accent); }
#theme { font: 500 .8rem var(--sans); background: none; border: 1px solid var(--rule); color: var(--ink); padding: .3rem .8rem; border-radius: 999px; cursor: pointer; transition: border-color .2s ease; }
#theme:hover { border-color: var(--accent); }

.hero { padding: 5rem 0 4rem; display: grid; grid-template-columns: 1fr 10rem; gap: 2.5rem; align-items: center; }
.headshot { margin: 0; width: 10rem; height: 10rem; border-radius: 50%; position: relative; overflow: hidden; border: 1px solid var(--rule); background: var(--card); grid-column: 2; grid-row: 1; }
.headshot span { position: absolute; inset: 0; display: grid; place-items: center; font: 700 2.6rem var(--serif); color: var(--accent); }
.headshot img { position: absolute; inset: 0; width: 100%; height: 100%; object-fit: cover; }
.hero-text { grid-column: 1; grid-row: 1; min-width: 0; }
h1.hero-name { display: block; max-width: 100%; white-space: nowrap; font: 700 clamp(2.4rem, 10vw, 4.75rem)/1.05 var(--serif); letter-spacing: -.02em; margin: 0 0 .5rem; cursor: default; }
h1.hero-name.is-chinese { font-family: "PingFang SC", "Noto Sans SC", "Microsoft YaHei", var(--serif), sans-serif; letter-spacing: 0; }
.role { font: 500 1rem var(--sans); color: var(--graphite); margin: 0 0 1.5rem; }
.vision { font: 400 1.25rem/1.6 var(--serif); margin: 0 0 2rem; max-width: 34rem; }
.links { display: flex; flex-wrap: wrap; gap: .6rem; padding: 0; margin: 0; list-style: none; }
.links a { display: inline-flex; align-items: center; gap: .45rem; font: 500 .9rem var(--sans); padding: .4rem .9rem; border: 1px solid var(--rule); border-radius: 999px; background: var(--card); color: var(--ink); text-decoration: none; transition: border-color .2s ease, color .2s ease, transform .2s ease; }
.links a:hover { border-color: var(--accent); color: var(--accent); transform: translateY(-1px); }
.links svg { width: 1rem; height: 1rem; fill: currentColor; }

section { padding: 3.5rem 0; border-top: 1px solid var(--rule); }
h2 { font: 700 1.6rem/1.2 var(--serif); margin: 0 0 1.75rem; }
p { margin: 0 0 1rem; }

.news, .awards { list-style: none; margin: 0; padding: 0; }
.news li, .awards li { display: grid; grid-template-columns: 7rem 1fr; gap: 1rem; padding: .75rem 0; }
.news time, .awards time, .timeline time { font: 500 .9rem var(--sans); color: var(--graphite); padding-top: .15rem; }

.timeline { list-style: none; margin: 0; padding: 0; }
.timeline > li { display: grid; grid-template-columns: 7rem 1fr; gap: 1rem; padding: 1.5rem 0; border-top: 1px solid var(--rule); }
.timeline > li:first-child { border-top: 0; padding-top: 0; }
.timeline h3 { font: 700 1.15rem var(--serif); margin: 0 0 .2rem; }
.timeline .where { color: var(--graphite); margin: 0 0 .6rem; font-size: 1rem; }
.timeline ul { margin: 0; padding-left: 1.1rem; }
.timeline ul li { padding: 0 0 .4rem; }

.cards { display: grid; gap: 1.25rem; }
.card { background: var(--card); border: 1px solid var(--rule); border-radius: 8px; padding: 1.4rem 1.5rem; transition: background-color .4s ease, border-color .2s ease; }
.card:hover { border-color: var(--accent); }
.card h3 { font: 700 1.15rem var(--serif); margin: 0 0 .4rem; }
.card p { margin: 0 0 .5rem; color: var(--graphite); font-size: 1rem; }
.card .meta { font: 500 .85rem var(--sans); color: var(--graphite); }

footer { padding: 2.5rem 0 3.5rem; border-top: 1px solid var(--rule); color: var(--graphite); font-size: .95rem; }

.js .reveal { opacity: 0; transform: translateY(14px); transition: opacity .7s ease, transform .7s ease; }
.js .reveal.in { opacity: 1; transform: none; }
@media (prefers-reduced-motion: reduce) {
  html { scroll-behavior: auto; }
  body, header.top, .card { transition: none; }
  .js .reveal { opacity: 1; transform: none; transition: none; }
  .links a:hover { transform: none; }
}

@media (max-width: 600px) {
  .hero { grid-template-columns: 1fr; gap: 1.5rem; padding: 2.5rem 0 3rem; }
  .headshot { grid-column: 1; grid-row: 1; width: 7.5rem; height: 7.5rem; }
  .headshot span { font-size: 2rem; }
  .hero-text { grid-column: 1; grid-row: 2; }
  .news li, .awards li, .timeline > li { grid-template-columns: 1fr; gap: .15rem; }
  header.top a.nav.opt { display: none; }
}
</style>
</head>
<body>
<header class="top">
  <div class="wrap">
    <a class="brand" href="#top">Shen Khaw</a>
    <a class="nav" href="#news">News</a>
    <a class="nav" href="#experience">Experience</a>
    <a class="nav opt" href="#projects">Projects</a>
    <button id="theme" type="button">Dark</button>
  </div>
</header>

<main id="top">
  <div class="wrap">
    <div class="hero reveal">
      <!-- TODO: save a headshot as assets/headshot.jpg (square crop). Until then the SK monogram shows. -->
      <figure class="headshot"><span aria-hidden="true">SK</span><img src="assets/headshot.jpg" alt="Shen Khaw" width="160" height="160" onerror="this.remove()"></figure>
      <div class="hero-text">
        <h1 id="profile-title" class="hero-name" data-alt="sh3nkhaw" data-chinese="许晟">Shen Khaw</h1>
        <p class="role">Aspiring neurobiologist in Penang, Malaysia</p>
        <p class="vision">I want to build a <strong>vascularized neuroimmune organoid</strong> that models sporadic Alzheimer’s disease, solving the “dead core” and microglia maturation problems by combining wet-lab biology, mechanobiology and <strong>computational biology</strong>.</p>
        <ul class="links" aria-label="External links">
          <li><a href="https://github.com/shenkhaw" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M12 2.5a9.5 9.5 0 0 0-3 18.51c.48.09.65-.2.65-.46v-1.67c-2.65.58-3.2-1.13-3.2-1.13-.43-1.1-1.06-1.4-1.06-1.4-.87-.6.07-.59.07-.59.96.07 1.47.99 1.47.99.86 1.47 2.25 1.05 2.8.8.09-.62.34-1.05.62-1.29-2.12-.24-4.35-1.06-4.35-4.72 0-1.04.37-1.89.98-2.56-.1-.24-.42-1.21.09-2.52 0 0 .8-.26 2.62.98A9.1 9.1 0 0 1 12 7.61a9.1 9.1 0 0 1 2.39.32c1.82-1.24 2.62-.98 2.62-.98.51 1.31.19 2.28.09 2.52.61.67.98 1.52.98 2.56 0 3.67-2.23 4.47-4.36 4.71.34.29.65.84.65 1.69v2.5c0 .26.17.55.66.46A9.5 9.5 0 0 0 12 2.5Z"/></svg>GitHub</a></li>
          <li><a href="https://www.linkedin.com/in/khaws/" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M5.25 3.5a1.75 1.75 0 1 0 0 3.5 1.75 1.75 0 0 0 0-3.5ZM3.75 8.25h3v12h-3v-12Zm4.88 0h2.87v1.64h.04c.4-.76 1.38-1.96 2.84-1.96 3.04 0 3.6 2 3.6 4.6v5.72h-3v-5.07c0-1.21-.02-2.77-1.69-2.77-1.69 0-1.95 1.32-1.95 2.68v5.16h-3v-12Z"/></svg>LinkedIn</a></li>
          <!-- Add a Google Scholar link here once your profile exists -->
          <li><a href="ShenkhawCV.pdf" target="_blank" rel="noopener"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M6 2.75h8.3L19 7.46v13.79H6V2.75Zm7.5 1.9v3.65h3.65L13.5 4.65ZM8.25 11h7.5v1.5h-7.5V11Zm0 3.25h7.5v1.5h-7.5v-1.5Z"/></svg>Resume</a></li>
          <li><a href="mailto:sh3nkhaw@gmail.com"><svg viewBox="0 0 24 24" aria-hidden="true"><path d="M3.5 5.25h17v13.5h-17V5.25Zm1.7 1.5L12 12.02l6.8-5.27H5.2Zm13.8 10.5v-8.6L12 14.08 4.98 8.65v8.6h14.04Z"/></svg>Email</a></li>
        </ul>
      </div>
    </div>

    <section id="news" class="reveal">
      <h2>News</h2>
      <ul class="news">
        <li><time>Nov 2026</time><span>Joining Dr. Navid Bavi’s lab at UNSW and UCLA as a remote research intern, working on the mechanobiology of ion channels.</span></li>
        <li><time>Sep 2026</time><span>Started a remote research internship in the Gene Editing and Organoid Laboratory at <a href="https://www.nju.edu.cn/en/" target="_blank" rel="noopener">Nanjing University</a>.</span></li>
        <li><time>Sep 2026</time><span>Received the Top Talent Award at AYBO 2026, placing in the top 1.2 percentile of 2,000 participants.</span></li>
        <li><time>Aug 2026</time><span>Finished a three-month internship at <a href="https://cemacs.usm.my/" target="_blank" rel="noopener">CEMACS</a>, Universiti Sains Malaysia.</span></li>
      </ul>
    </section>

    <section id="experience" class="reveal">
      <h2>Experience</h2>
      <ol class="timeline">
        <li><time>Nov 2026</time><div><h3>Remote Research Intern, Bavi Lab</h3><p class="where">UNSW and UCLA</p>
          <ul><li>Mechanobiology, biophysics and structural biology of membrane proteins and ion channels.</li></ul></div></li>
        <li><time>Sep 2026 to present</time><div><h3>Remote Research Intern</h3><p class="where">Gene Editing and Organoid Laboratory, Institute of Modern Biology, <a href="https://www.nju.edu.cn/en/" target="_blank" rel="noopener">Nanjing University</a>. Supervised by Peipei Qin.</p>
          <ul>
            <li>Mapping transcriptome-wide off-target analysis workflows for <strong>ADAR-mediated RNA editing</strong>.</li>
            <li>Studying how A-to-G editing events are identified, filtered and validated with RNA-seq data, to tell credible off-target sites from background noise.</li>
          </ul></div></li>
        <li><time>Jun to Aug 2026</time><div><h3>Student Intern</h3><p class="where"><a href="https://cemacs.usm.my/" target="_blank" rel="noopener">Centre for Marine and Coastal Studies</a>, <a href="https://www.usm.my/" target="_blank" rel="noopener">Universiti Sains Malaysia</a>. Worked with Abe Woo’s research team.</p>
          <ul>
            <li>Maintained aquatic organism tank systems used for experimental research.</li>
            <li>Entered data and prepared presentations for visitors.</li>
          </ul></div></li>
      </ol>
    </section>

    <section id="projects" class="reveal">
      <h2>Projects</h2>
      <div class="cards">
        <article class="card">
          <h3>Computational analysis of PA-GFP</h3>
          <p>In silico mutagenesis using <a href="https://pymol.org/" target="_blank" rel="noopener">PyMOL</a>, analysing five structural metrics: cavity expansion, proton-wire geometry, packing loss, solvent access and chromophore planarity.</p>
          <span class="meta">Jul to Aug 2026</span>
        </article>
        <article class="card">
          <h3>ADAR off-target analysis workflow</h3>
          <p>Mapping how <strong>ADAR-mediated RNA editing</strong> off-target sites are called and validated across the transcriptome.</p>
          <span class="meta">Nanjing University, 2026</span>
        </article>
      </div>
    </section>

    <section id="awards" class="reveal">
      <h2>Awards and certifications</h2>
      <ul class="awards">
        <li><time>Sep 2026</time><span><strong>Top Talent Award</strong>, AYBO 2026, Asian Gifted Youth Association.</span></li>
        <li><time>Aug 2026</time><span><strong>Financing Biotech Innovations</strong>, <a href="https://www.tum.de/en/" target="_blank" rel="noopener">Technical University of Munich</a> via <a href="https://www.coursera.org/" target="_blank" rel="noopener">Coursera</a>. Competitive scholarship.</span></li>
        <li><time>Jun 2026</time><span><strong>Applied Bioinformatics</strong>, <a href="https://ucsd.edu/" target="_blank" rel="noopener">UC San Diego</a> via <a href="https://www.coursera.org/" target="_blank" rel="noopener">Coursera</a>. Competitive scholarship.</span></li>
      </ul>
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
<script>
(function () {
  var items = document.querySelectorAll('.reveal');
  var reduce = window.matchMedia('(prefers-reduced-motion: reduce)').matches;
  if (reduce || !('IntersectionObserver' in window)) {
    items.forEach(function (el) { el.classList.add('in'); });
    return;
  }
  var io = new IntersectionObserver(function (entries) {
    entries.forEach(function (entry) {
      if (entry.isIntersecting) { entry.target.classList.add('in'); io.unobserve(entry.target); }
    });
  }, { threshold: 0.08 });
  items.forEach(function (el) { io.observe(el); });
})();
</script>
</body>
</html>
