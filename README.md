mr_HACKED
<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <title>🤣 ল্যাগ মজা 🤣</title>
  <style>
    body {
      margin: 0;
      overflow: hidden;
      background: black;
      color: white;
      font-family: sans-serif;
    }
    .emoji {
      position: absolute;
      font-size: 30px;
      animation: fall linear infinite;
    }
    @keyframes fall {
      from { transform: translateY(-50px); }
      to { transform: translateY(100vh); }
    }
  </style>
</head>
<body>
  <h1 style="text-align:center;">⚡ ফোন ল্যাগ মজা শুরু হলো ⚡</h1>
  <script>
    function randomEmoji() {
      const emojis = ["😂","🤣","🔥","😱","💀","👻","🤯","🐸","🌀","⭐"];
      return emojis[Math.floor(Math.random() * emojis.length)];
    }

    function createEmoji() {
      const span = document.createElement("span");
      span.className = "emoji";
      span.textContent = randomEmoji();
      span.style.left = Math.random() * window.innerWidth + "px";
      span.style.animationDuration = (Math.random() * 3 + 2) + "s";
      document.body.appendChild(span);

      setTimeout(() => span.remove(), 5000);
    }

    // প্রতি মিলিসেকেন্ডে ইমোজি বানাও 😆
    setInterval(createEmoji, 5);
  </script>
</body>
</html>
