# Politique de confidentialité — LumeTV

_Dernière mise à jour : 28 juin 2026_

LumeTV est un **lecteur IPTV personnel** pour Android TV. Cette politique décrit quelles
données l'application manipule et comment.

## En résumé

- LumeTV **ne collecte aucune donnée personnelle** et **n'envoie rien** au développeur ni
  à un quelconque serveur tiers.
- **Aucune publicité, aucun traceur, aucun outil d'analyse.**
- LumeTV **ne fournit aucun contenu** : tu renseignes ta propre source IPTV.

## Données stockées sur ton appareil

Pour fonctionner, LumeTV enregistre **localement sur ton appareil** :

- les **identifiants de ta source** (M3U / Xtream), **chiffrés** (Android Keystore) ;
- tes **favoris**, **chaînes/catégories masquées**, **filtres** et **réglages** ;
- le **code PIN parental** (stocké sous forme de **hash**, jamais en clair).

Ces données restent sur l'appareil. Les **désinstaller** supprime l'application les efface.

## Sauvegarde Google Drive (optionnelle)

Si — et seulement si — tu actives la sauvegarde, LumeTV utilise le scope
**`https://www.googleapis.com/auth/drive.appdata`** pour stocker une copie de **ta
configuration** dans le **dossier « App Data » privé et caché de ton propre Google Drive**.

- Ce dossier est **isolé à l'application** : il n'apparaît pas dans « Mon Drive » et n'est
  accessible **que par LumeTV**, **sur ton compte**.
- La sauvegarde contient ta **configuration** (sources **avec identifiants**, favoris,
  réglages, masquages, hash du PIN parental). Elle **ne contient pas** le flux des chaînes.
- Elle sert **uniquement** à te permettre de **restaurer ta configuration** sur un autre
  appareil. Elle **n'est partagée avec personne**, **ni avec le développeur**.
- LumeTV n'accède à **aucun autre fichier** de ton Drive (le scope `drive.appdata` ne le
  permet pas).

### Justification du scope
Le scope `drive.appdata` est utilisé exclusivement pour la **sauvegarde/restauration de la
configuration de l'utilisateur**, dans son propre espace privé. Aucun autre usage.

## Suppression de tes données

- **Sur l'appareil** : désinstalle LumeTV, ou utilise « Déconnecter » / réinitialise la config.
- **Sur Drive** : déconnecte ton compte dans LumeTV, et/ou supprime les données de
  l'application depuis les réglages Google de ton compte
  (drive.google.com → Paramètres → Gérer les applications).

## Contact

Pour toute question : **celtiore109@gmail.com**.

---

_LumeTV est un projet personnel, distribué tel quel, sans garantie._
