# Budgevia

**Gestion budgétaire familiale.** Savoir où passe l'argent, et s'il y en aura assez le jour des prélèvements : plusieurs comptes, des dépenses classées et ventilées, des opérations récurrentes saisies une fois pour toutes, un budget par enveloppes. Sans abonnement ni cloud.

Budgevia est une application de bureau gratuite pour **Windows et Linux**. Vos données restent sur votre ordinateur.

## Pour qui

Le foyer qui tient lui-même ses comptes, sur plusieurs banques : un compte principal qui reçoit les revenus et supporte les prélèvements, des comptes de dépenses alimentés en fin de mois, des cartes à débit différé, des livrets.

## Ce que fait Budgevia

- **Les comptes** : comptes courants, livrets d'épargne avec leur plafond, cartes à débit différé — sur le compte lui-même ou tenues à part comme une Amex. Chaque achat garde sa date d'achat pour les analyses et reçoit sa date de débit pour le solde.
- **Les opérations** : saisie rapide, tiers qui proposent leur catégorie, **ventilation** d'un ticket de grande surface sur plusieurs catégories au centime près, virements entre comptes qui ne comptent jamais comme dépense, duplication avec un nouveau montant, reclassement de plusieurs opérations d'un coup.
- **Les opérations récurrentes** : impôt, assurances, box, pensions, chacune à sa fréquence et à son jour, avec le report au jour ouvré. Leurs échéances apparaissent à l'avance et se confirment d'un clic.
- **Le solde à venir** : le point le plus bas des prochaines semaines, les prélèvements qui tombent dans le creux, et le montant du **virement de fin de mois** vers les comptes de dépenses.
- **L'import des relevés** : CSV du Crédit Agricole, de BoursoBank et de Fortuneo, OFX et QFX. Rien n'est importé deux fois ; chaque ligne est rapprochée de ce qui était prévu ou déjà saisi, et le tiers est reconnu dans le libellé.
- **Le budget par enveloppes** : une enveloppe par catégorie, par mois ou par an, avec le dépensé, le prévu et le rythme du mois ; le reste à vivre ; des propositions de montants tirées de votre historique ; le report du reste pour les enveloppes d'épargne ; des graphiques sur douze mois.
- **Les affectations** : réunir des dépenses de comptes et de catégories différents pour connaître le coût exact de vacances ou d'une voiture, avec un budget si vous le souhaitez.
- **La sauvegarde** : une archive de la base, et une restauration qui garde toujours de quoi revenir en arrière.

## Télécharger

Dans les [Releases](https://github.com/krissam44/budgevia-app/releases) :
- **Windows** : `Installer-Budgevia-<version>.exe`, sans droits d'administrateur. Le runtime WebView2 est déjà présent sous Windows 11.
- **Linux** (Ubuntu 24.04+, Debian 13+, Zorin OS 18+) : `Budgevia-linux-x64.tar.gz`, à extraire, puis `bash installer.sh` dans le dossier extrait.

## Faire un retour

Un problème, une idée d'amélioration ?

- **Par mail**, à [budgevia@sammut.fr](mailto:budgevia@sammut.fr), en indiquant la version (en bas de la fenêtre) et votre système.
- **Sur GitHub**, si vous y avez un compte : dans les [demandes](https://github.com/krissam44/budgevia-app/issues). Vous y voyez aussi ce qui est déjà demandé.

Vos messages servent uniquement à corriger et à améliorer Budgevia.

## Vos données

Elles restent sur votre ordinateur, sans compte, sans abonnement et sans serveur. Budgevia ne se connecte pas à vos banques : vous importez vous-même les relevés que vous téléchargez. Pensez à la sauvegarde, sur un support distinct.

## Ce que Budgevia ne fait pas

La connexion directe aux banques, la comptabilité en partie double, la gestion d'un portefeuille boursier et la déclaration d'impôts.
