<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Pinakkhi Kar — Resume</title>

  <!-- Google font (internet available) -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --accent:#0b6efd;
      --muted:#6b7280;
      --page-bg:#f6f7fb;
      --card-bg:#ffffff;
      --border:#e6e9ef;
      --max-w:900px;
      --padding:24px;
      font-family: "Inter", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }

    html,body{
      height:100%;
      margin:0;
      background:var(--page-bg);
      color:#111827;
    }

    .wrap{
      max-width:var(--max-w);
      margin:28px auto;
      padding:18px;
    }

    .resume{
      background:linear-gradient(180deg, rgba(255,255,255,0.8), rgba(255,255,255,1));
      border:1px solid var(--border);
      border-radius:10px;
      overflow:hidden;
      display:flex;
      box-shadow:0 8px 30px rgba(15,23,42,0.06);
    }

    /* Left column */
    .left{
      width:34%;
      min-width:240px;
      background:linear-gradient(180deg,#ffffff,#fbfdff);
      padding:var(--padding);
      border-right:1px solid var(--border);
    }

    .photo{
      width:110px;
      height:110px;
      border-radius:8px;
      background:linear-gradient(135deg,var(--accent),#7cc1ff);
      display:flex;
      align-items:center;
      justify-content:center;
      color:white;
      font-weight:700;
      font-size:20px;
      margin-bottom:14px;
      box-shadow:0 6px 18px rgba(11,110,253,0.12);
    }

    .name{
      font-size:20px;
      font-weight:700;
      margin:6px 0 2px;
      letter-spacing:0.2px;
    }
    .role{
      font-size:13px;
      color:var(--muted);
      margin-bottom:12px;
    }

    .contact-list, .side-section{
      margin-top:8px;
      font-size:14px;
    }
    .side-section h4{
      margin:14px 0 8px;
      font-size:13px;
      color:var(--muted);
      letter-spacing:0.6px;
      text-transform:uppercase;
    }
    .side-section p, .contact-list p{
      margin:6px 0;
      line-height:1.45;
    }
    .small{
      color:var(--muted);
      font-size:13px;
    }

    /* Right column */
    .right{
      width:66%;
      padding:var(--padding);
    }

    .section{
      margin-bottom:18px;
    }
    .section h3{
      margin:0 0 8px;
      font-size:15px;
      color:var(--accent);
      letter-spacing:0.6px;
    }

    .keyinfo{
      display:flex;
      gap:12px;
      flex-wrap:wrap;
    }

    .info-row{
      display:flex;
      justify-content:space-between;
      border-bottom:1px dashed #eef2ff;
      padding:10px 0;
    }

    .education-table{
      width:100%;
      border-collapse:collapse;
      margin-top:8px;
      font-size:14px;
    }
    .education-table th, .education-table td{
      border:1px solid var(--border);
      padding:8px 10px;
      text-align:left;
    }
    .education-table th{
      background:#fbfdff;
      color:var(--muted);
      font-weight:600;
      font-size:13px;
    }

    .bullet{
      margin:6px 0;
      line-height:1.6;
    }

    .footer-row{
      display:flex;
      justify-content:space-between;
      align-items:center;
      margin-top:22px;
    }
    .signature{
      width:220px;
      border-top:1px solid #c7cbd6;
      text-align:center;
      padding-top:6px;
      font-size:13px;
      color:var(--muted);
    }

    /* print friendly */
    @media print{
      body{background:white;}
      .wrap{margin:0;box-shadow:none;}
      .resume{box-shadow:none;border:none;}
    }

    /* responsive */
    @media (max-width:800px){
      .resume{flex-direction:column;}
      .left,.right{width:100%}
      .left{border-right:none;border-bottom:1px solid var(--border)}
    }

    /* action buttons */
    .actions{
      display:flex;
      gap:8px;
      margin-bottom:12px;
      justify-content:flex-end;
      padding-right:6px;
    }
    .btn{
      border:0;
      padding:8px 12px;
      border-radius:8px;
      cursor:pointer;
      font-weight:600;
      font-size:13px;
    }
    .btn.print{background:var(--accent); color:white;}
    .btn.pdf{background:#f1f5f9; color:#0b6efd; border:1px solid #e2e8f0;}
  </style>
</head>
<body>

  <div class="wrap">
    <div class="actions">
      <button class="btn print" onclick="window.print()">Print / Save PDF</button>
      <button class="btn pdf" onclick="downloadHTML()">Download HTML</button>
    </div>

    <div class="resume" id="resume">
      <!-- LEFT -->
      <aside class="left" aria-label="left column">
        <div style="display:flex;align-items:center;gap:12px">
          <div class="photo" aria-hidden="true">PK</div>
          <div>
            <div class="name">Pinakkhi Kar</div>
            <div class="role">B.A. (Hons) — Appearing</div>
            <div class="small">Fresher — Seeking office/administrative roles</div>
          </div>
        </div>

        <div class="contact-list">
          <div style="margin-top:12px;">
            <div class="small">Phone</div>
            <p>+91 6290508801</p>
          </div>

          <div style="margin-top:8px;">
            <div class="small">Email</div>
            <p>pinakkhikar@gmail.com</p>
          </div>

          <div style="margin-top:8px;">
            <div class="small">Address</div>
            <p style="font-size:13px;line-height:1.3">
              Bogapara, Jagannath Nagar,<br>
              P.S. Maheshtala, P.O. Jagannath Nagar,<br>
              South 24 Parganas, Kolkata - 700141
            </p>
          </div>
        </div>

        <div class="side-section">
          <h4>Personal</h4>
          <p><strong>Father's Name:</strong> Pradip Kar</p>
          <p><strong>D.O.B:</strong> 13/10/2002</p>
          <p><strong>Nationality:</strong> Indian</p>
          <p><strong>Religion:</strong> Hinduism</p>
          <p><strong>Marital Status:</strong> Unmarried</p>
          <p><strong>Category:</strong> General</p>
        </div>

        <div class="side-section">
          <h4>Languages</h4>
          <p>Bengali, Hindi &amp; English</p>
        </div>

      </aside>

      <!-- RIGHT -->
      <main class="right" aria-label="main column">
        <section class="section">
          <h3>Professional Summary</h3>
          <p class="bullet">
            Responsible, motivated fresher with basic computer knowledge and strong communication skills in Bengali, Hindi and English. Looking for entry-level office/administrative or data-entry roles where I can learn and contribute.
          </p>
        </section>

        <section class="section">
          <h3>Educational Background</h3>

          <table class="education-table" aria-label="education table">
            <thead>
              <tr>
                <th>Examination</th>
                <th>Board / University</th>
                <th>Year of Passing</th>
                <th>Percentage</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>Secondary</td>
                <td>W.B.B.S.E</td>
                <td>2017</td>
                <td>44.42%</td>
              </tr>
              <tr>
                <td>Higher Secondary</td>
                <td>W.B.C.H.S.E</td>
                <td>2019</td>
                <td>51%</td>
              </tr>
              <tr>
                <td>B.A. (Hons)</td>
                <td>Calcutta University (C.U)</td>
                <td>Appearing</td>
                <td>—</td>
              </tr>
            </tbody>
          </table>
        </section>

        <section class="section">
          <h3>Skills & Computer</h3>
          <p class="bullet"><strong>Computer:</strong> Basic knowledge of computer (MS Office basics, typing, internet).</p>
          <p class="bullet"><strong>Other skills:</strong> Good verbal communication, punctual, quick learner.</p>
        </section>

        <section class="section">
          <h3>Work Experience</h3>
          <p class="bullet"><strong>Fresher</strong> — No formal work experience yet. Eager to start and learn on the job.</p>
        </section>

        <section class="section">
          <h3>Declaration</h3>
          <p class="bullet small">
            I hereby declare that all the information furnished above is true to the best of my knowledge.
          </p>

          <div class="footer-row">
            <div>
              <div class="small">Place: Kolkata</div>
              <div class="small">Date: ____________________</div>
            </div>

            <div class="signature">Signature</div>
          </div>
        </section>
      </main>
    </div>
  </div>

<script>
  function downloadHTML(){
    const html = document.documentElement.outerHTML;
    const blob = new Blob([html], {type: "text/html"});
    const a = document.createElement("a");
    a.href = URL.createObjectURL(blob);
    a.download = "Pinakkhi_Kar_Resume.html";
    a.click();
    URL.revokeObjectURL(a.href);
  }
</script>
</body>
</html>
