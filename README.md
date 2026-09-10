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

Les textes intégraux des licences sont dans `licences/`.

## Ce qui n'est pas encore ici

**L'allemand et l'italien**, et pour deux raisons différentes :

- le dictionnaire allemand réunit des lemmes sous **ODbL** et des prononciations
  du Wiktionnaire sous **CC BY-SA**. Les deux clauses de partage à l'identique se
  contredisent, et aucune licence unique ne les satisfait toutes les deux. Tant
  que ce n'est pas tranché, publier ce fichier reviendrait à le distribuer sous
  des conditions qu'on ne sait pas énoncer ;
- le dictionnaire italien dérive de **PhonItalia 1.10**, dont la licence n'est
  pas établie : le site d'origine est hors ligne et l'article de 2014 dit
  seulement « freely available ». On ne republie pas ce qu'on n'a pas le droit
  de republier.

Les deux arriveront ici quand ces points seront réglés.

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
