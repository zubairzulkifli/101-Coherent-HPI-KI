# 🎯 Anleitung: Wie man einen Skill-Prompt erstellt

---

## 📚 Was ist ein Skill-Prompt?

Ein **Skill-Prompt** ist eine strukturierte Anleitung, die Sie einem KI-Assistenten geben, damit er ein wiederverwendbares Skill für Sie erstellt. 

**Denken Sie daran wie an eine Vorlage für Ihre tägliche Arbeit:**
- Sie beschreiben einmal genau, WAS das Skill können soll
- Die KI erstellt daraus ein fertiges Skill
- Danach können Sie das Skill immer wieder nutzen – wie eine Vorlage, die Sie für ähnliche Aufgaben verwenden

**Für Coherent-Mitarbeiter bedeutet das:**
Egal ob Sie im Marketing, HR, Sales oder Engineering arbeiten – Skills helfen Ihnen, wiederkehrende Aufgaben effizienter zu erledigen. Sie müssen kein KI-Experte sein, um ein Skill zu erstellen. Dieser Workshop zeigt Ihnen Schritt für Schritt, wie es geht.

**💡 Ein praktisches Beispiel:**
Stellen Sie sich vor, Sie schreiben jede Woche Newsletter-Betreffzeilen für Coherent-Produkte. Anstatt jedes Mal von vorne anzufangen, erstellen Sie einmal ein "Hook Creator"-Skill. Danach geben Sie nur noch das Produkt ein, und die KI generiert automatisch 10 verschiedene Betreffzeilen-Vorschläge für Sie – in Sekunden statt Stunden.

---

## 🔍 Analyse des "Hook Creator" Beispiel-Prompts

Schauen wir uns an, wie der Beispiel-Prompt aufgebaut ist und **WARUM** das wichtig ist:

### 1️⃣ Klare Zielsetzung am Anfang

```markdown
Help me create a Skill called "Hook Creator" that generates 
attention-grabbing headlines and hooks for marketing content.
```

**Was passiert hier?**
- ✅ Gibt dem Skill einen **eindeutigen Namen** ("Hook Creator")
- ✅ Erklärt in **einem Satz**, was das Skill macht
- ✅ Definiert den **Anwendungsbereich** (Marketing Content)

**💡 Lernen Sie daraus:**
Beginnen Sie immer mit einer klaren, einfachen Beschreibung. Die KI muss sofort verstehen, wofür das Skill da ist – genau wie eine Kollegin, der Sie Ihre Aufgabe erklären würden.

**Bei Coherent könnte das sein:**

**Für Marketing:**
```markdown
Erstelle ein Skill namens "Coherent Product Story Creator", 
das überzeugende Produktgeschichten für unsere Laser-, 
Networking- und Materials-Lösungen erstellt.
```

**Für Sales:**
```markdown
Erstelle ein Skill namens "Customer Email Responder", 
das professionelle Antworten auf Kundenanfragen zu 
Coherent-Produkten formuliert.
```

**Für HR:**
```markdown
Erstelle ein Skill namens "Job Description Generator", 
das ansprechende Stellenausschreibungen für Coherent erstellt, 
die unsere I CARE Werte widerspiegeln.
```

---

### 2️⃣ Skill Purpose (Zweck des Skills)

```markdown
## Skill Purpose
This skill should help me quickly generate 5-10 hook options 
for any marketing content using proven copywriting frameworks...
```

**Was passiert hier?**
- ✅ Erklärt das **Hauptziel** detaillierter
- ✅ Gibt **konkrete Zahlen** an (5-10 Optionen)
- ✅ Nennt **Methoden** (Copywriting Frameworks)

**💡 Lernen Sie daraus:**
Dieser Abschnitt ist das "Warum". Er erklärt, welches Problem das Skill löst und wie es das tut. Je klarer Sie das definieren, desto besser wird das Ergebnis.

**Für Coherent Marketing:**
```markdown
## Zweck des Skills
Dieses Skill soll Marketing-Mitarbeitern helfen, aufmerksamkeitsstarke 
Headlines für Coherent-Produktankündigungen zu erstellen. Das Skill 
generiert 5-10 Varianten, die:
- Die Tagline "Innovations That Resonate" widerspiegeln
- Unsere wissenschaftliche Expertise und Innovation betonen
- Für verschiedene Zielmärkte (Industrial, Communications, 
  Electronics, Instrumentation) geeignet sind
- Die Coherent Brand Voice (Wissenschaftlich, Innovativ, 
  Vertrauenswürdig, Zugänglich) einhalten
```

**Für Coherent HR:**
```markdown
## Zweck des Skills
Dieses Skill soll HR-Teams helfen, ansprechende Stellenausschreibungen 
zu erstellen, die:
- Unsere I CARE Werte (Integrity, Collaboration, Accountability, 
  Respect, Enthusiasm) kommunizieren
- Die richtige Balance zwischen fachlicher Expertise und 
  Unternehmenskultur finden
- Kandidaten aus verschiedenen Bereichen (Engineering, Administration, 
  Marketing, Sales) ansprechen
```

---

### 3️⃣ When to Use This Skill (Wann wird es genutzt?)

```markdown
## When to Use This Skill
Invoke this skill whenever I need to:
- Write email subject lines
- Create social media hooks
- Draft ad headlines
...
```

**Was passiert hier?**
- ✅ Listet **konkrete Anwendungsfälle** auf
- ✅ Hilft der KI zu erkennen, **wann** das Skill relevant ist
- ✅ Gibt Ihnen als Nutzer **Orientierung** für die Verwendung

**💡 Lernen Sie daraus:**
Je klarer Sie definieren, WANN das Skill verwendet wird, desto besser kann die KI es automatisch erkennen und vorschlagen.

**Für Coherent Marketing wäre das:**
```markdown
## When to Use This Skill
Invoke this skill whenever I need to:
- Schreibe E-Mail-Betreffzeilen für Produktankündigungen
- Erstelle LinkedIn-Posts über Coherent-Technologien
- Formuliere Headlines für Pressemitteilungen
- Entwickle Taglines für Messeauftritte (z.B. LASER World of PHOTONICS)
- Schreibe Social-Media-Posts für neue Produkte
- Erstelle Überschriften für Blog-Artikel über Photonik-Themen
```

**Für Coherent Sales:**
```markdown
## When to Use This Skill
Invoke this skill whenever I need to:
- Erstelle Angebots-Zusammenfassungen für Kunden
- Schreibe E-Mail-Antworten auf Kundenanfragen
- Formuliere Value Propositions für spezifische Branchen 
  (z.B. Automotive für SiC-Produkte, Datacom für Transceiver)
- Erstelle Executive Summaries für Kundenpräsentationen
- Bereite Follow-up-E-Mails nach Kundenmeetings vor
```

**Für Coherent HR:**
```markdown
## When to Use This Skill
Invoke this skill whenever I need to:
- Schreibe Stellenausschreibungen für verschiedene Positionen
- Erstelle Welcome-E-Mails für neue Mitarbeiter
- Formuliere interne Ankündigungen zu Unternehmensereignissen
- Verfasse Job-Posting-Texte für LinkedIn und Karriereseiten
- Erstelle Beschreibungen für Ausbildungs- und Praktikumsplätze
```

**Für Coherent Administration:**
```markdown
## When to Use This Skill
Invoke this skill whenever I need to:
- Erstelle professionelle E-Mail-Vorlagen für häufige Anfragen
- Schreibe Meeting-Zusammenfassungen und Protokolle
- Formuliere interne Kommunikation zu Prozessänderungen
- Erstelle Anleitungen für Office-Prozesse
- Verfasse Nachrichten für Team-Updates
```

---

### 4️⃣ Required Inputs (Benötigte Eingaben)

```markdown
## Required Inputs
When I invoke this skill, ask me for:
1. [Content type] - email, social post, ad, landing page, etc.
2. [Target audience] - who I'm writing for
3. [Main benefit or promise] - what the content delivers
4. [Tone] - professional, casual, urgent, playful, etc.
```

**Was passiert hier?**
- ✅ Definiert, welche **Informationen** die KI vom Nutzer braucht
- ✅ Gibt **Beispiele** für jede Eingabe
- ✅ Macht das Skill **interaktiv** – die KI stellt gezielte Fragen

**💡 Lernen Sie daraus:**
Das ist der wichtigste Teil! Sie sagen der KI genau, welche Informationen sie VOR der Arbeit von Ihnen erfragen soll. Dadurch werden die Ergebnisse viel präziser und nützlicher für Ihre konkrete Situation.

**Für ein Coherent Marketing-Skill wäre das:**
```markdown
## Required Inputs
When I invoke this skill, ask me for:
1. [Produktbereich] - Networking (Transceiver, VCSEL), Materials 
   (SiC, Optiken), Lasers (Faserlaser, Ultrakurzpulslaser, CO2-Laser)
2. [Zielmarkt] - Industrial, Communications, Electronics, Instrumentation
3. [Zielgruppe] - CTO/Engineering-Entscheider, Procurement-Manager, 
   End-User, allgemeine Öffentlichkeit
4. [Content-Typ] - LinkedIn-Post, Pressemitteilung, E-Mail-Betreffzeile, 
   Messebanner, Produktdatenblatt-Headline
5. [Hauptbotschaft] - Was ist der zentrale Nutzen? (z.B. "800G-Transceiver 
   ermöglichen schnellere KI-Rechenzentren", "SiC verbessert E-Mobilität")
6. [Tonalität] - Wissenschaftlich-präzise, innovativ-inspirierend, 
   vertrauenswürdig-erfahren, oder zugänglich-praxisnah
```

**Für ein Coherent Sales-Angebots-Skill:**
```markdown
## Required Inputs
When I invoke this skill, ask me for:
1. [Kundenbranche] - Automotive, Semiconductor Manufacturing, 
   Datacom/Telecom, Medical/Life Sciences, Aerospace & Defense
2. [Produktlösung] - Welches Coherent-Produkt? (z.B. 800G Transceiver, 
   SiC Substrate, Ultrakurzpulslaser, VCSEL Arrays)
3. [Kundenherausforderung] - Welches Problem lösen wir? 
   (z.B. "Höhere Datenraten im Rechenzentrum", "Effizientere EV-Batterieproduktion")
4. [Projektzeitrahmen] - Pilotphase (3-6 Monate), Rollout (6-12 Monate), 
   Langfristpartnerschaft
5. [Key Decision Maker] - CTO, VP Engineering, Procurement Director, 
   Plant Manager
6. [Hauptargument] - Technischer Vorteil (Performance), Wirtschaftlich (ROI/TCO), 
   oder Strategisch (Zukunftssicherheit)
```

