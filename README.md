# homepage redesign der StuVe-Hompage

**Aktuell:** erste Vorschläge, Entwürfe, Machbarkeit (Uni-Typo3 weiterhin als CMS)

**Federführung:** Öffentlichkeitsreferat

**Vorschau** für den aktuellen Entwurf: http://stuve.github.io/homepage-redesign/

## Vorgehen

1) Die Startseite wurde einfach mal mit Firefox Datei > Speichern unter… (Komplette Webseite) gespeichert. Das CSS sah dann so aus:
```Shell
% wc -l index_files/*.css
   176 index_files/jquery-ui.css
  1307 index_files/merged-59048ffc5447b047b2f1ebf3e60b6a45-2e99828edfbaaa06b98f.css
    55 index_files/powermailDateTimePicker-52c4ee0d634bb969d854e14299d850dc00f6.css
    31 index_files/print_003-5d0d10c4f8fe6544cf7bb48133c82cde7ab9.css
    41 index_files/socialwidgets.css
    20 index_files/styles.css
   465 index_files/ui.css
  2095 total
```

2) Mit [Atoms](https://atom.io/) [atom-beautify](https://atom.io/packages/atom-beautify) ~~dem online Tool ~~[Tabifier](http://tools.arantius.com/tabifier)~~ die CSS-Dateien schöner gemacht. Resultat:
```Shell
% wc -l index_files/*.css
   216 index_files/jquery-ui.css
  5349 index_files/merged-59048ffc5447b047b2f1ebf3e60b6a45-2e99828edfbaaa06b98f.css
   298 index_files/powermailDateTimePicker-52c4ee0d634bb969d854e14299d850dc.css
   119 index_files/print_003-5d0d10c4f8fe6544cf7bb48133c82cde.css
    40 index_files/socialwidgets.css
    72 index_files/styles.css
  1546 index_files/ui.css
  7640 total
```
