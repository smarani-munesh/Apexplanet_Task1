<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>HOW ARE YOU FEELING TODAY?</h1>
    <button onclick="Moodnow('happy')">Happy</button>
    <button onclick="Moodnow('sad')">Sad</button>
    <button onclick="Moodnow('excited')">Excited</button>
    <button onclick="Moodnow('tired')">Tired</button>

<script>
  function Moodnow(mood) {
    if (mood === 'happy') message = 'That’s awesome! Keep smiling! :)';
    if (mood === 'sad') message = 'It’s okay to feel sad. Better days are ahead all days are not ours!';
    if (mood === 'excited') message = 'Yay! Keep up the energy and work smart!';
    if (mood === 'tired') message = 'Take some rest and hydrate with sip of mojito!';
    alert(message);
  }
</script>
</body>
</html>
