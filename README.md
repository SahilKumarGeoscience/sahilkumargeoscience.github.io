<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <title>Sahil Kumar | EGU 2026 Research Profile</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: linear-gradient(135deg, #eef4f8, #f8fafc);
      color: #1f2933;
    }

    .page {
      max-width: 980px;
      margin: auto;
      padding: 24px;
    }

    .card {
      background: rgba(255, 255, 255, 0.95);
      border-radius: 24px;
      padding: 34px;
      box-shadow: 0 15px 40px rgba(0, 0, 0, 0.10);
      animation: fadeUp 0.9s ease forwards;
    }

    @keyframes fadeUp {
      from {
        opacity: 0;
        transform: translateY(28px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .header {
      text-align: center;
    }

    .profile {
      width: 155px;
      height: 155px;
      border-radius: 50%;
      object-fit: cover;
      border: 5px solid #e5edf3;
      box-shadow: 0 10px 25px rgba(0,0,0,0.15);
      animation: softPulse 3s infinite ease-in-out;
    }

    @keyframes softPulse {
      0%, 100% {
        transform: scale(1);
        box-shadow: 0 10px 25px rgba(0,0,0,0.15);
      }
      50% {
        transform: scale(1.035);
        box-shadow: 0 14px 35px rgba(31,78,121,0.25);
      }
    }

    h1 {
      margin: 18px 0 6px;
      font-size: 36px;
      color: #102a43;
    }

    .subtitle {
      font-size: 18px;
      color: #52606d;
      margin-bottom: 10px;
    }

    .affiliation {
      font-size: 15px;
      color: #627d98;
      margin-bottom: 26px;
    }

    .poster-title {
      background: linear-gradient(135deg, #123c69, #1f4e79);
      color: white;
      padding: 24px;
      border-radius: 18px;
      margin: 28px 0;
      animation: fadeIn 1.2s ease forwards;
    }

    .poster-title small {
      display: block;
      font-size: 14px;
      opacity: 0.85;
      margin-bottom: 10px;
      letter-spacing: 0.5px;
    }

    .poster-title strong {
      font-size: 23px;
      line-height: 1.35;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    .buttons {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 14px;
      margin: 28px 0;
    }

    .button {
      display: block;
      padding: 16px 18px;
      border-radius: 14px;
      text-decoration: none;
      color: white;
      font-weight: bold;
      font-size: 16px;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    .button:hover {
      transform: translateY(-4px);
      box-shadow: 0 10px 25px rgba(0,0,0,0.18);
    }

    .poster { background: #8a2f2f; }
    .abstract { background: #2f6f4e; }
    .linkedin { background: #0a66c2; }
    .cv { background: #333333; }

    .section {
      margin-top: 30px;
      padding: 22px;
      background: #f8fafc;
      border-radius: 18px;
      border-left: 5px solid #1f4e79;
      animation: fadeUp 1s ease forwards;
    }

    .section h2 {
      margin-top: 0;
      color: #102a43;
      font-size: 22px;
    }

    .section p {
      line-height: 1.65;
      font-size: 16px;
      color: #334e68;
    }

    .highlight {
      font-weight: bold;
      color: #8a2f2f;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 14px;
      margin-top: 18px;
    }

    .mini-card {
      background: white;
      padding: 18px;
      border-radius: 16px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.07);
      text-align: center;
      transition: transform 0.2s ease;
    }

    .mini-card:hover {
      transform: translateY(-4px);
    }

    .mini-card strong {
      display: block;
      color: #1f4e79;
      font-size: 22px;
      margin-bottom: 6px;
    }

    .mini-card span {
      color: #52606d;
      font-size: 14px;
    }

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 15px;
    }

    .tag {
      background: #e6eef6;
      color: #1f4e79;
      padding: 8px 12px;
      border-radius: 999px;
      font-size: 14px;
      font-weight: bold;
    }

    .contact {
      text-align: center;
      margin-top: 35px;
      color: #52606d;
      line-height: 1.7;
    }

    footer {
      text-align: center;
      margin-top: 24px;
      font-size: 13px;
      color: #829ab1;
    }

    @media (max-width: 700px) {
      .page {
        padding: 14px;
      }

      .card {
        padding: 22px;
        border-radius: 18px;
      }

      h1 {
        font-size: 30px;
      }

      .poster-title strong {
        font-size: 19px;
      }

      .buttons {
        grid-template-columns: 1fr;
      }

      .grid {
        grid-template-columns: 1fr;
      }

      .profile {
        width: 135px;
        height: 135px;
      }
    }
  </style>
</head>

<body>
  <div class="page">
    <div class="card">

      <div class="header">
        <img class="profile"
          src="https://github.com/user-attachments/assets/d9bb628f-b378-437f-854c-69b2036c3bdb"
          alt="Sahil Kumar">

        <h1>Sahil Kumar</h1>

        <div class="subtitle">
          M.Sc. Geoscience · Landscape Evolution Modelling · Geomorphology
        </div>

        <div class="affiliation">
          University of Tübingen · Department of Geosciences · Germany
        </div>
      </div>

      <div class="poster-title">
        <small>EGU 2026 Research Profile · Final Poster Title</small>
        <strong>
          Sensitivity of Escarpment Evolution to Lithology and Climate Forcing:<br>
          Forward Landscape Evolution Study from the Swabian Alb
        </strong>
      </div>

      <div class="buttons">
        <a class="button poster" href="Sahil_Kumar_EGU2026_Final_Poster.pdf" target="_blank">
          Final Poster PDF
        </a>

        <a class="button abstract" href="#" target="_blank">
          EGU Abstract — Public Link Coming Soon
        </a>

        <a class="button linkedin" href="https://www.linkedin.com/in/sahil-kumar-0767a2110/" target="_blank">
          LinkedIn Profile
        </a>

        <a class="button cv" href="Sahil_Kumar_CV.pdf" target="_blank">
          Short Academic CV
        </a>
      </div>

      <div class="section">
        <h2>Why this work matters</h2>
        <p>
          Long-term surface stability depends not only on how much erosion occurs, but also on
          <span class="highlight">where erosion remains focused</span>. My work investigates whether future erosion
          in the Swabian Alb is randomly distributed or persistently concentrated along specific geomorphic zones.
        </p>
        <p>
          The main result is clear: high-magnitude erosion remains concentrated along the
          <span class="highlight">Albtrauf escarpment</span>, while the plateau interior remains comparatively stable.
          Lithology controls the spatial pattern, while climate mainly amplifies incision in channels that are already active.
        </p>
      </div>

      <div class="grid">
        <div class="mini-card">
          <strong>1 Myr</strong>
          <span>forward simulation horizon</span>
        </div>

        <div class="mini-card">
          <strong>1,728</strong>
          <span>model ensemble simulations</span>
        </div>

        <div class="mini-card">
          <strong>250 m</strong>
          <span>landscape evolution model grid</span>
        </div>
      </div>

      <div class="section">
        <h2>Research snapshot</h2>
        <p>
          My master’s thesis applies numerical landscape evolution modelling to study future development of the
          Swabian Alb in southwestern Germany. The work combines DEM data, lithological information,
          precipitation forcing, uplift scenarios, and forward modelling to analyse erosion hotspots,
          escarpment retreat, plateau stability, and drainage-divide migration.
        </p>

        <div class="tags">
          <span class="tag">Landlab</span>
          <span class="tag">Python</span>
          <span class="tag">MATLAB</span>
          <span class="tag">TopoToolbox</span>
          <span class="tag">QGIS</span>
          <span class="tag">Geomorphology</span>
          <span class="tag">Erosion Hotspots</span>
          <span class="tag">Swabian Alb</span>
        </div>
      </div>

      <div class="section">
        <h2>Poster and abstract information</h2>
        <p>
          <strong>Final poster title:</strong><br>
          Sensitivity of Escarpment Evolution to Lithology and Climate Forcing:
          Forward Landscape Evolution Study from the Swabian Alb
        </p>

        <p>
          <strong>Submitted EGU abstract title:</strong><br>
          Sensitivity of Escarpment Evolution to Lithology and Climate Forcing:
          Forward Landscape Evolution Study from the Swabian Alb
        </p>

        <p>
          <strong>Version note:</strong>
          The EGU abstract is the official submitted version. The final poster represents the updated presentation
          version prepared after thesis refinement, figure updates, and interpretation improvements. Minor differences
          in wording, structure, figures, and emphasis may exist, but the scientific focus remains the same.
        </p>
      </div>

      <div class="section">
        <h2>Open to research discussion</h2>
        <p>
          I am interested in research opportunities, collaborations, and discussions related to numerical landscape
          evolution modelling, geomorphology, GIS-based spatial analysis, erosion processes, and
          lithology–climate–topography interactions.
        </p>
      </div>

      <div class="contact">
        <strong>Contact</strong><br>
        Sahil Kumar · M.Sc. Geoscience<br>
        Tübingen, Germany<br>
        Email: <a href="mailto:shilsagwal@gmail.com">shilsagwal@gmail.com</a><br>
        LinkedIn:
        <a href="https://www.linkedin.com/in/sahil-kumar-0767a2110/" target="_blank">
          sahil-kumar-0767a2110
        </a>
      </div>

      <footer>
        EGU 2026 · Geomorphology · Numerical Landscape Evolution Modelling
      </footer>

    </div>
  </div>
</body>
</html>
