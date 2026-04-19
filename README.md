<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Happy Birthday ❤️</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #ff758c, #ff7eb3);
      color: white;
      text-align: center;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }.container {
  background: rgba(0, 0, 0, 0.4);
  padding: 40px;
  border-radius: 20px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.3);
  max-width: 500px;
}

h1 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

p {
  font-size: 1.2rem;
  margin: 15px 0;
}

button {
  background: white;
  color: #ff4e7a;
  border: none;
  padding: 12px 20px;
  border-radius: 25px;
  font-size: 1rem;
  cursor: pointer;
  transition: 0.3s;
}

button:hover {
  background: #ffe3ec;
}

.hidden-message {
  margin-top: 20px;
  display: none;
  font-size: 1.2rem;
}

  </style>
</head>
<body>
  <div class="container">
    <h1>Happy Birthday My Love 🎂❤️</h1>
    <p>You make my world brighter every single day.</p>
    <p>I'm so lucky to have you in my life 💖</p><button onclick="showMessage()">Click for a surprise 🎁</button>

<div class="hidden-message" id="message">
  I love you more than words can explain. 💕
</div>

  </div>  <script>
    function showMessage() {
      document.getElementById('message').style.display = 'block';
    }
  </script></body>
</html>
