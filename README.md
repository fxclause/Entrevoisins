 - Application EntreVoisins -

Exécution de l’application
Sur un émulateur
Un émulateur permet de reproduire le comportement d’un appareil réel d’une façon
virtuelle. L’utilisation d’un émulateur nous évite d’avoir à charger à chaque fois l’application dans un appareil pour la tester. On pourra ainsi lancer l’application
dans l’IDE et elle s’exécutera sur un appareil virtuel appelé Android Virtual Device
AVD qui émule le comportement d’un téléphone, une tablette ou autre.
Pour configurer un émulateur, allez dans Tools > Android > AVD Manager, un
émulateur existe par défaut, mais vous pourriez rajouter d’autres appareils en cliquant sur Create Virtual Device .
Nous sélectionnons ensuite le processeur qui sera émulé. En cochant Show downloadable
system images vous pouvez télécharger d’autres images systèmes avec d’autres
versions Android. En cliquant sur Next Vous avez ensuite la possibilité de configurer d’autres paramètres.
Notez qu’à la création de l’appareil sa résolution vous est signalée. Ceci est important à noter pour l’intégration d’images dans l’application.
Pour lancer l’exécution sur l’émulateur, appuyez sur le bouton d’exécution et sélectionnez l’émulateur sur lequel vous souhaitez lancer l’application. Vous pouvez cochez Use same device for future launches pour éviter d’avoir à sélectionner
l’appareil à chaque lancement. L’émulateur se lance, ça peut prendre quelques minutes soyez patients. Rassurez-vous, vous n’aurez pas à le relancer à chaque fois que vous compilez votre projet, laissez-le ouvert et à chaque fois que vous compilez
et relancez votre application, elle pourra être chargée dans l’émulateur en cours.

Sur un appareil réel
Connectez votre appareil par câble USB à l’ordinateur et installez le pilote si
nécessaire 2
.
Activez l’option de débogage USB sur l’appareil en allant dans les paramètres, sous
développement ou options pour les développeurs. Pour les versions supérieures
à 4.2, cette option est cachée par défaut, pour la faire apparaitre, allez dans
Paramètres>A propos .. et touchez Numéro de build sept fois. Retournez ensuite
à l’écran Paramètres , vous verrez apparaitre Options pour les développeurs, rentrez
y et activez le débogage.
Lancez l’application depuis Android Studio comme précédemment. Si on vous
demande de choisir l’appareil, sélectionnez Choose a running device, puis votre
téléphone ou tablette. Android Studio installera l’application sur votre appareil
et la lancera.
Si au moment de la sélection de l’appareil vous recevez un message indiquant
que l’appareil n’est pas compatible, assurez vous d’abord que la version Sdk de
l’appareil est bien supérieure au minSdk version de votre projet. Si c’est le cas,
allez sur votre appareil tout en étant connecté par USB désactivez puis réactivez
l’option de débogage USB , il vous demandera de confirmer l’identifiant de votre ordinateur, confirmez en lui indiquant de toujours faire confiance à cet ordinateur.
