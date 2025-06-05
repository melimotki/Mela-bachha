# Mela-bachha
<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <title>Meli Pyali Motki 😘</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(120deg, #fbc2eb 0%, #a6c1ee 100%);
      overflow: hidden;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .container {
      background: rgba(255, 255, 255, 0.7);
      border-radius: 20px;
      padding: 40px;
      box-shadow: 0 8px 32px rgba(0, 0, 0, 0.2);
      text-align: center;
      max-width: 600px;
      animation: fadeInSlide 1.5s ease-out;
    }

    h1 {
      font-size: 1.8rem;
      color: #ff4081;
      animation: pulse 2.5s infinite;
    }

    p {
      font-size: 1.1rem;
      margin: 10px 0;
      color: #444;
    }

    h2 {
      margin-top: 20px;
      font-size: 1.5rem;
      color: #6a1b9a;
    }

    .heart {
      font-size: 3rem;
      animation: heartbeat 1.5s infinite;
      color: red;
    }

    @keyframes heartbeat {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }

    @keyframes fadeInSlide {
      0% {
        opacity: 0;
        transform: translateY(30px);
      }
      100% {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes pulse {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.05); }
    }

    .bubble {
      position: absolute;
      background: rgba(255, 255, 255, 0.3);
      border-radius: 50%;
      animation: floatUp 10s infinite ease-in-out;
      pointer-events: none;
    }

    @keyframes floatUp {
      0% {
        transform: translateY(100vh) scale(0.5);
        opacity: 0;
      }
      50% {
        opacity: 0.6;
      }
      100% {
        transform: translateY(-10vh) scale(1.2);
        opacity: 0;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="heart">❤️</div>
    <h1>main tumhare drd ka andaaza bhi lga skta babu 🥺</h1>
    <p>Pr bhulo mt tum bhut strong ho 😊</p>
    <p>tu meri pgli ho ☺️</p>
    <p>Apna khyaal rkho 😃</p>
    <p>aur jab Mann ho to mujhe call krna jrur 🫂</p>
    <p>Main tumhare liye 24 Ghnta free hun 🤗</p>
    <p>Mujhe bhut dukh h ki main is waqt tumhare pas nhi hun 😥😩🤦😭</p>
    <p>Kaas koi aesa rasta hota jisse ham dono is waqt saath hote ☺️🥺🥺🥺</p>
    <p><strong>Pr tum apna khyaal rkho ☺️😃</strong></p>
    <h2>~ meli pyali motki 😘😘</h2>
  </div>

  <!-- Floating bubbles -->
  <script>
    for (let i = 0; i < 20; i++) {
      let bubble = document.createElement('div');
      bubble.classList.add('bubble');
      let size = Math.random() * 40 + 10;
      bubble.style.width = size + "px";
      bubble.style.height = size + "px";
      bubble.style.left = Math.random() * 100 + "vw";
      bubble.style.animationDuration = (Math.random() * 5 + 10) + "s";
      document.body.appendChild(bubble);
    }
  </script>
</body>
</html>
