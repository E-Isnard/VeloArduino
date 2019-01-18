# Rapport de Enzo Isnard

## Rapport du 14/12/18

La séance précédante nous avont fait des recherches sur le fonctionement physique de l'équilibrage de notre
vélo à l'aide d'une roue d'inertie. Nous avons vu que notre vélo pouvait être assimilier à un pendule inversé,c-à-d un pendule qui est dans sa position d'équilibre instable. Nous avons aussi cherché les roues pour notre vélo, que nous avons finalement trouvé au cours d'une longue recherche. 

Durant cette séance nous avons convenu que Sacha fera le partie équilibrage(pid,roue d'inertie) et que je m'occuperai de créer le vélo mais sans équilibrage(Déplacement et communication Bluetooth).

## Rapport du 18/12/18

Durant cette séance nous avons testé un moteur qui pourrait être le futur moteur de la la roue d'inertie. Nous avons soudé des fils sur le moteur et il fonctionne parfaitement.Ce moteur dispose d'un grand nombre de tours par minute et d'un faile couple puisqu'il n'a pas d'encodeur. L'idéal pour la roue d'inertie serait d'utiliser un moteur de disque dur (beaucoup de t/min et Nm faible).J'ai vu aussi que le moteur conseillé pour les roues que nous avons commandées était le Motoréducteur GM8, il est cependant assez similaire aux moteurs que nous avons utilisés pour les voitures donc pas sûr qu'on en commande un si ces derniers nous vont.Nous avons également essayé l'accéléromètre mais nous n'avons pas réussi à le faire fonctionner. Avec les programmes que nous avons testés il nous renvoyait toujours la même valeur. On pense que cela doit être du aux codes qu'on a utilisés. Durant cette séance Sacha a également trouvé un code pour un pendule inversé utilisant le pid, ce qui pourrait grandement faciliter la réalisation de notre programme. Pour la prochaine séance il faudrait qu'on commence à réaliser le corps du vélo de manière de manière à pouvoir rapidement tester l'équilibre du vélo, qui est la partie la plus complexe du projet. 

## Rapport du 11/01/19

Aujourd'hui j'ai commencé la construction du corps du vélo avec les meccano. J'essaie de m'inspirer de la structure du vélo de ce site:https://iedprojects2015.blogspot.com/2015/03/self-balancing.html. J'ai eu du mal à créer une structure stable car les vis ne correspondaient pas aux trous du moteur donc j'ai du scié deux bouts de fils de fer qui avaient un largeure plus adéquate. J'ai pour l'instant juste réussi à créer une structure autour de la roue qu'on pourra joindre au corps du vélo.

![photo roue](https://raw.githubusercontent.com/ComfortablyDumb/VeloArduino/master/image_roue.jpg)

Il me reste donc beaucoup à faire et je pense essayer de quasiment finir la structure durant ce weekend.
Quant à Sacha il a réussi à faire fonctionner l'accéléromètre et a pu faire fonctionner un code faisant varier la vitesse du moteur de la roue d'inertie en fonction de l'inclinaison de l'accéléromètre.
Durant des recherches sur notre projet j'ai trouvé un pdf décrivant une méthode pour configurer les coefficients du pid (<https://brage.bibsys.no/xmlui/bitstream/handle/11250/2451060/12762_FULLTEXT.pdf?sequence=1> à la page 15).

## Rapport du 18/01/19

Durant cette semaine j'ai beaucoup avancé la structure du vélo. J'ai réussi à créer une base en enfonçant deux pièces et en les visant entre elles. J'ai aussi vissé la roue avec la moteur.
A la fin j'avais quelque chose qui resemblait à ça :
![photo velo 1](https://raw.githubusercontent.com/ComfortablyDumb/VeloArduino/master/image_velo_1.jpg)
J'ai eu cependant un problème: les écrous que j'avais ne correspondaient pas parfaitement aux vis que j'utilisaient, ce qui fait que la roue ne tenait pas très bien.

J'ai ensuite pendant cette séance essayé de résoudre les problemes de stabilité de la roue avec le moteur et d'attacher la roue sans moteur au corps du vélo. J'ai eu pas beaucoup de mal car aucun écrou ne correspondait aux vis que j'utilisaient. Finalement avec l'assistant de monsieur Masson on a décidé des fils de plastiques pour serrer la roue sur le moteur à la place.La roue était bien plus stable comme ça. J'ai alors commencé à fixer la deuxieme roue mais il n'y avait qu'un seul type de vis qui rentrait dans la roue et cela ne permettait pas à la fois de laisser la roue tourner et faire en sort qu'elle ne sorte pas de son axe. Au final j'ai agrandit le trou de la roue avec une perceuse et j'ai pu mettre une tige de fer comme axe à la place de la vis. J'ai aussi fixé des bouts de caoutchou pour que la roue ne puissent pas partir de son axe, à la fin j'avais comme résultat:

![photo velo 2](https://raw.githubusercontent.com/ComfortablyDumb/VeloArduino/master/image_roue_2.jpg)

J'ai encore comme problemes que quand je visse la roue sans moteur sur le vélo que cette dernière peut tourner car la vis se déssert sans cesse et que les deux roues ne sont pas encore complètement parralèles.
Durant ce weekend je vais essayé de résoudre ces problemes qui sont du moins assez simples à résoudre à mon avis.