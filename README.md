<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DO YOU LOVE ME </title>
    <style>
        @keyframes heartbeat {
            0% { transform: scale(1); }
            20% { transform: scale(1.1); }
            40% { transform: scale(1); }
            60% { transform: scale(1.1); }
            80% { transform: scale(1); }
            100% { transform: scale(1.1); }
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideIn {
            from { transform: translateY(-50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
        body {
            font-family: ITALIC, sans-serif;
            background-color: #f7f9fc;
            text-align: center;
            padding: 50px;
            animation: fadeIn 2s ease-in-out;
        }
        h1 {
            color: #ff6363;
            animation: slideIn 1.5s ease-in-out;
        }
        .heart {
            font-size: 100px;
            color: #ff6363;
            margin: 20px 0;
            animation: heartbeat 2s infinite;
        }
        p {
            animation: fadeIn 2s ease-in-out;
            animation-delay: 1s;
            animation-fill-mode: both;
        }
        button {
            background-color: #ff6363;
            color: white;
            padding: 15px 30px;
            font-size: 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s, transform 0.3s;
            animation: fadeIn 2s ease-in-out;
            animation-delay: 2s;
            animation-fill-mode: both;
        }
        button:hover {
            background-color: #e55757;
            transform: scale(1.1);
        }
    </style>
</head>
<body>
    <h1>DO YOU LOVE ME </h1>
    <p>We ENJOYED EVERY MOMEMENT together 🖤</p>
    <div class="heart">❤️</div>
    <p>So,if you say no i will kill you...😒😒😒</p>
    <button onclick="showAnswer('yes')">YES!</button>
    <button onclick="showAnswer('no')">no!</button>
    <button onclick="showAnswer('other')">other?</button>

    <script>
        function showAnswer(answer) {
            if (answer === 'yes') {
                alert("Yay!now lets live life together....😁");
                ("open in another page");
            } else {
                alert("Oh no! You've broken my heart... 😢");
                alert("you have to say yes because you are my pookie....🫀")
            }
        }
    </script>
</body>
</html>
