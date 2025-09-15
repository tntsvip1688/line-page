<!DOCTYPE html>
<html lang="zh-TW">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>加入我的 LINE 公眾號</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 50px;
      background: #f8f9fa;
    }
    h1 {
      color: #06C755; /* LINE 綠 */
    }
    button {
      display: block;
      width: 250px;
      margin: 20px auto;
      padding: 15px;
      font-size: 16px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
    .copy-btn {
      background: #06C755;
      color: white;
    }
    .line-btn {
      background: #00BFFF;
      color: white;
    }
  </style>
</head>
<body>
  <h1>加入我的 LINE 公眾號</h1>
  <p>公眾號 ID：<strong>@529fnyrn</strong></p>
  
  <button class="copy-btn" onclick="copyText()">📋 一鍵複製 ID</button>
  <button class="line-btn" onclick="addLine()">💬 直接加好友</button>

  <script>
    function copyText() {
      const text = "@529fnyrn";
      navigator.clipboard.writeText(text).then(() => {
        alert("已複製 ID: " + text);
      });
    }
    function addLine() {
      window.location.href = "https://line.me/R/ti/p/@529fnyrn";
    }
  </script>
</body>
</html>
