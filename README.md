[donita_san_valentin.html](https://github.com/user-attachments/files/25195483/donita_san_valentin.html)
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>💖 Para Donita 💖</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .card {
      background: white;
      padding: 25px;
      border-radius: 20px;
      width: 90%;
      max-width: 350px;
      text-align: center;
      box-shadow: 0 10px 20px rgba(0,0,0,0.2);
    }
    h1 { color: #e91e63; }
    button {
      background: #e91e63;
      color: white;
      border: none;
      padding: 10px 15px;
      margin: 8px;
      border-radius: 20px;
      font-size: 15px;
    }
    button:hover { background: #c2185b; }
  </style>
</head>
<body>

<div class="card">
  <h1>💖 Juego del Amor 💖</h1>
  <p id="q">Hola Donita 🥰<br>¿Lista para jugar?</p>
  <div id="buttons">
    <button onclick="next()">Sí 💕</button>
  </div>
</div>

<script>
const questions = [
  "¿Quién dio el primer beso? 💋",
  "¿Cuál fue nuestra primera date? 💑",
  "¿Quién es más dependiente de la otra? 😅",
  "¿Quién dijo “te amo” primero? ❤️",
  "¿A quién le gusta más molestar a la otra? 😂",
  "Donita… ¿quieres ser mi San Valentín? 💘"
];

let i = 0;

function next() {
  if (i < questions.length) {
    document.getElementById("q").innerText = questions[i];
    i++;
  } else {
    document.querySelector(".card").innerHTML =
      "<h1>💘 Feliz San Valentín 💘</h1><p>Te amo muchísimo Donita 🥰<br>Gracias por existir ❤️</p>";
  }
}
</script>

</body>
</html>
