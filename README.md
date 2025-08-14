<!doctype html>
<html lang="ko">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>나의 홈페이지</title>
  <meta name="description" content="GitHub Pages로 만든 간단한 개인 홈페이지" />
  <link rel="stylesheet" href="styles.css" />
  <link rel="icon" href="data:;base64,iVBORw0KGgo=" /> <!-- 임시 파비콘 -->
</head>
<body>
  <header class="site-header">
    <div class="container">
      <a class="brand" href="/">MySite</a>
      <nav class="nav">
        <a href="#about">소개</a>
        <a href="#projects">프로젝트</a>
        <a href="#contact">연락처</a>
        <button id="themeToggle" aria-label="테마 전환">🌓</button>
      </nav>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="container">
        <h1>안녕하세요 👋</h1>
        <p>이 사이트는 <strong>GitHub Pages</strong>로 배포되었습니다.</p>
        <a class="btn" href="https://github.com/" target="_blank" rel="noreferrer">GitHub 살펴보기</a>
      </div>
    </section>

    <section id="about" class="section">
      <div class="container">
        <h2>소개</h2>
        <p>
          간단한 정적 사이트 템플릿입니다. <code>index.html</code>, <code>styles.css</code>,
          <code>script.js</code> 세 파일만으로 구성되어 있어 유지보수가 쉽습니다.
        </p>
      </div>
    </section>

    <section id="projects" class="section">
      <div class="container">
        <h2>프로젝트</h2>
        <ul class="cards">
          <li class="card">
            <h3>프로젝트 A</h3>
            <p>설명 텍스트. 깔끔한 카드 UI.</p>
            <a href="#" class="card-link">자세히</a>
          </li>
          <li class="card">
            <h3>프로젝트 B</h3>
            <p>설명 텍스트. 링크만 교체하면 끝.</p>
            <a href="#" class="card-link">자세히</a>
          </li>
          <li class="card">
            <h3>프로젝트 C</h3>
            <p>설명 텍스트. 필요 없으면 삭제.</p>
            <a href="#" class="card-link">자세히</a>
          </li>
        </ul>
      </div>
    </section>

    <section id="contact" class="section">
      <div class="container">
        <h2>연락처</h2>
        <ul>
          <li>Email: <a href="mailto:you@example.com">you@example.com</a></li>
          <li>GitHub: <a href="https://github.com/your-id" target="_blank" rel="noreferrer">@your-id</a></li>
        </ul>
      </div>
    </section>

    <!-- (선택) 댓글 달기: Giscus 사용 예시
      1) https://giscus.app 에서 자신의 리포로 설정값 생성
      2) 아래 스크립트의 data-* 값 교체 후 주석 해제
    -->
    <!--
    <section class="section">
      <div class="container">
        <h2>댓글</h2>
        <script src="https://giscus.app/client.js"
          data-repo="your-id/your-repo"
          data-repo-id="REPO_ID"
          data-category="General"
          data-category-id="CATEGORY_ID"
          data-mapping="pathname"
          data-strict="0"
          data-reactions-enabled="1"
          data-emit-metadata="0"
          data-input-position="bottom"
          data-theme="light"
          data-lang="ko"
          crossorigin="anonymous"
          async>
        </script>
      </div>
    </section>
    -->
  </main>

  <footer class="site-footer">
    <div class="container">
      <small>© <span id="year"></span> MySite. Powered by GitHub Pages.</small>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
