# Sujet

## Qu'est-ce que c'est ?

Générateur de sites web statiques.

## Pourquoi ?

Élimine le **JavaScript** du côté client, donc produit des sites web performant, tout en permettant d'utiliser le *framework* de son choix du côté serveur.

## Exemple

Installer Astro :

`npm install astro`

Créer un projet Astro :

`npm create astro@latest`

## Forces

- Simple
- Site performant

## Limites

- Pas pour des sites complexes avec de nombreuses interactions.

## Ressources

- [Astro](https://astro.build/)
- [Doc](https://docs.astro.build/en/getting-started/)
- [Essayer](https://astro.new/)
- [En 100 secondes](https://www.youtube.com/watch?v=dsTXcSeAZq8&ab_channel=Fireship)
- [Gallerie](https://astro.build/showcase/)

## Problèmes rencontrés :

- Node.js version 12 requise
	- :boomerang: Node.js version 10 dans les packages par défaut.
	- :adhesive_bandage: Utilisé [une autre source de packages](https://computingforgeeks.com/how-to-install-nodejs-on-ubuntu-debian-linux-mint/)
-  `UnhandledPromiseRejectionWarningSy` à l'initialisation d'un projet.
	- Quelqu'un a créé [un ticket similaire](https://github.com/withastro/astro/issues/1115) :boomerang: <sub>Échec</sub>
	- Essayé `npm create astro`  :boomerang: <sub>Échec</sub>
	- Désinstallé Astro et réinstallé avec Node.js 12 :boomerang: <sub>Échec</sub>
	- 