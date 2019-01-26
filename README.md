# AntBots
+ Robot Warrior (AntClass)
+ Robo Wars in der Ant-Class aus dem 3D Drucker
![Susi - AntBot](https://github.com/merlin1031/AntBots/blob/master/CAD-Daten/Bilder/Susi-Konzept1-4.png)
![Susi - AntBot Prototyp](https://github.com/merlin1031/AntBots/blob/master/CAD-Daten/Bilder/Susi-Prototyp_01.jpeg)

# Spezifikationen
+ Dimensionen max. 10x10x10 cm
+ Gewicht: max. 150g
+ Antrieb: 2S (7,4V)
+ Motor: Geriebemotor 6V, Übersetzung 1:200
+ Räder: Pololu 40x7mm Gummi

# CAD
+ Konstruktion mit SolidWorks 2017/18
+ Slicing und 3D-Druck: Repetier Host und Creality Ender 3

# Gewichtsübersicht
| Komponente                                       | Gewicht [g]|
| -------------                                    | -----------|
| Empfänger FrySky D4R-II                          |          4 |
| Empfänger 2.4G 4CH Mini Frsky D8 (banggood)      |          2 |
| Akkukabel JST-BEC Buchse ca. 8cm Kabel           |          1 |
| Lipo Akku 3S 800mA Turnegy 20-30C                |         47 |
| Lipo Akku 3S 500mA Turnegy 20-30C                |         33 |
| Lipo Akku 3S 350mA LemonRC 35C                   |         24 |
| 5V BEC 2A (Eckstein / D24V50F5)                  |          2 |
| Diatone 5V BEC V2.0 (flyingfolk)                 |          1 |
| ESC Pololu A4990 (ohne Kabel)                    |          1 |
| Susi Frame PLA incl. Kugelroller/Motoren/Räder   |         86 |
| Schraube M3x30                                   |          1 |

# Bezugsquellen
## Schrauben
+ Inbus Schrauben DIN 912: [Edelstahlschrauben M3 DIN 912](https://gedex-shop.de/de/schrauben/ZYLINDERSCHRAUBEN/Zylinderkopf-DIN-3699/DIN-912-M3-Innensechskantschrauben-mit-Zylinderkopf-Edelstahl-rostfrei-A2-3700/)

## Antrieb
+ Rad:[Pololu Wheel 40×7mm](https://eckstein-shop.de/Pololu-Wheel-407mm-Pair-Black)
+ Getriebemotor: [V-TEC Micro DC Motor Gleichstrom Getriebemotor 10x8mm 6V](https://eckstein-shop.de/V-TEC-Micro-DC-Motor-Gleichstrom-Getriebemotor-10x8mm-10x12mm-12x13mm-3V-6V-17-560RPM)
+ Getriebemotor Alternative: [Orlandoo OH35P01 KIT RC Car Parts Gear Motor - 300](https://www.banggood.com/custlink/v3KGERK978)
Leider bietet Eckstein nur Getriebe bis zur Übersetzung 1:200 an (Stand Dez. 2018). Nach den ersten Fahrversuchen wird sich zeigen ob diese Übersetzung "zu langsam" ist. Falls ja müsste eine kleinere Übersetzung wie z.B. diese 1:300 eingestezt werden.
+ ESC: [ Dual Motor Driver Carrier dual H-bridge](https://eckstein-shop.de/Pololu-A4990-Dual-Motor-Driver-Carrier-dual-H-bridge)
+ ESC Alternative: [DasMikro 2S6A Micro Dual Bi-Directional Speed Controller for Tank Crawler and Boat without Brake](https://www.banggood.com/custlink/vmGmdEGiuN)
Interessant ist die Version A mi eingebauem Mischer. Dabei ist Signal 1 für die Motorendrehzahl (vorwärts / rückwärts) zuständig und Signal 2 für die Richtung (links / rechts).
Mit dem Mischer wird es dann möglich den Roboter mit einer handelsüblichen, günstigen Colt-Anlage zu steuern. In der Regel besitzen diese Sender keine Mischer um das softwareseitig einstellen zu können. Bei normalen Knüppel-Sendern (z.B. FrySky 9D Plus) kann dies über einen etsprechnden Software-Mischer im Sender eingestellt werden.
+ 5V BEC: [Mini BEC 5V 2A V2 bis 6S Lipo!](http://flyingfolk.com/Voltage-Regulators-Spannungsregler/FPV-Mini-UBEC-BEC-5V-2A-2S-6S-LiPo-Step-Down-Spannungswandler)
