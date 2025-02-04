<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Be My Valentine?</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            background-color: pink;
        }
        .container {
            margin-top: 100px;
        }
        .question {
            font-size: 24px;
            font-weight: bold;
        }
        .buttons {
            margin-top: 20px;
            position: relative;
        }
        #yes, #no {
            padding: 10px 20px;
            font-size: 18px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
        }
        #yes {
            background-color: green;
            color: white;
        }
        #no {
            background-color: red;
            color: white;
            position: absolute;
        }
        .hidden {
            display: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <p class="question">Can you be my Valentine?</p>
        <div class="buttons">
            <button id="yes">Yes</button>
            <button id="no">No</button>
        </div>
        <div id="response" class="hidden">
            <img src= "data:image/jpeg;base64,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" alt="New Image Description" width="300">
            <p style="font-size: 20px; font-weight: bold;">Let's go out on a date!</p>
        </div>
    </div>

    <script>
        const noButton = document.getElementById('no');
        const yesButton = document.getElementById('yes');
        const responseDiv = document.getElementById('response');

        noButton.addEventListener('mouseover', () => {
            const maxX = window.innerWidth - noButton.clientWidth;
            const maxY = window.innerHeight - noButton.clientHeight;
            const randomX = Math.random() * maxX;
            const randomY = Math.random() * maxY;
            noButton.style.left = randomX + 'px';
            noButton.style.top = randomY + 'px';
        });

        yesButton.addEventListener('click', () => {
            document.querySelector('.buttons').classList.add('hidden');
            document.querySelector('.question').classList.add('hidden');
            responseDiv.classList.remove('hidden');
        });
    </script>
</body>
</html>
