# REST-Countries Browser-Konsole

Eine einfache Browser-basierte Konsolenanwendung, die die REST-Countries-API nutzt, um Informationen über Länder anzuzeigen.

## Beschreibung

Diese Anwendung simuliert eine Konsolenschnittstelle direkt im Webbrowser und ermöglicht es Schülern, nach Länderinformationen zu suchen. Sie verwendet die öffentliche [REST-Countries-API](https://restcountries.com), um Daten wie:

- Offizieller Name
- Hauptstadt
- Region/Subregion
- Bevölkerungszahl
- Fläche
- Währungen
- Sprachen
- Flagge (Emoji)

zu einem gewünschten Land anzuzeigen.

## Verwendung

1. Öffne die `konsole_browser.html` Datei in einem beliebigen Webbrowser
2. Gib den Namen eines Landes in die Konsole ein und drücke die Enter-Taste
3. Die Anwendung zeigt Informationen über das gesuchte Land an
4. Falls mehrere Ergebnisse gefunden werden, kannst du aus der Liste das gewünschte Land auswählen (durch Eingabe der Nummer oder Klick auf den Eintrag)

## Verfügbare Befehle

- **Ländername**: Gib einfach den Namen eines Landes ein, um Informationen darüber anzuzeigen
- **help**: Zeigt Hilfeinformationen und verfügbare Befehle an
- **clear**: Löscht den Konsoleninhalt
- **exit**: Beendet das Programm (lädt die Seite neu)

## Besonderheiten der Browser-Konsole

- **Befehlsverlauf**: Nutze die Pfeiltasten nach oben/unten, um durch vorherige Befehle zu navigieren
- **Klickbare Ergebnisse**: Bei mehreren Suchergebnissen kannst du direkt auf ein Land klicken
- **Keine Installation nötig**: Funktioniert direkt im Browser ohne externe Abhängigkeiten
- **Konsolendesign**: Ähnelt einer echten Konsole mit dunklem Hintergrund und Monospace-Schrift

## Technische Details

Diese Anwendung besteht aus einer einzigen HTML-Datei mit eingebettetem JavaScript und CSS. Sie benötigt:
- Einen modernen Webbrowser mit JavaScript-Unterstützung
- Keine zusätzlichen Abhängigkeiten
- Keine Installation von Software
- Keine Serverkomponente

## Lernzwecke

Diese Anwendung eignet sich hervorragend, um Schülern die folgenden Konzepte beizubringen:

- Verwendung von REST-APIs mit JavaScript
- Asynchrone Programmierung mit async/await
- Fehlerbehandlung in JavaScript
- DOM-Manipulation zur Simulation einer Konsole
- Event-Handling für Benutzereingaben
- Datenverarbeitung und -anzeige

Die Anwendung ist bewusst einfach gehalten, um den Fokus auf die Nutzung der API und die grundlegenden JavaScript-Konzepte zu legen. 