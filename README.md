
<html lang="ko">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>야구록 / Baseball Log</title>
  <meta
    name="description"
    content="야구록(Baseball Log) 공식 안내 페이지입니다. 개인정보처리방침과 이용약관을 확인할 수 있습니다."
  />
  <style>
    :root {
      --bg: #f7f4ee;
      --card: #fffaf2;
      --card-strong: #ffffff;
      --text: #2a2118;
      --muted: #6f6257;
      --accent: #8a5a2b;
      --accent-dark: #5f3d1d;
      --border: rgba(42, 33, 24, 0.12);
      --shadow: rgba(42, 33, 24, 0.08);
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      min-height: 100vh;
      background:
        radial-gradient(circle at top left, rgba(138, 90, 43, 0.12), transparent 36%),
        linear-gradient(180deg, #f7f4ee 0%, #efe6d8 100%);
      color: var(--text);
      font-family: -apple-system, BlinkMacSystemFont, "Apple SD Gothic Neo", "Noto Sans KR",
        "Segoe UI", sans-serif;
      line-height: 1.68;
    }

    main {
      width: min(920px, calc(100% - 40px));
      margin: 0 auto;
      padding: 56px 0 72px;
    }

    .hero {
      padding: 34px 30px;
      background: rgba(255, 250, 242, 0.92);
      border: 1px solid var(--border);
      border-radius: 28px;
      box-shadow: 0 20px 60px var(--shadow);
    }

    .badge {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      margin-bottom: 18px;
      padding: 7px 12px;
      border-radius: 999px;
      background: #ffffff;
      border: 1px solid var(--border);
      color: var(--accent-dark);
      font-size: 13px;
      font-weight: 700;
      letter-spacing: -0.02em;
    }

    h1 {
      margin: 0;
      font-size: clamp(34px, 7vw, 58px);
      line-height: 1.08;
      letter-spacing: -0.055em;
    }

    .subtitle {
      margin: 14px 0 0;
      color: var(--muted);
      font-size: clamp(16px, 2.8vw, 19px);
      letter-spacing: -0.025em;
    }

    .description {
      max-width: 720px;
      margin: 24px 0 0;
      color: var(--text);
      font-size: 16px;
      letter-spacing: -0.02em;
    }

    .actions {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      margin-top: 30px;
    }

    .button {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      min-height: 48px;
      padding: 0 18px;
      border-radius: 16px;
      border: 1px solid var(--border);
      text-decoration: none;
      font-size: 15px;
      font-weight: 700;
      letter-spacing: -0.02em;
      transition: transform 0.16s ease, box-shadow 0.16s ease, background 0.16s ease;
    }

    .button:hover {
      transform: translateY(-1px);
      box-shadow: 0 10px 26px rgba(42, 33, 24, 0.10);
    }

    .button.primary {
      background: var(--accent);
      border-color: var(--accent);
      color: #ffffff;
    }

    .button.secondary {
      background: #ffffff;
      color: var(--accent-dark);
    }

    .info-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 12px;
      margin-top: 18px;
    }

    .info-card {
      padding: 18px;
      background: var(--card-strong);
      border: 1px solid var(--border);
      border-radius: 20px;
    }

    .info-card strong {
      display: block;
      margin-bottom: 6px;
      font-size: 14px;
      color: var(--text);
      letter-spacing: -0.025em;
    }

    .info-card span {
      display: block;
      color: var(--muted);
      font-size: 14px;
      letter-spacing: -0.02em;
    }

    footer {
      margin-top: 28px;
      padding: 20px 4px 0;
      color: var(--muted);
      font-size: 14px;
      text-align: center;
    }

    footer a {
      color: var(--accent-dark);
      text-underline-offset: 3px;
    }

    @media (max-width: 720px) {
      main {
        width: min(100% - 28px, 920px);
        padding: 30px 0 48px;
      }

      .hero {
        padding: 26px 20px;
        border-radius: 24px;
      }

      .actions {
        flex-direction: column;
      }

      .button {
        width: 100%;
      }

      .info-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
  <main>
    <section class="hero" aria-labelledby="page-title">
      <div class="badge">SS54 · Baseball Log</div>

      <h1 id="page-title">야구록<br />Baseball Log</h1>

      <p class="subtitle">
        경기기록, 일정, 연습기록을 관리하는 야구 기록 앱
      </p>

      <p class="description">
        야구록은 사용자의 야구 경기기록, 일정, 연습기록, 선수 카드와 팀 정보를 관리하기 위한 앱입니다.
        이 페이지에서는 야구록의 개인정보처리방침과 이용약관을 확인할 수 있습니다.
      </p>

      <div class="actions" aria-label="문서 바로가기">
        <a class="button primary" href="/privacy">개인정보처리방침 보기</a>
        <a class="button secondary" href="/terms">이용약관 보기</a>
      </div>
    </section>

    <section class="info-grid" aria-label="앱 정보">
      <div class="info-card">
        <strong>앱 이름</strong>
        <span>야구록 / Baseball Log</span>
      </div>

      <div class="info-card">
        <strong>운영자</strong>
        <span>SS54</span>
      </div>

      <div class="info-card">
        <strong>문의</strong>
        <span>ss54.baseballlog@gmail.com</span>
      </div>
    </section>

    <footer>
      <p>
        문의:
        <a href="mailto:ss54.baseballlog@gmail.com">ss54.baseballlog@gmail.com</a>
      </p>
      <p>© SS54. All rights reserved.</p>
    </footer>
  </main>
</body>
</html>
