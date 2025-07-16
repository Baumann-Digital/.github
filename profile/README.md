# Baumann-Digital
Dokumentation zu Baumann-Digital (Onlineportal, Datenstruktur/-schemata)


<div align="center"> 
 
**[Online-Portal (Sitemap)](#online-portal-sitemap) • 
[Kataloge](#kataloge) • 
[Datenstrukturen](#datenstrukturen)**

</div>

# Online-Portal (Sitemap)
Mit dieser Dokummentation wird die Stuktur des Onlineportals dargestellt

## Startseite
Landing Page mit Zugang zu den Katalogen (Kacheln), einer Timeline des Projekts und einer Kontaktmöglichkeit.

## Ludwig Baumann
Sehr kurze biografische Skizze zu Ludwig Baumann

## Kataloge
Die Daten sind in Katalogen organisiert.
Kataloge sind hier Sammlungen von Datensätzen (i.e. Register)

### Werke
In dieser Kategorie sind Datensätze zu den Werken Ludwig Baumanns erfasst.
Bei den Datensätzen zu den Werken handelt es sich um MEI-Dateien, welche die Werke allgemein beschreiben (Metadaten).
Sie sind als MEI-Fragmente codiert, beginnen mit dem Element `<work>` und folgen dem XML-Schema `baudi_mei` ([kompiliertes RNG](https://github.com/Baumann-Digital/baudi-odd/blob/develop/rng/baudi_mei.rng "BauDI MEI RNG"), [ODD-file](https://github.com/Baumann-Digital/baudi-odd/blob/develop/odd/baudi_mei.odd "BauDi MEI ODD file")). 

### Quellen
In dieser Kategorie sind die Quellen zu den Werke Ludwig Baumanns erfasst.
Bei den Datensätzen zu den (musikalischen Quellen) handelt es sich um MEI-Dateien, welche die Quellen allgemein beschreiben (Metadaten).
Sie beginnen mit dem Element `<mei>` und folgen dem XML-Schema `baudi_mei` ([kompiliertes RNG](https://github.com/Baumann-Digital/baudi-odd/blob/develop/rng/baudi_mei.rng "BauDI MEI RNG"), [ODD-file](https://github.com/Baumann-Digital/baudi-odd/blob/develop/odd/baudi_mei.odd "BauDi MEI ODD file")). 

### Editionen
In dieser Kategorie sind Editionen von Werken von Ludwig Baumanns verzeichnet.

### Personen
In dieser Kategorie sind Personen aus dem Umfeld Baumanns und seiner Werke verzeichent.
Bei den Datensätzen zu den Werken handelt es sich um TEI-Dateien, welche einen Referenzdatensatz für das Portal darstellen.
Sie sind als TEI-Fragmente codiert, beginnen mit dem Element `<person>` und folgen dem XML-Schema `baudi_tei` ([kompiliertes RNG](https://github.com/Baumann-Digital/baudi-odd/blob/develop/rng/baudi_tei.rng "BauDI TEI RNG"), [ODD-file](https://github.com/Baumann-Digital/baudi-odd/blob/develop/odd/baudi_tei.odd "BauDi TEI ODD file")). 

### Institutionen
In dieser Kategorie sind Institutionen aus dem Umfeld Baumanns und seiner Werke verzeichent.
Bei den Datensätzen zu den Institutionen handelt es sich um TEI-Dateien, welche einen Referenzdatensatz für das Portal darstellen.
Sie sind als TEI-Fragmente codiert, beginnen mit dem Element `<org>` und folgen dem XML-Schema `baudi_tei` ([kompiliertes RNG](https://github.com/Baumann-Digital/baudi-odd/blob/develop/rng/baudi_tei.rng "BauDI TEI RNG"), [ODD-file](https://github.com/Baumann-Digital/baudi-odd/blob/develop/odd/baudi_tei.odd "BauDi TEI ODD file")).

### Orte
In dieser Kategorie sind Orte verzeichnet, die im Kontext von Baumann's Leben und Wirken relevant sind.
Bei den Datensätzen zu den Orten handelt es sich um TEI-Dateien, welche einen Referenzdatensatz für das Portal darstellen.
Sie sind als TEI-Fragmente codiert, beginnen mit dem Element `<place>` und folgen dem XML-Schema `baudi_tei` ([kompiliertes RNG](https://github.com/Baumann-Digital/baudi-odd/blob/develop/rng/baudi_tei.rng "BauDI TEI RNG"), [ODD-file](https://github.com/Baumann-Digital/baudi-odd/blob/develop/odd/baudi_tei.odd "BauDi TEI ODD file")).

## Über das Projekt
### BauDi
Projektbeschreibung

### Impressum
Impressum zur Webseite.

# Datenstrukturen
Die Datenschemata basieren auf TEI und MEI. Auch der crApp basiert im wesentlichen auf MEI.

## Werke
tbc., Beispiel + Link zu Schema

## Quellen
tbc., Beispiel + Link zu Schema

## Editionen
tbc., Beispiel + Link zu Schema

## Personen
tbc., Beispiel + Link zu Schema

## Institutionen
tbc., Beispiel + Link zu Schema

## Orte
tbc., Beispiel + Link zu Schema
