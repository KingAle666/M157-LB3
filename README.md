

Copyright  2020	Fetsluck
Auftraggeber:	Gaming-Verein Worlds Beyond Reality / P. Albrecht
Letzter Abgabe Termin:	21.01.2021, 23:59
Vorstellung Umsetzung:	28.01.2021
Dateiname:	M157_Fettsluck_LB02.docx
Gruppenname:	Fetsluck
Projektleiter:	Alessio van Berkel
Projektmitarbeiter:	Kyan Zürcher, Luca Lopes Commandeur
Markdown Repository:	
Modul:	Modul 157: IT-System-Einführung planen und durchführen
 

Inhaltsverzeichnis
01 Lastenheft -/ Pflichtenheft	1
1	Ausgangslage	3
1.1	Ausgangslage 9  Minecraft Server	3
2	Einleitung	3
3	Ist-Zustand und Rahmenbedingungen	3
3.1	Ist-Zustand	3
3.2	Rahmenbedingungen	4
4	Ziele	4
5	Funktionale / Nicht Funktionale Anforderungen	4
5.1	Funktionale Anforderungen:	4
5.2	Nicht Funktionale Anforderungen:	5
6	Fragenkatalog	5
02 Angebot (Auftragnehmer)	6
1 Bezugnahme	7
2 Einleitung	7
3 Beschreibung der Lösung	7
4 Mengengerüst / Kostenaufstellung	8
5 Vorgehen (Planung)	9
6 Risikoanalyse	10
6.1	Risikomatrix	11
7	Rahmenbedingungen	16
8	Antworten des Fragekatalog	17

1	Ausgangslage
1.1	Ausgangslage 9  Minecraft Server
Der Gaming-Verein Worlds Beyond Reality feiert jedes Jahr zusammen eine Neujahrsparty. Von den dreissig Mitglieder nehmen dabei meist etwa fünfzehn Personen teil. Einige der Mitglieder haben Bedenken aufgrund der aktuellen Corona Lage geäussert, weshalb der Vorstand ihren Mitgliedern den Vorschlag unterbreitet hat die Party virtuell auf einem Minecraft Server abzuhalten. Der bisherige Minecraft Server ist ein wenig in die Jahre gekommen und lief äusserst instabil. Ein paar Mitglieder haben sich bereiterklärt sich um einen neuen Minecraft Server zu kümmern. Im Vergleich zum letzten Server soll der neue Server auch ein Monitoring über ein Web-Interfacehaben. Dort sollen allgemeine Informationen über die Systemauslastung, sowie wenn möglich auch Informationen des Servers selbst (Anzahl Spieler, TPS, usw.) dargestellt werden. Damit die Systemtechniker nicht dauernd auf das Monitoring schauen müssen und frühestmöglich bei Störungen informiert werden, soll das System bei hoher CPU-Auslastung automatisch eine Benachrichtigung abschicken. Auf dem Server soll auch pünktlich zum Jahreswechsel ein kleines mehrteiliges Feuerwerk mit Musik gezeigt werden. Der Vorstand erstellt nun für die Mitglieder all diese notwendigen Anforderungen zusammen, damit diese ein Projekt erstellen und den Aufwand berechnen können.
2	Einleitung
Der Spieleverband Worlds Beyond Reality feiert jedes Jahr eine Neujahrsparty. Von den dreißig Mitgliedern nehmen normalerweise etwa fünfzehn Personen teil. Einige Mitglieder äußerten sich besorgt über die aktuelle Corona Situation, weshalb das Komitee seinen Mitgliedern einen Vorschlag unterbreitete, die Party virtuell auf dem Minecraft-Server abzuhalten. Da der aktuelle Minecraft Server schon in die Jahre gekommen ist. Das Besorgen des Servers beinhaltet nicht nur die Hardware zu beschaffen, sondern auch die Konfiguration des Servers und die Integration eines Monitorings. (Ein Monitoring Tool war beim alten Server nicht vorhanden). Durch das Monitoring möchten wir genau wissen, wann der Server ausgelastet ist. Zudem ein Automatische Benachrichtigung, sobald es eine Aktivität auf dem Server gibt. Ausserdem sollte Inbegriffen sein ein Feuerwerk mit Musik pünktlich zum neuen Jahr in der Minecraft Spielwelt auf dem Minecraft-Server. Auf dem Minecraft-Server sollten ca. 15 Spieler gleichzeitig Spielen können, ohne das es Spielunterbrüche gibt. Die Spielwelt, muss nichts Besonderes aufweisen, jegliche das Feuerwerk und die Musik. 
3	Ist-Zustand und Rahmenbedingungen
3.1	Ist-Zustand
Der vorherige Minecraft-Server ist 5 Jahre alt und sehr instabil, aufgrund vielen Auslastungen auf dem Server. Der Server befindet sich noch auf der Version 1.12.3 und mittlerweile hat man die Möglichkeit auf die Version 1.16.5 zu erweitern. Es gibt eine alte Spielwelt wo bereits gearbeitet bzw. gespielt wurde. Einige Mitglieder haben zugestimmt, sich um den neuen Minecraft-Server zu kümmern. Der Admin kann den Server nicht über eine Weboberfläche überwachen, steuern und verschiedene Information dort rauslesen die helfen sollen herauszufinden Probleme herauszufinden, zudem bekommt er keine Benachrichtig, sobald der CPU-Ausgelastet ist oder sich jemand versucht anzumelden ohne Berechtigung darauf zu haben. Ein Server Neustart werden nicht protokolliert, deswegen wird der Admin auch nicht informiert. Der Admin kann auch über eine Kommandozeile Befehle für das Spiel eingeben und ausführen wie z. B. die Berechtigung zu verteilen auf der Minecraft-Spielwelt etwas abzubauen oder zu platzieren. Zudem sollten auch Befehle funktionieren einige Befehle nicht mit denen man die Spieler wieder ausschliessen könnte u. a., wenn jemand denn Verband verlässt.

