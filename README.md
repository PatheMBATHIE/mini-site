**Description des Pages :**
*Accueil (index.html) :* Présentation globale avec une photo de profil intégrée dans un cadre arrondi soigné, accompagnée du texte de présentation textuelle mettant en valeur mon profil académique.

*Mes Projets (projets.html) :* Grille dynamique exposant mes projets clés tels que BuC-Space (Système de gestion de bibliothèque sous Streamlit/Python), Projet d'initiation, Wiiri et SIMPA (), ainsi que mes thématiques de veille technologique.

*Mon CV (cv.html) :* Synthèse de mon parcours académique (Licence Informatique), de mes compétences techniques (SQL, C, Html, Css, JS etc.) et de mes activités de créateur de contenu de vulgarisation technologique.

*Contact (contact.html) :* Formulaire d'envoi de message ergonomique couplé à un bloc de coordonnées professionnelles (Email, LinkedIn, GitHub, Tech Autour).

**Choix de Design & Identité Visuelle**
L'ensemble de l'interface a été pensé pour refléter l'univers du Data Engineering et de la Tech, tout en restant sobre, institutionnel et hautement accessible.

1. **Palette de Couleurs (Variables CSS :root)**
La gestion des couleurs est centralisée de manière professionnelle à l'aide des variables CSS suivantes intégrées dans le projet :
:root {
    --color-text : black;            /* Couleur du texte principal pour un contraste maximal */
    --color-du_fond: rgba(0, 0, 0, 0.05); /* Fond de page doux et épuré (gris très léger) */
    --color-ombre: rgba(0, 0, 0, 0.616);  /* Couleur des ombres pour marquer l'élévation des éléments */
    --color-accent: #0056B3;         /* Bleu roi technologique pour les titres, boutons et liens actifs */
    --color-du_site: white;          /* Blanc pur utilisé pour détacher les blocs de contenu */
}
*Application (Règle des 60-30-10)* : Le fond du site (--color-du_fond) occupe la majorité de l'espace visuel, les blocs de texte et structures exploitent le contraste net du noir (--color-text) sur blanc (--color-du_site), tandis que la couleur d'accent (--color-accent) dynamise les points d'interaction importants.
2. Typographie & Lissage
Corps & Navigation : Utilisation d'une pile de polices système moderne et géométrique (-apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif). Elle assure un affichage net, pro et instantané sans dépendance stricte à des serveurs tiers.

**Spécifications Techniques**
*HTML5 sémantique :* Utilisation rigoureuse des balises structurantes (<header>, <nav>, <main>, <section>, <article>, <footer>) pour un meilleur référencement et une structure de code exemplaire.

*CSS Extensible :* Recours aux variables CSS (:root) pour centraliser la palette de couleurs et la typographie, facilitant toute maintenance ou évolution future du design.

*Zéro JavaScript :* L'ensemble des animations, mises en page réactives et comportements interactifs (survol, focus formulaire) est géré exclusivement en CSS pur, garantissant des performances optimales.

*Développé avec rigueur dans le cadre du projet de développement de Mini-Site Personnel.*

