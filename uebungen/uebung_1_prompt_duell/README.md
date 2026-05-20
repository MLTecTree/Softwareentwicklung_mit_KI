# Übung 1: Prompt-Duell mit OpenCode (Tag 1)

## Ziel
Implementiert eine deutsche Kennzeichen-Validierung mit dem Coding-Agenten `opencode` im Terminal.

## Aufgabe
Schreibt eine Funktion `validate_kennzeichen(s: str) -> bool`, die prüft, ob ein deutsches Autokennzeichen gültig ist:
- **Format**: `1-3 Buchstaben` (Ortskürzel), `Bindestrich`, `1-2 Buchstaben`, `1-4 Ziffern` (z.B. `AC-AB1234`, `DN-X1`).

## Ablauf (30 Minuten)
1. **Rollenverteilung**: 2er-Teams. Ein *Prompter* (schreibt Prompts und steuert OpenCode) und ein *Reviewer* (prüft den Code und gibt Feedback). Nach 10 Minuten Rollen tauschen!
2. **Spontaner Start**: Startet OpenCode mit `opencode` und gebt einen schnellen, spontanen Prompt ein, ohne vorher lange nachzudenken.
3. **Beobachtung**: Wie gut schlägt sich die KI beim ersten Versuch? Welche Fehler oder Edge-Cases (Randfälle) übersieht sie?
4. **Korrektur**: Korrigiert Fehler durch Anschlussprompts.

## Dateien
- `kennzeichen.py` (Euer Code)
- `test_kennzeichen.py` (Tests)
