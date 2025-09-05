 <!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Dotnet Developer — Portfolio</title>
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--muted:#94a3b8;--accent:#06b6d4;--glass:rgba(255,255,255,0.03)}
    *{box-sizing:border-box}
    body{font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,'Helvetica Neue',Arial; margin:0; background:linear-gradient(180deg,#071028 0%, #081227 100%); color:#e6eef6; -webkit-font-smoothing:antialiased}
    .container{max-width:1000px;margin:36px auto;padding:24px}
    header{display:flex;align-items:center;gap:16px}
    .avatar{width:88px;height:88px;border-radius:16px;background:linear-gradient(135deg,var(--accent),#7c3aed);display:flex;align-items:center;justify-content:center;font-weight:700;font-size:28px}
    h1{margin:0;font-size:28px}
    p.lead{color:var(--muted);margin:6px 0 0}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:20px;margin-top:24px}
    .card{background:var(--card);padding:18px;border-radius:12px;box-shadow:0 6px 24px rgba(2,6,23,0.6)}
    .section-title{font-weight:600;margin:0 0 12px}
    .skills{display:flex;flex-wrap:wrap;gap:8px}
    .chip{background:var(--glass);padding:6px 10px;border-radius:999px;font-size:13px;color:var(--muted)}
    .project{border-radius:10px;padding:14px;background:linear-gradient(180deg, rgba(255,255,255,0.02), transparent);margin-bottom:12px}
    .project h4{margin:0}
    .project .meta{font-size:13px;color:var(--muted);margin-top:6px}
    .btn{display:inline-block;padding:8px 12px;border-radius:10px;text-decoration:none;font-weight:600;background:linear-gradient(90deg,var(--accent),#7c3aed);color:#021724}
    aside .small{font-size:13px;color:var(--muted)}
    footer{margin-top:28px;text-align:center;color:var(--muted);font-size:13px}
    @media (max-width:900px){.grid{grid-template-columns:1fr;}.avatar{width:72px;height:72px}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="avatar" >HM</div>
      <div>
        <h1>Harish Mantur — .NET Developer</h1>
        <p class="lead">Building scalable web APIs and clean front-ends with .NET, C#, EF Core, SQL Server and Azure. Open-source contributor and lifelong learner.</p>
      </div>
    </header>

    <div class="grid">
      <main>
        <section class="card">
          <h2 class="section-title">Featured Projects</h2>

          <article class="project">
            <h4>InventoryFlow — Warehouse API & Dashboard</h4>
            <div class="meta">ASP.NET Core Web API • EF Core • SQL Server • React • Docker • Azure App Service</div>
            <p>Designed a RESTful API for inventory and order management supporting JWT auth, CQRS, and background stock reconciliation. Built an admin React dashboard to visualize stock trends and low-stock alerts.</p>
            <p><strong>Highlights:</strong> Unit/integration tests (xUnit), EF Core migrations, Dockerized deployments, CI with GitHub Actions.</p>
            <p><a class="btn" href="#">View repo</a> <a class="btn" href="#">Live demo</a></p>
          </article>

          <article class="project">
            <h4>PayBuddy — Payment Microservice</h4>
            <div class="meta">ASP.NET Core • gRPC • Redis • PostgreSQL • Kubernetes</div>
            <p>High-throughput payments microservice with idempotency keys, event-driven notifications (Kafka), and observability via OpenTelemetry.</p>
            <p><strong>Highlights:</strong> Circuit-breaker with Polly, request tracing, and performance tuning to handle burst traffic.</p>
            <p><a class="btn" href="#">View repo</a></p>
          </article>

          <article class="project">
            <h4>Portfolio CMS — Headless CMS</h4>
            <div class="meta">.NET Minimal APIs • Azure Functions • Blob Storage</div>
            <p>Serverless content API paired with a static site generator for fast/cheap hosting. Uses Azure Blob for media and role-based access for content editors.</p>
            <p><a class="btn" href="#">View repo</a></p>
          </article>
        </section>

        <section class="card" style="margin-top:18px">
          <h2 class="section-title">Experience</h2>
          <p><strong>Intern — Sion Semiconductors</strong> — Worked on VLSI tooling and Verilog testbenches. (Jun 2024 — Aug 2024)</p>
          <p><strong> .NET Developer</strong> — Built REST APIs and automation scripts for SMB clients.</p>
        </section>

        <section class="card" style="margin-top:18px">
          <h2 class="section-title">Education & Certificates</h2>
          <ul>
            <li>PU College equivalent — Pre-University (PCMB)<link rel="stylesheet"href="https://spoco.org/" ></li>
            <li>Jain College Of Engineering And Research
                <link rel="stylesheet" href="https://jcer.in/"> </li>
            <li>Microsoft: AZ-204 / Fundamentals (if applicable)</li>
            <li>Pragim Tech — .NET Full Stack training</li>
          </ul>
        </section>
      </main>

      <aside>
        <div class="card">
          <h3 class="section-title">Skills</h3>
          <div class="skills">
            <span class="chip">C#</span>
            <span class="chip">ASP.NET Core</span>
            <span class="chip">Entity Framework Core</span>
            <span class="chip">SQL Server</span>
            <span class="chip">Azure</span>
            <span class="chip">Docker</span>
            <span class="chip">Kubernetes</span>
            <span class="chip">Redis</span>
            <span class="chip">gRPC</span>
            <span class="chip">xUnit / NUnit</span>
            <span class="chip">Git / GitHub</span>
            <span class="chip">CI/CD</span>
          </div>
        </div>

        <div class="card" style="margin-top:18px">
          <h3 class="section-title">Contact</h3>
          <p class="small">Email:harishmantur433@gmail.com</p>
          <p class="small">GitHub: github.com/harish</p>
          <p class="small">LinkedIn: linkedin.com/in/harish</p>
          <p style="margin-top:10px"><a class="btn" href="mailto:harish@example.com">Email me</a></p>
        </div>

        <div class="card" style="margin-top:18px">
          <h3 class="section-title">Quick Blurb</h3>
          <p class="small">I'm a .NET developer who focuses on clean APIs, reliable architecture, and shipping production-ready code. I love automated tests and improving developer experience.</p>
        </div>
      </aside>
    </div>

    <footer>
      <div>Built with All copyright</div>
    </footer>
  </div>
</body>
</html>

</body>
</html>
