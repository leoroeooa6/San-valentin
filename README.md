# San-valentin <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feliz San Valentín, Génesis!</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f8e1e1;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #ff6f61;
            color: white;
            padding: 20px;
        }
        h1 {
            font-size: 2.5em;
        }
        p {
            font-size: 1.2em;
            color: #333;
            margin: 20px 0;
        }
        .interactive-button {
            padding: 15px 30px;
            background-color: #ff4d4d;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 1.2em;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .interactive-button:hover {
            background-color: #ff2a2a;
        }
        .message {
            display: none;
            font-size: 1.5em;
            color: #555;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>¡Feliz San Valentín, Génesis!</h1>
</header>

<p>Hoy es un día muy especial, ya que es la primera vez que paso San Valentín contigo y no puedo estar más feliz.</p>

<p>Gracias por ser mi inspiración y por hacer que cada día sea más bonito. ¡Te quiero muchísimo!</p>

<button class="interactive-button" onclick="mostrarMensaje()">¡Ver la sorpresa!</button>

<p class="message" id="mensajeSorpresa">Eres la razón por la que mi vida tiene más color. ¡Gracias por estar siempre a mi lado, Génesis! Estoy emocionado de compartir este primer San Valentín contigo, y sé que será el primero de muchos más.</p>

<script>
    function mostrarMensaje() {
        document.getElementById("mensajeSorpresa").style.display = "block";
    }
</script>

</body>
</html>
