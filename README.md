# LifeInvader Breach Terminal

Terminal de hack interactif inspiré de l'univers GTA V — LifeInvader.

4 mini-jeux de hacking enchaînés :
1. **Traceur GPS** — Mots déjà vus / nouveaux
2. **Neural Brute** — Mémorisation de grille
3. **Grid Scanner** — Séquence dans une grille
4. **Cypher Lock** — Cartes mélangées

## Installation

```bash
npm install
```

## Développement local

```bash
npm run dev
```

## Déploiement GitHub Pages

```bash
git init
git add .
git commit -m "initial commit"
git remote add origin https://github.com/TON_USERNAME/lifeinvader-terminal.git
git branch -M main
git push -u origin main
npm run deploy
```

Le site sera sur : `https://TON_USERNAME.github.io/lifeinvader-terminal/`

---

## Astuce

Il y a un petit bouton **SKIP ►** un peu caché en bas du logo LifeInvader (en haut à gauche). Il permet de passer directement au hack suivant si tu veux tester sans tout refaire.

## Mots de passe

Entre chaque hack, un écran de coordonnées GPS demande un mot de passe pour débloquer le hack suivant :

| Transition | Mot de passe |
|---|---|
| Hack 1 → Hack 2 | `781G8U53WV` |
| Hack 2 → Hack 3 | `691JHIL7EK` |
| Hack 3 → Hack 4 | `P31L33HM1J` |

Le hack 4 enchaîne directement sur le rapport de mission final, sans mot de passe.
