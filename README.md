<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>สร้างข้อความ</title>
    <style>
        .container {
            text-align: center;
            margin-top: 50px;
        }
        .box {
            border: 2px solid #000;
            width: 300px;
            padding: 20px;
            margin-bottom: 20px;
        }
        .button-container {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="box">
            <p>คุณอยากให้มีเซิฟ SS6 ไหม</p>
            <p id="response">โปรดพิมพ์...</p>
            <input type="text" id="textInput"><br><br>
            <div class="button-container">
                <button onclick="cancel()">ยกเลิก</button>
                <button onclick="confirm()">ตกลง</button>
            </div>
        </div>
    </div>

    <script>
        function confirm() {
            document.getElementById("response").innerText = "ขอบคุณสำหรับความคิดเห็น";
            document.getElementById("response").style.color = "green";
        }

        function cancel() {
            window.location.href = "https://youtu.be/QVjNk2vmN9A?si=q79VdsiY94lamnkc";
        }
    </script>
</body>
</html>
