
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>JK | Engineering Portfolio</title>
  <style>
    :root {
      --bg: #0b1220;
      --card: #142137;
      --text: #f8fafc;
      --muted: #a1aec1;
      --accent: #38bdf8;
      --border: #29384d;
    }
    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; }
    body {
      margin: 0;
      background: var(--bg);
      color: var(--text);
      font-family: "Pretendard", "Noto Sans KR",
                   Arial, sans-serif;
      line-height: 1.7;
    }
    a { color: inherit; text-decoration: none; }
    .container {
      width: min(1100px, 90%);
      margin: auto;
    }
    header {
      position: sticky;
      top: 0;
      z-index: 10;
      background: rgba(11,18,32,.94);
      border-bottom: 1px solid var(--border);
      backdrop-filter: blur(12px);
    }
    nav {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 20px 0;
    }
    .logo { font-size: 22px; font-weight: 800; }
    .logo span, .accent { color: var(--accent); }
    .links { display: flex; gap: 25px; }
    .links a:hover { color: var(--accent); }
    .hero {
      min-height: 76vh;
      display: flex;
      align-items: center;
      padding: 80px 0;
    }
    .eyebrow {
      color: var(--accent);
      font-size: 13px;
      letter-spacing: 2px;
      font-weight: bold;
    }
    h1 {
      font-size: clamp(35px, 5vw, 65px);
      line-height: 1.3;
      margin: 20px 0;
      letter-spacing: -2px;
    }
    .hero p {
      max-width: 690px;
      color: var(--muted);
      font-size: 18px;
    }
    .btn {
      display: inline-block;
      margin-top: 25px;
      padding: 13px 25px;
      border-radius: 8px;
      background: var(--accent);
      color: #071320;
      font-weight: bold;
      transition: transform .2s;
    }
    .btn:hover { transform: translateY(-3px); }
    section { padding: 85px 0; }
    h2 { font-size: 32px; margin: 0 0 30px; }
    .intro { color: var(--muted); max-width: 850px; }
    .grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
      margin-top: 30px;
    }
    .card {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 14px;
      padding: 28px;
      transition: transform .2s, border-color .2s;
    }
    .card:hover {
      transform: translateY(-5px);
      border-color: var(--accent);
    }
    .card h3 { margin: 0 0 12px; }
    .card p { color: var(--muted); font-size: 15px; }
    .tag {
      display: inline-block;
      padding: 5px 11px;
      margin: 5px 5px 0 0;
      background: #203650;
      border-radius: 20px;
      color: #bceaff;
      font-size: 12px;
    }
    .stat { font-size: 36px; color: var(--accent); }
    .timeline {
      border-left: 2px solid var(--accent);
      padding-left: 25px;
    }
    .timeline-item { margin-bottom: 35px; }
    .timeline-item small { color: var(--accent); }
    .timeline-item p { color: var(--muted); }
    footer {
      border-top: 1px solid var(--border);
      padding: 35px 0;
      text-align: center;
      color: var(--muted);
      font-size: 13px;
    }
    @media (max-width: 760px) {
      .links { gap: 12px; font-size: 12px; }
      .grid { grid-template-columns: 1fr; }
      .hero { min-height: 65vh; }
      h2 { font-size: 27px; }
    }
  </style>
