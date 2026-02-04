<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>PrimeDrops | Sports Store</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f4f4f4;
        }

        header {
            background: #111;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .container {
            padding: 30px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            background: white;
            border-radius: 10px;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

        .card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
            border-radius: 8px;
        }

        .price {
            font-size: 18px;
            font-weight: bold;
            color: #27ae60;
            margin: 10px 0;
        }

        button {
            background: #27ae60;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 6px;
            cursor: pointer;
        }

        button:hover {
            background: #219150;
        }

        footer {
            text-align: center;
            padding: 15px;
            background: #111;
            color: white;
            margin-top: 30px;
        }
    </style>
</head>
<body>

<header>
    <h1>PrimeDrops</h1>
    <p>Premium Sports Gear — Prices from $20</p>
</header>

<div class="container">
    <div class="card">
        <img src="https://images.unsplash.com/photo-1599058917212-d750089bc07e" alt="Running Shoes">
        <h3>Running Shoes</h3>
        <p class="price">$45</p>
        <button>Add to Cart</button>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1605296867304-46d5465a13f1" alt="Dumbbells">
        <h3>Dumbbells Set</h3>
        <p class="price">$60</p>
        <button>Add to Cart</button>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1594381898411-846e7d193883" alt="Football">
        <h3>Professional Football</h3>
        <p class="price">$25</p>
        <button>Add to Cart</button>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1552674605-db6ffd4facb5" alt="Fitness Gloves">
        <h3>Fitness Gloves</h3>
        <p class="price">$20</p>
        <button>Add to Cart</button>
    </div>
</div>

<footer>
    © 2026 PrimeDrops. All rights reserved.
</footer>

</body>
</html>
