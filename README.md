# 🏚️ La Maison Hantée — Le Manoir Grimm

> Un jeu de l'oie version manoir hanté, **sinistre à première vue, adorable à la seconde**.
> Un seul fichier HTML, 100 % autonome, jouable hors ligne. Fuyez avant l'aube !

![Aperçu du jeu](capture-3-plateau.png)

---

## 🕯️ Le concept

Inspiré du classique **Jeu de l'Oie**, *La Maison Hantée* vous plonge dans le Manoir Grimm :
63 pièces disposées en spirale, des esprits farceurs, des pièces piégées et un seul objectif —
atteindre **pile** la pièce 63 (la SORTIE) pour vous échapper avant que l'aube ne se lève.
Dépassez la case 63 ? Vous **rebondissez en arrière**… le manoir ne lâche pas ses visiteurs si facilement.

![Vestibule](capture-1-vestibule.png)

## ✨ Fonctionnalités

- 🎭 **2 à 6 joueurs** — chacun choisit sa créature : 👻 Fantôme, 🧛 Vampire, 🎃 Citrouille,
  💀 Squelette, 🧟 Zombie ou 🐈‍⬛ Chat noir
- 🌀 **Manoir généré aléatoirement** à chaque partie : les pièges ne sont jamais deux fois au même endroit
- 🎲 **1 ou 2 dés** au choix, déplacement animé case par case
- 🃏 **Cartes Chance** (le spiritisme parle !) et **Cartes Sortilège** en main (max 3, jouables avant les dés)
- ⚖️ **11 actions** aux poids réglables, pour doser les forces obscures :

  | Action | Effet |
  |---|---|
  | 👻 Frisson d'Adrénaline | Relance les dés immédiatement |
  | 💨 La Peur au Ventre | Avance du montant du dernier lancer |
  | 🪵 Parquet Pourri | Recule de 2 pièces |
  | 🔀 Corps Poltergeist | Échange votre place avec le joueur devant |
  | ⚖️ Le Bal des Fantômes | Le premier recule, le dernier avance |
  | 🕯️ Bougie Magique | Tire une Carte Chance |
  | 🚪 Passage Secret | Avance de 6 pièces |
  | 🕸️ Coincé sous les Draps | Passe un tour |
  | 🌀 Couloir Sans Fin | Recule de 4 pièces |
  | 🌬️ Courant Spectral | Avance de 3 pièces |
  | ☠️ Le Faucheur | Recule de 8 pièces |

- 📜 **Journal narratif** : chaque événement de la nuit est raconté
- 🎨 Ambiance **cartoon gothique** (Corpse Bride × Little Nightmares) : brouillard animé,
  lune, toile d'araignée, bougie vacillante, fenêtres orange qui luent…

## 🎮 Comment jouer

1. **Le Vestibule** : choisissez le nombre d'aventuriers, leur créature et leur nom.
2. Réglez les forces obscures : % de pièces piégées, % de cartes Sortilège par tour, 1 ou 2 dés.
3. **Lancez les dés** et avancez. Chaque pièce piégée déclenche son effet !
4. Jouez vos **Cartes Sortilège** avant de lancer les dés pour retourner la situation.
5. Le premier qui tombe **pile sur la pièce 63** s'échappe et gagne. 🌅

## 🚀 Lancer le jeu

Aucune installation, aucun serveur, aucun build :

```bash
git clone https://github.com/VOTRE-COMPTE/VOTRE-REPO.git
```

Puis ouvrez simplement **`maison-hantee.html`** dans votre navigateur (double-clic suffit).

## 📱 Compatibilité

- ✅ Desktop et mobile (responsive 360 px → 1440 px)
- ✅ Chrome, Firefox, Edge, Safari
- ✅ Fonctionne **hors ligne** (seules les polices Google Fonts et Tailwind sont chargées via CDN)
- 🔇 100 % silencieux : aucun son, aucune donnée collectée, aucune sauvegarde locale

## 🛠️ Technique

- **Un seul fichier** : HTML + CSS + JavaScript vanilla (ES6)
- Tailwind CSS (CDN) + Google Fonts (*Creepster* & *Nunito*)
- Illustration du manoir en **SVG inline** (aucune image externe)
- État du jeu en mémoire uniquement

## 📄 License

Projet libre — faites-en ce que vous voulez, à condition de fuir avant l'aube. 🌙
