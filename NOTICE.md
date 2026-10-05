# TrainerManager — Notice d'utilisation et avertissements

Merci d'utiliser TrainerManager. Cette notice explique comment démarrer et,
surtout, ce qu'il faut savoir avant de s'en servir. Elle est distribuée avec
l'application : gardez-la à portée de main.

---

## 1. Qu'est-ce que TrainerManager ?

TrainerManager est un gestionnaire de trainers pour jeux PC **solo
(single-player)**. Il ne fournit aucun trainer lui-même : il vous aide à
organiser, lancer et fermer proprement ceux que **vous** ajoutez (fichiers
`.exe` ou tables Cheat Engine `.CT`), aux côtés de vos jeux détectés
automatiquement (Steam, Epic, GOG, Ubisoft Connect, Battle.net) ou ajoutés à
la main.

L'application fonctionne **100 % en local** : aucune création de compte,
aucun service en ligne obligatoire, aucune donnée personnelle collectée.

---

## 2. Installation : où placer `TrainerManager.exe`

Au premier lancement, TrainerManager crée automatiquement, **juste à côté**
de `TrainerManager.exe`, trois dossiers : `data` (vos jeux, trainers et
réglages), `cache` (jaquettes téléchargées) et `logs`. Un quatrième,
`backups`, apparaîtra plus tard si vous utilisez SaveGuard. C'est normal et
voulu : vos données restent toujours avec l'exécutable, où que vous le
mettiez.

Pour cette raison :