3.2	Rahmenbedingungen
Wir stellen Ihnen sehr gerne die Minecraft-Server Dateien wie z. B. die Spielwelt (world), Konfiguration (config) stellen wir Ihnen gerne zur Verfügung. Die Spielwelt beinhaltet denn Fortschritt die, die Spieler zuvor auf dem alten Server gemacht haben. Das Logo für den Minecraft-Server würden wir Ihnen auch bereitstellen, sodass vor dem Beitreten des Minecraft-Server das Logo ersichtlich ist. Es werden sonst keine Technische Mittel zur Verfügung gestellt. 
4	Ziele
	Alle 15 Spieler können miteinander gleichzeitig und an verschiedenen Orten auf dem Minecraft-Server auf der Minecraft- Spielwelt zusammenspielen.
	Am Neujahrtag um genau 00:00 Uhr werden verschiedene Feuerwerkskörper in der Spielwelt abgefeuert, dabei soll auch Musik abgespielt werden.
	Es soll ein physischer Server bereitgestellt werden, auf dem der Minecraft-Server lauft. 
	Ein Webinterface mit verschiedenen Informationen über den Minecraft-Server wie z. B. die Aktivitäten, CPU-Auslastung, Anzahl Spieler usw.
	Es sollen Befehle funktionierten, die es erlaubt die Spielwelt zu verwalten mit Berechtigungen, Ausschliessungen oder sonstiges.
	Der Minecraft-Server sollte auf der neuesten möglichen Version laufen, sodass das Spielerlebnis aktuell ist.
	Die alte Spielwelt soll übernommen werden und dort sollten die Feuerwerke gezündet werden mit einer passenden Musik.
	Die jeweiligen Spieler müssen auf einer Whitelist stehen, um auf den Minecraft-Server breitzutreten, sodass keine unerwünschten Spieler auf dem Server erscheinen.
	Der physische Server muss leistungsfähig sein, sodass Spielunterbrüche soweit wie möglich vermieden werden können, auch wenn die Spieler an verschiedenen Orten auf der Minecraft- Spielwelt spielen.
