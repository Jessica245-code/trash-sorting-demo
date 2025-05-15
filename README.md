
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>分類結果</title>
  <style>
    body {
      font-family: sans-serif;
      text-align: center;
      background-color: #f2f2f2;
      margin: 0;
      padding: 2em;
    }
    .message {
      font-size: 2em;
      margin-bottom: 1em;
    }
    .correct {
      color: green;
    }
    .wrong {
      color: red;
    }
    .celebrate {
      animation: flash 1s ease-in-out infinite alternate;
      font-size: 2em;
      color: gold;
    }
    @keyframes flash {
      from { background-color: gold; }
      to { background-color: white; }
    }
  </style>
</head>
<body>
  <div id="result"><div class="message celebrate">🎉 全部分類完成！</div></div>
  <audio id="sound" autoplay src="3.mp3"></audio>
</body>
</html>