---

### 5️⃣ Output Format (Wie soll das Ergebnis aussehen?)

```markdown
## Output Format
Generate 10 hook options using at least 5 different frameworks. 
For each hook:
- Present the hook text
- Label which framework was used in parentheses
- Keep hooks under 100 characters when possible
```

**Was passiert hier?**
- ✅ Definiert die **Struktur** der Ausgabe
- ✅ Gibt **Formatierungsvorgaben** (z.B. Zeichenlimit)
- ✅ Erklärt, wie die Ergebnisse **präsentiert** werden sollen

**💡 Lernen Sie daraus:**
Je präziser Sie das Format beschreiben, desto konsistenter und nützlicher sind Ihre Ergebnisse. Das spart Ihnen Zeit beim Nachbearbeiten.

**Für ein Coherent Marketing Hook Creator Skill:**
```markdown
## Output Format
Erstelle 10 Hook-Varianten unter Verwendung von mindestens 5 verschiedenen 
Copywriting-Frameworks. Für jede Hook:

**Struktur:**
1. Hook-Text (unter 100 Zeichen für E-Mail-Betreffzeilen, 
   bis 150 Zeichen für LinkedIn)
2. Framework-Label in Klammern (z.B. "Before-After-Bridge", "Problem-Agitation-Solution")
3. Kurze Begründung, warum dieser Hook für Coherent funktioniert
4. Empfohlener Anwendungsfall (z.B. "LinkedIn-Post für Networking-Segment", 
   "Pressemitteilungs-Headline")

**Coherent-spezifische Anforderungen:**
- Integriere wo möglich die Tagline "Innovations That Resonate"
- Verwende Coherent-Terminologie (z.B. "Photonik-Leader", "vertikal integriert", 
  "von Materialien bis zu Systemen")
- Reflektiere die Brand Voice: Wissenschaftlich, Innovativ, Vertrauenswürdig, Zugänglich
- Berücksichtige den Zielmarkt (Industrial, Communications, Electronics, Instrumentation)
- Vermeide übertriebene Marketing-Sprache – bleibe faktisch und präzise

**Beispiel-Output:**
1. "800G-Transceiver: Die Photonen-Autobahn für KI-Rechenzentren" 
   *(Metapher-Framework)*
   - Erklärt komplexe Technologie zugänglich
   - Empfohlen für: LinkedIn-Post, Targeting: Datacenter-Operators

2. "Von 50ms zu 5ms: Wie Coherent die Latenz in Ihrer Datacenter-Infrastruktur 
   revolutioniert" *(Before-After-Bridge)*
   - Zeigt konkreten, messbaren Nutzen
   - Empfohlen für: E-Mail-Kampagne an CTOs im Communications-Markt
```

**Für ein Coherent HR Job-Description-Skill:**
```markdown
## Output Format
Erstelle eine vollständige Stellenausschreibung mit folgender Struktur:

**1. Attention-Grabbing Headline (1 Zeile)**
- Macht die Position attraktiv und spiegelt Coherent-Kultur wider

**2. Einleitung: Über Coherent (2-3 Sätze)**
- Kurze Vorstellung: "Coherent ist ein globaler Photonik-Leader..."
- Tagline einbinden: "Innovations That Resonate"
- Hauptprodukte/Märkte nennen

**3. Ihre Rolle bei uns (3-4 Bulletpoints)**
- Was macht die Position spannend?
- Welchen Impact hat die Rolle?
- Wie passt sie zur Coherent-Mission?

**4. Das bringen Sie mit (5-7 Bulletpoints)**
- Must-Have Qualifikationen
- Nice-to-Have Skills
- Persönliche Eigenschaften (im Kontext der I CARE Werte)

**5. Das bieten wir Ihnen (5-6 Bulletpoints)**
- Konkrete Benefits
- Entwicklungsmöglichkeiten
- Arbeitskultur-Aspekte
- Verweis auf I CARE Werte

**6. So bewerben Sie sich**
- Call-to-Action
- Kontaktdaten
- Hinweis auf Chancengleichheit

**Coherent-spezifische Anforderungen:**
- Verwende die offizielle Unternehmensvorstellung aus dem Coherent-Styleguide
- Integriere I CARE Werte authentisch (Integrity, Collaboration, Accountability, 
  Respect, Enthusiasm)
- Vermeide Fachjargon, der Bewerbende abschrecken könnte
- Betone globale Präsenz (130+ Standorte, 20+ Länder) wenn relevant
- Für technische Rollen: Erwähne spezifische Technologien/Produkte
- Für nicht-technische Rollen: Erkläre, wie die Position das Business unterstützt
```

---

### 6️⃣ Copywriting Frameworks (Für Marketing-Skills)

```markdown
## Copywriting Frameworks to Use

1. **AIDA (Attention, Interest, Desire, Action)**
   - Grab attention with surprising fact
   - Build interest with unique benefit
   - Create desire with transformation promise
   - End with clear action

2. **Problem-Agitation-Solution (PAS)**
   - State the problem clearly
   - Agitate by showing consequences
   - Present solution as relief

[... weitere Frameworks ...]
```

**Was passiert hier?**
- ✅ Definiert **bewährte Methoden**, die die KI nutzen soll
- ✅ Gibt **konkrete Anleitungen** für jede Methode
- ✅ Sorgt für **Vielfalt** in den Ergebnissen

**💡 Lernen Sie daraus:**
Frameworks sind wie Rezepte – sie geben der KI eine bewährte Struktur. Für Coherent sollten diese Frameworks unsere wissenschaftliche, innovative und vertrauenswürdige Brand Voice widerspiegeln.

**Coherent-angepasste Copywriting Frameworks:**

```markdown
## Copywriting Frameworks für Coherent Marketing

1. **AIDA (Attention, Interest, Desire, Action) – Coherent-Stil**
   - **Attention**: Beginne mit technischer Innovation oder Markttrend 
     (z.B. "KI-Rechenzentren brauchen 3x mehr Bandbreite")
   - **Interest**: Zeige Coherent-Lösung mit konkreten Specs 
     (z.B. "Unsere 800G-Transceiver liefern...")
   - **Desire**: Betone den Wettbewerbsvorteil und unsere Expertise 
     ("50+ Jahre Photonik-Erfahrung")
   - **Action**: Klarer CTA ("Entdecken Sie...", "Erfahren Sie mehr...")

2. **Problem-Agitation-Solution (PAS) – Wissenschaftlich präzise**
   - **Problem**: Faktisch beschreiben (mit Zahlen/Daten wenn möglich)
   - **Agitation**: Konsequenzen klar machen (ohne Angstmache)
   - **Solution**: Coherent-Technologie als Enabler positionieren

3. **Before-After-Bridge (BAB) – Für Transformation Stories**
   - **Before**: Ausgangssituation des Kunden (technisch präzise)
   - **After**: Ziel-Zustand mit Coherent-Lösung (messbare Verbesserungen)
   - **Bridge**: Wie Coherent die Transformation ermöglicht

4. **Feature-Advantage-Benefit (FAB) – Für Produktkommunikation**
   - **Feature**: Technische Spezifikation (z.B. "800Gbit/s Datenrate")
   - **Advantage**: Technischer Vorteil (z.B. "4x schneller als 200G")
   - **Benefit**: Business Impact (z.B. "Rechenzentrum bewältigt 
     wachsende KI-Workloads")

5. **The "Why This, Why Now" Framework – Für Thought Leadership**
   - **Why This**: Warum ist diese Technologie wichtig? (Marktkontext)
   - **Why Now**: Warum gerade jetzt relevant? (Trends, Entwicklungen)
   - **Why Coherent**: Was macht unsere Lösung einzigartig? 
     (vertikale Integration, Expertise)

6. **Story Framework: "Photons in Action"**
   - **Setup**: Kundenherausforderung im Zielmarkt
   - **Conflict**: Technische/wirtschaftliche Hürde
   - **Resolution**: Wie Coherent-Photonik das Problem löst
   - **Impact**: Messbare Ergebnisse und Zukunftsausblick

7. **The "From-To" Framework – Für Transformations-Stories**
   - **From**: Legacy-Technologie oder aktueller Stand
   - **To**: Next-Generation mit Coherent
   - **Why**: Vorteile der Migration (Performance, Effizienz, Zukunftssicherheit)

8. **Credibility Framework – Für B2B Trust Building**
   - **Expertise**: "50+ Jahre Photonik-Erfahrung"
   - **Scale**: "130+ Standorte, 28.000+ Mitarbeiter"
   - **Proof**: Kundenreferenzen, Case Studies, Zertifizierungen
   - **Vision**: "Innovations That Resonate" – Zukunftsausrichtung

9. **The "What-How-Why" Framework – Für Erklärungsbedürftige Technologien**
   - **What**: Was ist die Technologie? (z.B. "Silicon Photonics")
   - **How**: Wie funktioniert sie? (vereinfacht, aber präzise)
   - **Why**: Warum ist sie relevant? (Anwendungsbeispiel aus Zielmarkt)

10. **Comparison Framework – Für Differenzierung**
    - **Old Way**: Traditioneller Ansatz (ohne Wettbewerber zu nennen)
    - **New Way**: Coherent-Lösung
    - **Advantage**: Konkrete Verbesserungen (Zahlen, Fakten)
```

**Wichtig für alle Frameworks bei Coherent:**
- ✅ Immer faktisch und präzise bleiben
- ✅ Technische Exzellenz kommunizieren, aber zugänglich erklären
- ✅ Innovationsführerschaft zeigen ohne Arroganz
- ✅ Kundenwert in den Mittelpunkt stellen
- ❌ Keine übertriebenen Marketing-Superlative
- ❌ Keine negativen Wettbewerbsvergleiche

---

### 7️⃣ Additional Guidelines (Zusätzliche Richtlinien)

