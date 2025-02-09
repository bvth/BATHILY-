# BATHILY-
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bvth Service - Matériel Téléphonique</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #1a1a1a;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #333;
            padding: 15px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .product-card {
            border: 1px solid #ddd;
            padding: 15px;
            text-align: center;
            border-radius: 5px;
        }

        .product-card img {
            max-width: 200px;
            height: auto;
            margin-bottom: 10px;
        }

        .price {
            color: #e67e22;
            font-size: 1.2em;
            margin: 10px 0;
        }

        .buy-btn {
            background-color: #e67e22;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        footer {
            background-color: #1a1a1a;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 50px;
        }

        .payment-info {
            background-color: #f4f4f4;
            padding: 20px;
            margin: 20px 0;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bvth Service</h1>
        <p>Votre destination pour le matériel téléphonique</p>
    </header>

    <nav>
        <a href="#home">Accueil</a>
        <a href="#products">Produits</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <div class="payment-info">
            <h2>Paiement par Orange Money</h2>
            <p>Numéro de paiement: <strong>77 123 45 67</strong></p>
            <p>Procédure:
                <ol>
                    <li>Sélectionnez votre produit</li>
                    <li>Cliquez sur "Acheter"</li>
                    <li>Effectuez le transfert via Orange Money</li>
                    <li>Envoyez la confirmation au +221 77 123 45 67</li>
                </ol>
            </p>
        </div>

        <div class="products" id="products">
            <div class="product-card">
                <img src="cable-usb.jpg" alt="Câble USB">
                <h3>Câble USB Original</h3>
                <p class="price">2 500 FCFA</p>
                <button class="buy-btn">Acheter</button>
            </div>

            <div class="product-card">
                <img src="chargeur.jpg" alt="Chargeur">
                <h3>Chargeur Rapide</h3>
                <p class="price">4 000 FCFA</p>
                <button class="buy-btn">Acheter</button>
            </div>

            <div class="product-card">
                <img src="ecouteurs.jpg" alt="Écouteurs">
                <h3>Écouteurs Bluetooth</h3>
                <p class="price">8 000 FCFA</p>
                <button class="buy-btn">Acheter</button>
            </div>
        </div>

        <div id="contact">
            <h2>Contact</h2>
            <form>
                <input type="text" placeholder="Nom" required>
                <input type="email" placeholder="Email" required>
                <textarea placeholder="Message" required></textarea>
                <button type="submit">Envoyer</button>
            </form>
        </div>
    </div>

    <footer>
        <p>© 2023 Bvth Service - Tous droits réservés</p>
        <p>Paiement sécurisé par Orange Money</p>
    </footer>
</body>
</html>