<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Colour Trading Prediction Game</title>
  <style>
    body { font-family: Arial, text-align: center; padding: 30px; }
    button { padding: 10px 20px; margin: 10px; }
    #result { font-size: 24px; margin-top: 20px; }
  </style>
</head>
<body>
  <h1>Colour Trading Prediction</h1>
  <p>Choose: Big (5-9) or Small (0-4)</p>
  <button onclick="makePrediction('Big')">Big</button>
  <button onclick="makePrediction('Small')">Small</button>

  <div id="result"></div>

  <script>
    function makePrediction(choice) {
      const number = Math.floor(Math.random() * 10); // 0 to 9
      const outcome = number >= 5 ? 'Big' : 'Small';

      let message = `Number: ${number} (${outcome})<br>`;
      message += (choice === outcome) ? "<b style='color: green'>You Win!</b>" : "<b style='color: red'>You Lose!</b>";

      document.getElementById('result').innerHTML = message;
    }
  </script>
</body>
</html>
