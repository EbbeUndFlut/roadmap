# Start
## Day 1
- Was ist NodeJS überhaupt?
Grob erklären was man mit NodeJS machen kann bzw.
erklären das man normalerweise Javascript ja nur im Browser ausführen kann und durch Node kann man das jetzt auch ohne Browser tun.

Vielleicht nochmal die Möglichkeiten die Node eröffnet ansprechen.
  - Desktopapplikationen
  - Handyapps
  - usw

Die V8 Engine von Chrome ansprechen, nur grob und nicht so tief, aber die Teilnehmer sollen wissen das die es halt möglicht macht den JS Code auszuführen.


Den unterschied von blocking IO und non blockingh IO darstellen.

Ich hab dafür immer eine Darstellung von einer Supermarktkasse (blocking) und einem Restaurant mit Kellner(non blocking) erstellt

Dann sprechen wir noch import/export an. Dazu gehört das Modulesystem.
Ich habe im letzten Kurs ESM (ECMAScript Modules) genommen. 
Davor wurde immer commonJs genutzt.

Warum brauchen wir Modules?
Wie ist das entstanden?
Nochmal drauf eingehen das JS ja kleine gestartet ist und dann immer mehr wurde, so das auch der wunsch nach modulen größer wurde damit der code strukturiert werden kann usw.

## Day 2
### Filesystem -> sync und async mit callbacks
Wir sprechen über synchron und asynchron. Dafür nutzen wir das 'fs' Module von Node.
Funktionen als Parameter -> Funktionen sind in Javascript First Class Citizien
Da wir Funktionen einfach in Variabeln speichern können, können wir sie auch als argumente an Funktionen übergeben.

Ab hier habe ich auch immer regelmässig auf die Node Dokumentation verwiesen, irgendwie vergessen die Teilnehmer immer wieder das es sowas gibt.

Dran denken das wir keine Promises nutzen sondern erstmal die ganzen Funktionen, die ein callback nutzen.

## Day 3
### HTTP http module
Kommunikation im Web -> Client Server
Immer gerne auch mit Zeichnungen arbeiten, z.B. mit Miro

Was passiert eigentlich wenn ich im Browser eine Adresse eingebe?
Request -> Response

Mit Client ist aber nicht immer nur der Browser gemeint, auch ein anderer Server kann als Client fungieren.
Versuchen das die Teilnehmer verstehen das es verschiedene Clients gibt und damit nur gemeint ist das einer etwas möchte und ein anderer etwas liefert oder so :D

#### Server schreiben
Dann nutzen wir das http Module um einen eigenen Server zu schreiben. Erst ganz simpel mit einem statischen Response und dann mit dem fs Module die auslieferung von html css und js Dateien

Immer schön bei den anderen Kursen den Code klauen ;)

Dabei nochmal auf die Pfade eingehen, was ist ein relativer Pfad und was ist ein absoluter.

## Day 4