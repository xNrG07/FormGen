# AdSense-/Rechts-Audit – 10.03.2026

Dieses Projekt wurde inhaltlich, technisch und rechtlich grob für eine sauberere AdSense-Einreichung überarbeitet.

## Direkt behobene Punkte

- Eigene Consent-/Werbeeinbindung aus den HTML-Seiten entfernt.
- Datenschutzerklärung auf den aktuellen Zustand angepasst: AdSense derzeit nicht aktiv.
- Google-Fonts-Import entfernt, damit keine unnötige Drittverbindung für Schriftarten aufgebaut wird.
- Veralteten ODR-Hinweis im Impressum ersetzt (EU-ODR-Plattform eingestellt).
- `robots.txt` so bereinigt, dass CSS/JS nicht mehr blockiert werden.
- Startseite korrigiert:
  - 6 statt 7 Vorlagen
  - fehlerhafte/fehlende Mietminderung-Karte entfernt
  - Deutschland-spezifische Bescheid-Vorlage klarer gekennzeichnet
- Rechtlich heikle Formulierungen in den Vorlagen entschärft bzw. aktualisiert:
  - Kündigung: keine pauschalen Kündigungsfristen mehr
  - Mängelrüge: Beweislast/Vermutungsregel korrekt auf das erste Jahr angepasst
  - Mahnung: keine pauschale 40-EUR-Verzugspauschale mehr für alle Fälle
  - Widerruf: Rückerstattung bei Waren korrekt präzisiert
- Leere Register-Sektion im Impressum bereinigt.

## Wichtiger nächster Schritt vor echter AdSense-Aktivierung

Für EWR-/UK-/CH-Traffic sollte keine eigene einfache Cookie-/Consent-Leiste verwendet werden. Vor der echten Aktivierung von AdSense muss eine von Google zertifizierte CMP / Consent-Lösung sauber eingebunden werden.

## Manuell prüfen vor dem Livegang

- Stimmt die finale Domain wirklich mit allen Canonical-URLs und der `sitemap.xml` überein?
- Gehört die Publisher-ID in `ads.txt` wirklich zu deinem AdSense-Konto?
- Sind Name, Adresse und Kontakt im Impressum exakt so gewünscht?
- Soll die Seite zunächst ohne Werbung live gehen und AdSense erst nach Freigabe der CMP aktiviert werden?

