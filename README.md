# css-code
/* Reset default browser styles */
body, h1, h2, h3, h4, h5, h6, p, ul, li {
    margin: 0;
    padding: 0;
}

/* Global styles */
body {
    
    background-attachment: fixed;
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
}

header {
    text-align: center;
    background-color: #f2f2f2;
    padding: 20px;
}

h1 {
    text-align: center;
    font-size: 36px;
    margin-bottom: 10px;
}

nav ul {
    list-style: none;
}

nav li {
    display: inline-block;
    margin-right: 20px;
}

nav li:last-child {
    margin-right: 0;
}

nav a {
    text-decoration: none;
    color: #333;
    font-size: 18px;
}

nav a:hover {
    color: #007bff; /* Change to your preferred link hover color */
}

main {
    text-align: center;
    padding: 20px;
}

#about, #experience, #projects, #contact {
    text-align: center;
    margin-bottom: 30px;
}

#about h1, #experience h2, #projects h6, #contact h7 {
    font-size: 26px;
    margin-bottom: 10px;
}
/* Styles for the "About" section */
#about {
    display: flex;
    align-items: center; /* Align items vertically in the flex container */
}

#about img {
    flex: 1; /* Let the image take up available space */
    max-width: 300px; /* Adjust the width as per your image size */
    margin-right: 20px; /* Add some spacing between the image and the paragraph */
}

#about p {
    flex: 2; /* Let the paragraph take up twice the space of the image */
}


#experience ul {
    display: flex;
    flex-direction: column;
    align-items: center;
    list-style: none;
    padding: 0;
}

#experience li {
    margin-bottom: 20px;
}

#experience h3, #experience h4, #experience h5 {
    font-size: 18px;

    margin-bottom: 5px;
}

#projects .projects-image img {
   
    max-width: 20%;
    margin-bottom: 10px;
}

section#contact p1, section#contact p2, section#contact p3 {
    margin-bottom: 5px;
}

footer {
    background-color: #f2f2f2;
    padding: 10px;
    text-align: center;
}

/* Media query for responsive design */
@media screen and (max-width: 600px) {
    header {
        text-align: center;
    }

    nav {
        display: block;
        text-align: center;
        margin-top: 10px;
    }

    nav li {
        display: block;
        margin-bottom: 10px;
    }
}
/* Styles to move the navigation to the top of the page */
header {
    display: flex;
    align-items: center;
    justify-content: space-between; /* Space the elements evenly across the header */
    padding: 20px; /* Add some padding to the header for spacing */
}

nav {
    display: flex;
    align-items: center;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
}

nav li {
    margin-right: 20px;
}

nav li:last-child {
    margin-right: 0;
}
/* Styles to move the navigation to the top of the page */
header {
    display: flex;
    align-items: center;
    justify-content: space-between; /* Space the elements evenly across the header */
    padding: 10px 20px; /* Add some padding to the header for spacing (adjust as needed) */
    margin-top: 10px; /* Add margin to push the header closer to the top */
}

nav {
    display: flex;
    align-items: center;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
}

nav li {
    margin-right: 20px;
}

nav li:last-child {
    margin-right: 0;
}
/* Styles for the header */
header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 10px 20px;
    margin-top: 10px;
    background-image: url("C:\Users\Asus\OneDrive\Desktop\mon site\photoportfolio\farou1 logo.png"); 
    background-repeat: no-repeat;
    background-size: contain; /* pour ajustez la taille de l'image pour qu'elle s'adapte correctement */
    background-position: left center; /* pour ajustez la position de l'image par rapport au header */
}
/* Styles for h3, h4, and h5 to display inline-block with space between them */
h3, h4, h5 {
    display: inline-block;
    margin-right: 10px; /* pour ajoutez un petit espace entre les titres */
}
/* Styles for the "Experience and Education" section */
#experience {
    text-align: center; /* Pour centrer le contenu de la section */
}

#experience h3, #experience h4, #experience h5,
#experience p1, #experience p2, #experience p3 {
    display: block;
    margin-bottom: 10px; /* pour ajouter une marge entre les éléments */
}
/* Styles for the "Header" section */

/* Styles for the "About" section */
#about {
    background-image: url("C:\Users\Asus\OneDrive\Desktop\mon site\photoportfolio\background1.jpg");
    background-size: cover;
    background-size: contain;
    height: 100vh;
    
}

/* Styles for the "Experience and Education" section */
#experience {
    background-image: url("C:\Users\Asus\OneDrive\Desktop\mon site\photoportfolio\background1.jpg");
    background-size: cover;
    height: 100vh;
    
}

/* Styles for the "Projects" section */
#projects {
    background-image: url("C:\Users\Asus\OneDrive\Desktop\mon site\photoportfolio\background1.jpg");
    background-size: cover;
    height: 100vh;
    
}

/* Styles for the "Contact" section */

#contact {
    background-image: url("C:\Users\Asus\OneDrive\Desktop\mon site\photoportfolio\background1.jpg");
    background-size: cover;
    height: 100vh; /* Hauteur de 100% de la hauteur de la fenêtre */
   
}
