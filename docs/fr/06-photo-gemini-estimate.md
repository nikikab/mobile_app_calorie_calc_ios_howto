# 6. Photo d'aliment : estimation Gemini

Gemini estime le repas à partir de la photo : nom, grammes, calories et macros.

**Prérequis:** Une clé API Gemini saisie dans les Réglages (voir le scénario 10) et votre accord pour l'envoi des photos. Tant qu'une clé est définie, la photo est envoyée à Google à chaque prise de vue.

## Étapes

1. Photographiez l'aliment ou choisissez une photo. La première fois, une alerte demande **Envoyer à Google Gemini ?** ; lisez-la et touchez **Accepter et continuer**. Avec **Pas maintenant**, rien n'est envoyé.

2. Après quelques secondes, l'estimation Gemini apparaît sous la photo, une carte par aliment avec ses ingrédients.

   ![Photo d'aliment : estimation Gemini – 2](../../media/06-photo-gemini-estimate/en-01-estimate.png)

3. Touchez le **Ajouter** vert sur une carte. L'entrée va dans le repas choisi comme estimation, avec la photo. L'étoile enregistre le plat en favori.

## Résultat

Les estimations sont approximatives. Si quelque chose ne va pas, corrigez-le avec le scénario suivant. Sans clé, la photo n'obtient que les étiquettes de l'appareil.

---

[← Précédent](05-photo-offline-labels.md) · [Retour au sommaire](../../README.fr.md#sommaire) · [Suivant →](07-edit-estimate-add-all.md)
