<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>F-Kirana Mart | Rudlapur</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f5f7fa;
            color: #222;
        }

        header {
            background: linear-gradient(135deg, #16a34a, #15803d);
            color: white;
            text-align: center;
            padding: 35px 15px;
        }

        header h1 {
            font-size: 38px;
            margin: 0;
        }

        header p {
            font-size: 18px;
        }

        nav {
            background: #14532d;
            padding: 15px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 12px;
            font-weight: bold;
        }

        .hero {
            text-align: center;
            padding: 60px 20px;
            background: white;
        }

        .hero h2 {
            font-size: 32px;
            color: #15803d;
        }

        .hero p {
            font-size: 19px;
        }

        .btn {
            display: inline-block;
            background: #16a34a;
            color: white;
            padding: 14px 25px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            margin-top: 15px;
        }

        section {
            padding: 45px 20px;
            text-align: center;
        }

        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .card {
            background: white;
            width: 220px;
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0 5px 18px #0002;
        }

        .card .icon {
            font-size: 45px;
        }

        .card h3 {
            color: #15803d;
        }

        .about {
            background: #ecfdf5;
        }

        footer {
            background: #14532d;
            color: white;
            text-align: center;
            padding: 25px;
        }
    </style>
</head>

<body>

<header>
    <h1>🛒 F-Kirana Mart</h1>
    <p>आपकी अपनी किराना दुकान</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#products">Products</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>

<div class="hero" id="home">

    <h2>Welcome to F-Kirana Mart 🎉</h2>

    <p>
        📍 Rudlapur में, CMK के पास
    </p>

    <p>
        👤 मालिक: <b>Vijay Pandey</b>
    </p>

    <a class="btn" href="#products">
        🛍️ Products देखें
    </a>

</div>

<section id="products">

    <h2>🛍️ हमारे Products</h2>

    <div class="products">

        <div class="card">
            <div class="icon">🍚</div>
            <h3>Rice & Dal</h3>
            <p>चावल और दाल</p>
        </div>

        <div class="card">
            <div class="icon">🌾</div>
            <h3>Atta</h3>
            <p>आटा और अनाज</p>
        </div>

        <div class="card">
            <div class="icon">🧂</div>
            <h3>Masala</h3>
            <p>मसाले और नमक</p>
        </div>

        <div class="card">
            <div class="icon">🥤</div>
            <h3>Drinks</h3>
            <p>Cold Drinks और अन्य सामान</p>
        </div>

        <div class="card">
            <div class="icon">🍪</div>
            <h3>Biscuits</h3>
            <p>बिस्किट और Snacks</p>
        </div>

        <div class="card">
            <div class="icon">🧴</div>
            <h3>Daily Items</h3>
            <p>रोजमर्रा की जरूरत का सामान</p>
        </div>

    </div>

</section>

<section class="about" id="about">

    <h2>🏪 हमारी दुकान</h2>

    <p><b>दुकान का नाम:</b> F-Kirana Mart</p>

    <p><b>मालिक:</b> Vijay Pandey</p>

    <p><b>स्थान:</b> Rudlapur, CMK के पास</p>

    <p>
        यहाँ रोजमर्रा की जरूरत का किराना सामान मिल सकता है।
    </p>

</section>

<section id="contact">

    <h2>📞 Contact</h2>

    <p>दुकान से संपर्क करने के लिए अपना वास्तविक मोबाइल नंबर यहाँ जोड़ें।</p>

    <!-- YOUR_NUMBER की जगह असली नंबर डालें -->
    <a class="btn" href="tel:YOUR_NUMBER">
        📞 Call Now
    </a>

</section>

<footer>
    <h3>🛒 F-Kirana Mart</h3>
    <p>Rudlapur • CMK के पास</p>
    <p>Owner: Vijay Pandey</p>
    <p>© 2026 F-Kirana Mart</p>
</footer>

</body>
</html>
