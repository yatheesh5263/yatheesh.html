# yatheesh.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Image5 positions</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      height: 100vh;
      display: flex;
      flex-direction: column;
    }

    .container {
      flex: 1;
      position: relative;
    }

 .image {
      position: absolute;
      max-width: 100%;
      max-height: 100%;
    }

    .top-left {
      top: 0;
      left: 0;
    }

    .top-right {
      top: 0;
      right: 0;
    }

    .bottom-left {
      bottom: 0;
      left: 0;
    }

    .bottom-right {
      bottom: 0;
      right: 0;
    }

    .center {
      top: 50%;
      left: 50%;
      transform: translate(50%, 50%);
    }
  </style>
</head>
<body>
  <div class="container">
    <img src=" first.jpg " alt="Image 1" class="image top-left">
    <img src=" 2.jpg " alt="Image 2" class="image top-right">
    <img src=" bg.jpg " alt="Image 3" class="image bottom-left">
    <img src=" un.jpg " alt="Image 4" class="image bottom-right">
    <img src=" robert.jpg " alt="yatheesh pawan kumar" class="image center">
  </div>
</body>
</html>
