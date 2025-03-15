# Envoi-Express
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Envoi Express - Votre partenaire de confiance pour le déménagement au Maroc et à l'international. Services professionnels d'emballage, transport et manutention.">
    <meta name="keywords" content="déménagement, Maroc, transport, emballage, manutention, déménagement international, MarocMoveTrans, Casablanca, Rabat, Tanger">
    <meta name="author" content="Envoi Express">
    <meta name="robots" content="index, follow">
    
    <!-- Open Graph Meta Tags for Social Media -->
    <meta property="og:title" content="Envoi Express - Services de Déménagement Professionnel">
    <meta property="og:description" content="Services de déménagement fiables et professionnels au Maroc et à l'international. Devis gratuit pour votre prochain déménagement.">
    <meta property="og:image" content="https://www.envoi-express.com/images/logo.png"> <!-- Add your logo URL -->
    <meta property="og:url" content="https://www.envoi-express.com"> <!-- Add your website URL -->
    
    <!-- Canonical Link for SEO -->
    <link rel="canonical" href="https://www.envoi-express.com"> <!-- Your homepage URL -->
    <title>Envoi Express - Services de Déménagement Professionnel au Maroc | Déménagement International</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    
    <!-- Custom CSS -->
    <style>
        .body {
    background: #e0e0e0;
    margin: 0;
    padding: 0;
}

.navbar {
    background: #ffffff;
    height: 60px;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.navbar .container {
    padding-left: 0;
}

.navbar-brand {
    padding-left: 0;
    margin-left: 0;
    
}

.navbar-brand img {
    width: 40px;
    height: 40px;
    border-radius: 50%;
    object-fit: cover;
    margin-left: 0;
    float: left;
    
}


.feature-card {
    padding: 30px;
    text-align: center;
    background: #ffffff;
    border-radius: 50px;
    box-shadow: 0 8px 20px rgba(135, 162, 255, 0.1);
    transition: all 0.3s ease;
    margin: 20px 0;
    cursor: pointer;
}

.feature-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 12px 25px rgba(135, 162, 255, 0.15);
}

.feature-card h3 {
    color: #002147;
    margin: 20px 0;
    font-weight: 600;
    font-size: 1.4rem;
}

.feature-card p {
    color: #4a5568;
    line-height: 1.6;
    margin-bottom: 0;
}

.testimonial-card {
    background: #ffffff;
    padding: 30px;
    border-radius: 20px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.1);
    margin: 20px 0;
    transition: all 0.3s ease;
}

.testimonial-card:hover {
    transform: translateY(-5px);
    
    box-shadow: 0 8px 25px rgba(135, 162, 255, 0.2);
}

.testimonial-card .avatar {
    width: 60px;
    height: 60px;
    border-radius: 50%;
    margin-bottom: 15px;
}

.testimonial-card .name {
    font-weight: 600;
    color: #002147;
    margin-bottom: 5px;
}

.testimonial-card .rating {
    color: #ffd700;
    margin-bottom: 10px;
}

.testimonial-card .comment {
    color: #4a5568;
    font-style: italic;
    line-height: 1.6;
}

.win-win-section {
    background: linear-gradient(135deg, #87A2FF 0%, #ffffff 100%);
    padding: 120px 0;
    border-radius: 30px;
    box-shadow: 0 15px 30px rgba(0,0,0,0.1);
    margin: 50px 0;
    position: relative;
    overflow: hidden;
}

.win-win-section::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: linear-gradient(45deg, rgba(255,255,255,0.1) 0%, rgba(255,255,255,0.3) 100%);
    transform: skewY(-5deg);
}

.service-card {
    background: rgb(255, 255, 255);
    padding: 40px;
    border-radius: 20px;
    box-shadow: 0 15px 30px rgba(0,0,0,0.1);
    transition: all 0.3s ease;

}

footer {
    background: linear-gradient(135deg, #002147 0%, #003366 100%);
    color: #ffffff;
    padding: 80px 0 40px;
}

.social-icon {
    background: rgba(255, 255, 255, 0.08);
    padding: 12px;
    border-radius: 50%;
    display: inline-flex;
    margin: 0 10px;
}

.social-icon img {
    width: 20px;
    height: 20px;
}
.link ul li a{
   
    
    border-radius: 15px;
   
    text-align: center;
    
}
.link ul li a:hover{
    background-color: #3460fd;
    border-radius: 15px;
    
    
}
@media screen and (max-width:950px){
    .link ul li{
        justify-content: center;
    }
    .link ul li a{
        justify-content: center;

    }
    .link ul li a:hover{
        background-color: #3460fd;
        border-radius: 15px;
        
        
        
    }

}
.expedier{
justify-content: center;
margin: 0;
}

/* About Section Styles */
.about-section {
padding: 80px 0;
background-color: #f8f9fa;
}

.about-section h2 {
font-size: 2.5rem;
font-weight: 700;
color: #113f85;
margin-bottom: 30px;
}

.about-section p {
font-size: 1.1rem;
line-height: 1.8;
color: #6c757d;
margin-bottom: 20px;
}

.about-section .about-image {
border-radius: 10px;
box-shadow: 0 10px 30px rgba(0,0,0,0.1);
overflow: hidden;
}

.about-section .about-image img {
width: 100%;
height: auto;
transition: transform 0.3s ease;
}

.about-section .about-image:hover img {
transform: scale(1.05);
}
.navbar .expedier{
    width: 300px;
}
@media screen and (max-width: 768px) {
.about-section {
padding: 60px 0;
}

.about-section h2 {
font-size: 2rem;
}
}
/* How it Works Section Styles */
.how-it-works-section {
background-color: #ffffff;
padding: 80px 0;
}

.how-it-works-section h2 {
font-size: 2.5rem;
font-weight: 700;
color: #113f85;
}

.step-card {
background-color: #f8f9fa;
border-radius: 15px;
transition: transform 0.3s ease, box-shadow 0.3s ease;
border: 1px solid #e9ecef;
}

.step-card:hover {
transform: translateY(-5px);
box-shadow: 0 10px 20px rgba(0,0,0,0.1);
}

.step-card h3 {
font-size: 1.5rem;
color: #113f85;
margin-bottom: 1rem;
}

.step-card p {
color: #6c757d;
font-size: 1.1rem;
line-height: 1.6;
}

.mascot-container {
max-width: 300px;
margin: 0 auto;
}

.mascot-container img {
max-width: 100%;
height: auto;
}

.mascot-container p {
color: #6c757d;
font-size: 1.1rem;
}

@media screen and (max-width: 768px) {
.how-it-works-section {
    padding: 60px 0;
}


.how-it-works-section h2 {
    font-size: 2rem;
}

.step-card {
    margin-bottom: 20px;
}
.navbar .expedier{
    width: 100%;
}
}


#service h2{
color: #004d99;
}
.service-section {
background-color: white;
padding: 20px;
margin: 20px 0;
border-radius: 25px;
box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
box-shadow:2px 3px 10px #0000009c;
}

.service-section h2 {
font-size: 24px;
margin-bottom: 10px;
color: #333;
}

.service-section ul {
list-style-type: none;
padding: 0;
}

.service-section li {
font-size: 18px;
margin-bottom: 8px;
color: #555;
}

.service-section li::before {
content: "📦";
margin-right: 10px;
color: #007BFF;
}

/* Section About */
.about-section {
background-color: #f8f9fa;
padding: 80px 20px;
text-align: center;
}

.container {
max-width: 1200px;
margin: auto;
}

.section-title {
font-size: 2.5em;
color: #003366;
font-weight: bold;
text-transform: uppercase;
position: relative;
margin-bottom: 50px;
}

.section-title::after {
content: "";
display: block;
width: 80px;
height: 4px;
background-color: #ffd700;
margin: 10px auto 0;
border-radius: 2px;
}

/* Grille des cartes */
.about-container {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
gap: 30px;
}

