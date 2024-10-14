<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rooti Gendhis</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('https://example.com/background.jpg'); /* Ganti dengan URL gambar latar belakang */
            background-size: cover;
            background-position: center;
        }
        header {
            background-color: rgba(255, 204, 0, 0.9);
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.3);
        }
        h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            margin: 15px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        .container {
            max-width: 1200px;
            margin: 40px auto;
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 15px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
        }
        h2 {
            grid-column: span 1;
            text-align: center;
            font-size: 2em;
            color: #333;
            margin-bottom: 30px;
            grid-column: 1 / -1; /* Menyebar di seluruh kolom */
        }
        .product {
            display: flex;
            flex-direction: column;
            align-items: center;
            border: 1px solid #ccc;
            padding: 15px;
            background: #fff;
            border-radius: 10px;
            transition: transform 0.2s;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .product:hover {
            transform: scale(1.05);
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin-bottom: 10px;
        }
        footer {
            text-align: center;
            padding: 15px;
            background-color: #333;
            color: #fff;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Rooti Gendhis</h1>
    <nav>
        <a href="#">Beranda</a>
        <a href="#">Produk</a>
        <a href="#">Kontak</a>
        <a href="#">Tentang Kami</a>
    </nav>
</header>

<div class="container">
    <h2>Produk Kami</h2>
    <div class="product">
        <h3>Roti Tawar</h3>
        <img src="https://images.tokopedia.net/img/cache/900/VqbcmM/2023/11/1/1cb67ebb-c250-40cf-8305-1108263de40a.jpg" alt="Roti Tawar"> <!-- Ganti dengan URL gambar roti tawar -->
        <p>Roti tawar segar yang lembut.</p>
        <p>Harga: Rp 15.000</p>
    </div>
    <div class="product">
        <h3>Roti Manis</h3>
        <img src="https://images.tokopedia.net/img/cache/900/VqbcmM/2023/11/1/62783428-33b6-4917-9f9f-896e81820974.jpg" alt="Roti Manis"> <!-- Ganti dengan URL gambar roti manis -->
        <p>Roti manis dengan isian coklat lezat.</p>
        <p>Harga: Rp 20.000</p>
    </div>
    <div class="product">
        <h3>Roti Terenak</h3>
        <img src="https://images.tokopedia.net/img/cache/900/VqbcmM/2023/11/1/0da131d0-a733-4c03-87a1-89d9d4f06d10.jpg" alt="Roti Terenak"> <!-- Ganti dengan URL gambar roti terenak -->
        <p>Roti dengan topping keju dan kismis.</p>
        <p>Harga: Rp 25.000</p>
    </div>
    <div class="product">
        <h3>Roti Coklat</h3>
        <img src="https://images.tokopedia.net/img/cache/900/VqbcmM/2023/11/1/44e41fc9-5bd7-47e6-853b-6206c4c69701.jpg" alt="Roti Coklat"> <!-- Ganti dengan URL gambar roti coklat -->
        <p>Roti lezat dengan coklat premium.</p>
        <p>Harga: Rp 22.000</p>
    </div>
    <div class="product">
        <h3>Roti Kismis</h3>
        <img src="https://images.tokopedia.net/img/cache/900/VqbcmM/2023/11/1/ac97942d-3942-4dec-bbf7-bab4fc734014.jpg" alt="Roti Kismis"> <!-- Ganti dengan URL gambar roti kismis -->
        <p>Roti dengan kismis manis dan gurih.</p>
        <p>Harga: Rp 18.000</p>
    </div>
</div>

<footer>
    <p>&copy; 2024 Rooti Gendhis. Semua hak dilindungi.</p>
</footer>

</body>
</html>
