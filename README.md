OLED-Bildschirm
----
*(Seeed Studio Grove – OLED Display 1.12")*

<img src=https://www.makeyourschool.de/wp-content/uploads/2018/10/63_oled_bildschirm-1024x1024.jpg width=400px>

Bildquelle: *Wissenschaft im Dialog*

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

----

Im Rahmen von [*Make Your School*](https://www.makeyourschool.de/) finden an Schulen Hackdays statt. Dabei überlegen sich Schülerinnen und Schüler, wie sie ihre Schule mitgestalten und mit technischen und digitalen Tools noch besser machen können. Unterstützt werden sie dabei von Mentorinnen und Mentoren, die die Veranstaltung begleiten und fachliche Impulse geben. *Make Your School* ist ein Projekt von *Wissenschaft im Dialog*. Die Klaus Tschira Stiftung ist bundesweiter Förderer.

Mit diesen **Bibliotheken und Beispiel-Codes** kann der euch vorliegende Sensor/Aktor getestet werden. Den **Mentorinnen und Mentoren von *Make Your School*** steht es frei, die hier zusammengestellten Codes **nach Bedarf und den individuell gemachten Erfahrungen anzupassen**. Beispiele können einfach im Ordner „examples“ hinzugefügt oder bearbeitet werden. Wir werden eure Beiträge regelmäßig prüfen und das Repository mithilfe eurer Änderungsvorschläge aktualisieren.

Das Repository basiert grundlegend auf den veröffentlichten Informationen und Codes von Seeed Studio. Die deutsche Übersetzung stammt von *Make Your School*, Fehlinterpretationen und Änderungen vorbehalten. Die Informationen dürfen frei genutzt, angepasst und verbreitet werden, solange die Lizenzrechte (siehe License.txt) beachtet werden.


**Weitere Informationen:**

[Repository von Seeed Studio](https://github.com/Seeed-Studio/OLED_Display_96X96)

[Offizielles Wiki von Seeed Studio](http://wiki.seeedstudio.com/Grove-OLED_Display_1.12inch/)

[Materialkoffer von *Make Your School*](https://www.makeyourschool.de/material/oled-bildschirm/)
