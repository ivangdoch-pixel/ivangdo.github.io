<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>aprende con el vago de Ivan</title>
<style>
    body {
        margin: 0;
        min-height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        font-family: Arial, sans-serif;
        background: #111827;
        color: white;
    }

    .contenedor {
        text-align: center;
    }

    h1 {
        margin-bottom: 30px;
    }

    .nivel {
        display: flex;
        justify-content: center;
        gap: 20px;
        flex-wrap: wrap;
    }

    button {
        padding: 20px 40px;
        font-size: 18px;
        border: none;
        border-radius: 12px;
        cursor: pointer;
        background: #2563eb;
        color: white;
        transition: 0.2s;
    }

    button:hover {
        background: #1d4ed8;
        transform: scale(1.05);
    }
</style>

<div class="contenedor">
    <h1>¿Qué nivel hacemos hoy?</h1>

    <div class="nivel">

        <button onclick="abrirHTML('https://github.com/ivangdoch-pixel/ivangdo.github.io/blob/main/aleman_a1_quiz_1000.html')">
            A1 (1000 preguntas)
        </button>

        <button onclick="abrirHTML('https://github.com/ivangdoch-pixel/aprenderalemangitano/blob/main/quiz-aleman-a2.html')">
            A2 (1000 preguntas)
        </button>

        <button onclick="abrirHTML('https://github.com/ivangdoch-pixel/aprenderalemangitano/blob/main/quiz-aleman-b1.html')">
            B1 (1000 preguntas)
        </button>

    </div>
</div>

<script>
    function abrirHTML(archivo) {
        window.location.href = archivo;
    }
</script>

</body>
</html>
