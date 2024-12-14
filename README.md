# 🎉 Bienvenue au deuxième atelier découverte du Développement Web! 🎉

Dans cet atelier, vous allez intégrer une **maquette simple** en **HTML** et **CSS**. Vous allez apprendre à utiliser **Flexbox** pour disposer les éléments de votre page de manière fluide et responsive. 🚀

## 📋 Objectif de l'exercice

En 1 heure, vous allez créer une page web en intégrant une maquette fournie en utilisant les concepts de **Flexbox**. L'objectif est d'apprendre à structurer et styliser une page en HTML/CSS de manière moderne.

La maquette est à intégrer seulement en version desktop, mais pour les plus avancés, vous pouvez tenter de rendre la maquette **responsive** afin qu'elle soit bien affichée sur toutes les tailles d'écrans ! 📱💻

## 📂 Contenu du dossier

Votre dossier d'exercice contient les éléments suivants :

- **index.html** : Votre fichier HTML où vous allez écrire votre code.
- **styles.css** : Votre fichier CSS où vous allez styliser votre page.
- **assets/** : Dossier contenant des ressources graphiques (images, icônes, etc.). **Un asset** est un fichier multimédia qui est utilisé dans votre page web pour l'enrichir visuellement.

## 🎨 Les Couleurs à Utiliser

- **Couleur Primaire** : `#83EB83`
- **Couleur Secondaire** : `#217565`

Ce sont ce que l'on appelle des code Hexadécimal, mais le nom importe peu, il suffit de remplacer `blue` ou `red` par le code, à côté de propriétés CSS qui influence la couleur tel que background-color (couleur d'arrière-plan), ou color (couleur d'un texte).

## ✍️ Les Polices d'Écriture

Voici les polices que vous allez utiliser dans votre maquette. Vous devrez les importer depuis Google Fonts.

### 1. **Font Title :** "Lobster"

- **Lien** : [Lobster sur Google Fonts](https://fonts.google.com/specimen/Lobster?preview.text=La%20Pomme&preview.text_type=custom)
- **Importation** :
    ```css
    @import url('https://fonts.googleapis.com/css2?family=Lobster&display=swap');
    ```
- **Utilisation dans votre CSS** :
    ```css
    font-family: 'Lobster', cursive;
    ```

### 2. **Font Article & Footer :** "Lobster Two"

- **Lien** : [Lobster Two sur Google Fonts](https://fonts.google.com/specimen/Lobster+Two?preview.text=contact@lapomme.com&preview.text_type=custom&query=lobster)
- **Importation** :
    ```css
    @import url('https://fonts.googleapis.com/css2?family=Lobster+Two&display=swap');
    ```
- **Utilisation dans votre CSS** :
    ```css
    font-family: 'Lobster Two', cursive;
    ```

## 🌈 Instructions de Mise en Page avec Flexbox

Voici quelques propriétés **Flexbox** que vous allez utiliser pour aligner et disposer vos éléments :

- **`display: flex;`** : Active le mode Flexbox sur un conteneur.
- **`justify-content`** : Aligne les éléments horizontalement.
  - `start` : Aligne les éléments au début du conteneur.
  - `center` : Centre les éléments horizontalement dans un conteneur.
  - `end` : Aligne les éléments à la fin du conteneur.
  - `space-between` : Espace entre les éléments.
- **`align-content`** : Aligne les éléments verticalement.
  - `center` : Centre les éléments verticalement.
  - ainsi que les mêmes attributs que justify-content.

N'hésitez pas à consulter la documentation officielle (c'est ce qu'un vrai développeur fait !) pour comprendre un peu mieux comment celà fonctionne :
* [Flexbox](https://developer.mozilla.org/fr/docs/Learn/CSS/CSS_layout/Flexbox)
* [Justify-content](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)
* [Align-content](https://developer.mozilla.org/en-US/docs/Web/CSS/align-content)

### Exemple d'utilisation :

```css
.container {
    display: flex;
    justify-content: center; /* Centre les éléments horizontalement */
    align-content: center; /* Centre les éléments verticalement */
}
```

### 💡 Tips pour Aller Plus Loin
* Essayez d'utiliser **Flexbox** pour faire une mise en page fluide qui s'adapte à toutes les tailles d'écrans.
* Explorez d'autres propriétés Flexbox comme flex-direction, flex-wrap, justify-items et align-items !

### 🚀 À vous de jouer !
N'hésitez pas à poser des questions et à demander de l'aide si vous êtes bloqué(e) ! 😊
# dw
