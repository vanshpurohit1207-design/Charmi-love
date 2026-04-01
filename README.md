# Charmi-love
I love you charmii
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>For Charmi ❤️</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: linear-gradient(to right, #ff9a9e, #fad0c4);
      color: #fff;
      text-align: center;
    }

    .container {
      padding: 50px 20px;
    }

    h1 {
      font-size: 3em;
      animation: fadeIn 2s ease-in-out;
    }

    p {
      font-size: 1.5em;
      max-width: 700px;
      margin: 20px auto;
      animation: fadeIn 3s ease-in-out;
    }

    .heart {
      font-size: 50px;
      animation: heartbeat 1.5s infinite;
    }

    button {
      background: #ff4d6d;
      border: none;
      padding: 15px 25px;
      font-size: 18px;
      color: white;
      border-radius: 30px;
      cursor: pointer;
      margin-top: 20px;
      transition: 0.3s;
    }

    button:hover {
      background: #ff1e4d;
    }

    #hiddenMessage {
      display: none;
      margin-top: 30px;
      font-size: 1.8em;
      animation: fadeIn 2s ease-in-out;
    }

    @keyframes heartbeat {
      0% { transform: scale(1); }
      50% { transform: scale(1.3); }
      100% { transform: scale(1); }
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>Hey Charmi ❤️</h1>
    <div class="heart">💖</div>

    <p>
      From the moment you came into my life, everything started feeling more beautiful.
      Your smile, your voice, your presence — everything about you makes my world better.
    </p>

    <p>
      I may not always say it perfectly, but I truly love you more than words can explain.
      You are my happiness, my peace, and my favorite person in this world.
    </p>

    <button onclick="showMessage()">Click here ❤️</button>

    <div id="hiddenMessage">
      I LOVE YOU SO MUCH CHARMI 💕
    </div>
  </div>

  <script>
    function showMessage() {
      document.getElementById("hiddenMessage").style.display = "block";
    }
  </script>

</body>
</html>
