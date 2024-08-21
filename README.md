# github-test
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Shopping Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }

        nav {
            background-color: #444;
            color: #fff;
            padding: 15px;
            text-align: center;
        }

        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }

        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }

        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }

        .product {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 15px;
            padding: 20px;
            width: 30%;
            box-sizing: border-box;
        }

        .product img {
            width: 100%;
            height: auto;
        }

        .product h3 {
            margin: 10px 0;
        }

        .product p {
            color: #333;
        }

        .product button {
            background-color: #333;
            color: #fff;
            border: none;
            padding: 10px;
            cursor: pointer;
        }

        footer {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <header>
        <h1>Online Shopping Website</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">Products</a>
        <a href="#">Cart</a>
        <a href="#">Contact</a>
    </nav>

    <div class="container">
        <h2>Products</h2>
        <div class="products">
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Product 1">
                <h3>Product 1</h3>
                <p>$10.00</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Product 2">
                <h3>Product 2</h3>
                <p>$15.00</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/300" alt="Product 3">
                <h3>Product 3</h3>
                <p>$20.00</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </div>

    <footer>
        <p>Online Shopping Website &copy; 2024</p>
    </footer>

</body>
</html>
