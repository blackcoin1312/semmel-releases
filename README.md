<p align="center"><img src="icon.png" width="128" alt="Semmel-Icon"></p>

<h1 align="center">Semmel</h1>

<p align="center">Eine einfache, blau-weiße Tabellenkalkulation für macOS und Windows.</p>

<p align="center"><a href="https://github.com/blackcoin1312/semmel-releases/releases/latest"><b>⬇ Neueste Version herunterladen</b></a></p>

## Installation

### macOS (Apple Silicon und Intel, ab macOS 11)

1. `Semmel-<Version>-macOS.dmg` aus dem [neuesten Release](https://github.com/blackcoin1312/semmel-releases/releases/latest) herunterladen.
2. Die DMG öffnen und **Semmel** auf den Ordner **Programme** ziehen.
3. Beim ersten Start im Programme-Ordner **Rechtsklick auf Semmel → Öffnen** wählen und bestätigen
   (die App ist nicht bei Apple notarisiert). Alternativ: *Systemeinstellungen → Datenschutz & Sicherheit → Trotzdem öffnen*.

### Windows (10 und 11, 64 Bit)

1. `Semmel-<Version>-Windows-Setup.exe` aus dem [neuesten Release](https://github.com/blackcoin1312/semmel-releases/releases/latest) herunterladen.
2. Das Setup starten. Falls Windows SmartScreen warnt: **Weitere Informationen → Trotzdem ausführen**.
3. Im Assistenten **Nur für mich** (ohne Administratorrechte) oder **Für alle Benutzer** wählen.
4. Semmel steht danach im Startmenü. Deinstallieren über *Einstellungen → Apps* – dabei wird auch die gespeicherte Anmeldung entfernt.

Für IT: stille Installation mit `/VERYSILENT /SUPPRESSMSGBOXES /NORESTART` (plus `/ALLUSERS` für alle Benutzer).
Semmel braucht HTTPS-Zugang zu `*.supabase.co` (Anmeldung, Mappen) sowie `api.github.com`, `github.com` und
`objects.githubusercontent.com` (Updates).

## Was Semmel kann

- Mit Konto anmelden – alle Mappen liegen sicher online und werden automatisch gespeichert
- Mehrere Personen oder Geräte bearbeiten dieselbe Mappe gleichzeitig
- Mappen mit anderen teilen (Ansehen oder Bearbeiten)
- Zellen mit Text, Zahlen und Formeln, Schrift, Ausrichtung, Zahlenformate und Farben
- Zeilen, Spalten und Zellen einfügen und löschen, mehrere Tabellenblätter pro Mappe
- Herunterladen als Excel-Arbeitsmappe oder CSV

## Updates

Semmel prüft beim Start, ob hier eine neuere Version liegt, und zeigt dann oben rechts **⬆ Update** an.

---

Dieses Repository enthält nur die Installer. Semmel nutzt die Tabellen-Engine von
[GridCraft](https://github.com/storytold/gridcraft) (MIT/Apache-2.0).
