# Packet Forge — CrackTheCode

**Packet Forge** est un simulateur narratif et pédagogique 100% fictif, intégré à l’univers **CrackTheCode**.

- Environnement sandbox **sans aucune interaction réelle avec Internet**.
- Simule un analyste cyber / opérateur réseau dans l’univers d’Akira, Sam & Lyra.exe.
- Campagne longue : missions procédurales, progression, XP, traces, artifacts.
- Sauvegarde automatique locale + export / import de partie.
- Pensé pour être intégré sur `crackthecode.ca/jeux` via un `<iframe>`.

> ⚠️ **Important** : Ce projet est conçu uniquement à des fins éducatives et immersives.  
> Aucun code, commande ou payload ne doit être utilisé en dehors de ce simulateur.

---

## Fonctionnalités

- **Terminal virtuel**
  - Commandes simulées : `help`, `mission`, `forge`, `send`, `inspect`, `block`, `replay`, `status`, `report`, `clear`, etc.
  - Messages dynamiques de `Lyra.exe` pour guider le joueur (vision Blue Team).

- **Éditeur de paquets (fictifs)**
  - Forge des paquets avec type, cible, priorité.
  - Envoi vers des noeuds fictifs : `dmz.akiranet`, `ghost.akiranet`, `core`, etc.
  - Visualisation des paquets dans une **topologie réseau animée** (SVG).

- **Missions & progression**
  - Génération de missions multi-étapes (recon → analyse → forensic → mitigation → rapport).
  - Gain d’XP, montée de niveau, temps de jeu cumulé.
  - Pensé pour plusieurs heures de jeu si le joueur explore et lit les logs.

- **Sauvegarde**
  - **Auto-save** via `localStorage`.
  - Sauvegarde manuelle.
  - Export / import de sauvegarde au format JSON.
  - Export des logs de session pour partage / analyse (toujours fictif).

---

## Installation / Développement

Aucune dépendance, aucun build.

1. Cloner ou créer le dépôt :
   ```bash
   git clone https://github.com/samuellapierre-tech/crackthecode-packetforge.git
