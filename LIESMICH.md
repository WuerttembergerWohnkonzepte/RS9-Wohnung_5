# Roseggerstrasse 9, Kirchheim unter Teck, Wohnung Nr. 5 (2. OG links)

## Was in diesem Ordner liegt

    index.html          das Expose
    bilder/             18 Bilddateien, vom Expose eingebunden
    unterlagen/         18 PDF, ueber die Downloadkarten verlinkt

Alle drei muessen beieinander bleiben. Fehlt "bilder", zeigt die Seite
keine Fotos. Fehlt "unterlagen", laufen die Downloads ins Leere.

Zusaetzlich liegt eine Stufe hoeher die Datei
`Vorschau_Roseggerstrasse-9_Wohnung-5.html`. Darin sind alle Bilder
eingebettet, sie laesst sich per Doppelklick oeffnen und weitergeben.
Die Downloadkarten funktionieren dort nicht, weil der Ordner
"unterlagen" fehlt. Die Vorschau ist nur zum Gegenlesen,
veroeffentlicht wird der Ordner.

Aufgebaut ist das Expose auf der Fassung der Wohnung Nr. 3
(1. OG links). Struktur, Gestaltung, Rechner und rechtliche Hinweise
sind unveraendert, geaendert wurden die objektbezogenen Zahlen und
Texte.

## VOR DER VEROEFFENTLICHUNG UNBEDINGT ERLEDIGEN

1. **Nettokaltmiete klaeren. Das ist der wichtigste Punkt.**
   Das Expose rechnet durchgehend mit **515 EUR**, so steht es in
   "2. Og Links.xlsx", Zelle J10.

   In den Unterlagen liegt aber das Mieterhoehungsschreiben vom
   31.03.2025. Darin nennt der Voreigentuemer 522 EUR als damals
   gezahlte Miete und verlangt eine Anhebung auf **615 EUR ab dem
   01.07.2025**. Eine Zustimmung des Mieters liegt dem Paket nicht bei.
   Die Wohnungsgroesse ist in dem Schreiben mit "ca. 65 qm" ausserdem
   falsch angegeben, richtig sind 56,80 m2.

   Gilt tatsaechlich ein anderer Betrag als 515 EUR, aendern sich:
   Miete und Miete je m2 in Kapitel 02 und 03, die Mietluecke und die
   Marktmiete in Kapitel 03, die Monatsrechnung und der Steuerkasten in
   Kapitel 06, der Satz der Sondereigentumsverwaltung in Kapitel 04
   und 05 sowie `miete` im Rechenmodell. Bitte in dem Fall kurz
   Bescheid geben, dann ziehe ich es sauber durch.

2. **Bodenwert: 36.567 EUR statt 35.567 EUR.**
   Die Herleitung der Kaufpreisaufteilung rechnet
   390,00 m2 x 132,06/1.000 = 51,5034 m2, mal 710 EUR Bodenrichtwert,
   also 36.567 EUR. In der Excel stehen in Zelle J26 dagegen
   35.567 EUR, das sieht nach einem Zahlendreher aus. Das Expose
   verwendet den Wert aus der Herleitung, weil er nachrechenbar ist.

   Folge: Abschreibungsbasis 165.663 EUR statt 166.663 EUR,
   Abschreibung 8.719 EUR im Jahr statt 8.772 EUR, Gebaeudeanteil
   81,92 Prozent. Das Expose rechnet damit einen Tick vorsichtiger als
   die Excel. Soll es andersherum sein, ist es eine Zahl im
   Rechenmodell (`geb`) und der Kasten "Woher die 8.719 EUR
   Abschreibung kommen" in Kapitel 06.

3. **Angesetzte Marktmiete: 850 EUR.**
   Hergeleitet aus der modernisierten Nr. 1 im Erdgeschoss links, dort
   1.000 EUR auf 63,90 m2, also 15,65 EUR je m2. Auf 56,80 m2
   uebertragen waeren das 889 EUR, angesetzt wird bewusst darunter,
   weil die Wohnung unter dem Dach liegt.

   Besser waere die Nr. 6 im zweiten Obergeschoss rechts. Sie wurde
   2026 ebenfalls modernisiert, liegt auf derselben Etage und hat
   dieselben Dachschraegen. Wenn du weisst, zu welcher Miete sie
   vermietet ist, ist das die staerkere Vergleichszahl und ich tausche
   sie aus.

