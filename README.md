<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
   <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Animated Webpage</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      text-align: center;
      background-color: #f2f2f2;
    }

    /* Animation 1: Fade In Header */
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    header {
      background-color: #333;
      color: white;
      padding: 30px;
      font-size: 2em;
      animation: fadeIn 2s ease-in;
    }

    /* Animation 2: Bouncing Button */
    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-15px); }
    }

    .animated-button {
      margin-top: 50px;
      padding: 15px 30px;
      font-size: 18px;
      background-color: #2196F3;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      animation: bounce 1.5s infinite;
    }

    .animated-button:hover {
      background-color: #0b7dda;
    }
  </style>
</head>
<body>

  <header>
    Welcome to My Animated Page
  </header>

  <button class="animated-button">Click Me</button>

</body>
</html> 
</body>
</html> 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
</body>
</html> 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Custom Video Player</title>
  <style>
    body {
      background-color: #121212;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
      font-family: Arial, sans-serif;
    }

    .video-container {
      position: relative;
      width: 80%;
      max-width: 800px;
      background: #000;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
    }

    video {
      width: 100%;
      border-radius: 10px;
      display: block;
    }
.controls {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 10px;
      background: rgba(0, 0, 0, 0.7);
      position: absolute;
      bottom: 0;
      width: 100%;
    }

    .controls button {
      background: none;
      border: none;
      color: white;
      font-size: 20px;
      cursor: pointer;
    }

    .controls input[type="range"] {
      width: 100px;
    }
  </style>
</head>
<body>

  <div class="video-container">
    <video id="video" src="sample.mp4"></video>

    <div class="controls">
      <button id="playPause">▶</button>
      <input type="range" id="seekBar" value="0"ss
