# Übung 3: Context Crafting in OpenCode (Tag 2)

## Ziel
Lernen, wie eine präzise Kontext-Vorbereitung (Mock-Daten, Glossar, Spezifikationen) die Qualität von KI-generiertem Java-Code massiv verbessert.

## Aufgabe
Ihr sollt eine Funktion schreiben, die **Datumsangaben validiert**.
Alle Teams starten mit demselben vagen Basis-Prompt:
> *"Schreibe eine Funktion, die Datumsangaben validiert."*

Eure Aufgabe ist es, das Ergebnis der KI zu verbessern, **ohne** den Prompt selbst zu ändern! Ihr dürft ausschließlich den Kontext im Ordner verbessern.

## Ablauf (25 Minuten)
1. **Rollen**: Gleiche 2er-Teams wie an Tag 1. Rollen (Prompter/Reviewer) alle 10 Minuten tauschen!
2. **Schritt 1 (Mock-Daten)**: Erstellt Testfälle (3-5 Beispiele für gültige und ungültige Datumsformate).
3. **Schritt 2 (Spezifikation)**: Legt fest, welche Java-Klasse (z.B. `java.time.LocalDate`), welches Format (z.B. `yyyy-MM-dd`) und welche Fehlerbehandlung erwartet wird.
4. **Schritt 3 (Glossar)**: Erstellt eine `GLOSSARY.md` mit fachlichen Begriffen (z.B. Definition von "Schaltjahr", "ISO-8601"), damit OpenCode diese Begriffe versteht.
5. **DoD (Definition of Done)**:
   - `GLOSSARY.md` ist im Ordner angelegt.
   - Code ist in `src/main/java/Datum.java` implementiert.
   - Mindestens 1 JUnit-Test in `src/test/java/DatumTest.java` ist grün.
   - Das Ergebnis wurde mit Git committet.

## Dateien
- `pom.xml` (Maven Konfiguration)
- `src/main/java/Datum.java` (Euer Code)
- `src/test/java/DatumTest.java` (Tests)
- `GLOSSARY_TEMPLATE.md` (Vorlage für fachliche Begriffe)
