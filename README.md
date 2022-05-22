# Schnittstellendefinition für das museum4punkt0-Teilprojekt "Eine virtuelle Zeitreise in E.T.A. Hoffmanns Frankfurt"

An diesem Ort werden die für die Erstellung einer AR-Anwendung notwendigen Schnittstellen zwischen den im Teilprojekt zu entwickelnden Modulen dokumentiert.

## Module

- Ein "Lokalisierungsdienst" signalisiert, dass Inhalte angezeigt werden sollen
  + Ein [ortsbasierter Lokalisierungsdienst (etwa auf GPS-Basis)](https://github.com/freies-deutsches-hochstift/virtuelle-zeitreise-lokalisierung-gps)
  + oder ein [QR-Code-basierter Lokalisierungsdienst](https://github.com/freies-deutsches-hochstift/virtuelle-zeitreise-lokalisierung-qr-code)
- Die anzuzeigenden Inhalte werden von einem "[Mediendienst](https://github.com/freies-deutsches-hochstift/virtuelle-zeitreise-mediendienst)" über den Videostream der Kamera gelegt
- Um den Mediendienst zu unterstützen, kann eine browserbasierte [Abstandsmessung](https://github.com/freies-deutsches-hochstift/virtuelle-zeitreise-abstandsmessung) vorgenommen werden
- Ein [integrierendes Modul](https://github.com/freies-deutsches-hochstift/virtuelle-zeitreise-integration/) erstellt auf Basis der beschriebenen Komponenten eine Web-Anwendung. Es kann über eine CSV-Datei konfiguriert werden.

## Förderung

Das Projekt museum4punkt0 wird gefördert durch die Beauftragte der Bundesregierung für Kultur und Medien aufgrund eines Beschlusses des Deutschen Bundestages.

![BKM-Logo](https://github.com/museum4punkt0/images/blob/2c46af6cb625a2560f39b01ecb8c4c360733811c/BKM_Fz_2017_Web_de.gif)
![NeustartKultur](https://github.com/museum4punkt0/media_storage/blob/a35eedb36e5b502e90cd76d669a6b337002b230a/BKM_Neustart_Kultur_Wortmarke_pos_RGB_RZ_web.jpg)
