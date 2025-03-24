# Temporäre-Mailer

Temp Mail ist eine GUI-Anwendung, die eine temporäre E-Mail mit dem Dienst mail.tm erstellt.

## Temp Mail Anwendung

Diese Anwendung wurde mit den folgenden Paketen erstellt:
- fyne (Version 2.3.0 oder höher)
- mailtm
- eventsource

## Funktionen
- Erstellt eine temporäre E-Mail
- Anmeldung mit einer bestehenden mail.tm E-Mail
- E-Mail löschen
- Automatische Aktualisierung des Posteingangs mit SSE
- Funktioniert unter Linux und Windows, sollte auch unter MacOS funktionieren (nicht getestet)
- Dunkles Thema

## Voraussetzungen

Um zu kompilieren und auszuführen, müssen Sie Go auf Ihrem Computer installiert haben. Siehe die Installationsanweisungen.

## Installation

```bash
go install github.com/kvnschmu/temporary-mailer```

```Ausführen```

```temporary-mailer```
