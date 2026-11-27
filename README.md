# Arztrechnungen

Web-App zum Verwalten von Arztrechnungen für Beihilfe-Berechtigte mit privater Krankenversicherung:

1. **Überweisen**: Zahlungsfrist, IBAN und Verwendungszweck im Blick
2. **Einreichen** bei Beihilfe und PKV, mit Warnung vor Ablauf der Beihilfe-Antragsfrist
3. **Erstattung prüfen**: Geldeingang mit Betrag erfassen, Abweichungen und Eigenanteil sehen

Rechnungen lassen sich per Foto oder als PDF einlesen, auch mehrseitig. Die Felder werden automatisch ausgefüllt.

**Webadresse:** https://johnnyp68.github.io/Ki-ler/

## Datenschutz

- Die Texterkennung läuft direkt auf dem Gerät. Rechnungsbilder werden nicht hochgeladen.
- Alle Rechnungsdaten liegen nur im Browser des jeweiligen Geräts, nicht in diesem Repository und auf keinem Server.
- Aus dem Internet geladen werden nur die Programmbibliotheken (Tesseract.js, pdf.js) von öffentlichen CDNs.
- Bitte regelmäßig über „Sichern (JSON)“ eine Kopie anlegen.

## Webseite einschalten (einmalig)

1. Auf GitHub das Repository öffnen: **Settings → Pages**
2. Bei **Source** „Deploy from a branch“ wählen, Branch `claude/vibrant-cannon-01lhea`, Ordner `/ (root)`, **Save**
3. Nach 1–2 Minuten ist die Seite unter der obigen Adresse erreichbar.

Hinweis: Für private Repositories gibt es GitHub Pages nur mit GitHub Pro. Alternativ das Repository unter
**Settings → General → Danger Zone → Change visibility** auf „Public“ stellen. Es enthält nur Programmcode, keine persönlichen Daten.

## Auf dem Handy als App nutzen

- **iPhone (Safari):** Teilen-Symbol → „Zum Home-Bildschirm“
- **Android (Chrome):** Menü ⋮ → „App installieren“ bzw. „Zum Startbildschirm hinzufügen“

Wichtig: Die App vom Startbildschirm und die Webseite im Browser haben auf dem iPhone getrennte Speicher.
Bitte immer denselben Weg nutzen.
