<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>For Sanika 💜</title>

  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital@0;1&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      padding: 0;
      min-height: 100vh;
      background: linear-gradient(135deg, #ffe6f0, #f6f1eb, #f2e6ff);
      font-family: 'Playfair Display', serif;
      display: flex;
      justify-content: center;
      align-items: center;
      color: #4a3f3f;
      ;
    }

    /* FLOWING PINK HEARTS */
    .heart {
      position: absolute;
      width: 16px;
      height: 16px;
      background: rgba(255, 105, 180, 0.35);
      transform: rotate(45deg);
      animation: float 4s linear infinite;
    }

    .heart::before,
    .heart::after {
      content: '';
      position: absolute;
      width: 16px;
      height: 16px;
      background: rgba(255, 105, 180, 0.35);
      border-radius: 50%;
    }

    .heart::before {
      top: -8px;
      left: 0;
    }

    .heart::after {
      left: -8px;
      top: 0;
    }

    @keyframes float {
      0% {
        transform: translateY(80vh) rotate(45deg);
        opacity: 0;
      }
      10% { opacity: 1; }
      100% {
        transform: translateY(-5vh) rotate(45deg);
        opacity: 0;
      }
    }

    .card {
      background: rgba(255, 255, 255, 0.88);
      backdrop-filter: blur(8px);
      padding: 50px 60px;
      max-width: 620px;
      border-radius: 20px;
      box-shadow: 0 25px 50px rgba(0,0,0,0.08);
      line-height: 1.8;
      z-index: 10;
    }

    h1 {
      text-align: center;
      font-size: 34px;
      margin-bottom: 30px;
      color: #6b4c6f;
    }

    p {
      font-size: 18px;
      margin-bottom: 20px;
    }

    .signature {
      margin-top: 35px;
      text-align: right;
      font-size: 18px;
      color: #6b4c6f;
      font-style: italic;
    }

    .date {
      text-align: center;
      margin-top: 25px;
      font-size: 14px;
      color: #9a8f8f;
    }
  </style>
</head>
<body>

  <!-- FAST FLOWING HEARTS -->
  <script>
    for (let i = 0; i < 40; i++) {
      const heart = document.createElement("div");
      heart.className = "heart";
      heart.style.left = Math.random() * 100 + "vw";
      heart.style.animationDuration = (3 + Math.random() * 2) + "s";
      heart.style.animationDelay = Math.random() * 1.5 + "s";
      document.body.appendChild(heart);
    }
  </script>

<div class="card">
    <h1>For Sanika ✨</h1>

    <p>
      Hi Sanika,
    </p>

    <p>
      This little note exists for one simple reason — you.
      No big speeches, no heavy meanings… just something soft, like you.
    </p>

    <p>
      You have this quiet way of making moments feel lighter.
      Even on days that feel messy, your presence feels calm —
      like a pause the world needed.
    </p>

    <p>
      You don’t always realize it, but you make people feel seen,
      heard, and comfortable just by being yourself.
      That’s rare. And that’s beautiful.
    </p>

    <p>
      On your birthday, just remember this —
      you don’t have to be anything more than who you already are.
      You’re doing just fine.
    </p>

    <p>
      Happy Birthday, Sanika 💞  
      May this year bring you gentle happiness,
      small wins, and many reasons to smile.
    </p>

    <p>
      And whenever you read this again —
      I hope it feels like a quiet reminder that you matter.
    </p>

    <div class="signature">
      — always cheering for you
    </div>

    <div class="date">
      13 January
    </div>
  </div>

</body>
</html>
