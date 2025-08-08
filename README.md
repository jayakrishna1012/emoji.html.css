# emoji.html.css
emoji

![Image 2025-08-07 at 14 51 44_aa97f5b4](https://github.com/user-attachments/assets/a902735a-82e0-4fc6-946e-4c14a04cbac6)




<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Pig Emoji</title>
  <style>
    body {
      background-color: #e6f2f2;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .pig {
      position: relative;
      width: 200px;
      height: 200px;
      background-color: #ffb6c1;
      border-radius: 50%;
    }

    .ear {
      position: absolute;
      width: 60px;
      height: 60px;
      background-color: #ffb6c1;
      border-radius: 50%;
      top: -30px;
    }

    .ear.left {
      left: -10px;
    }

    .ear.right {
      right: -10px;
    }

    .eye {
      position: absolute;
      width: 30px;
      height: 30px;
      background-color: white;
      border-radius: 50%;
      top: 50px;
    }

    .eye::after {
      content: "";
      position: absolute;
      top: 8px;
      left: 8px;
      width: 12px;
      height: 12px;
      background-color: black;
      border-radius: 50%;
    }

    .eye.left {
      left: 40px;
    }

    .eye.right {
      right: 40px;
    }

    .snout {
      position: absolute;
      width: 80px;
      height: 50px;
      background-color: #ff69b4;
      border-radius: 25px;
      bottom: 40px;
      left: 50%;
      transform: translateX(-50%);
    }

    .nostril {
      position: absolute;
      width: 15px;
      height: 20px;
      background-color: black;
      border-radius: 50%;
      top: 15px;
    }

    .nostril.left {
      left: 15px;
    }

    .nostril.right {
      right: 15px;
    }
  </style>
</head>
<body>
  <div class="pig">
    <div class="ear left"></div>
    <div class="ear right"></div>
    <div class="eye left"></div>
    <div class="eye right"></div>
    <div class="snout">
      <div class="nostril left"></div>
      <div class="nostril right"></div>
    </div>
  </div>
</body>
</html>
