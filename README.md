OLED-Bildschirm
----
*(Seeed Studio Grove – Dust sensor)*

<img src=https://www.makeyourschool.de/wp-content/uploads/2018/10/8_feinstaubsensor-1024x1024.jpg width=400px>

Auf den 96×96 Pixel des OLED-Bildschirms können Bilder, Informationen oder auch Diagramme o.ä. in 16 Graustufen und hohem Kontrast dargestellt werden. Der Bildschirm lässt sich direkt oder mithilfe des Grove Shields an einen Arduino oder Raspberry Pi über die serielle Schnittstelle I2C anschließen.

Im Folgenden sind wichtige Hinweise für die jeweiligen Bildschirm-Versionen (bisher nur auf englischer Sprache) aufgezählt:


Grove OLED Display 1.12'' V1.0
===
It is a 16 color grayscale 96×96 dot matrix OLED display module with Grove compatible 4pin I2C interface. Grove - OLED 96x96 is constructed with 96 x 96 dot matrix OLED module LY120 and SSD1327 driver IC. Comparing to LCD, OLED screens are more competitive, which has a number of advantages such as high brightness, self-emission, high contrast ratio, slim / thin outline, wide viewing angle, wide temperature range, and low power consumption.

- See ./examples/OLED_SSD1327_v1

When using V1.0 hardware, please check initialize functionality before uploading Arduino sketch.
```
SeeedGrayOled.init(SSD1327);
```

Grove OLED Display 1.12'' V2.0
===
**Note that the OLED v2.0 has a 128x128 dot matrix OLED display, when showing image, bitmap size should be 128x128 pixel.**

- See ./examples/OLED_SH1107G_v2

Change driver IC to SH1107G, when using V2.0 hardware, please check initialize functionality before uploading Arduino sketch.


```
SeeedGrayOled.init(SH1107G);
```

For more information, please refer to [wiki page][1]

----
In diesem Repository findet ihr **Bibliotheken und Beispiel-Codes**, mit denen der hier vorliegende Sensor getestet werden kann. Wir richten uns hiermit an **jeden Mentor und jede Mentorin aus dem Rahmen von Make Your School** und ermutigen euch, die hier zusammengestellten Codes **nach Bedarf** und individuell gemachten Erfahrungen **anzupassen**. Beispiele können einfach im Ordner /examples hinzugefügt oder angepasst werden. Wir versuchen das Repository regelmäßig mit Hilfe von euren Änderungsvorschlägen zu aktualisieren.

Das Repository basiert grundlegend auf den veröffentlichten Informationen und Codes von Seeed Studio. 
Die deutsche Übersetzung stammt von [Make Your School](https://www.makeyourschool.de/). Fehlinterpretationen und Änderungen vorbehalten. Die Informationen dürfen frei genutzt, angepasst und verbreitet werden, solange die Lizenzrechte (siehe License.txt) beachtet werden.

**Weitere Informationen:**

[Repository von Seed Studio](https://github.com/Seeed-Studio/)

[Offizielles Wiki von Seed Studio](http://wiki.seeedstudio.com/Grove/)

[Materialkoffer von Make Your School](https://www.makeyourschool.de/material/)
