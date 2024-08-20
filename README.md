### Hi there 👋, I'm Kirill

## I'm a Software Engineering Student
- 💪 I like to understand complex things
- 🎉 I just love music
- ⚡ I love active recreation
- 🤹🏽 Upgrading my skills in Yandex Workshop

<div align="center">
    <img src="https://raw.githubusercontent.com/omidnikrah/profile-activity-generator/master/demo.png" />
</div>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Всплывающая колонка</title>
    <style>
        .popup {
            display: none;
            position: absolute;
            width: 300px;
            background-color: #f9f9f9;
            border: 1px solid #ccc;
            padding: 10px;
            z-index: 1;
        }
    </style>
</head>
<body>

<button onclick="togglePopup()">Показать/Скрыть колонку</button>

<div id="popup" class="popup">
    Это всплывающая колонка!
</div>

<script>
    function togglePopup() {
        var popup = document.getElementById("popup");
        if (popup.style.display === "none" || popup.style.display === "") {
            popup.style.display = "block";
        } else {
            popup.style.display = "none";
        }
    }
</script>

</body>
</html>
