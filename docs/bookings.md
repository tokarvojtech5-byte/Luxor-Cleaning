# Buchungen & Kontaktoptionen

Optionen, um Kundenbuchungen zu realisieren:

1) Einfache Kontakt-E-Mail (Platzhalterformular)
   - Nutzen Sie das vorhandene Formular in `website/index.html` und richten Sie z.B. Formspree ein
   - Vorteile: kein Backend nötig
   - Nachteil: manuelle Terminvergabe

2) Externe Scheduler (empfohlen für MVP)
   - Calendly, Setmore, Acuity: Einbettbarer Scheduler; Kunden wählen Datum/Zeit und Termine werden automatisch
     in Ihren Kalender gesendet.
   - Integration: embed-Code in `website/index.html` oder Link zur Buchungsseite

3) Eigenes kleines Backend (später)
   - Kurzes Node/Flask/Lambda-Endpoint, der Anfragen verarbeitet, prüft Verfügbarkeit und sendet Bestätigungen.
   - Empfehlung: für mehr Automatisierung, aber erhöht Komplexität und erfordert Hosting.

Empfehlung
- Für den Start: Calendly-Embed oder Formspree für Kontakt-E-Mails. Wenn Sie viele Anfragen erwarten, wechseln Sie später zu
  einem Scheduler mit Kalenderintegration.
