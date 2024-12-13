# -ECO
e commerce page<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gros Store - Page d’Accueil</title>
    <link rel="stylesheet" href="cv.css">
</head>
<body>
    <header>
        <h1>Gros Store</h1>
        <p>🔥 Bienvenue chez votre magasin préféré 🔥</p>
    </header>
    <nav>
        <a href="#">Accueil</a>
        <a href="#about">À propos</a>
        <a href="#community">Notre Communauté</a>
    </nav>
    <div class="container">
        <section id="about">
            <h2>Bienvenue chez Gros Store</h2>
            <p>Explorez nos collections exclusives et rejoignez une communauté dynamique d'entreprises locales : <b>Casual Algeria</b>, <b>ChicDrobe</b>, et <b>Blackwears</b>. Découvrez le style, le confort et la qualité au meilleur prix.</p>
        </section>
        <section id="community" class="community">
            <div class="card casual">
                <h3>Casual Algeria</h3>
                <p>Designs casual pour un style quotidien inégalé.</p>
                <a href="https://www.instagram.com/casual_algeria" target="_blank">Instagram: casual_algeria</a>
            </div>
            <div class="card chic">
                <h3>ChicDrobe</h3>
                <p>Mode chic pour toutes les occasions spéciales.</p>
                <a href="https://www.instagram.com/chicdrobe.dz" target="_blank">Instagram: chicdrobe.dz</a>
            </div>
            <div class="card blackwears">
                <h3>Blackwears</h3>
                <p>Des vêtements élégants, entièrement noirs, avec une touche unique.</p>
                <a href="https://www.instagram.com/blackwears.co" target="_blank">Instagram: blackwears.co</a>
            </div>
        </section>
        <section class="contact">
            <h2>Nous contacter</h2>
            <p>Téléphone : +213 770795028</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Gros Store. Tous droits réservés.</p>
    </footer>
</body>
</html>
/* Global styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    color: #333;
    background: #d3d3d3;
}

header {
    background-color: #333;
    color: #110f0f;
    padding: 20px;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 3em;
    animation: fadeIn 2s;
}

header p {
    font-size: 1.5em;
    margin-top: 10px;
    color: #a09f98;
}

nav {
    display: flex;
    justify-content: center;
    background-color: #444;
    padding: 10px 0;
}

nav a {
    color: #fff;
    margin: 0 15px;
    text-decoration: none;
    font-weight: bold;
    font-size: 1.2em;
    animation: slideIn 1.5s;
}

nav a:hover {
    color: #d8d4be;
    transform: scale(1.1);
}

.container {
    max-width: 1200px;
    margin: 20px auto;
    padding: 20px;
}

section h2 {
    text-align: center;
    margin-bottom: 15px;
    color: #333;
    font-size: 2em;
}

.community {
    display: flex;
    justify-content: space-between;
    gap: 20px;
    margin: 20px 0;
}

.card {
    background: #fff;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
    padding: 20px;
    width: 30%;
    border-radius: 10px;
    animation: fadeInUp 1s ease-in-out;
    position: relative;
    text-align: center;
    transition: transform 0.3s, background-color 0.3s;
}

.card:hover {
    transform: scale(1.1);
    background: #eaeaea;
}

.card h3 {
    margin-bottom: 10px;
    color: #444;
    font-size: 1.5em;
}

.card p {
    font-size: 1.2em;
}

.card a {
    display: inline-block;
    margin-top: 15px;
    padding: 10px 15px;
    background: #777676;
    color: #ebe2e2;
    text-decoration: none;
    border-radius: 5px;
    transition: transform 0.3s, background-color 0.3s;
}

.card a:hover {
    background: #1f1f1e;
    transform: scale(1.1);
}

footer {
    background-color: #333;
    color: #f8f3f3;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}

footer p {
    margin: 0;
}

/* Animations */
@keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
}

@keyframes slideIn {
    from { transform: translateX(-100%); }
    to { transform: translateX(0); }
}

@keyframes fadeInUp {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
}

