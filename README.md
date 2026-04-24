
<style>
  @import url('https://fonts.googleapis.com/css2?family=Geist+Mono:wght@400;500&family=Geist:wght@300;400;500&display=swap');
  *{box-sizing:border-box;margin:0;padding:0}
  .wrap{font-family:'Geist',var(--font-sans);max-width:680px;padding:2rem 0}
  .header{border-bottom:0.5px solid var(--color-border-tertiary);padding-bottom:1.5rem;margin-bottom:1.5rem}
  .name{font-size:22px;font-weight:500;color:var(--color-text-primary);letter-spacing:-0.3px}
  .tagline{font-size:14px;color:var(--color-text-secondary);margin-top:4px}
  .section{margin-bottom:1.5rem}
  .section-label{font-size:11px;font-weight:500;text-transform:uppercase;letter-spacing:0.08em;color:var(--color-text-tertiary);margin-bottom:10px}
  .body-text{font-size:14px;line-height:1.75;color:var(--color-text-secondary)}
  .tech-grid{display:flex;flex-wrap:wrap;gap:6px}
  .tag{font-family:'Geist Mono',var(--font-mono);font-size:12px;padding:3px 10px;border-radius:4px;background:var(--color-background-secondary);border:0.5px solid var(--color-border-tertiary);color:var(--color-text-secondary)}
  .tag.featured{background:var(--color-background-primary);color:var(--color-text-primary);border-color:var(--color-border-secondary)}
  .links{display:flex;gap:1rem;flex-wrap:wrap}
  .link{font-size:13px;color:var(--color-text-secondary);text-decoration:none;display:flex;align-items:center;gap:5px}
  .link:hover{color:var(--color-text-primary)}
  .link-icon{width:14px;height:14px;opacity:0.6}
  .focus-list{display:flex;flex-direction:column;gap:6px}
  .focus-item{font-size:13px;color:var(--color-text-secondary);padding-left:12px;position:relative;line-height:1.5}
  .focus-item::before{content:'';position:absolute;left:0;top:7px;width:4px;height:4px;border-radius:50%;background:var(--color-border-secondary)}
  .divider{border:none;border-top:0.5px solid var(--color-border-tertiary);margin:1.5rem 0}
</style>
<div class="wrap">
  <div class="header">
    <div class="name">wulnrydev</div>
    <div class="tagline">Full-stack developer — web apps, backend systems, Minecraft plugins</div>
  </div>

  <div class="section">
    <div class="section-label">About</div>
    <p class="body-text">
      I build things that are practical, maintainable, and actually useful. Most of my work sits across modern frontend with React and Next.js, backend APIs in Node.js, database-driven applications, and server-side Java for Minecraft plugin development. I care about clean structure, performance where it matters, and writing code that's easy to work on later.
    </p>
  </div>

  <hr class="divider">

  <div class="section">
    <div class="section-label">Tech stack</div>
    <div class="tech-grid">
      <span class="tag featured">TypeScript</span>
      <span class="tag featured">React</span>
      <span class="tag featured">Next.js</span>
      <span class="tag featured">Node.js</span>
      <span class="tag featured">Java</span>
      <span class="tag">Tailwind CSS</span>
      <span class="tag">Express.js</span>
      <span class="tag">PostgreSQL</span>
      <span class="tag">MongoDB</span>
      <span class="tag">Redis</span>
      <span class="tag">Docker</span>
      <span class="tag">GitHub Actions</span>
    </div>
  </div>

  <hr class="divider">

  <div class="section">
    <div class="section-label">What I build</div>
    <p class="body-text">
      Portfolio sites and landing pages, full-stack web applications, REST API services, Discord bots, and Minecraft plugins and server tools.
    </p>
  </div>

  <hr class="divider">

  <div class="section">
    <div class="section-label">Current focus</div>
    <div class="focus-list">
      <div class="focus-item">Building better Next.js applications</div>
      <div class="focus-item">Improving backend architecture</div>
      <div class="focus-item">Writing cleaner TypeScript</div>
      <div class="focus-item">Developing more structured Minecraft plugin systems</div>
    </div>
  </div>

  <hr class="divider">

  <div class="section">
    <div class="section-label">Contact</div>
    <div class="links">
      <a class="link" href="https://github.com/wulnrydev">
        <svg class="link-icon" viewBox="0 0 16 16" fill="currentColor"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"/></svg>
        github.com/wulnrydev
      </a>
      <a class="link" href="https://www.wulnrydev.com">
        <svg class="link-icon" viewBox="0 0 16 16" fill="none" stroke="currentColor" stroke-width="1.5"><circle cx="8" cy="8" r="7"/><path d="M8 1c0 0-3 3-3 7s3 7 3 7"/><path d="M8 1c0 0 3 3 3 7s-3 7-3 7"/><path d="M1 8h14"/></svg>
        wulnrydev.com
      </a>
      <span class="link">
        <svg class="link-icon" viewBox="0 0 16 16" fill="currentColor"><path d="M13.545 2.907a13.227 13.227 0 0 0-3.257-1.011.05.05 0 0 0-.052.025c-.141.25-.297.577-.406.833a12.19 12.19 0 0 0-3.658 0 8.258 8.258 0 0 0-.412-.833.051.051 0 0 0-.052-.025c-1.125.194-2.22.534-3.257 1.011a.041.041 0 0 0-.021.018C.356 6.024-.213 9.047.066 12.032c.001.014.01.028.021.037a13.276 13.276 0 0 0 3.995 2.02.05.05 0 0 0 .056-.019c.308-.42.582-.863.818-1.329a.05.05 0 0 0-.01-.059.051.051 0 0 0-.018-.011 8.875 8.875 0 0 1-1.248-.595.05.05 0 0 1-.02-.066.051.051 0 0 1 .015-.019c.084-.063.168-.129.248-.195a.05.05 0 0 1 .051-.007c2.619 1.196 5.454 1.196 8.041 0a.052.052 0 0 1 .053.007c.08.066.164.132.248.195a.051.051 0 0 1-.004.085 8.254 8.254 0 0 1-1.249.594.05.05 0 0 0-.03.03.052.052 0 0 0 .003.041c.24.465.515.909.817 1.329a.05.05 0 0 0 .056.019 13.235 13.235 0 0 0 4.001-2.02.049.049 0 0 0 .021-.037c.334-3.451-.559-6.449-2.366-9.106a.034.034 0 0 0-.02-.019z"/></svg>
        wulnrydev
      </span>
    </div>
  </div>
</div>