5	Funktionale / Nicht Funktionale Anforderungen
5.1	Funktionale Anforderungen:
	Der Minecraft-Server muss von überall, sprich von jedem Gerät mit einer funktionierende Interleitung erreichbar sein.
	Der Server muss über genügend Prozessorleistung, Grafikleistung und Arbeitsspeicher verfügen, sodass 15 Spieler gleichzeitig Spielen können.
	Das Monitoring, mit Übersicht über die Auslastung der verschiedenen Serverkomponenten muss über eine Webseite aufrufbar sein.
	Sobald der Prozessor ausgelastet ist, muss automatisch eine Benachrichtigung an die Systemtechniker geschickt werden.
	An Silvester muss ein Feuerwerk mit Musik in der Minecraft Welt laufen.
	Das Monitoring muss über Web Interface aufrufbar sein 
	Soll allgemeine Informationen über Systemauslastung und auch Informationen des Servers selbst (Anzahl Spieler, TPS, usw.) anzeigen 
	Bei hoher CPU-Auslastung soll automatisch eine Benachrichtigung an die Systemtechniker geschickt werden, damit sie nicht die ganze Zeit ein Auge auf das Web Interface halten müssen. 
	Der Server soll auslastungsfähig sein, sodass alle Spieler auf dem Server ohne Unterbrüche spielen können und an verschiedenen Orten auf der Welt.
	Die Spieler können sich via die IP-Adresse 51.154.166.140 im Minecraft Launcher über die Funktion Join Server dem Minecraft-Server beitreten.
	Wenn ein Fehler auftritt, sollte das System automatisch Benachrichtigungen senden, zum Beispiel wenn die CPU-Auslastung hoch ist.
5.2	Nicht Funktionale Anforderungen:
	Mindestens 15 Leute müssen sich gleichzeitig auf den Server verbinden können.
	Der Minecraft-Server sollte 24 Stunden inkl. Neustarts oder kurze Wartungen erreichbar sein. 
	Wenn ein Spieler nicht auf der Whitelist ist, kann dieser nicht auf den Minecraft-Server beitreten.
	Der CPU-Auslastung befindet sich im Rahmen auch wenn 15 Spieler gleichzeitig Spielen.
	Es muss genug Speicherplatz haben auf dem physischen Server, sodass die Spielwelt auch erweitert werden kann u. a. auch bei Aktualisieren der Version des Minecraft-Servers
6	Fragenkatalog 
-	Ist der Zugriff auf dem physischen Server oder Minecraft-Server jederzeit möglich?
-	Welche Erfahrungen haben Sie in diesem Bereich bereits gemacht?
-	Über welche Plattform wird der Minecraft-Server gehostet, sprich verwaltet?
-	Haben Sie auch andere Spiele, die sie verwalten?
-	Haben Sie bereits Erfahrung im Umgang mit Minecraft-Server Spieldateien?
-	Haben Sie bereits Erfahrungen im Umgang mit Minecraft-Server Sicherheiten (Spielwelt, Berechtigungen usw.)? 
Copyright  2020	Fetsluck
Auftraggeber:	Gaming-Verein Worlds Beyond Reality
Letzter Abgabe Termin:	21.01.2021, 23:59
Vorstellung Umsetzung:	28.01.2021
Dateiname:	M157_Fettsluck_02Angebote.docx
Gruppenname:	Fetsluck
Projektleiter:	Alessio van Berkel
Projektmitarbeiter:	Kyan Zürcher, Luca Commandeur Lopes
Modul:	Modul 157: IT-System-Einführung planen und durchführen

1 Bezugnahme 
Wir haben unser Angebot kurz und knapp gefasst. Es besteht ausfolgenden Dienstleistungen: 
	Evaluation der Hardware 
	Beschaffung der Hardware 
	Konfiguration der Dienste 
	Monitoring integrieren (mit automatischer Meldung, wenn CPU-Temperatur zu hoch ist) 
	Wartung des Servers 
2 Einleitung 
Da der Spieleverband Worlds Beyond Reality einen neuen Minecraft Server benötigt, stellen wir, die Firma FetsLuck, uns zur Verfügung diesen Server bereitzustellen und zu verwalten. Wir sind sehr motiviert dies zu machen, da wir selbst Mitglieder des Spieleverbands sind und wir wollen, dass wir zusammen Neujahr feiern können. (auch wenn Corona leider noch weitverbreitet ist.) 
Das Projekt beinhaltet verschiedene Aspekte wie z.B. die Planung des Projektes, damit wir einen sicheren Ablauf garantieren können, die Realisierung des Projektes basierend auf den Rahmenbedingungen des Spieleverbands und auch auf die Rahmenbedingungen, die wir uns selbst stellen werden, den Unterhalt und die Wartung des Servers, usw. 
Da wir Systemtechniker sind, kennen wir uns schon mit Servern aus, mit Minecraft Servern haben wir auch schon Erfahrungen gesammelt, was das Projekt sicherlich positiv beeinflussen wird. Wir wissen, dass wir das Ganze mit einer guten Planung zum Laufen bringen und sehen positiv auf die ganze Sache. 
3 Beschreibung der Lösung 
Wie schon erwähnt wird der momentane Minecraft-Server vom Gaming-Verein Worlds Beyond Reality durch ein neuen und zeitgerechten Minecraft Server von uns der Gruppe FetsLuck ersetzt. 
Es wird ein neuer Minecraft-Server mit der Version 1.16.5 bereitgestellt auf dem mindestens fünfzehn Personen gleichzeitig teilnehmen können. Die Spieler des Gaming-Verein Worlds Beyond Reality werden sich via die IP-Adresse 51.154.166.140 im Minecraft Launcher über die Funktion Join Server verbinden können. 
	Dies wird mit der MINECRAFT: JAVA EDITION-SERVER umgesetzt. 
