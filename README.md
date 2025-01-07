<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contactez-nous - Matcha Tea</title>
    <link rel="stylesheet" href="Masha3.css">
    <script src="https://unpkg.com/boxicons@2.1.4/dist/boxicons.js"></script>
</head>
<body>
    <!-- Header -->
    <header class="header">
        
        <h1 class="title">Matcha Tea</h1>
        <div class="cart">
            <a href="#" class="cart-link">
                <span class="cart-icon">🛒</span>
            </a>
        </div>
      
    </header>
    <div class="DI">
        <p>Discutons autour d'une bonne tasse de Thé </p>
    </div>
     <!-------------Img----------------->
 <img src="R.jpg" alt="Thé">



      <!-------------Img----------------->
    <!-- Formulaire de contact -->
    <main class="contact-form-container">
        <h2>Formulaire de Contact</h2>
        <form action="#" method="post">
            <div class="form-group">
                <label for="name">Nom :</label>
                <input type="text" id="name" name="name" placeholder="Votre nom complet" required>
            </div>
            <div class="form-group">
                <label for="email">Email :</label>
                <input type="email" id="email" name="email" placeholder="Votre adresse email" required>
            </div>
            <div class="form-group">
                <label for="sex">Sexe :</label>
                <select id="sex" name="sex" required>
                    <option value=""> Sélectionnez </option>
                    <option value="male">Homme</option>
                    <option value="female">Femme</option>
                    <option value="other">Autre</option>
                    <option value="prefer-not-say">Préfére ne pas répondre</option>
                </select>
            </div>
            <div class="form-group">
                <label for="favorite-tea">Thé préféré :</label>
                <input type="text" id="favorite-tea" name="favorite-tea" placeholder="Votre thé préféré (optionnel)">
            </div>
            <div class="form-group">
                <label for="message">Message :</label>
                <textarea id="message" name="message" rows="5" placeholder="Votre message..." required></textarea>
            </div>
            <div class="form-group">
                <button type="submit">Envoyer</button>
            </div>
        </form>
    </main>
      <section class="box">
      <h1> Contactez-nous</h1>
     <p> Notre équipe est à votre disposition pour vous répondre à toutes vos questions et vous conseiller au mieux
        sur les selections de produits ou quelconque demandes.
     </p>
      </section>

<!------------------------------FOOTER--------------------------------------------------------->
<footer class="footer">
    <div class="footer-h1">
       <div class="footer1">
          <h1>Masha Thé</h1>
        <p>Conditions d'utilisations</p>
        <p>Conditions d'expéditions </p>
        <p>Politique de remboursements</p>
        <p>Politique de confidentialité</p>
        <p>Mentions légales</p>
       </div>
        <div class="footer2">
            <h1>Information</h1>
             <p>Contact</p>
             <p>FAQ</p>
             <p>Suivi de commandes</p>
        </div>
        <div class="footer3">
            <h1>Boutique</h1>
            <p>88 Rue M.Berliet , 69008 Lyon</p>
            <p>Lundi . vendredi : 9h - 18h</p>
            <p>Tél : <u>09 59 97 80 00</u></p>
            <div class="box-icons">
                <box-icon type='solid' name='envelope'></box-icon>
                <box-icon type='logo' name='linkedin-square'></box-icon>
                <box-icon type='logo' name='github'></box-icon>
            </div>
        </div>
    </div>
   </footer>
</body>
</html>
