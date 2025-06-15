<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <title>대구 역사와 독립운동가 이야기</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: url('태극기.jpg') no-repeat center center fixed;
      background-size: cover;
      font-family: 'Noto Sans KR', sans-serif;
      text-align: center;
      color: white;
    }

    .overlay {
      background-color: rgba(0,0,0,0.6);
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      gap: 20px;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 30px;
    }

    .btn {
      padding: 15px 30px;
      font-size: 1.2rem;
      background-color: #2980b9;
      color: white;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      transition: transform 0.2s;
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .btn:hover {
      background-color: #1a5276;
      transform: scale(1.05);
    }

    audio {
      position: fixed;
      bottom: 20px;
      left: 20px;
    }
  </style>
</head>
<body>
  <div class="overlay">
    <h1>대구 역사와 독립운동가 이야기</h1>
    <button class="btn" onclick="location.href='choi.html'">📘 최제우 선생</button>
    <button class="btn" onclick="location.href='jang.html'">🎖️ 장진홍 선생</button>
    <button class="btn" onclick="location.href='game.html'">🎮 일본 경찰과 독립운동가</button>
  </div>

  <audio autoplay loop controls>
    <source src="애국가.mp3" type="audio/mpeg">
    브라우저가 오디오 태그를 지원하지 않습니다.
  </audio>
</body>
</html>