4. **Kapitel 07 zeigt Bilder der Nr. 1 im Erdgeschoss.**
   Aufnahmen der modernisierten Nr. 6 (2. OG rechts) lagen nicht bei.
   Die Bildunterschrift stellt deshalb klar, dass die Nr. 1 im
   Erdgeschoss liegt und keine Dachschraegen hat. Kommen Fotos der
   Nr. 6, sind sie der bessere Beleg, weil sie den Zustand nach der
   Modernisierung unter denselben Schraegen zeigen.

5. **Foto des dritten Zimmers fehlt.** Der Bildstreifen zeigt Garten,
   Flur, Bad, WC, Aussenansicht, Wohnen und Essen, Kueche und
   Schlafzimmer. Vom dritten Zimmer (KINDER, 8,19 m2 angerechnet) gibt
   es keine Aufnahme. Der Platz dafuer ist frei gehalten: Kommt eine
   dazu, als `bilder/07_kinderzimmer.jpg` ablegen und im Kapitel 02
   eine Zeile in den Bildstreifen einfuegen, hinter
   `06_schlafzimmer.jpg`, das ist die letzte Zeile des Streifens:

       <figure><img src="bilder/07_kinderzimmer.jpg" alt="Drittes Zimmer der Wohnung Nr. 5" decoding="async"></figure>

6. **Kueche pruefen.** Auf der Aufnahme ist eine eingebaute Kueche mit
   Unter- und Oberschraenken, Arbeitsplatte, Backofen und Dunstabzug zu
   sehen. Ob sie zum Verkauf gehoert oder dem Mieter, geht aus den
   Unterlagen nicht hervor, im Mietvertrag von 1998 ist nur "Kueche mit
   Herd" angekreuzt. Das Expose behauptet deshalb keine Einbaukueche,
   sondern nennt nur "Kueche als eigener Raum mit Fenster". Gehoert sie
   mit dazu, laesst sich das in Kapitel 02 unter "Ausstattung und
   Zustand" ergaenzen, das ist ein echtes Verkaufsargument.

7. **Adresse der veroeffentlichten Seite.** Eingetragen ist
   `https://wuerttembergerwohnkonzepte.github.io/RS9-Wohnung_5/`. Falls
   die Seite spaeter unter einer anderen Adresse liegt, in der
   index.html die Zeile `var EXPOSE_URL = ...` anpassen, sonst zeigt
   die vorbereitete Mail an die Moeglichmacher auf die falsche Seite.

8. **GEAENDERTE SUMME DER MIETSUBVENTION: 9.920 EUR statt 8.060 EUR.**
   Die Staffelung haengt jetzt an der Mieterhoehung im April 2027 und
   laeuft in Dreijahresstufen weiter. Dadurch stehen die Stufen laenger
   als in der Kalkulation, die Einzelbetraege sind unveraendert. Der
   Unterschied von 1.860 EUR ist eine kaufmaennische Entscheidung, keine
   Rechenfrage. Entweder wird die Kalkulation auf 9.920 EUR angehoben,
   oder die Stufen im Expose werden gekuerzt. Solange das nicht
   entschieden ist, weichen Expose und Kalkulation hier voneinander ab.
   Die Aufstellung steht weiter unten.

9. **Herleitung der Kaufpreisaufteilung vervollstaendigen.** Die Datei
   geht nicht in den oeffentlichen Ordner, muss vor der Beurkundung
   aber gefuellt werden. Offen sind: "zweites Obergeschoss [bitte
   ergaenzen: links oder rechts]" ist links, der Kaufpreis fehlt
   (189.000 EUR), Gebaeudeanteil und Prozentwerte sind offen
   (152.433 EUR und 80,65 Prozent bezogen auf den Kaufpreis, im Expose
   wird mit 165.663 EUR und 81,92 Prozent bezogen auf die
   Gesamtinvestition gerechnet), der Hinweis zum Abstellraum SNR 5 ist
   gegen die Teilungserklaerung zu pruefen, und der Absatz zur
   Vermietungssituation ist leer. Fuer den letzten Punkt:
   Nettokaltmiete 515 EUR, Mietverhaeltnis seit 01.09.1998, Miete
   deutlich unter der ortsueblichen Vergleichsmiete, dadurch
   eingeschraenkte Nutzbarkeit.

