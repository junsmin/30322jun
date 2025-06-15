<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>대구 역사와 독립운동가 이야기</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@400;700&display=swap');

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Noto Sans KR', sans-serif;
      margin: 0;
      padding: 0;
      background: url('https://upload.wikimedia.org/wikipedia/commons/thumb/2/2b/Flag_of_South_Korea.svg/2560px-Flag_of_South_Korea.svg.png') no-repeat center center fixed;
      background-size: cover;
      color: #2c3e50;
      line-height: 1.7;
    }

    /* 시작 화면 */
    #start-screen {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      background: rgba(255, 255, 255, 0.8);
      text-align: center;
      padding: 20px;
      box-sizing: border-box;
    }

    #start-screen img {
      max-width: 250px;
      animation: pulse 3s infinite;
      margin-bottom: 30px;
      border-radius: 16px;
      box-shadow: 0 0 20px rgba(0,0,0,0.2);
    }

    @keyframes pulse {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.05); }
    }

    #start-screen h1 {
      font-size: 2.5rem;
      color: #1a5276;
      margin-bottom: 40px;
    }

    #start-screen .btn-container {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      justify-content: center;
    }

    #start-screen button {
      cursor: pointer;
      background-color: #2980b9;
      color: white;
      border: none;
      border-radius: 10px;
      padding: 12px 20px;
      font-size: 1rem;
      font-weight: 700;
      display: flex;
      align-items: center;
      gap: 8px;
      box-shadow: 0 4px 8px rgba(41, 128, 185, 0.5);
      transition: background-color 0.3s ease;
    }

    #start-screen button:hover {
      background-color: #1a3f61;
    }

    /* 메인 컨텐츠 스타일 */
    main {
      max-width: 900px;
      margin: 60px auto 80px auto;
      background-color: rgba(255, 255, 255, 0.95);
      padding: 40px;
      border-radius: 16px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }

    h1, h2 {
      color: #1a5276;
      border-bottom: 2px solid #2980b9;
      padding-bottom: 6px;
    }

    h1 {
      margin-bottom: 1rem;
      text-align: center;
      animation: fadeIn 2s ease-in-out;
    }

    section {
      margin-bottom: 2.5rem;
      background-color: #ffffff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
      animation: slideUp 1s ease-in-out;
    }

    ul {
      margin-top: 0.3rem;
    }

    ul li {
      margin-bottom: 0.5rem;
    }

    img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
      border: 1px solid #ccc;
      margin-top: 1rem;
    }

    footer {
      margin-top: 3rem;
      font-size: 0.9rem;
      color: #777;
      text-align: center;
      border-top: 1px solid #ddd;
      padding-top: 10px;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes slideUp {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

  <!-- 배경음악 (애국가) -->
  <audio autoplay loop>
    <source src="https://upload.wikimedia.org/wikipedia/commons/6/65/National_Anthem_of_South_Korea.ogg" type="audio/ogg">
    브라우저가 오디오를 지원하지 않습니다.
  </audio>

  <!-- 시작 화면 -->
  <section id="start-screen">
    <img src="태극기.jpg" alt="태극기" />
    <h1>대구 역사와 독립운동가 이야기</h1>
    <div class="btn-container">
      <button onclick="scrollToSection('main')">🏠 도입부</button>
      <button onclick="scrollToSection('choi')">📖 최제우 선생</button>
      <button onclick="scrollToSection('jang')">💣 장진홍 선생</button>
      <button onclick="scrollToSection('game')">🕵️ 일본경찰과 독립운동가</button>
    </div>
  </section>

  <!-- 본문 -->
  <main id="main">
    <section>
      <h2>1. 도입부</h2>
      <ul>
        <li>대구의 역사적 장소와 동학 창시자 최제우 선생, 독립운동가 장진홍 선생을 소개.</li>
        <li>그들의 숨결이 서린 의미 깊은 장소를 배경으로 활동형 게임을 통해 이야기 전달.</li>
      </ul>
    </section>

    <section id="choi">
      <h2>2. 동학과 최제우 선생님 소개</h2>
      <ul>
        <li>19세기 말 최제우 선생님이 동학을 창시.</li>
        <li>‘인내천’, 즉 ‘사람이 곧 하늘이다’라는 평등사상으로 민중에게 희망 제공.</li>
      </ul>
      <img src="순도비.jpg" alt="동학 교조 수운 최제우 순도비" />
      <p>
        위 사진은 <strong>동학 교조 수운 최제우 순도비</strong>입니다. 이 비석은 대구 중구에서 순국한 최제우 선생님의 희생을 기리기 위해 세워졌습니다.
        그분의 동학 사상은 이후의 항일 운동과 민권 운동에도 큰 영향을 끼쳤습니다.
      </p>
      <h3>💬 활동: 동학 토론 게임</h3>
      <p>학생들은 두 팀으로 나뉘어 토론을 진행합니다.</p>
      <ul>
        <li><strong>A팀:</strong> 동학 사상이 조선 사회에 긍정적인 영향을 주었다는 입장</li>
        <li><strong>B팀:</strong> 동학 사상은 긍정적이지만 한계도 있었다는 입장</li>
      </ul>
      <p>토론을 통해 최제우 선생님의 사상이 오늘날에도 어떤 의미를 갖는지 함께 생각해 봅니다.</p>
    </section>

    <section id="jang">
      <h2>3. 장진홍 선생과 조선은행 대구지점</h2>
      <ul>
        <li>이곳은 장진홍 선생님이 일제의 식민 지배에 저항하며 활동했던 조선은행 대구지점입니다.</li>
        <li>그는 일제의 경제 중심지를 상대로 폭탄을 던져, 강력한 항일 의지를 보여주었습니다.</li>
        <li>이 용기 있는 행동은 독립운동사에 있어 큰 의미를 지니며, 후대에 강한 영감을 주었습니다.</li>
      </ul>
      <img src="장진홍흉상.jpg" alt="순국의사 장진홍 선생 흉상" />
      <p>
        사진 속 인물은 <strong>순국의사 장진홍 선생</strong>의 흉상과 기념비입니다. 이 흉상은 대구 중구 조선은행 터에 세워져 있으며,
        선생님의 용기와 희생을 기리고 있습니다.
      </p>
      <h3>🎲 활동: 폭탄 돌리기 보드게임</h3>
      <p>
        학생들이 원을 이루어 앉고, ‘폭탄’을 상징하는 물건을 돌립니다.<br />
        음악이 멈추거나 타이머가 울리면, 폭탄을 들고 있는 학생은 <strong>실존 독립운동가의 이름을 한 명 외칩니다</strong>.
      </p>
      <ul>
        <li>예: 장진홍, 유관순, 안중근, 김구 등</li>
        <li>게임을 통해 독립운동가들의 이름과 업적을 자연스럽게 기억할 수 있습니다.</li>
      </ul>
      <p>※ 활동 후, 학생들이 언급한 인물을 간단히 소개해 주면 효과가 더욱 큽니다.</p>
    </section>

    <section id="game">
      <h2>4. 일본 경찰과 독립운동가 게임</h2>
      <p>
        총 4명이 참여하는 팀 게임입니다. 게임 시작 전 <strong>가위바위보</strong>를 통해 2명은 일본 경찰, 2명은 독립운동가 역할을 맡습니다.
      </p>
      <ul>
        <li>경찰은 독립운동가를 쫓고, <strong>잡히면 "얼음"</strong>이 되어 움직일 수 없습니다.</li>
        <li>다른 독립운동가가 "땡!" 하고 터치하면 얼음이 풀립니다.</li>
        <li>제한 시간 내 모든 독립운동가가 얼음이 되면 경찰 승리, 한 명이라도 살아남으면 독립운동가 승리!</li>
      </ul>
      <p>
        마지막에는 모두 함께 <strong>태극기를 들고 “대한독립만세!”를 외치며</strong>, 독립운동가의 희생을 기립니다.
      </p>
    </section>

    <footer>
      제작: 30320 정민재 | 30322 최민준
    </footer>
  </main>

  <script>
    // 버튼 클릭 시 해당 섹션으로 부드럽게 스크롤 이동
    function scrollToSection(id) {
      // main까지 스크롤할 때 시작화면 숨김 처리(선택사항)
      const startScreen = document.getElementById('start-screen
