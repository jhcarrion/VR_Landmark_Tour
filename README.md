# VR Grapple Wahrzeichen

Geiles VR game wo man wie spider man and Wahrzeichen hoch schwingt

# Funktionalität und gameplay bis jetzt - Version 1.1 und 1.2
https://drive.google.com/drive/folders/1pDZPR0Qwg5-lrSK635B5nh772KlJxDnd?usp=sharing

# Designfragen?

* Wenn man den Grapplehook schießt, ist es ein Projektil oder instant?
	* Festgestellt auf instant - funktioniert eher wie ein Laser

* Nachdem der Grapple verbunden ist, wird man zum kontaktpunkt gezogen? Automatisch oder manuell?
	* Manuell

* Kann man alles grapplen oder gibt es oberflächen wo man es nicht kann?
	* Man kann bis jetzt nur die Wahrzeichen grapplen (und Boden)

* Zeitlimit? Begrenzte Leben?
	* Tbd

* Checkpoints / Respawn punkte?
	* Tdb - wenn man für irgendein Gründ aus der Environment raus fliegt oder runterfällt, muss man die Anwendung neu starten

* Sound Effekte lokal gespeichert - muss noch integriert werden

# Herausforderungen
* Continuous movement buggy 
* Gewicht, Masse und Größe beinflussen swinging - momentan ist der Spieler relativ klein, k.A ob das der Performance beinflusst
* Grapple schießt nur wenn eine Öberflache mit Collider gezielt wird, ansonsten macht nichts
* Da man selbst ein Collider ist, wenn man sich selbst schießt, wird man sehr schnell nach oben geschossen
	* eventuell eine verschiedene Funktionalität finden damit das nicht passiert
* Alle Modelle müssen Mesh Collider Component beinhalten um grapplebar zu sein  --> sehr rechenintensiv

# Langzeit Ziele

* Startmenu, Pausemenu und Einstellungen 

* Sound effekte? Wind rauschen, grapple schuss...   - lokal gespeichert

* Umgebung? Verschiedene Umgebungen bzw. Levels für die verschiedene Wahrzeichen

* Spielbare Eigenschaften? Zb. durch Ringe fliegen und Punkte kriegen oder einsammelbare objekte? zb. Gold Münzen

* Grapple "Laser" tatsächlich wie ein Grappling Gun modellieren

* Hände korrekt modellieren
