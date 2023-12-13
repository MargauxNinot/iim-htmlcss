# Étape 1 : Création des Fichiers HTML et CSS

1. Créer un fichier HTML : nommez-le `index.html`.
2. Créer un fichier CSS : nommez-le `styles.css`.

# Étape 2 : Structure de Base du Fichier HTML (index.html)

- Utiliser le raccourci ! pour générer le squelette de base du HTML.
- Définir le titre du document dans la balise <title>.

# Étape 3 : Importation du Fichier CSS

- Ajouter un lien vers le fichier CSS dans la balise <head> du HTML.

# Étape 4 : Création des Éléments de la Page

- Ajouter un élément <header> dans le <body>.
- À l'intérieur du <header>, ajouter une barre de navigation (<nav>)

- Ajouter un élément <main> après le <header> (son grand frère).
- Créer trois sections (<section>) à l'intérieur du <main>.

  Dans au moins une section, inclure une balise <article>.
  Dans au moins une section, inclure une balise <img> pour une image.
  Dans au moins une section, inclure une balise <a> pour un lien.

  Chaque section doit contenir au moins un titre (<h1> à <h6>) et un paragraphe (<p>).

- Ajouter un élément <footer> après le <main> (son grand frère).
- Inclure un texte de droit d'auteur.
- Ajouter trois icônes de réseaux sociaux en utilisant FontAwesome.

# Étape 5 : Stylisation avec CSS (styles.css)

1. Utilisation d'IDs et de Classes pour le Stylisme

Choisissez deux éléments (par exemple, une section spécifique ou le header) et attribuez-leur un ID unique. Appliquez des styles spécifiques à ces éléments en utilisant leurs IDs dans votre fichier CSS.
Utilisez des classes pour styliser les autres éléments. Par exemple, appliquez une classe commune aux sections ou aux éléments de la liste de navigation pour une stylisation cohérente.

2. Stylisation de la Barre de Navigation

Créez une liste non ordonnée (<ul>) pour les éléments de navigation.
Utilisez display: flex; pour afficher les éléments de la liste (<li>) en ligne.
Centre verticalement et horizontalement les éléments avec les flexbox.
Stylisez les liens de navigation directement sans classe ni ID, en utilisant le sélecteur d'élément a dans le CSS. Définissez leur couleur en bleu.

3. Stylisation des Sections dans le <main>
   Utilisez des classes pour appliquer des styles communs aux sections.
   Personnalisez l'apparence des titres, paragraphes, et autres éléments en utilisant des classes pour une meilleure cohérence et lisibilité.

4. Stylisation du <footer>
   Utilisez les flexbox pour aligner centralement et horizontalement les éléments, y compris les icônes de réseaux sociaux.
   Stylisez le footer en utilisant une classe ou un ID spécifique pour assurer un design distinct et harmonieux.

5. Cohérence et Finitions
   Assurez-vous que l'ensemble du site présente un style cohérent en termes de couleurs, de polices, et d'espacement.
   Testez la réactivité du site pour s'assurer qu'il s'affiche correctement sur différents appareils.

6. Vérification et Ajustements
   Ouvrez le site dans différents navigateurs pour tester sa compatibilité et son affichage.
   Effectuez des ajustements si nécessaire pour optimiser l'apparence et l'accessibilité.

# BONUS :

Rajouter un lien cliquable fixé en bas a gauche du site internet avec une icon de flèche vers le haut, au clique on doit pouvoir scroll tout en haut du site
