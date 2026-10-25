<h1 align="center">☕ Coffee Machine</h1>

<p align="center"><em>Espresso, latte ou cappuccino : une machine à café qui gère ses stocks et sa caisse.</em></p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python 3" />
  <img src="https://img.shields.io/badge/d%C3%A9pendances-aucune-success?style=for-the-badge" alt="Aucune dépendance" />
  <img src="https://img.shields.io/badge/projet%20d%27apprentissage-ff69b4?style=for-the-badge" alt="Projet d'apprentissage" />
</p>

---

## ✨ Pourquoi tu vas l'adorer

- **Une vraie classe** `CoffeeMachine` : la machine garde en mémoire ses stocks et sa caisse entre deux actions.
- **Contrôle des stocks** avant chaque boisson : pas assez de lait ? Elle refuse et te le dit.
- **Un menu** qui tourne en boucle jusqu'à `exit`.

## 📋 La carte

| Boisson | 💧 Eau | 🥛 Lait | ☕ Café | 💰 Prix |
|---|---:|---:|---:|---:|
| Espresso | 250 ml | — | 16 g | $4 |
| Latte | 350 ml | 75 ml | 20 g | $7 |
| Cappuccino | 200 ml | 100 ml | 12 g | $6 |

Stock de départ : 400 ml d'eau, 540 ml de lait, 120 g de café, 9 gobelets et $550 en caisse.

## 🎮 Actions

| Action | Effet |
|---|---|
| `buy` | Commande une boisson : `1` espresso, `2` latte, `3` cappuccino, `back` pour revenir |
| `fill` | Recharge eau, lait, café et gobelets |
| `take` | Vide la caisse |
| `remaining` | Affiche l'état des stocks |
| `exit` | Éteint la machine |

## 🚀 Lancer

```bash
python3 Python_Code
```

## 🕹️ Exemple

```text
Write action (buy, fill, take, remaining, exit):
remaining

The coffee machine has:
400 of water
540 of milk
120 of coffee beans
9 of disposable cups
$550 of money
```

## 🧠 Sous le capot

- Les stocks et la caisse sont des **attributs** (`self.ml_water`, `self.num_money`…) : c'est l'état de l'objet.
- `check_if_enough()` centralise la vérification des stocks avant chaque préparation.
- `automate()` fait tourner la boucle du menu.

## 🔭 Pistes d'évolution

- Ranger les recettes dans un dictionnaire pour ne plus répéter le même bloc de code pour chaque boisson.
- Prévenir quand un stock passe sous un seuil.

---

<p align="center"><sub>Fait avec ❤️ et Python par DSKarim</sub></p>
