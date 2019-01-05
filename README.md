# AntBots
+ Robot Warrior (AntClass)
+ Robo Wars in der Ant-Class aus dem 3D Drucker
![Susi - AntBot](https://github.com/merlin1031/AntBots/blob/master/CAD-Daten/Bilder/Susi-Konzept1-4.png)

# Spezifikationen
+ Dimensionen max. 10x10x10 cm
+ Gewicht: max. 150g
+ Antrieb: 2S (7,4V)
+ Motor: Geriebemotor 6V, Übersetzung 1:200
+ Räder: Pololu 40x7mm Gummi

# CAD
+ Konstruktion mit SolidWorks 2017/18
+ Slicing und 3D-Druck: Repetier Host und Creality Ender 3


# Bezugsquellen
## Schrauben
+ Inbus Schrauben DIN 912: [Edelstahlschrauben M3 DIN 912](https://gedex-shop.de/de/schrauben/ZYLINDERSCHRAUBEN/Zylinderkopf-DIN-3699/DIN-912-M3-Innensechskantschrauben-mit-Zylinderkopf-Edelstahl-rostfrei-A2-3700/)

## Antrieb
+ Rad:[Pololu Wheel 40×7mm](https://eckstein-shop.de/Pololu-Wheel-407mm-Pair-Black)
+ Getriebemotor: [V-TEC Micro DC Motor Gleichstrom Getriebemotor 10x8mm 6V](https://eckstein-shop.de/V-TEC-Micro-DC-Motor-Gleichstrom-Getriebemotor-10x8mm-10x12mm-12x13mm-3V-6V-17-560RPM)
+ Getriebemotor Alternative: [Orlandoo OH35P01 KIT RC Car Parts Gear Motor - 300](https://www.banggood.com/custlink/v3KGERK978)
Leider bietet Eckstein nur Getriebe bis zur Übersetzung 1:200 an (Stand Dez. 2018). Nach den ersten Fahrversuchen wird sich zeigen ob diese Übersetzung "zu langsam" ist. Falls ja müsste eine kleinere Übersetzung wie z.B. diese 1:300 eingestezt werden.
+ ESC: [Pololu A4990 Dual Motor Driver Carrier dual H-bridge](https://eckstein-shop.de/Pololu-A4990-Dual-Motor-Driver-Carrier-dual-H-bridge)
+ ESC Alternative: [DasMikro 2S6A Micro Dual Bi-Directional Speed Controller for Tank Crawler and Boat without Brake](https://www.banggood.com/custlink/vmGmdEGiuN)
Interessant ist die Version A mi eingebauem Mischer. Dabei ist Signal 1 für die Motorendrehzahl (vorwärts / rückwärts) zuständig und SIgnal 2 für die Richtung (links / rechts). Mit dem Mischer wird es dann möglich den Roboter mit einer handelsüblichen, günstigen Colt-Anlage zu steuern. In der Regel besitzen diese Sender keine Mischer um das Softwareseitig einstellen zu können. Bei normalen Knüpel-Sendern (z.B. FrySky 9D Plus) kann dies über einen etsprechnden Software-Mischer im Sender eingestellt werden.
