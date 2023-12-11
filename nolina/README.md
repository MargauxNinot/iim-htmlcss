# Projet HTML/CSS : Organisation et Structuration

## Objectif :

Créer une page web bien structurée et organisée en utilisant HTML et CSS, intégrant divers éléments médias (images, fonts, SVG).

### Étape 1 : Préparation du Dossier de Projet

- À l'intérieur de ce dossier, créez trois sous-dossiers : images, fonts, svg et css.
- Placez toutes vos images dans le dossier images, vos polices de caractères dans fonts, vos fichiers SVG dans svg et vos fichiers CSS dans le css.

### Étape 2 : Création de la Structure de Base HTML

- Créez un fichier `index.html`, qui sera votre page principale.

- Définissez la structure de base de votre page HTML (doctype, head, body).

- Ajoutez des commentaires pour diviser votre page en sections (par exemple, en-tête, corps principal, pied de page).

### Étape 3 : Intégration des balies <header>, <main> et <footer>

1. Utilisez la balise <header> pour créer l'en-tête de votre page. Cela peut inclure votre logo, le titre de la page, et la navigation.

2. Employez la balise <main> pour le contenu principal de votre page. C'est ici que vous placerez la majorité de votre contenu textuel, images, et autres médias.

3. Utilisez la balise <footer> pour le pied de page de votre site. Incluez des informations telles que les droits d'auteur, les liens de contact, et les références.

Intégrez les polices de caractères depuis le dossier fonts à l'aide de CSS @font-face.
Ajoutez des éléments SVG depuis le dossier svg directement dans votre HTML.

### Étape 4 : Mise en Forme avec CSS

- Créez un fichier `style.css`.
- Liez le fichier CSS à votre HTML avec une balise <link>.
- Utilisez CSS pour styliser votre page, y compris la police, la couleur, la mise en page.

#### Instructions :

Pour ajouter différentes épaisseurs de police (comme **gras**, **regular**, **light**) en utilisant les polices Google dans votre fichier CSS, suivez ces étapes :

1. Choix de la police sur Google Fonts :

- Rendez-vous sur le site Google Fonts : https://fonts.google.com/
- Recherchez et sélectionnez la police de votre choix.
- Une fois la police sélectionnée, cliquez sur la famille de polices pour ouvrir le menu des styles disponibles.

2. Sélection des épaisseurs de police :

Dans le menu, vous verrez une liste d'épaisseurs de police disponibles (comme **300 pour light**, **400 pour regular**, **700 pour bold**, etc.).

Sélectionnez les épaisseurs que vous souhaitez utiliser sur votre site web en cliquant sur les cases correspondantes.
Intégration de la police dans votre CSS :

Après avoir sélectionné les styles, Google Fonts générera un lien à intégrer dans votre projet.

Copiez le lien fourni et collez-le dans la section <head> de votre fichier HTML, avant la référence à votre fichier CSS. Ce lien ressemblera à quelque chose comme <link href="https://fonts.googleapis.com/css2?family=Noto+Sans:wght@400;700&display=swap" rel="stylesheet">.

3. Utilisation des polices dans votre fichier CSS :

- Dans votre fichier style.css, utilisez la propriété `font-family` pour définir la police sur les éléments souhaités.

**Par exemple :**

```css
font-family: "Noto Sans", sans-serif;
```

Pour appliquer différentes épaisseurs, utilisez la propriété `font-weight`.

Par exemple, pour **regular** :

```css
font-weight: 400;
```

Par exemple, pour **bold** :

```css
font-weight: 700;
```

### Étape 5 : Créer Plusieurs Pages

1. Créer de Nouvelles Pages HTML

Faites des Nouvelles Pages : Créez de nouveaux fichiers HTML pour différentes parties de votre site.

Par exemple, créez un fichier `about.html` pour une page "À propos" et `contact.html` pour une page "Contact".

**Structure de Base :** Copiez la structure de base de votre `index.html` dans ces nouveaux fichiers. N'oubliez pas les parties comme <header>, <main>, et <footer>.

2. Ajouter des Liens de Navigation

**Mettez des Liens :** Dans chaque page, ajoutez des liens pour passer d'une page à l'autre. Utilisez la balise <a> pour cela. Par exemple : <a href="about.html">À propos</a>.

3. Utiliser un Fichier CSS Commun

**Fichier CSS pour Tous :** Utilisez un seul fichier CSS pour toutes vos pages. Nommez-le `common.css`.

Liez le CSS : Assurez-vous que chaque page HTML est liée à ce fichier CSS. Ajoutez cette ligne dans la partie <head> de chaque fichier HTML : <link rel="stylesheet" href="common.css">.

**Styles Partagés :** Mettez les styles pour des choses comme le haut (<header>) et le bas (<footer>) de la page dans `common.css`. Comme ça, chaque page aura le même look pour ces parties.

4. Fichiers CSS pour Styles Spécifiques (Optionnel)

**Styles Uniques :** Si vous voulez des styles uniques pour une page spécifique, vous pouvez créer un autre fichier CSS. Par exemple, `about.css` pour la page `about.html`.

Liez les Styles Uniques : Ajoutez le lien de ce fichier CSS dans la page HTML correspondante, après le lien pour `common.css`.
