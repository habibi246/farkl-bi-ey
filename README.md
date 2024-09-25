<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Örnek HTML Sayfası</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #35424a;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        section {
            margin: 20px 0;
            padding: 20px;
            background: white;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background: #35424a;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Web Sayfam</h1>
        <nav>
            <a href="#hakkimizda">Hakkımızda</a>
            <a href="#hizmetler">Hizmetler</a>
            <a href="#iletisim">İletişim</a>
        </nav>
    </header>
    
    <div class="container">
        <section id="hakkimizda">
            <h2>Hakkımızda</h2>
            <p>Bu bölüm, şirketimiz hakkında bilgi verir. Vizyonumuz, misyonumuz ve değerlerimiz hakkında bilgi içerir.</p>
        </section>
        
        <section id="hizmetler">
            <h2>Hizmetler</h2>
            <ul>
                <li>Web Geliştirme</li>
                <li>Dijital Pazarlama</li>
                <li>Danışmanlık Hizmetleri</li>
            </ul>
        </section>
        
        <section id="iletisim">
            <h2>İletişim</h2>
            <form action="gonder.php" method="post">
                <label for="isim">İsim:</label><br>
                <input type="text" id="isim" name="isim" required><br><br>
                <label for="email">E-posta:</label><br>
                <input type="email" id="email" name="email" required><br><br>
                <label for="mesaj">Mesaj:</label><br>
                <textarea id="mesaj" name="mesaj" rows="4" required></textarea><br><br>
                <input type="submit" value="Gönder">
            </form>
        </section>
    </div>


    <footer>
        <p>Tüm Hakları Saklıdır &copy; 2024</p>
    </footer>
</body>
</html>

