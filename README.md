<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>date and time in java Script</title>
    <style>
        body{
           background: url('./bg23.jpg') no-repeat center center/cover;
           height: 100vh;
        }
        .container{
            display: flex;
            align-items: center;
            width: 300px;
            font-size: 23px;
            background:linear-gradient(to right,purple,blue);
            border: 2px solid gold;
            margin: 5px;
            padding: 10px;
            border-radius: 20px;
            text-align: center;
        }
        #time{
            font-weight: bold;
            color: yellow;
            text-align: center;
        }
        h3{
            color: white;
        }
    </style>
</head>
<body>
    <div class="container">
     <h3>Time is</h3>
     <span id="time"></span>
    </div>
    <script>
    setInterval(updateTime, 1000);


function updateTime() {
    time.innerHTML = new Date;
}

    </script>
</body>
</html>
