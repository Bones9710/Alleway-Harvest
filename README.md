
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alleway Harvest - Produits Locaux de Saint-Martin</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-image: url('guavaberry-trees.jpg'); background-size: cover; }
        header { background: #8B0000; color: white; text-align: center; padding: 20px; }
        section { padding: 20px; max-width: 800px; margin: auto; background: rgba(255, 255, 255, 0.8); border-radius: 10px; }
        .product { border: 1px solid #ddd; padding: 15px; margin: 10px 0; text-align: center; background: rgba(255, 255, 255, 0.9); }
        footer { background: #333; color: white; text-align: center; padding: 10px; position: fixed; width: 100%; bottom: 0; }
        .highlight { text-align: center; margin-bottom: 20px; }
        .highlight img { width: 100%; border-radius: 10px; }
    </style>
</head>
<body>
    <header>
        <h1>Alleway Harvest</h1>
        <p>Spécialiste du Guavaberry à Saint-Martin</p>
    </header>
    <section class="highlight">
        <h2>Découvrez le Guavaberry</h2>
        <img src="guavaberry-fruit.jpg" alt="Fruits de Guavaberry">
        <p>Le Guavaberry, un fruit emblématique de Saint-Martin, utilisé pour créer une liqueur unique et savoureuse.</p>
    </section>
    <section>
        <h2>Nos Produits</h2>
        <div class="product">
            <h3>Liqueur de Guavaberry Rouge</h3>
            <p>Bouteille de 750ml - 25€</p>
        </div>
        <div class="product">
            <h3>Liqueur de Guavaberry Jaune</h3>
            <p>Bouteille de 750ml - 25€</p>
        </div>
    </section>
    <section>
        <h2>Contact</h2>
        <p>Pour toute commande ou information, contactez-nous :</p>
        <form>
            <label for="name">Nom :</label>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">Email :</label>
            <input type="email" id="email" name="email" required><br><br>
            <label for="message">Message :</label><br>
            <textarea id="message" name="message" required></textarea><br><br>
            <button type="submit">Envoyer</button>
        </form>
    </section>
    <footer>
        &copy; 2025 Alleway Harvest - Tous droits réservés.
    </footer>
</body>
</html>
