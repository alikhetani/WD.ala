<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Butterfly Animation</title>
  <style>
    body {
      margin: 0;
      overflow: hidden;
      background: linear-gradient(to top, #87ceeb, #ffffff);
      height: 100vh;
    }

    .butterfly {
      position: absolute;
      width: 60px;
      height: 60px;
      background-image: url('wd.webp');
      background-size: cover;
      animation: fly 15s linear infinite;
    }

    @keyframes fly {
      0% {
        transform: translate(-100px, 60vh) rotate(0deg);
      }
      25% {
        transform: translate(30vw, 30vh) rotate(10deg);
      }
      50% {
        transform: translate(60vw, 50vh) rotate(-10deg);
      }
      75% {
        transform: translate(90vw, 20vh) rotate(15deg);
      }
      100% {
        transform: translate(120vw, 60vh) rotate(0deg);
      }
    }
  </style>
</head>
<body>
  <div class="butterfly"></div>

  <script>
    // You can add multiple butterflies or effects later if you like
  </script>
</body>
</html>
