Webmontag-iOS
=================

## General information

The source code published here is intended for learning purposes. Not only Webmontag Halle members may use it to learn more about developing apps, but also other interested people. **Please note** that the **comments in the source code** and the **rest of this document** are in **German only**.

## Screenshots

![](screenshots/Artikel.png)

![](screenshots/Jobs.png)

![](screenshots/Kategorien.png)

![](screenshots/News.png)

![](screenshots/Videos.png)

## Informationen zum Projekt

### Zwecke verschiedener Dateien

Das Projekt befindet sich im Ordner „Webmontag“.

* Webmontag.xcodeproj: Xcode-Projekt-Datei
* AppDelegate: enthält Funktionen für das Verhalten der App beim Start, Beenden, Übergang in den Hintergrund usw.
* Main.storyboard: Benutzeroberfläche der App (kann grafisch nur in Xcode dargestellt werden)
* Images.xcassets: enthält die Icons und LaunchImages für die verschiedenen Display-Größen
* NewsViewController: Code für den Bereich „News“
* ArtikelViewController: Code für den in „News“ ausgewählten Artikel
* VideosViewController: Code für den Bereich „Videos“
* VideoViewController: Code für das in „Videos“ ausgewählte Video
* JobsViewController: Code für den Bereich „Jobs“
* JobViewController: Code für den in „Jobs“ ausgewählten Job
* JobsKategorienViewController: Code für die Auswahl der Job-Kategorien
* MehrViewController: Code für den Bereich „Mehr“
* CopyrightViewController: Code für das Copyright und das Impressum
* copyright.html: enthält das Copyright und das Impressum
* Reachability: von Apple zur Verfügung gestellter Code zum Überprüfen der Internetverbindung
* PNG-Bilder: Tab Bar- und Kategorien-Symbole für die App für die verschiedenen Display-Größen

In einigen Dateien werden Frameworks importiert, die sich in Xcode zum Projekt hinzufügen lassen. Diese sind im Repository nicht enthalten

## Informationen zur App

Mit der Webmontag-App hast Du alle News und Videos des Webmontags in Halle (Saale) und aktuelle Job-Angebote in der Region an einem Ort.
Lies Dich durch alle Artikel zu den Themen der letzten Webmontage und schaue Dir die entsprechenden Videos an. Informiere Dich zu attraktiven Job-Angeboten im Bereich der Web-Entwicklung in der Umgebung um Halle.

Die Webmontag-App ist im App Store für das iPhone, das iPad und den iPod touch kostenlos verfügbar. Sie erfordert mindestens iOS 6.

[Laden im App Store](http://AppStore.com/Webmontag)