Der neue Server wird über ein Monitoring über ein Web-Interface verfügen. Dort werden allgemeine Informationen über die Systemauslastung, sowie wenn möglich auch Informationen des Servers selbst (Anzahl Spieler, TPS, usw.) dargestellt werden. Damit nicht dauernd auf das Monitoring schauen müssen und frühestmöglich bei Störungen informiert werden, soll das System bei hoher CPU-Auslastung automatisch eine Benachrichtigung abschicken. Dies wird mit dem MC-MONITOR Docker Container umgesetzt, der dies mit Prometheus monitort. 

4 Mengengerüst / Kostenaufstellung 
Aufstellung aller verwendeten Geräte: 
Der Minecraft-Server wird auf einem Mac Pro (Late 2013) laufen gehostet, der über die folgenden Spezifikationen verfügt: 
-	Version: macOS Big Sur 11.1 
-	Prozessor: 3.5 GHz 6-Core Intel Xeon E5 
-	Arbeitsspeicher: 32GB 1866 MHz DDR3 
-	Festplattenspeicher: 2 Festplatten mit 3 TB Speicher 
Der Server wird pro Jahr vermietet, siehe hier die folgende Preistabelle: 
 
Dauer	Preis
Ein Jahr (Silber)	300 CHF
Zwei Jahre (Gold)	550 CHF
Drei Jahre (Diamant)	800 CHF
 
Der Aufwand wird auf die Stunde verrechnet, sprich pro Stunde wird ein Stundenansatz von 80 CHF.- pro Person fällig. Für die Umsetzung des Minecraft-Servers rechnen wir mit einem zeitlichen Aufwand von 5 Stunden pro Person und für das Monitoring mit 3 Stunden pro Person. 
 
Aufgabe	Zeit	Total	Preis
Minecraft-Servers	5 Stunden * 3	15 Stunden	1200 CHF
Monitoring	3 Stunden * 3	9 Stunden	720 CHF
Total 1920 CHF
 
Aufwand und Hosting	Preis
Aufwand + Silber Hosting	Total 2220 CHF
Aufwand + Gold Hosting	Total 2470 CHF
Aufwand + Diamant Hosting	Total 2720 CHF

5 Vorgehen (Planung) 
Wir die Gruppe Fetsluck machen jedes Projekt mit Kanban und dem Program KanBoard. 
Ein solchen Kanban-Board sieht so aus: 
  
Und in diesen Kärtchen sind alle Sub Tasks definiert: 

6 Risikoanalyse
Die Risikoanalyse soll aufzeigen, welche Eintrittswahrscheinlichkeit und Schadenshöhe ein Problem auslöst. In der Risikomatrix wird diese dann ersichtlich. Die verschiedenen Stufen wurden mit Zahlen versehen, um eine genaue Punktzahl zu erhalten, um diese einzustufen. 

