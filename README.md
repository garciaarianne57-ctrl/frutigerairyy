<!DOCTYPE html>
<html>
<head>
  <title>frutiger bio</title>

  <style>
    body {
      margin: 0;
      height: 100vh;
      overflow: hidden;
      font-family: Arial, sans-serif;
      color: #0b1b2b;
      display: flex;
      justify-content: center;
      align-items: center;

      /* Aero gradient sky */
      background: linear-gradient(180deg, #b7f0ff 0%, #e6fff7 40%, #c9f7ff 100%);
    }

    /* soft bubble effects */
    .bubble {
      position: absolute;
      width: 80px;
      height: 80px;
      background: rgba(255,255,255,0.4);
      border-radius: 50%;
      filter: blur(1px);
      animation: float 8s infinite ease-in-out;
    }

    .b1 { top: 10%; left: 15%; }
    .b2 { top: 60%; left: 70%; width: 120px; height: 120px; }
    .b3 { top: 30%; left: 80%; }

    @keyframes float {
      0% { transform: translateY(0px); }
      50% { transform: translateY(-20px); }
      100% { transform: translateY(0px); }
    }

    /* glass panel */
    .panel {
      position: relative;
      padding: 35px;
      border-radius: 25px;
      background: rgba(255,255,255,0.35);
      backdrop-filter: blur(12px);
      box-shadow: 0 10px 40px rgba(0,0,0,0.15);
      text-align: center;
      width: 280px;
    }

    h1 {
      margin: 0;
      font-size: 26px;
      letter-spacing: 1px;
    }

    p {
      margin-top: 10px;
      opacity: 0.75;
      font-size: 14px;
    }

    a {
      display: block;
      margin-top: 12px;
      color: #0066cc;
      text-decoration: none;
      font-weight: bold;
    }

    a:hover {
      color: #00aaff;
    }

    .badge {
      margin-top: 15px;
      font-size: 12px;
      opacity: 0.6;
    }
  </style>
</head>

<body>

  <div class="bubble b1"></div>
  <div class="bubble b2"></div>
  <div class="bubble b3"></div>

  <div class="panel">
    <h1>your name</h1>
    <p>🌊 floating in a frutiger aero world</p>

    <a href="#">instagram</a>
    <a href="#">tiktok</a>
    <a href="#">spotify</a>

    <div class="badge">.png • .mp4 • digital life</div>
  </div>

</body>
</html>