1. Placez `TrainerManager.exe` dans **son propre dossier** (par exemple
   `Documents\TrainerManager\`), plutôt que directement sur le Bureau ou
   dans `Téléchargements` — sinon ces quatre dossiers s'y retrouveront
   pêle-mêle avec vos autres fichiers.
2. Pour y accéder facilement, créez un **raccourci** vers
   `TrainerManager.exe` sur le Bureau (clic droit sur l'exe → *Envoyer vers*
   → *Bureau (créer un raccourci)*), plutôt que de déplacer l'exécutable
   lui-même.
3. Si vous devez un jour déplacer l'application, déplacez le **dossier
   entier** (l'exe et les quatre dossiers ensemble), pas seulement l'exe,
   sous peine de laisser vos données derrière.

---

## 3. Démarrage rapide

1. Lancez TrainerManager. Vos jeux installés sont détectés automatiquement
   au premier démarrage.
2. Pour un jeu, ouvrez son panneau et ajoutez un trainer (bouton
   « Gérer les trainers ») : un fichier `.exe` que vous possédez déjà, ou une
   table Cheat Engine `.CT`.
3. Cliquez sur **JOUER** : le jeu se lance, puis le trainer s'attache
   automatiquement une fois le jeu détecté.
4. Si le trainer est réglé sur « fermer avec le jeu », il se fermera tout
   seul quand vous quitterez le jeu.

Les journaux détaillés (utiles en cas de problème) sont accessibles via le
bouton « Ouvrir les logs » dans l'application.

---

## 4. Avertissements importants — à lire avant utilisation

### 4.1 Usage solo uniquement — jamais en ligne ou multijoueur

**N'utilisez jamais un trainer sur un jeu en ligne, en multijoueur, ou sur
une partie classée.** La plupart des jeux en ligne détectent la
manipulation de mémoire et peuvent **bannir votre compte**, parfois de
façon définitive et parfois pour l'ensemble d'un jeu (pas seulement un
mode). TrainerManager est conçu pour un usage **strictement solo**
(campagnes, bac à sable, parties hors ligne). Vous seul(e) êtes responsable
de la façon dont vous utilisez un trainer.

### 4.2 Les trainers et tables tiers ne sont pas vérifiés par TrainerManager

TrainerManager **n'analyse, ne vérifie ni ne garantit** le contenu des
fichiers `.exe` ou `.CT` que vous ajoutez : il se contente de les lancer. Ces
fichiers viennent d'ailleurs (sites de trainers tiers, communautés, etc.), pas
de TrainerManager lui-même.

- Téléchargez uniquement depuis des sources en qui vous avez confiance.
- Gardez un antivirus à jour : les trainers sont une cible fréquente de
  faux positifs, mais aussi, parfois, de véritables fichiers malveillants
  déguisés en trainer. En cas de doute, ne l'exécutez pas.
- TrainerManager ne peut pas être tenu responsable d'un fichier tiers que
  vous avez choisi d'ajouter et d'exécuter.

### 4.3 Safety Shield : un avertissement indicatif, pas une garantie

Avant un lancement avec trainer, TrainerManager peut afficher un
avertissement s'il repère un anti-cheat connu (EasyAntiCheat, BattlEye,
PunkBuster) dans le dossier du jeu. **C'est purement indicatif** : la
détection se base sur des noms de fichiers connus. Un anti-cheat absent de
cette liste, ou installé ailleurs, ne sera pas détecté — l'**absence**
d'avertissement ne prouve donc jamais qu'un jeu est sûr à utiliser avec un
trainer. Cet avertissement ne bloque jamais automatiquement un lancement :
la décision finale vous revient toujours.

### 4.4 SaveGuard protège vos sauvegardes, mais n'est pas infaillible

SaveGuard peut archiver automatiquement le dossier de sauvegardes d'un jeu
avant chaque lancement avec trainer, pour pouvoir revenir en arrière en cas
de problème. Néanmoins :

- **C'est vous qui indiquez le dossier à sauvegarder** : TrainerManager ne
  le devine jamais. Si le mauvais dossier est indiqué (ou aucun), rien
  d'utile n'est sauvegardé.
- Un échec de sauvegarde ne bloque jamais le lancement du jeu (il est
  seulement signalé) : vérifiez de temps en temps que vos archives sont bien
  créées.
- Faites vos propres sauvegardes importantes ailleurs si elles vous sont
  précieuses. TrainerManager ne remplace pas une sauvegarde manuelle de vos
  fichiers les plus importants.

### 4.5 Cheat Engine (tables .CT)

Les tables `.CT` nécessitent que **Cheat Engine soit installé séparément**
par vos soins (TrainerManager ne l'installe, ne le télécharge et ne le
fournit jamais). Cheat Engine demandera très probablement les **droits
administrateur** à chaque lancement : c'est normal, c'est une exigence de
Cheat Engine lui-même, que TrainerManager ne contourne pas et ne doit pas
contourner. Cheat Engine peut aussi vous demander de confirmer l'exécution
d'un script au lancement d'une table : c'est une protection native de
Cheat Engine, pas une erreur de TrainerManager.

### 4.6 Confidentialité et réseau

TrainerManager ne se connecte à Internet que pour deux choses, toujours
volontaires de votre part :

- La récupération automatique de jaquettes (désactivée par défaut,
  activable dans Paramètres) : seul le **nom du jeu** est envoyé, jamais un
  chemin de fichier ni aucune autre donnée personnelle.
- Les liens vers des sites de trainers que **vous** configurez vous-même :
  TrainerManager ouvre votre navigateur, mais ne télécharge jamais rien
  automatiquement.

Aucune télémétrie, aucun compte, aucune donnée envoyée à l'éditeur de
l'application.

### 4.7 Vérifier que l'exécutable n'a pas été modifié

Chaque version publiée de `TrainerManager.exe` est accompagnée d'un
fichier `TrainerManager.exe.sha256.txt` contenant son empreinte SHA-256.
Pour vérifier que le fichier que vous avez téléchargé est bien celui qui a
été publié (et non une copie modifiée), ouvrez une invite de commandes à
l'endroit où vous l'avez téléchargé et tapez :

```
certutil -hashfile TrainerManager.exe SHA256
```

Le résultat doit correspondre exactement à l'empreinte publiée pour cette
version. Si ce n'est pas le cas, ne l'exécutez pas.

### 4.8 Aucune garantie

TrainerManager est fourni gratuitement, « tel quel », sans garantie d'aucune
sorte. Son auteur ne peut être tenu responsable d'un dommage, d'une perte de
données, d'un bannissement de compte ou de tout autre préjudice résultant de
son utilisation ou de celle d'un fichier tiers (trainer, table) que vous y
avez ajouté. Vous utilisez ce logiciel à vos propres risques.

---

## 5. Besoin d'aide ?

En cas de problème, ouvrez les journaux depuis l'application (bouton
« Ouvrir les logs ») : ils détaillent chaque étape (détection du jeu,
lancement du trainer, fermeture automatique...) et sont la première chose à
consulter avant de demander de l'aide.