Nr.	Risikobeschrieb	Ursache	Eintrittswahr-scheinlichkeit	Schadens-höhe	Effekt	Massnahme	Priorität
1-10	Zuständigkeit
1	Spielwelt auf dem Minecraft-Server nicht mehr funktionsfähig (Error, gelöscht oder verloren)	Wenn z. B. ein Update gemacht wird oder die Welt einen Fehler aufweist durch einen Bug.	Gering (1)	Hoch (3)	Durch das geht der Spielfortschritt auf der Spielwelt verloren.	Mit Backups der Spielwelt Datei die Wöchentlich oder auch täglich erstellt werden, somit verliert man nicht den ganzen Spielfortschritt.	7	Fetsluck
2	Hardware überlastet, sodass auf dem Server nicht mehr oder sehr schlecht gespielt werden kann.	Es kann verschiedene Ursachen haben, wie z. B. zu viele Spieler auf dem Server oder Hardware Fehler.	Mittel (2)	Hoch (3)	Durch das kann es zu Spielunterbrüchen kommen und dass der Server nicht mehr erreichbar ist.	Gute Hardwareleistung, die auch aktuell ist und die Anforderungen von einem Minecraft Server erfüllen. 	9	Fetsluck
3	Unberechtigte Verbindung zum Server bzw. eine Person, die sich versucht anzumelden, um Schaden zu verursachen.	Wenn z. B. keine Whitelist auf dem Server aktiviert wurde und jemand die IP-Adresse herausfindet, kann er sich entsprechen auf dem Server anmelden.	Gering (1)	Sehr hoch (16)	Dadurch kann auf dem Minecraft-Server Spielfortschritte zerstört werden, die mit viel Fleiss und Zeit aufgebaut wurden. Zudem könnte er sich Zugriff auf den physischen Server erschleichen.	Mit einer Whitelist die aktiviert wird und in dem die Spieler eingetragen wurden mit dem Spielname, dadurch werden diese genehmigt auf den Minecraft-Server beizutreten. 	10	Fetsluck
4	Server ist nicht mehr erreichbar, nach einem Neustart.	Es kann sein das der Server nach einem Neustart nicht mehr hochfahrt aus irgendwelchen Gründen.	Gering (1)	Sehr hoch (16)	Der Minecraft-Server ist nicht mehr erreichbar, somit können sich die Spieler nicht mehr mit dem Minecraft-Server verbinden.	Mit einem automatischen Benachrichtig wird der Admin bzw. Systemtechniker informiert das der Server nicht online ist für eine gewisse Zeit.	8	Andere
5	Plugins funktionieren nicht so wie es sollen.	Wenn viele Plugins installiert werden kann es sein das andere damit nicht kompatibel sind.	Sehr hoch (4)	Gering (1)	Es gehen keine Daten oder ähnliches verloren, jedoch werden der Plugin nicht spielbar und somit hat man Probleme beim Konfigurieren der Plugins.	In dem man das Plugin deaktiviert oder entfernt, somit kann man das ausschliessen und ggf. sich selbst informieren welche Plugins mit welchen Kompatibel sind.	3	Andere

6.1	Risikomatrix
1.	Spielwelt auf dem Minecraft-Server nicht mehr funktionsfähig (Error, gelöscht oder verloren)

Eintrittswahrscheinlichkeit	Sehr hoch (4)	4	8	12	16
	Hoch (3)	3	6	9	12
	Mittel (2)	2	4	6	8
	Gering (1)	1	2	3	4
Gering (1)	Mittel (2)	Hoch (3)	Sehr hoch (4)
Schadenshöhe
Die Chance das dieses Risiko Eintritt ist Gering, jedoch ist die Schadenshöhe Hoch, denn es sind sehr wichtige Spieldateien, jedoch kann man diese schnell neu erstellen. 

2.	Hardware überlastet, sodass auf dem Server nicht mehr oder sehr schlecht gespielt werden kann.
Eintrittswahrscheinlichkeit	Sehr hoch (4)	4	8	12	16
	Hoch (3)	3	6	9	12
	Mittel (2)	2	4	6	8
	Gering (1)	1	2	3	4
Gering (1)	Mittel (2)	Hoch (3)	Sehr hoch (4)
Schadenshöhe

Die Chance das dieses Risiko Eintritt ist Mittel, jedoch ist die Schadenshöhe Hoch denn es hat einen starken Einfluss auf die Minecraft-Welt.

3.	Unberechtigte Verbindung zum Server bzw. eine Person, die sich versucht anzumelden, um Schaden zu verursachen.

Eintrittswahrscheinlichkeit	Sehr hoch (4)	4	8	12	16
	Hoch (3)	3	6	9	12
	Mittel (2)	2	4	6	8
	Gering (1)	1	2	3	4
Gering (1)	Mittel (2)	Hoch (3)	Sehr hoch (4)
Schadenshöhe


Die Chance das dieses Risiko Eintritt ist Gering, jedoch ist die Schadenshöhe Sehr hoch (16), denn es hat einen starken Einfluss auf die Minecraft-Welt.

4.	Server ist nicht mehr erreichbar, nach einem Neustart.
Eintrittswahrscheinlichkeit	Sehr hoch (4)	4	8	12	16
	Hoch (3)	3	6	9	12
	Mittel (2)	2	4	6	8
	Gering (1)	1	2	3	4
