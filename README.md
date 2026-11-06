# Beydosh Releases

Öffentliche signierte Updates für Beydosh PIM, Windows x64.

## Beta-Updates

Aktueller Stand: **0.9.127** (Beta).

- [Version und Änderungen](https://github.com/Beydosh/releases/releases/tag/v0.9.127)
- [Updatekanal](beta/updates/stable/)
- [Alle Versionen](https://github.com/Beydosh/releases/releases)

0.9.127 korrigiert die zentrale eBay-Verkaufsfreigabe und ergänzt Aktiv, Pausiert und
Deaktiviert für Schnittstelle, Markt und Produkt. Die erste native Codex-Anbindung
für Produktpflege ist unter Einstellungen / Konto standardmäßig ausgeschaltet.
Das gemeinsame sanfte Scrollen, die Benachrichtigungs-Kopfzeile, Kontonamen bei
Export-Verbindungen und das Laden von E-Mails wurden überarbeitet. Der passende
Launcher ist im normalen Update enthalten.

149 Desktop-Selbsttests sowie die isolierte Prüfung von Signatur, Manipulationsabwehr,
Aktivierung und Rücknahme sind bestanden. Eine tatsächliche Installation oder ein
erfolgreicher eBay-Angebotstest wird damit noch nicht behauptet. Details stehen beim Release.

Seit 0.9.121 gleicht PIM den Standard-Versandstandort unter Einstellungen / Shopinformationen
mit dem Unternehmensprofil auf der Website ab. Nur der bestätigte Unternehmensinhaber
kann die gemeinsame Adresse ändern. Mitglieder können sie sehen. Ein bisher lokaler
Standort wird erst nach ausdrücklicher Übernahme und Speicherung zentral geteilt.
Ungespeicherte Eingaben bleiben bei Hintergrundaktualisierungen erhalten;
gleichzeitige Änderungen werden erkannt und nicht automatisch überschrieben.
Verbindungsspezifische Adressen bleiben lokal. Der Abgleich ändert keine bestehenden
eBay-Standorte oder Angebote.

Die aktuelle Version enthält auch die bisherigen Verbesserungen:

- 0.9.120: Standard-Versandstandort und optionale Adressausnahmen je Verbindung;
  ausdrücklich bestätigtes Anlegen eines neuen eBay-Standorts.
- 0.9.119: Absturzkorrektur beim Entfernen einer Verbindung mit fehlendem oder
  beschädigtem gespeichertem Zugang.
- 0.9.118: getrennte Skalierung für Oberfläche, Texte und Bedienelemente,
  chronologische Benachrichtigungen ohne Suche und Verbesserungen beim E-Mail-Lesen.
- 0.9.117: überarbeitete Fensterlayouts, einheitliche Reiter der KI-Assistenten
  und Prüfung der zentralen PIM-Kontofreischaltung.
- 0.9.116: einfachere eBay-Einrichtung mit Marktsuche und getrennten Exportangaben.

Für eBay werden das eigene Verkäuferkonto, ein aktiver Versandstandort, passende
Rahmenbedingungen und vollständige Export-Pflichtangaben benötigt. Die Anmeldung
allein veröffentlicht nichts. Verkauf und automatische Preis-/Bestandsübertragung
setzen die ausdrückliche Freigabe der Verbindung und der ausgewählten Produkte voraus.
Rahmenbedingungen können im PIM angelegt und zugeordnet werden. Eine vollständige
Live-Verkaufsabnahme wird durch diese Versionsübersicht nicht behauptet.

Enthält die Zuordnung und Bearbeitung des eigenen Unternehmensprofils aus 0.9.115.
Name und Logo werden mit dem Website-Konto abgeglichen; eingeladene Mitarbeiter
können fremde Unternehmensprofile nicht bearbeiten. Vorhandene lokale Originale
bleiben erhalten. Die Shopwährung bleibt lokal.

Benachrichtigungen behalten kleine Mausradschritte und erreichen bei anhaltendem
Scrollen eine höhere Höchstgeschwindigkeit. Während der eBay-Anmeldung bleiben
Mail und andere PIM-Fenster bedienbar. Der passende Launcher wird über das normale
PIM-Update mitgeliefert und übernommen; ein separates Launcher-Update entfällt.

Enthält die direkte eBay-Echtkonto-Anmeldung aus 0.9.114. Produkte werden nach dem
Verbinden in PIM ausgewählt; die Anmeldung allein veröffentlicht nichts.
Kontoeinstellungen bleiben bei eBay; Verkaufsrichtlinien können im PIM gepflegt werden.
Hinweise und Testgrenzen stehen beim Release.

Ein kontofähiger Launcher ab 0.9.108 ist erforderlich. Eine Kontoanmeldung
synchronisiert keine lokalen Produkte, Preise, Bestände oder Mail-Zugangsdaten.
Die Übernahme eines bisherigen lokalen Unternehmensprofils erfolgt ausdrücklich.

## Setup

[Setup-Informationen](Setup/). Neue Setup-Pakete bleiben vorerst lokal und werden
nicht veröffentlicht. Die Updatepakete sind keine ausführbaren Installer.

Historische signierte Pakete werden nicht überschrieben. Anwendungssourcen,
Signierschlüssel und Zugangsdaten gehören nicht in dieses öffentliche Repository.

[Website](https://beydosh.com/) · [Dokumentation](https://github.com/Beydosh/docs)
