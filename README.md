

<h1>💘 Donita 💘</h1>
<p>¿Quieres ser mi San Valentín?</p>

<div id="botones">
    <button class="opcion" onclick="respuestaIncorrecta()">Tal vez 🤔</button>
    <button class="opcion" onclick="respuestaIncorrecta()">No 😅</button>
    <button class="opcion" onclick="respuestaCorrecta()">Sí 💖</button>
    <button class="opcion" onclick="respuestaIncorrecta()">Sorpréndeme 😳</button>
</div>

<script>
    function respuestaCorrecta() {
        document.body.innerHTML = `
            <h1>💖 ¡Sabía que dirías que sí! 💖</h1>
            <p>Eres lo mejor que me ha pasado 💕</p>
            <p>Te amo Donita 🥰</p>
        `;
    }

    function respuestaIncorrecta() {
        alert("Esa no es la respuesta correcta 😜 intenta otra vez 💕");
    }
</script>

</body>
</html>
