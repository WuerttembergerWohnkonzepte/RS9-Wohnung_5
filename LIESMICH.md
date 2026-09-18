# Tulpenstrasse 15, Sindelfingen, Wohnung Nr. 5

Neu aufgebaut nach dem Muster der Index-Vorlage.

## Was in diesem Ordner liegt

    index.html          das Expose, rund 4,1 MB
    bilder/             21 Bilddateien, als Sicherung
    unterlagen/         11 PDF, ueber die Downloadkarten verlinkt

Alle Bilder stecken als Base64 direkt in der index.html, genau wie in
der Index-Vorlage. Der Ordner "bilder" wird von der Seite nicht mehr
gebraucht; er liegt nur als Sicherung dabei, falls einzelne Fotos
getauscht werden sollen.

Der Ordner "unterlagen" wird dagegen gebraucht. Fehlt er, gehen die
Downloads ins Leere.

## Was gegenueber der alten Fassung anders ist

Nach dem Muster der Index-Vorlage entfernt:

    Kapitelnavigation unter der Kopfzeile
    Vertrauensband unter dem Hero (5,0 Sterne, 30+, 0 Euro Provision)
    Logo in Kopfzeile und Fusszeile
    A4-Drucklayout; es gilt jetzt der Druckstand der Vorlage

Der Abschnitt "Ablauf" mit den neun Schritten ist wieder drin, als
Kapitel 10, Kontakt ist Kapitel 11.

Zinsregler: Standard 5,00 Prozent, Bereich 4,50 bis 5,50 Prozent.
Kostenrahmen Renovierung: 11.830 Euro netto, 14.078 Euro brutto,
mit Einbaukueche (3.500 Euro) rund 17.600 Euro. Amortisation aus der Mehrmiete
nach gut drei Jahren statt zweieinhalb.

Neu eingesetzt:

    Sieben Fotos der baugleichen, spiegelbildlichen Dachgeschosswohnung
    nach der Renovierung, in Abschnitt 07: vier Wohnraeume,
    dazu Kueche, Bad und Balkon

Nebenbei korrigiert: In den Kontakt- und Finanzierungslinks sowie im
Namen der ZIP-Datei stand bisher "Wohnung Nr. 2".

## Noch offen

Auf dem Kuechenbild ist keine Einbaukueche montiert, der Text nennt aber
eine neue Einbaukueche fuer 3.500 Euro. Bitte pruefen, ob das Bild vor dem
Einbau entstanden ist.

Fuer den Umbau der Sitzbadewanne zur Dusche sind 3.000 Euro netto
angesetzt. Dafuer liegt kein Angebot vor, der Betrag ist geschaetzt und
in der Bildunterschrift als solcher gekennzeichnet.

Der Link zum Webexpose in der Finanzierungsmail steht auf

    https://wuerttembergerwohnkonzepte.github.io/TS15-Wohnung_5/

Diese Adresse ist nach dem Muster von Wohnung 2 gebildet und nicht
geprueft. Sie steht in der index.html in der Zeile

    var EXPOSE_URL = "...";

## Hochladen

Ein eigenes Repository fuer diese Wohnung anlegen. Dann auf
"Add file", danach "Upload files", und in das Fenster ziehen:

    index.html
    unterlagen        (der ganze Ordner)

Der Ordner "bilder" muss nicht mit hoch. Die index.html muss im
Repository ganz oben liegen.

## Pages einschalten

Settings, dann Pages. Bei Source "Deploy from a branch" waehlen,
Branch `main`, Ordner `/ (root)`. Speichern. Der erste Aufbau dauert
ein bis zwei Minuten.

## Falls der Unterlagenordner anders heissen soll

In der index.html steht im Skript genau eine Zeile:

    var DOKBASE='unterlagen/';

Nur diese aendern. Der Schraegstrich am Ende muss bleiben.

## Nicht enthalten, mit Absicht

Grundbuchauszug, Restnutzungsdauergutachten und Mietvertrag liegen nicht
in "unterlagen". Sie enthalten personenbezogene Daten. Auf GitHub Pages
ist jede Datei im Repository oeffentlich abrufbar, auch wenn sie auf der
Seite nicht verlinkt ist. Im Expose steht deshalb, dass diese Unterlagen
bei ernsthaftem Kaufinteresse nachgereicht werden.

## Hinweis zum Oeffnen von der Festplatte

Per Doppelklick erscheint die Seite vollstaendig, weil die Bilder in der
Datei stecken. Die Downloads der Unterlagen funktionieren dort je nach
Browsereinstellung nicht. Auf der veroeffentlichten Seite greift alles.
