AAM 6 - Another AM6
===================

Please post your makes.

Einleitung
----------
Mein Anet A6 hat einige Mängel, die ich verbessern will. Zuerst einmal is da der Acryl-Rahmen, nicht sehr stabil und ich muss öfters mal die Schrauben nachziehen. Die Aufnahmebohrungen der Führungsstangen haben viel zuviel Spiel und die Stangen selbst sind bis zu 0.06mm zu klein, es wackelt also alles. Beim Einbau von Auto-Bett-Leveling habe ich bemerkt, dass der Speicher beim Anet-Mainboard vorne und hinten nicht ausrreicht, um die von mir gewünschten Funktionen von Marlin zu aktivieren.
Ich habe mir schon seit einiger Zeit Gedanken zu einem Upgrade auf einen Metallrahmen gemacht, ein Wechsel der Führungsstangen und ein neues Mainboards gehen dann im gleichen Zug.
Daher habe ich mich auf Thingiverse umgeschaut und Inspiration bei [pheneeny](https://www.thingiverse.com/thing:2263216), [Soravia](https://www.thingiverse.com/thing:2394506) und dem [Alu-Rahmen PK6 von pk_mbau](https://www.ebay.de/itm/PK6-Alu-Frame-Upgrade-Kit-V2-0-Rahmen-fur-Anet-A6-3D-Drucker/283041733029?hash=item41e69a19a5:m:mTSGz1bzeuv2UNjjm2iuy2Q) gefunden. Bei allen Varianten habe ich einige Sachen für gut befunden, andere weniger gut. 
Ich habe mich also daran gemacht, die meiner Meinung nach besten Eigenschaften zu vereinen. Ob es objektiv wirklich besser geworden ist, weiss ich nicht, aber von meinem Gefühl her schon.

Folgende Ziele wollte ich erreichen:
- Stabiler Rahmen für höhere Druckgeschwindigkeiten
- Beibehaltung des Direkt-Extruders
- Erhöhung der Genauigkeit
- Einfache Möglichkeit, Erweiterungen am Drucker anzubringen
- Umbau auf Arduino Mega/Ramps/Ramps-Display

Herausgekommen ist ein Mix aus AM8, AM6 und PK6. Es ist mehr Metall als im AM6/8 aber weniger als im PK6 verbaut. Ich habe hier Teile neu gekauft, vom A6 übernommen, selbst konstruiert und in einem Fall von einer der oben erwähnten Quellen übernommen.


Konstruktion
------------
Es kommen Alu-Profile mit 5er Nut zum Einsatz da ich die meisten Teile für den Rahmen günstiger und schneller von motedis.com bestellen kann als aus China. Aus China kommen ausschliesslich Nut6-Lösungen.
Ich habe die Dimensionen für den Rahmen 1:1 übernommen, so dass ein fertiges Kit (nur Profile!) für den AM8/AM6 gekauft werden kann. Ich selbst habe mich für Item-Profile (Europäisch Typ-I) 20x40 entschieden, die eine Nut 5 haben. Ich kann die meisten Teile für den Rahmen günstiger, schneller und in besserer Qualität von motedis.com bestellen kann als aus China oder von Amazon, aber ein Preis-Vergleich lohnt sich in jedem Fall.

Die meisten am Markt angebotenen Kits haben aber Nut 6, kompatibel zu praktisch allen asiatischen Angeboten. 

Ein angenehmer Nebeneffekt des neuen Rahmens ist ein Verfahrweg in Z von ca. 280mm.

Ein kleiner Trick um ein Schwingen in der Z-Achse durch die Kuppler zu verhindern: Eine 5mm Kugel zwischen Motor-Achse und Trapezspindel einlegen. So ist ein Spiel gegen unten ausgeschaltet, der Kuppler kann aber seine Funktion trotzem erfüllen.


Modifikationen
--------------
- Y-Achse Endstopp nach hinten versetzt damit ein grösserer Verfahrweg möglich ist.
- Y-Achse Schrittmotor nach unten versetzt. Dazu die Motothalterung modifiziert. Es sollte nun möglich sein, das Heizbett mit bereits angepassen Gurtklemmen 1:1 zu übernehmen.





Stückliste
----------
Eine detaillierte Stückliste ist als PDF bei den Dateien dabei. 

Folgende Teile wurden gekauft:
- Aluprofile
- Gelaserte Aluplatten
- Eck-Verbindungsstücke
- T-Nutensteine
- Schrauben und Muttern
- Führungstangen 4x 380mm, 2x 445mm
- Trapezspindel mit Mutter 2x 350mm

Folgende Teile und Baugruppen wurden vom A6 übernommen:
- Heizbett und Träger kpl.
- Druckkopf kpl.
- Endschalter
- Riemen
- Kuppler
- Motoren


Folgende Teile sind von AM8 oder AM6 übernommen:
- Y-Stangenhalter


Folgende Teile wurden von mir modifiziert, konstruiert oder von anderen Dingen hier inkludiert
- Y-Stangenhalter mit Endstop-Halter
- Y-Motorhalter
- Y-Riemenspanner kpl.
- [Y-Gurt-Halter](https://www.thingiverse.com/thing:3039772)


