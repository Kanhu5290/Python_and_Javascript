<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Cybersecurity Student — Portfolio</title>
  <meta name="description" content="Portfolio page for a self-learning cybersecurity student. Completed Google's Cybersecurity Professional Certificate (Coursera). Currently reading 'Hacking: The Art of Exploitation' by Jon Erickson." />
  <style>
    :root{
      --bg:#0f1724;
      --card:#0b1220;
      --muted:#94a3b8;
      --accent:#60a5fa;
      --glass: rgba(255,255,255,0.04);
      --glass-2: rgba(255,255,255,0.02);
      --success:#86efac;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      background:linear-gradient(180deg,#071029 0%, #071b2b 60%);
      color:#e6eef8;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.5;
      padding:32px;
    }
    .container{
      max-width:980px;
      margin:0 auto;
    }
    header{
      display:flex;
      align-items:center;
      gap:18px;
      margin-bottom:22px;
    }
    .avatar{
      width:88px;
      height:88px;
      border-radius:12px;
      background:linear-gradient(135deg,var(--accent),#7c3aed);
      display:flex;
      align-items:center;
      justify-content:center;
      font-weight:700;
      font-size:28px;
      color:#021028;
      box-shadow:0 6px 20px rgba(2,8,23,0.6);
      flex-shrink:0;
    }
    h1{font-size:24px;margin:0}
    p.lead{margin:6px 0 0;color:var(--muted)}
    .card{
      background:linear-gradient(180deg,var(--card), #061226);
      border-radius:12px;
      padding:20px;
      margin-top:18px;
      box-shadow:0 6px 30px rgba(2,8,23,0.6);
      border:1px solid rgba(255,255,255,0.03);
    }
    .grid{
      display:grid;
      grid-template-columns: 1fr 320px;
      gap:18px;
    }
    @media (max-width:880px){
      .grid{grid-template-columns:1fr}
    }
    h2{font-size:16px;margin:0 0 12px}
    ul{margin:0;padding-left:18px;color:var(--muted)}
    .badge{
      display:inline-block;
      padding:6px 10px;
      background:var(--glass);
      color:var(--accent);
      border-radius:999px;
      font-weight:600;
      font-size:13px;
      border:1px solid rgba(96,165,250,0.12);
    }
    .meta{
      display:flex;
      gap:8px;
      flex-wrap:wrap;
      margin-top:10px;
    }
    .muted{color:var(--muted);font-size:14px}
    .button{
      display:inline-flex;
      gap:10px;
      align-items:center;
      padding:10px 14px;
      background:linear-gradient(90deg,var(--accent),#7c3aed);
      color:#021028;
      border-radius:10px;
      text-decoration:none;
      font-weight:600;
      border:0;
      box-shadow:0 8px 20px rgba(96,165,250,0.12);
    }
    .small{
      font-size:13px;
      color:var(--muted);
    }
    .list-card{
      background:var(--glass-2);
      border-radius:8px;
      padding:12px;
      border:1px solid rgba(255,255,255,0.02);
      margin-bottom:10px;
    }
    .skill{
      display:inline-block;
      padding:6px 9px;
      margin:6px 6px 6px 0;
      background:rgba(255,255,255,0.03);
      color:var(--muted);
      border-radius:8px;
      font-size:13px;
    }
    footer{margin-top:22px;text-align:center;color:var(--muted);font-size:13px}
    .link{color:var(--accent);text-decoration:none}
    .cert-link{display:inline-block;margin-top:8px;color:#9be7ff;font-weight:600;text-decoration:none}
    .project-title{font-weight:700;color:#e6eef8;margin:0 0 6px}
    .note{font-size:13px;color:var(--muted);margin-top:8px}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="avatar" aria-hidden="true">CY</div>
      <div>
        <h1>Self-learning Cybersecurity Student</h1>
        <p class="lead">Completed the <span class="badge">Google Cybersecurity Professional Certificate</span> on Coursera. Currently studying <em>Hacking: The Art of Exploitation</em> by Jon Erickson.</p>
        <div class="meta">
          <span class="small muted">Location: —</span>
          <span class="small muted">Email: <a class="link" href="mailto:sitakantabaliarsingh2@gmail.com">sitakantabaliarsingh2@gmail.com</a></span>
        </div>
        
      </div>
    </header>

    <main class="grid">
      <!-- Left column: about, skills, certifications, learning -->
      <section>
        <div class="card">
          <h2>About</h2>
          <p class="small muted">I am a motivated self-taught cybersecurity student focused on defensive security fundamentals, incident response, network security, and hands-on exploitation techniques. My learning path combines structured certificates and hands-on labs.</p>

          <div style="margin-top:14px">
            <h2>Key Skills</h2>
            <div style="margin-top:8px">
              <span class="skill">Linux (bash)</span>
              <span class="skill">Networking (TCP/IP)</span>
              <span class="skill">Security fundamentals</span>
              <span class="skill">Vulnerability assessment</span>
              <span class="skill">Python scripting</span>
              <span class="skill">Wireshark</span>
              <span class="skill">Basic exploitation</span>
              <span class="skill">Cryptography (basics)</span>
            </div>
          </div>

          <div style="margin-top:14px">
            <h2>Certifications</h2>
            <div class="list-card">
              <div style="display:flex;align-items:center;justify-content:space-between;gap:12px">
                <div>
                  <div style="font-weight:700">Google Cybersecurity Professional Certificate</div>
                  <div class="small muted">Issued by Coursera — Verified</div>
                </div>
                <div style="text-align:right">
                  <!-- Replace href with your cert URL -->
                  <a class="button" href="https://www.coursera.org/account/accomplishments/professional-cert/D6ICUILCGWIW" title="View certificate (https://www.coursera.org/account/accomplishments/professional-cert/D6ICUILCGWIW)">View certificate</a>
                </div>
              </div>
              <div>
                  <div style="font-weight:700">Google IT Support Certificate</div>
                  <div class="small muted">Issued by Coursera — Verified</div>
                </div>
                <div style="text-align:right">
                  <!-- Replace href with your cert URL -->
                  <a class="button" href="https://www.coursera.org/account/accomplishments/professional-cert/RYLZWE53R55X" title="View certificate (https://www.coursera.org/account/accomplishments/professional-cert/RYLZWE53R55X)">View certificate</a>
                </div>
              </div>
            </div>

          <div style="margin-top:14px">
            <h2>Current Learning</h2>
            <div class="list-card">
              <div style="display:flex;gap:12px;align-items:center;justify-content:space-between">
                <div>
                  <div class="project-title">Reading — <em>Hacking: The Art of Exploitation</em></div>
                  <div class="small muted">Author: Jon Erickson</div>
                  <div class="small muted" style="margin-top:8px">Focus: low-level exploitation, memory/stack, C programming, and practical lab exercises.</div>
                </div>
                <div style="text-align:right">
                  <a class="cert-link" href="https://github.com/Kanhu5290/Readme" title="Reading notes link">Reading notes</a>
                </div>
              </div>
            </div>
          </div>

          <div style="margin-top:14px">
            <h2>Projects & Labs</h2>
            <div class="list-card">
              <div style="font-weight:700">Example: Vulnerable VM lab</div>
              <div class="small muted">Practice: use of debugging tools, exploit development basics, and network monitoring.</div>
              <div class="note">Add short writeups and links to GitHub repos for each project to showcase your practical skills.</div>
            </div>
            <div class="list-card">
              <div style="font-weight:700">Example: Packet analysis</div>
              <div class="small muted">Practice: Wireshark captures and protocol analysis with documented findings.</div>
            </div>
          </div>

        </div>
      </section>

      <!-- Right column: contact, quick links, resume -->
      <aside>
        <div class="card">
          <h2>Quick Links</h2>
          <div style="display:flex;flex-direction:column;gap:10px;margin-top:8px">
            <a class="button" href="https://github.com/Kanhu5290/Readme" style="justify-content:center" title="GitHub profile">GitHub profile</a>
            <a class="button" href="#" style="justify-content:center;background:linear-gradient(90deg,#22c55e,#16a34a)" title="Resume (replace)">Download Resume</a>
            <a class="button" href="https://www.coursera.org/account/accomplishments/professional-cert/D6ICUILCGWIW" style="justify-content:center;background:linear-gradient(90deg,#f97316,#fb7185)" title="Coursera certificate (replace)">Coursera Certificate</a>
          </div>

          <div style="margin-top:14px">
            <h2>Contact</h2>
            <p class="small muted">Want to collaborate or give feedback? Reach out below.</p>
            <div style="margin-top:8px">
              <div class="small muted">Email</div>
              <div style="font-weight:700;margin-top:4px"><a class="link" href="mailto:sitakantabaliarsingh2@gmail.com">sitakantabaliarsingh2@gmail.com</a></div>
            </div>
            <div style="margin-top:10px">
              <div class="small muted">LinkedIn</div>
              <div style="font-weight:700;margin-top:4px"><a class="link" href="https://www.linkedin.com/in/sitakanta-baliarsingh-036051322/" target="_blank" rel="noopener">https://www.linkedin.com/in/sitakanta-baliarsingh-036051322/</a></div>
            </div>
          </div>
        </div>

       

        <div class="card" style="margin-top:14px;">
          <h2>Notes & Next Steps</h2>
          <ul>
            <li class="small muted">I will add short writeups for 3–5 hands-on projects with links to code and reports that I completed in short <time datetime="2023-10-01">October 2023</time>.</li>
            <li class="small muted">The snapshot link will be included in the writeups with screenshots or GIFs of labs (VMs, Wireshark captures, code snippets).</li>
            <li class="small muted">Consider a short blog section with lessons learned from the book and labs visit my wordpress blog <a href="https://yourblog.wordpress.com" target="_blank" rel="noopener">here</a>.</li>
          </ul>
        </div>
      </aside>
    </main>

    <footer>
      <div>Made with care • I will keep this updated with my latest work.</div>
      <div style="margin-top:8px" class="small muted">© <span id="year"></span> Sitakanta Baliarsingh(Kanhu) — <a class="link" href="#" target="_blank" rel="noopener">License</a></div>
    </footer>
  </div>

  <script>
    // auto year
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