```markdown
## Additional Guidelines

**Coherent Brand Voice Alignment:**
- Alle Outputs müssen die vier Brand Voice Säulen reflektieren:
  1. **Wissenschaftlich**: Präzise, fachlich korrekt, faktenbasiert
  2. **Innovativ**: Zukunftsorientiert, bahnbrechend, transformativ
  3. **Vertrauenswürdig**: Erfahren, zuverlässig, marktführend
  4. **Zugänglich**: Kundenorientiert, partnerschaftlich, verständlich

**Terminologie:**
- Verwende bevorzugte Begriffe: "Photonics leader" (nicht nur "Laser company"), 
  "Breakthrough technologies", "Innovations that resonate", "From materials to systems"
- Produktbereiche korrekt bezeichnen: Networking, Materials, Lasers
- Märkte: Industrial, Communications, Electronics, Instrumentation
- Vermeide: generische Floskeln wie "best-in-class", "game-changer" 
  (es sei denn, es ist wirklich zutreffend)

**Tonalität nach Kontext:**
- **Corporate/Thought Leadership**: Visionär, inspirierend, professionell
- **Produktkommunikation**: Präzise, fachlich, lösungsorientiert
- **Social Media**: Engagiert, aktuell, aber immer professionell
- **Kundenkommunikation**: Partnerschaftlich, lösungsorientiert, vertrauenswürdig

**Compliance & Qualität:**
- Keine Übertreibungen oder unbelegte Behauptungen
- Technische Angaben müssen verifizierbar sein
- Bei Vergleichen: faktenbasiert, nicht diffamierend
- Respektiere Wettbewerb, aber kommuniziere Coherent-Vorteile klar

**Vermeidungen:**
❌ Veraltete Markenbezüge (II-VI, altes Coherent Inc. – außer historischer Kontext)
❌ Zu akademische Sprache ohne Praxisbezug
❌ Aggressive oder negative Konkurrenzvergleiche
❌ Technologie um ihrer selbst willen (immer Kundenwert zeigen)
```

---

## 📋 Vollständige Skill-Prompt-Vorlage für Coherent

Hier ist eine fertige Vorlage, die Sie für Ihre eigenen Skills anpassen können:

```markdown
# SKILL-PROMPT VORLAGE FÜR COHERENT

Help me create a Skill called "[SKILL-NAME]" that [HAUPTFUNKTION].

## Skill Purpose
Dieses Skill soll [ZIELGRUPPE] bei Coherent Corp. helfen, [HAUPTZIEL] zu erreichen. 
Das Skill generiert [ANZAHL/ART DER OUTPUTS], die:
- [KRITERIUM 1 – z.B. Brand Voice einhalten]
- [KRITERIUM 2 – z.B. Zielmarkt-spezifisch sind]
- [KRITERIUM 3 – z.B. Compliance-Anforderungen erfüllen]

## When to Use This Skill
Invoke this skill whenever I need to:
- [ANWENDUNGSFALL 1]
- [ANWENDUNGSFALL 2]
- [ANWENDUNGSFALL 3]
- [ANWENDUNGSFALL 4]
- [ANWENDUNGSFALL 5]

## Required Inputs
When I invoke this skill, ask me for:
1. [EINGABE 1 MIT BEISPIELEN]
2. [EINGABE 2 MIT BEISPIELEN]
3. [EINGABE 3 MIT BEISPIELEN]
4. [EINGABE 4 MIT BEISPIELEN]
5. [EINGABE 5 MIT BEISPIELEN]

## Output Format
[BESCHREIBE DIE STRUKTUR DER AUSGABE]

**Coherent-spezifische Anforderungen:**
- [ANFORDERUNG 1]
- [ANFORDERUNG 2]
- [ANFORDERUNG 3]

**Beispiel-Output:**
[ZEIGE EIN KONKRETES BEISPIEL]

## Frameworks/Methoden
[LISTE BEWÄHRTE METHODEN, DIE DAS SKILL NUTZEN SOLL]

## Additional Guidelines
**Coherent Brand Voice:**
- Wissenschaftlich, Innovativ, Vertrauenswürdig, Zugänglich

**Terminologie:**
- [LISTE BEVORZUGTER BEGRIFFE]
- [LISTE ZU VERMEIDENDER BEGRIFFE]

**Compliance:**
- [RELEVANTE SICHERHEITS- ODER COMPLIANCE-HINWEISE]

**Qualitätssicherung:**
- [WIE SOLL QUALITÄT SICHERGESTELLT WERDEN?]

Erstelle dieses Skill jetzt und speichere es für Coherent-Mitarbeiter.
```

---

## 🎯 Praxisbeispiele: Fertige Skill-Prompts für Coherent

Hier sind konkrete, sofort einsetzbare Skill-Prompts für verschiedene Bereiche bei Coherent:

### Beispiel 1: Coherent Product Launch Communicator (Marketing)

```markdown
Help me create a Skill called "Coherent Product Launch Communicator" that generates 
comprehensive launch communication materials for new Coherent products across 
all channels.

## Skill Purpose
Dieses Skill soll Marketing-Teams bei Coherent helfen, konsistente, überzeugende 
Produktankündigungen zu erstellen, die unsere Brand Voice widerspiegeln und 
verschiedene Stakeholder ansprechen. Das Skill generiert:
- Pressemitteilungs-Headlines und Lead-Paragraphen
- LinkedIn-Ankündigungs-Posts (kurz und lang)
- E-Mail-Kampagnen-Texte für Kunden
- Interne Ankündigungen für Sales-Teams
- FAQs für Customer Support

## When to Use This Skill
Invoke this skill whenever I need to:
- Bereite die Markteinführung eines neuen Produkts vor (Laser, Transceiver, Material)
- Kommuniziere ein Major Product Update oder Feature-Release
- Erstelle Launch-Materialien für eine Produktlinie
- Koordiniere Multi-Channel-Kommunikation für einen Launch
- Bereite Sales Enablement Content für neue Produkte vor

## Required Inputs
When I invoke this skill, ask me for:
1. [Produktname & Typ] - z.B. "800G ZR/ZR+ Transceiver", "ACE FL Two-Micron Fiber Laser"
2. [Produktbereich] - Networking, Materials (SiC, Optiken), oder Lasers 
   (Faserlaser, Ultrakurzpuls, CO2, etc.)
3. [Zielmarkt] - Industrial, Communications, Electronics, Instrumentation
4. [Hauptinnovation] - Was ist neu/bahnbrechend? (z.B. "Erste 150mm InP-Fertigung weltweit")
5. [Key Benefits] - Top 3 Kundenvorteile (technisch und wirtschaftlich)
6. [Technische Highlights] - 3-5 wichtige Spezifikationen (z.B. "1.6Tbit/s Datenrate", 
   "30% geringerer Stromverbrauch")
7. [Zielgruppe] - Engineering-Entscheider, Procurement, C-Level, allgemeine Fachpresse
8. [Launch-Kontext] - Messe (z.B. OFC, LASER World), Produkt-Refresh, 
   Markteinführung neuer Kategorie

## Output Format
Erstelle ein vollständiges Launch Communication Package mit folgenden Komponenten:

**1. Pressemitteilungs-Elemente**
- Headline (unter 100 Zeichen, aufmerksamkeitsstark)
- Subheadline (ergänzender Kontext)
- Lead-Paragraph (2-3 Sätze: Was, Warum wichtig, Für wen)
- Executive Quote (CEO oder Produktverantwortlicher)

**2. LinkedIn-Posts (3 Varianten)**
- **Kurz** (150-200 Zeichen): Teaser mit CTA
- **Medium** (400-500 Zeichen): Story + Benefits + CTA
- **Lang** (800-1000 Zeichen): Deep Dive mit technischen Details

**3. E-Mail-Kampagnen-Texte**
- Betreffzeile (5 Varianten, A/B-Test-geeignet)
- Preview-Text (40-50 Zeichen)
- E-Mail-Body (300-400 Wörter): Problem-Solution-Benefit Struktur
- CTA-Button-Text (2-3 Wörter)

**4. Interne Sales Enablement**
- One-Pager für Sales-Team (Elevator Pitch)
- Key Talking Points (5-7 Bullets)
- Competitive Positioning (ohne Namen zu nennen)
- Customer Objection Handling (häufige Einwände + Antworten)

**5. Customer Support FAQs**
- 5-7 erwartbare Kundenfragen
- Präzise, technisch korrekte Antworten
- Verweis auf weiterführende Ressourcen

**Coherent-spezifische Anforderungen:**
- Integriere "Innovations That Resonate" wo passend
- Verwende Coherent-Terminologie konsistent
- Brand Voice: Balance zwischen wissenschaftlich-präzise und zugänglich
- Erwähne vertikale Integration bei Networking-Produkten ("from silicon photonics to systems")
- Bei Materials: Betone Expertise ("50+ years in advanced materials")
- Bei Lasers: Hebe Anwendungsexpertise hervor ("Coherent Labs")

## Copywriting Frameworks
Nutze für verschiedene Kommunikationskanäle unterschiedliche Frameworks:
- **Pressemitteilung**: Inverted Pyramid (Wichtigstes zuerst)
- **LinkedIn**: AIDA oder Story Framework
- **E-Mail**: Problem-Agitation-Solution
- **Sales Enablement**: Feature-Advantage-Benefit
- **Support FAQs**: What-How-Why

## Additional Guidelines

**Tonalität:**
- Pressemitteilung: Autoritativ, visionär, faktisch
- LinkedIn: Engagiert, innovativ, aber professionell
- E-Mail: Lösungsorientiert, partnerschaftlich
- Sales Enablement: Vertrauenswürdig, technisch kompetent
- Support FAQs: Präzise, hilfreich, zugänglich

**Technische Präzision:**
- Alle Spezifikationen müssen verifizierbar sein
- Verwende Einheiten korrekt (Gbit/s, W, nm, µm, etc.)
- Bei Vergleichen: Immer Referenzpunkt nennen ("4x schneller als 200G")

**Compliance:**
- Keine unbelegten Behauptungen ("best", "fastest") ohne Kontext
- Forward-Looking Statements vermeiden oder kennzeichnen
- Bei regulierten Märkten (z.B. Medical): Besondere Vorsicht

**Qualitätssicherung:**
- Jede technische Angabe muss durch Produktdatenblatt belegbar sein
- Marketing-Claims müssen mit Engineering-Team abgestimmt sein
- Bei Unsicherheit: Konservativ formulieren, dann mit Fachbereich klären

Erstelle dieses Skill jetzt und speichere es für Coherent Marketing-Teams.
```

---

### Beispiel 2: Coherent Customer Email Responder (Sales & Customer Success)

