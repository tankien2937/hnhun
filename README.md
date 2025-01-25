<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Xin Lỗi Vợ Iu</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f0f8ff;
            color: #333;
            text-align: center;
            padding: 50px;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            margin: 0;
        }

        h1 {
            color: #ff1493;
            font-size: 3em;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }

        .message {
            font-size: 1.5em;
            color: #ff69b4;
            opacity: 0; /* Chữ sẽ bắt đầu ẩn */
            transition: opacity 2s ease-in-out;
            margin-top: 20px;
        }

        .heart {
            font-size: 80px;
            color: #ff6347;
            margin-top: 30px;
        }

        .button {
            background-color: #ff69b4;
            border: none;
            padding: 15px 30px;
            color: white;
            font-size: 1.2em;
            border-radius: 25px;
            cursor: pointer;
            margin-top: 30px;
            transition: background-color 0.3s;
        }

        .button:hover {
            background-color: #ff1493;
        }

        .footer {
            margin-top: 50px;
            color: #696969;
            font-size: 1.1em;
        }

    </style>
</head>
<body>
    <button class="button" onclick="showMessage()">Bấm vào điiii</button>
    <p class="message">Anh xin lỗi bé nhiều ạaaaa.Từ giờ anh hổng làm z nữa đâu anh hứa.Bé đừng giận anh nữa nhaaaaaa</p>
    <p class="heart">😭</p>
    <script>
        function showMessage() {
            const message = document.querySelector('.message');
            message.style.opacity = 1; // Khi bấm nút, chữ sẽ hiện ra từ từ
        }
    </script>
</body>
</html>
