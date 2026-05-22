# Übung 1: Prompt-Duell mit OpenCode (Tag 1)

## Ziel
Implementiert eine deutsche Kennzeichen-Validierung mit dem Coding-Agenten `opencode` im Terminal unter Verwendung von Java.

## Aufgabe
Schreibt eine statische Methode `boolean validateKennzeichen(String s)` in der Klasse `Kennzeichen` (`src/main/java/Kennzeichen.java`), die prüft, ob ein deutsches Autokennzeichen gültig ist:
- **Format**: `1-3 Buchstaben` (Ortskürzel), `Bindestrich`, `1-2 Buchstaben`, `1-4 Ziffern` (z.B. `AC-AB1234`, `DN-X1`).

## Ablauf (30 Minuten)
1. **Rollenverteilung**: 2er-Teams. Ein *Prompter* (schreibt Prompts und steuert OpenCode) und ein *Reviewer* (prüft den Code und gibt Feedback). Nach 10 Minuten Rollen tauschen!
2. **Spontaner Start**: Startet OpenCode mit `opencode` im aktuellen Übungs-Ordner und gebt einen schnellen, spontanen Prompt ein, ohne vorher lange nachzudenken.
3. **Beobachtung**: Wie gut schlägt sich die KI beim ersten Versuch? Welche Fehler oder Edge-Cases (Randfälle) übersieht sie?
4. **Korrektur**: Korrigiert Fehler durch Anschlussprompts.
5. **Kompilieren und Testen**: Lasst die KI euer Projekt mit Maven kompilieren und testen (`mvn clean test`).

## Dateien
- `pom.xml` (Maven Konfiguration)
- `src/main/java/Kennzeichen.java` (Euer Code)
- `src/test/java/KennzeichenTest.java` (Tests mit JUnit 5)
