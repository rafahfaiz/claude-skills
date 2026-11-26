# Tests: dc

| # | Eingabe | Erwartung | Ergebnis | Notiz |
|---|---|---|---|---|
| 1 | `/dc ich habe gestern die videos fertig gemacht` | Korrigierte Fassung zuerst, Groß und Kleinschreibung erklärt | ⬜ | |
| 2 | `/dc` ohne Text | Korrigiert die letzte Nachricht | ⬜ | |
| 3 | `/dc ein Skill, wo mir hilft` | Erkennt typischen Fehler „wo“ → „der“ | ⬜ | |
| 4 | Text ohne Fehler | Lobt kurz, erfindet keine Fehler | ⬜ | |

Legende: ✅ gut · ⚠️ teilweise · ❌ schlecht · ⬜ noch nicht getestet

## Changelog

- v1 (11/2026): erste Version
