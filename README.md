# ![Pr0t0s Phishing Panel v 1.0](http://www0.xup.in/exec/ximg.php?fid=12947185)


## Info

Das Phishig Panel auf der grundlage von dem Toolstore Panel programmiert.
Das Panel ist auf Benutzerfreundlichkeit und Umfang ausgelegt.
100 % Der Fehler im Panel enstehen NUR durch falsche Einstellung.
Das Panel selber hat KEINE Elemente mehr vom Toolstore Panel die nicht mehr als 80% ver�ndert wurden.


## Funktionen

- E-Mail Benachrichtigung an jede beliebige E-Mail Adresse �ber jeden SMTP Server. (Siehe Config.php)
- Multi Tasking (Mehr als nur eine Phishing Website auf einem Externen Server einsehbar)
- Export Funktion (Export in 2 verschiedenen Formaten)
- IP Auto Trace + L�nder Flagge als 16x16 .gif
- 100% Stable.
- Keine Fehlerausgabe ausserhalb des Internen Bereichs des Panels.
- Volle Konfigurations M�glichkeit.
- Das erstellen von spezifischen Required Hosts.
- Ausw�hlen der zu speichernden GET&POST Parameter.
- 100 % SQLi sicher.
- Fremdnutzung ausgeschlossen durch Non Database Login.
- Verschiedene Statistiken.
- ....


## Tutorial

!0. Die Config.php&MySQL.php einstellen!
�ffnen und lesen Sie die Datei : "inc/config.php" und tragen Sie dort alle Infos ein.
Sie k�nnen dort auch die E-Mail Optionen einstellen.
Danach �ffnen Sie die Datei : "connect/mysql.php" und tragen Sie dort alle MYSQL Daten ein.


1. Das erstellen und Benutzen eines Hosts.
Zum erstellen eines Hosts unter dem Tab "Hosts" geben Sie in das erste Feld ein Icon Pfad an.
Diese Bilder sind hochzuladen unter /img/Pictures/. Wenn Sie in den Ordner zb Amazon.ico hochgeladen haben,
tragen Sie in das erste Feld : "Amazon.ico" (Mit gro�&klein) ein. In das Zweite Feld kommt dann Ihr Pers�hnliches Kommentar zum Host zb "Amazon Phishing Site".

2. Das einstellen der GET&POST Parameter.
Zum einstellen der Parameter unter "Settings" w�hlen Sie Ihren gew�nschten Host aus, danach tragen Sie den Namen des Parameters ein z.B. "User" danach den Parameternamen
des n�chsten Operaten z.B. "Passwort" und als letzes die Website auf die das Opfer weitergeleited werden soll zb "http://www.google.de/" ("http://" & "www." werden ben�tigt).
Dann best�tigen Sie ihre Angaben und Ihre Phishing Website ist eingetragen.

3. Nutzung
Sie erstellen eine Phishing Website und tragen als Ziel f�r die Daten folgende Datei an : "http://www.IHREDOMAIN.de/gate.php?HostID=" Dann die Host ID von ihrers zuvor erstellen
Hosts unter "Hosts" im Panel z.B. "1". Der fertige Link sieht dann so aus : "http://www.IHREDOMAIN.de/gate.php?HostID=1". Dass ist alles, nat�rlich m�ssen die �bergebenen Parameter
mit den angegebenen Parametern �bereinstimmen.

4. Service
Falls Sie sachliche und begr�ndete Fragen haben k�nnen Sie den Nutzer "Pr0t0s" im Forum "Hackbase.cc" diese Fragen zukommen lassen.


## Screenshots

Index
![index](http://www0.xup.in/exec/ximg.php?fid=16297381)

Stats
![Stats](http://www0.xup.in/exec/ximg.php?fid=18567161)

Logs
![Logs](http://www0.xup.in/exec/ximg.php?fid=18191059)

Hosts
![Hosts](http://www0.xup.in/exec/ximg.php?fid=17300056)

Settings
![Settings](http://www0.xup.in/exec/ximg.php?fid=65429879)

Export
![Export](http://www0.xup.in/exec/ximg.php?fid=10990488)

Credits
![Credits](http://www0.xup.in/exec/ximg.php?fid=17482988)

~~Thread @ Hackbase.cc~~
~~https://hackbase.cc/showthread.php?38870-Script-Pr0t0s-Phishing-Panel&p=216634~~


## Zukunft
Geplant sind keine neuen Features aber ich bin offen f�r Ideen.

## �nderungen von LucidTrip

Folgende �nderungen die vorgenommen wurden:

- Die gate.php wurde um den $_GET["ip"] erweitert damit der user nicht unbedingt auf das Panel weiter geleitet werden muss, so kann das Phising skript
einfach die n�tigen Parameter �bermitteln und selbst sich drum k�mmern wohin der Vic weitergeleitet werden soll. Ist aber optional, also es kann auch wie
gehabt verwendet werden.
- ein Backup Skript was die Datenbank via crontab immer mal auf uploaded.to hochl�d, um f�r den fall eine Bust/Own/Hack noch die Datenbank zu haben.
- hier und da wurden paar Bilder falsch angezeigt, wurde gefixxt.
- das hinzuf�gen von Hosts hat auch nicht functioniert, wurde gefixxt.
- die host.php musste auch aufger�umt werden, glaub das h�tte so wenn �berhaupt nur im IE funktioniert.
- das wars auch erst mal, weitere Ideen folgen.


## Credits
1. Pr0t0s @ ~~Hackbase.cc~~ (Coding,GFX und alles andere)
~~Hackbase.cc~~

2. mod: LucidTrip
date: 05.04.2015
