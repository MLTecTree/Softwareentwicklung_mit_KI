# Softwareentwicklung mit KI 🚀
### Zweitägiger Praxis-Workshop für MATSE-Auszubildende (Juni 2026)

Willkommen im Repository für den Workshop **"Softwareentwicklung mit KI"**. 

In diesem zweitägigen Workshop lernen wir, wie wir KI-Modelle nicht nur als einfache Chat-Partner, sondern als produktive **Coding Agents** im Terminal steuern, wie wir durch präzisen Kontext die Codequalität maximieren und wie wir durch automatisierte Tests und Linter verlässliche Absicherungen (Leitplanken) einbauen.

---

## 🎯 Lernziele

*   **Coding Agents beherrschen**: Einen terminalbasierten Coding Agenten (`opencode` oder `claude-code`) autonom steuern.
*   **Vom Konzept zur Spec**: Aus vagen Ideen im Dialog mit der KI präzise, umsetzbare Spezifikationen (Mini-Specs) formulieren.
*   **Absicherung & Qualität**: KI-generierten Code mit automatisierten Tests (pytest) und Lintern (ruff) absichern.
*   **Werkzeug vor Modell**: Verstehen, warum das Orchestrierungs-Harness (Tools, Planung, Gedächtnis) wichtiger ist als das reine LLM-Modell.
*   **Grenzen & Verantwortung**: Risiken (Halluzinationen, Datenschutz, Urheberrecht) kennen und aktiv bewerten.

---

## 📅 Agenda & Ablauf

### Tag 1 — Wie steuere ich KI sinnvoll?
*   **0:00 — Check-In**: Erwartungen & Kennenlernen
*   **0:15 — Konzepte**: LLM, Prompting, Kontext und der Unterschied zwischen **Chat vs. Agent**
*   **0:40 — Setup**: Hype vs. Realität und Einrichtung der Tools (`opencode`)
*   **1:10 — Prompting-Grundlagen**: Mock-Daten & der `/grill-me` Skill
*   **1:40 — Pause** ☕
*   **1:55 — Übung 1**: Prompt-Duell mit OpenCode (Spontanes Coden im Team)
*   **2:25 — Spezifikation**: Warum "erst spezifizieren, dann generieren" gewinnt
*   **2:55 — Übung 2**: Eigene Mini-Spec für ein Feature schreiben
*   **3:30 — Review**: Spec-Reviews & Leitplanken
*   **3:55 — Reflexion**: Abschluss Tag 1

### Tag 2 — Wie prüfe ich KI professionell?
*   **0:00 — Rückblick & Ausblick**
*   **0:15 — Modell-Auswahl**: Welches Modell für welche Aufgabe?
*   **0:30 — Das Harness**: Planung, Tools und Fehlerbehandlung von Agenten
*   **1:00 — Übung 3**: Context Crafting (Codequalität über Kontext steuern)
*   **1:40 — Pause** ☕
*   **1:55 — Qualität**: "Bad code is the most expensive it's ever been" & statische Analyse
*   **2:15 — Übung 4**: Test-Driven Development (TDD) mit OpenCode
*   **2:55 — Übung 5**: Eigene Mini-Spec aus Tag 1 komplett umsetzen
*   **3:45 — Reflexion & Feedback**: Was nehmen wir mit in den Alltag?

---

## 🛠️ Unsere Werkzeuge im Workshop

Wir arbeiten im Terminal mit **OpenCode**, einem extrem leistungsfähigen Open-Source-Agenten:
*   **Harnessed Execution**: Er kann Dateien lesen, editieren, neue Dateien schreiben, Suchen durchführen und Befehle im Terminal direkt ausführen.
*   **Interaktive Skills**:
    *   `/grill-me`: Befragt dich kritisch zu deinem Entwurf, um Lücken in deiner Spezifikation aufzudecken, bevor Code geschrieben wird.
    *   `/tdd`: Führt dich Schritt für Schritt durch die testgetriebene Entwicklung (Red-Green-Refactor).

---

## 📂 Die Praxis-Übungen (Workshop-Verzeichnisse)

Hier findest du die vorbereiteten Verzeichnisse und Aufgabenstellungen für alle Übungseinheiten:

1.  **[Übung 1: Prompt-Duell](./uebungen/uebung_1_prompt_duell/)** (Tag 1)  
    *Deutsches Autokennzeichen validieren.* Erlebe den Unterschied zwischen schnellem Prompting und inkrementeller Korrektur.
2.  **[Übung 2: Mini-Spec schreiben](./uebungen/uebung_2_mini_spec/)** (Tag 1)  
    *Vom Konzept zum präzisen 6-Felder-Dokument.* Erstelle eine Spezifikation, die fehlerfreie KI-Generierung garantiert.
3.  **[Übung 3: Context Crafting](./uebungen/uebung_3_context_crafting/)** (Tag 2)  
    *Datum validieren.* Verbessere das KI-Ergebnis ausschließlich über Mock-Daten und ein fachliches `GLOSSARY.md`, ohne den Prompt zu ändern.
4.  **[Übung 4: TDD mit OpenCode](./uebungen/uebung_4_tdd/)** (Tag 2)  
    *Testgetriebenes Kennzeichen-Validieren.* Nutze den `/tdd` Skill, um die KI Schritt für Schritt sicher durch Randfälle zu führen.
5.  **[Übung 5: Spec-Umsetzung](./uebungen/uebung_5_spec_umsetzung/)** (Tag 2)  
    *Das große Finale.* Setze deine Spezifikation aus Übung 2 komplett mit Glossar, Tests, Linter und Commits um.

---

## 🚨 Leitplanken gegen KI-Fehler (Die 5-Punkte-Checkliste)

Wenn du Code von einem Agenten prüfen oder generieren lässt, achte stets auf diese 5 Punkte:
1.  **Erfüllt es die Aufgabe?** (Spec danebenlegen und Punkt für Punkt prüfen)
2.  **Randfälle bedacht?** (Leere Eingaben, Null-Werte, unerwartete Formate)
3.  **Gibt es Sicherheitskonflikte?** (SQL-Injections, hartcodierte Secrets/Passwörter)
4.  **Sind Struktur & Namen lesbar?** (Verständliche Variablennamen, Funktionslängen)
5.  **Wo halluziniert der Code?** (Nicht existierende Bibliotheken, erfundene Parameter)

---

Viel Erfolg und viel Spaß beim Experimentieren im Workshop! 💻✨
