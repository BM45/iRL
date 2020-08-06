# iRadio on Linux ist eine Linuxdistribution für Internetradios

iRL ist eine Linuxdistribution für Internetradios auf Basis von Debian/Raspbian für Raspberry 1A(+), 1B(+), 2B, 3A+, 3B(+), 4.

<p align="center">
  <img width="700" height="450" src="https://github.com/BM45/iRadio/blob/master/pics4www/ITT_Viola_350_1.jpeg">
  <img width="700" height="450" src="https://github.com/BM45/iRadio/blob/master/pics4www/Cassettensimulation.jpg">
</p>

Die Linuxdistribution enthält den zum Releasedatum gültigen Stand des iRadio-Softwarebaukastens https://github.com/BM45/iRadio.

Standardmßig aktiviert sind:
- Displaydaemon für I2C-LCD-Modul, 
- Tastatursteuerung per gpiod, 
- Bluetoothservice für Raspberrys mit BT-Hardware, 
- FM-Sendefunktion über GPIO-Header (für die HF-Ausgabe ist noch eine FM.txt per USB-Stick einzuspielen),
- aktiver SSH-Zugang,
- beschleunigte Grafiktreiber für X11.

#### Download der aktuellen Version vom 08.2020 (Buster-Release, SD-Karte mit mindestens 8GB ) hier
https://mega.nz/file/vSZ00Y6K#yej494B-CD68MqDpl1jM-DxmYdn2ms4JpRldmxuYe1I

Standardlogin auf der Console/SSH: pi/raspberry

Nach dem Kopieren des Images auf eine SD-Karte können die WLAN-Zugangsdaten direkt beim ersten Booten über USB-Stick eingespielt werden. Andere Steuer- oder Displaydaemonen, sowie Skalensimulationen können per Installerskript aktiviert werden. Sämtliche Konfigurationsdateien für einen USB-Stick sind im iRL-Github enthalten und können eigenen Bedürfnissen angepasst werden.
