<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <title>Menu Chức Năng Game</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #111;
      color: #fff;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 20px;
    }

    h1 {
      color: #00ffff;
      margin-bottom: 20px;
    }

    .feature {
      background: #222;
      border-radius: 10px;
      padding: 15px 20px;
      margin: 10px 0;
      display: flex;
      justify-content: space-between;
      align-items: center;
      width: 300px;
      box-shadow: 0 0 10px rgba(0, 255, 255, 0.3);
    }

    .switch {
      position: relative;
      width: 50px;
      height: 25px;
    }

    .switch input {
      opacity: 0;
      width: 0;
      height: 0;
    }

    .slider {
      position: absolute;
      cursor: pointer;
      top: 0; left: 0;
      right: 0; bottom: 0;
      background-color: #555;
      transition: .4s;
      border-radius: 25px;
    }

    .slider:before {
      position: absolute;
      content: "";
      height: 19px; width: 19px;
      left: 3px;
      bottom: 3px;
      background-color: white;
      transition: .4s;
      border-radius: 50%;
    }

    input:checked + .slider {
      background-color: #00ffff;
    }

    input:checked + .slider:before {
      transform: translateX(24px);
    }

    .note {
      margin-top: 30px;
      color: #aaa;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <h1>Menu Chức Năng ⚙</h1>

  <div class="feature"><span>Nhẹ Tâm</span><label class="switch"><input type="checkbox"><span class="slider"></span></label></div>
  <div class="feature"><span>Bám Tâm</span><label class="switch"><input type="checkbox"><span class="slider"></span></label></div>
  <div class="feature"><span>Bám Đầu</span><label class="switch"><input type="checkbox"><span class="slider"></span></label></div>
  <div class="feature"><span>Fix Rung</span><label class="switch"><input type="checkbox"><span class="slider"></span></label></div>
  <div class="feature"><span>Fix Lố</span><label class="switch"><input type="checkbox"><span class="slider"></span></label></div>
  <div class="feature"><span>Nhạy Tâm</span><label class="switch"><input type="checkbox"><span class="slider"></span></label></div>
  <div class="feature"><span>Fake AimlockDagV1⚡︎☠</span><label class="switch"><input type="checkbox"><span class="slider"></span></label></div>
  <div class="feature"><span>Tối Ưu FPS</span><label class="switch"><input type="checkbox"><span class="slider"></span></label></div>
  <div class="feature"><span>Tối Ưu Điện Thoại</span><label class="switch"><input type="checkbox"><span class="slider"></span></label></div>

  <div class="note">Kéo nút qua phải để bật ☑ | qua trái để tắt ☐</div>
</body>
</html>
