# Les dictionnaires dérivés de Rimble

Ce dépôt existe pour une raison précise : les dictionnaires de [Rimble](https://jasspym.github.io/rimble-legal/)
sont construits à partir de bases lexicales ouvertes, et **leurs licences imposent
que la base dérivée soit republiée, lisible, sous la même licence.**

Une application de l'App Store est chiffrée : personne ne pourrait exercer ces
droits sur un fichier enfermé dedans. Ces fichiers-ci sont donc la version
libre, en clair, de ce que le jeu embarque.

**Il n'y a pas une licence, il y en a une par langue.** Chaque fichier porte la
sienne dans son propre champ `licence`, avec sa `notice` d'attribution et la
liste de ses `modifications`.

| Fichier | Sources | Licence |
|---|---|---|
| `lexique-rimble.json` | Lexique 3.82 (New & Pallier) | CC BY-SA 4.0 |
| `lexique-rimble-es.json` | lemmes michmech · fréquences OpenSubtitles | ODbL 1.0 |
| `lexique-rimble-pt.json` | lemmes michmech · fréquences OpenSubtitles | ODbL 1.0 |
| `lexique-rimble-en.json` | CMUdict · lemmes michmech · fréquences OpenSubtitles | ODbL 1.0 |
| `lexique-rimble-de.json` | Wiktionnaire allemand via kaikki.org · fréquences OpenSubtitles | CC BY-SA 4.0 |

Les textes intégraux des licences sont dans `licences/`.

## L'italien n'est plus au catalogue

Sa phonologie venait de **PhonItalia 1.10**, distribué sous *Creative Commons
Attribution – NonCommercial – ShareAlike 3.0*. La page d'origine, retrouvée dans
les archives du web parce que le site est mort, précise que « PhonItalia et
toutes les bases dérivées sont librement disponibles pour un usage de recherche
non commercial ».

La clause vise donc exactement ce qu'un jeu payant en ferait. L'italien a été
retiré de Rimble et sa base dérivée de ce dépôt. Elle reviendra le jour où elle
sera reconstruite depuis une source qui ne l'interdit pas — le Wiktionnaire
italien, comme l'allemand.

## Ce que ces fichiers contiennent

Aucun mot n'a été ajouté à aucune source. Pour chaque langue : les formes
retenues, groupées par famille de rimes, avec l'étiquette affichée par le jeu,
un niveau de difficulté et un drapeau « mot courant ». La rime est **calculée**
depuis la colonne phonémique de la source, jamais depuis l'orthographe.

Les colonnes des sources dont le jeu ne se sert pas ne sont pas reproduites.

## Attributions

**Lexique** — base de données lexicales du français, Boris New & Christophe
Pallier, <https://www.lexique.org>, sous CC BY-SA 4.0. Le dictionnaire français
de Rimble en est une adaptation modifiée. Fourni en l'état, sans garantie.

**Lemmatization Lists** — Michal Boleslav Měchura, sous Open Database License
(ODbL) 1.0. *Contains information from lemmatization-lists, which is made
available under the ODbL.*

**CMU Pronouncing Dictionary** — Copyright (C) 1993-2015 Carnegie Mellon
University. All rights reserved. Redistribué selon les termes de la licence BSD
à deux clauses, reproduite dans `licences/BSD-2-cmudict.txt`.

**FrequencyWords** — Hermit Dave, dérivé du corpus OpenSubtitles, sous licence
MIT. Copyright (c) 2016 Hermit Dave.

---

Une question : <contact@jasspym.com>
