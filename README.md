# ScribeNotes.github.io
CBSE notes for class 9-12 by students
---
layout: default
title: ScribeNotes
---

<style>
  :root {
    --green: #16a34a;
    --green-dark: #15803d;
    --bg: #ffffff;
    --text: #1f2937;
    --border: #e5e7eb;
  }
    * { box-sizing: border-box; margin: 0; padding: 0; }
  body { background: var(--bg); color: var(--text); font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif; }
  .wrap { max-width: 600px; margin: 0 auto; padding: 1rem; }
  
  .header { padding: 1.5rem 0; text-align: center; border-bottom: 1px solid var(--border); }
  .logo {
    font-size: 1.8rem; font-weight: 800; color: var(--green);
    letter-spacing: -0.5px; text-decoration: none;
  }
  .logo span { color: var(--green-dark); }
  
  .hero { text-align: center; padding: 3rem 1rem 2rem 1rem; }
  .hero h1 { font-size: 1.75rem; font-weight: 700; margin-bottom: 0.5rem; }
  .hero p { color: #6b7280; font-size: 1rem; }
  
  .class-grid {
    display: grid; grid-template-columns: 1fr; gap: 1rem;
    margin: 2rem 0 4rem 0;
  }
  .class-btn {
    display: block; background: var(--green); color: white;
    text-decoration: none; padding: 1.5rem; border-radius: 12px;
    font-size: 1.25rem; font-weight: 600; text-align: center;
    transition: 0.2s; border: 2px solid var(--green);
  }
  .class-btn:hover { background: var(--green-dark); transform: scale(1.02); }
  .class-btn:active { transform: scale(0.98); }
  
  .footer {
    text-align: center; padding: 2rem 1rem; border-top: 1px solid var(--border);
    color: #6b7280; font-size: 0.9rem; line-height: 1.6;
  }
  .footer a { color: var(--green); text-decoration: none; font-weight: 500; }
  
  @media (min-width: 640px) {
    .class-grid { grid-template-columns: 1fr 1fr; }
    .hero h1 { font-size: 2.25rem; }
  }
</style>

<div class="wrap">
  <header class="header">
    <a href="/" class="logo">Scribe<span>Notes</span></a>
  </header>

  <div class="hero">
    <h1>Free CBSE Notes by Students</h1>
    <p>Class 9 to 12 • All Streams • Zero Ads</p>
  </div>

  <div class="class-grid">
    <a href="/class9" class="class-btn">Class 9</a>
    <a href="/class10" class="class-btn">Class 10</a>
    <a href="/class11" class="class-btn">Class 11</a>
    <a href="/class12" class="class-btn">Class 12</a>
  </div>

  <footer class="footer">
    ScribeNotes © 2026 | Made by Class 11 Students<br>
    <a href="mailto:patwaadhish@gmail.com">Request Notes</a>
  </footer>
</div>
