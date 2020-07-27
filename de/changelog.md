# Änderungsprotokoll

Diese Seite dokumentiert die wichtigsten Änderungen an Krystara.io.

## Inhalt

1. [Version 1](#version-1)
2. [Version 2](#version-2)

## Version 1

- Basisversion, geschrieben in React + NodeJS in etwa 4 Stunden.
- Nur Unterstützung für PvP-Rangliste.
- Keine Sprachunterstützung, keine Plattformunterstützung.
- Keine mobiltaugliche Oberfläche.

## Version 2

- Die App wurde innerhalb von etwa einer Woche komplett neu geschrieben.
- Einsatz von MaterialUI für das Styling, für Kompatibilität mit Mobiltelefonen.
- Unterstützung für mehrere Plattformen zu allen bestehenden Ansichten hinzugefügt.
- Unterstützung für Lokalisierung hinzugefügt (für alle vom Spiel verwendeten Sprachen).
- Unterstützung für Dunkelmodus hinzugefügt.
- Der Datenlader holt jetzt 5 Minuten vor dem Zurücksetzen (für genaue Tagesend-Leaderboard-Daten) und 5 Minuten nach dem Zurücksetzen (um die Aufzeichnung früh zu beginnen).
- [PvP-Rangliste](/pvp)-Ansicht überarbeitet.
- Ansicht [Aktuelle Aufgaben](/Tasks) hinzugefügt.
- Ansicht [Bevorstehende Ereignisse](/Ereignisse) hinzugefügt.
- Ansicht [Gilden-Rangliste](/Gilde) hinzugefügt.
- Ansicht [Guild Wars-Klammern](/guildwars) hinzugefügt.
- Ansicht **Änderungsprotokoll** (dieses Dokument) hinzugefügt.
- Ansicht [Datenschutz](/privacy) hinzugefügt.
- Verbesserte Leistung und Sicherheit durch spezielle HTTP-Kopfzeilen.
- Bevorzugte Einstellungen für Dunkelmodus, Plattform und Sprache werden jetzt im lokalen Speicher abgelegt.
- [Community-Lokalisierungsprojekt](https://github.com/MasterEric/gow-stuff-i18n) erstellt.
