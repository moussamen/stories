<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Change Color</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: white;
        }

        .container {
            text-align: center;
        }

        button {
            margin: 5px;
            padding: 10px 20px;
            border: none;
            color: white;
            background-color: black;
            cursor: pointer;
            font-size: 16px;
        }

        button:hover {
            opacity: 0.8;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Change Background Color</h1>
        <button onclick="changeColor('red')">Red</button>
        <button onclick="changeColor('green')">Green</button>
        <button onclick="changeColor('blue')">Blue</button>
        <button onclick="changeColor('white')">White</button>
    </div>
    <script>
        function changeColor(color) {
            document.body.style.backgroundColor = color;
        }
    </script>
</body>
</html>
