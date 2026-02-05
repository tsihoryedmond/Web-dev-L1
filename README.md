pizza coders 
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pizza Coder's</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- En-tête de la page -->
    <header>
        <nav>
            <ul>
                <li><a href="#accueil">Accueil</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Section Accueil -->
    <section id="accueil">
        <h1>Bienvenue chez Pizza Coder's</h1>
        <p>Les meilleures pizzas codées juste pour vous !</p>
    </section>

    <!-- Section Menu -->
    <section id="menu">
        <h2>Notre Menu</h2>
        <div class="pizza">
            <h3>Pizza Margherita</h3>
            <p>Tomate, mozzarella, basilic frais.</p>
        </div>
        <div class="pizza">
            <h3>Pizza Pepperoni</h3>
            <p>Pepperoni, mozzarella, sauce tomate.</p>
        </div>
        <div class="pizza">
            <h3>Pizza Végétarienne</h3>
            <p>Poivrons, olives, champignons, tomate, mozzarella.</p>
        </div>
    </section>

    <!-- Section Contact -->
    <section id="contact">
        <h2>Contactez-nous</h2>
        <form action="#" method="POST">
            <label for="nom">Votre Nom :</label>
            <input type="text" id="nom" name="nom" required>
            
            <label for="email">Votre Email :</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message :</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Envoyer</button>
        </form>
    </section>

    <!-- Pied de page -->
    <footer>
        <p>&copy; 2026 Pizza Coder's - Tous droits réservés.</p>
    </footer>
</body>
</html>
