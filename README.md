<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>Thông tin cá nhân</title>
  <style>
    body {
      font-family: sans-serif;
      background: #f0f0f0;
      padding: 20px;
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }
    .card {
      display: block; /* để thẻ <a> hoạt động như một khối */
      background: white;
      border: 1px solid #ccc;
      border-radius: 5px;
      padding: 10px;
      width: 250px;
      text-align: center;
      text-decoration: none; /* bỏ gạch chân mặc định của link */
      color: black; /* giữ màu chữ */
      transition: transform 0.2s;
    }
    .card:hover {
      transform: scale(1.05); /* hiệu ứng khi rê chuột */
    }
    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 5px;
    }
    .card h3 {
      margin: 10px 0 5px;
    }
    .card p {
      margin: 3px 0;
    }
  </style>
</head>
<body>

  <a href="https://example.com/gia-minh" target="_blank" class="card">
    <img src="gia-minh.jpg" alt="Nguyễn Vũ Gia Minh">
    <h3>Nguyễn Vũ Gia Minh</h3>
    <p>Ngày sinh: 19/12/2008</p>
    <p>Nơi sinh: Quảng Ngãi</p>
    <p>Sở thích: chơi game, nghe nhạc</p>
  </a>

  <a href="https://example.com/thanh-tra" target="_blank" class="card">
    <img src="thanh-tra.jpg" alt="Lê Thị Thanh Trà">
    <h3>Lê Thị Thanh Trà</h3>
    <p>Ngày sinh: 07/11/2008</p>
    <p>Nơi sinh: Quảng Ngãi</p>
    <p>Sở thích: vẽ tranh, xem phim</p>
  </a>

  <a href="https://example.com/minh-tri" target="_blank" class="card">
    <img src="minh-tri.jpg" alt="Trịnh Minh Trí">
    <h3>Trịnh Minh Trí</h3>
    <p>Ngày sinh: 18/10/2008</p>
    <p>Nơi sinh: Quảng Ngãi</p>
    <p>Sở thích: chơi game, học lập trình</p>
  </a>

  <a href="https://example.com/duy-duc" target="_blank" class="card">
    <img src="duy-duc.jpg" alt="Lê Duy Đức">
    <h3>Lê Duy Đức</h3>
    <p>Ngày sinh: 01/01/2008</p>
    <p>Nơi sinh: Quảng Ngãi</p>
    <p>Sở thích: đá bóng, chơi game</p>
  </a>

</body>
</html>
