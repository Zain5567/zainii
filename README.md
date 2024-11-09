<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>زر تغيير النص</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        button {
            padding: 10px 20px;
            font-size: 18px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <button id="myButton" onclick="changeText()">مرحبًا</button>

    <script>
        function changeText() {
            var button = document.getElementById("myButton");
            button.textContent = "اهلين";
        }
    </script>
</body>
</html>

