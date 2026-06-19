html

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Taj Wali Khan — AI Engineer</title>
<meta name="description" content="Taj Wali Khan — AI Engineer & BS Computer Science (AI) student building fraud detection systems, legal RAG chatbots, and computer vision tools.">
<meta name="theme-color" content="#14182B">

<!-- Open Graph -->
<meta property="og:title" content="Taj Wali Khan — AI Engineer">
<meta property="og:description" content="Building AI systems that tell signal from noise — fraud detection, legal RAG chatbots, computer vision, and more.">
<meta property="og:type" content="website">

<link rel="icon" type="image/svg+xml" href="assets/favicon.svg">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,400;9..144,500;9..144,600;9..144,700&family=Inter:wght@400;500;600;700&family=JetBrains+Mono:wght@400;500;600&display=swap" rel="stylesheet">
<link rel="stylesheet" href="css/style.css">
</head>
<body>

<a class="skip-link" href="#main">Skip to content</a>

<!-- ============ NAV ============ -->
<header class="nav" id="nav">
  <div class="nav-inner container">
    <a href="#hero" class="nav-brand" aria-label="Back to top">
      <span class="brand-mark" aria-hidden="true">TWK</span>
      <span class="brand-name">Taj Wali Khan</span>
    </a>
    <nav class="nav-links" id="navLinks">
      <a href="#about"><span class="idx">01</span>Index</a>
      <a href="#skills"><span class="idx">02</span>Toolkit</a>
      <a href="#projects"><span class="idx">03</span>Case&nbsp;Files</a>
      <a href="#education"><span class="idx">04</span>Record</a>
      <a href="#contact"><span class="idx">05</span>Contact</a>
    </nav>
    <a href="assets/resume.pdf" class="btn btn-ghost nav-resume" download>Résumé</a>
    <button class="nav-toggle" id="navToggle" aria-label="Toggle menu" aria-expanded="false">
      <span></span><span></span><span></span>
    </button>
  </div>
</header>

