<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Love Confession</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>Click the button to see my feelings for you</h1>
    <button id="revealButton">Reveal</button>
    <div id="heartContainer" class="hidden">
      <b>I Love You</b>
      <div class="heart"></div>
    </div>
  </div>
</body>
<script>
  document.getElementById('revealButton').addEventListener('click', function() {
    document.getElementById('heartContainer').classList.remove('hidden');
  });
</script>
</html>