```markdown
Help me create a Skill called "Coherent Customer Email Responder" that generates 
professional, helpful responses to customer inquiries about Coherent products, 
technical specifications, and services.

## Skill Purpose
Dieses Skill soll Sales, Customer Success und Technical Support Teams helfen, 
schnelle, präzise und markenkonform auf Kundenanfragen zu antworten. Das Skill:
- Erkennt die Art der Anfrage (technisch, kommerziell, Support)
- Generiert strukturierte, professionelle Antworten
- Integriert relevante Produktinformationen
- Schlägt nächste Schritte/CTAs vor
- Wahrt die Coherent Brand Voice (vertrauenswürdig, partnerschaftlich, kompetent)

## When to Use This Skill
Invoke this skill whenever I need to:
- Antworte auf technische Produktanfragen von Kunden
- Bearbeite RFI/RFQ-Anfragen (Request for Information/Quotation)
- Erstelle Follow-up-E-Mails nach Kundenmeetings
- Beantworte Spezifikations- oder Anwendungsfragen
- Formuliere Antworten auf komplexe Support-Cases
- Reagiere auf Inquiry-Forms von der Website

## Required Inputs
When I invoke this skill, ask me for:
1. [Anfrage-Typ] - Technische Specs, Pricing/Quote, Anwendungsberatung, 
   Support-Case, Allgemeine Information
2. [Produktbereich] - Networking (welches Produkt?), Materials (welches Material?), 
   Lasers (welcher Laser-Typ?)
3. [Kundenkontext] - Branche des Kunden (Automotive, Datacom, Medical, etc.), 
   Größe (Startup, Mittelstand, Enterprise), geografische Region
4. [Spezifische Frage] - Was möchte der Kunde genau wissen?
5. [Dringlichkeit] - Standard (3-5 Werktage), Dringend (24h), Kritisch (same day)
6. [Vorhandene Informationen] - Was wissen wir bereits über den Kunden? 
   (Bestandskunde, Neukunde, Partner, Wettbewerber-Kontakt)

## Output Format
Erstelle eine vollständige E-Mail-Antwort mit folgender Struktur:

**Betreffzeile**
- Professionell, klar, Bezug zur ursprünglichen Anfrage
- Format: "Re: [Kundenanfrage] – [Coherent Produktbereich] Informationen"

**E-Mail-Body**

**1. Begrüßung & Dank (1-2 Sätze)**
- Persönliche Ansprache (wenn Name bekannt)
- Dank für Interesse an Coherent-Produkten

**2. Direkte Antwort auf Hauptfrage (2-3 Absätze)**
- Beantworte die spezifische Frage präzise
- Gib relevante technische Informationen (Specs, Datenblätter)
- Erkläre den Nutzen im Kontext der Kundenanwendung

**3. Zusätzliche relevante Informationen (optional, 1-2 Absätze)**
- Erwähne verwandte Produkte, wenn sinnvoll
- Weise auf Application Notes oder White Papers hin
- Gib Anwendungsbeispiele aus ähnlichen Industrien

**4. Nächste Schritte / Call-to-Action (1 Absatz)**
- Biete an: Produktdemo, Technical Call mit Engineering-Team, 
  Testmuster/Evaluation Kits, Angebot/Quote
- Gib klare Handlungsoptionen

**5. Abschluss**
- Höfliche Verabschiedung
- Angebot für weitere Fragen
- Unterschrift (Name, Titel, Coherent Corp.)

**Coherent-spezifische Anforderungen:**
- Verwende "wir" statt "ich" (Team-Perspektive)
- Erwähne Coherent-Expertise wo relevant ("50+ Jahre Photonik-Erfahrung")
- Bei technischen Fragen: Präzise, aber verständlich erklären
- Verweise auf Ressourcen: Website, Datenblätter, Application Notes
- Biete proaktiv nächste Schritte an (Customer Success Mindset)

## Response Style Guidelines

**Für verschiedene Anfrage-Typen:**

**1. Technische Spezifikationen:**
- Präzise Zahlen und Einheiten
- Verweis auf Produktdatenblätter
- Erkläre, warum diese Specs für Kundenanwendung relevant sind

**2. Pricing/Quotation:**
- Höflich aber klar: Pricing nach Anfrage (wenn zutreffend)
- Erkläre Faktoren, die Preis beeinflussen (Volumen, Customization)
- Verbinde mit Sales-Kontakt für detailliertes Angebot

**3. Anwendungsberatung:**
- Stelle Gegenfragen, um Anforderungen zu verstehen
- Empfehle passende Produktlinien
- Biete Technical Application Engineering Support an

**4. Support-Cases:**
- Empathisch und lösungsorientiert
- Erkenne Problem-Dringlichkeit an
- Gib Zeitrahmen für Lösung/weitere Updates

## Additional Guidelines

**Tonalität:**
- **Vertrauenswürdig**: Präzise, ehrlich, transparent
- **Partnerschaftlich**: "Wir unterstützen Sie...", "Gemeinsam finden wir..."
- **Kompetent**: Zeige Expertise, ohne überheblich zu wirken
- **Zugänglich**: Komplexe Technik verständlich erklären

**Terminologie:**
- Verwende Coherent-Produktnamen korrekt
- Erkläre Abkürzungen beim ersten Auftauchen
- Nutze Kundenterminologie, wenn bekannt (z.B. ihre internen Projektnamen)

**Compliance & Datenschutz:**
- Keine vertraulichen Informationen anderer Kunden
- Keine technischen Details, die unter NDA stehen könnten
- Bei Unsicherheit: Biete direkten Kontakt mit Fachbereich an

**Vermeidungen:**
❌ Übertriebene Marketing-Sprache
❌ Versprechen, die nicht eingehalten werden können
❌ Negative Erwähnungen von Wettbewerbern
❌ Technische Details, bei denen du unsicher bist (lieber: "Ich kläre das mit unserem Engineering-Team")

**Qualitätssicherung:**
- Immer: Rechtschreibung/Grammatik prüfen
- Bei technischen Angaben: Abgleich mit offiziellem Datenblatt
- Bei Pricing-Fragen: Koordination mit Sales-Team
- Bei kritischen Cases: Eskalation an Management

Erstelle dieses Skill jetzt und speichere es für Coherent Sales & Customer Success Teams.
```

---

### Beispiel 3: Coherent Job Description Generator (HR)

```markdown
Help me create a Skill called "Coherent Job Description Generator" that creates 
compelling, authentic job postings that attract top talent while reflecting 
Coherent's culture, values, and employer brand.

## Skill Purpose
Dieses Skill soll HR-Teams und Hiring Managers helfen, professionelle 
Stellenausschreibungen zu erstellen, die:
- Unsere I CARE Werte (Integrity, Collaboration, Accountability, Respect, Enthusiasm) 
  authentisch kommunizieren
- Die richtige Balance zwischen Fachkompetenz und Cultural Fit finden
- Verschiedene Zielgruppen ansprechen (Engineering, Administration, Marketing, 
  Sales, Operations)
- Diversity & Inclusion fördern
- Coherent als attraktiven Arbeitgeber positionieren

## When to Use This Skill
Invoke this skill whenever I need to:
- Erstelle eine neue Stellenausschreibung
- Überarbeite eine bestehende Job Description
- Formuliere Postings für verschiedene Kanäle (LinkedIn, Website, Jobbörsen)
- Erstelle Ausschreibungen für Ausbildungs- oder Praktikumsplätze
- Verfasse internationale Job Postings (angepasst an lokale Märkte)

## Required Inputs
When I invoke this skill, ask me for:
1. [Position Title] - Genauer Job-Titel (z.B. "Photonics Application Engineer", 
   "Marketing Manager EMEA", "HR Business Partner")
2. [Department/Bereich] - Engineering (welche Disziplin?), Marketing, Sales, 
   Operations, HR, Finance, Quality, Supply Chain
3. [Standort] - Welche Coherent-Location? (z.B. Saxonburg/USA, Hamburg/Deutschland, 
   Ipoh/Malaysia, etc.)
4. [Seniorität] - Entry Level, Mid-Level, Senior, Leadership/Management
5. [Reporting Line] - Wem berichtet die Position? (Titel oder Funktion)
6. [Team Size/Context] - Größe des Teams, Art der Zusammenarbeit
7. [Key Responsibilities] - Top 5 Hauptaufgaben der Rolle
8. [Must-Have Qualifications] - Unverzichtbare Skills/Erfahrungen (max. 5-7)
9. [Nice-to-Have Qualifications] - Wünschenswerte Zusatzqualifikationen (max. 3-5)
10. [Produktbereich/Markt (wenn relevant)] - Networking, Materials, Lasers | 
    Industrial, Communications, Electronics, Instrumentation
11. [Besonderheiten] - Remote-Möglichkeit? Reiseanteil? Schichtarbeit? 
    Projekteinsätze?

## Output Format
Erstelle eine vollständige Stellenausschreibung mit folgender Struktur:

**1. Attention-Grabbing Headline (1 Zeile)**
- Macht Position attraktiv und spiegelt Coherent-Kultur wider
- Format: "[Position] bei Coherent – [einzigartiger Aspekt der Rolle]"
- Beispiel: "Photonics Engineer bei Coherent – Shape the Future of AI Infrastructure"

**2. Über Coherent Corp. (3-4 Sätze)**
- Kurze Vorstellung: "Coherent ist ein globaler Photonik-Leader mit über 
  28.000 Mitarbeitern an 130+ Standorten in 20+ Ländern..."
- Tagline einbinden: "Innovations That Resonate"
- Kurze Erwähnung der drei Geschäftsbereiche (Networking, Materials, Lasers)
- Hauptmärkte: Industrial, Communications, Electronics, Instrumentation

**3. Ihre Rolle bei uns (4-5 Bulletpoints)**
- Was macht die Position spannend?
- Welchen Impact hat die Rolle auf Produkte/Kunden/Unternehmen?
- Wie passt sie zur Coherent-Mission?
- Welche Projekte/Technologien werden Sie mitgestalten?
- Mit wem arbeiten Sie zusammen? (z.B. "Cross-functional Teams", "Global R&D Network")

**4. Das bringen Sie mit (7-10 Bulletpoints)**
- **Must-Haves** (deutlich kennzeichnen):
  - Ausbildung/Abschluss
  - Berufserfahrung (Jahre + Bereich)
  - Fachliche Hard Skills
  - Sprachen (wenn relevant)
- **Nice-to-Haves** (deutlich kennzeichnen):
  - Zusätzliche Zertifikate
  - Bonus-Skills
- **Persönliche Eigenschaften** (im Kontext der I CARE Werte):
  - Z.B. "Collaborative mindset", "Accountable for results", 
    "Enthusiastic problem-solver"

**5. Das bieten wir Ihnen (6-8 Bulletpoints)**
- **Karriereentwicklung**: Weiterbildung, Training, internationale Assignments
- **Innovatives Umfeld**: Arbeit an cutting-edge Technologien
- **Globale Perspektive**: Teil eines weltweiten Teams
- **I CARE Kultur**: Authentische Erwähnung der Unternehmenswerte
- **Work-Life Balance**: Flexible Arbeitszeiten, Remote-Optionen (wenn zutreffend)
- **Benefits**: Wettbewerbsfähige Vergütung, Zusatzleistungen (länder-spezifisch anpassen)
- **Impact**: "Your work enables..." (Bezug zum Zielmarkt)

**6. So bewerben Sie sich**
- Call-to-Action: "Werden Sie Teil unseres Teams!"
- Bewerbungsprozess kurz umreißen
- Kontaktdaten HR oder Link zu Karriereportal
- Hinweis auf Chancengleichheit: "Coherent is an Equal Opportunity Employer. 
  We celebrate diversity and are committed to creating an inclusive environment 
  for all employees."

**Coherent-spezifische Anforderungen:**
- Verwende die offizielle Unternehmensvorstellung (siehe Sektion 2)
- Integriere I CARE Werte authentisch, nicht als Buzzwords
- Für technische Rollen: Erwähne spezifische Technologien/Produkte 
  (z.B. "Sie arbeiten an 800G-Transceivern für KI-Rechenzentren")
- Für nicht-technische Rollen: Erkläre, wie die Position das Business 
  unterstützt (z.B. "Sie ermöglichen unseren Vertriebsteams, erfolgreich 
  zu sein")
- Betone globale Präsenz, wenn relevant für die Rolle
- Erwähne Innovationsführerschaft ohne Arroganz

## Language & Tone Guidelines

**Für verschiedene Zielgruppen:**

**1. Engineering/Technical Roles:**
- Präzise Technologie-Beschreibung (keine Marketing-Floskeln)
- Konkrete Projekte oder Produkte nennen
- R&D-Umfeld, Tools, Methoden beschreiben
- Challenge hervorheben ("komplexe Probleme lösen")

**2. Marketing/Creative Roles:**
- Dynamisch und inspirierend
- Kreativität und strategisches Denken betonen
- Marktdynamik und Impact hervorheben
- "Storytelling" und "Thought Leadership" als Aspekte

**3. Sales/Customer-Facing Roles:**
- Beziehungsorientiert ("build lasting partnerships")
- Business Impact und Erfolgsmetriken
- Kundensegmente beschreiben
- Lösungsorientierung betonen

**4. Administration/Operations:**
- Prozessverbesserung und Effizienz
- Team-Unterstützung und Cross-functional Collaboration
- Organisationstalent und Detailgenauigkeit
- "Enabler"-Rolle würdigen

## Additional Guidelines

**Diversity & Inclusion:**
- Gender-neutrale Sprache verwenden
- Keine unbewussten Bias in Anforderungen (z.B. "10+ Jahre Erfahrung" 
  kann Frauen abschrecken, die Career Breaks hatten)
- "You" statt "He/She"
- Ermutigung für diverse Bewerbende: "We encourage applications from 
  candidates of all backgrounds"

**Legal Compliance:**
- Keine diskriminierenden Anforderungen (Alter, Geschlecht, Herkunft)
- Bei physischen Anforderungen: "with or without reasonable accommodation"
- Datenschutz: DSGVO-konforme Hinweise für EU-Rollen

**Authentizität:**
- Keine unrealistischen Versprechen ("100% Remote" wenn nicht zutreffend)
- Ehrlich über Herausforderungen (z.B. "This role requires occasional travel")
- Realistische Qualifikations-Listen (nicht die eierlegende Wollmilchsau)

**Vermeidungen:**
❌ Übertriebene Superlative ("world's best", "unbeatable")
❌ Zu lange Anforderungslisten (entmutigt Bewerbende)
❌ Fachjargon ohne Erklärung
❌ Klischee-Phrasen ("rockstar", "ninja")
❌ Ageism-Signale ("digital native", "young and dynamic team")

**Qualitätssicherung:**
- Lasse HR und Hiring Manager reviewen
- Prüfe auf unbewusste Bias
- Vergleiche mit erfolgreichen vergangenen Postings
- Teste auf verschiedenen Plattformen (LinkedIn vs. Karriereseite)

Erstelle dieses Skill jetzt und speichere es für Coherent HR-Teams.
```