/* Style des cartes */
.about-card {
background: white;
padding: 25px;
border-radius: 12px;
box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
transition: transform 0.3s ease, box-shadow 0.3s ease;
position: relative;
overflow: hidden;
}

.about-card:hover {
transform: translateY(-5px);
box-shadow: 0px 6px 15px rgba(0, 0, 0, 0.15);
}

/* Animation en haut des cartes */
.about-card::before {
content: "";
position: absolute;
width: 100%;
height: 5px;
background: #ffd700;
top: 0;
left: 0;
}

/* Icônes animées */
.icon img {
width: 80px;
height: 80px;
margin-bottom: 15px;
animation: float 3s ease-in-out infinite;
}

/* Animation flottante */
@keyframes float {
0%, 100% { transform: translateY(0px); }
50% { transform: translateY(-8px); }
}

/* Titres */
.about-card h3 {
font-size: 1.4em;
color: #004d99;
margin-bottom: 15px;
font-weight: bold;
}

/* Paragraphe */
.about-card p {
font-size: 1.1em;
line-height: 1.6;
color: #333;
}

/* Responsive */
@media (max-width: 768px) {
.section-title {
font-size: 2em;
}

.about-container {
grid-template-columns: 1fr;
}

.about-card {
padding: 20px;
}
}

