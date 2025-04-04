<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>meow meow</title>
    <style>
        body  { font-family: Arial, sans-serif;
            background-color: #000000;
            margin: 0;
            padding: 0;}
        head  {background-color: #000000;
            color: rgb(247, 181, 225);
            text-align: center;
            padding: 1rem}
        .menu-contrainer { display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 20px;}
        .menu-item { background-color: rgb(0, 0, 0);
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 200px;
            text-align: center;
            padding: 10px;
            transition: transform 0.3s;}
        .menu-item:hover {transform: translateY(-10px);}
        .menu-item img {width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 8px; }
        .menu-item h3 {margin: 10px 0;
            font-size: 1.2rem;
            color: #ffffff;}
    
        .price {font-weight: bold;
            color: #ffe985;}
        </style>
    </head>
    <body>
        <header>
            <h1>meow menu</h1>
            <p>welcome to meow cafe</p>
        </header>
        <div class="menu-contrainer">
            <div class="menu-item">
                <img src="https://postimg.cc/LJ6bpSPr"> 

            </div>
        </div>
</body>
</html>