---

### Beispiel 4: Coherent Meeting Summary Creator (Administration & Operations)

```markdown
Help me create a Skill called "Coherent Meeting Summary Creator" that generates 
clear, actionable meeting summaries and follow-up communications for various 
types of meetings at Coherent.

## Skill Purpose
Dieses Skill soll Mitarbeitern aus allen Bereichen (besonders Administration, 
Operations, Projektmanagement) helfen, professionelle Meeting-Zusammenfassungen 
zu erstellen, die:
- Klare Action Items und Verantwortlichkeiten definieren
- Entscheidungen dokumentieren
- Nächste Schritte festhalten
- Als Kommunikationsmittel für Nicht-Teilnehmer dienen
- Nachverfolgung und Accountability ermöglichen

## When to Use This Skill
Invoke this skill whenever I need to:
- Erstelle Protokolle von Team-Meetings
- Fasse Projekt-Status-Meetings zusammen
- Dokumentiere Kundenmeetings (intern)
- Bereite Follow-up-E-Mails nach Meetings vor
- Erstelle Executive Summaries für Leadership-Meetings
- Dokumentiere Entscheidungen für spätere Referenz

## Required Inputs
When I invoke this skill, ask me for:
1. [Meeting-Typ] - Team-Meeting, Projekt-Status, Kundengespräch (intern), 
   Leadership-Meeting, Cross-functional Workshop, One-on-One
2. [Meeting-Titel/Thema] - Worum ging es?
3. [Teilnehmer] - Wer war dabei? (Namen oder Rollen)
4. [Datum & Dauer] - Wann fand es statt? Wie lange?
5. [Hauptthemen] - Was waren die 3-5 wichtigsten Diskussionspunkte?
6. [Getroffene Entscheidungen] - Welche Entscheidungen wurden getroffen?
7. [Action Items] - Wer macht was bis wann? (Liste)
8. [Offene Punkte/Blockers] - Was ist noch ungeklärt? Was blockiert Fortschritt?
9. [Nächster Termin] - Wann ist das nächste Meeting? (falls zutreffend)
10. [Verteilerliste] - Wer soll die Zusammenfassung erhalten?

## Output Format
Erstelle eine strukturierte Meeting-Zusammenfassung mit folgenden Komponenten:

**E-Mail-Betreffzeile:**
Format: "Meeting Summary: [Meeting-Titel] – [Datum]"

**Meeting-Zusammenfassung (E-Mail-Body):**

**1. Meeting-Details**
- **Datum & Zeit**: [Datum], [Uhrzeit-Zeitzone]
- **Teilnehmer**: [Liste der Teilnehmer]
- **Thema**: [Kurze Beschreibung des Meeting-Zwecks]

**2. Key Discussion Points (3-5 Bulletpoints)**
- Fasse die wichtigsten Diskussionen zusammen
- Kurz und prägnant (1-2 Sätze pro Punkt)
- Fokus auf Substanz, nicht auf Details

**3. Decisions Made** ✅
- Liste alle getroffenen Entscheidungen klar und eindeutig
- Format: "Decision: [Was wurde entschieden?] | Rationale: [Warum?]"
- Beispiel: "Decision: Wir nutzen 800G-Transceiver für Datacenter-Projekt X | 
  Rationale: Höhere Bandbreite bei gleichen Kosten"

**4. Action Items** 🎯
- Tabelle mit:
  - **Action**: Was muss getan werden?
  - **Owner**: Wer ist verantwortlich?
  - **Due Date**: Bis wann?
  - **Status**: Not Started / In Progress / Done
  
| Action | Owner | Due Date | Status |
|--------|-------|----------|---------|
| [Aufgabe 1] | [Name] | [Datum] | Not Started |
| [Aufgabe 2] | [Name] | [Datum] | Not Started |

**5. Open Issues / Blockers** ⚠️
- Liste ungeklärte Punkte
- Identifiziere Blockers (was verhindert Fortschritt?)
- Vorschläge zur Lösung (optional)

**6. Next Steps**
- **Nächstes Meeting**: [Datum], [Thema]
- **Vorbereitung**: Was sollten Teilnehmer bis dahin tun?

**7. Abschluss**
- Dank an Teilnehmer
- Kontaktinformation für Rückfragen
- Hinweis: "Bei Fragen oder Korrekturen, bitte bis [Datum] melden"

**Coherent-spezifische Anforderungen:**
- Verwende klare, professionelle Sprache
- Halte Zusammenfassungen prägnant (max. 1 Seite)
- Fokus auf Actionability (was muss passieren?)
- Bei technischen Meetings: Präzise Terminologie, aber für Nicht-Experten 
  verständlich
- Bei Projekt-Meetings: Status-Updates zu Projekten transparent darstellen

## Format Variations

**Für verschiedene Meeting-Typen:**

**1. Team-Meetings:**
- Informell, fokussiert auf Team-Zusammenarbeit
- Betone Teamwork und Erfolge
- Action Items klar, aber kollegial

**2. Projekt-Status-Meetings:**
- Strukturiert, fortschrittsorientiert
- Status-Tracking (On Track / At Risk / Blocked)
- Metriken und KPIs einbinden, falls relevant

**3. Kundenmeetings (interne Dokumentation):**
- Faktisch, präzise
- Kundenanforderungen klar dokumentieren
- Vereinbarungen und Zusagen festhalten
- ⚠️ Hinweis: "Confidential – Internal Use Only"

**4. Leadership-Meetings:**
- Executive Summary Format
- High-level Decisions und strategische Richtung
- Knapp und fokussiert (Busy Leaders!)

## Additional Guidelines

**Tonalität:**
- Professionell, aber nicht steif
- Klar und direkt
- Wertschätzend (besonders bei Action Items: "Jane wird...", nicht "Jane muss...")

**Best Practices:**
- **Objektivität**: Fasse zusammen, interpretiere nicht
- **Klarheit**: Keine Mehrdeutigkeiten bei Action Items
- **Vollständigkeit**: Alle wichtigen Punkte erfassen
- **Prägnanz**: So kurz wie möglich, so lang wie nötig

**Compliance & Datenschutz:**
- Bei Kundenmeetings: Keine vertraulichen Kundeninformationen ohne Zustimmung
- Bei HR/Personal-Themen: Besondere Vertraulichkeit
- Bei Strategie-Meetings: "Confidential" markieren

**Vermeidungen:**
❌ Wörtliche Transkription (zu lang, nicht hilfreich)
❌ Persönliche Meinungen oder Wertungen
❌ Vage Action Items ("Wir sollten mal...", "Jemand könnte...")
❌ Zu viele Details (Fokus auf Kernpunkte)

**Qualitätssicherung:**
- Sende Draft an Meeting-Organizer zur Freigabe (bei wichtigen Meetings)
- Prüfe Action Items auf Klarheit (SMART-Kriterien)
- Alle Teilnehmer korrekt genannt?
- Nächster Termin eingetragen (falls vereinbart)?

Erstelle dieses Skill jetzt und speichere es für alle Coherent-Mitarbeiter, 
besonders Administration & Operations.
```