10. **Entfernungen im Kapitel Lage pruefen.** Die Geh- und Fahrzeiten
    sind aus dem Expose der Nr. 3 uebernommen und gerundet.

11. **Kosten im Kapitel 07.** Ausgewiesen sind die tatsaechlich
    abgerechneten 12.489 EUR brutto fuer die Wohnung Nr. 1, wie im
    Expose der Nr. 3. Fuer die Nr. 5 liegt kein Angebot vor, das steht
    so auch im Text. Die Nr. 1 liegt im Erdgeschoss und hat keine
    Dachschraegen, bei den Fenstern unter den Gauben kann der Preis
    abweichen.

## Zahlengrundlage im Expose

Alle Werte stammen aus "2. Og Links.xlsx", Blatt Kalkulation, sowie
aus den Unterlagen dieser Einheit.

    Kaufpreis                    189.000 EUR
    Kaufpreis je m2                3.327 EUR
    Erwerbsnebenkosten 7 %        13.230 EUR
    Gesamtinvestition            202.230 EUR
    Grund und Boden               36.567 EUR   51,5034 m2 x 710 EUR
    Abschreibungsbasis           165.663 EUR   = 81,92 % der Gesamtinvestition
    Restnutzungsdauer            19 Jahre      Gutachten BeMa vom 09.08.2026,
                                               Stichtag 08.06.2026, AZ-R-2026-1155
    Abschreibung im Jahr           8.719 EUR   = 5,26 %
    Wohnflaeche                    56,80 m2    WoFlV, Aufmass 08.06.2026
    Miteigentumsanteil           132,06 / 1.000
    Nettokaltmiete                   515 EUR   = 9,07 EUR/m2, siehe Punkt 1 oben
    Mietverhaeltnis              seit 01.09.1998
    Hausgeld gesamt                  188 EUR   HG-Vorschuss Wirtschaftsplan 2026
    Instandhaltungsruecklage       51,11 EUR   Ruecklagenzufuehrung 2026
    Abstellraum                  SNR 5 im Untergeschoss, 3,38 m2
    Energieausweis               95,8 kWh, Klasse C, Verbrauch
    Mietsubvention                 9.920 EUR   siehe Staffelung unten

Die Mietsubvention ist mit **9.920 EUR** angesetzt:

    Dez. 2026 bis Maerz 2027   140 EUR je Monat      560 EUR
    April 2027 bis Maerz 2030  120 EUR je Monat    4.320 EUR
    April 2030 bis Maerz 2033  100 EUR je Monat    3.600 EUR
    April 2033 bis Maerz 2036   40 EUR je Monat    1.440 EUR
    Summe                                         9.920 EUR

Die Kalkulation rechnet in Zelle M44 dagegen mit 8.060 EUR. Dort sind
die 140 EUR nur fuer einen Monat angesetzt, die 120 EUR nur fuer zwei
Jahre statt fuer drei. Siehe Punkt 8 oben.

Im Rechenmodell der index.html steht dafuer

    stufeM: 3
    sub: [140, 120, 100, 40, 0]

Die Werte sind dem Mietstand zugeordnet, nicht dem Kalenderjahr. Die
140 EUR fuer den Dezember 2026 liegen vor dem ersten Rechenjahr und
sind im Rechner nicht enthalten, weil er ab Januar 2027 in ganzen
Jahren rechnet.

## Wohnflaeche und Dachschraegen

Die Wohnung liegt unter dem Dach. Nach der Wohnflaechenberechnung vom
08.06.2026 zaehlen diese Anteile nur zur Haelfte:

    Flur                      9,00 m2
    Kueche                    3,03 m2 voll + 1,16 m2 (von 2,32 m2)
    Kinder                    6,85 m2 voll + 1,34 m2 (von 2,68 m2)
    Bad                       4,90 m2
    Wohnen/Essen             13,67 m2 voll + 2,02 m2 (von 4,04 m2)
    Schlafen                 11,77 m2 voll + 1,75 m2 (von 3,50 m2)
    WC                        1,31 m2
    Summe                    56,80 m2

Das Expose weist die Schraegen offen aus, in Kapitel 02 unter einer
eigenen Zwischenueberschrift, in der Faktenliste, in der
Bildunterschrift des Grundrisses und als Begruendung dafuer, dass die
angesetzte Marktmiete unter dem Wert der Nr. 1 liegt. Es rechnet
durchgehend mit 56,80 m2.

## Abgleich mit der Kalkulation

