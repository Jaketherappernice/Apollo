<!DOCTYPE html>
<html>
<head>
  <title>Rainbow Text</title>
  <style>
    body {
      background: #111;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    h1 {
      font-size: 3em;
      font-family: 'Arial Black', Arial, sans-serif;
      background: linear-gradient(270deg, #ff5f6d, #ffc371, #47e07f, #43cea2, #185a9d, #ff5f6d);
      background-size: 1200% 1200%;
      color: transparent;
      background-clip: text;
      -webkit-background-clip: text;
      animation: rainbow 4s linear infinite;
    }
    @keyframes rainbow {
      0% { background-position: 0% 50%; }
      100% { background-position: 100% 50%; }
    }
  </style>
</head>
<body>
  <h1>RAINBOW MAGIC!</h1>
</body>
</html>