Gering (1)	Mittel (2)	Hoch (3)	Sehr hoch (4)
Schadenshöhe

Die Chance das dieses Risiko Eintritt ist Gering, jedoch ist die Schadenshöhe Sehr hoch (16), denn es hat einen starken Einfluss auf die Spieler.

5.	Plugins funktionieren nicht so wie es sollen.

Eintrittswahrscheinlichkeit	Sehr hoch (4)	4	8	12	16
	Hoch (3)	3	6	9	12
	Mittel (2)	2	4	6	8
	Gering (1)	1	2	3	4
Gering (1)	Mittel (2)	Hoch (3)	Sehr hoch (4)
Schadenshöhe


Die Chance das dieses Risiko Eintritt ist Sehr hoch, jedoch ist die Schadenshöhe Gering, denn es hat keinen Einfluss auf die Spieler oder auf die Spielwelt.

7	Rahmenbedingungen 
-	Der Minecraft-Server wird von überall zur Verfügung stehen, sprich von jedem Gerät mit einer funktionierende Interleitung erreichbar sein.  
-	Der Server verfügt über Prozessorleistung, Grafikleistung und Arbeitsspeicher verfügen, sodass mindestens 15 Spieler und maximal 20 Spieler gleichzeitig Spielen können.  
-	Das Monitoring, mit Übersicht über die Auslastung der verschiedenen Serverkomponenten wird per Web aufrufbar sein.  
-	Sobald der Prozessor ausgelastet ist, wird automatisch eine Benachrichtigung an uns die Systemtechniker geschickt werden.  
-	Für Silvester wird eine Welt bereitgestellt auf ein Feuerwerk mit Musik in der Minecraft Welt ausgelöst werden kann.  
-	Das Monitoring wir allgemeine Informationen wie Systemauslastung und auch Informationen des Servers selbst (Anzahl Spieler, TPS, usw.) anzeigen. 
-	Bis zu 20 Spielern wird es möglich sein ohne Unterbrüche spielen können und das am verschiedenen Orten auf der Welt.  
-	Die IP-Adresse 51.154.166.140 wird übernommen, sodass die Spieler keine Änderungen im Minecraft Launcher vornehmen müssen, damit wird das Joinen der Server gleichbleiben. 
-	Wenn das Monitoring ein Fehler erkennt wird das System automatisch eine Benachrichtigung senden, zum Beispiel wenn die CPU-Auslastung hoch ist. 
-	Der Minecraft-Server wird sicher 23 Stunden und 45 Minuten inkl. Neustarts oder kurze Wartungen erreichbar sein.  
-	Nur Spieler die gewhitelistet sind wird es möglich sein zu Joinen, die Liste führt die Gaming-Verein Worlds Beyond Reality. 

8	Antworten des Fragekatalog
	Ist der Zugriff auf dem physischen Server oder Minecraft-Server jederzeit möglich? 
-	Nein, wir können das leider nicht zu 100% garantieren. Jedoch ist der Minecraft Server sicherlich an Neujahr verfügbar.
	Welche Erfahrungen haben Sie in diesem Bereich bereits gemacht? 
-	Alle Mitglieder der Gruppe haben bereits einen Server gehostet, jedoch haben nur Zwei der Drei Mitglieder haben bereits die Erfahrung damit gemacht einen Minecraft Server zu hosten.  
	Über welche Plattform wird der Minecraft-Server gehostet, sprich verwaltet? 
-	Der Minecraft Server, wird auf dem Servermodell Namens Mac Pro (Late 2013) gehostet. Das Betriebssystem, das auf dem Server laufen wird, ist das MacOS mit der Version BigSur 11.1
	Haben Sie auch andere Spiele, die sie verwalten? 
-	Was das Hosten von Gameservern anbelangt, haben wir bis jetzt nur Erfahrung mit dem Minecraft Server gesammelt.
	Haben Sie bereits Erfahrung im Umgang mit Minecraft-Server Spieldateien? 
-	Ja, haben wir. Die einten Teammitglieder mehr die anderen wiederum weniger.
	Haben Sie bereits Erfahrungen im Umgang mit Minecraft-Server Sicherheiten (Spielwelt, Berechtigungen usw.)? 
-	Ja, haben wir. Die einten Teammitglieder mehr die anderen wiederum weniger.
 


