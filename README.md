# Takt

Privates Zyklus-Tracking als Web-App für das iPhone.

- Alle Einträge bleiben im lokalen Speicher des Geräts. Kein Server, kein Konto, keine Analyse-Tools.
- Die Content-Security-Policy verbietet der App jede Verbindung zu Servern (`connect-src 'none'`).
- Backups werden mit einem Passwort verschlüsselt (AES-GCM, PBKDF2-SHA256).

Dateien: `index.html` (die App), `manifest.webmanifest`, `sw.js` (Offline-Nutzung), `icon-180.png`, `icon-512.png`.

Demo mit Beispieldaten: die Adresse der App mit `#demo` am Ende öffnen. Die Demo nutzt einen eigenen Speicher und berührt deine echten Daten nicht.

Keine Verhütungs-App, kein Medizinprodukt.
