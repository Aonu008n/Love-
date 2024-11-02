# Love-
Love 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>I Love You?</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            font-family: Arial, sans-serif;
            background-image: url('https://example.com/your-background-image.jpg'); /* Replace with your image URL */
            background-size: cover;
            background-position: center;
            color: white;
            text-shadow: 1px 1px 5px rgba(0, 0, 0, 0.7);
            margin: 0;
        }
        h1 {
            color: #ffcccb;
        }
        .buttons {
            margin-top: 20px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            margin: 0 10px;
            cursor: pointer;
            background-color: #333;
            color: white;
            border: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #555;
        }
        #response {
            margin-top: 20px;
            font-size: 20px;
            color: #ffcccb;
        }
    </style>
</head>
<body>
    <h1>Do you love me?</h1>
    <div class="buttons">
        <button onclick="sayYes()">Yes</button>
        <button onclick="moveButton()">No</button>
    </div>
    <p id="response"></p>

    <script>
        function sayYes() {
            document.getElementById("response").innerText = "I knew it! ❤️";
        }

        function moveButton() {
            const button = document.querySelector('.buttons button:last-child');
            button.style.position = 'absolute';
            button.style.top = `${Math.random() * 80 + 10}%`;
            button.style.left = `${Math.random() * 80 + 10}%`;
        }
    </script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>I Love You?</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            font-family: Arial, sans-serif;
            background-image: url('https://example.com/your-background-image.jpg'); /* Replace with your image URL */
            background-size: cover;
            background-position: center;
            color: white;
            text-shadow: 1px 1px 5px rgba(0, 0, 0, 0.7);
            margin: 0;
        }
        h1 {
            color: #ffcccb;
        }
        .buttons {
            margin-top: 20px;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            margin: 0 10px;
            cursor: pointer;
            background-color: #333;
            color: white;
            border: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #555;
        }
        #response {
            margin-top: 20px;
            font-size: 20px;
            color: #ffcccb;
        }
    </style>
</head>
<body>
    <h1>Do you love me?</h1>
    <div class="buttons">
        <button onclick="sayYes()">Yes</button>
        <button onclick="moveButton()">No</button>
    </div>
    <p id="response"></p>

    <script>
        function sayYes() {
            document.getElementById("response").innerText = "I knew it! ❤️";
        }

        function moveButton() {
            const button = document.querySelector('.buttons button:last-child');
            button.style.position = 'absolute';
            button.style.top = `${Math.random() * 80 + 10}%`;
            button.style.left = `${Math.random() * 80 + 10}%`;
        }
    </script>
</body>
</html>
