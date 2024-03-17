<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>www.nectarconcept.fr</title>
    <link href="Users/clement/Desktop/HTML/Mon site/Websites/Site web template/App React/HOME/style.css" rel="stylesheet" type="text/css"/>
    <link href="Users/clement/Desktop/HOME/style.css" rel="stylesheet" type="text/css"/>
<style>
    body {
    background-color: black
    }

h1 {
    color: #F25774;
    font: 4.8rem "Stara", sans-serif;
    margin-left: 20px;
    font-weight: bolder;
    }

h3 {
    color: #FFFFFF;
    font: 2rem "Stara", sans-serif;
    margin-left: 20px;
    font-weight: bold;
    }

h4 {
    color: #FFFFFF;
    font: 1.6rem "Stara", sans-serif;
    margin-left: 20px;
    }


p {
    color: white;
    font: 1rem "Stara", sans-serif;
    margin-left: 20px;
    }

h6 {
    color: rgb(121,121,244);
    font: 1.5rem "Stara", sans-serif;
    margin-left: 20px;
    }

.box20 {
    font: 1rem "Stara", sans-serif;
    align-self: center;
    text-align: center;
    color: white
    }

.box21 {
    font: 1rem "Stara", sans-serif;
    align-self: center;
    text-align: center;
    color: white
    }

.topnav {
    background-color: black;
    overflow: hidden;
    margin-right: 20px;
    align-self: right;
    position: right;
    border-radius: 5%;
    font: 1rem "Stara", sans-serif;
    margin-right: 100px;
    }
  
.topnav a {
    float: right;
    color: #FFFFFF;
    text-align: right;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 15px;
    border-radius: 5%;
    font: 1rem "Stara", sans-serif;
    }
  
  .topnav a:hover {
    background-color: #ffffff;
    color: #090909;
    border-radius: 5%;
    font: 1rem "Stara", sans-serif;
    transition: 1s ease;
  }
  
  .topnav a.active {
    background-color: black;
    color: #F25774;
    font: 1rem "Stara", sans-serif;
  }

img {
    align-self: auto;
    width: 600px;
    height: auto;
    border-radius: 5%;
    object-fit: cover;
}

object {
    object-fit: contain;
    width: 800px;
    height: auto;
}

table {
    table-layout: fixed;
    width: 100%;
    border-spacing: 4.8rem 10px;
    border: 3px solid black;
    margin-left: auto;
    margin-right: auto;
    text-align: justify;
    }

.footer {
    border: none;
}


@import url('https://fonts.googleapis.com/css?family=Stara');

body{
	font-family: 'Stara', sans-serif;
}
* {
	margin: 0;
	padding: 0;
}
i {
	margin-right: 10px;
}

.navbar-logo{
	padding: 15px;
	color: #fff;
}
.navbar-mainbg{
	background-color: rgb(121,121,244);
	padding: 0px;
}
#navbarSupportedContent{
	overflow: hidden;
	position: relative;
}
#navbarSupportedContent ul{
	padding: 0px;
	margin: 0px;
}
#navbarSupportedContent ul li a i{
	margin-right: 10px;
}
#navbarSupportedContent li {
	list-style-type: none;
	float: left;
}
#navbarSupportedContent ul li a{
	color: rgba(255,255,255,0.5);
    text-decoration: none;
    font-size: 15px;
    display: block;
    padding: 20px 20px;
    transition-duration:0.6s;
	transition-timing-function: cubic-bezier(0.68, -0.55, 0.265, 1.55);
    position: relative;
}
#navbarSupportedContent>ul>li.active>a{
	color: rgb(121,121,244);
	background-color: transparent;
	transition: all 0.7s;
}
#navbarSupportedContent a:not(:only-child):after {
	content: "\f105";
	position: absolute;
	right: 20px;
	top: 10px;
	font-size: 14px;
	font-family: "Font Awesome 5 Free";
	display: inline-block;
	padding-right: 3px;
	vertical-align: middle;
	font-weight: 900;
	transition: 0.5s;
}
#navbarSupportedContent .active>a:not(:only-child):after {
	transform: rotate(90deg);
}
.hori-selector{
	display:inline-block;
	position:absolute;
	height: 100%;
	top: 0px;
	left: 0px;
	transition-duration:0.6s;
	transition-timing-function: cubic-bezier(0.68, -0.55, 0.265, 1.55);
	background-color: #fff;
	border-top-left-radius: 15px;
	border-top-right-radius: 15px;
	margin-top: 10px;
}
.hori-selector .right,
.hori-selector .left{
	position: absolute;
	width: 25px;
	height: 25px;
	background-color: #fff;
	bottom: 10px;
}
.hori-selector .right{
	right: -25px;
}
.hori-selector .left{
	left: -25px;
}
.hori-selector .right:before,
.hori-selector .left:before{
	content: '';
    position: absolute;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    background-color: rgb(121,121,244);
}
.hori-selector .right:before{
	bottom: 0;
    right: -25px;
}
.hori-selector .left:before{
	bottom: 0;
    left: -25px;
}


