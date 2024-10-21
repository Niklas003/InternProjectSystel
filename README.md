# InternProjectSystel 🚄
Web Projektaufgabe für Schülerpraktikant*innen bei der DB Systel

## Projektbeschreibung
Ziel des Projektes ist es eine digitale Bahnhofstafel zu erstellen mit welcher über eine Weboberfläche interagiert werden kann.
Für die Bahnhofstafel sollen Echtzeitdaten verwendet werden. Des Weiteren soll die Anwendung dem Look and Feel anderer DB Anwendungen nahe sein.

### Teil 1
- Eine Bahnhofstafel mit der Auflistung aller in der nächsten Stunde Abfahrenden Zügen (Regional- und Fernverkehr). (Ohne Bus, Tram, U-Bahn)
- Anzeige von Abfahrtsgleis und geplanter Abfahrtszeit
- Anzeige von realer Abfahrtszeit und die Kenntlichmachung von Verspätungen
- Sollte ein Zug ausfallen/andere Bemerkungen haben so soll das deutlich dargestellt werden.
- Die Anwendung sollte Responsive sein d.h. wenn ich die Anwendung auf schmaleren Bildschirmen öffne sollte ich sie immmer noch gut benutzen können.

### Teil 2
- Bei der Auswahl eines Zuges (draufklicken) öffnet sich ein Modal in welchem alle Halte des Zuges mit den jeweiligen Ankunfts- und Abfahrtszeiten gezeigt werden
- In dem Modal werden (wenn vorhanden) weitere Hinweise über die Zugfahrt angegeben z.B. Betreiber

### Teil 3
- Über eine Suchleiste sollen Bahnhöfe gesucht werden können dessen Abfahrtstafel angezeigt werden soll.

### Teil 4
Anhand von Geodaten die Latitude und Longditude kann die Position eines Zuges bestimmt werden. Betrachtet man diese Positionsdaten über einen gewissen Zeitraum so verändern diese sich (da sich der Zug ja bewegt... zumindest sollte er das).
Aus den veränderten Daten lässt sich in etwa die aktuelle Geschwindigkeit eines Zuges berechnen.

- Im Modal in welchem nähere Informationen zu einer Zugfahrt angezeigt werden soll die aktuelle geschätzte Geschwindigkeit angegeben werden.

### Teil 5
- Im Modal soll auf einer Karte die aktuelle Position des Zuges angegeben werden.
- Die Position aktualisiert sich automatisch bzw. wandert dynamisch über die Karte

## Umsetzung

### Tech Stack
Welchen Tech Stack du für die Umsetzung des Projektes verwendest ist dir selbst überlassen. Da es sich hierbaei aber um eine Webanwendung handelt empfielt es sich entsprechende Technologien zu verwenden.
Greife gerne auf Frameworks wie Angular, Vue oder React in Kombination mit JavaScript/typeScript zurück, oder nutze auch gerne pures JavaScrpit/Typescript.

Wichtig ist es bei der Umsetzung darauf zu Achten, dass nicht nur du allein den Code verstehst sondern er auch von anderen Personen gelesen und gewartet werden kann.
In diesem Projekt ist es wichtiger dass du eine gute Anwendung/Code schreibst und möglicherweise auch etwas dabei lernst. Ob du alle Anforderungen umsetzen konntest ist zweitrangig.

## Hilfreiche Werkzeuge
[ntransport.rest](https://transport.rest/) - API für Öffi Echtzeitdaten

[tailwindcss](https://tailwindcss.com/) - ein CSS Framework für schnelleres/einfacheres Styling von Web Interfaces (optional)

[Primefaces](https://www.primefaces.org/) bietet eine anpassbare UI Library für alle gängigen Frontend Frameworks an (optional)

[Angular Material](https://material.angular.io/) - solltest du dich entscheiden mit Angualr zu arbeiten bietet Angular Material eine gute UI Library

[DB UI](https://db-ui.github.io/) - das OpenSource UI System der DB (optional)

[Leaflet](https://leafletjs.com/) - OpenSource JS library für interaktive Karten (wird ab Teil 5 interessant)

Andere Librarys sind natürlich auch möglich, das sind hier alles nur Vorschläge.

## Design

[Farben](https://marketingportal.extranet.deutschebahn.com/marketingportal/Marke-und-Design/Basiselemente/Farbe#) - hier findest du die Farben welche bei der DB häufig eingesetzt werden.

[Marketingportal](https://marketingportal.extranet.deutschebahn.com/marketingportal) - Im Marketingportal findest du einiges zu Design bei der DB (erterner Zugriff ist leider beschränkt 😒)

[Abfahrtsboard](https://digital-board-official.vercel.app/) - Eigene Kreation die ich mal vor ein paar Jahren erstellt habe... Ist aber seit Ewigkeiten nicht mehr Maintained weshalb die ein oder andere Funktion Broken ist 😅. Darf aber gerne als Design referenz genutzt werden
