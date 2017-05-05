Ulysses
=======

![Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License](https://i.creativecommons.org/l/by-nc-sa/3.0/88x31.png "Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License")

This repo contains a **defunct attempt at creating a** reliable digital text of James Joyce's novel *Ulysses* built off the Creative Commons licensed plaintext transcription of the 1922 first printing of Ulysses by **Matthew Kochis** and **Patrick Belk** with the **[Modernist Versions Project] (http://web.uvic.ca/~mvp1922/)**; **Amanda Visconti** has added OCR transcription-error corrections, regex formatting replacements, and HTML/CSS for important typographical choices used in the 1922 first printing of the novel (as verified against the Modernist Versions Project's digital images of the printing); she has also created importable CSVs and .export files so that others can easily import the text into any website or as indivdiual book pages into a Drupal book. This is the text used in the **[InfiniteUlysses.com](http://www.InfiniteUlysses.com)** digital edition of *Ulysses*.

**NOTE**: I'm finding formatting changes and corrections as I annotate these chapters that aren't in the CSVs/.exports yet; notably, italics and cerntering of song lyrics are missing. Chapters 1-4 on the site have all been proofed (and italics/centering/otehr formating added). I've been editing those pages as I read through them; the original plan was to list every change I make to the MVP transcription in this repo and on the digital edition, but that proved too time consuming. Instead, when I've finishe proofing the novel I will collate the resulting text against the original MVP text and post all changes at that point.

## CSVs
Used to bulk-import pages of a given Ulysses episode (chapter). Contain formatting (e.g. dialogue indentations) but not typography (e.g. italicizations, centering, some all-caps). Will update here with import instructions eventually.
- [x] Episode 1, Telemachus
- [x] Episode 2, Nestor
- [x] Episode 3, Proteus
- [x] Episode 4, Calypso
- [x] Episode 5, Lotus Eaters
- [x] Episode 6, Hades
- [x] Episode 7, Aeolus
- [x] Episode 8, Lestrygonians
- [x] Episode 9, Scylla and Charybdis
- [x] Episode 10, Wandering Rocks
- [x] Episode 11, Sirens
- [x] Episode 12, Cyclops
- [x] Episode 13, Nausicaa
- [x] Episode 14, Oxen of the Sun
- [x] Episode 15, Circe
- [x] Episode 16, Eumaeus
- [x] Episode 17, Ithaca
- [x] Episode 18, Penelope

## .Export Files
Used to bulk-import pages of a given Ulysses episode. Contain formatting (e.g. dialogue indentations) and typography (e.g. italicizations, centering, all-caps). Will update here with import instructions eventually; I believe you can just use the Node Export module on a Drupal site.
- [x] Episode 1, Telemachus
- [x] Episode 2, Nestor
- [ ] Episode 3, Proteus (available, need to add to repo)
- [ ] Episode 4, Calypso (available, need to add to repo)
- [ ] Episode 5, Lotus Eaters
- [ ] Episode 6, Hades
- [ ] Episode 7, Aeolus
- [ ] Episode 8, Lestrygonians
- [ ] Episode 9, Scylla and Charybdis
- [ ] Episode 10, Wandering Rocks
- [ ] Episode 11, Sirens
- [ ] Episode 12, Cyclops
- [ ] Episode 13, Nausicaa
- [ ] Episode 14, Oxen of the Sun
- [ ] Episode 15, Circe
- [ ] Episode 16, Eumaeus
- [ ] Episode 17, Ithaca
- [ ] Episode 18, Penelope

#Licensing
This repo is **licensed [CC BY SA](https://creativecommons.org/licenses/by-nc-sa/3.0/)** in accordance with the CC BY SA license placed on the Modernist Versions Project text. You can read more about the Modernist Versions Project at [http://web.uvic.ca/~mvp1922](http://web.uvic.ca/~mvp1922/). 

The Modernist Versions Project prepends the following notice to their digital transcription:
*"This material has been reproduced and made available on this site based on its public domain status in Canada. By viewing these materials, you acknowledge that it is your responsibility to comply with the laws of your jurisdiction, particularly copyright (where applicable). The Modernist Versions Project accepts no liability or responsibility for the manner in which the material is used by others or the results of such use. As this digital object contains certain embedded technical functionality, individuals interested in reproducing this digital object in a publication or web site or for any commercial purpose must first receive permission from the Modernist Versions Project."*
