<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>loader</title>
</head>
<body>
    <div class="loader">
       L
    </div>
    <style>
        .loader{
        height: 200px;
        width: 200px;
        background-size: cover;
        background-repeat: no-repeat;
        background:linear-gradient(coral,purple);
        position:absolute;
        top:50%;
        left:45%;
        padding:20px;
        margin: 20px;
        animation:anime 3s infinite alternate;
        border-radius:100px;
        display: flex;
        justify-content:center;
        align-items: center;
        font-size:10em;
        color: white;
        }
        *{
            margin: 0;
            padding: 0;
            background-color: #121212;
        }
        @keyframes anime {
            0%{
                transform:rotateZ(0deg)rotateY(0deg)rotateX(0deg);
            }
            100%{
                transform:rotateZ(360deg)rotateX(360deg)rotateY(360deg);
            }
        }
    </style>
</body>
</html>
