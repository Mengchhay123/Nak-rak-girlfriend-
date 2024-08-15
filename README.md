<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dog Life - By Chhay</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f8f8f8;
        }
        h1 {
            color: #2c3e50;
        }
        img {
            width: 300px;
            height: auto;
            border-radius: 8px;
            margin-top: 20px;
        }
        button {
            padding: 10px 20px;
            background-color: #3498db;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
            margin-top: 20px;
        }
        button:hover {
            background-color: #2980b9;
        }
    </style>
</head>
<body>

    <h1>Dog Life</h1>
    <h3>By Chhay</h3>
    <img id="dogImage" src="https://placedog.net/500" alt="Dog Image">
    <br>
    <button onclick="changeDogImage()">Show Another Dog</button>

    <script>
        function changeDogImage() {
            // API to fetch random dog images
            const dogImageAPI = "https://placedog.net/500?random=" + new Date().getTime();
            document.getElementById("dogImage").src = dogImageAPI;
        }
    </script>

</body>
</html># Nak-rak-girlfriend-