---

### Beispiel 5: Coherent Technical Content Simplifier (Engineering → Marketing Bridge)

```markdown
Help me create a Skill called "Coherent Technical Content Simplifier" that 
translates complex photonics and engineering content into accessible language 
for non-technical audiences while maintaining technical accuracy.

## Skill Purpose
Dieses Skill soll helfen, die Lücke zwischen Engineering und Marketing/Sales 
zu schließen. Es:
- Übersetzt technische Produktspezifikationen in verständliche Benefits
- Macht komplexe Photonik-Konzepte für Nicht-Ingenieure zugänglich
- Bewahrt technische Genauigkeit, aber reduziert Komplexität
- Erstellt verschiedene Versionen für unterschiedliche Zielgruppen
  (C-Level, Marketing, Sales, Kunden)

## When to Use This Skill
Invoke this skill whenever I need to:
- Übersetze Engineering-Datenblätter in Marketing-Content
- Erstelle Executive Summaries aus technischen Reports
- Bereite technische Präsentationen für nicht-technische Stakeholder vor
- Formuliere Produkt-Benefits aus technischen Features
- Schreibe Blogposts über komplexe Coherent-Technologien
- Erstelle Sales Enablement Content aus Engineering-Dokumentation

## Required Inputs
When I invoke this skill, ask me for:
1. [Quelle] - Was soll vereinfacht werden? (Datenblatt, White Paper, 
   technischer Bericht, Engineering-Präsentation)
2. [Technisches Thema] - z.B. "Silicon Photonics Integration", "VCSEL-Array-Technologie", 
   "SiC-Epitaxie für EVs", "Ultrafast Laser Pulse Shaping"
3. [Zielgruppe] - Marketing-Team, Sales-Team, C-Level Executives, 
   Technische Buyer (aber keine Experten), Endkunden, Presse/Journalisten
4. [Output-Format] - 1-Pager, LinkedIn-Post, Blog-Artikel, E-Mail-Text, 
   Präsentations-Folie, Produkt-Brief
5. [Technik-Level gewünscht] - Keine Tech-Details, Basic Tech-Verständnis, 
   Moderate Tech-Tiefe
6. [Hauptbotschaft] - Was soll das Publikum verstehen/mitnehmen?
7. [Use Case/Anwendung] - In welchem Markt wird die Technologie eingesetzt?

## Output Format
Erstelle verschiedene Content-Versionen basierend auf der Zielgruppe:

**1. Executive Version (für C-Level)**
- **Headline** (1 Zeile): Business Impact in einem Satz
- **Business Problem** (2-3 Sätze): Welche Marktherausforderung existiert?
- **Coherent Solution** (2-3 Sätze): Wie löst unsere Technologie das Problem?
- **Key Benefits** (3 Bullets): Business-Outcomes, nicht Features
  - Beispiel: "30% Kostenreduktion in Datacenter-Infrastruktur" 
    (nicht: "1.6Tbit/s Datenrate")
- **Market Opportunity** (1-2 Sätze): Größe des Marktes, Wachstum, Position von Coherent
- **Call-to-Action**: Nächste Schritte

**2. Marketing/Content Version**
- **Attention-Grabbing Intro** (1-2 Absätze): Story-basiert oder Trend-basiert
- **The Challenge** (1 Absatz): Industrie-Problem beschreiben
- **The Coherent Approach** (2-3 Absätze): 
  - Was ist die Technologie? (vereinfacht erklärt mit Analogien)
  - Wie funktioniert sie? (High-level, ohne tief in Physik einzutauchen)
  - Warum ist Coherent's Ansatz besonders? (Differenzierung)
- **Real-World Applications** (3-5 Bullets mit kurzen Beschreibungen)
- **Customer Impact** (1-2 Absätze): Was bedeutet das für Kunden?
- **Visual Suggestion**: Welche Art von Grafik/Bild würde helfen?
- **CTA**

**3. Sales Enablement Version (Feature-Advantage-Benefit Format)**
- **Feature** (technisch präzise, aber kompakt):
  "Coherent's 800G ZR/ZR+ Transceiver nutzt digitale kohärente Optik 
  mit DSP-Algorithmen..."
- **Advantage** (technischer Vorteil):
  "Das ermöglicht 4x höhere Datenraten als 200G bei nur 2x Stromverbrauch..."
- **Benefit** (Business Impact):
  "Kunden können ihre Datacenter-Kapazität verdoppeln ohne zusätzliche Switches 
  zu kaufen → 40% Capex-Einsparung..."
- **Proof Points** (Zahlen, Case Studies, Kundenzitate falls verfügbar)
- **Objection Handling** (3-5 häufige Kundeneinwände + Antworten)
- **Competitive Positioning** (ohne Wettbewerber zu nennen):
  "Anders als andere Lösungen, bietet Coherent vertikale Integration von..."

**4. Press/Media Version (für Journalisten)**
- **Lede** (Eröffnungssatz): Fasse die Nachricht zusammen (who, what, why wichtig)
- **Context** (2-3 Absätze): Branchenhintergrund, warum ist das relevant?
- **The Technology** (2-3 Absätze): Was ist neu? Wie funktioniert es? 
  (Erkläre wie für Fachpresse, aber nicht zu akademisch)
- **Expert Quote** (CEO, CTO, oder Produktverantwortlicher)
- **Market Impact** (1-2 Absätze)
- **Availability & Next Steps**

**Coherent-spezifische Anforderungen:**
- Verwende Analogien aus dem Alltag, wo sinnvoll:
  - "VCSELs sind wie viele winzige Laser-Pointer, die präzise koordiniert arbeiten"
  - "Silicon Photonics ist wie ein Mikrochip, der mit Licht statt Elektrizität rechnet"
- Verwende die "From-To"-Struktur:
  - "From: Legacy 100G Transceiver → To: Next-Gen 800G with 8x throughput"
- Integriere "Innovations That Resonate" wo passend
- Nutze Coherent's Unique Positioning:
  - "Vertikal integriert – von Materials bis zu Systemen"
  - "50+ Jahre Photonik-Expertise"
  - "Global scale – 130+ Standorte in 20+ Ländern"

## Simplification Techniques

**1. Die "Erklären Sie es einem 12-Jährigen"-Methode**
- Verwende einfache Worte
- Baue Konzepte schrittweise auf
- Nutze Vergleiche aus dem Alltag

**2. Die Feature-to-Benefit Translation**
- Feature: "Silicon Photonics Integration"
- Advantage: "Licht statt Elektrizität für Datenübertragung"
- Benefit: "Schneller, energieeffizienter, kompakter"

**3. Die Story-Methode**
- "Stellen Sie sich vor, Sie betreiben ein Rechenzentrum und..."
- "Früher war es so... Jetzt ist es so..."

**4. Die Visual-Metaphern-Methode**
- "Ein Transceiver funktioniert wie eine Übersetzerin zwischen elektrischen 
  und optischen Signalen..."
- "SiC ist wie das Hochleistungsmaterial für Leistungselektronik – stärker, 
  effizienter, hitzebeständiger als herkömmliche Halbleiter"

## Additional Guidelines

**Dos:**
✅ Verwende Analogien, die das Publikum versteht
✅ Erkläre "Warum das wichtig ist" nach jedem technischen Punkt
✅ Nutze konkrete Zahlen (aber einfach: "4x schneller" statt "Datenrate von 1.6 Tbit/s")
✅ Zeige Real-World Anwendungen (z.B. "Ermöglicht Face ID in Ihrem Smartphone")
✅ Halte Sätze kurz und klar

**Don'ts:**
❌ Verwende keine Fachbegriffe ohne Erklärung
❌ Keine langen Absätze (max. 3-4 Sätze)
❌ Keine technischen Details, die nicht zum Verständnis beitragen
❌ Keine Annahme, dass Publikum Grundwissen hat (erkläre alles nötig)
❌ Nicht "dumbing down" zu weit (wahre technische Richtigkeit)

**Qualitätssicherung:**
- Lasse einen Nicht-Ingenieur den Text lesen (Verständlichkeitstest)
- Prüfe: Sind alle Benefits klar?
- Prüfe: Ist es technisch korrekt? (Review durch Engineering)
- Verwende Readability-Scores (Flesch-Kincaid: Ziel 8th-10th Grade)

Erstelle dieses Skill jetzt und speichere es für Coherent Marketing-, Sales-, 
und Content-Teams.
```

---

### Beispiel 6: Coherent Internal Communication Booster (HR & Internal Comms)

