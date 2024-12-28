# Batterie-Wechselrichter

Der Kombiwechselrichter ist AC-seitig an das Hausnetz angeschlossen und übernimmt folgende Aufgaben

- Laden der Batterien mit Gleichspannung 48V (Solarlader)
- Inverter zur Erzeugung von Wechselspannung aus den Batterien

Mit dem Greenrocksystem ursprünglich verbaut wurde ein Victron MultiplusII 3kW
Dieser wurde ersetzt durch einen [Victron Multiplus II 5kW](https://www.victronenergy.de/inverters-chargers/multiplus-ii) im Zuge des Austauschs und der Vergrösserung der [Speicherbatterie](Pylontech.md).

## Topologie der Installation

![grafik](https://github.com/user-attachments/assets/2d932e9a-123b-46e1-9953-30a096f3e4ad)

AC-DC-System - Strommessung erfolgt extern [Stromzähler Cavazzi EM340](https://www.victronenergy.com/upload/documents/Datasheet-Energy-Meters-Selection-Guide-EN.pdf)

Anschluss der Batterien and die Wechselrichter erfolgt über den Victron Distributor - mit Einzelabsicherung der Module
![grafik](https://github.com/user-attachments/assets/9de7455d-18c9-4211-8cde-0655d82d8015)

Die Steuerung der Anlage erfolgt über einen [Cerbo GX](https://www.victronenergy.com/panel-systems-remote-monitoring/cerbo-gx#manuals)
![grafik](https://github.com/user-attachments/assets/7e51eabf-f02d-471c-84c6-aac179b2dc61)

[back to installation](installation.md)
