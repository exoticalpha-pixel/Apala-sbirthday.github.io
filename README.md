# Apala-sbirthday.github.io
Happy birthday 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happy Birthday!</title>
  <style>
    body {
      background: linear-gradient(to right, #fbc2eb, #a6c1ee);
      text-align: center;
      font-family: 'Segoe UI', sans-serif;
      color: #333;
      padding: 50px;
    }

    h1 {
      font-size: 3em;
      color: #ff69b4;
    }

    p {
      font-size: 1.5em;
    }

    .cake {
      font-size: 100px;
      animation: bounce 1s infinite;
    }

    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-15px); }
    }

    .wish-box {
      background: white;
      padding: 20px;
      margin-top: 30px;
      border-radius: 15px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
      display: inline-block;
    }

    .friend-photo {
      width: 200px;
      border-radius: 50%;
      margin-bottom: 20px;
      box-shadow: 0 0 10px #fff;
    }

    .gift-button {
      margin-top: 20px;
      background-color: #ff69b4;
      color: white;
      padding: 12px 24px;
      font-size: 1em;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      transition: 0.3s;
    }

    .gift-button:hover {
      background-color: #ff1493;
    }

    /* Fireworks style (CSS only for demo) */
    .firework {
      position: fixed;
      top: 10px;
      left: 50%;
      transform: translateX(-50%);
      font-size: 50px;
      animation: explode 1s ease-in-out infinite;
    }

    @keyframes explode {
      0% { transform: translateY(0) scale(1); opacity: 1; }
      100% { transform: translateY(-100px) scale(1.5); opacity: 0; }
    }
  </style>
</head>
<body>

  <audio autoplay loop>
    <source src="https://www.bensound.com/bensound-music/bensound-celebration.mp3" type="audio/mpeg">
    Your browser does not support the audio tag.
  </audio>

  <div class="firework">🎆</div>
  <div class="cake">🎂</div>
  <h1>Happy Birthday!</h1>

  <img src="https://via.placeholder.com/200x200.png?text=Friend+Photo" class="friend-photo" alt="Friend Photo">

  <div class="wish-box">
    <p>Dear Friend,</p>
    <p>On your special day, I just want to say...</p>
    <p><strong>May your life be filled with joy, love, and cake! 🍰</strong></p>
    <p>🎉 Enjoy every moment of your birthday! 🎈</p>
    <p>— From Mahran 💖</p>

    <button class="gift-button" onclick="alert('🎁 Surprise! A big virtual hug and your favorite treat!')">
      🎁 Click to open your gift
    </button>
  </div>

</body>
</html>