Das Expose ist auf denselben Stand gebracht wie die Nr. 3.
Uebernommen sind: Zinssatz 5,00 %, Steigerung von Hausgeld und
Ruecklage mit je 3 % im Jahr, Mietsubvention ausserhalb der
steuerlichen Betrachtung, Mieterhoehung erstmals im April 2027.

**Mietsubvention wird nicht versteuert.** Der Zuschuss geht in den
Cashflow ein, nicht in das steuerliche Ergebnis. Im Rechenmodell steht
er deshalb nicht in `zvE`. Die Kalkulation hat ihn versteuert, das war
falsch und ist hier korrigiert.

**Mieterhoehung.** Die erste Erhoehung um 15 % faellt im April 2027,
danach alle 36 Monate. Der Rechner arbeitet dafuer monatsweise. In
einem Wechseljahr enthaelt der Jahreswert drei Monate zum alten und
neun Monate zum neuen Stand, deshalb steht fuer 2027 eine krumme Miete
von 572,94 EUR. Gesteuert wird das ueber `stufeM: 3` und `sub`.

**Steigerung der Kosten.** Hausgeld und Ruecklage steigen mit je 3 %
im Jahr, eingestellt ueber `kost: 0.03`.

**Zinsregler.** Startwert 5,00 %, Bereich 4,50 bis 5,50 %.

**Bodenwert.** Siehe Punkt 2 oben, 36.567 EUR statt 35.567 EUR.

**Nicht umlegbares Hausgeld.** Angesetzt sind 55 EUR im Monat, wie in
der Kalkulation. Der rein nicht umlagefaehige Anteil aus dem
Wirtschaftsplan liegt rechnerisch niedriger, bei 276,27 EUR im Jahr,
also rund 23 EUR im Monat. Der Ansatz von 55 EUR deckt zusaetzlich den
Teil der umlagefaehigen Kosten ab, der ueber der
Nebenkostenvorauszahlung des Mieters liegt. Der Hinweis auf den Wert
aus dem Wirtschaftsplan steht auf Wunsch nicht im Expose, weil dieser
Punkt noch geklaert wird.

**Instandhaltungsruecklage.** Im Rechenmodell mit 52 EUR gerundet, in
der Faktenliste mit dem tatsaechlichen Wert 51,11 EUR ausgewiesen.

**Bruttomietrendite und Kaufpreisfaktor** werden nicht ausgewiesen. Mit
der Mietsubvention waeren beide Kennzahlen irrefuehrend.

## Zu den Bildern

Das Titelbild ganz oben (`02_hausansicht_hero.jpg`) ist die
Strassenansicht aus dem Ordner der Nr. 3, es ist dasselbe Haus.

Im Bildstreifen steht an fuenfter Stelle die Aussenansicht mit der
gelben Markierung (`03_hausansicht_markiert.jpg`). Sie stammt aus dem
Fotoordner dieser Einheit und zeigt die Gauben des zweiten
Obergeschosses.

Die Gartenaufnahme (`11_garten.jpg`) ist ebenfalls aus dem Fotoordner
der Nr. 5.

Reihenfolge im Bildstreifen: Garten, Flur, Bad, WC, Wohnen und Essen,
Kueche, Schlafzimmer, Hausansicht. Auf der ersten Ansicht liegen damit
Garten, Flur, Bad und WC, der Rest kommt beim Wischen. Die Dateinamen
sind nach der urspruenglichen Reihenfolge nummeriert und stimmen mit
der Anzeigereihenfolge bewusst nicht ueberein. `07` ist fuer das dritte
Zimmer frei gehalten.

Die sechs Innenaufnahmen sind die KI-aufbereiteten Fassungen aus dem
Fotoordner, also die Dateien mit dem Zusatz "KI". Der kurze Hinweis
dazu steht unter dem Bildstreifen, ausfuehrlich steht er in den
rechtlichen Hinweisen unter "Einsatz von KI": echte Aufnahmen dieser
Wohnung, mit KI aufgeraeumt, persoenliche Dinge des Mieters aus
Datenschutzgruenden entfernt.

