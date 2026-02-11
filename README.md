<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Moon Eyes & Cal — Weekly Political Satire</title>
  <meta name="description" content="Moon Eyes & Cal is a weekly political cartoon observing power, narrative, and consequence through fictional characters." />

  <style>
    :root{
      --bg:#0b1220;
      --panel:#0f1b33;
      --card:#101f3a;
      --text:#eaf0ff;
      --muted:#b8c6ef;
      --line:rgba(255,255,255,.12);
      --shadow:0 14px 34px rgba(0,0,0,.40);
      --radius:18px;
      --max:1100px;
      --accent:#4da3ff;
    }

    *{box-sizing:border-box}
    html,body{height:100%}

    body{
      margin:0;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, sans-serif;
      background: var(--bg);
      color:var(--text);
    }

    a{color:inherit}

    .wrap{
      max-width:var(--max);
      margin:0 auto;
      padding:22px 18px 70px;
    }

    /* WORDMARK */
    .wordmark{
      font-family: Georgia, "Times New Roman", Times, serif;
      font-size: 20px;
      font-weight: 600;
      letter-spacing: 0.3px;
    }
    .wordmark span{
      font-weight: 400;
    }

    /* TOP BAR */
    .topbar{
      display:flex;
      gap:14px;
      align-items:center;
      justify-content:space-between;
      padding:12px 14px;
      border:1px solid var(--line);
      border-radius:16px;
      background:rgba(16,31,58,.75);
      box-shadow: var(--shadow);
      position:sticky;
      top:10px;
      z-index:10;
    }

    .brand{
      display:flex;
      flex-direction:column;
      gap:4px;
      line-height:1.1;
    }

    .brand span{
      font-size:12px;
      color:var(--muted);
    }

    .nav{
      display:flex;
      gap:10px;
      flex-wrap:wrap;
    }

    .pill{
      text-decoration:none;
      font-size:13px;
      padding:8px 12px;
      border:1px solid var(--line);
      border-radius:999px;
      background:rgba(15,27,51,.65);
    }

    /* HERO */
    .hero{
      margin-top:18px;
      border:1px solid var(--line);
      border-radius:24px;
      background:rgba(16,31,58,.60);
      box-shadow: var(--shadow);
    }

    .heroInner{
      padding:22px;
    }

    .hero h1{
      margin:0 0 10px;
      font-size:26px;
    }

    .hero p{
      margin:0;
      color:var(--muted);
      font-size:14px;
      line-height:1.6;
    }

    /* SECTIONS */
    .section{
      margin-top:22px;
      border:1px solid var(--line);
      border-radius:22px;
      background:rgba(16,31,58,.55);
      box-shadow: var(--shadow);
      overflow:hidden;
    }

    .sectionHead{
      padding:14px 16px;
      border-bottom:1px solid var(--line);
      background:rgba(15,27,51,.70);
    }

    .sectionHead h2{
      margin:0;
      font-size:16px;
    }

    .sectionBody{
      padding:16px;
    }

    /* STRIP DISPLAY (NO CROPPING) */
    .stripMedia{
      width:100%;
      background:rgba(11,18,32,.40);
      border:1px solid var(--line);
      border-radius:16px;
      overflow:hidden;
    }

    .stripMedia img{
      width:100%;
      height:auto;
      display:block;
    }

    .stripInfo{
      margin-top:12px;
      font-size:13px;
      color:var(--muted);
      line-height:1.6;
    }

    /* CHARACTERS */
    .chars{
      display:grid;
      grid-template-columns:1fr 1fr;
      gap:14px;
    }

    .char{
      border:1px solid var(--line);
      border-radius:16px;
      padding:14px;
      background:rgba(15,27,51,.55);
    }

    .char h3{
      margin:0 0 8px;
      font-size:15px;
    }

    .char p{
      margin:0;
      font-size:13px;
      color:var(--muted);
      line-height:1.6;
    }

    /* FOOTER */
    footer{
      margin-top:30px;
      text-align:center;
      font-size:12px;
      color:var(--muted);
    }

    @media (max-width: 800px){
      .chars{
        grid-template-columns:1fr;
      }
      .topbar{
        position:static;
      }
    }
  </style>
</head>

<body>
  <div class="wrap">

    <!-- HEADER -->
    <header class="topbar">
      <div class="brand">
        <strong class="wordmark">Moon Eyes <span>&amp;</span> Cal</strong>
        <span>Weekly political satire • fictional characters • consequence meets narrative</span>
      </div>
      <nav class="nav" aria-label="Primary">
        <a class="pill" href="#latest">Latest</a>
        <a class="pill" href="#characters">Characters</a>
        <a class="pill" href="#archive">Archive</a>
        <a class="pill" href="#about">About</a>
      </nav>
    </header>

    <!-- HERO -->
    <section class="hero">
      <div class="heroInner">
        <h1>We don’t lean. We observe.</h1>
        <p>
          Moon Eyes &amp; Cal is a weekly political cartoon watching how power talks to itself —
          and what reality does in response. Sometimes narrative wins. Sometimes consequence does.
        </p>
      </div>
    </section>

    <!-- LATEST -->
    <section id="latest" class="section">
      <div class="sectionHead">
        <h2>Week One</h2>
      </div>
      <div class="sectionBody">
        <div class="stripMedia">
          <!-- Replace src with your actual image file -->
          <!-- Example: strips/week-one.png -->
          <img src="strips/week-one.png" alt="Moon Eyes & Cal — Week One" />
        </div>
        <div class="stripInfo">
          A discussion about solutions, narratives, and what they leave out.
        </div>
      </div>
    </section>

    <!-- CHARACTERS -->
    <section id="characters" class="section">
      <div class="sectionHead">
        <h2>Characters</h2>
      </div>
      <div class="sectionBody">
        <div class="chars">
          <div class="char">
            <h3>Cal</h3>
            <p>
              Polished, well-informed, and confident in the power of framing.
              Cal believes most problems can be managed — if explained correctly.
            </p>
          </div>
          <div class="char">
            <h3>Moon Eyes</h3>
            <p>
              Quietly intelligent and uninterested in winning arguments.
              Moon Eyes listens, notices patterns, and remarks only when the outcome is already visible.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- ARCHIVE -->
    <section id="archive" class="section">
      <div class="sectionHead">
        <h2>Archive</h2>
      </div>
      <div class="sectionBody">
        <p class="stripInfo">
          Week One — The Deal
        </p>
      </div>
    </section>

    <!-- ABOUT -->
    <section id="about" class="section">
      <div class="sectionHead">
        <h2>About</h2>
      </div>
      <div class="sectionBody">
        <p class="stripInfo">
          This project is a work of political satire using fictional characters.
          It does not advocate positions. It observes outcomes.
        </p>
      </div>
    </section>

    <footer>
      Satire • Fiction • All rights reserved
    </footer>

  </div>
</body>
</html>
