# TY Toitures — ty toitures

Site vitrine statique (HTML / CSS / JS, sans build) hébergé sur GitHub Pages,
domaine `tytoitures.shop`.

> Généré depuis `C:\Users\souha\coaching-sites-factory` (fichier `sites/tytoitures.mjs`).
> Pour une modification de contenu, éditez ce fichier puis relancez `node build.mjs tytoitures` :
> une modification faite directement ici serait écrasée à la prochaine génération.

## À compléter avant de communiquer sur le site

| Priorité | Quoi | Où |
|---|---|---|
| 🔴 Bloquant | Mentions légales : identité de l’éditeur, SIREN, adresse, médiateur. Obligatoire en France. | `mentions-legales.html` |
| 🟠 Important | Adresse `contact@tytoitures.shop` : créer une redirection e-mail chez Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Formulaire : remplacer `VOTRE_ID_FORMSPREE` (sinon repli automatique en `mailto:`). | `contact.html` |
| 🟠 Important | Présentation de la personne qui coache (nom, parcours réel, photo). | `a-propos.html` |
| 🟡 Plus tard | Tarifs (Sur devis / Sur devis / Sur devis €) et contenu des formules à ajuster à votre offre réelle. | `index.html` `#tarifs` |
| 🟡 Plus tard | Témoignages : n’en ajoutez que des vrais, avec l’accord des personnes. | — |

## Description de l’activité (Stripe, annuaires…)

```
TY Toitures, société de droit belge inscrite à la Banque-Carrefour des Entreprises sous le numéro 1031.232.635, est une entreprise de couverture établie à Liège : pose et rénovation de toitures en tuiles, ardoises et bardeaux, isolation de toiture par l’intérieur ou par l’extérieur, étanchéité des toitures plates et des murs enterrés, et repérage de l’amiante avant tout démontage d’une couverture ancienne. Chaque chantier fait l’objet d’un devis écrit mentionnant ce qui n’est pas compris. Le désamiantage est confié à une entreprise agréée. Site : tytoitures.shop
```

## Structure

```
index.html            Accueil : hero, programmes, méthode, tarifs, approche, FAQ
programmes.html       Détail des 4 programmes
a-propos.html         Notre approche et principes
contact.html          Formulaire de prise de contact
mentions-legales.html Mentions légales, confidentialité, CGV
404.html              Page d’erreur (chemins absolus)
assets/css/style.css  Couleurs de la marque en tête de fichier, puis styles communs
assets/js/main.js     Menu, thème, animations, formulaire
```

## DNS (Namecheap → Advanced DNS)

Supprimer les enregistrements de parking, puis :

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
