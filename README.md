# Bizkor - Application de Recette & Gestion des Tests UAT 🚀

Application web interactive et autonome conçue pour la préparation, l'exécution et l'homologation des recettes utilisateurs (**UAT**) sur les projets Salesforce.

---

## 🔗 Accès direct à l'Application

* **Lien de l'application (GitHub Pages)** : [https://MichaelFrombizKor.github.io/UATAppManager/](https://<votre-compte-github>.github.io/<nom-du-repo>/)

* **Accès local immédiat** : Téléchargez le dépôt et ouvrez directement [`index.html`](./index.html) dans votre navigateur.

---

## 🎨 Charte Graphique Officielle Bizkor (Digital / RVB)

L'application applique scrupuleusement l'identité visuelle de **bizkor** :

### 1. Palette de Couleurs

| Rôle / Usage | Nom | Code HEX | Valeurs RVB | Valeurs CMJN |
| :--- | :--- | :--- | :--- | :--- |
| **Couleur principale** | **Bleu bizkor** | `#11BBF0` | 17, 187, 240 | C:69 M:0 J:0 N:0 |
| **Couleur complémentaire** | **Prune bizkor** | `#520D50` | 83, 13, 80 | C:60 M:100 J:0 N:50 |
| **Couleur additionnelle** | **Jaune bizkor** | `#FAE920` | 250, 233, 32 | C:6 M:0 J:88 N:0 |
| **Couleur de texte** *(au lieu du noir)* | **Bleu kimeia** | `#03224C` | 3, 34, 76 | C:100 M:88 J:42 N:42 |
| **Couleur de fond** *(au lieu du blanc)* | **Bright snow** | `#FBFAF8` | 251, 250, 248 | C:2 M:2 J:0 N:0 |

### 2. Typographie & Formes
* **Police de caractères** : [DM Sans](https://fonts.google.com/specimen/DM+Sans) (Google Fonts).
* **La Goutte Bizkor** : Forme géométrique signature (arrondie avec pointe marquée dans l'angle supérieur droit), déclinée sur les conteneurs, les boutons et les cartes d'indicateurs.
* **Ressources graphiques officielles** :
  * [Logo principal bizkor (Drive)](https://drive.google.com/file/d/1uWMJiD1k9TtSXvXPqBTTGkrRVW6MKw1c/view?usp=drive_link)
  * [Isotype Bizkor RVB (Drive)](https://drive.google.com/file/d/1EO7fnfcE8GDJTxVL_ffKoJVi0yA3Ja5U/view?usp=sharing)



## 🛠️ Fonctionnalités Principales

* **Zéro donnée par défaut** : Démarre sur un cahier de recette vierge prêt à la saisie.
* **En-tête de gouvernance UAT** : Nom du projet, Nom du client, Date de recette, Testeur et Environnement Salesforce (Sandbox / Staging).
* **Bloc d'Homologation & Signature Client** :
  * Émargement manuscrit interactif (tactile ou souris).
  * Date d'approbation et décision de recette (*Validé sans réserve / Go Live*, *Validé sous réserves*, *Refusé*).
* **Hiérarchie Agile** : Regroupement dynamique par **Epic** puis par **User Story**.
* **Tableau de bord & Filtrage instantané** :
  * Métriques KPI cliquables (Scénarios totaux, OK, KO, Bloqué, Non testé).
  * Barre de recherche plein texte en direct.
  * Menus déroulants filtrants par Epic, par User Story et par Statut.
* **Import & Export complets** :
  * Export **Excel (.xlsx)** et export **PDF** officiel (mise en page optimisée pour l'impression).
  * Import automatique de fichiers Excel / CSV avec détection automatique des colonnes.
  * Téléchargement d'un fichier **Modèle Excel** type.
* **Persistance locale** : Sauvegarde automatique en direct dans le navigateur (`localStorage`).
