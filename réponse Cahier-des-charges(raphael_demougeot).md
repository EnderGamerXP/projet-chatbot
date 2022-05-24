# _Qu’est ce qui rendrait le ChatBot naturel et efficace ?

## une base de donné lingustique permetant la casse.
 ### faute d'ortographe par exemple

_Comment devrait réagir le ChatBot en cas de demande
inconnue ?

2 cas de figure

-1 la demande à des similaritée avec d'autre demandes elles sont alors proposée

-2 si aucune similaritée même après un annalyse appronfondit des caractère repondre
"je n'arrive pas à comprendre votre demande désolé"

_Pour chacun des points précédent, trouver une solution
logicielle ou matérielle.

. usage potentiel d'une Arduino
. relier par une raspberry pi pour le réseau
. la base de donné SQL "mariaDB ?" sera modifiable en tant qu'utilisateur, mais seulement via l'IHM du chatbot, dons l'accès requièt un mot de passe

_Résumer en quelques lignes ce que vous avez compris du projet à réaliser. Quelles
sont les zones d’ombre, les points non compris ?

le projet consite principalement au dévelopement d'une IHM en C pour une maison domotisée sous la forme d'un chatbot

_Répondre aux trois questions posées dans le cahier des charges (surlignées en jaune).

fait î

_Quelle approche algorithmique envisagez-vous pour réaliser le ChatBot ? Autrement
dit, une fois la phrase de l’utilisateur récupérée comment comptez-vous procéder
pour l’analyser et comprendre quelle action faire ?

la phrase sera décomposée mot par mot et envoyer individuelement à la base de donné, qui retournera un ou plusieur identifiant de demande assosier,
la demande ayent étée le plus retourner par la base de donné sera choisi,
en cas dégalité les deux demandes seront proposée par l'IHM,
les nouveaux mots assosier à une demande seront insèrer par l'utilisateur via une demande dédier,
mot par défaut assosier à cette demande "sela" "signifira" "que" , note de fonctionnement (demande à associer) (demande d'assosiation) (mots à associer),
pour effacer un mot enregistrer une demande uniquement assosier au mot "oublier" et mis à disposition de l'utilisateur autentifier, le prossus se fait cepandant via un avertissement avant le lancement de la procedure,
(les mots inserer par défaut dans la base de donne ne pourront pas être suprimer ?)
(proposition d'amélioration l'utilisateur pourrait crée des demandes "raccourcis/demande combiner" à partir d'autre demandes ?)

_Proposer un schéma complet du système.

voir dossier "chatbot UML"
