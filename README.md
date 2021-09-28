<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Download Card</title>
    <style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        h1{
            margin-top: 10px;
        }
        .card{
            height: 80vh;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }
        .card a{
            margin: 40px;
            border: 1px solid red;
            padding: 10px 20px;
            text-decoration: none;
            color: rgb(38, 0, 255);
            font-size: 22px;
            font-weight: bold;
            font-family: cursive;
            transition: .5s;
        }
        .card a:first-child{
            margin-top: 0px;
        }
        .card a:last-child{
            margin-bottom: 0px;
        }
        .card a:hover{
            color: blue;
            background: yellow;
            border: none;
        }
    </style>
</head>
<body>
    <h1 style="text-align: center;color: rgb(204, 0, 255);">DOWNLOAD YOUR VACCINE CARD</h1>

    <div class="card">
        <a href="./NASIR FOKIR/2021_09_28_14-44-46_pm.pdf" download>Nasir Fokir</a>
        <a href="./NASIR FOKIR/2021_09_28_14-52-26_pm.pdf" download>Liza Akter</a>
        <a href="./NASIR FOKIR/2021_09_28_14-56-37_pm.pdf" download>Sonia Begum</a>
        <a href="./NASIR FOKIR/2021_09_28_15-02-44_pm.pdf" download>Hoshneara Begum</a>
    </div>
        
    
</body>
</html>