```markdown
Help me create a Skill called "Coherent Internal Communication Booster" that 
generates engaging, clear internal communications for various company updates, 
announcements, and cultural initiatives.

## Skill Purpose
Dieses Skill soll HR, Internal Communications, und Leadership helfen, 
wirkungsvolle interne Mitteilungen zu erstellen, die:
- Mitarbeiter informieren und motivieren
- I CARE Werte sichtbar machen
- Transparenz und Engagement fördern
- Verschiedene Formate abdecken (E-Mails, Intranet-Posts, Newsletter, 
  Town Hall Slides)
- Cultural Change und Transformation unterstützen

## When to Use This Skill
Invoke this skill whenever I need to:
- Kommuniziere Unternehmensnachrichten (Quartalsergebnisse, strategische Updates)
- Kündige organisatorische Änderungen an
- Feiere Teamerfolge und Meilensteine
- Kommuniziere neue Policies oder Prozesse
- Erstelle Inhalte für Employee Newsletter
- Bereite Town Hall Meeting Slides oder Scripts vor
- Kommuniziere Diversity & Inclusion Initiativen
- Teile Erfolgsgeschichten aus verschiedenen Standorten

## Required Inputs
When I invoke this skill, ask me for:
1. [Kommunikationstyp] - Company Update, Organizational Change, Team Success Story, 
   Policy Announcement, Cultural Initiative, Event Invitation, Employee Recognition
2. [Zielgruppe] - All Employees, Specific Department, Leadership, 
   Specific Site/Region
3. [Hauptbotschaft] - Was soll kommuniziert werden?
4. [Kontext/Background] - Warum ist das wichtig? Was ist der Hintergrund?
5. [Gewünschter Ton] - Inspirierend, Informativ, Feiernd, Sachlich, 
   Motivierend, Transparent
6. [I CARE Werte-Bezug] - Welcher der I CARE Werte wird reflektiert? 
   (Integrity, Collaboration, Accountability, Respect, Enthusiasm)
7. [Call-to-Action] - Was sollen Mitarbeiter tun/wissen? (falls zutreffend)
8. [Format] - E-Mail, Intranet-Post, Newsletter-Artikel, Town Hall Slide, 
   Video-Script

## Output Format
Erstelle interne Kommunikation mit folgenden Komponenten:

**Für E-Mail-Format:**

**Betreffzeile**
- Aufmerksamkeitsstark, aber professionell
- Klar kommunizieren, worum es geht
- Format: "[Kategorie] [Hauptbotschaft]"
- Beispiel: "Company Update: Coherent erreicht 800G Transceiver Meilenstein"

**E-Mail-Body**

**1. Eröffnung (1-2 Sätze)**
- Persönliche Ansprache ("Liebe Coherent Familie", "Dear Team", etc.)
- Hook: Warum ist diese Nachricht wichtig/spannend?

**2. Hauptbotschaft (2-3 Absätze)**
- Was ist passiert/wird passieren?
- Warum ist das wichtig für Coherent?
- Kontext und Hintergründe

**3. I CARE Werte-Connection (1 Absatz)**
- Wie reflektiert diese Nachricht unsere Werte?
- Konkrete Beispiele, nicht nur Buzzwords

**4. Was bedeutet das für Sie? (1-2 Absätze)**
- Impact auf Mitarbeiter
- Wie trägt das zu unserer gemeinsamen Vision bei?

**5. Call-to-Action / Next Steps (optional)**
- Was sollten Mitarbeiter tun?
- Wo gibt es mehr Informationen?
- Kontaktperson für Fragen

**6. Abschluss**
- Motivierend und wertschätzend
- Dank/Anerkennung
- Unterschrift (Name, Titel)

**Für Intranet-Post / Newsletter-Artikel:**

**Headline** (aufmerksamkeitsstark, max. 10 Wörter)

**Hero Image Suggestion** (welches Bild würde passen?)

**Lead Paragraph** (2-3 Sätze): Kern der Story

**Body** (3-5 Absätze): 
- Story erzählen
- Fakten und Context
- Menschlicher Touch (Zitate, Anekdoten)
- Visuals einbinden (Fotos, Infografiken)

**Quote Box** (Zitat von beteiligter Person oder Leadership)

**Closing** (Ausblick, CTA)

**Für Town Hall Slide/Script:**

**Slide 1 - Titel:**
- Kurze, prägnante Headline
- Visual (Bild-Vorschlag)

**Slide 2-3 - Key Points:**
- 3-5 Bullets pro Slide (max!)
- Groß, lesbar, klar
- Supporting Visual

**Speaker Notes:**
- Was soll gesagt werden? (ausformuliert)
- Emotional Connectors (Storytelling-Elemente)
- Pause-Punkte für Fragen

**Coherent-spezifische Anforderungen:**
- Verwende "wir" und "unser" (Zugehörigkeitsgefühl)
- Integriere globale Perspektive (wenn Teams aus verschiedenen Ländern betroffen)
- Bei Erfolgsgeschichten: Name the heroes (Mitarbeiter erwähnen)
- Bei Changes: Transparent über Gründe, empathisch zu Bedenken
- Verwende Coherent-Terminologie konsistent

## Tone & Style Guidelines

**Für verschiedene Kommunikationstypen:**

**1. Company Updates / Strategic News:**
- **Ton**: Inspirierend, aber faktisch
- **Stil**: "Here's where we're going, and why it matters"
- **Fokus**: Vision, Impact, Zukunft

**2. Organizational Changes:**
- **Ton**: Transparent, empathisch, zukunftsorientiert
- **Stil**: "We understand this may raise questions, here's what you need to know"
- **Fokus**: Klarheit, Unterstützung, Rationale

**3. Team Success Stories:**
- **Ton**: Feiernd, wertschätzend, motivierend
- **Stil**: "Look what we achieved together!"
- **Fokus**: Recognition, Team-Spirit, Inspiration

**4. Policy Announcements:**
- **Ton**: Klar, sachlich, unterstützend
- **Stil**: "Here's what's changing and why, here's how it works"
- **Fokus**: Clarity, Compliance, Fairness

**5. Cultural Initiatives (D&I, Sustainability):**
- **Ton**: Authentisch, engagiert, action-orientiert
- **Stil**: "This is who we are, this is what we do"
- **Fokus**: Values in Action, Concrete Steps

**6. Employee Recognition:**
- **Ton**: Warm, persönlich, aufrichtig
- **Stil**: "We see you, we value you, thank you"
- **Fokus**: Individuelle Leistung, Team Contribution

## Storytelling Elements

**Verwende das Story-Framework:**

**1. Setup:** 
- Was war die Situation/Herausforderung?

**2. Challenge:** 
- Welche Hürde gab es zu überwinden?

**3. Action:** 
- Was hat das Team/Individuum getan?

**4. Resolution:** 
- Was war das Ergebnis?

**5. Impact:** 
- Was bedeutet das für Coherent? Für Kunden? Für die Zukunft?

**6. Reflection (I CARE Connection):**
- Wie zeigt diese Story unsere Werte?

## Additional Guidelines

**Dos:**
✅ Sei authentisch und ehrlich
✅ Feiere Erfolge enthusiastisch
✅ Bei schlechten Nachrichten: Transparent und empathisch
✅ Verwende konkrete Beispiele und Zahlen
✅ Lade zur Interaktion ein (Fragen stellen, Feedback geben)
✅ Danke Menschen namentlich (bei Erfolgen)
✅ Zeige globale Vielfalt (verschiedene Standorte erwähnen)

**Don'ts:**
❌ Keine Corporate-Speak oder Buzzword-Bingo
❌ Keine schlechten Nachrichten beschönigen
❌ Keine langen, unstrukturierten Texte (Absätze nutzen!)
❌ Keine passiven Formulierungen ("Es wurde entschieden..." → "Wir haben entschieden...")
❌ Keine einseitige Top-Down Kommunikation (Dialog fördern)

**Compliance:**
- Bei HR-Themen: Rechtliche Review einholen
- Bei finanziellen News: Investor Relations checken (Public Company!)
- Bei sensiblen Themen: Legal/Compliance Review

**Accessibility:**
- Verwende inklusive Sprache
- Berücksichtige verschiedene Zeitzonen bei "heute", "gestern"
- Übersetze wichtige Nachrichten (wenn global relevant)

**Qualitätssicherung:**
- Lasse Internal Communications Team reviewen
- Bei Leadership-Kommunikation: Approval durch entsprechendes Level
- Teste Tonalität: Kommt die gewünschte Message an?
- Prüfe Fakten, Zahlen, Daten auf Korrektheit

Erstelle dieses Skill jetzt und speichere es für Coherent HR, 
Internal Communications, und Leadership.
```

---

## 🎓 Was Sie gelernt haben

Nach dieser Anleitung können Sie:

✅ Die **Anatomie eines Skill-Prompts** für verschiedene Coherent-Anwendungsfälle verstehen  
✅ **Eigene Skills** für Ihre tägliche Arbeit bei Coherent erstellen (Marketing, Sales, HR, Admin, Engineering)  
✅ **Best Practices** für strukturierte Prompts anwenden  
✅ Skills für Ihr **Team teilen** und Coherent-Standards einhalten  
✅ Den Unterschied zwischen **generischen und Coherent-spezifischen** Prompts erkennen  
✅ **Brand Voice und I CARE Werte** in Skills integrieren  
✅ **Wiederverwendbare Vorlagen** für typische Aufgaben erstellen

---

## 🚀 Ihr nächster Schritt

**1. Wählen Sie einen Use Case aus Ihrem Arbeitsbereich:**

**Marketing:**
- Produkt-Launch-Kommunikation
- Social Media Content Creation
- Blog-Artikel über Photonik-Themen
- Messe-Material-Erstellung
- E-Mail-Kampagnen

**Sales & Customer Success:**
- Kundenanfragen beantworten
- Angebots-Zusammenfassungen
- Value Propositions für spezifische Branchen
- Follow-up-E-Mails
- Executive Summaries

**HR:**
- Stellenausschreibungen
- Onboarding-Materialien
- Interne Ankündigungen
- Employee Recognition Communications

**Administration & Operations:**
- Meeting-Zusammenfassungen
- E-Mail-Vorlagen für häufige Anfragen
- Prozessdokumentationen
- Team-Updates

**Engineering & Technical:**
- Technische Dokumentation vereinfachen
- Produktspezifikationen für Marketing übersetzen
- Anwendungsbeispiele erstellen
- Technical Blogs

**2. Kopieren Sie die Coherent-Vorlage** (siehe oben)

**3. Füllen Sie die Vorlage aus** mit Ihren spezifischen Anforderungen:
- Welche Informationen benötigt das Skill von mir?
- Wie soll die Ausgabe strukturiert sein?
- Welche Coherent-Standards müssen eingehalten werden? (Brand Voice, Terminologie)
- Welche Compliance-/Sicherheitsaspekte sind relevant? (siehe Sicherheitshinweise unten)

**4. Geben Sie den Prompt an Claude oder Ihren KI-Assistenten**

**5. Testen Sie das generierte Skill** mit einem echten Beispiel aus Ihrer Arbeit

**6. Verfeinern Sie bei Bedarf** – Skills sind iterativ! Wenn das Ergebnis nicht perfekt ist, 
passen Sie den Prompt an.

**7. Teilen Sie Ihr Skill** mit Kollegen (wenn sinnvoll)

---

## 🔒 Wichtige Sicherheitshinweise für Coherent

**Bei der Erstellung und Nutzung von Skills beachten Sie bitte:**

### Datenschutz & Compliance

⚠️ **Geben Sie NIEMALS folgende Informationen in KI-Prompts ein:**

