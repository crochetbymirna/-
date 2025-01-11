<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Crochet by Mirna</title>
    <style>
        /* General Styling */
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #ffffff, #f8f8f8);
            color: #333;
            overflow-x: hidden;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        /* Header Section */
        header {
            background: linear-gradient(135deg, rgba(255, 154, 162, 0.9), rgba(255, 196, 209, 0.9));
            color: white;
            text-align: center;
            padding: 100px 20px;
            position: relative;
            backdrop-filter: blur(10px);
            border-bottom: 5px solid rgba(255, 154, 162, 0.6);
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }

        header h1 {
            font-size: 4rem;
            margin: 0;
            letter-spacing: 3px;
            text-shadow: 2px 3px 5px rgba(0, 0, 0, 0.3);
        }

        header p {
            font-size: 1.5rem;
            margin: 20px 0;
            opacity: 0.9;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2.5rem;
            }

            header p {
                font-size: 1.2rem;
            }
        }

        /* Product Section */
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 25px;
            padding: 40px;
            max-width: 1200px;
            margin: 20px auto;
            background: #ffffff;
            border-radius: 20px;
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.1);
        }

        .product {
            background: #ffffff;
            border-radius: 15px;
            overflow: hidden;
            transition: transform 0.4s ease, box-shadow 0.4s ease;
            position: relative;
            border: 1px solid rgba(200, 200, 200, 0.3);
        }

        .product:hover {
            transform: translateY(-5px);
            box-shadow: 0 12px 25px rgba(0, 0, 0, 0.2);
        }

        .product img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            transition: transform 0.3s ease;
        }

        .product:hover img {
            transform: scale(1.1);
        }

        .product .details {
            padding: 15px;
            text-align: center;
            background: #fdfdfd;
            border-top: 1px solid rgba(200, 200, 200, 0.5);
        }

        .product .details .price {
            font-size: 1.4rem;
            color: #e91e63;
            font-weight: bold;
        }

        @media (max-width: 768px) {
            .products {
                grid-template-columns: 1fr;
                gap: 20px;
            }

            .product .details .price {
                font-size: 1.2rem;
            }
        }

        /* Footer Section */
        footer {
            background: linear-gradient(135deg, #f6f6f6, #eaeaea);
            color: #555;
            text-align: center;
            padding: 50px 20px;
            box-shadow: 0 -4px 10px rgba(0, 0, 0, 0.1);
        }

        footer p {
            margin: 0;
            font-size: 1rem;
        }

        @media (max-width: 768px) {
            footer p {
                font-size: 0.9rem;
            }
        }

        /* Pagination Section */
        .pagination {
            text-align: center;
            margin: 30px 0;
        }

        .pagination button {
            background: linear-gradient(to right, #e91e63, #ff6f8e);
            color: white;
            border: none;
            border-radius: 30px;
            padding: 12px 25px;
            font-size: 1rem;
            font-weight: bold;
            cursor: pointer;
            transition: background 0.3s ease, transform 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
        }

        .pagination button:hover {
            background: linear-gradient(to right, #d81b60, #ff5673);
            transform: translateY(-3px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }

        .pagination button:active {
            transform: translateY(0);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        @media (max-width: 768px) {
            .pagination button {
                padding: 10px 20px;
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Crochet by Mirna</h1>
        <p>Handcrafted with love, designed for you. Customize your perfect bag today!</p>
    </header>


    <section id="products" class="products">
        <div class="product">
            <img src="https://i.imgur.com/KJqcajw.jpeg" alt="Bag">
            <div class="details">
                <p class="price">$30</p>
            </div>
        </div>
        <div class="product">
            <img src="https://i.imgur.com/ZTZudst.jpeg" alt="Bag">
            <div class="details">
                <p class="price">$35</p>
            </div>
        </div>
        <div class="product">
            <img src="https://i.imgur.com/lbBxPGY.jpeg" alt="Bag">
            <div class="details">
                <p class="price">$30</p>
            </div>
        </div>
        <div class="product">
            <img src="https://i.imgur.com/zaMLXM6.jpeg" alt="Bag">
            <div class="details">
                <p class="price">$35</p>
            </div>
        </div>
        <div class="product">
            <img src="https://i.imgur.com/WjVz4BQ.jpeg" alt="Bag">
            <div class="details">
                <p class="price">$30</p>
            </div>
        </div>
        <div class="product">
            <img src="https://i.imgur.com/C2FF4aO.jpeg" alt="Bag">
            <div class="details">
                <p class="price">$45</p>
            </div>
        </div>
        <div class="product">
            <img src="https://i.imgur.com/gBLDkPg.jpeg" alt="Bag">
            <div class="details">
                <p class="price">$60</p>
            </div>
        </div>
        <div class="product">
            <img src="https://i.imgur.com/DuOWMSk.jpeg" alt="Bag">
            <div class="details">
                <p class="price">$35</p>
            </div>
        </div>
        <div class="product">
            <img src="https://i.imgur.com/G5qHktC.jpeg" alt="Bag">
            <div class="details">
                <p class="price">$35</p>
            </div>
        </div>
        <div class="product full-width">
            <img src="https://i.imgur.com/OxQLg23.jpeg" alt="Bag">
            <div class="details">
                <p class="price">$45</p>
            </div>
        </div>
    </section>

    <div class="pagination">
        <button onclick="gotoPage('bag1.html')">1</button>
        <button onclick="gotoPage('bag2.html')">2</button>
    </div>

    <footer>
        <p>&copy; 2025 Crochet by Mirna. All Rights Reserved.</p>
    </footer>

    <script>
        function gotoPage(page) {
            window.location.href = page;
        }
    </script>
</body>
</html>
