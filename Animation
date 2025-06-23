<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Animation Rolex</title>
  <style>
    body {
      margin: 0;
      background: black;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      overflow: hidden;
      perspective: 1000px;
    }

    .watch-container {
      width: 300px;
      height: 300px;
      background-image: url('https://i.imgur.com/6jG3zXY.png'); /* Image style Rolex */
      background-size: cover;
      background-position: center;
      border-radius: 50%;
      position: relative;
      animation: zoomRotate 6s ease-in-out forwards;
      transform-style: preserve-3d;
    }

    @keyframes zoomRotate {
      0% {
        transform: scale(1) rotateY(0deg);
      }
      100% {
        transform: scale(1.6) rotateY(30deg);
      }
    }

    .hand {
      position: absolute;
      width: 2px;
      height: 40%;
      background: white;
      top: 10%;
      left: 50%;
      transform-origin: bottom center;
      transform: rotate(0deg);
      animation: rotateHand 4s linear forwards;
    }

    @keyframes rotateHand {
      from {
        transform: rotate(0deg);
      }
      to {
        transform: rotate(360deg);
      }
    }
  </style>
</head>
<body>
  <div class="watch-container">
    <div class="hand"></div>
  </div>
</body>
</html>