**Geschützte Geschäftsinformationen:**
- Proprietäre Produktdaten (z.B. interne Spezifikationen, die nicht öffentlich sind)
- Patentinformationen oder Forschungsergebnisse vor Veröffentlichung
- Vertrauliche Kundendaten (Namen, Projekte, Spezifikationen)
- Vertrags- oder Angebotsdaten (Preise, Konditionen)
- Fertigungsprozesse oder Rezepturen mit Wettbewerbsrelevanz

**Personenbezogene Daten:**
- Mitarbeiterdaten (Gehälter, Personalnummern, private Kontakte)
- Kundenkontaktdaten ohne explizite Zustimmung
- Gesundheitsdaten
- Interne Organisationsstrukturen im Detail

**Rechtlich geschützte Informationen:**
- Alles, was unter NDAs (Non-Disclosure Agreements) fällt
- Informationen aus vertraulichen Partnerschaften
- Regulatorische Compliance-Details, die nicht öffentlich sind

### ✅ Qualitätssicherung (Human-in-the-Loop)

**Wichtig:** Bitte prüfen Sie alle KI-generierten Ergebnisse eigenverantwortlich, bevor Sie sie weitergeben oder veröffentlichen. 

Das **Human-in-the-Loop-Prinzip** ist essentiell:
- Verlassen Sie sich nie ausschließlich auf automatisierte Ausgaben
- Nutzen Sie Ihr Fachwissen zur kritischen Bewertung
- Führen Sie eine finale Qualitätskontrolle durch
- Bei technischen Inhalten: Lassen Sie Engineering reviewen
- Bei öffentlichen Kommunikationen: Lassen Sie Corporate Communications reviewen
- Bei HR-Themen: Lassen Sie HR/Legal reviewen

### 📋 Best Practices

**✅ So nutzen Sie Skills sicher:**
- Verwenden Sie **anonymisierte oder fiktive Daten** in Beispielen
- Generalisieren Sie Informationen (z.B. "Ein Automotive-Kunde" statt "BMW Projekt X")
- Nutzen Sie öffentlich verfügbare Produktinformationen (von coherent.com)
- Bei Unsicherheit: Fragen Sie Ihre Führungskraft oder Compliance

**✅ Teilen Sie Skills verantwortungsvoll:**
- Skills mit generischen Vorlagen können geteilt werden
- Skills mit kundenspezifischen Details: Nur intern, nach Freigabe
- Bei öffentlicher Nutzung (z.B. LinkedIn): Keine internen Details

---

## 💡 Best Practices für Coherent-Skills

### DO: ✅

**Markenwerte integrieren:**
✅ Coherent Brand Voice einhalten (Wissenschaftlich, Innovativ, Vertrauenswürdig, Zugänglich)  
✅ I CARE Werte authentisch kommunizieren (nicht als Buzzwords)  
✅ "Innovations That Resonate" wo passend einbinden  
✅ Globale Perspektive zeigen (130+ Standorte, 20+ Länder)

**Qualität sichern:**
✅ Technische Präzision mit Verständlichkeit kombinieren  
✅ Faktenbasiert kommunizieren (Zahlen, Daten belegen)  
✅ Kundennutzen in den Mittelpunkt stellen  
✅ Expertise zeigen ohne Arroganz  
✅ Skills iterativ verbessern (Feedback einholen)

**Collaboration fördern:**
✅ Skills mit Kollegen teilen (wenn angemessen)  
✅ Voneinander lernen (Best Practices austauschen)  
✅ Cross-functional zusammenarbeiten (Engineering ↔ Marketing)

### DON'T: ❌

**Vermeiden Sie:**
❌ Generische Marketing-Floskeln ohne Substanz ("best-in-class", "game-changer")  
❌ Übertriebene Versprechen, die nicht eingehalten werden können  
❌ Negative oder aggressive Wettbewerbsvergleiche  
❌ Fachjargon ohne Erklärung (denken Sie an Ihre Zielgruppe!)  
❌ Veraltete Markenbezüge (II-VI, altes Coherent Inc. – außer historischer Kontext)  
❌ Unkorrekte oder veraltete technische Informationen

**Datenschutz:**
❌ Keine Kundendaten oder vertrauliche Informationen in Skills  
❌ Keine proprietären Details in öffentlichen Prompts  
❌ Keine personenbezogenen Daten ohne Zustimmung

---

## 🏢 Coherent-Spezifische Vorteile von Skills

### Für Sie persönlich:
- **Zeitersparnis**: Weniger Zeit für Routine-Aufgaben, mehr Zeit für strategische Arbeit
- **Konsistenz**: Gleichbleibende Qualität in Ihrer Arbeit
- **Professionalität**: Immer markenkonforme, hochwertige Outputs
- **Lernkurve**: Skills helfen Ihnen, Best Practices zu verinnerlichen

### Für Ihr Team:
- **Wissensaustausch**: Expertise wird in Skills kodifiziert und geteilt
- **Onboarding**: Neue Mitarbeiter lernen schneller durch Skill-Nutzung
- **Effizienz**: Team kann mehr schaffen mit gleichen Ressourcen
- **Qualität**: Coherent-Standards automatisch eingehalten

### Für Coherent Corp.:
- **Brand Consistency**: Einheitliche Markenkommunikation über alle Kanäle
- **Skalierbarkeit**: Mehr Projekte mit gleichen Ressourcen
- **Innovation**: Zeit für Wertschöpfung statt Administration
- **Kundenzufriedenheit**: Schnellere, präzisere Antworten und Lieferungen

---

## 📝 Abteilungsspezifische Quick-Wins mit Skills

### Marketing-Team 🎨

**Sofort einsetzbare Skills:**
1. **Social Media Post Generator** → LinkedIn-Posts für Produktankündigungen
2. **Blog Headline Creator** → 10 Varianten für jeden Artikel
3. **Email Subject Line Optimizer** → A/B-Test-fähige Betreffzeilen
4. **Event Invitation Writer** → Messepräsenz-Ankündigungen
5. **Press Release Drafter** → Grundgerüst für Pressemitteilungen

**Typische Zeitersparnis:** 60-70% bei Content-Erstellung

### Sales-Team 💼

**Sofort einsetzbare Skills:**
1. **Customer Email Responder** → Professionelle Antworten auf Anfragen
2. **Value Proposition Generator** → Angepasst an Kundenbranche
3. **Meeting Follow-up Creator** → Strukturierte Nachfassaktionen
4. **Quote Summary Writer** → Executive Summaries für Angebote
5. **Objection Handler** → Vorbereitung auf Kundeneinwände

**Typische Zeitersparnis:** 40-50% bei E-Mail-Kommunikation

### HR-Team 👥

**Sofort einsetzbare Skills:**
1. **Job Description Generator** → Ansprechende Stellenausschreibungen
2. **Welcome Email Creator** → Onboarding-Kommunikation für neue Mitarbeiter
3. **Internal Announcement Writer** → Unternehmensnachrichten
4. **Employee Recognition Message** → Wertschätzende Kommunikation
5. **Policy Explainer** → Verständliche Erklärungen neuer Richtlinien

**Typische Zeitersparnis:** 50-60% bei Standardkommunikation

### Administration & Operations 📋

**Sofort einsetzbare Skills:**
1. **Meeting Summary Creator** → Protokolle und Action Items
2. **Email Template Generator** → Vorlagen für häufige Anfragen
3. **Process Documentation Writer** → Klare Anleitungen
4. **Status Report Formatter** → Strukturierte Updates
5. **Reminder Message Creator** → Freundliche Erinnerungen

**Typische Zeitersparnis:** 70-80% bei Routine-Dokumentation

### Engineering-Team ⚙️

**Sofort einsetzbare Skills:**
1. **Technical Content Simplifier** → Komplexe Technik verständlich erklären
2. **Application Note Drafter** → Grundstruktur für Tech-Docs
3. **Specification Summarizer** → Executive-Summaries für Datenblätter
4. **Customer Tech-Support Response** → Präzise technische Antworten
5. **Product Feature Explainer** → Features zu Benefits übersetzen

**Typische Zeitersparnis:** 30-40% bei Dokumentationsaufgaben

---

## 🎯 Tipps für den Alltag mit Skills

### Tipp 1: Starten Sie klein
- Beginnen Sie mit **einem** Skill für Ihre häufigste Aufgabe
- Testen Sie es 2-3 Wochen
- Verfeinern Sie basierend auf Ihren Erfahrungen
- Dann: Nächstes Skill erstellen

### Tipp 2: Nutzen Sie die "70%-Regel"
- Erwarten Sie nicht Perfektion beim ersten Versuch
- Wenn das Skill 70% Ihrer Arbeit übernimmt → Erfolg!
- Die restlichen 30% sind Ihre Expertise und Feinschliff

### Tipp 3: Kombinieren Sie Skills
- Nutzen Sie verschiedene Skills für komplexe Projekte
- Beispiel: "Hook Creator" → "Product Launch Communicator" → "Email Responder"
- Workflow statt einzelne Tasks

### Tipp 4: Feedback-Loop etablieren
- Notieren Sie, was gut funktioniert
- Teilen Sie Erkenntnisse mit Kollegen
- Verbessern Sie Skills basierend auf echten Ergebnissen

### Tipp 5: Bleiben Sie flexibel
- Skills sind Werkzeuge, keine Regeln
- Passen Sie sie an Ihre Bedürfnisse an
- Experimentieren Sie mit verschiedenen Ansätzen

---

## Zusammenfassung: Die goldenen Regeln für Coherent

1. **Strukturierte Prompts nutzen** – Klare Anweisungen führen zu besseren Ergebnissen
2. **Brand Voice wahren** – Wissenschaftlich, Innovativ, Vertrauenswürdig, Zugänglich
3. **I CARE Werte leben** – Integrity, Collaboration, Accountability, Respect, Enthusiasm
4. **Qualität vor Quantität** – Lieber ein gutes Skill als fünf mittelmäßige
5. **Human-in-the-Loop** – Immer eigenverantwortlich prüfen vor Veröffentlichung
6. **Datenschutz wahren** – KEINE proprietären Daten, Kundenprojekte, oder NDA-Informationen
7. **Iterativ verbessern** – Skills entwickeln sich mit Ihren Erfahrungen
8. **Wissen teilen** – Erfolgreiche Skills mit Kollegen teilen (wo angemessen)
9. **Authentisch bleiben** – KI unterstützt, ersetzt aber nicht Ihre Expertise
10. **Experimentieren erlaubt** – Probieren Sie verschiedene Ansätze aus!

---

**@ 2025 - HPI KI Workshops | Tutorials**

