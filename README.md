# tarjeta-personal

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tarjeta Personal</title>
    <style>
        body {
            font-family: sans-serif;
            background: #eef2f3;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .tarjeta {
            background: white;
            padding: 30px;
            border-radius: 12px;
            text-align: center;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }
        .tarjeta img {
            width: 150px;
            border-radius: 50%;
            margin-bottom: 15px;
        }
        .tarjeta h1 {
            margin: 10px 0;
        }
        .tarjeta button {
            background: #0077cc;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
        }
        .tarjeta button:hover {
            background-color: #005fa3;
            transform: scale(1.05);
            transition: all 0.3s ease;
        }
    </style>
</head>
<body>
    <div class="tarjeta">
        <img src="https://via.placeholder.com/150" alt="Foto de perfil">
        <h1>Miguel Pérez</h1>
        <p>Estudiante de informática en formación</p>
        <button id="contacto">Contáctame</button>
    </div>
    <script>
        document.getElementById("contacto").addEventListener("click", function () {
            alert("¡Gracias por visitar mi tarjeta! 😄");
        });
    </script>
</body>
</html>