@media(min-width: 992px){
	.navbar-expand-custom {
	    -ms-flex-flow: row nowrap;
	    flex-flow: row nowrap;
	    -ms-flex-pack: start;
	    justify-content: flex-start;
	}
	.navbar-expand-custom .navbar-nav {
	    -ms-flex-direction: row;
	    flex-direction: row;
	}
	.navbar-expand-custom .navbar-toggler {
	    display: none;
	}
	.navbar-expand-custom .navbar-collapse {
	    display: -ms-flexbox!important;
	    display: flex!important;
	    -ms-flex-preferred-size: auto;
	    flex-basis: auto;
	}
}

.audit {
    color: #FFFFFF;
    font: 1.6rem "Stara", sans-serif;
    margin-left: auto;
    margin-right: auto;
    text-align: justify;
    border-color: #FFFFFF;
    border-radius: 20px;
    border: solid;
    border-width: 1px;
    padding : 30px;
}

.marketing {
    color: #FFFFFF;
    font: 1.6rem "Stara", sans-serif;
    margin-left: auto;
    margin-right: auto;
    text-align: justify;
    border-color: #FFFFFF;
    border-radius: 20px;
    border: solid;
    border-width: 1px;
    padding : 30px;
}

.site {
    color: #FFFFFF;
    font: 1.6rem "Stara", sans-serif;
    margin-left: auto;
    margin-right: auto;
    text-align: justify;
    border-color: #FFFFFF;
    border-radius: 20px;
    border: solid;
    border-width: 1px;
    padding : 30px;
}

.interface {
    color: #FFFFFF;
    font: 1.6rem "Stara", sans-serif;
    margin-left: auto;
    margin-right: auto;
    text-align: justify;
    border-color: #FFFFFF;
    border-radius: 20px;
    border: solid;
    border-width: 1px;
    padding : 30px;
}

.referencement {
    color: #FFFFFF;
    font: 1.6rem "Stara", sans-serif;
    margin-left: auto;
    margin-right: auto;
    text-align: justify;
    border-color: #FFFFFF;
    border-radius: 20px;
    border: solid;
    border-width: 1px;
    padding : 30px;
}

.lancement {
    color: #FFFFFF;
    font: 1.6rem "Stara", sans-serif;
    margin-left: auto;
    margin-right: auto;
    text-align: justify;
    border-color: #FFFFFF;
    border-radius: 20px;
    border: solid;
    border-width: 1px;
    padding : 30px;
}

.allie {
    color: #FFFFFF;
    font: 1.6rem "Stara", sans-serif;
    margin-left: auto;
    margin-right: auto;
    text-align: justify;
    border-color: #FFFFFF;
    border-radius: 20px;
    border: solid;
    border-width: 1px;
    padding : 30px;
}

.styled {
    border: 0.1;
    border-color: #ffffff;
    line-height: 2.5;
    padding: 0 20px;
    font-size: 1rem;
    text-align: center;
    color: #ffffff;
    text-shadow: 1px 1px 1px #7a7a7a;
    border-radius: 30px;
    background-color: black;
    margin-left: 20px;
  }
  
  .styled:hover {
    border-color: rgb(121,121,244);
    color: rgb(121,121,244);
    font-size: 0.9rem;
    transition: 0.2s ease;
  }
  
  .styled:active {
    box-shadow:
      inset: #F25774;
      inset 2px 2px 3px #F25774;
  }

  .styled2 {
    border: 0.1;
    border-color: #ffffff;
    line-height: 2.5;
    padding: 0 20px;
    font-size: 1rem;
    text-align: center;
    color: #ffffff;
    text-shadow: 1px 1px 1px #7a7a7a;
    border-radius: 30px;
    background-color: black;
    margin-left: 15px;
  }
  
  .styled2:hover {
    border-color: rgb(121,121,244);
    color: rgb(121,121,244);
    font-size: 0.9rem;
    transition: 0.2s ease;
  }
  
  .styled2:active {
    box-shadow:
      inset: #F25774
      inset 2px 2px 3px #F25774;
  }

