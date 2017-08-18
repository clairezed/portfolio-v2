# Portfolio v2

## How to use

La config globale, commune à tous les environnements de développement, se trouve dans `_config.yml`. C'est la config qui est utilisée automatiquement par les pages github en production, on y trouve donc aussi les éléments de configuration propres à la production.

Dans `_config.dev.yml` ne figurent **que** les éléments spécifiques au développement local. Ainsi, en lançant la commande ci-dessous, c'est comme lancer le fichier `_config.yml`, mais avec les éléments spécifiques de `_config.dev.yml`.

### Développement

Lancer le serveur :
```bash
bundle exec jekyll serve --config _config.yml,_config.dev.yml
```
Votre site est visible sur [localhost:4000](localhost:4000)

## Les spécificités

- Un dossier pour les pages, que je n'aime pas voir traîner (`_pages`). Du coup, ne pas oublier de mettre le permalink dans le frontmatter.
- un fichier de `_config` par environnement


## Ressources

### Netlify

- [CMS](https://www.netlifycms.org/)
- [Netlify docs](https://www.netlify.com/docs/)

## Theme

**Forty - Jekyll Theme** : A Jekyll version of the "Forty" theme by [HTML5 UP](https://html5up.net/), jekyllized by [Andrew Banchich](https://github.com/andrewbanchich/forty-jekyll-theme) ([licence](https://github.com/andrewbanchich/forty-jekyll-theme/blob/master/LICENSE.md))


Original README from HTML5 UP:

```
Forty by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


This is Forty, my latest and greatest addition to HTML5 UP and, per its incredibly
creative name, my 40th (woohoo)! It's built around a grid of "image tiles" that are
set up to smoothly transition to secondary landing pages (for which a separate page
template is provided), and includes a number of neat effects (check out the menu!),
extra features, and all the usual stuff you'd expect. Hope you dig it!

Demo images* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images
you can use for pretty much whatever.

(* = not included)

AJ
aj@lkn.io | @ajlkn


Credits:

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fortawesome.github.com/Font-Awesome)

	Other:
		jQuery (jquery.com)
		html5shiv.js (@afarkas @jdalton @jon_neal @rem)
		background-size polyfill (github.com/louisremi)
		Misc. Sass functions (@HugoGiraudel)
		Respond.js (j.mp/respondjs)
		Skel (skel.io)
```