<main id="main">

  <!-- ============ HERO ============ -->
  <section class="hero" id="hero">
    <div class="container hero-inner">
      <div class="hero-copy reveal">
        <p class="eyebrow"><span class="dot"></span>Case File — Open</p>
        <h1 class="hero-title">I build AI systems<br>that tell <em>signal</em><br>from <em>noise</em>.</h1>
        <p class="hero-sub">BS Computer Science (Artificial Intelligence) student at Abdul Wali Khan University, Mardan — currently building fraud detectors, legal chatbots, and computer&nbsp;vision tools that turn messy, real-world data into decisions you can trust.</p>
        <div class="hero-cta">
          <a href="#projects" class="btn btn-primary">Open Case Files</a>
          <a href="assets/resume.pdf" class="btn btn-outline" download>Download Résumé</a>
          <a href="#contact" class="btn btn-text">Say hello →</a>
        </div>
        <dl class="hero-stats">
          <div><dt>20+</dt><dd>Projects on file</dd></div>
          <div><dt>3.36</dt><dd>CGPA / 4.00</dd></div>
          <div><dt>2027</dt><dd>Expected graduation</dd></div>
        </dl>
      </div>

      <div class="hero-seal reveal" aria-hidden="true">
        <svg viewBox="0 0 240 240" class="seal-svg" id="sealSvg">
          <defs>
            <path id="sealCirclePath" d="M 120,120 m -92,0 a 92,92 0 1,1 184,0 a 92,92 0 1,1 -184,0" />
          </defs>
          <circle class="seal-ring seal-ring-outer" cx="120" cy="120" r="112"/>
          <circle class="seal-ring seal-ring-inner" cx="120" cy="120" r="92"/>
          <text class="seal-text">
            <textPath href="#sealCirclePath" startOffset="0%">TAJ WALI KHAN&nbsp;&nbsp;•&nbsp;&nbsp;AI ENGINEER&nbsp;&nbsp;•&nbsp;&nbsp;GENERATIVE AI&nbsp;&nbsp;•&nbsp;&nbsp;RAG&nbsp;&nbsp;•&nbsp;&nbsp;</textPath>
          </text>
          <text x="120" y="113" text-anchor="middle" class="seal-initials">TWK</text>
          <line x1="92" y1="130" x2="148" y2="130" class="seal-rule"/>
          <text x="120" y="150" text-anchor="middle" class="seal-est">EST. 2023</text>
        </svg>
      </div>
    </div>
  </section>

  <!-- ============ ABOUT / INDEX ============ -->
  <section class="section" id="about">
    <div class="container">
      <div class="section-head reveal">
        <p class="eyebrow">Index</p>
        <h2>The file on me</h2>
      </div>
      <div class="about-grid">
        <p class="about-copy reveal">
          I'm an AI &amp; Machine Learning student who'd rather ship a working prototype than
          admire a slide deck. Over the past couple of years that's meant building a scam
          detector that reads text, URLs, images, and voice together; a chatbot that explains
          Pakistani law without making things up; and a handful of computer-vision and NLP
          tools in between. I care about AI that's explainable and useful in the hands of
          someone who isn't an engineer — that's the thread running through most of what's
          below.
        </p>
        <dl class="case-meta reveal">
          <div><dt>Field</dt><dd>Artificial Intelligence</dd></div>
          <div><dt>Institution</dt><dd>Abdul Wali Khan University, Mardan</dd></div>
          <div><dt>Based in</dt><dd>Dir (Lower), Khyber&nbsp;Pakhtunkhwa, Pakistan</dd></div>
          <div><dt>Status</dt><dd><span class="status-dot"></span>Open to AI/ML internships</dd></div>
          <div><dt>Focus</dt><dd>Generative AI · RAG · Agentic AI · Computer Vision</dd></div>
        </dl>
      </div>
    </div>
  </section>

  <!-- ============ SKILLS ============ -->
  <section class="section section-alt" id="skills">
    <div class="container">
      <div class="section-head reveal">
        <p class="eyebrow">Toolkit</p>
        <h2>What I work with</h2>
      </div>
      <div class="skills-grid reveal">
        <div class="skill-group">
          <h3>Languages</h3>
          <ul class="chips"><li>Python</li><li>SQL</li></ul>
        </div>
        <div class="skill-group">
          <h3>AI &amp; Machine Learning</h3>
          <ul class="chips">
            <li>Machine Learning</li><li>Deep Learning</li><li>Generative AI</li>
            <li>Agentic AI</li><li>NLP</li><li>RAG</li><li>Computer Vision</li><li>Prompt Engineering</li>
          </ul>
        </div>
        <div class="skill-group">
          <h3>Frameworks &amp; Libraries</h3>
          <ul class="chips">
            <li>TensorFlow</li><li>PyTorch</li><li>Scikit-learn</li><li>Hugging Face</li>
            <li>FAISS</li><li>Streamlit</li><li>Flask</li><li>FastAPI</li>
          </ul>
        </div>
        <div class="skill-group">
          <h3>Databases</h3>
          <ul class="chips"><li>MySQL</li><li>SQL Server</li><li>MongoDB</li></ul>
        </div>
        <div class="skill-group">
          <h3>Tools &amp; Platforms</h3>
          <ul class="chips">
            <li>Git</li><li>GitHub</li><li>VS Code</li><li>Google Colab</li><li>Jupyter Notebook</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- ============ PROJECTS / CASE FILES ============ -->
  <section class="section" id="projects">
    <div class="container">
      <div class="section-head reveal">
        <p class="eyebrow">Case Files</p>
        <h2>Selected work</h2>
        <p class="section-sub">Six projects pulled from an active caseload of 20+ — each one a real attempt to make AI more useful, honest, or safe.</p>
      </div>

      <div class="case-grid">

        <article class="case-card reveal" style="--tilt:-1.2deg">
          <div class="case-card-tape" aria-hidden="true"></div>
          <div class="case-top">
            <span class="case-no">CASE&nbsp;01</span>
            <span class="case-tag tag-security">Fraud &amp; Security AI</span>
          </div>
          <h3>Multi-Modal AI Scam &amp; Fraud Detector</h3>
          <p>Detects online scams by analyzing text, URLs, images, and voice together, then generates a transparent risk score and real-time safety guidance through an interactive dashboard.</p>
          <ul class="tech-row">
            <li>Python</li><li>NLP</li><li>Streamlit</li><li>Flask/FastAPI</li><li>TensorFlow/PyTorch</li>
          </ul>
        </article>

        <article class="case-card reveal" style="--tilt:1.4deg">
          <div class="case-card-tape" aria-hidden="true"></div>
          <div class="case-top">
            <span class="case-no">CASE&nbsp;02</span>
            <span class="case-tag tag-legal">Legal AI · RAG</span>
          </div>
          <h3>QanoonAI — Pakistani Legal RAG Chatbot</h3>
          <p>A Retrieval-Augmented Generation chatbot that explains Pakistani law in plain language, answering strictly from trusted legal documents with citations for every claim.</p>
          <ul class="tech-row">
            <li>Python</li><li>Hugging Face</li><li>FAISS</li><li>Streamlit</li>
          </ul>
        </article>

        <article class="case-card reveal" style="--tilt:-0.8deg">
          <div class="case-card-tape" aria-hidden="true"></div>
          <div class="case-top">
            <span class="case-no">CASE&nbsp;03</span>
            <span class="case-tag tag-health">Healthcare AI</span>
          </div>
          <h3>Medical Chatbot — AI Healthcare Assistant</h3>
          <p>An intelligent assistant that gives basic medical guidance and helps people find reliable health information quickly, without the noise of a general search engine.</p>
          <ul class="tech-row">
            <li>Python</li><li>NLP</li><li>Machine Learning</li><li>Streamlit</li>
          </ul>
        </article>

        <article class="case-card reveal" style="--tilt:1.1deg">
          <div class="case-card-tape" aria-hidden="true"></div>
          <div class="case-top">
            <span class="case-no">CASE&nbsp;04</span>
            <span class="case-tag tag-security">Security AI</span>
          </div>
          <h3>AI Smart Email Security System</h3>
          <p>A phishing and spam detection tool that reads incoming emails and automatically flags suspicious content using natural language processing.</p>
          <ul class="tech-row">
            <li>Python</li><li>NLP</li><li>Scikit-learn</li>
          </ul>
        </article>

        <article class="case-card reveal" style="--tilt:-1.5deg">
          <div class="case-card-tape" aria-hidden="true"></div>
          <div class="case-top">
            <span class="case-no">CASE&nbsp;05</span>
            <span class="case-tag tag-vision">Computer Vision</span>
          </div>
          <h3>YOLOv8 Object Detection &amp; Tracking</h3>
          <p>A custom-trained YOLOv8 model for real-time object detection and tracking, deployed through a Flask API for practical, real-world use.</p>
          <ul class="tech-row">
            <li>Python</li><li>YOLOv8</li><li>OpenCV</li><li>Flask</li>
          </ul>
        </article>

        <article class="case-card reveal" style="--tilt:0.9deg">
          <div class="case-card-tape" aria-hidden="true"></div>
          <div class="case-top">
            <span class="case-no">CASE&nbsp;06</span>
            <span class="case-tag tag-creative">Generative AI</span>
          </div>
          <h3>AI Concept Art &amp; Storyboard Generator</h3>
          <p>A Gemini API–powered tool that automatically generates concept art and storyboards to speed up early-stage creative work for game and film projects.</p>
          <ul class="tech-row">
            <li>Python</li><li>Gemini API</li><li>Streamlit</li>
          </ul>
        </article>

      </div>

      <div class="more-cases reveal">
        <h3>Additional builds on file</h3>
        <p>Medical Legal RAG System · Object Detection &amp; Tracking System · CNN FashionMNIST Classification · CNN-YOLO Flask API Deployment · Music Generation with AI · AI-Powered Content Generation &amp; Optimization Tool · Advanced FAQ Chatbot · Language Translation Tool · Smart Trip Planner &amp; Health Optimizer · AI Robotic Arm Simulation · SmartStay Hub · GDP Dashboard · Internship RAG Showcase · Learning Habit Tracker · Portfolio Website</p>
        <a href="https://github.com/tajwalikhan-code" target="_blank" rel="noopener" class="btn btn-outline">Full archive on GitHub ↗</a>
      </div>
    </div>
  </section>

  <!-- ============ EDUCATION / RECORD ============ -->
  <section class="section section-alt" id="education">
    <div class="container">
      <div class="section-head reveal">
        <p class="eyebrow">Record</p>
        <h2>Education &amp; credentials</h2>
      </div>
      <ol class="docket reveal">
        <li>
          <span class="docket-date">2023 — 2027<small>Expected</small></span>
          <div class="docket-body">
            <h3>BS Computer Science (Artificial Intelligence)</h3>
            <p>Abdul Wali Khan University, Mardan &nbsp;·&nbsp; CGPA 3.36 / 4.00</p>
          </div>
        </li>
        <li>
          <span class="docket-date">2026<small>Certification</small></span>
          <div class="docket-body">
            <h3>HEC Generative AI Training — Cohort 2</h3>
            <p>Higher Education Commission (HEC), Pakistan &nbsp;·&nbsp; Generative AI, LLMs, AI Automation, Prompt Engineering, AI Applications</p>
          </div>
        </li>
        <li>
          <span class="docket-date">2023<small>Grade A</small></span>
          <div class="docket-body">
            <h3>Intermediate (FSc / ICS)</h3>
            <p>The Knowledge School &amp; College, Dir (L)</p>
          </div>
        </li>
        <li>
          <span class="docket-date">2020<small>Grade A</small></span>
          <div class="docket-body">
            <h3>Matriculation</h3>
            <p>Govt. High School Khall Kandaro, Dir (L)</p>
          </div>
        </li>
      </ol>
    </div>
  </section>

  <!-- ============ BEYOND THE CODE ============ -->
  <section class="section" id="beyond">
    <div class="container">
      <div class="section-head reveal">
        <p class="eyebrow">Beyond the Code</p>
        <h2>Off duty</h2>
      </div>
      <div class="beyond-grid">
        <p class="about-copy reveal">
          Outside of notebooks and APIs, I help run the <strong>Dir Students Society</strong>,
          organizing elections, seminars, and cultural events for fellow students, and I've
          spoken as a guest on student leadership and community engagement. It's taught me as
          much about working with people as any model ever has.
        </p>
        <ul class="soft-chips reveal">
          <li>Leadership</li><li>Communication</li><li>Teamwork</li><li>Problem Solving</li>
          <li>Public Speaking</li><li>Project Management</li><li>Time Management</li>
          <li>Critical Thinking</li><li>Adaptability</li><li>Research Mindset</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- ============ CONTACT ============ -->
  <section class="section section-contact" id="contact">
    <div class="container">
      <div class="section-head reveal">
        <p class="eyebrow">Get in touch</p>
        <h2>Let's build something worth trusting.</h2>
        <p class="section-sub">Open to AI/ML internships, research collaborations, and interesting problems. I usually reply within a day or two.</p>
      </div>

      <div class="contact-grid reveal">
        <a class="contact-card" href="mailto:tajwalikhanoffical@gmail.com">
          <svg viewBox="0 0 24 24" class="icon"><path d="M3 6h18v12H3z"/><path d="M3 6l9 7 9-7"/></svg>
          <span>tajwalikhanoffical@gmail.com</span>
        </a>
        <a class="contact-card" href="tel:+923039333624">
          <svg viewBox="0 0 24 24" class="icon"><path d="M5 4h4l2 5-2.5 1.5a11 11 0 0 0 5 5L15 13l5 2v4a2 2 0 0 1-2 2A16 16 0 0 1 3 6a2 2 0 0 1 2-2z"/></svg>
          <span>0303-9333624</span>
        </a>
        <a class="contact-card" href="https://www.linkedin.com/in/taj-wali-khan-03a7693aa" target="_blank" rel="noopener">
          <svg viewBox="0 0 24 24" class="icon"><rect x="3" y="3" width="18" height="18" rx="2"/><path d="M7 10v7M7 7v.01M11 17v-4.5a2.5 2.5 0 0 1 5 0V17M11 10v7"/></svg>
          <span>linkedin.com/in/taj-wali-khan-03a7693aa</span>
        </a>
        <a class="contact-card" href="https://github.com/tajwalikhan-code" target="_blank" rel="noopener">
          <svg viewBox="0 0 24 24" class="icon"><path d="M12 2a10 10 0 0 0-3.16 19.49c.5.09.68-.22.68-.48v-1.7c-2.78.6-3.37-1.34-3.37-1.34-.45-1.16-1.11-1.47-1.11-1.47-.91-.62.07-.6.07-.6 1 .07 1.53 1.03 1.53 1.03.89 1.53 2.34 1.09 2.91.83.09-.65.35-1.09.63-1.34-2.22-.25-4.56-1.11-4.56-4.95 0-1.09.39-1.99 1.03-2.69-.1-.25-.45-1.27.1-2.64 0 0 .84-.27 2.75 1.03a9.4 9.4 0 0 1 5 0c1.91-1.3 2.75-1.03 2.75-1.03.55 1.37.2 2.39.1 2.64.64.7 1.03 1.6 1.03 2.69 0 3.85-2.34 4.7-4.57 4.94.36.31.68.92.68 1.85v2.74c0 .27.18.58.69.48A10 10 0 0 0 12 2z"/></svg>
          <span>github.com/tajwalikhan-code</span>
        </a>
        <a class="contact-card contact-card-static">
          <svg viewBox="0 0 24 24" class="icon"><path d="M12 21s-7-5.33-7-11a7 7 0 0 1 14 0c0 5.67-7 11-7 11z"/><circle cx="12" cy="10" r="2.5"/></svg>
          <span>Dir (Lower), Khyber Pakhtunkhwa, Pakistan</span>
        </a>
      </div>
    </div>
  </section>

</main>

<!-- ============ FOOTER ============ -->
<footer class="footer">
  <div class="container footer-inner">
    <p>Case File #2023-AI-04 · Built in Dir, KPK · © <span id="year">2026</span> Taj Wali Khan</p>
    <a href="#hero" class="footer-top">Back to top ↑</a>
  </div>
</footer>

<script src="js/main.js"></script>
</body>
</html>
