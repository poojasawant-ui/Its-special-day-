# Its-special-day-
Its Sumits special Day <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Happy Birthday Advocate Sumit</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #0f172a, #1e293b, #7c3aed);
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      overflow: hidden;
      color: white;
    }

    .card {
      width: 90%;
      max-width: 700px;
      background: rgba(255,255,255,0.1);
      backdrop-filter: blur(12px);
      border-radius: 25px;
      padding: 40px;
      text-align: center;
      box-shadow: 0 0 30px rgba(255,255,255,0.2);
      animation: glow 3s infinite alternate;
    }

    @keyframes glow {
      from {
        box-shadow: 0 0 20px rgba(255,255,255,0.2);
      }
      to {
        box-shadow: 0 0 40px rgba(255,255,255,0.6);
      }
    }

    h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }

    h2 {
      color: #facc15;
      margin-bottom: 25px;
    }

    p {
      font-size: 1.2rem;
      line-height: 1.8;
    }

    .btn {
      margin-top: 30px;
      display: inline-block;
      padding: 15px 30px;
      border-radius: 50px;
      background: #facc15;
      color: black;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn:hover {
      transform: scale(1.1);
      background: white;
    }

    .heart {
      position: absolute;
      color: rgba(255,255,255,0.5);
      animation: float 6s linear infinite;
      font-size: 24px;
    }

    @keyframes float {
      0% {
        transform: translateY(100vh);
        opacity: 0;
      }
      100% {
        transform: translateY(-10vh);
        opacity: 1;
      }
    }
  </style>
</head>
<body>

  <div class="card">
    <h1>🎂 Happy Birthday 🎂</h1>
    <h2>Advocate Sumit ⚖️❤️</h2>

    <p>
      Happy Birthday to the only advocate who can easily win arguments…
      and my attention too 😌⚖️❤️
    </p>

    <p>
      To my favorite advocate — if charm was a court case,
      you’d win every single hearing without evidence 😌⚖️
    </p>

    <p>
      Wishing the most handsome advocate endless success, happiness,
      and smiles today and always ✨
    </p>

    <a class="btn" href="#">
      💌 Open Your Special Birthday Verdict 💌
    </a>
  </div>

  <script>
    function createHeart() {
      const heart = document.createElement('div');
      heart.classList.add('heart');
      heart.innerHTML = '❤️';
      heart.style.left = Math.random() * 100 + 'vw';
      heart.style.animationDuration = (Math.random() * 3 + 3) + 's';
      document.body.appendChild(heart);

      setTimeout(() => {
        heart.remove();
      }, 6000);
    }

    setInterval(createHeart, 300);
  </script>

</body>
</html>
