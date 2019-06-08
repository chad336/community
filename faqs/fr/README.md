# MakerDAO FAQs

* [CDP Calculator](https://docs.google.com/spreadsheets/d/1AdDOW1maMmVkSBQwzS-9mkkAKIjOvU8CO8rfNYqxNt0)
<!-- * [Glossary of Terms](glossary.md) -->

## Position de Dette Collatéralisée (CDP)

* [Qu'est-ce qu'une position de dette garantie \(CDP\) ?](#quest-ce-quune-position-de-dette-garantie-cdp)
* [Comment fonctionne un CDP ?](#comment-fonctionne-un-cdp)
* [Qui peut ouvrir un CDP ?](#qui-peut-ouvrir-un-cdp)
* [Y a-t-il des frais associés à l'utilisation d'un CDP ?](#y-a-t-il-des-frais-associés-à-lutilisation-dun-cdp)
* [Qu'est-ce que le niveau de garantie ?](#quest-ce-que-le-niveau-de-garantie)
* [Quels risques encourent les propriétaires de CDP ?](#quels-risques-encourent-les-propriétaires-de-cdp)
* [Quelles sont les bonnes pratiques permettant de limiter les risques ?](#quelles-sont-les-bonnes-pratiques-permettant-de-limiter-les-risques)
* [Quel est l'intérêt d'avoir un CDP ?](#quel-est-lintérêt-davoir-un-cdp)
* [Pourquoi ouvrir un CDP ?](#pourquoi-ouvrir-un-cdp)
* [Quand faut-il éviter d'ouvrir un CDP ?](#quand-faut-il-éviter-douvrir-un-cdp)
* [Quels sont les types de garanties acceptées pour un CPD ?](#quels-sont-les-types-de-garanties-acceptées-pour-un-cpd)
* [Peut-on rembourser ses dais depuis une bourse de cryptomonnaies ?](#peut-on-rembourser-ses-dais-depuis-une-bourse-de-cryptomonnaies)
* [Y a-t-il un niveau de garantie maximum ?](#y-a-t-il-un-niveau-de-garantie-maximum)
* [Si mes ethers sont dans un CDP, que se passe-t-il lors d'un parachutage de jetons \(_airdrop_\) ?](#si-mes-ethers-sont-dans-un-cdp-que-se-passe-t-il-lors-dun-parachutage-de-jetons-_airdrop_)
* [Puis-je simultanément placer mes cryptoactifs dans un CDP et dans un autre projet ?](#puis-je-simultanément-placer-mes-cryptoactifs-dans-un-cdp-et-dans-un-autre-projet)
* [Dois-je rembourser mes dais même si ma garantie a pris de la valeur ?](#dois-je-rembourser-mes-dais-même-si-ma-garantie-a-pris-de-la-valeur)
* [Puis-je continuer d'utiliser mon CDP après liquidation ?](#puis-je-continuer-dutiliser-mon-cdp-après-liquidation)
* [Comment vérifier la solvabilité de l'écosystème des CDP ?](#comment-vérifier-la-solvabilité-de-lécosystème-des-cdp)

## Dai

* [Qu'est-ce que le dai ?](#quest-ce-que-le-dai)
* [Pourquoi vouloir utiliser le dai ?](#pourquoi-vouloir-utiliser-le-dai)
* [Un dai vaut-il toujours exactement un dollar ?](#un-dai-vaut-il-toujours-exactement-un-dollar)
* [D'où vient le dai ?](#doù-vient-le-dai)
* [Quelqu'un d'autre a-t-il des droits sur mon Dai ?](#quelquun-dautre-a-t-il-des-droits-sur-mon-dai)
* [Comment le prix du dai reste-t-il stable ?](#comment-le-prix-du-dai-reste-t-il-stable)
* [Comment créer des dais ?](#comment-créer-des-dais)
* [Où acheter des dais ?](#où-acheter-des-dais)
* [Où peut-on consulter la quantité de garanties protégeant le dai ?](#où-peut-on-consulter-la-quantité-de-garanties-protégeant-le-dai)
* [Quelles organisations utilisent le dai ?](#quelles-organisations-utilisent-le-dai)

## Gouvernance

* [Qu'est-ce que le processus de gouvernance?](#quest-ce-que-le-processus-de-gouvernance)
* [Comment les détenteurs de MKR gèrent-ils le _Système de Crédit Dai_?](#comment-les-détenteurs-de-mkr-gèrent-ils-le-_système-de-crédit-dai_)
* [Comment puis-je voter?](#comment-puis-je-voter)
* [Comment puis-je m'assurer que mon vote est compté?](#comment-puis-je-massurer-que-mon-vote-est-compté)
* [Est-il possible de participer à un vote déjà en cours?](#est-il-possible-de-participer-à-un-vote-déjà-en-cours)
* [Est-il possible de changer mon vote?](#est-il-possible-de-changer-mon-vote)
* [Comment est-ce que le résultat d'un vote est calculé?](#comment-est-ce-que-le-résultat-dun-vote-est-calculé)
* [Quels sont les différents types de votes?](#quels-sont-les-différents-types-de-votes)
* [À quoi ressemble un vote typique?](#à-quoi-ressemble-un-vote-typique)
* [Est-ce que la _Fondation Maker_ vote?](#est-ce-que-la-_fondation-maker_-vote)
* [Quand est-ce que les sondages de gouvernance ont lieu?](#quand-est-ce-que-les-sondages-de-gouvernance-ont-lieu)
* [Quelle est la durée d'un sondage de gouvernance?](#quelle-est-la-durée-dun-sondage-de-gouvernance)
* [Quand est-ce que les votes exécutifs ont lieu?](#quand-est-ce-que-les-votes-exécutifs-ont-lieu)
* [Qu'est-ce que le vote en approbation continue?](#quest-ce-que-le-vote-en-approbation-continue)
* [Pourquoi est-ce que le vote en approbation continue est nécessaire?](#pourquoi-est-ce-que-le-vote-en-approbation-continue-est-nécessaire)
* [Quelle est la durée d'un vote exécutif?](#quelle-est-la-durée-dun-vote-exécutif)
* [Comment est-ce que le portail de vote fonctionne?](#comment-est-ce-que-le-portail-de-vote-fonctionne)
* [À quoi sert le contrat mandataire de vote?](#à-quoi-sert-le-contrat-mandataire-de-vote)
* [Qu'est-ce qu'un contrat mandataire?](#quest-ce-quun-contrat-mandataire)
* [Pourquoi est-ce que j'ai besoin d'un contrat mandataire?](#pourquoi-est-ce-que-jai-besoin-dun-contrat-mandataire)
* [Quelles sont les permissions accordées?](#quelles-sont-les-permissions-accordées)
* [Est-ce que chaque vote me coûte du gaz?](#est-ce-que-chaque-vote-me-coûte-du-gaz)
* [Quel est le coût total en gaz? Est-ce qu'il provient du portefeuille chaud ou froid?](#quel-est-le-coût-total-en-gaz-est-ce-quil-provient-du-portefeuille-chaud-ou-froid)
* [Combien de transactions est-ce que je dois signer?](#combien-de-transactions-est-ce-que-je-dois-signer)
* [À quoi sert le lien entre portefeuille chaud et portefeuille froid?](#à-quoi-sert-le-lien-entre-portefeuille-chaud-et-portefeuille-froid)
* [Qui contrôle mes jetons MKR lorsqu'ils sont verrouillés?](#qui-contrôle-mes-jetons-mkr-lorsquils-sont-verrouillés)
* [Comment est-ce que je peux m'assurer que mes jetons MKR sont verrouillés?](#comment-est-ce-que-je-peux-massurer-que-mes-jetons-mkr-sont-verrouillés)
* [Comment est-ce que je peux récupérer mes jetons MKR?](#comment-est-ce-que-je-peux-récupérer-mes-jetons-mkr)
* [Qu'est-ce qui advient de mes votes précédents si je retire mes jetons MKR?](#quest-ce-qui-advient-de-mes-votes-précédents-si-je-retire-mes-jetons-mkr)
* [Est-ce que je dois déverrouiller mes jetons MKR après avoir voté?](#est-ce-que-je-dois-déverrouiller-mes-jetons-mkr-après-avoir-voté)
* [Est-ce que je peux transférer mes jetons MKR à partir de mon portefeuille froid pendant qu'ils sont verrouillés?](#est-ce-que-je-peux-transférer-mes-jetons-mkr-à-partir-de-mon-portefeuille-froid-pendant-quils-sont-verrouillés)
* [Qu'est-ce qui se passe si j'envoie plus de jetons MKR vers mon portefeuille froid avec l'avoir lié?](#quest-ce-qui-se-passe-si-jenvoie-plus-de-jetons-mkr-vers-mon-portefeuille-froid-avec-lavoir-lié)
* [Est-ce que je peux briser le lien entre mon portefeuille chaud et mon portefeuille froid?](#est-ce-que-je-peux-briser-le-lien-entre-mon-portefeuille-chaud-et-mon-portefeuille-froid)
* [Est-ce qu'il est possible de combiner plusieurs adresses dans le même contrat de vote?](#est-ce-quil-est-possible-de-combiner-plusieurs-adresses-dans-le-même-contrat-de-vote)

## Liquidation

* [Qu'est-ce que le processus de liquidation?](#quest-ce-que-le-processus-de-liquidation)
* [Pourquoi a-t-on besoin d'un processus de liquidation?](#pourquoi-a-t-on-besoin-dun-processus-de-liquidation)
* [Qu'est-ce que le seuil de liquidation?](#quest-ce-que-le-seuil-de-liquidation)
* [Quel est le prix de liquidation?](#quel-est-le-prix-de-liquidation)
* [Quelle est la pénalité de liquidation?](#quelle-est-la-pénalité-de-liquidation)
* [Comment se déroule une liquidation?](#comment-se-déroule-une-liquidation)
* [Que reste-t-il comme garantie dans un CDP après une liquidation?](#que-reste-t-il-comme-garantie-dans-un-cdp-après-une-liquidation)
* [Comment puis-je calculer mon prix de liquidation?](#comment-puis-je-calculer-mon-prix-de-liquidation)
* [Comment puis-je calculer mon niveau de garantie?](#comment-puis-je-calculer-mon-niveau-de-garantie)
* [Comment puis-je diminuer le prix de liquidation de mon CDP?](#comment-puis-je-diminuer-le-prix-de-liquidation-de-mon-cdp)
* [Comment puis-je éviter la liquidation?](#comment-puis-je-éviter-la-liquidation)
* [Comment est-ce que le contrat de liquidité gère les ventes?](#comment-est-ce-que-le-contrat-de-liquidité-gère-les-ventes)
* [Est-ce que je peux acheter des jetons PETH qui ont été saisis?](#est-ce-que-je-peux-acheter-des-jetons-peth-qui-ont-été-saisis)
* [Comment un krach éclair affecterait-il la liquidation des CDP?](#comment-un-krach-éclair-affecterait-il-la-liquidation-des-cdp)
* [Où puis-je voir de l'information sur les liquidations en direct?](#où-puis-je-voir-de-linformation-sur-les-liquidations-en-direct)

## Frais de stabilité

* [Que sont les frais de stabilité ?](#que-sont-les-frais-de-stabilité)
* [Quand faut-il payer les frais de stabilité ?](#quand-faut-il-payer-les-frais-de-stabilité)
* [Les nouveaux frais s'appliquent-ils aux dettes passées ?](#les-nouveaux-frais-sappliquent-ils-aux-dettes-passées)
* [À quoi servent les frais de stabilité ?](#à-quoi-servent-les-frais-de-stabilité)
* [Pourquoi les frais de stabilité changent-ils ?](#pourquoi-les-frais-de-stabilité-changent-ils)
* [Comment les frais de stabilité sont-ils calculés ?](#comment-les-frais-de-stabilité-sont-ils-calculés)
* [Qu'arrive-t-il aux frais récoltés ?](#quarrive-t-il-aux-frais-récoltés)
* [Où consulter mes frais de stabilité accumulés ?](#où-consulter-mes-frais-de-stabilité-accumulés)
* [Comment les frais influencent-ils l'offre et la demande ?](#comment-les-frais-influencent-ils-loffre-et-la-demande)
* [Comment calculer l'impact d'un changement de frais de stabilité ?](#comment-calculer-limpact-dun-changement-de-frais-de-stabilité)
* [Comment en apprendre plus sur les équipes de gestion du risque et entrer en communication avec la Fondation au sujet de changements actuels ou futurs ?](#comment-en-apprendre-plus-sur-les-équipes-de-gestion-du-risque-et-entrer-en-communication-avec-la-fondation-au-sujet-de-changements-actuels-ou-futurs)
* [Y a-t-il une limite à la variation des frais de stabilité ?](#y-a-t-il-une-limite-à-la-variation-des-frais-de-stabilité)
* [Comment un détenteur de CDP peut-il réduire son exposition aux changements de frais de stabilité ?](#comment-un-détenteur-de-cdp-peut-il-réduire-son-exposition-aux-changements-de-frais-de-stabilité)
* [Que se passe-t-il si un vote de changement de frais échoue ?](#que-se-passe-t-il-si-un-vote-de-changement-de-frais-échoue)
* [À quelle fréquence les frais de stabilité changent-ils ?](#à-quelle-fréquence-les-frais-de-stabilité-changent-ils)