span {
    display: inline-block;
    background: linear-gradient(to left, #F25774, rgb(121,121,244));
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    margin-left: 20px;
    font-size: 50px;
    font: "Stara", sans-serif;
}

video {
	max-width: 100%;
	height: auto;
    align-self : center;
    position: relative;
    border: none;
    background-color: black;
}

.starter {
    color: white;
    font: 1.6rem "Stara", sans-serif;
    margin-left: auto;
    margin-right: auto;
    text-align: justify;
    border-color: none;
    background-color: #0c0c0c;
    border-radius: 20px;
    border: solid;
    border-width: 0px;
    padding : 30px;
}

.flex {
    color: white;
    font: 1.6rem "Stara", sans-serif;
    margin-left: auto;
    margin-right: auto;
    text-align: justify;
    border-color: none;
    background-color: #0c0c0c;
    border-radius: 20px;
    border: solid;
    border-width: 0px;
    padding : 30px;
}

.full {
    color:white;
    font: 1.6rem "Stara", sans-serif;
    margin-left: auto;
    margin-right: auto;
    text-align: justify;
    border-color: none;
    background-color: #0c0c0c;
    border-radius: 20px;
    border: solid;
    border-width: 0px;
    padding : 30px;
}

.adefinir {
    color: white;
    font: 1.6rem "Stara", sans-serif;
    margin-left: auto;
    margin-right: auto;
    text-align: justify;
    border-color: none;
    background-color: #0c0c0c;
    border-radius: 20px;
    border: solid;
    border-width: 0px;
    padding : 30px;
}

h5 {
    color: white;
    font: 1rem "Stara", sans-serif;
    margin-left: 20px;
    }

.space {
    height: 100vh;
}

li {
    color: white;
    font: 1rem "Stara", sans-serif;
    margin-left: 20px;
    list-style-type: "\1F44D";
    }

ul {
    color: white;
    font: 1rem "Stara", sans-serif;
    margin-left: 20px;
    list-style-type: "\1F44D";
    }
</style>
    
</head>
<body>
    <div class="topnav">
        <a href="#contact">Contact</a>
        <a href="#devis">Devis</a>
        <a href="#Ressources">Ressources</a>
        <a href="#solutions">Solutions</a>
        <a href="#services">Services</a>
        <a class="active" href="#accueil">Accueil</a>
      </div>
    <br>
    <div id="accueil">
        <div class="video">
            <video preload="auto" autoplay muted loop src="Users/clement/Desktop/HTML/Mon site/Websites/Site web template/Final teaser.mp4" type="video"></video>
        </div>
    </div>
    <br>
    <br>
    <br>
    <br>
    <div class="responsive-timeline">
    <br>
    <br>
    <br>
    <br>
    <br></div>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <div id="services">
    <table>
        <tr>
            <td>
                <span>Prêts pour l'aventure</span>
                <br>
                <br>
                <br>
                <br>
                <br>
            </td>
        </tr>
    </table>
    </div>
    <br>
    <br>
    <table>
        <tr>
            <td><div class="object"><img src="Users/clement/Desktop/HTML/Mon site/Websites/Site web template/App React/React.Js.png"></div></td>
            <td>
            <h3>Le design next generation</h3>
            <br>
            <h4>Entrepreneurs individuels, TPE & PME français<br> utilisent Nectar,
            pour construire leur identité de<br> marque et développer leur 
            patrimoine digital</h4>
            <br>
            <br>
            <input class="styled" type="button" value="Devis" />
            <input class="styled2" type="button" value="Nous contacter" />
            <br>
        </tr>
    </table>
    <br>
    <br>
    <br>
    <br>
    <table>
        <tr>
            <td><h3>Une solution multi-potentiel</h3>
            <br>
            <p>Vous pouvez utiliser Nectar pour changer d'interface web,mais aussi pour optimiser vos processus de vente,
            mettre à niveau vos systèmes et outils existants,proposer vos produits et services directement aux
            consommateurs,simplifier votre tunnel de vente en ligne et créer des visuels uniques. Bénéficiez des conseils
            de notre équipe,des services aux entreprises et de nos partenaires pour tirer plus rapidement profit de votre solution Nectar.</p></td>
            <td><img src="Users/clement/Desktop/HTML/Mon site/Websites/Site web template/App React/1_X6MdPvKC_JnapInkGYObdQ.gif"></td>
        </tr>
    </table>
    <table>
        <tr>
            <td><img src="Users/clement/Desktop/HTML/Mon site/Websites/Site web template/App React/0_F3Gi5iXlor4CCInA.gif"></td>
            <td><h3>Favorisez l'agilité de votre entreprise</h3>
            <br>
            <p>Vous pouvez utiliser Nectar pour changer d'interface web, mais aussi pour optimiser vos processus de vente, mettre à
                niveau vos systèmes et outils existants, proposer vos produits et services directement aux consommateurs, simplifier votre
                tunnel de vente en ligne et créer des visuels uniques. Bénéficiez des conseils de notre équipe, des services aux
                entreprises et de nos partenaires pour tirer plus rapidement profit de votre solution Nectar.</p></td> 
        </tr>
    </table>
<br>
<br>
    <table>
        <tr>
            <td><h3>Développez votre entreprise plus efficacement</h3>
            <br>
            <p>Les start-up font confiance à Nectar pour se lancer plus rapidement, évoluer plus facilement, faciliter le parcours
            de leurs clients et construire des outils simples à prendre en main afin de faire mieux avec moins. Utilisez nos solutions 
            sans code ou nécessitant peu de code, faciles à implémenter et suffisamment puissantes pour s'adapter parfaitement à vos besoins.</p></td>
            <td><img src="Users/clement/Desktop/HTML/Mon site/Websites/Site web template/App React/1_9PB6ooej_LyIEFHOe8dMbg.gif"></td> 
        </tr>
    </table>
<br>
<br>
    <table>
        <tr>
            <td><img src="Users/clement/Desktop/HTML/Mon site/Websites/Site web template/App React/1_l07nC0xwRXzmIZFsKpbxyQ.gif"></td>
            <td><h3>Vous disposez de tout, à portée de main</h3>
            <br>
            <p>Nous designons votre site web et plus largement vos interfaces, de façon à ce que vous viviez une expérience unique lors de votre navigation.
            Accessibilité, cohérence, clarté, hiérarchie des informations, simplicité et respect des normes sont les maîtres mots de nos produits.</p></td>
        </tr>
    </table>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<div id="services"></div>
<table>
    <tr>
        <td>
            <span>Parce que c'est un métier,<br>et que nous le maîtrisons</span>
        </td>
    </tr>
</table>
</div>
<br>
<br>
<br>
<br>
<br>
<br>
<table>
        <tr>
            <td>
                <br>
                <div class="audit">
                <h3>Nous auditons votre solution actuelle</h3>
            <br>
            <p>La fonction d'auditeur est centrale dans notre activité. C'est la première étape de la mission que vous nous confiez. Nous sommes
            chargés d'examiner et d'évaluer les processus, les opérations, les systèmes et les finances de votre organisation, en ce qui concerne
            les outils digitaux, pour s'assurer qu'ils sont conformes aux normes établies, aux réglementations en vigueur et aux meilleures pratiques.
        </p></td></div>
            <td>
            <br>
            <div class="referencement">
            <h3>Nous vous référençons pour être trouvé facilement</h3>
            <br>
            <p>En mettant en œuvre les bonnes stratégies d'optimisation SEO, vous pouvez améliorer la visibilité, la pertinence et la crédibilité de votre
            site web aux yeux des moteurs de recherche, ce qui peut entraîner une augmentation du trafic organique et de la conversion. Vous gagnez ainsi
            des prospects.</p>
            </div>
            <br>
            </td>
        </tr>
</table>
<br>
    <table>
        <tr>
            <td>
                <br>
                <br>
                <br>
                <br>
                <div class="marketing">
                <h3>Nous vous conseillons autour des stratégies de marketing</h3>
                <br>
                <p>Analyse de votre marché, veille concurrentielle, stratégie de prix, marketing de contenu, relations publiques, développement 
                de marque, stratégie de communication... Les possibilités de vous réinventer sont nombreuses et nous vous aidons grâce à notre expertise.
                Vous pouvez par exemple collaborer avec des influenceurs, organiser des événements, investir dans la publicité, définir à nouveau 
                votre public cible, créer une identité de marque forte, changer de site web pour plus de convivialité, utiliser les réseaux sociaux.
                Ce ne sont que quelques exemples, dont nous détenons les clés. </p>
                </div>
            </td> 
            <td>
                <div class="allie">
                    <h3>L'allié le plus puissant au monde</h3>
                    <br>
                    <p>La création d'un site web est un processus complexe qui implique plusieurs étapes, de la planification initiale à la mise en ligne du
                        site. Nous nous occupons de tout, de la définition de vos objectifs jusqu'à la livraison, grâce à la meilleure technologie de développement web au monde.</p>
                    </div>
                    <br>
                    <br>
            </td>
        </tr> 
    </table>
    <table>
        <tr>
            <td>
                <div class="interface">
                    <h3>Nous créons des intéractions simples et originales</h3>
                    <br>
                    <p>Nous designons votre site web et plus largement vos interfaces, de façon à ce que vous viviez une expérience unique lors de 
                    votre navigation. Avec notre palette numérique, nous transformons les concepts en réalité visuelle en harmonisant les couleurs, 
                    les images, les typographies et les animations, de façon à simplifier chacune de vos intéractions. Chaque projet est un espace 
                    où notre créativité prend son envol. </p>
                </div>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
            </td>
            <td>
                <br> 
                    <br> 
                    <br> 
                    <br> 
                <div class="site">  
                    <h3>Nous créons votre nouveau site web</h3>
                <br>
                <p>La création d'un site web est un processus complexe qui implique plusieurs étapes, de la planification initiale à la mise 
                    en ligne du site. Nous nous occupons de tout, de la définition de vos objectifs jusqu'à la livraison.Commençons par lister 
                    vos objectifs liés à cette création, puis étudions votre marché et votre concurrence, définissons l'architecture du site web, 
                    concevons-le graphiquement, mettons-le en production, ajoutons le contenu et testons le bon fonctionnement du site web. </p></div>
                    <br>
                    <br>
                    <br>
                    <br>
                    <br>
                    <br>
                    <br>
                    <br>
                    <br>
            </td>
        </tr>
    </table>
    <table>
        <tr>
            <td>
                <span>Nos projets</span>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                <br>
                <video width="960" height="540" controls poster="Users/clement/Desktop/HOME/Capture d’écran 2024-03-15 à 14.35.21.png">
                <source src="https://github.com/nectar-concept/nectar-concept.github.io/blob/main/Design%20sans%20titre.mp4" type=video/mp4>
            </td>
                    <td>
                        <br>
                        <br>
                        <br>
                        <br>
                        <br>
                        <br>
                        <br>
                        <br>
                        <br>
                        <br>
                        <br>
                        <br>
                    <video width="960" height="540" controls poster="Users/clement/Desktop/HOME/Capture d’écran 2024-03-15 à 14.34.10.png">
                    <source src="https://github.com/nectar-concept/nectar-concept.github.io/blob/main/zenly.mp4" type=video/mp4>
                </td>
            </div>
        </tr>
    </table>
    <table>
        <tr>
            <td>
                <video width="960" height="540" controls poster="Users/clement/Desktop/HOME/Capture d’écran 2024-03-15 à 14.33.00.png">
                <source src="https://github.com/nectar-concept/nectar-concept.github.io/blob/main/Landscapes.mp4" type=video/mp4>
            </td>
            <td>
                <video width="960" height="540" controls poster="/Users/clement/Desktop/HOME/Capture d’écran 2024-03-15 à 14.32.35.png">
                <source src="https://github.com/nectar-concept/nectar-concept.github.io/blob/main/oriental.mp4" type=video/mp4>
            </td>
            </div>
        </tr>
    </table>
    <br>
    <br>
    <br>
    <br>
    <table>
        <tr>
            <td>
        </td>
            <td></td>
        </tr>
    </table>
<div id="solutions"></div>       
    <table>
        <tr>
            <td><span>Découvrez nos solutions</span></td>
            <td></td>
        </tr>
    </table>
</div>
<br>
<br>
<table>
        <tr>
            <td><h3>Startups, indépendants & TPE</h3>
            <br>
            <p>Avec l'aide de Nectar, des start-up  et TPE ambitieuses parties de rien ont atteint leur pic de croissance. 
            Constituez votre entreprise, testez et acceptez les designs avec nos services et concentrez-vous sur votre coeur 
            de métier pour accélérer votre croissance.
            <br>
            <br>
            Générez plus de leads, plus vite
            Créez une expérience unique lorsque vos visiteurs visitent votre site web et/ou votre application mobile. Pas besoin d'y 
            consacrer 1000 heures, une journée peut suffire.
            <br>
            <br>
            <br>
            <td><h3>PME</h3>
                <br>
                <p>Une plateforme digitale complète pour les PME
                <br>
                <br>
                Nectar réunit tous les outils digitaux nécessaires pour vous permettre d'être plus visible auprès de votre clientèle cible. 
                Tirez profit de nos solutions pour optimiser les conversions.
                <br>
                <br>
                Avec l'aide de Nectar, des start-up ambitieuses parties de rien ont atteint leur pic de croissance. Constituez votre entreprise, 
                testez et acceptez les designs avec des solutions sans code, et concentrez-vous sur votre coeur de métier pour accélérer 
                votre croissance.</td>
        </tr>
    </table>
    <table>
        <tr>
            <td><img src="Users/clement/Desktop/HTML/Mon site/Websites/Site web template/App React/Design sans titre.png"></td>
            <br>
            <td><img src="Users/clement/Desktop/HTML/Mon site/Websites/Site web template/App React/Design sans titre1.png"></td>
        </tr>
    </table>
<br>
<br>
<br>
<table>
    <tr>
        <td><span>Nos forfaits</span></td>
        <td></td>
    </tr>
</table>
</div>
<br>
<br>
<br>
<br>
<table>
    <tr>
        <td>
        <div class="starter"><span>Starter</span>
        <br>
        <br>
        <h5>Débutez en toute légereté</h5>
        <br>
        <h5>Forfait de 10 heures</h5>
        <br>
        <h6>600€ HT/mois</h6>
        <br>
        <br>
        <h5><strong>Inclus dans le pack :</strong></h5>
        <br>
        <ul>
        <li>Identité visuelle (logo, charte graphique)</li>
        <br>
        <li>Maquette de produit</li>
        <br>
        <li>Web design sans codage</li>
        <br>
        <li>Animation de logo - typographie - objets</li></div>
        </ul>
        </td>
        <br>
        <br>
        <br>
        <br>
        <td>
        <div class="flex"><span>Flex</span>
        <br>
        <br>
        <h5>Besoin de plus de souplesse ?</h5>
        <br>
        <h5>Forfait illimité</h5>
        <br>
        <h6>900€ HT/mois</h6>
        <br>
        <br>
        <h5><strong>Inclus dans le pack :</strong></h5>
        <br>
        <ul>
        <li>Elements de l'offre "starter" et :</li>
        <br>
        <li>Web design avec codage</li>
        <br>
        <li>Optimisation de l'expérience utilisateur (UI design)</li>
        <br>
        <li>Vidéo de témoignage ou publicitaire</li></div>
        </ul>
        </td>
    </tr>
</table>
<br>
<table>
    <tr>
        <td>
        <div class="full"><span>Full</span>
        <br>
        <br>
        <h5>Une offre complète pour plus de tranquilité</h5>
        <br>
        <h5>Forfait illimité</h5>
        <br>
        <h6>1500€ HT/mois</h6>
        <br> 
        <br>
        <h5><strong>Inclus dans le pack :</strong></h5>
        <br>
        <ul>
            <li> Elements de l'offre "Flex" et :</li>
            <br>
            <li> Maintenance hebdomadaire du site web</li>
            <br>
            <li> Contenu pour posts sur les réseaux sociaux</li>
            <br>
            <li> Illustration, retravail d'image</li>
        </ul>
        </td>
        <td>
        <div class="adefinir"><span>A définir</span>
        <br>
        <br>
        <h5>Une prestation horaire sur devis</h5>
        <br>
        <h5>8 heures maximum</h5>
        <br>
        <h6>60€ HT/heure</h6>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br></div>
        </td>
    </tr>
</table>
<br>
<b>
<div id="contact"></div>
    <iframe src="https://github.com/nectar-concept/nectar-concept.github.io/blob/main/Footer.html" title="footer"; width="1440"; height="470"; class="footer"; loading="lazy"></iframe>
</div>
    <script src="Users/clement/Desktop/HTML/Mon site/Websites/Site web template/App React/APP/script.js"></script>
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>

</body>
</html>