/* Style des cartes */
.about-card {
background: white;
padding: 25px;
border-radius: 10px;
box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.about-card:hover {
transform: translateY(-5px);
box-shadow: 0px 6px 15px rgba(0, 0, 0, 0.15);
}

.about-card h3 {
font-size: 1.5em;
color: #004d99;
margin-bottom: 15px;
text-transform: uppercase;
}

.about-card p {
font-size: 1.1em;
line-height: 1.6;
color: #333;
}

/* Responsive */
@media (max-width: 750px) {


    .link ul li{
        display: flex;
        justify-content: center;
    }
    .link ul li a{
        justify-content: center;

    }
    .link ul li :hover{
        background-color: #3460fd;
        border-radius: 15px;
        width: 40%;
        
        
    }





.section-title {
font-size: 2em;
}
.navbar-collapse {
    position: absolute;
    top: 54px;
    left: 100%;
    padding-left: 15px;
    padding-right: 15px;
    padding-bottom: 15px;
    width: 80%;
    display: block;
    height: auto !important;
    transition: all 0.6s ease;
    margin-left: 20%;
   
    }
    .navbar-collapse.show {
    left: 0;
    }

.about-container {
grid-template-columns: 1fr;
}

.about-card {
padding: 20px;
}
}

.counter-container {
    background-color: white; /* Fond jaune doré */
    border: 7px solid black; /* Bordure noire épaisse */
    padding: 10px; /* Ajoute de l'espace autour du texte */
    text-align: center; /* Centre le texte */
    width: 40%; /* Largeur de la zone */
    margin: 50px auto; /* Centre horizontalement */
    border-radius: 50px; /* Coins arrondis */
    box-shadow: 5px 5px 15px rgba(0, 0, 0, 0.2); /* Légère ombre */
    position: relative; /* Nécessaire pour positionner l'image à droite */
}

.counter {
    font-size: 3em; /* Augmente la taille du compteur */
    font-weight: bold; /* Rend le texte gras */
    color: black; /* Texte en noir */
}

.counter-label {
    font-size: 1em; /* Taille du texte en dessous */
    color: black; /* Texte en noir */
}

.right-image {
    position: absolute; /* Permet de positionner l'image indépendamment du flux normal */
    left: -80px; /* Déplace l'image vers la droite */
    top: 50%; /* Centre l'image verticalement */
    transform: translateY(-50%); /* Assure que l'image est parfaitement centrée */
    width: 200px; /* Ajuste la taille de l'image si nécessaire */
}



    </style>
</head>
<body>
    <!-- Navigation -->
<body>

<nav class="navbar navbar-expand-lg fixed-top bg-light">
    <div class="container-fluid">
        <a class="navbar-brand d-flex align-items-center" href="#">
            <img src="https://media.licdn.com/dms/image/v2/C4E0BAQFgcE-5uAnb4Q/company-logo_200_200/company-logo_200_200/0/1630638188660?e=1749081600&v=beta&t=4AinKQXJExEBrH0fQtqnOfJR3tpsJUNjxs7KyIQiMaE" alt="Logo" width="40">
            <div class="ms-3">
                <span style="color: #113f85;">𝙀</span><span style="color: black;">𝙣𝙫𝙤𝙞 </span> 
                <span style="color: #113f85;">𝙀</span><span style="color: rgb(0, 0, 0);">𝙭𝙥𝙧𝙚𝙨𝙨</span>
            </div>
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
            aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse bg-white rounded-3" id="navbarNav">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item ms-3"><a class="nav-link" href="#home">Accueil</a></li>
                <li class="nav-item ms-3"><a class="nav-link" href="#service">Service</a></li>
                <li class="nav-item ms-3"><a class="nav-link" href="#comment">Avis</a></li>
                <li class="nav-item ms-3"><a class="nav-link" href="#contact">Contact</a></li>
                <li class="nav-item me-3"><a class="nav-link" href="#about">À Propos</a></li>
            </ul>
            <button onclick="toggleForm('shippingForm')" class="btn btn-primary btn-lg ms-3">Expédier un colis</button>
        </div>
    </div>
</nav>
<style>
/* Navbar Styling */
        .navbar {
            background: #ffffff;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
            padding: 15px 20px;
            border-radius: 10px;
        }

        /* Navbar Links */
        .navbar-nav .nav-link {
            font-size: 16px;
            font-weight: 500;
            color: #333;
            transition: color 0.3s ease-in-out, transform 0.2s;
        }

        .navbar-nav .nav-link:hover {
            color: #007bff;
            transform: scale(1.05);
        }

        /* Navbar Toggler */
        .navbar-toggler {
            border: none;
            outline: none;
        }

        .navbar-toggler:focus {
            box-shadow: none;
        }

        /* Expédier Button */
        .btn-primary {
            background: linear-gradient(135deg, #007bff, #0056b3);
            border: none;
            padding: 10px 20px;
            font-size: 18px;
            border-radius: 8px;
            transition: all 0.3s ease-in-out;
        }

        .btn-primary:hover {
            background: linear-gradient(135deg, #0056b3, #003d80);
            transform: scale(1.05);
        }

        /* Shipping Form Styling */
        #shippingForm {
            display: none;
            background: white;
            padding: 20px;
            margin-top: 10px;
            border-radius: 10px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease-in-out;
        }

        /* Fade-in effect */
        .show {
            display: block !important;
            animation: fadeIn 0.3s ease-in-out;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(-10px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
<!-- Bootstrap JavaScript -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
<section class="hero position-relative text-white py-5">
    <div class="container">
        <div class="row align-items-center">
            <div class="col-lg-8">
                <h1 class="display-3 fw-bold text-dark animate-fadeIn">Simple & Moins Cher</h1>
                <h2 class="display-5 fw-semibold animate-fadeIn">La Livraison Qu'il Vous Faut</h2>
                <p class="lead text-primary animate-slideUp">
                    Expédiez <span class="text-warning fw-bold">(presque) tout</span>, partout au Maroc grâce à des trajets déjà prévus.
                </p>

                <!-- Buttons -->
                <div class="d-flex gap-3 flex-wrap mt-4">
                    <button onclick="toggleForm('shippingForm')" class="btn btn-glow btn-lg">📦 Expédier un colis</button>
                    <button onclick="toggleForm('trackingForm')" class="btn btn-outline-light btn-lg btn-glow-dark">🔍 Voir les colis sur ma route</button>
                </div>

                <!-- Shipping Form -->
                <div id="shippingForm" class="form-container">
                    <h4 class="text-dark mb-3">📍 Informations d'expédition</h4>
                    <form>
                        <input type="text" class="form-control input-glow mb-3" placeholder="👤 Votre Nom" required>
                        <input type="tel" class="form-control input-glow mb-3" placeholder="📞 Numéro de téléphone" required>
                        <input type="text" class="form-control input-glow mb-3" placeholder="Ville de départ" required>
                        <input type="text" class="form-control input-glow mb-3" placeholder="Ville d'arrivée" required>
                        
    <button class="order">

        <span class="default">demander</span>
    
        <span class="success"> devis ajouté<svg viewbox="0 0 12 10">
    
            <polyline points="1.5 6 4.5 9 10.5 1"></polyline>
    
        </svg></span>
    
        <div class="box"></div>
    
        <div class="truck">
    
            <div class="back"></div>
    
            <div class="fronts">
    
                <div class="window"></div>
    
            </div>
    
            <div class="light top"></div>
    
            <div class="light bottom"></div>
    
        </div>
    
        <div class="lines"></div>
    
    </button>
    
    <!-- js api -->
    
    <script src='https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js'></script>
    
    <!-- js link-->
    
    
    
    <style>
    /* goole font link */
    
    @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap');
    
    /* root valu */
    
    :root{
    
        --primary:#ef4444;
    
        --primary-light: #f87171;
    
        --dark: #1c212e;
    
        --gray-dark:#3f4656;
    
        --gray: #6c7486;
    
        --gray-light: #cdd9ed;
    
        --white:#fff;
    
        --green:#16bf78;
    
        --sand: #fbbf24;
    
        --sand-light: #fbbf24;
    
        --blue: #000000;                   
    
    
    
    
    
    }
  
    
    
    body .dribbble {
    
        position: fixed;
    
        display: block;
    
        right: 20px;
    
        bottom: 20px;
        margin-left: 100px;
        margin-right: 50px;
    
    }
    
    body .dribbble img{
    
        display: block;
    
        height: 28px;
    
    }
    
    .order{
    
        -webkit-appearance: none;
    
        -moz-appearance: none;
    
        appearance: none;
    
        border: 0;
    
        background: var(--dark);
    
        position: relative;
    
        height: 63px;
    
        width: 240px;
    
        padding: 0;
        margin-left: 70px;
    
        outline: none;
    
        cursor: pointer;
    
        border-radius: 32px;
        background: #000000;
        color: #ffffff;
        font-size: 16px;
        font-weight: 600;
        text-transform: uppercase;
        letter-spacing: 0.5px;
        padding: 12px 24px;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    
    
    
        -webkit-tap-highlight-color: transparent;
    
        overflow: hidden;
    
        transition: all;
    
    }
    
    .order span{
    
        --o: 1;
    
        position: absolute;
    
        left: 0;
    
        right: 0;
    
        text-align: center;
    
        top: 19px;
    
        line-height: 24px;
    
        color: var(--white);
    
        font-size: 16px;
    
        opacity: var(--o);
    
        transition: opacity 0.3s ease;
    
    }
    
    .order span.default{
    
        transition-delay: 0.3s;
    
    }
    
    .order span.success{
    
        --offset: 16px;
    
        --o: 0;
    
    }
    
    .order span.success svg{
    
        width: 12px;
    
        height: 10px;
    
        display: inline-block;
    
        vertical-align: top;
    
        fill: none;
    
        margin: 7px 0 0 4px;
    
        stroke: var(--green);
    
        stroke-width: 2;
    
        stroke-linecap: round;
    
        stroke-linejoin: round;
    
        stroke-dasharray: 16px;
    
        stroke-dashoffset: var(--offset);
    
        transition: stroke-dashoffset 0.3s ease;
    
    }
    
    .order:active{
    
        transform: scale(0.96);
    
    }
    
    .order .lines{
    
        opacity: 0;
    
        position: absolute;
    
        height: 3px;
    
        background: var(--white);
    
        border-radius: 2px;
    
        width: 6px;
    
        top: 30px;
    
        left: 100%;
    
        box-shadow: 15px 0 0 var(--white),
    
                    30px 0 0 var(--white),
    
                    45px 0 0 var(--white),
    
                    60px 0 0 var(--white),
    
                    75px 0 0 var(--white),
    
                    90px 0 0 var(--white),
    
                    105px 0 0 var(--white),
    
                    120px 0 0 var(--white),
    
                    135px 0 0 var(--white),
    
                    150px 0 0 var(--white),
    
                    165px 0 0 var(--white),
    
                    180px 0 0 var(--white),
    
                    195px 0 0 var(--white),
    
                    210px 0 0 var(--white),
    
                    225px 0 0 var(--white),
    
                    240px 0 0 var(--white),
    
                    255px 0 0 var(--white),
    
                    270px 0 0 var(--white),
    
                    285px 0 0 var(--white),
    
                    300px 0 0 var(--white),
    
                    315px 0 0 var(--white),
    
                    330px 0 0 var(--white);
    
    }
    
    .order .back,
    
    .order .box{
    
        --start: var(--white);
    
        --stop: var(--gray-light);
    
        border-radius: 2px;
    
        background: linear-gradient(var(--start), var(--stop));
    
        position: absolute;
    
    }
    
    .order .truck{
    
        width: 60px;
    
        height: 41px;
    
        left: 100%;
    
        z-index: 1;
    
        top: 11px;
    
        position: absolute;
    
        transform: translateX(24px);
    
    }
    
    .order .truck::before,
    
    .order .truck::after{
    
        --r: -90deg;
    
        content: "";
    
        height: 2px;
    
        width: 20px;
    
        right: 58px;
    
        position: absolute;
    
        display: block;
    
        background: var(--white);
    
        border-radius: 1px;
    
        transform-origin: 100% 50%;
    
        transform: rotate(var(--r));
    
    }
    
    .order .truck::before{
    
        top: 4px;
    
    }
    
    .order .truck::after{
    
        --r: 90deg;
    
        bottom: 4px;
    
    }
    
    .order .truck .back{
    
        left: 0;
    
        top: 0;
    
        width: 60px;
    
        height: 41px;
    
        z-index: 1;
    
    }
    
    .order .truck .fronts{
    
        overflow: hidden;
    
        position: absolute;
    
        border-radius: 2px 9px 9px 2px;
    
        width: 26px;
    
        height: 41px;
    
        left: 60px;
    
    }
    
    .order .truck .fronts::before,
    
    .order .truck .fronts::after{
    
        content: "";
    
        position: absolute;
    
        display: block;
    
    }
    
    .order .truck .fronts::before{
    
        height: 13px;
    
        width: 2px;
    
        left: 0;
    
        top: 14px;
    
        background: linear-gradient(var(--gray), var(--gray-dark));
    
    }
    
    .order .truck .fronts::after{
    
        border-radius:  2px 9px 9px 2px;
    
        background: var(--primary);
    
        width: 24px;
    
        height: 41px;
    
        right: 0
    
    }
    
    .order .truck .fronts .window{
    
        overflow: hidden;
    
        border-radius: 2px 8px 8px 2px;
    
        background: var(--primary-light);
    
        transform: perspective(4px) rotateY(3deg);
    
        width: 22px;
    
        height: 41px;
    
        position: absolute;
    
        top: 0;
    
        z-index: 1;
    
        transform-origin: 0 50%;
    
    }
    
    .order .truck .fronts .window::before,
    
    .order .truck .fronts .window::after{
    
        content: "";
    
        position: absolute;
    
        right: 0;
    
    }
    
    .order .truck .fronts .window::before{
    
        top: 0;
    
        bottom: 0;
    
        width: 14px;
    
        background: var(--dark);
    
    }
    
    .order .truck .fronts .window::after{
    
        width: 14px;
    
        top: 7px;
    
        height: 4px;
    
        position: absolute;
    
        background: rgba(255, 255, 255, 0.14);
    
        transform: skewY(14deg);
    
        box-shadow:  0 7px 0 rgba(255, 255, 255, 0.14);
    
    }
    
    .order .truck .light{
    
        width: 3px;
    
        height: 8px;
    
        left: 83px;
    
        transform-origin: 100% 50%;
    
        position: absolute;
    
        border-radius: 2px;
    
        transform: scaleX(0.8);
    
        background: #f0dc5f;
    
    }
    
    .order .truck .light::before{
    
        content: "";
    
        height: 4px;
    
        width: 7px;
    
        opacity: 0;
    
        transform: perspective(2px) rotateY(-15deg) scaleX(0.94);
    
        position: absolute;
    
        transform-origin: 0 50%;
    
        left: 3px;
    
        top: 50%;
    
        margin-top: -2px;
    
        background: linear-gradient(90deg, #f0dc5f, rgba(240, 220, 95, 0.7), rgba(240, 220, 95, 0));
    
    }
    
    .order .truck .light.top{
    
        top: 4px;
    
    }
    
    .order .truck .light.bottom{
    
        bottom: 4px;
    
    }
    
    .order .box{
    
        --start:var(--sand-light);
    
        --stop: var(--sand);
    
        width: 21px;
    
        height: 21px;
    
        right: 100%;
    
        top: 21px;
    
    }
    
    .order .box::before, 
    
    .order .box::after{
    
        content:  "";
    
        top: 10px;
    
        position: absolute;
    
        left: 0;
    
        right: 0;
    
    }
    
    .order .box::before{
    
        height: 3px;
    
        margin-top: -1px;
    
        background: rgba(0, 0, 0, 0.1);
    
    }
    
    .order .box::after{
    
        height: 1px;
    
        background: rgba(0, 0, 0, 0.15);
    
    }
    
    .order.animate .default{
    
        --o: 0;
    
        transition-delay: 0s;
    
    }
    
    .order.animate .success{
    
        --offset: 0;
    
        --o: 1;
    
        transition-delay: 7s;
    
    }
    
    .order.animate .success svg{
    
        transition-delay: 7.3s;
    
    }
    
    .order.animate .truck{
    
        -webkit-animation: truck 10s ease forwards;
    
        animation: truck 10s ease forwards;
    
    }
    
    .order.animate .truck::before {
    
        -webkit-animation: door1 2.4s ease forwards 0.3s;
    
        animation: door1 2.4s ease forwards 0.3s;
    
    }
    
    .order.animate .truck::after{
    
        -webkit-animation: door2 2.4s ease forwards 0.6s;
    
        animation: door2 2.4s ease forwards 0.6s;
    
    }
    
    .order.animate .truck .light::before,
    
    .order.animate .truck .light::after{
    
        -webkit-animation: light 10s ease forwards;
    
        animation: light 10s ease forwards;
    
    }
    
    .order.animate .box{
    
        -webkit-animation: box 10s ease forwards;
    
        animation: box 10s ease forwards;
    
    }
    
    .order.animate .lines{
    
        -webkit-animation: lines 10s ease forwards;
    
        animation: lines 10s ease forwards;
    
    }
    
    @-webkit-keyframes truck {
    
        10%, 30%{
    
            transform: translateX(-164px);
    
        }
    
        40%{
    
           transform: translateX(-104px); 
    
        }
    
        60%{
    
            transform: translateX(-224px);
    
        }
    
        75%, 100%{
    
            transform: translateX(24px);
    
        }
    
    }
    
    @keyframes truck {
    
        10%, 30%{
    
            transform: translateX(-164px);
    
        }
    
        40%{
    
           transform: translateX(-104px); 
    
        }
    
        60%{
    
            transform: translateX(-224px);
    
        }
    
        75%, 100%{
    
            transform: translateX(24px);
    
        }
    
    }
    
    @-webkit-keyframes lines{
    
        0%, 30%{
    
            opacity: 0;
    
            transform: scaleY(0.7) translateX(0);
    
        }
    
        35%, 65%{
    
            opacity: 1;
    
        }
    
        70%{
    
            opacity: 0;
    
        }
    
        100%{
    
            transform: scaleY(0.7) translateX(-400px);
    
        }
    
    }
    
    @keyframes lines{
    
        0%, 30%{
    
            opacity: 0;
    
            transform: scaleY(0.7) translateX(0);
    
        }
    
        35%, 65%{
    
            opacity: 1;
    
        }
    
        70%{
    
            opacity: 0;
    
        }
    
        100%{
    
            transform: scaleY(0.7) translateX(-400px);
    
        }
    
    }
    
    @-webkit-keyframes light{
    
        0%, 30%{
    
            opacity: 0;
    
            transform: perspective(2px) rotateY(-15deg) scaleX(0.88);
    
        }
    
        40%, 100%{
    
            opacity: 1;
    
            transform: perspective(2px) rotateY(-15deg) scaleX(0.94);
    
        }
    
    }
    
    @keyframes light{
    
        0%, 30%{
    
            opacity: 0;
    
            transform: perspective(2px) rotateY(-15deg) scaleX(0.88);
    
        }
    
        40%, 100%{
    
            opacity: 1;
    
            transform: perspective(2px) rotateY(-15deg) scaleX(0.94);
    
        }
    
    }
    
    @-webkit-keyframes door1{
    
        30%, 50%{
    
            transform: rotate(32deg);
    
        }
    
    }
    
    @keyframes door1{
    
        30%, 50%{
    
            transform: rotate(32deg);
    
        }
    
    }
    
    @-webkit-keyframes door2{
    
        30%, 50%{
    
            transform: rotate(-32deg);
    
        }
    
    }
    
    @keyframes door2{
    
        30%, 50%{
    
            transform: rotate(-32deg);
    
        }
    
    }
    
    @-webkit-keyframes box{
    
        8%, 10%{
    
            transform: translateX(40px);
    
            opacity: 1;
    
        }
    
        25%{
    
            transform: translateX(112px);
    
            opacity: 1;
    
        }
    
        26%{
    
            transform: translateX(112px);
    
            opacity: 0;
    
        }
    
        27%, 100%{
    
            transform: translateX(0px);
    
            opacity: 0;
    
        }
    
    }
    
    @keyframes box{
    
        8%, 10%{
    
            transform: translateX(40px);
    
            opacity: 1;
    
        }
    
        25%{
    
            transform: translateX(112px);
    
            opacity: 1;
    
        }
    
        26%{
    
            transform: translateX(112px);
    
            opacity: 0;
    
        }
    
        27%, 100%{
    
            transform: translateX(0px);
    
            opacity: 0;
    
        }
    
    }
    </style>
                    </form>
                </div>

                <!-- Tracking Form -->
                <div id="trackingForm" class="form-container">
                    <h4 class="text-dark mb-3">🔍 Suivi de votre colis</h4>
                    <form>
                        <input type="text" class="form-control input-glow mb-3" placeholder="🔢 Entrez votre numéro de demande" required>
                        <button type="submit" class="btn btn-glow-dark w-100">📦 Rechercher mon colis</button>
                    </form>
                </div>
            </div>
        </div>
    </div>
</section>



<style>
/* 🌟 Background */
.hero {
    min-height: 100vh;
    background: linear-gradient(120deg, #1e3c72, #2a5298, #37d1d6);
    display: flex;
    align-items: center;
    border-radius: 40px;
    padding: 50px 0;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
}

/* ✨ Button Styles */
.btn-glow {
    background: linear-gradient(45deg, #007BFF, #1e90ff);
    color: white;
    font-weight: bold;
    border: none;
    padding: 12px 20px;
    transition: all 0.3s ease-in-out;
    box-shadow: 0px 4px 15px rgba(11, 85, 197, 0.4);
}
.btn-glow:hover {
    transform: scale(1.05);
    box-shadow: 0px 6px 20px rgba(19, 77, 185, 0.6);
}

/* 🖤 Dark Button */
.btn-glow-dark {
    background: linear-gradient(45deg, #141e30, #243b55);
    color: white;
    font-weight: bold;
    border: none;
    transition: all 0.3s ease-in-out;
    box-shadow: 0px 4px 15px rgba(36, 59, 85, 0.4);
}
.btn-glow-dark:hover {
    transform: scale(1.05);
    box-shadow: 0px 6px 20px rgba(36, 59, 85, 0.6);
}

/* 🔥 Input Fields */
.input-glow {
    border: 2px solid #2b80ff;
    border-radius: 8px;
    padding: 12px;
    font-size: 16px;
    transition: all 0.3s ease-in-out;
}
.input-glow:focus {
    border-color: #ff416c;
    box-shadow: 0px 0px 10px rgba(255, 65, 108, 0.5);
}

/* 🌀 Animated Forms */
.form-container {
    display: none;
    max-width: 400px;
    background: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.2);
    opacity: 0;
    transform: translateY(-10px);
    transition: opacity 0.5s ease-in-out, transform 0.5s ease-in-out;
}
.form-container.show {
    display: block;
    opacity: 1;
    transform: translateY(0);
}

/* 🎭 Fade & Slide Animations */
@keyframes fadeIn {
    from { opacity: 0; transform: translateY(-10px); }
    to { opacity: 1; transform: translateY(0); }
}
@keyframes slideUp {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
}

/* 🔄 Apply Animations */
.animate-fadeIn {
    animation: fadeIn 0.8s ease-in-out;
}
.animate-slideUp {
    animation: slideUp 0.8s ease-in-out;
}
</style>
<script>
    document.addEventListener("DOMContentLoaded", function () {
        const forms = document.querySelectorAll(".form-container");
        
        function toggleForm(formId) {
            const form = document.getElementById(formId);
    
            if (form.classList.contains("show")) {
                // Start fade-out effect by reducing opacity
                form.style.transition = "opacity 0.5s ease";  // Add transition
                form.style.opacity = "0";  // Set opacity to 0
                
                // After the fade-out duration, hide the form by removing the display property
                setTimeout(() => {
                    form.style.display = "none";
                }, 500); // Matches transition duration
                form.classList.remove("show");
            } else {
                forms.forEach(f => {
                    f.classList.remove("show");
                    // Start fade-out effect for other forms
                    f.style.transition = "opacity 0.5s ease";
                    f.style.opacity = "0";
                    setTimeout(() => {
                        f.style.display = "none";
                    }, 500);
                });
    
                form.style.display = "block";  // Show the form
                setTimeout(() => {
                    form.classList.add("show");
                    form.style.transition = "opacity 0.5s ease";  // Add transition
                    form.style.opacity = "1";  // Set opacity to 1 to make it visible
                }, 10); // Small delay to trigger transition
            }
        }
    
        window.toggleForm = toggleForm;
    });
    </script>
    
    
    <!-- Features Section -->
    <section class="features-section py-5">
        <div class="container">
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="feature-card">
                        <img src="https://img.freepik.com/premium-photo/cheerful-cartoon-dollar-symbol-clean-white-background_994764-194917.jpg" alt="Symbole dollar souriant" class="mb-3" style="width: 80px">
                        <h3>Livraison économique</h3>
                        <p>Jusqu'à 80% moins cher pour les gros colis, meubles et objets.</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="feature-card">
                        <img src="https://img.freepik.com/free-vector/cartoon-style-blue-shield_78370-1110.jpg" alt="Bouclier bleu" class="mb-3" style="width: 80px">
                        <h3>Assurance sérénité</h3>
                        <p>Une assurance pour tous vos envois ! Jusqu'à 5000€ en option.</p>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="feature-card">
                        <img src="https://png.pngtree.com/png-clipart/20240707/original/pngtree-cartoon-blue-star-with-smiling-face-png-image_15507812.png" alt="Étoile souriante" class="mb-3" style="width: 80px">
                        <h3>Excellente satisfaction</h3>
                        <p>Avis vérifiés : nos clients nous notent en moyenne 4,7 sur 5</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials py-5">
        <div class="container">
            <h2 class="text-center mb-4">Ce que nos clients disent de nous</h2>
            <p class="text-center mb-5">4,7/5 étoiles sur plus de 400 000 avis clients </p>
            
            <div class="row" id="comment">
                <div class="col-md-3">
                    <div class="testimonial-card p-3">
                        <div class="stars mb-2 text-warning">★★★★★</div>
                        <p class="testimonial-text">"Service excellent ! Mon canapé a été livré en parfait état et le transporteur était très professionnel."</p>
                        <p class="client-name">- Sophie D.</p>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="testimonial-card p-3">
                        <div class="stars mb-2 text-warning">★★★★★</div>
                        <p class="testimonial-text">"Rapide, efficace et économique. J'ai pu faire livrer mes meubles à un prix imbattable."</p>
                        <p class="client-name">- Mohammed L.</p>
                    </div>
                </div>
                    <div class="col-md-3">
                        <div class="testimonial-card p-3">
                            <div class="stars mb-2 text-warning">★★★★★</div>
                            <p class="testimonial-text">"Service impeccable ! Mon salon a été transporté sans aucun souci, et le personnel est très courtois."</p>
                            <p class="client-name">- Fatima Z.</p>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="testimonial-card p-3">
                            <div class="stars mb-2 text-warning">★★★★★</div>
                            <p class="testimonial-text">"Transport rapide et sécurisé. J'ai reçu mes colis à temps, je suis très satisfait."</p>
                            <p class="client-name">- Youssef A.</p>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="testimonial-card p-3">
                            <div class="stars mb-2 text-warning">★★★★★</div>
                            <p class="testimonial-text">"Très bonne communication et un excellent rapport qualité-prix. Je recommande sans hésitation."</p>
                            <p class="client-name">- Samira H.</p>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="testimonial-card p-3">
                            <div class="stars mb-2 text-warning">★★★★★</div>
                            <p class="testimonial-text">"Un service professionnel et fiable. Mon déménagement s'est fait sans stress."</p>
                            <p class="client-name">- Ahmed K.</p>
                        </div>
                    </div>
                </div>
            
    <script>
        document.addEventListener("DOMContentLoaded", function () {
    const commentContainer = document.getElementById("comment");
    commentContainer.style.display = "flex";
    commentContainer.style.flexDirection = "row";
    commentContainer.style.overflow = "hidden";
    commentContainer.style.whiteSpace = "nowrap";
    commentContainer.style.width = "100%";
    commentContainer.style.position = "relative";

    const testimonials = document.querySelectorAll(".testimonial-card");
    const wrapper = document.createElement("div");
    wrapper.style.display = "flex";
    wrapper.style.transition = "transform 0.5s ease-in-out";
    commentContainer.appendChild(wrapper);
    
    testimonials.forEach(testimonial => {
        testimonial.style.flex = "0 0 auto";
        testimonial.style.minWidth = "300px";
        testimonial.style.marginRight = "20px";
        wrapper.appendChild(testimonial);
    });

    let index = 0;

    function slideTestimonials() {
        wrapper.style.transform = `translateX(-${index * 320}px)`;
        index = (index + 1) % testimonials.length;
    }

    setInterval(slideTestimonials, 3000);
});
    </script>
            <div class="row g-4">
                <!-- Testimonial cards in a scrollable row -->
                <div class="col-12">
                    <div class="d-flex gap-4 overflow-auto pb-4">
                        <!-- Original testimonial cards content -->
                        <!-- Each card wrapped in a flex-shrink-0 div -->
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Win-Win Section -->
    <section class="win-win-section" style="background: #FFCF50;">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="display-5 mb-4" style="color: #000000;">La livraison des uns fait le bonheur des autres.</h2>
                <p class="lead" style="color: #000000;">
                    Les uns remboursent leurs frais de route, les autres paient leur livraison au prix juste. Un service gagnant-gagnant qui augmente votre pouvoir d'achat !
                </p>
            </div>

            <div class="row g-4">
                <div class="col-md-6">
                    <div class="service-card h-100">
                        <h3>Expédier ou recevoir un colis</h3>
                        <h4>Expéditeurs</h4>
                        <p>Avec Envoi Express, vous expédiez tous types de colis, même les plus volumineux, jusqu'à 60% moins cher ! C'est simple, économique et ça contribue à protéger notre planète.</p>
                        <a href="#" class="btn btn-primary mt-3">Expédier un colis</a>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="service-card h-100">
                        <h3>Transporteurs</h3>
                        <p>Avec Envoi Express, vous économisez en moyenne 600dh par trajet ! Que ce soit pour aller au bureau ou partir en vacances, toutes les occasions sont bonnes pour rentabiliser vos trajets.</p>
                        <a>Devenir transporteur</a>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- How it Works Section -->
    <section class="how-it-works-section py-5">
        <div class="container">
            <div class="text-center mb-5">
                <h2 class="display-5 mb-4">Comment ça marche</h2>
            </div>

            <div class="row g-4">
                <div class="col-md-4">
                    <div class="step-card h-100 p-4">
                        <h3>Créez une demande de transport</h3>
                        <p>Renseignez les caractéristiques du colis à envoyer (description, dimensions et poids). Ajoutez une photo et validez le prix.</p>
                    </div>
                </div>

                <div class="col-md-4">
                    <div class="step-card h-100 p-4">
                        <h3>Validez votre réservation</h3>
                        <p>Payez en ligne et bénéficiez de l'assurance Cocolis. Cocolis est tiers de confiance : le paiement est versé au transporteur une fois le colis livré.</p>
                    </div>
                </div>

                <div class="col-md-4">
                    <div class="step-card h-100 p-4">
                        <h3>Recevez des propositions</h3>
                        <p>Nous transmettons votre demande d'envoi à notre communauté : des voyageurs et des transporteurs dont le trajet coïncide avec votre livraison.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>



<!-- Déménagement & Transport Section -->
<div class="container-fluid p-5 rounded-5 my-1" id="service" style="background: #FFCF50">
    <div class="service-section">
        <h2>Déménagement & Transport</h2>
        <ul>
            <li>Déménagement Local – Transport de meubles et affaires personnelles dans la même ville.</li>
            <li>Déménagement National – Déplacement entre différentes villes du Maroc.</li>
            <li>Déménagement International – Transport et logistique pour un déménagement à l’étranger.</li>
            <li>Transport Express – Livraison rapide pour colis et petits déménagements.</li>
            <li>Transport de Marchandises – Pour professionnels et entreprises.</li>
        </ul>
    </div>
    
    <!-- Emballage & Protection Section -->
    <div class="service-section">
        <h2>Emballage & Protection</h2>
        <ul>
            <li>Fourniture de Matériel d’Emballage – Cartons, couvertures, papier bulle, etc.</li>
            <li>Service d’Emballage Professionnel – Protection des objets fragiles et électroniques.</li>
            <li>Démontage & Montage de Meubles – Assistance pour assembler et démonter les meubles.</li>
        </ul>
    </div>
    
    <!-- Services pour Entreprises & Bureaux Section -->
    <div class="service-section">
        <h2>Services pour Entreprises & Bureaux</h2>
        <ul>
            <li>Déménagement d’Entreprise – Déplacement de bureaux, archives et équipements.</li>
            <li>Archivage et Stockage – Espace de stockage temporaire pour documents et matériels.</li>
            <li>Transfert Industriel – Déménagement d’usines ou équipements lourds.</li>
        </ul>
    </div>
    
    <!-- Services Complémentaires Section -->
    <div class="service-section">
        <h2>Services Complémentaires</h2>
        <ul>
            <li>Stockage Sécurisé – Garde-meubles pour une courte ou longue durée.</li>
            <li>Nettoyage après Déménagement – Remise en état des locaux après départ.</li>
            <li>Assurance Déménagement – Protection contre les dommages et pertes.</li>
        </ul>
    </div>
    </div>
    
</div>


    <!-- About Section -->
    <section id="about" class="about-section">
        <div class="container">
            <h2 class="section-title text-center">À Propos de Nous</h2>
            <div class="about-container">
                <!-- Carte 1 -->
                <div class="about-card">
                    <div class="icon">
                        <img src="https://cdn-icons-png.flaticon.com/512/3595/3595587.png" alt="Entreprise">
                    </div>
                    <h3>NH COM, VOTRE PARTENAIRE DE CONFIANCE</h3>
                    <p>Depuis 2018, NH COM se distingue par sa position géostratégique au cœur du Maroc. Nous proposons des solutions logistiques innovantes pour vous accompagner dans votre croissance.</p>
                </div>
    
                <!-- Carte 2 -->
                <div class="about-card">
                    <div class="icon">
                        <img src="https://cdn-icons-png.flaticon.com/512/2905/2905711.png" alt="Livraison">
                    </div>
                    <h3>Spécialiste de la Livraison Express</h3>
                    <p>Nous assurons la prise en charge, le transport et la livraison rapide, que vous soyez une PME, une grande entreprise ou un e-commerçant.</p>
                </div>
    
                <!-- Carte 3 -->
                <div class="about-card">
                    <div class="icon">
                        <img src="https://cdn-icons-png.flaticon.com/128/9626/9626953.png" alt="Transport Urgent">
                    </div>
                    <h3>Transport Urgent</h3>
                    <p>Besoin d'une livraison dans l’heure ? Nous organisons un transport immédiat 24h/24, 7j/7 grâce à notre réseau étendu de chauffeurs-livreurs.</p>
                </div>
    
                <!-- Carte 4 -->
                <div class="about-card">
                    <div class="icon">
                        <img src="https://cdn-icons-png.flaticon.com/512/1519/1519159.png" alt="Messagerie">
                    </div>
                    <h3>Transport en Messagerie</h3>
                    <p>Avec plus de 5 ans d'expérience, nous livrons vos colis en 24/48/72h selon vos exigences avec un service fiable et sécurisé.</p>
                </div>
    
                <!-- Carte 5 : Fret Urgent 24/7 - Des délais imbattables -->
                <div class="about-card">
                    <div class="icon">
                        <img src="https://cdn-icons-png.flaticon.com/512/1478/1478930.png" alt="Fret Urgent">
                    </div>
                    <h3>Service de Livraison Premium</h3>
                    <p>Efficacité et précision pour tous vos envois
                        Nous prenons en charge la distribution de vos colis avec des délais adaptés à vos contraintes commerciales.</p>
                </div>
    
                <!-- Carte 6 : Solutions E-commerce -->
                <div class="about-card">
                    <div class="icon">
                        <img src="https://cdn-icons-png.flaticon.com/512/3081/3081559.png" alt="E-commerce">
                    </div>
                    <h3>Solutions E-commerce</h3>
                    <p>Optimisez vos ventes en ligne avec nos solutions dédiées : stockage, expédition rapide et suivi en temps réel pour une logistique fluide.</p>
                </div>
            </div>
        </div>
    </section>

    <button class="order">

        <span class="default">livraison express</span>
    
        <span class="success"> devis ajouté<svg viewbox="0 0 12 10">
    
            <polyline points="1.5 6 4.5 9 10.5 1"></polyline>
    
        </svg></span>
    
        <div class="box"></div>
    
        <div class="truck">
    
            <div class="back"></div>
    
            <div class="fronts">
    
                <div class="window"></div>
    
            </div>
    
            <div class="light top"></div>
    
            <div class="light bottom"></div>
    
        </div>
    
        <div class="lines"></div>
    
    </button>
    
    <!-- js api -->
    
    <script src='https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js'></script>
    
    <!-- js link-->
    
    
    
    <style>
    /* goole font link */
    
    @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap');
    
    /* root valu */
    
    :root{
    
        --primary:#ef4444;
    
        --primary-light: #f87171;
    
        --dark: #1c212e;
    
        --gray-dark:#3f4656;
    
        --gray: #6c7486;
    
        --gray-light: #cdd9ed;
    
        --white:#fff;
    
        --green:#16bf78;
    
        --sand: #fbbf24;
    
        --sand-light: #fbbf24;
    
        --blue: #000000;                   
    
    
    
    
    
    }
   
    
    
    body .dribbble {
    
        position: fixed;
    
        display: block;
    
        right: 20px;
    
        bottom: 20px;
        margin-left: 100px;
        margin-right: 50px;
    
    }
    
    body .dribbble img{
    
        display: block;
    
        height: 28px;
    
    }
    
    .order{
    
        -webkit-appearance: none;
    
        -moz-appearance: none;
    
        appearance: none;
    
        border: 0;
    
        background: var(--dark);
    
        position: relative;
    
        height: 63px;
    
        width: 240px;
    
        padding: 0;
        margin-left: 80px;
    
        outline: none;
    
        cursor: pointer;
    
        border-radius: 32px;
        background: #000000;
        color: #ffffff;
        font-size: 16px;
        font-weight: 600;
        text-transform: uppercase;
        letter-spacing: 0.5px;
        padding: 12px 24px;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    
    
    
        -webkit-tap-highlight-color: transparent;
    
        overflow: hidden;
    
        transition: all;
    
    }
    
    .order span{
    
        --o: 1;
    
        position: absolute;
    
        left: 0;
    
        right: 0;
    
        text-align: center;
    
        top: 19px;
    
        line-height: 24px;
    
        color: var(--white);
    
        font-size: 16px;
    
        opacity: var(--o);
    
        transition: opacity 0.3s ease;
    
    }
    
    .order span.default{
    
        transition-delay: 0.3s;
    
    }
    
    .order span.success{
    
        --offset: 16px;
    
        --o: 0;
    
    }
    
    .order span.success svg{
    
        width: 12px;
    
        height: 10px;
    
        display: inline-block;
    
        vertical-align: top;
    
        fill: none;
    
        margin: 7px 0 0 4px;
    
        stroke: var(--green);
    
        stroke-width: 2;
    
        stroke-linecap: round;
    
        stroke-linejoin: round;
    
        stroke-dasharray: 16px;
    
        stroke-dashoffset: var(--offset);
    
        transition: stroke-dashoffset 0.3s ease;
    
    }
    
    .order:active{
    
        transform: scale(0.96);
    
    }
    
    .order .lines{
    
        opacity: 0;
    
        position: absolute;
    
        height: 3px;
    
        background: var(--white);
    
        border-radius: 2px;
    
        width: 6px;
    
        top: 30px;
    
        left: 100%;
    
        box-shadow: 15px 0 0 var(--white),
    
                    30px 0 0 var(--white),
    
                    45px 0 0 var(--white),
    
                    60px 0 0 var(--white),
    
                    75px 0 0 var(--white),
    
                    90px 0 0 var(--white),
    
                    105px 0 0 var(--white),
    
                    120px 0 0 var(--white),
    
                    135px 0 0 var(--white),
    
                    150px 0 0 var(--white),
    
                    165px 0 0 var(--white),
    
                    180px 0 0 var(--white),
    
                    195px 0 0 var(--white),
    
                    210px 0 0 var(--white),
    
                    225px 0 0 var(--white),
    
                    240px 0 0 var(--white),
    
                    255px 0 0 var(--white),
    
                    270px 0 0 var(--white),
    
                    285px 0 0 var(--white),
    
                    300px 0 0 var(--white),
    
                    315px 0 0 var(--white),
    
                    330px 0 0 var(--white);
    
    }
    
    .order .back,
    
    .order .box{
    
        --start: var(--white);
    
        --stop: var(--gray-light);
    
        border-radius: 2px;
    
        background: linear-gradient(var(--start), var(--stop));
    
        position: absolute;
    
    }
    
    .order .truck{
    
        width: 60px;
    
        height: 41px;
    
        left: 100%;
    
        z-index: 1;
    
        top: 11px;
    
        position: absolute;
    
        transform: translateX(24px);
    
    }
    
    .order .truck::before,
    
    .order .truck::after{
    
        --r: -90deg;
    
        content: "";
    
        height: 2px;
    
        width: 20px;
    
        right: 58px;
    
        position: absolute;
    
        display: block;
    
        background: var(--white);
    
        border-radius: 1px;
    
        transform-origin: 100% 50%;
    
        transform: rotate(var(--r));
    
    }
    
    .order .truck::before{
    
        top: 4px;
    
    }
    
    .order .truck::after{
    
        --r: 90deg;
    
        bottom: 4px;
    
    }
    
    .order .truck .back{
    
        left: 0;
    
        top: 0;
    
        width: 60px;
    
        height: 41px;
    
        z-index: 1;
    
    }
    
    .order .truck .fronts{
    
        overflow: hidden;
    
        position: absolute;
    
        border-radius: 2px 9px 9px 2px;
    
        width: 26px;
    
        height: 41px;
    
        left: 60px;
    
    }
    
    .order .truck .fronts::before,
    
    .order .truck .fronts::after{
    
        content: "";
    
        position: absolute;
    
        display: block;
    
    }
    
    .order .truck .fronts::before{
    
        height: 13px;
    
        width: 2px;
    
        left: 0;
    
        top: 14px;
    
        background: linear-gradient(var(--gray), var(--gray-dark));
    
    }
    
    .order .truck .fronts::after{
    
        border-radius:  2px 9px 9px 2px;
    
        background: var(--primary);
    
        width: 24px;
    
        height: 41px;
    
        right: 0
    
    }
    
    .order .truck .fronts .window{
    
        overflow: hidden;
    
        border-radius: 2px 8px 8px 2px;
    
        background: var(--primary-light);
    
        transform: perspective(4px) rotateY(3deg);
    
        width: 22px;
    
        height: 41px;
    
        position: absolute;
    
        top: 0;
    
        z-index: 1;
    
        transform-origin: 0 50%;
    
    }
    
    .order .truck .fronts .window::before,
    
    .order .truck .fronts .window::after{
    
        content: "";
    
        position: absolute;
    
        right: 0;
    
    }
    
    .order .truck .fronts .window::before{
    
        top: 0;
    
        bottom: 0;
    
        width: 14px;
    
        background: var(--dark);
    
    }
    
    .order .truck .fronts .window::after{
    
        width: 14px;
    
        top: 7px;
    
        height: 4px;
    
        position: absolute;
    
        background: rgba(255, 255, 255, 0.14);
    
        transform: skewY(14deg);
    
        box-shadow:  0 7px 0 rgba(255, 255, 255, 0.14);
    
    }
    
    .order .truck .light{
    
        width: 3px;
    
        height: 8px;
    
        left: 83px;
    
        transform-origin: 100% 50%;
    
        position: absolute;
    
        border-radius: 2px;
    
        transform: scaleX(0.8);
    
        background: #f0dc5f;
    
    }
    
    .order .truck .light::before{
    
        content: "";
    
        height: 4px;
    
        width: 7px;
    
        opacity: 0;
    
        transform: perspective(2px) rotateY(-15deg) scaleX(0.94);
    
        position: absolute;
    
        transform-origin: 0 50%;
    
        left: 3px;
    
        top: 50%;
    
        margin-top: -2px;
    
        background: linear-gradient(90deg, #f0dc5f, rgba(240, 220, 95, 0.7), rgba(240, 220, 95, 0));
    
    }
    
    .order .truck .light.top{
    
        top: 4px;
    
    }
    
    .order .truck .light.bottom{
    
        bottom: 4px;
    
    }
    
    .order .box{
    
        --start:var(--sand-light);
    
        --stop: var(--sand);
    
        width: 21px;
    
        height: 21px;
    
        right: 100%;
    
        top: 21px;
    
    }
    
    .order .box::before, 
    
    .order .box::after{
    
        content:  "";
    
        top: 10px;
    
        position: absolute;
    
        left: 0;
    
        right: 0;
    
    }
    
    .order .box::before{
    
        height: 3px;
    
        margin-top: -1px;
    
        background: rgba(0, 0, 0, 0.1);
    
    }
    
    .order .box::after{
    
        height: 1px;
    
        background: rgba(0, 0, 0, 0.15);
    
    }
    
    .order.animate .default{
    
        --o: 0;
    
        transition-delay: 0s;
    
    }
    
    .order.animate .success{
    
        --offset: 0;
    
        --o: 1;
    
        transition-delay: 7s;
    
    }
    
    .order.animate .success svg{
    
        transition-delay: 7.3s;
    
    }
    
    .order.animate .truck{
    
        -webkit-animation: truck 10s ease forwards;
    
        animation: truck 10s ease forwards;
    
    }
    
    .order.animate .truck::before {
    
        -webkit-animation: door1 2.4s ease forwards 0.3s;
    
        animation: door1 2.4s ease forwards 0.3s;
    
    }
    
    .order.animate .truck::after{
    
        -webkit-animation: door2 2.4s ease forwards 0.6s;
    
        animation: door2 2.4s ease forwards 0.6s;
    
    }
    
    .order.animate .truck .light::before,
    
    .order.animate .truck .light::after{
    
        -webkit-animation: light 10s ease forwards;
    
        animation: light 10s ease forwards;
    
    }
    
    .order.animate .box{
    
        -webkit-animation: box 10s ease forwards;
    
        animation: box 10s ease forwards;
    
    }
    
    .order.animate .lines{
    
        -webkit-animation: lines 10s ease forwards;
    
        animation: lines 10s ease forwards;
    
    }
    
    @-webkit-keyframes truck {
    
        10%, 30%{
    
            transform: translateX(-164px);
    
        }
    
        40%{
    
           transform: translateX(-104px); 
    
        }
    
        60%{
    
            transform: translateX(-224px);
    
        }
    
        75%, 100%{
    
            transform: translateX(24px);
    
        }
    
    }
    
    @keyframes truck {
    
        10%, 30%{
    
            transform: translateX(-164px);
    
        }
    
        40%{
    
           transform: translateX(-104px); 
    
        }
    
        60%{
    
            transform: translateX(-224px);
    
        }
    
        75%, 100%{
    
            transform: translateX(24px);
    
        }
    
    }
    
    @-webkit-keyframes lines{
    
        0%, 30%{
    
            opacity: 0;
    
            transform: scaleY(0.7) translateX(0);
    
        }
    
        35%, 65%{
    
            opacity: 1;
    
        }
    
        70%{
    
            opacity: 0;
    
        }
    
        100%{
    
            transform: scaleY(0.7) translateX(-400px);
    
        }
    
    }
    
    @keyframes lines{
    
        0%, 30%{
    
            opacity: 0;
    
            transform: scaleY(0.7) translateX(0);
    
        }
    
        35%, 65%{
    
            opacity: 1;
    
        }
    
        70%{
    
            opacity: 0;
    
        }
    
        100%{
    
            transform: scaleY(0.7) translateX(-400px);
    
        }
    
    }
    
    @-webkit-keyframes light{
    
        0%, 30%{
    
            opacity: 0;
    
            transform: perspective(2px) rotateY(-15deg) scaleX(0.88);
    
        }
    
        40%, 100%{
    
            opacity: 1;
    
            transform: perspective(2px) rotateY(-15deg) scaleX(0.94);
    
        }
    
    }
    
    @keyframes light{
    
        0%, 30%{
    
            opacity: 0;
    
            transform: perspective(2px) rotateY(-15deg) scaleX(0.88);
    
        }
    
        40%, 100%{
    
            opacity: 1;
    
            transform: perspective(2px) rotateY(-15deg) scaleX(0.94);
    
        }
    
    }
    
    @-webkit-keyframes door1{
    
        30%, 50%{
    
            transform: rotate(32deg);
    
        }
    
    }
    
    @keyframes door1{
    
        30%, 50%{
    
            transform: rotate(32deg);
    
        }
    
    }
    
    @-webkit-keyframes door2{
    
        30%, 50%{
    
            transform: rotate(-32deg);
    
        }
    
    }
    
    @keyframes door2{
    
        30%, 50%{
    
            transform: rotate(-32deg);
    
        }
    
    }
    
    @-webkit-keyframes box{
    
        8%, 10%{
    
            transform: translateX(40px);
    
            opacity: 1;
    
        }
    
        25%{
    
            transform: translateX(112px);
    
            opacity: 1;
    
        }
    
        26%{
    
            transform: translateX(112px);
    
            opacity: 0;
    
        }
    
        27%, 100%{
    
            transform: translateX(0px);
    
            opacity: 0;
    
        }
    
    }
    
    @keyframes box{
    
        8%, 10%{
    
            transform: translateX(40px);
    
            opacity: 1;
    
        }
    
        25%{
    
            transform: translateX(112px);
    
            opacity: 1;
    
        }
    
        26%{
    
            transform: translateX(112px);
    
            opacity: 0;
    
        }
    
        27%, 100%{
    
            transform: translateX(0px);
    
            opacity: 0;
    
        }
    
    }
    </style>
    <script>
        $('.order').click(function (e) {
    
    let button = $(this);
    
    if(!button.hasClass('animate')) {
    
        button.addClass('animate');
    
        setTimeout(() => {
    
            button.removeClass('animate');
    
        }, 10000);
    
    }
    
    })
    </script>
<style>
    .about-card {
        background-color: #ffffff;
        border-radius: 10px;
        padding: 20px;
        box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        transition: transform 0.3s ease;
    }
    .about-card:hover {
        transform: translateY(-5px);
    }
    .about-card img {
        width: 50px;
        height: 50px;
        border-radius: 50%;
        object-fit: cover;
    }
    .about-card p {
        font-size: 16px;
        line-height: 1.6;
        color: #333;
    }
    .about-card h3 {
        font-size: 20px;
        font-weight: bold;
        margin-bottom: 10px;
    }
</style>
    <!-- Footer -->
    <footer class="pt-5">
        <div class="container" id="contact">
            <div class="row g-4">
                <div class="col-md-4">
                    <h3 class="h5 mb-3">Présentation</h3>
                    <p>A propos de Envoi Express</p>
                    <p>Nous sommes une entreprise de déménagement au Maroc</p>
                    <p>1er étage Appartement 02، 46 شارع عقبة بن نافع، الرباط 10090، المغرب</p>
                    <p>Rabat, Code postal : 10090 - Maroc.</p>
                    <p>Tél :0661334939</p>
                </div>
                <div class="col-md-4">
                    <h3 class="h5 mb-3">A propos de nous</h3>
                    <ul class="list-unstyled">
                        <li><a href="#about" class="text-white text-decoration-none">Présentation</a></li>
                        <li><a href="#about" class="text-white text-decoration-none">Notre Histoire</a></li>
                        <li><a href="#about" class="text-white text-decoration-none">Blog</a></li>
                    </ul>
                </div>
                <div class="col-md-4">
                    <h3 class="h5 mb-3">Services</h3>
                    <ul class="list-unstyled">
                        <li><a href="#" class="text-white text-decoration-none">Déménagement interurbain</a></li>
                        <li><a href="#" class="text-white text-decoration-none">Déménagement Résidentiel</a></li>
                        <li><a href="#" class="text-white text-decoration-none">Déménagement Commercial</a></li>
                        <li><a href="#" class="text-white text-decoration-none">Envoi Express</a></li>
                        <li><a href="#" class="text-white text-decoration-none">Nouveau</a></li>
                        <li><a href="#" class="text-white text-decoration-none">Entreposage</a></li>
                    </ul>
                    <div class="mt-4">
                        <h3 class="h5 mb-3">Suivez-nous</h3>
                        <div class="d-flex">
                            <a href="https://www.instagram.com/envoiexpress/" class="social-icon">
                                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e7/Instagram_logo_2016.svg/2048px-Instagram_logo_2016.svg.png" alt="Instagram">
                            </a>
                            <a href="https://www.facebook.com/EnvoiExpress" class="social-icon">
                                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Facebook_Logo_%282019%29.png/1024px-Facebook_Logo_%282019%29.png" alt="Facebook">
                            </a>
                            <a href="https://www.linkedin.com/company/envoi-express/about/" class="social-icon">
                                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/640px-LinkedIn_logo_initials.png" alt="LinkedIn">
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </footer>
    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
