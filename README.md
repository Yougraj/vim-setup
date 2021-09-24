<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.1/css/all.css">
    <style>
        body {
            padding: 25px;
            background-color: white;
            color: black;
            font-size: 25px;
        }
        .dark-mode {
            background-color: black;
            color: white;
        }
    </style>
</head>

<body>
    <a onclick="darkMode()">
        <i id="mode" class="fas fa-moon moon icon"></i>
    </a>
    <h1>clone the repo</h1>
    <h2>git clone https://github.com/Yougraj/vim-setup.git</h2>
    <h1>After installing</h1>
    <p>type these commands for updating and installing missing plugins</p>
    <ol type="I">
        <li>vim ~/.vimrc</li>
        <li>:PlugInstall</li>
        <li>:PlugUpdate</li>
    </ol>
    <script>
        function darkMode() {
            var element = document.body;
            element.classList.toggle("dark-mode");
        }
    </script>
</body>

</html>

<!-- <i class = "fas fa-sun"> </i> -->