# -shop

<!DOCTYPE html><html lang="th">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>ไอตี๋ Shop | ขายไก่ตัน Blox Fruits</title>
  <style>
    body {
      font-family: 'Kanit', sans-serif;
      margin: 0;
      padding: 0;
      background: #f8f9fa;
    }
    header {
      background: #1f2937;
      color: #fff;
      text-align: center;
      padding: 20px;
    }
    header img {
      max-width: 120px;
    }
    h1 {
      margin: 10px 0 5px;
    }
    .product {
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      margin: 20px;
      padding: 15px;
    }
    .product img {
      width: 100%;
      border-radius: 12px;
    }
    .product h2 {
      margin-top: 10px;
    }
    .product p {
      margin: 5px 0;
    }
    .product button, .discord-button {
      background: #5865F2;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 8px;
      cursor: pointer;
      font-size: 16px;
    }
    .discord-button {
      margin: 20px;
      display: inline-block;
    }
    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <img src="ไอตี๋โลโก้.png" alt="ไอตี๋โลโก้">
    <h1>ไอตี๋ Shop</h1>
    <p>ขายไก่ตัน Blox Fruits ตึงๆ ราคาดี ของแน่น</p>
  </header>  <div class="container">
    <div class="product">
      <img src="sample_kaaitan.jpg" alt="บัญชีไก่ตัน">
      <h2>ไก่ตัน LV.2550</h2>
      <p>ผล: เสือ | อาวุธ: Cursed Dual Katana</p>
      <p>หมัดครบ, เผ่า V4</p>
      <p><strong>ราคา: 150฿</strong></p>
      <button>สั่งซื้อเลย</button>
    </div>
    <div class="product">
      <img src="sample_kaaitan2.jpg" alt="บัญชีไก่ตัน">
      <h2>ไก่ตันเทพ V4</h2>
      <p>ผล: มังกร | อาวุธ: Shisui + Skull Guitar</p>
      <p>ครบทุกสาย PVP</p>
      <p><strong>ราคา: 250฿</strong></p>
      <button>สั่งซื้อเลย</button>
    </div>
  </div>  <div style="text-align: center;">
    <a href="https://discord.gg/HtQaRjpF" class="discord-button">ติดต่อผ่าน Discord</a>
  </div>
</body>
</html>
