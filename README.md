# End of 10 Präsentation

Präsentation für die [End of 10 Veranstaltungsreihe](https://erfindergeist.org/2025/09/30/end-of-10-veranstaltungsreihe-umstieg-auf-linux/) des Erfindergeist Jülich e.V.

Die Präsentation wird mit quarto und revealjs erstellt (https://prerelease.quarto.org/docs/presentations/revealjs/).

## Bauen und ausführen
* [Quarto](https://quarto.org/) installieren
* Die Präsentation bauen `quarto render index.md`
* Das resultierenden `index.html` im Browser öffnen
* Synchronisieren auf den Server `rsync -ravh  img index.html index_files root@erfindergeist-headscale:/var/www/html/endof10/`
