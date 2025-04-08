<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Google Classroom</title>
  <link rel="icon" href="https://ssl.gstatic.com/classroom/favicon.png">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    html, body {
      margin: 0;
      height: 100%;
      background-color: #f1f3f4;
      font-family: 'Roboto', sans-serif;
    }
    #fake-header {
      background-color: #1a73e8;
      color: white;
      padding: 12px 24px;
      font-size: 20px;
      font-weight: 500;
    }
    iframe {
      width: 100%;
      height: calc(100% - 48px);
      border: none;
    }
  </style>
</head>
<body>
  <div id="fake-header">Google Classroom</div>
  <iframe id="gameFrame" allowfullscreen></iframe>

  <script>
    // Base64 encoded URL for added stealth
    const url = atob("aHR0cHM6Ly9kaWVwLmlv"); // => https://diep.io
    document.getElementById("gameFrame").src = url;
  </script>
</body>
</html>
