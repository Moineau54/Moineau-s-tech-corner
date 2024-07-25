[Englische Version](/2024/07/13/Nmap%20Host%20Vulnerability%20Scanner%20Script.md) | [Französische Version](/2024/07/13/Nmap%20Host%20Vulnerability%20Scanner%20Script%20fr.md)

Raspberry Pis sind kleine, kreditkartengroße Computer, die für eine Vielzahl von Projekten verwendet werden können. Sie sind kostengünstig, einfach zu bedienen und können für eine breite Palette von Anwendungen eingesetzt werden.

Vor kurzem konnte ich aus verschiedenen Gründen meinen Hauptcomputer nicht benutzen, also entschied ich mich, meinen Raspberry Pi eine Weile als Hauptcomputer zu verwenden. Für diese Aufgabe wählte ich einen Raspberry Pi 5 mit 4 GB RAM und einer 128 GB SD-Karte. Ich installierte das Betriebssystem [Kali Linux](https://www.kali.org/docs/introduction/) darauf, da ich mich für Cybersicherheit interessiere. Hier ist, was ich während meiner Reise gelernt habe:

## 1. Einrichtung des Raspberry Pi

Alles, was Sie benötigen, ist ein Raspberry Pi, eine Stromversorgung, eine SD-Karte, ein SD-Kartenleser, ein Ethernet-Kabel und ein Computer, um die [Imager](https://www.raspberrypi.com/software/)-Software herunterzuladen. Die Imager-Software hilft Ihnen, das Betriebssystem auf die SD-Karte zu flashen. In meinem Fall habe ich Kali Linux gewählt.

## 2. Mein erster Einsatz des Raspberry Pi

Nach der Einrichtung des Raspberry Pi habe ich ihn mit einem Monitor, einer Tastatur und einer Maus verbunden. Ich konnte den Raspberry Pi starten und sofort benutzen. Zuerst habe ich das System mit den folgenden Befehlen aktualisiert:

```bash
sudo apt update
sudo apt upgrade -y
```

Nachdem ich das System aktualisiert hatte, installierte ich einige wichtige Werkzeuge wie 'Visual Studio Code' und andere. Nachdem ich die Einrichtung abgeschlossen hatte, begann ich, den Raspberry Pi und seine Fähigkeiten zu erkunden. Eines der ersten Dinge, die man vergessen muss, ist, ihn wie einen normalen Computer zu benutzen, da er nicht so leistungsstark ist wie ein herkömmlicher Computer, also muss man bei einigen Dingen Kompromisse eingehen. Für mich bedeutete das, im Internet mit vielen geöffneten Tabs zu surfen und ihn für Spiele zu nutzen. Ich habe ihn ausschließlich für das Programmieren und andere leichte Aufgaben verwendet.  
Eine der Sachen, die mir am Raspberry Pi gefallen, ist, dass er sehr energieeffizient ist und nicht viel Strom verbraucht. Ich konnte ihn stundenlang ohne Probleme laufen lassen. Eine weitere großartige Sache ist die Vielfalt der Projekte, die Sie damit machen können. Sie können ihn zum Programmieren, für die Hausautomation und vieles mehr verwenden. Darüber hinaus hat der Raspberry Pi eine große Community von Nutzern, die immer bereit sind, Ihnen zu helfen, wenn Sie auf Probleme stoßen. Und schließlich ist sein Preis sehr erschwinglich, was ihn zu einer großartigen Option für jeden macht, der mehr über Computer und Programmierung lernen möchte. Nicht zu vergessen, es ist ein großartiges Werkzeug, um Linux zu lernen, da es sehr leicht, flexibel und nachsichtig ist (wenn Sie etwas falsch machen, können Sie die SD-Karte immer einfach neu flashen).

Da sein Betriebssystem auf [Debian](https://www.debian.org/) basiert, werden Sie nicht vermeiden können, das Terminal zu benutzen, also müssen Sie sich daran gewöhnen. Aber keine Sorge, es ist nicht so schwer, und Sie werden sich schnell daran gewöhnen.

## 3. Fazit

Insgesamt habe ich derzeit nur Gutes über den Raspberry Pi zu sagen. Es ist ein großartiges Werkzeug, um mehr über Computer, Programmierung und Linux zu lernen. Es ist ein großartiges Werkzeug für jeden, der mehr über Computer und Programmierung lernen oder einfach einige Aufgaben automatisieren möchte. Ich empfehle es jedem, der an Technologie interessiert ist und mehr über Computer und Programmierung erfahren möchte. Ich werde meinen Raspberry Pi 5 weiterhin als Hauptcomputer verwenden und sehen, wie weit ich ihn nutzen kann.