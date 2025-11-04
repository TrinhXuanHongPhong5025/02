<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Trang web đáp ứng đẹp mắt</title>

  <style>

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: "Poppins", "Segoe UI", Arial, sans-serif;
    }


    body {
      min-height: 100vh;
      background: linear-gradient(270deg, #a8edea, #fed6e3);
      background-size: 400% 400%;
      animation: gradientMove 10s ease infinite;
      display: flex;
      justify-content: center;
      align-items: center;
      color: #333;
      overflow-x: hidden;
    }

    @keyframes gradientMove {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      width: 100%;
      max-width: 1200px;
      padding: 20px;
      gap: 20px;
      animation: fadeIn 1.2s ease forwards;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .card {
      background: rgba(255, 255, 255, 0.9);
      border-radius: 16px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      transition: transform 0.4s ease, box-shadow 0.4s ease;
      width: 90%;
      text-align: center;
    }

    .card:hover {
      transform: translateY(-10px) scale(1.03);
      box-shadow: 0 12px 30px rgba(0, 0, 0, 0.2);
    }

    .card img {
      width: 100%;
      height: auto;
      object-fit: cover;
      transition: transform 0.6s ease;
    }

    .card:hover img {
      transform: scale(1.1);
    }

    .card h2 {
      color: #2b4a7d;
      font-size: 1.4rem;
      margin: 15px 0 8px;
    }

    .card p {
      color: #555;
      padding: 0 15px 20px;
      line-height: 1.6;
    }

  
    @media screen and (min-width: 772px) {
      .container {
        flex-direction: row;
        flex-wrap: wrap;
        justify-content: space-around;
      }

      .card {
        width: 45%;
      }

      .card img {
        max-height: 30vh;
      }
    }

   
    @media screen and (min-width: 998px) {
      .card {
        width: 30%;
      }
    }
  </style>
</head>

<body>
  <div class="container">
    <div class="card">
      <img src="https://hoanghamobile.com/tin-tuc/wp-content/uploads/2024/04/anh-ma-kinh-di-1.jpg" alt="Hình 1">
      <h2> 1</h2>
      <p>..---..-......--.---.-.-.--.....-.--.--.</p>
    </div>

    <div class="card">
      <img src="https://preview.redd.it/the-scarlet-king-by-bluewolfartista-v0-o9mbmqz98as81.jpg?width=640&crop=smart&auto=webp&s=ed28c57843295fd6e3320c8276939df94af4e4d0" alt="Hình 2">
      <h2>2</h2>
      <p>.---........------.-........------.....</p>
    </div>

    <div class="card">
      <img src="https://i.pinimg.com/736x/4a/36/c0/4a36c042609d12ca82dc3b3c6c2bcf25.jpg" alt="Hình 3">
      <h2> 3</h2>
      <p>--..-.----..........-------...---------..</p>
    </div>

     <footer>
    <p>© 2025 All Rights Reserved by (<a href="https://www.facebook.com/TP.BaKa"
          style="color: rgb(231, 34, 221);">Gió</a>)</p>
  </footer>

  </div>

  
</body>
</html>
