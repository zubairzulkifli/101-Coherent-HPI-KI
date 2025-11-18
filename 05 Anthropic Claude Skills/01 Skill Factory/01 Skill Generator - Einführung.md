# 🚀 Claude Skill-Werkstatt: Deine eigene KI-Fähigkeit in 5 einfachen Schritten

Stell dir vor, du könntest Claude beibringen, genau die Aufgaben zu erledigen, die du für deine Arbeit brauchst – wie ein persönlicher Assistent, der perfekt auf dich zugeschnitten ist. Genau das machen "Skills"! Mit dieser Anleitung erstellst du deine eigenen Skills, ganz ohne Vorkenntnisse.

---

## Was ist ein "Skill" überhaupt?

Ein Skill ist wie eine **Fähigkeit** oder ein **Werkzeug**, das du Claude gibst. Du bringst ihm bei, eine bestimmte Aufgabe nach deinen Regeln zu erledigen. Zum Beispiel:

-   Einen **Social-Media-Post** in deinem Markenstil schreiben.
-   Eine **Kunden-E-Mail** zusammenfassen.
-   Eine **Tabelle** mit Verkaufszahlen analysieren.

Du gibst Claude eine Anleitung, und er erledigt die Aufgabe immer wieder perfekt für dich.

---

## Schritt 1: Das Projekt vorbereiten (Dein Werkzeugkasten)

Bevor wir loslegen, richten wir unseren Arbeitsbereich in Claude ein. Das ist wie das Vorbereiten einer Werkbank.

1.  **Öffne Claude** und starte einen neuen Chat.
2.  **Lade die Anleitungen hoch:** Klicke auf die Büroklammer (📎) und lade die offiziellen Anleitungen von Claude hoch. Das ist wie das Handbuch für unsere Werkzeuge. Du musst sie nicht lesen, Claude erledigt das für dich!
    -   [Claude Skills Blog](https://claude.com/blog/skills)
    -   [Claude Skills Dokumentation](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/overview)
    -   [Claude Skills Beispiele (Cookbook)](https://github.com/anthropics/claude-cookbooks/tree/main/skills)
3.  **Lade Beispiel-Skills hoch:** Lade dir von der GitHub-Seite (dem "Cookbook") ein paar Beispiel-Skills als ZIP-Dateien herunter und lade auch diese in Claude hoch. So hat Claude schon mal ein paar fertige Werkzeuge gesehen.

**Dein Chat sollte jetzt so aussehen:** Du hast einen neuen Chat gestartet und mehrere Dateien (Links und ZIPs) hochgeladen. Perfekt! Dein Werkzeugkasten ist bereit.

---

## Schritt 2: Der Master-Prompt (Die Bauanleitung)

Jetzt geben wir Claude die eigentliche **Bauanleitung**, um neue Skills zu erstellen. Dafür verwenden wir einen "Master-Prompt". Das ist ein langer, detaillierter Befehl, der Claude genau sagt, was er tun soll.

**Kopiere den gesamten Text aus der Datei `pasted_content_2.txt` und füge ihn in den Claude-Chat ein.**

### Was steht in diesem Master-Prompt? (Einfach erklärt)

Stell dir vor, du beauftragst einen Handwerker, dir ein Möbelstück zu bauen. Du würdest ihm eine sehr genaue Anleitung geben. Genau das tut dieser Prompt:

1.  **Deine Rolle:** "Du bist ein Experte für die Erstellung von Claude-Skills."
    -   *Bedeutet:* Wir sagen Claude, er soll sich wie ein Profi verhalten.

2.  **Deine Mission:** "Erstelle fertige Skills basierend auf den Ideen des Nutzers."
    -   *Bedeutet:* Claude weiß, sein Ziel ist es, aus deiner Idee einen funktionierenden Skill zu machen.

3.  **Benötigte Komponenten:** Hier listen wir alle Teile auf, die ein guter Skill braucht:
    -   `SKILL.md`: Eine **Anleitungsdatei**, die beschreibt, was der Skill kann und wie man ihn benutzt.
    -   `Python-Skripte (.py)`: **Optionale Code-Dateien** für komplexe Aufgaben wie Berechnungen oder Datenumwandlungen.
    -   `Test-Daten`: **Beispieldateien** (z.B. eine kleine CSV-Tabelle), damit der Skill etwas zum Üben hat.
    -   `sample_prompt.md`: Eine Datei mit **Beispiel-Befehlen**, damit du weißt, wie du den Skill später aufrufst.
    -   `ZIP-Datei`: Eine gepackte Datei, die du einfach in Claude importieren kannst.

4.  **Qualitätsstandards & Design-Prinzipien:** "Jeder Skill muss professionell, klar und nützlich sein."
    -   *Bedeutet:* Wir geben Claude vor, dass er keine halben Sachen machen soll. Jeder Skill soll wie ein hochwertiges Werkzeug sein.

5.  **Benutzer-Konfiguration:** Am Ende des Prompts gibt es einen Abschnitt, den **DU** ausfüllst. Hier sagst du Claude, was für einen Skill du haben möchtest.

**Wichtig:** Du musst nicht jedes Detail des Master-Prompts verstehen. Er ist für Claude geschrieben. Du musst nur wissen, wie du ihn am Ende ausfüllst.

---

## Schritt 3: Deine Idee formulieren (Der Bauplan)

Jetzt kommst du ins Spiel! Am Ende des Master-Prompts findest du den Abschnitt **"User Configuration Variables"**. Hier beschreibst du deine Idee. Fülle die folgenden Punkte direkt im Chat aus:

-   `BUSINESS_TYPE`: In welcher Branche arbeitest du? (z.B. "Ich bin im Marketing für ein Technologie-Unternehmen.")
-   `USE_CASES`: Welche Aufgabe soll der Skill erledigen? (z.B. "Ich möchte einen Skill, der mir hilft, Blog-Artikel über unsere Produkte zu schreiben.")
-   `NUMBER_OF_SKILLS`: Wie viele Skills sollen erstellt werden? (Für den Anfang ist `1` eine gute Wahl.)
-   `COMPLEXITY_LEVEL`: Wie kompliziert soll der Skill sein? (Wähle `beginner` für den Start.)

**Beispiel für deine Eingabe:**

```
BUSINESS_TYPE: Ich arbeite im Marketing für ein Software-Unternehmen.
USE_CASES:
- Einen LinkedIn-Post aus einem langen Blog-Artikel erstellen.
NUMBER_OF_SKILLS: 1
COMPLEXITY_LEVEL: beginner
PYTHON_PREFERENCE: minimal
```

---

## Schritt 4: Claude die Arbeit machen lassen (Die Fertigung)

Nachdem du deine Idee formuliert hast, drücke "Enter". Claude wird nun den Master-Prompt und deine Idee verarbeiten und dir einen kompletten, fertigen Skill erstellen. Er wird dir alle notwendigen Dateien und Inhalte direkt im Chat ausgeben:

-   Den Inhalt für die `SKILL.md`.
-   Den Inhalt für die `sample_prompt.md`.
-   Anweisungen, wie du die ZIP-Datei erstellst.

---

## Schritt 5: Deinen neuen Skill nutzen (Das Werkzeug einsetzen)

Jetzt hast du deinen ersten eigenen Skill! Folge den Anweisungen von Claude, um die `SKILL.md` in eine ZIP-Datei zu packen und diese in Claude hochzuladen.

Sobald der Skill importiert ist, kannst du ihn mit den Befehlen aus der `sample_prompt.md` sofort ausprobieren.


# Der Mega Prompt, um mit den Ressourcen neue Skills zu erstellen




