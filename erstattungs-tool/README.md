# Arztrechnungen Abgleich

Tracker für Arztrechnungen der Familie: Einreichung bei der BVAEB (meineSV) und Erstattung durch die Zusatzversicherung.

- **Kinder** → Merkur Versicherung (Portal: portal.merkur.at → „Meine Einreichungen“)
- **Tobias** → UNIQA Lehrergruppen-Krankenversicherung, Privatarzttarif (myUNIQA)

Zuordnung passiert automatisch über die Person und kann pro Rechnung überschrieben werden.

## Automatische Prüfungen (3 Stufen)

1. **Plausibilität**: Erstattungen höher als die Rechnung, Datum in falscher Reihenfolge, falsche Zusatzversicherung für die Person.
2. **Offene Lücken**: BVAEB erledigt, aber nicht bei Merkur/UNIQA eingereicht; über 8 Wochen ohne Erstattung.
3. **Dubletten & Vollständigkeit**: gleiche Rechnung doppelt erfasst; fehlender Arzt oder Betrag.

## Daten

Die Seite (`index.html`) läuft als claude.ai-Artifact. Die Rechnungen liegen im Artifact-Datenspeicher (Sammlung `eintraege`) und sind nur für den Eigentümer lesbar. Es stehen **keine** Gesundheitsdaten in diesem Repository.

Import: Spalten aus Excel oder meineSV kopieren und über „Liste einfügen“ einfügen. Export: CSV (Strichpunkt, Excel-kompatibel).
