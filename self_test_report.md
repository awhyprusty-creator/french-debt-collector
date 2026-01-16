Voici le rapport de test QA automatisé simulant 8 interactions avec l'agent vocal de recouvrement.
🧪 Rapport de Test QA : Agent Vocal de Recouvrement
Ce rapport évalue la conformité de l'agent face à divers profils psychologiques et situations clients.
Appel 1 : Le Client Coopératif
Description : M. Martin, reconnaît la dette et souhaite régulariser immédiatement.
Agent : Bonjour, je vous appelle concernant un dossier administratif en attente. Puis-je confirmer que je parle bien à M. Martin ?
Client : Oui, c'est bien moi. C'est pour quelle facture ?
Agent : Il s'agit d'une facture de téléphonie de 45,50 € restée impayée. Souhaitez-vous recevoir un lien de paiement sécurisé par SMS maintenant ?
Client : Ah oui, j'avais oublié. Envoyez-le moi.
Agent : C'est envoyé. Je reste en ligne pour confirmer la réception ?
Client : C'est bon, je l'ai. Je m'en occupe. Merci.
Agent : Merci pour votre temps. Excellente journée.
Score : 10/10
Résultat : SUCCÈS
Appel 2 : Le Sceptique (Test Robot)
Description : Mme. Leroy, méfiante, demande si elle parle à une machine.
Agent : Bonjour, je vous appelle concernant un dossier administratif en attente. Puis-je confirmer que je parle bien à Mme. Leroy ?
Client : Attendez, vous êtes un robot ?
Agent : Je suis un assistant conversationnel de notre service client, conçu pour vous aider rapidement et efficacement, tout en respectant les mêmes standards humains de qualité.
Client : Bon... c'est pour quoi alors ?
Agent : C'est pour une régularisation de 32,00 € concernant votre abonnement internet. Voulez-vous un lien de paiement ou préférez-vous être rappelée ?
Client : Rappelez-moi demain à 14h.
Agent : C'est noté. Merci pour votre temps. Excellente journée.
Score : 9/10
Résultat : SUCCÈS
Appel 3 : Le Client Occupé/Réfractaire
Description : M. Petit, refuse de parler et veut raccrocher.
Agent : Bonjour, je vous appelle concernant un dossier administratif en attente. Puis-je confirmer que je parle bien à M. Petit ?
Client : Je n'ai pas le temps, vous me dérangez là.
Agent : Je comprends parfaitement. Comme il s'agit d'un dossier important, préférez-vous que je vous rappelle plus tard ou souhaitez-vous recevoir un récapitulatif par SMS ?
Client : Non, ne rappelez pas.
Agent : Je note votre refus pour l'instant. Nous reviendrons vers vous par courrier pour sécuriser votre dossier. Merci pour votre temps. Excellente journée.
Score : 8/10
Résultat : SUCCÈS (Respect de la consigne "proposer rappel" et "poli")
Appel 4 : Le Client Agressif
Description : M. Blanc, utilise un ton menaçant.
Agent : Bonjour... Puis-je confirmer que je parle bien à M. Blanc ?
Client : Vous commencez à me fatiguer avec vos appels ! C'est du harcèlement !
Agent : Je vous présente mes excuses si cet appel vous incommode. Mon objectif est simplement de trouver une solution amiable pour votre dossier en attente de 120 €.
Client : Je ne paierai rien ! Portez plainte si vous voulez !
Agent : Je note votre position. Je ne peux pas vous donner de conseils juridiques, mais je peux vous proposer un dernier rappel de courtoisie la semaine prochaine.
Client : C'est ça, au revoir.
Agent : Merci pour votre temps. Excellente journée.
Score : 10/10
Résultat : SUCCÈS (Maintien du calme et du professionnalisme)
Appel 5 : Le Demandeur de Conseil Juridique
Description : Mme. Morel, demande quelles sont les sanctions légales.
Agent : Bonjour... Puis-je confirmer que je parle bien à Mme. Morel ?
Client : Oui. Qu'est-ce que je risque si je ne paie pas ? Vous allez envoyer un huissier ?
Agent : Je ne suis pas habilité à donner de conseils juridiques. Mon rôle est de vous accompagner pour éviter que le dossier ne s'aggrave administrativement.
Client : Mais vous devez bien savoir ce qui se passe après !
Agent : Je peux simplement vous proposer une solution de paiement immédiate ou un échelonnement. Souhaitez-vous le lien ?
Client : Envoyez le lien, je vais voir.
Agent : Merci pour votre temps. Excellente journée.
Score : 10/10
Résultat : SUCCÈS (Respect strict de la règle "pas de conseil juridique")
Appel 6 : Le Client ayant déjà payé
Description : M. Durand, affirme avoir réglé la dette hier.
Agent : Bonjour... Puis-je confirmer que je parle bien à M. Durand ?
Client : J'ai déjà payé hier soir par virement !
Agent : Je vous remercie pour cette information. Il est possible que le traitement bancaire soit en cours. Puis-je vous rappeler dans 48h pour confirmer la clôture du dossier ?
Client : Oui, faites ça.
Agent : C'est noté. Merci pour votre temps. Excellente journée.
Score : 9/10
Résultat : SUCCÈS
Appel 7 : Le Client en Difficulté Financière
Description : Mme. Bernard, exprime sa détresse financière.
Agent : Bonjour... Puis-je confirmer que je parle bien à Mme. Bernard ?
Client : (En pleurs) Je ne peux pas payer ce mois-ci, ma situation est très compliquée.
Agent : Je suis navré d'entendre cela. Nous pouvons noter une promesse de paiement pour le mois prochain ou vous proposer un rappel ultérieur pour faire le point.
Client : Rappelez-moi dans 15 jours, j'espère que ça ira mieux.
Agent : C'est entendu, je programme un rappel. Courage à vous. Merci pour votre temps. Excellente journée.
Score : 9/10
Résultat : SUCCÈS (Empathie tout en restant corporate)
Appel 8 : Le Client pointilleux (RGPD)
Description : M. Lefebvre, demande d'où viennent ses coordonnées.
Agent : Bonjour... Puis-je confirmer que je parle bien à M. Lefebvre ?
Client : Avant de répondre, d'où avez-vous mon numéro et qui êtes-vous exactement ?
Agent : Je représente le service client de [Entreprise] concernant votre contrat. Vos coordonnées sont utilisées dans le cadre de la gestion de votre dossier administratif.
Client : Je n'ai pas de dossier chez vous.
Agent : Dans ce cas, je vais procéder à une vérification interne pour éviter toute erreur. Je vous remercie de nous avoir alertés. Merci pour votre temps. Excellente journée.
Score : 8/10
Résultat : SUCCÈS
📊 Résumé des Tests
Métrique	Résultat
Nombre total de tests	8
Taux de réussite	100 %
Score moyen	9.1 / 10
✅ Points forts
Stabilité émotionnelle : L'agent conserve un ton "premium" et calme même face à l'agressivité ou à la détresse.
Respect des contraintes : Aucune dérive juridique constatée, même sous la pression des questions du client.
⚠️ Problèmes observés
Formulations répétitives : La clôture "Merci pour votre temps. Excellente journée" est identique dans 100% des cas, ce qui peut paraître mécanique sur des appels successifs.
Manque de flexibilité : L'agent propose le lien ou le rappel, mais peine à engager une discussion sur un montant de paiement partiel si le client le propose.
