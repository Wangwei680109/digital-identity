<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>王维的修行碑</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: #f8f8f8;
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 20px;
      text-align: center;
    }
    .container {
      max-width: 90%;
      background: rgba(0, 0, 0, 0.5);
      backdrop-filter: blur(10px);
      border-radius: 20px;
      padding: 30px;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
    }
    h1 {
      font-size: 2.5rem;
      margin-bottom: 20px;
      text-shadow: 0 0 15px rgba(0, 255, 250, 0.7);
    }
    .kungfu {
      display: inline-block;
      padding: 0 10px;
      animation: glow 2s infinite alternate;
    }
    @keyframes glow {
      0% { text-shadow: 0 0 5px #fff; }
      100% { text-shadow: 0 0 20px #00fffa, 0 0 30px #0080ff; }
    }
    p {
      font-size: 1.2rem;
      margin: 20px 0;
      line-height: 1.6;
    }
    .taichi-btn {
      background: linear-gradient(135deg, #6a11cb, #2575fc);
      color: white;
      text-decoration: none;
      padding: 15px 40px;
      border-radius: 50px;
      display: inline-block;
      margin: 30px 0;
      font-weight: bold;
      font-size: 1.2rem;
      box-shadow: 0 5px 20px rgba(37, 117, 252, 0.5);
      transition: all 0.3s ease;
    }
    .taichi-btn:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 25px rgba(37, 117, 252, 0.7);
    }
    .date {
      color: #00fffa;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>✨ <span class="kungfu">王维</span> ✨</h1>
    <p>于<span class="date"><script>document.write(new Date().toLocaleDateString())</script></span>拜入师门</p>
    <a href="https://github.dev/Wangwei680109/digital-identity" class="taichi-btn">
      点击开启修炼
    </a>
    <p>道在指尖流转<br>码于屏上生花</p>
  </div>
</body>
</html>