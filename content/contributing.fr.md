---
title: "Contribuer"
---
Vous pouvez contribuer à OpenBlox de plusieurs manières. Vous pouvez corriger des erreurs que vous remarquez en naviguant sur le wiki et vous pouvez améliorer le contenu ou rédiger de nouveaux articles à propos d’OpenBlox. Si vous êtes programmeur, vous pouvez contribuer au moteur de jeu ou aux autres outils qui font partie du projet OpenBlox.

## Don

Nous acceptons les dons en bitcoin et litecoin ainsi que les paiements par PayPal. Vous pouvez trouver [nos adresses](/donate.asc) signées par la clé du chef de projet, John Harris. Les contributions monétaires permettent à nos serveurs de demeurer actifs, paient pour notre nom de domaine et accès à internet, entre autres choses.

### Matériel informatique

Nous acceptons aussi les dons de matériel informatique, ce qui inclut les appareils suivants&nbsp;:

* Serveurs Rackmount
* Stations de travail
* Ordinateurs portables
* Commutateurs réseau 10/100 ou gigabit
* Alimentation électrique sans coupure

Le matériel donné n’a pas besoin d’être en état de fonctionnement, mais il serait préférable que nous n’ayons pas à prendre notre administrateur système d’autres travaux pour réparer les périphériques. Envoyez les offres de matériel à [hardware-donation@openblox.org](mailto:hardware-donation@openblox.org).

## Documentation

La documentation d’OpenBlox est faite sur [le wiki](https://wiki.openblox.org). Pour contribuer, vous n’avez qu’à créer un compte. Comme mesure contre le spam et le vandalisme, les comptes nouvellement créés ne peuvent pas téléverser de fichiers, créer des pages autres que des pages de discussion ou déplacer des pages. Les comptes qui ont existé pour plus de cinq jours et qui ont fait plus de quinze modifications peuvent faire toutes ces choses. Si vous avez besoin d’aide pour modifier le wiki, vous pouvez voir les [pages d’aide de MediaWiki](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Contents) ou poser vos questions sur une [page de discussion](https://www.mediawiki.org/wiki/Special:MyLanguage/Help:Talk_pages).

La documentation des classes est faite avec les modèles [Infobox class](https://wiki.openblox.org/wiki/Template:Infobox_class), [Property](https://wiki.openblox.org/wiki/Template:Property), [Method](https://wiki.openblox.org/wiki/Template:Method) et [Event](https://wiki.openblox.org/wiki/Template:Event). Vous pouvez voir la documentation de chacun de ces modèles sur sa page de documentation.

## Traduction

Nous sommes toujours à la recherche de traducteurs pour le wiki, ainsi que le moteur de jeu et le client. Si vous souhaitez traduire le wiki, contactez [mark@openblox.org](mailto:mark@openblox.org). La traduction du moteur, du client et du studio est faite avec Qt Linguist. Si vous avez besoin d’aide avec cela, contactez [johnmh@openblox.org](mailto:johnmh@openblox.org).

## Développement

Le code source d’OpenBlox est hébergé à l’adresse [git.openblox.org](https://git.openblox.org). Vous aurez besoin du logiciel de gestion de versions Git. Vous pouvez choisir un des dépôts dans la liste présente sur git.openblox.org et utiliser la commande `git clone` pour cloner le dépôt en utilisant une des adresses données. Par exemple, pour cloner le dépôt pour le moteur de jeu, vous pourriez exécuter `git clone https://git.openblox.org/openblox/libopenblox.git`.

Cela créera un répertoire contenant le code source dans lequel vous pourrez apporter des modifications, les ajouter à l’index et les valider. Si vous n’êtes pas familier avec Git, vous pouvez voir le tutoriel Git avec la commande `git help tutorial`, ou vous pouvez voir le [tutoriel Git](https://www.kernel.org/pub/software/scm/git/docs/gittutorial.html) et le [Manuel de l’utilisateur de Git](https://www.kernel.org/pub/software/scm/git/docs/user-manual.html) dans un navigateur Web. Après avoir apporté des modifications, vous devrez compiler OpenBlox pour les tester. Ceci est fait avec la commande `make all` après l’installation des dépendances.

Une fois que vous avez validé des modifications que vous voudriez soumettre pour révision, exécutez <code>git format-patch -&#8208;to=devel@lists.openblox.org <var>commit</var></code>. Git va générer un patch pour chaque modification effectuée après (et incluant) celle désignée par <var>commit</var>, qui peut être le hash de commit, `HEAD ~1` pour la modification précédente, `HEAD~2` pour la modification avant cette modification, et ainsi de suite, ou `origin/master` si vous voulez inclure toutes les modifications ajoutées à votre dépôt local. La commande vous donnera le nom des fichiers patch créés. Envoyez ces messages par courrier électronique à [devel@lists.openblox.org](mailto:devel@lists.openblox.org) pour révision, en gardant le sujet et le contenu du message généré par Git. Vous pouvez utiliser n’importe quel client de courrier électronique, mais nous vous recommandons d’utiliser `git send-email` (voir `git help send-email`), que vous pouvez obtenir sur Debian et Fedora à partir du paquet `git-email`. Vous pouvez ajouter un message d’introduction avec l’option `--compose`, ce qui est souhaitable pour les correctifs non triviaux.