Der Grundriss `bilder/12_grundriss_we5.png` ist ein Ausschnitt aus dem
Aufteilungsplan, Blatt 2. Obergeschoss, Planstand 08.06.2026. Er zeigt
die Nr. 5 mit Moeblierungsvorschlag, links daneben das Treppenhaus mit
dem Wohnungszugang. Am linken Rand sind schmale Reste der Nr. 6
sichtbar, das laesst sich ohne Qualitaetsverlust nicht weiter
beschneiden. Die Raumbeschriftungen nennen jeweils "100 %", "50 %" und
"Gesamt", die Bildunterschrift erklaert das.

Kapitel 07 beginnt mit einem zweiten Bildstreifen, vier unbearbeitete
Aufnahmen der modernisierten Wohnung Nr. 1 im Erdgeschoss links.
Dateien `20_modernisierung_wohnen.jpg` bis `23_modernisierung_flur.jpg`.
Siehe dazu Punkt 4 oben.

Die Bildstreifen sind waagerecht wischbar. Die Pfeile und die Punkte
liegen unter dem Streifen, nicht mehr ueber den Bildern. Am Rechner
liegen vier Bilder nebeneinander, auf dem Tablet zwei, auf dem Telefon
eines. Ein Klick auf ein Bild oeffnet es gross in der
Lightbox. Im Ausdruck wird daraus ein Raster mit zwei Spalten.

## Zu den Unterlagen

Der Ordner entspricht dem der Nr. 3, das sind durchweg Unterlagen zum
Gemeinschaftseigentum und damit fuer alle Einheiten dieselben.
`04_Modernisierungsuebersicht.pdf` ist die Fassung dieser Einheit, sie
fuehrt unten "Wohnung 2. OG links" auf.

Bei den gebaeudeweiten Dokumenten liegen im Paket der Nr. 5 teilweise
groessere Scans derselben Datei, etwa 13 MB statt 3 MB beim Baugesuch
von 1970. Uebernommen wurden die kleineren Fassungen aus dem Ordner der
Nr. 3, Seitenzahl und Inhalt sind identisch. Das Sammelpaket bleibt so
bei rund 19 MB statt 46 MB.

Die Erschliessungsbeitragsauskunft lag im Paket der Nr. 5 nicht bei und
stammt deshalb aus dem Paket der Nr. 3.

Nicht im Ordner "unterlagen" liegen Grundbuchauszug,
Restnutzungsdauergutachten, Herleitung der Kaufpreisaufteilung,
Mietvertrag und Mieterhoehungsschreiben. Sie enthalten
personenbezogene Daten. Auf GitHub Pages ist jede Datei im Repository
oeffentlich abrufbar, auch wenn sie auf der Seite nicht verlinkt ist.
Im Expose steht deshalb, dass diese Unterlagen bei ernsthaftem
Kaufinteresse nachgereicht werden. Das Protokoll des Mietergespraechs
ist weder im Ordner noch im Expose erwaehnt.

Hinweis zur Teilungserklaerung, die im Ordner liegt: Sie enthaelt in
Abteilung III die Grundschulden des Verkaeufers. Das war bei der Nr. 2
und der Nr. 3 genauso. Falls das nicht gewuenscht ist, die Datei
`01_Teilungserklaerung.pdf` loeschen und den ersten Eintrag in der
Liste `DOKS` in der index.html entfernen.

## Hochladen

Ein eigenes Repository fuer diese Wohnung anlegen. Dann auf
"Add file", danach "Upload files", und in das Fenster alles drei
zusammen ziehen:

    index.html
    bilder            (der ganze Ordner)
    unterlagen        (der ganze Ordner)

Wichtig: nicht den Ordner "Roseggerstrasse-9-2OG-links" hochladen,
sondern seinen Inhalt. Die index.html muss im Repository ganz oben
liegen.

## Pages einschalten

Settings, dann Pages. Bei Source "Deploy from a branch" waehlen,
Branch `main`, Ordner `/ (root)`. Speichern. Der erste Aufbau dauert
ein bis zwei Minuten.

## Falls ein Ordner anders heissen soll

In der index.html steht im Skript genau eine Zeile:

    var DOKBASE='unterlagen/';

Nur diese aendern. Der Schraegstrich am Ende muss bleiben.
Der Bildordner ist in den Bildpfaden hinterlegt und heisst "bilder".

## Hinweis zum Oeffnen von der Festplatte

Oeffnest du die index.html per Doppelklick, sperrt der Browser bei
manchen Einstellungen den Zugriff auf Nachbarordner. Die Seite
erscheint, die Downloads funktionieren dort aber nicht immer. Auf der
veroeffentlichten Seite laeuft alles.
