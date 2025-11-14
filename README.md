<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>我的網頁</title>

    <!-- CSS 直接寫在 <style> 裡面 -->
    <style>
        body {
            background-color: #f5f5f5;
            font-family: Arial;
            padding: 20px;
        }

        h1 {
            color: blue;
        }

        #myBtn {
            padding: 10px 20px;
            font-size: 18px;
            background-color: orange;
            border: none;
            border-radius: 8px;
            cursor: pointer;
        }
    </style>
</head>

<body>

    <!-- HTML 網頁內容 -->
    <h1>哈囉！世界</h1>
    <p>這是一個 HTML + CSS + JS 都在同一個檔案的例子。</p>

    <button id="myBtn" onclick="sayHello()">按我</button>

    <p id="result"></p>

    <!-- JavaScript 寫在 <script> 裡面 -->
    <script>
        function sayHello() {
            document.getElementById("result").textContent = "你按下按鈕了！";
            alert("JS 成功運作！");
        }
    </script>

</body>
</html>
