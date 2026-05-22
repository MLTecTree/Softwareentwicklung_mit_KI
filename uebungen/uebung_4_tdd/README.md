# Übung 4: Test-Driven Development (TDD) mit OpenCode (Tag 2)

## Ziel
Den TDD-Zyklus (Red-Green-Refactor) im Zusammenspiel mit dem `/tdd` Skill von OpenCode erleben und verstehen, wie die KI sich durch Tests selbst korrigiert.

## Aufgabe
Implementiert die deutsche Kennzeichen-Validierung von Tag 1 erneut – diesmal aber streng **Test-Driven** in Java!

## Ablauf (30 Minuten)
1. **Vorbereitung**: Nutzt die Struktur in `src/test/java/KennzeichenTest.java`.
2. **Schritt 1 (Red)**: Schreibt den ersten, scheiternden JUnit-Test für einen Randfall.
3. **Schritt 2 (Green)**: Ruft den `/tdd`-Skill in OpenCode auf. Der Agent liest den Test, schreibt minimalen Java-Code, um ihn zu bestehen, und führt den Test mit `mvn test` aus.
4. **Schritt 3 (Refactor)**: Lasst die KI den Code refactoren, solange die Tests grün sind.
5. **Wiederholen**: Schreibt den nächsten Test (nächster Randfall), seht ihn fehlschlagen und lasst die KI wieder auf grün stellen.
6. **DoD (Definition of Done)**:
   - Mindestens 5 verschiedene Tests wurden geschrieben.
   - Mindestens 5 TDD-Iterationen (Red -> Green -> Refactor) wurden erfolgreich durchgeführt.

## Dateien
- `pom.xml`
- `src/main/java/Kennzeichen.java`
- `src/test/java/KennzeichenTest.java`
