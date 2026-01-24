# ChestProtect

Protection des conteneurs (coffres, shulker, barrel, hopper) avec accès autorisé, GUI et gestion complète.

---

## Français

### 🛡️ Fonctionnalités
- Protection des conteneurs (chest, shulker box, barrel, hopper)
- Autorisation d’accès par joueur
- GUI de gestion complète
- Empêche ouverture/cassage par les autres
- Protection anti-spam au placement
- Protection à proximité (anti pose proche d’un conteneur protégé)

### 🧩 Commandes
- `/protect` : protège le conteneur ciblé
- `/unprotect` : retire la protection
- `/chestadd <joueur>` : autorise un joueur
- `/chestremove <joueur>` : retire un joueur
- `/chestsetting` : ouvre le menu de gestion
- `/chestlist [page]` : liste des joueurs autorisés
- `/cs_addplayer [page]` : GUI d’ajout/retrait
- `/chestprotect` : guide rapide

### ⚙️ Permissions
- `admin.breakcontainer` : casser un conteneur protégé
- `admin.chest` : bypass anti-poser près d’un conteneur protégé

### 🧠 Notes
- Le propriétaire peut casser son conteneur sans problème.
- Les joueurs non autorisés ne peuvent ni ouvrir, ni casser, ni poser un coffre à proximité d’un conteneur protégé.

| Script réalisé par | Contact |
|---|---|
| Spiralyfox | Discord : @Spiralyfox |

---

## English

### 🛡️ Features
- Container protection (chest, shulker box, barrel, hopper)
- Player access authorization
- Full management GUI
- Prevent opening/breaking by others
- Anti-spam message cooldown on placement
- Nearby protection (prevents placing near protected containers)

### 🧩 Commands
- `/protect` : protect targeted container
- `/unprotect` : remove protection
- `/chestadd <player>` : authorize a player
- `/chestremove <player>` : remove a player
- `/chestsetting` : open management menu
- `/chestlist [page]` : list authorized players
- `/cs_addplayer [page]` : add/remove GUI
- `/chestprotect` : quick guide

### ⚙️ Permissions
- `admin.breakcontainer` : break protected container
- `admin.chest` : bypass placing near protected container

### 🧠 Notes
- Owner can break their container without issue.
- Unauthorized players cannot open, break, or place near protected containers.

| Script made by | Contact |
|---|---|
| Spiralyfox | Discord: @Spiralyfox |
# 🛡️ Chestprotect

---

## Français

### 🔹 Description
Ce Skript permet de protéger des conteneurs (coffres, shulker box, barrel, hopper) pour empêcher l’accès et la destruction par d’autres joueurs, avec gestion d’accès via GUI.

### 🔹 Commandes
| Commande | Effet |
|----------|-------|
| `/protect` | Protège le conteneur ciblé |
| `/unprotect` | Retire la protection |
| `/chestadd <joueur>` | Autorise un joueur |
| `/chestremove <joueur>` | Retire l’accès d’un joueur |
| `/chestsetting` | Ouvre le menu de gestion |
| `/chestlist [page]` | Liste les joueurs autorisés |
| `/cs_addplayer [page]` | Ajouter/retirer des joueurs via GUI |
| `/chestprotect` | Affiche le guide |

### 🔹 Permissions
| Permission | Description |
|------------|-------------|
| `spiralyskript.chestprotect.protect` | Autorise `/protect` |
| `spiralyskript.chestprotect.unprotect` | Autorise `/unprotect` |
| `spiralyskript.chestprotect.chestadd` | Autorise `/chestadd` |
| `spiralyskript.chestprotect.chestremove` | Autorise `/chestremove` |
| `spiralyskript.chestprotect.chestsetting` | Autorise `/chestsetting` |
| `spiralyskript.chestprotect.chestlist` | Autorise `/chestlist` |
| `spiralyskript.chestprotect.cs_addplayer` | Autorise `/cs_addplayer` |
| `spiralyskript.chestprotect.breakcontainer` | Autorise de casser un conteneur protégé |
| `spiralyskript.chestprotect.chest` | Autorise de poser un coffre près d’un conteneur protégé |
| `spiralyskript.chestprotect.guide` | Autorise `/chestprotect` |

### 🔹 Options modifiables
| Option | Valeur par défaut | Description |
|--------|------------------|-------------|
| `prefix` | `&b[Server name] &8» &r` | Préfixe des messages |
| `perm_*` | — | Permissions personnalisées |
| `msg_*` | — | Messages personnalisables |

| **Script réalisé par** | Spiralyfox |
|-----------------------|-----------|
| **Discord** | @Spiralyfox |
| **Des idées de Skripts ?** | Propose ton idée sur Discord |

---

## English

### 🔹 Description
This Skript allows protecting containers (chests, shulker boxes, barrels, hoppers) to prevent access and destruction by other players, with access management via GUI.

### 🔹 Commands
| Command | Effect |
|---------|--------|
| `/protect` | Protects the targeted container |
| `/unprotect` | Removes protection |
| `/chestadd <player>` | Allows a player |
| `/chestremove <player>` | Removes a player’s access |
| `/chestsetting` | Opens management menu |
| `/chestlist [page]` | Lists allowed players |
| `/cs_addplayer [page]` | Add/remove players via GUI |
| `/chestprotect` | Shows the guide |

### 🔹 Permissions
| Permission | Description |
|------------|-------------|
| `spiralyskript.chestprotect.protect` | Allows `/protect` |
| `spiralyskript.chestprotect.unprotect` | Allows `/unprotect` |
| `spiralyskript.chestprotect.chestadd` | Allows `/chestadd` |
| `spiralyskript.chestprotect.chestremove` | Allows `/chestremove` |
| `spiralyskript.chestprotect.chestsetting` | Allows `/chestsetting` |
| `spiralyskript.chestprotect.chestlist` | Allows `/chestlist` |
| `spiralyskript.chestprotect.cs_addplayer` | Allows `/cs_addplayer` |
| `spiralyskript.chestprotect.breakcontainer` | Allows breaking protected containers |
| `spiralyskript.chestprotect.chest` | Allows placing a container near a protected one |
| `spiralyskript.chestprotect.guide` | Allows `/chestprotect` |

### 🔹 Configurable options
| Option | Default value | Description |
|--------|---------------|-------------|
| `prefix` | `&b[Server name] &8» &r` | Message prefix |
| `perm_*` | — | Custom permissions |
| `msg_*` | — | Customizable messages |

| **Script made by** | Spiralyfox |
|-------------------|-----------|
| **Discord** | @Spiralyfox |
| **Need a Skript ?** | Propose your idea on Discord |
