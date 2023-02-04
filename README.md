<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>My GitHub Profile Page</title>
  <style>
    body {
      background-image: linear-gradient(to bottom, #000000, #6f42c1);
      background-repeat: no-repeat;
      background-size: cover;
      height: 100vh;
      font-family: 'Star Jedi', sans-serif;
      color: #fff;
      text-align: center;
    }
    h1 {
      font-size: 50px;
      margin-top: 100px;
    }
    .container {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100%;
    }
    .star {
      animation: twinkle 1s ease-in-out infinite;
      color: #fff;
      font-size: 50px;
      margin: 0 10px;
    }
    @keyframes twinkle {
      from {
        opacity: 1;
      }
      50% {
        opacity: 0.5;
      }
      to {
        opacity: 1;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>
      <i class="star">✰</i>
      Welcome to my GitHub Profile 
      <i class="star">✰</i>
    </h1>
  </div>
</body>
</html>
