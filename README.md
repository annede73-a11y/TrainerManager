# TrainerManager

Gestionnaire de trainers pour jeux PC **solo (single-player)** — une
alternative gratuite et **100 % locale** à WeMod. TrainerManager ne fournit
aucun trainer lui-même : il organise, lance et ferme proprement ceux que
vous ajoutez (`.exe` ou tables Cheat Engine `.CT`), à côté de vos jeux
détectés automatiquement (Steam, Epic, GOG, Ubisoft Connect, Battle.net).

> **Ce dépôt distribue uniquement l'application compilée.** Le code source
> n'est pas publié ici.

---

## Télécharger

Les versions sont publiées dans l'onglet **[Releases](../../releases)** de
ce dépôt. Chaque version propose deux fichiers :

- `TrainerManager.exe` — l'application, un seul fichier, rien à installer
- `TrainerManager.exe.sha256.txt` — son empreinte, pour vérifier que le
  fichier téléchargé est bien celui publié ici

### Vérifier le fichier téléchargé

Dans une invite de commandes, à l'endroit où vous l'avez téléchargé :

```
certutil -hashfile TrainerManager.exe SHA256
```

Le résultat doit correspondre exactement à l'empreinte du fichier
`.sha256.txt` de la même version. Si ce n'est pas le cas, ne l'exécutez
pas.

---

## Fonctionnalités

- Détection automatique des jeux installés (Steam, Epic Games, GOG
  Galaxy, Ubisoft Connect, EA App, Battle.net)
- Lancement du jeu + attache automatique du trainer, fermeture automatique
  du trainer à la fermeture du jeu
- Tables Cheat Engine (`.CT`) — nécessite d'avoir Cheat Engine déjà
  installé par vos soins
- SaveGuard : archivage automatique de vos sauvegardes avant chaque
  lancement avec trainer
- Safety Shield : avertissement si un anti-cheat connu est détecté dans le
  dossier du jeu
- Récupération automatique des jaquettes (optionnelle)
- 100 % local : aucun compte, aucune télémétrie

---

## Avant d'utiliser un trainer — l'essentiel

- **Jamais en ligne ou en multijoueur.** Un trainer peut faire bannir
  votre compte sur un jeu en ligne. Usage strictement solo.
- Les trainers et tables que vous ajoutez viennent de sites tiers :
  TrainerManager ne les vérifie pas. Téléchargez-les uniquement depuis des
  sources de confiance.
- L'avertissement Safety Shield est indicatif, pas une garantie : son
  absence ne prouve jamais qu'un jeu est sûr à utiliser avec un trainer.
- Application fournie « telle quelle », sans garantie, à vos propres
  risques.

La notice complète (installation, avertissements détaillés,
confidentialité) est dans [`NOTICE.md`](NOTICE.md).

---

## Conditions d'utilisation

TrainerManager est gratuit, pour un usage personnel. Vous êtes libre de le
télécharger et de l'utiliser librement. La redistribution de versions
modifiées n'est pas autorisée. Le code source n'est pas publié avec cette
application.

---

## Besoin d'aide ?

Ouvrez une [issue](../../issues) sur ce dépôt en décrivant votre problème
(idéalement avec le contenu du journal, accessible depuis l'application
via le bouton « Ouvrir les logs »).
