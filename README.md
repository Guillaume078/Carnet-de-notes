# Carnet-de-notes
Une petite app pour enregistrer des notes personnelles (texte court), avec possibilité d’ajouter, modifier et supprimer.
Très bonne idée 👍 ! Pour bien **maîtriser Flutter**, il te faut une app :

* **pas trop complexe** au début
* mais qui utilise les **principaux concepts Flutter** :

  * widgets (`Stateless`, `Stateful`)
  * navigation
  * gestion d'état (`setState`)
  * formulaires
  * stockage local
  * un peu de design

---

## 💡 Idée d'application : **"Mon Carnet de Notes"**

> Une petite app pour enregistrer des notes personnelles (texte court), avec possibilité d’ajouter, modifier et supprimer.

---

### 🎯 Fonctionnalités à créer :

✅ **Accueil**

* Affiche la liste des notes enregistrées (titre + aperçu)

✅ **Ajout de note**

* Formulaire simple (titre + contenu)
* Bouton « Enregistrer »

✅ **Modification**

* Taper une note → ouvre le formulaire avec les données existantes
* Modifier et sauvegarder

✅ **Suppression**

* Swipe pour supprimer ou bouton «🗑️»

✅ **Stockage local**

* Utilise `shared_preferences` ou `sqflite` (base de données SQLite)

---

### 🔧 Concepts Flutter que tu vas pratiquer :

| Compétence                        | Apprise dans ce projet ✅            |
| --------------------------------- | ----------------------------------- |
| Widgets `Stateful` et `Stateless` | ✔️ Interface dynamique              |
| `setState()`                      | ✔️ Mise à jour de l’interface       |
| ListView                          | ✔️ Affichage d’une liste de données |
| Formulaire + validation           | ✔️ Gestion de formulaire            |
| Navigation (`Navigator.push`)     | ✔️ Passer d’un écran à un autre     |
| Stockage local                    | ✔️ Sauvegarder les notes            |
| Design (Padding, Icons, etc.)     | ✔️ Layouts et UI                    |

---

### 🎁 Bonus possible :

* Ajout d’un système de **tags** ou **catégories**
* Filtrage par mot-clé
* Changement de thème (mode nuit)
* Export PDF ou partage de notes

---

Si tu veux, je peux te générer le **squelette du code de départ** (ex : page d'accueil avec un bouton pour ajouter une note). Tu veux ?
