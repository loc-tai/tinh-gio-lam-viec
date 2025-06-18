<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hết tiền rồi 😢</title>
  <style>
    body {
      background: linear-gradient(135deg, #f093fb, #f5576c);
      color: white;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      text-align: center;
      padding-top: 100px;
      animation: fadeIn 2s ease-in-out;
    }

    h1 {
      font-size: 4rem;
      margin-bottom: 20px;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
    }

    p {
      font-size: 1.5rem;
    }

    .money-icon {
      font-size: 5rem;
      animation: bounce 1s infinite;
    }

    @keyframes bounce {
      0%, 100% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-15px);
      }
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <div class="money-icon">💸</div>
  <h1>Hết tiền rồi!</h1>
  <p>Ví trống không, chờ ngày lĩnh lương thôi 😭</p>
</body>
</html>

