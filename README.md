
<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>나의 자기소개 페이지</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: "Arial", sans-serif;
      background: linear-gradient(135deg, #e0f2fe, #f8fafc);
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }

    .profile {
      background: white;
      padding: 50px 35px;
      border-radius: 20px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.1);
      text-align: center;
      max-width: 450px;
      width: 90%;
    }

    .avatar {
      font-size: 65px;
      margin-bottom: 15px;
    }

    h1 {
      color: #1e293b;
      margin-bottom: 10px;
    }

    .job {
      color: #2563eb;
      font-weight: bold;
    }

    p {
      color: #64748b;
      line-height: 1.8;
    }

    .tags {
      margin-top: 25px;
    }

    .tag {
      display: inline-block;
      background: #eff6ff;
      color: #2563eb;
      padding: 8px 14px;
      margin: 5px;
      border-radius: 20px;
      font-size: 14px;
    }

    footer {
      margin-top: 30px;
      font-size: 12px;
      color: #94a3b8;
    }
  </style>
</head>

<body>
  <div class="profile">

    <div class="avatar">👨‍💻</div>

    <h1>안녕하세요! 👋</h1>

    <h2>차준근입니다.</h2>

    <div class="job">
      전장설계 엔지니어
    </div>

    <p>
      새로운 기술을 배우고<br>
      다양한 문제를 해결하는 것을 좋아합니다.<br>
      꾸준히 성장하는 사람이 되고 싶습니다.
    </p>

    <div class="tags">
      <span class="tag">💻 기술</span>
      <span class="tag">📚 공부</span>
      <span class="tag">🏸 배드민턴</span>
      <span class="tag">🌍 여행</span>
    </div>

    <footer>
      © 2026 My Personal Page
    </footer>

  </div>
</body>
</html>
