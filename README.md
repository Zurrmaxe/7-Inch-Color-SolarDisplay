
Hallo zusammen
Hier mal eine Anzeige von zwei Hoymiles HMT2250T , einem Shelly 3EM und einer OpenDTU-onBattery für den Heimgebrauch.
![271224-1](https://github.com/user-attachments/assets/b5255e85-723e-4c3d-8d77-207c10b720a9)
![271224-2](https://github.com/user-attachments/assets/649386ff-d375-43d9-89b3-1e2a3558b583)

Hier erstmal die wichtigsten Infos zum Display:
https://github.com/lovyan03/LovyanGFX/discussions/424
https://www.haraldkreuzer.net/aktuelles/erste-schritte-mit-dem-sunton-esp32-s3-7-zoll-display-lovyangfx-und-lvgl


Hinweis:
Bitte unbedingt die Einstellungen in der Arduino IDE und der Librarys beachten ! 
Nicht alle aktuellen Librarys laufen problemlos. Die aufgeführten Versionsnummern bitte beachten.
Die Einstellungen für das Display müssen vorgfälltig vorgenommen werden. 
Sind an einer Arduino IDE **gleichzeitig** unterschiedliche Displays und ESPs angeschlossen, kann es zu Problemen kommen. 

Diese Anzeige kann natürlich auch für andere Inverter oder DTUs angepaßt werden. DAzu sind die entsprechenden Code für die Abfrage der JSON-Files entsprechend zu ändern.
 
Diese Anzeige ist noch nicht fertig und wird von mir laufend verändert. 

Beim Druck auf dem Bildschirm wird die Beleuchtung für 5 Sekunden heller eingestellt. 

Eine Nachabschaltung ist noch nicht vorhanden aber in Arbeit.

Neben dem Wochentag und der Uhrzeit wird noch die Qualität des WLAN angezeigt um das Display optimal zu plazieren.

Dann ist da noch  Anzeige der Raumtemperatur mit einem DHT11-Sensor, welcher am Display angeschlossen ist.

Wenn kein Solarinverter bzw. die dazugehörige DTU "erreichbar" ist, wird das jeweilige Feld ausgeblendet.

[7zoll_Solaranzeige271124.zip](https://github.com/user-attachments/files/18266139/7zoll_Solaranzeige271124.zip)

Natürlich alles ohne Garantie und Haftung für irgendwelche Schäden.


Alf
