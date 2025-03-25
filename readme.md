# 📋 **Exercice : Formulaire d'inscription en HTML**

Ce projet consiste en la création d'un **formulaire d'inscription** entièrement en **HTML**, sans CSS ni JavaScript externe. Le formulaire permet aux utilisateurs de s'inscrire en fournissant plusieurs informations personnelles et professionnelles. Il utilise principalement des balises HTML modernes et des attributs de validation pour garantir une expérience utilisateur fluide.

---

## ✨ **Description**

Le formulaire comprend les champs suivants :

1. **Prénom** : Un champ de texte pour le prénom de l'utilisateur.
2. **Nom** : Un champ de texte pour le nom de l'utilisateur.
3. **Âge** : Un champ numérique avec une validation permettant de saisir l'âge (entre 1 et 120 ans).
4. **Sexe** : Un groupe de boutons radio permettant de choisir entre Homme, Femme ou Autre.
5. **Adresse mail** : Un champ de type email pour saisir l'adresse e-mail.
6. **Adresse postale** : Un champ de texte pour saisir l'adresse postale de l'utilisateur.
7. **Code postal** : Un champ de texte avec une validation de format pour le code postal (5 chiffres).
8. **Ville** : Un champ de texte pour saisir la ville de l'utilisateur.
9. **Métier exercé** : Un menu déroulant permettant de sélectionner un métier parmi plusieurs options.
10. **Nationalité** : Un menu déroulant pour choisir la nationalité.
11. **Date de naissance** : Un champ de type date pour saisir la date de naissance.
12. **Pays de naissance** : Un champ de texte pour saisir le pays de naissance.
13. **Numéro de sécurité sociale** : Un champ de texte avec validation pour le numéro de sécurité sociale (15 chiffres).
14. **Numéro de passeport** : Un champ de texte avec validation pour le numéro de passeport (9 caractères alphanumériques).
15. **Date de délivrance du passeport** : Un champ de type date pour saisir la date de délivrance du passeport.
16. **Date de validité du passeport** : Un champ de type date pour saisir la date de validité du passeport.

Chaque champ est accompagné d'un **label** pour améliorer l'accessibilité, et plusieurs champs sont rendus obligatoires à l'aide de l'attribut `required`.

---

## 💻 **Technologies utilisées**

- **HTML5** : Le formulaire est entièrement construit avec du HTML5.
- **Balises HTML5** :
  - Utilisation des champs `type="email"`, `type="number"`, `type="date"`, etc. pour une validation côté client optimale.
  - Attributs comme `required`, `min`, `max`, `pattern` pour garantir la saisie correcte des informations.
  - Les balises `label` et les attributs `for` sont utilisés pour garantir l'accessibilité du formulaire.

---

## 🛠️ **Fonctionnalités principales**

- **Validation des champs** : Grâce à des attributs HTML comme `required`, `min`, `max`, `pattern`, les données saisies par l'utilisateur sont validées directement dans le navigateur.
  
- **Accessibilité améliorée** : Chaque champ de saisie est correctement étiqueté à l'aide des balises `label`, ce qui permet une meilleure expérience pour les utilisateurs ayant recours à des technologies d'assistance.

- **Structure claire** : Le formulaire est conçu de manière logique, avec des champs bien organisés pour garantir une navigation fluide.

---

## 🚀 **Comment l'utiliser**

1. Clonez ce repository sur votre machine locale.
2. Ouvrez le fichier `index.html` dans votre navigateur.
3. Remplissez les champs et soumettez le formulaire (notez que l'action de soumission n'est pas encore implémentée — il faudra l'adapter pour traiter les données côté serveur).

---


