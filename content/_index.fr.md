OpenBlox est un moteur de jeu libre et fiable qui est assez simple pour être utilisé par les débutants à la programmation, mais suffisamment puissant pour répondre aux besoins des développeurs plus sérieux. Il fournit une interface de programmation en Lua pour permettre aux développeurs de créer des jeux facilement et avec peu de restrictions. Ceci est le site officiel du projet OpenBlox. Les serveurs fournissant l’infrastructure et les services utilisés par le projet OpenBlox, collectivement appelés [OBNet]({{< relref "obnet.md" >}}), sont également utilisés pour héberger [un certain nombre d’autres projets](https://friends.openblox.org/).

Il est important de noter que le «&nbsp;Open&nbsp;» dans le nom OpenBlox ne fait pas référence à l’<i lang="en">open source</i>, mais plutôt au potentiel du moteur OpenBlox. Notre objectif est de fournir un moteur de jeu libre, et non de promouvoir un logiciel <i lang="en">open source</i>. Le moteur de jeu OpenBlox est lui-même sous la [licence publique générale GNU amoindrie](https://www.gnu.org/licenses/lgpl-3.0.fr.html), version&nbsp;3 ou ultérieure. Les implémentations de clients et de serveurs de référence, ainsi que le logiciel de studio, sont sous [licence publique générale GNU](https://www.gnu.org/licenses/gpl-3.0.fr.html), version&nbsp;3 ou ultérieure.

OpenBlox a besoin de votre aide&#8239;! Si vous êtes un programmeur et souhaitez contribuer, consultez [nos instructions]({{< relref "contributing.fr.md" >}}) pour obtenir le code source et envoyer des améliorations.

## Objectifs

L’objectif du projet OpenBlox est de créer un moteur de jeu entièrement libre qui fournit des composants de base pour créer des jeux simples joués dans un espace virtuel 3D. Nous voulons que le moteur de jeu mette en œuvre la physique et le rendu et offre des objets qui implémentent des personnages, des objets physiques, des interfaces graphiques, du terrain, des effets de particules et des véhicules, et nous voulons qu’il fournisse des objets pour changer l’éclairage du jeu, envoyer des demandes réseau, jouer des sons, obtenir l’entrée de la souris et du clavier et faire beaucoup plus encore.

Quelques principes directeurs sont à la base de nos objectifs&nbsp;:

* vous ne devriez pas avoir à implémenter des choses compliquées comme le rendu, la physique et la mise en réseau multijoueurs&#8239;;
* au lieu de cela, le moteur de jeu devrait vous fournir des composants que vous pouvez utiliser pour créer des jeux&#8239;;
* les composants doivent être assez généraux pour ne pas restreindre l’étendue des jeux que vous pouvez créer&#8239;;
* le moteur devrait être entièrement libre et gratuit et être disponible sur tous les principaux systèmes d’exploitation (Microsoft Windows, macOS, GNU/Linux, Android et iOS)&#8239;;
* il devrait être facile à apprendre.

## Obtenir

Nous ne fournissons pas de fichiers exécutables pour OpenBlox en ce moment. Vous pouvez télécharger le code source depuis [git.openblox.org](https://git.openblox.org) et le compiler. Vous devrez d’abord installer les dépendances.

## Création de jeux

OpenBlox utilise le langage de programmation Lua. Il fournit une interface de script similaire à celle de Roblox et tente de rester compatible tout en améliorant les choses qui peuvent être améliorées.

### Documentation

OpenBlox utilise Doxygen pour documenter l’interface C++. La documentation de la dernière version est disponible [sur le serveur Jenkins](https://ci.openblox.org/job/libopenblox/doxygen/index.html).

La documentation de l’interface Lua se trouve actuellement [sur notre wiki](https://wiki.openblox.org/wiki/Project:Home).

### Support

Nous ne fournissons pas de support professionnel pour OpenBlox. Toutefois, si vous souhaitez obtenir de l’aide, vous pouvez vous connecter au réseau IRC freenode et demander de l’aide dans [le canal #OpenBlox](ircs://chat.freenode.net/OpenBlox).

## Dons

Le projet OpenBlox accepte actuellement des dons en bitcoin, litecoin et par PayPal. Vous pouvez trouver nos [adresses actuelles](/donate.asc) signées par le chef de projet. Bien que les contributions monétaires aident à maintenir nos serveurs en marche, il existe d’autres façons d’aider le projet. Nous recherchons toujours de nouveaux contributeurs, afin de maintenir OpenBlox fort.