</head>
<body>
  <header>
    <nav class="container">
      <a href="#" class="logo">JK<span>.</span></a>
      <div class="links">
        <a href="#about">About</a>
        <a href="#experience">Experience</a>
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
      </div>
    </nav>
  </header>

  <main>
    <div class="container hero">
      <div>
        <div class="eyebrow">ELECTRICAL SYSTEM ENGINEER</div>
        <h1>
          기술로 문제를 해결하고,<br>
          <span class="accent">경험으로 더 나은 설계를</span><br>
          만듭니다.
        </h1>
        <p>
          산업차량 전장 시스템 개발, 텔레매틱스,
          품질 검증과 원가 개선까지.
          현장에서 발견한 문제를 다음 개발의
          검증 기준으로 연결하는 엔지니어입니다.
        </p>
        <a href="#projects" class="btn">프로젝트 살펴보기 →</a>
      </div>
    </div>

    <section id="about" class="container">
      <div class="eyebrow">01 / ABOUT ME</div>
      <h2>안녕하세요, 전장설계 엔지니어입니다.</h2>
      <p class="intro">
        HD현대사이트솔루션에서 산업차량 전장 시스템
        개발 업무를 수행하고 있습니다.
        전장 부품 설계와 검증, 차량 통신 및
        원격관리 시스템 개발을 경험했습니다.
        단순히 제품을 개발하는 데 그치지 않고,
        품질과 비용, 생산성을 함께 고려합니다.
      </p>
      <div class="grid">
        <div class="card">
          <div class="stat">2024</div>
          <h3>Career Start</h3>
          <p>산업차량 전장 개발 경력 시작</p>
        </div>
        <div class="card">
          <div class="stat">30%</div>
          <h3>Cost Reduction</h3>
          <p>부품 공급 방식 개선을 통한 원가 절감</p>
        </div>
        <div class="card">
          <div class="stat">100K+</div>
          <h3>Durability Testing</h3>
          <p>스위치 내구 검증 및 잠재 불량 발견</p>
        </div>
      </div>
    </section>

    <section id="experience" class="container">
      <div class="eyebrow">02 / EXPERIENCE</div>
      <h2>Career Journey</h2>
      <div class="timeline">
        <div class="timeline-item">
          <small>2024 — PRESENT</small>
          <h3>HD현대사이트솔루션</h3>
          <p>
            산업차량 전장 시스템 설계 및 개발<br>
            전장 부품 검증, CAN 통신,
            텔레매틱스 시스템 개발
          </p>
        </div>
        <div class="timeline-item">
          <small>ENGINEERING APPROACH</small>
          <h3>문제 해결 중심의 개발</h3>
          <p>
            필드 문제 분석 → 잠재 위험 발굴 →
            검증 기준 수립 → 설계 개선
          </p>
        </div>
      </div>
    </section>

    <section id="projects" class="container">
      <div class="eyebrow">03 / SELECTED PROJECTS</div>
      <h2>주요 프로젝트</h2>
      <div class="grid">
        <article class="card">
          <h3>01. Telematics</h3>
          <p>
            산업차량 원격통신모듈 개발 및
            차량 데이터 모니터링,
            원격 설정 기능 검증
          </p>
          <span class="tag">CAN</span>
          <span class="tag">J1939</span>
          <span class="tag">AWS</span>
        </article>
        <article class="card">
          <h3>02. Quality Improvement</h3>
          <p>
            과거 품질 문제를 바탕으로
            신규 스위치의 잠재 불량을 발견하고
            설계 변경과 재검증 추진
          </p>
          <span class="tag">Validation</span>
          <span class="tag">Reliability</span>
        </article>
        <article class="card">
          <h3>03. Cost Innovation</h3>
          <p>
            부품 공급 구조를 분석하고
            사급 전환을 제안하여
            기존 대비 약 30% 원가 절감
          </p>
          <span class="tag">Cost</span>
          <span class="tag">SCM</span>
        </article>
      </div>
    </section>

    <section id="skills" class="container">
      <div class="eyebrow">04 / TECHNICAL SKILLS</div>
      <h2>기술 역량</h2>
      <div class="card">
        <h3>Engineering & Development</h3>
        <div>
          <span class="tag">CAN / SAE J1939</span>
          <span class="tag">PCAN</span>
          <span class="tag">Telematics</span>
          <span class="tag">Electrical Design</span>
          <span class="tag">NX / Teamcenter</span>
          <span class="tag">DFSS</span>
          <span class="tag">Validation</span>
          <span class="tag">Cybersecurity</span>
        </div>
      </div>
    </section>

    <section class="container">
      <div class="eyebrow">05 / PHILOSOPHY</div>
      <h2>필드 문제를 한 건으로 끝내지 않습니다.</h2>
      <p class="intro">
        하나의 문제를 해결하는 것보다 중요한 것은
        같은 문제가 반복되지 않도록 만드는 것입니다.
        경험을 검증 기준으로 남기고,
        더 신뢰할 수 있는 제품을 개발하겠습니다.
      </p>
    </section>
  </main>

  <footer>
    <div class="container">
      © <span id="year"></span> JK Portfolio.
      Built with curiosity and engineering.
    </div>
  </footer>

  <script>
    document.getElementById("year").textContent =
      new Date().getFullYear();
  </script>
</body>
</html>
