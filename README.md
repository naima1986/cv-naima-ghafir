<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV - Naima Ghafir</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            background-color: #f4f4f4;
        }

        .cv-container {
            width: 90%;
            max-width: 1200px;
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            margin-top: 50px;
        }

        .left-column {
            width: 30%;
            background-color: #eaeaea;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .right-column {
            width: 65%;
            background-color: #ffffff;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        h1 {
            color: #333;
            margin-bottom: 20px;
        }

        h2 {
            color: #666;
            text-transform: uppercase;
            margin-bottom: 10px;
            border-bottom: 2px solid #ccc;
            padding-bottom: 5px;
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            margin-bottom: 10px;
        }

        .profile {
            margin-bottom: 30px;
        }

        .contact {
            margin-bottom: 30px;
        }

        .interests {
            margin-bottom: 30px;
        }

        .skills {
            display: flex;
            justify-content: space-between;
        }

        .languages, .software {
            width: 48%;
        }

        .icon {
            font-size: 18px;
            margin-right: 10px;
        }

        .logo {
            width: 100px;
            height: 100px;
            border: 2px solid #333;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            margin-bottom: 20px;
        }

        .logo svg {
            width: 60%;
            height: 60%;
        }
    </style>
</head>
<body>
    <div class="cv-container">
        <!-- Colonne de gauche -->
        <div class="left-column">
            <div class="logo">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="#333">
                    <path d="M12 2C6.477 2 2 6.477 2 12c0 5.523 4.477 10 10 10s10-4.477 10-10C22 6.477 17.523 2 12 2zm0 18c-4.411 0-8-3.589-8-8s3.589-8 8-8 8 3.589 8 8-3.589 8-8 8z"/>
                    <path d="M12 14c-1.1 0-2-.9-2-2s.9-2 2-2 2 .9 2 2-.9 2-2 2z"/>
                </svg>
            </div>

            <h2>PROFIL</h2>
            <p>Déterminé, sérieux, autonome et conscient du travail qui m'attend, je suis persuadé que je serais un élément moteur au sein de votre structure !</p>

            <h2>CONTACT</h2>
            <ul>
                <li><i class="icon">&#xf044;</i> gzenaya tanger</li>
                <li><i class="icon">&#xf0e0;</i> ghafirnaima2016@gmail.com</li>
                <li><i class="icon">&#xf095;</i> 0664312458</li>
                <li><i class="icon">&#xf1b9;</i> Permis</li>
            </ul>

            <h2>CENTRES D'INTÉRÊT</h2>
            <ul>
                <li><strong>SPORTS :</strong> Vélo, Natation</li>
                <li><strong>VOYAGES :</strong> Découvert un nouveau monde</li>
            </ul>
        </div>

        <!-- Colonne de droite -->
        <div class="right-column">
            <h1>Naima Ghafir</h1>

            <h2>FORMATION</h2>
            <ul>
                <li>2025 - Préparation de licence professionnel en génie informatique et développement des logiciels en groupe IKI</li>
                <li>2013 - Diplôme de technicienne de gestion informatique</li>
                <li>2008 - 1ère année en littérature française</li>
                <li>2007-2008 - 2ème année en droit français</li>
                <li>2005 - Bac littéraire</li>
            </ul>

            <h2>EXPÉRIENCES</h2>
            <ul>
                <li>
                    <strong>22/01/2023 - Formatrice</strong><br>
                    <span>- formatrice dans une société du câblage.</span>
                </li>
                <li>
                    <strong>21/01/2010 - Opératrice</strong><br>
                    <span>- j'ai occupé le poste d'opératrice dans une société du câblage.</span>
                </li>
            </ul>

            <h2>COMPÉTENCES</h2>
            <div class="skills">
                <div class="languages">
                    <h3>LANGUES</h3>
                    <ul>
                        <li>Arabe : Bilingue</li>
                        <li>Anglais : Niveau débutant</li>
                        <li>Français : Niveau avancé</li>
                    </ul>
                </div>
                <div class="software">
                    <h3>LOGICIELS MAÎTRISÉS</h3>
                    <ul>
                        <li>développement des logiciels</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
