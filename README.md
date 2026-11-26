# Claude Skills

Meine eigenen Skills für Claude. Jeder Skill liegt in einem eigenen Ordner unter `skills/` und hat zwei Dateien:

- `SKILL.md`: die Anleitung, die Claude liest
- `tests.md`: meine Testfälle, mit denen ich prüfe, ob der Skill gut funktioniert

## Übersicht

| Skill | Befehl | Wofür |
|---|---|---|
| [Deutsch Coach](skills/dc) | `/dc` | Korrigiert meine Texte und erklärt typische Fehler |
| [Behörden und Vertragsbriefe](skills/behoerden-und-vertragsbriefe) | `/behoerden-und-vertragsbriefe` | Formelle Briefe an Vermieter, Versicherungen, Ämter |
| [Tarif und Vertragsvergleich](skills/tarif-und-vertragsvergleich) | `/tarif-und-vertragsvergleich` | Strom, Kfz Versicherung, Handy: günstigere Tarife finden |
| [KI im Klartext Shorts](skills/ki-im-klartext-shorts) | `/ki-im-klartext-shorts` | YouTube Shorts für meinen Kanal produzieren |

## So entwickle ich einen Skill weiter

1. **Bauen:** Idee in Claude beschreiben, Skill vorschlagen lassen und speichern.
2. **Testen:** Die Testfälle aus `tests.md` in einem neuen Chat ausprobieren.
3. **Bewerten:** Pro Test notieren: ✅ gut, ⚠️ teilweise, ❌ schlecht und warum.
4. **Verbessern:** Claude sagen, was nicht gepasst hat, und die Änderung übernehmen.
5. **Hier aktualisieren:** `SKILL.md` und `tests.md` anpassen, Änderung im Changelog notieren.

## Neuen Skill anlegen

Kopiere den Ordner [`vorlage`](vorlage) und benenne ihn um.

## Nützliche Links

- [Offizielle Skill Beispiele von Anthropic](https://github.com/anthropics/skills)
- [Agent Skills Standard](https://github.com/agentskills/agentskills)
- [Claude Cookbooks](https://github.com/anthropics/claude-cookbooks)
