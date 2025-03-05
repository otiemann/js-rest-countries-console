# REST-Countries Browser-Konsole

Eine einfache Browser-basierte Konsolenanwendung, die die REST-Countries-API nutzt, um Informationen über Länder anzuzeigen.

## Beschreibung

Diese Anwendung nutzt die öffentliche [REST-Countries-API](https://restcountries.com), um Daten wie:

- Offizieller Name
- Hauptstadt
- Region/Subregion
- Bevölkerungszahl
- Fläche
- Währungen
- Sprachen
- Flagge (Emoji)

zu verschiedenen Ländern anzuzeigen.

## Versionen

Das Projekt enthält zwei verschiedene Implementierungen:

### 1. Browser-Konsole (`konsole_browser.html`)

Eine interaktive simulierte Konsolenanwendung im Browser mit Eingabemöglichkeit.

### 2. Reine Konsolenausgabe (`console_only.html`)

Eine sehr einfache Version, die Informationen zu fünf vordefinierten Ländern direkt in der Browser-Konsole (F12) ausgibt.

## Verwendung der Browser-Konsole

1. Öffne die `konsole_browser.html` Datei in einem beliebigen Webbrowser
2. Gib den Namen eines Landes in die Konsole ein und drücke die Enter-Taste
3. Die Anwendung zeigt Informationen über das gesuchte Land an
4. Falls mehrere Ergebnisse gefunden werden, kannst du aus der Liste das gewünschte Land auswählen (durch Eingabe der Nummer oder Klick auf den Eintrag)

### Verfügbare Befehle

- **Ländername**: Gib einfach den Namen eines Landes ein, um Informationen darüber anzuzeigen
- **help**: Zeigt Hilfeinformationen und verfügbare Befehle an
- **clear**: Löscht den Konsoleninhalt
- **exit**: Beendet das Programm (lädt die Seite neu)

### Besonderheiten der Browser-Konsole

- **Befehlsverlauf**: Nutze die Pfeiltasten nach oben/unten, um durch vorherige Befehle zu navigieren
- **Klickbare Ergebnisse**: Bei mehreren Suchergebnissen kannst du direkt auf ein Land klicken
- **Keine Installation nötig**: Funktioniert direkt im Browser ohne externe Abhängigkeiten
- **Konsolendesign**: Ähnelt einer echten Konsole mit dunklem Hintergrund und Monospace-Schrift

## Verwendung der reinen Konsolenausgabe

1. Öffne die `console_only.html` Datei in einem beliebigen Webbrowser
2. Öffne die Browser-Konsole (F12 oder Rechtsklick → "Untersuchen" → "Konsole")
3. Die Informationen zu folgenden Ländern werden automatisch angezeigt:
   - Deutschland
   - Frankreich
   - Spanien
   - Italien
   - Vereinigte Staaten

## Technische Details

Diese Anwendung besteht aus einfachen HTML-Dateien mit eingebettetem JavaScript und CSS. Sie benötigt:
- Einen modernen Webbrowser mit JavaScript-Unterstützung
- Keine zusätzlichen Abhängigkeiten
- Keine Installation von Software
- Keine Serverkomponente

## Lernzwecke

Diese Anwendung eignet sich hervorragend, um Schülern die folgenden Konzepte beizubringen:

- Verwendung von REST-APIs mit JavaScript
- Asynchrone Programmierung mit async/await
- Fehlerbehandlung in JavaScript
- DOM-Manipulation zur Simulation einer Konsole (in der Browser-Konsole-Version)
- Event-Handling für Benutzereingaben (in der Browser-Konsole-Version)
- Datenverarbeitung und -anzeige
- Konsolenausgaben mit console.log (in der reinen Konsolenversion)

Die Anwendungen sind bewusst einfach gehalten, um den Fokus auf die Nutzung der API und die grundlegenden JavaScript-Konzepte zu legen. 