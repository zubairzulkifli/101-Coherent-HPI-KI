# 📚 Teil A: Grundverständnis – Wie KI mit Sprache arbeitet 

## Kapitel 1: Wie „denkt" eine KI? 🟢 Basis

### Die Wahrscheinlichkeits-Maschine

Stellen Sie sich ein Wort-Ergänzungsspiel vor. Genau das macht ein Sprachmodell – nur mit Statistik und präziser Mustererkennung.

**Beispiel (vereinfacht):**

```
"Der Kunde benötigt eine Hochgeschwindigkeits-Transceiver-Lösung für..."
→ KI berechnet Wahrscheinlichkeiten:
   - 800G Datacom (38 %)
   - Kohärente Telekommunikation (27 %)
   - 1.6T AI-Cluster (22 %)
   - VCSEL-basierte Verbindungen (13 %)
```

Die KI hat aus sehr vielen Texten gelernt, **welche Wörter typischerweise aufeinander folgen**. Sie „versteht" nicht wie ein Mensch – sie **erkennt und reproduziert Muster**. Dies ähnelt dem Prinzip der Kohärenz in der Photonik: Geordnete Strukturen entstehen durch statistische Wahrscheinlichkeiten, nicht durch bewusstes Design.

### 🎯 Merksätze

* KI = Mustererkennung + Wahrscheinlichkeiten, kein echtes Verständnis.
* Antworten sind **Token für Token** berechnete Vorschläge.
* Wer **präzise Spezifikationen** vorgibt, erhält **präzise Ergebnisse**.

**Praktisches Coherent-Beispiel:**

```
Prompt: 
"Erstelle eine Betreffzeile für ein technisches Whitepaper zur 
Silizium-Photonik in AI-Rechenzentren."

KI denkt u.a.:
- "Silicon Photonics for 1.6T AI Infrastructure: Technical Deep Dive"
- "Enabling Next-Gen Datacom: Coherent's Integrated Photonics Approach"
```

---

## Kapitel 2: Tokens – Die Bausteine der KI-Kommunikation 🟢 Basis

### Was sind Tokens?

Tokens sind kleinste Spracheinheiten (ähnlich Silben/Wortteile). Denken Sie an **atomare Strukturen** – die fundamentalen Bausteine, die unsere Technologien ermöglichen.

**Visualisierung (vereinfachend):**

```
"Optoelektronik" → [Op][to][elek][tro][nik]  ≈ 5 Tokens
"Siliziumkarbid" → [Si][li][zi][um][kar][bid]  ≈ 6 Tokens
"Ultrakurzpulslaser" → [Ultra][kurz][puls][la][ser] ≈ 5 Tokens
```

**Grobe Faustregel (Deutsch):**

* **1 Token ≈ 4 Zeichen**
* **100 Tokens ≈ 70–80 Wörter**
* **Eine A4-Seite ≈ 500–700 Tokens** (je nach Dichte)

**Kostenbewusstsein (modellabhängig):**

```
Kurzer Betreff (10 Wörter)   ≈ 15 Tokens
E-Mail-Absatz (100 Wörter)    ≈ 130 Tokens
Technisches Datenblatt        ≈ 650 Tokens
Produktspezifikation          ≈ 2.600 Tokens
```

**Übung 1 – Token schätzen**

1. „InP" → ___ Tokens
2. „Optoelektronik" → ___ Tokens
3. „Siliziumkarbid-Substrat" → ___ Tokens

*Lösung (typisch):* 1) 1–2  |  2) 4–5  |  3) 6–7

**Warum wichtig?**

* **Jeder Token kostet** (Rechenzeit & Ressourcen).
* **Präziser & strukturierter** = effizienter & schneller.
* **Limits** begrenzen, wie viel technischer Kontext die KI gleichzeitig verarbeiten kann.

---

## Kapitel 3: Das Kontextfenster – das Arbeitsgedächtnis der KI 🟢 Basis

Die KI arbeitet mit einem **technischen Notizblock**. Alles, was Sie eingeben (und was die KI ausgibt), muss auf diesen Block passen – ähnlich wie bei der Optimierung von Datenpaketen in optischen Netzwerken.

**Richtwerte (modell-/anbieterabhängig, ändern sich kontinuierlich):**

```
Typische Größen: ~128.000 bis >1.000.000 Tokens
→ von „mehreren Dutzend" bis „vielen Hundert" A4-Seiten
```

**Wenn der Block voll ist:**

```
[Frühere Spezifikationen] → [Zwischenergebnisse] → [Aktuelles] → [VOLL]
         ↑                                            ↑
     wird verdrängt                              bleibt erhalten
```

**Token sparen – Beispiel:**

```
Weniger präzise:
"Ich hoffe, Sie haben einen angenehmen Tag. Ich hätte da eine Anfrage 
bezüglich optischer Transceiver..."
→ viele Füllwörter, ineffizient

Präzise:
"Liste: 5 technische Vorteile von 800G ZR/ZR+ Transceivern für 
hyperscale Datacenters. Pro Punkt max. 20 Wörter."
→ klar strukturiert, effizient
```

---

## Kapitel 4: Den Token-Fluss verstehen 🟡 Mittel

So verarbeitet die KI Ihren Text:

```
1) EINGABE (Prompt)
2) TOKENISIERUNG  → Zerlegung in Tokens
3) VERARBEITUNG   → Musterabgleich
4) GENERIERUNG    → Ausgabe Token für Token
5) AUSGABE        → fertiger Text
```

**Generierung geschieht sequenziell (vereinfacht):**

```
Schritt 1: "Die" 
Schritt 2: "Die Technologie" 
Schritt 3: "Die Technologie ermöglicht" 
Schritt 4: "Die Technologie ermöglicht präzise..." 
```

**Übung 2 – Prompt kürzen**

* „Könntest du bitte so freundlich sein und mir erklären…"
  → „Erkläre technisch präzise…"
* „Ich würde gerne von dir wissen, falls es möglich ist…"
  → „Spezifiziere…"
* „Es wäre hilfreich, wenn du mir mitteilen könntest…"
  → „Definiere…"

---

# 📝 Teil B: Erste Schritte – Prompts für den Coherent-Alltag

## Kapitel 5: Die 4-K-Formel 🟢 Basis

1. **K**ontext – Technischer Hintergrund, Anwendungsbereich
2. **K**onkrete Aufgabe – Präzise Spezifikation der Anforderung
3. **K**riterien – Wissenschaftliche Tiefe, technische Präzision, Zielgruppe
4. **K**ontrolle – Format (Liste/Tabelle), Länge, technische Details

**Beispiel (Produktdokumentation):**

```
Kontext: 
Technisches Datenblatt für 1.6T-DR8 Transceiver-Modul, 
Zielgruppe: Datacenter-Architekten.

Aufgabe: 
3 Anwendungsszenarien mit Performance-Charakteristiken.

Kriterien: 
Technisch fundiert, IEEE-Standards referenzieren, 
Power-Effizienz hervorheben.

Kontrolle: 
Tabelle, max. 12 Zeilen, am Ende 1 Differenzierungsaussage 
zu Wettbewerbslösungen.
```

---

## Kapitel 6: Kontext aufbauen und halten 🟡 Mittel

**Technik „Roter Faden"**

```
P1: 
"Thema: Entwicklung einer Marketingstrategie für SiC-Substrate Q2/2026. 
Zielgruppen: EV-Hersteller, Leistungselektronik, Ladeinfrastruktur."

P2: 
"Empfehle 5 technische Kommunikationskanäle, je 1 Satz Nutzen 
für die Zielgruppe."

P3: 
"Für Kanal 2: Entwurf eines 3-Monats-Content-Plans mit Fokus 
auf technische Differenzierung."
```

**Technik „Zwischenbilanz"**

```
"Fasse zusammen:
- Technische Spezifikationen (Stichpunkte)
- Offene Engineering-Fragen
- Nächste Entwicklungsschritte (Verantwortlich + Meilenstein)"
```

**Technik „Checkpoint"**

```
"Checkpoint:
Projekt: [Technologie/Produkt].
Erreichte Meilensteine: [Ergebnisse].
Technische Lücken: [Offene Punkte].
Nächster Sprint: [Aufgabe + technisches Format]."
```

**Übung 3 – Kontext-Kette (Produkteinführung)**

1. „Nenne 3 Hauptherausforderungen bei der Markteinführung von 1.6T Transceivermodulen."
2. „Entwickle für Herausforderung 1 drei technische Lösungsansätze (Coherent-Kontext)."
3. „Erstelle Implementierungs-Roadmap 120 Tage, Meilensteine & Engineering-Ressourcen."

---

## Kapitel 7: Token-Sparstrategien 🟡 Mittel

**1) Abkürzungen definieren**

```
"Ab jetzt:
InP = Indiumphosphid
VCSEL = Vertical-Cavity Surface-Emitting Laser
CPO = Co-Packaged Optics
USP = Ultrakurzpulslaser
SiC = Siliziumkarbid

Erstelle Produktvergleich: InP-basierte Transceiver vs. 
SiC-Substrate für CPO-Anwendungen."
```

**2) Struktur erzwingen**

```
"Ausgabe als Tabelle:
Spalte: Technologie | Performance-Vorteil | Anwendungsbereich | 
        Zielmarkt | Verfügbarkeit"
```

**3) Inkrementell arbeiten**

```
Schritt 1: 
"Liste 5 technische Herausforderungen bei der Skalierung 
von 800G auf 1.6T Datacom."

Schritt 2: 
"Detailliere Herausforderung 3 (Root Cause/Auswirkung/Lösung)."

Schritt 3: 
"Erstelle Engineering-Maßnahmenplan (Owner + Technologie-Milestone)."
```

**Mini-Tabelle**

| Technik                              | Vorher | Nachher | Ersparnis |
| ------------------------------------ | ------ | ------- | --------- |
| Abkürzungen & Technisches Glossar    | 150    | 90      | ~40%      |
| Tabellen statt Fließtext             | 300    | 120     | ~60%      |
| Präzise Spezifikationsvorgaben       | 500    | 200     | ~60%      |

---

## Kapitel 8: Häufige Anfängerfehler 🟢 Basis

* **Unstrukturierte Anfragen** → direkt, präzise, technisch fundiert.
* **„Erkläre alles über Photonik…"** → lieber modular (Teilbereiche: VCSEL, InP, SiC).
* **Kontextverlust** → regelmäßig **technische Zusammenfassungen** anfordern.
* **Format ignorieren** → **Tabelle/Liste** explizit spezifizieren.

**Checkliste vor dem Senden**

* [ ] Präzise technische Aufgabe definiert?
* [ ] Ein klar abgegrenztes Thema?
* [ ] Format + Länge spezifiziert?
* [ ] Proprietäre Daten/vertrauliche Informationen 
      entfernt/anonymisiert?
* [ ] Technische Standards (IEEE, ISO) referenziert wo relevant?

---

# 🚀 Teil C: Praxis im Coherent-Alltag

## Kapitel 9: Mini-Projekt – Produkteinführung planen 🟡 Mittel

**Phase 1 – Zielgruppenanalyse (Token-Budget ~100)**

```
Prompt 1.1:
"Erstelle 3 technische Personas für Entscheidungsträger (CTO Hyperscaler / VP Engineering Telecom Equipment / Director R&D Automotive).
Je Persona: Rolle | Hauptziel | Technische Anforderungen | Entscheidungskriterium (je max. 8 Wörter)."
```

**Phase 2 – Technische Strategie (Token-Budget ~150)**

```
Prompt 2.1:
"Für Persona 'CTO Hyperscaler': 3 technische Differenzierungsmerkmale von Coherent 1.6T-Transceivers.
Format: Feature-Name + 1 Satz technischer Nutzen + Performance-Metrik."
```

**Phase 3 – Inhalte (Token-Budget ~200)**

```
Prompt 3.1:
"Entwirf Executive Summary für C-Level-Stakeholder (max. 120 Wörter).
Ton: Technisch präzise, innovationsorientiert, faktenbasiert. Am Ende 1 strategische Empfehlung."
```

**Ihre Aufgabe:**
Dokumentieren Sie je Schritt: geschätzte Tokens, technische Präzision (Bewertung 1-5), Optimierungspotenzial.

---

## Kapitel 10: Fortgeschrittene Techniken 🔴

**1) Technische Denkkette anfordern (ohne proprietäre Daten)**

```
"Leite systematisch her:
1) Technische Problemdefinition
2) Physikalische/technologische Randbedingungen
3) Lösungsoptionen mit Bewertungskriterien
4) Technologie-Trade-offs
5) Empfehlung mit technischer Begründung (1 Satz)"
```

**2) Few-Shot (mit technischem Muster)**

```
"Beispiel-Produktbeschreibung:
- Technologie: VCSEL-Arrays für 3D-Sensing
- Spezifikation: 850nm, 10Gbps, <2mW/Kanal
- Anwendung: Smartphone Face Recognition
- Differenzierung: Vertikal integriert, höchste Zuverlässigkeit

Erstelle nach diesem Muster Beschreibung für: 1.6T-DR8 Transceiver-Modul."
```

**3) Constrained Output (Technische Präzision)**

```
"Beschreibe SiC-Substrate für EV-Leistungselektronik.
Constraints:
- Nur verifizierbare technische Fakten
- IEEE/JEDEC-Standards referenzieren
- Performance-Metriken quantifizieren
- Keine Marketing-Sprache
- Max. 150 Wörter"
```

**4) Multi-Step Reasoning (Technologievergleich)**

```
Prompt-Kette:
"Schritt 1: Nenne 3 Schlüsselparameter für Hochgeschwindigkeits-Transceiver (ohne Wertung)."
"Schritt 2: Bewerte Silizium-Photonik vs. InP-Technologie anhand dieser Parameter."
"Schritt 3: Empfehle Technologie für <100m Datacom (Begründung 2 Sätze)."
```

---

# 🧑‍💼 Persona-Galerie: Coherent Mitarbeiter und ihre KI-Prompts

> **Die „20-Wörter-Methode":**  
> Ein gut formulierter Persona-Prompt beginnt mit: „Ich möchte mit [Rolle] sprechen, der/die [Hauptaufgabe] macht und dabei [Herausforderung/Ziel] im Fokus hat."

Die folgenden Beispiele zeigen, wie unterschiedliche Rollen bei Coherent KI-Assistenten nutzen können, um ihre tägliche Arbeit zu optimieren – von technischer Dokumentation über Kundenkommunikation bis hin zu strategischer Planung.

---

## 1. Technical Sales Engineer für Networking Solutions (Vertrieb)

```markdown
Ich möchte mit einem Technical Sales Engineer sprechen, der 
High-Speed-Transceiver (800G/1.6T) an Hyperscaler verkauft und dabei 
technische Spezifikationen in Business Value übersetzen muss, während 
er gleichzeitig Wettbewerbsdifferenzierung klar kommuniziert und 
komplexe Datacenter-Architekturen verständlich erklärt.
```

**Anwendungsfall:** Erstellung technischer Verkaufspräsentationen, 
ROI-Kalkulationen für optische Netzwerk-Upgrades, Competitive 
Positioning Dokumente, technische Antworten auf RFPs/RFQs von 
Datacenter-Betreibern.

---

## 2. Photonics Application Engineer für Materials Division (Engineering & Technik)

```markdown
Ich möchte mit einem Photonics Application Engineer sprechen, der 
Kunden bei der Integration von SiC-Substraten in EV-Leistungselektronik 
berät und dabei Performance-Optimierung, thermisches Management und 
Zuverlässigkeitsfragen adressiert, während er technische Spezifikationen 
erstellt und Applikationsnotizen verfasst.
```

**Anwendungsfall:** Technische Whitepapers zu SiC-Eigenschaften, 
Anwendungsnotizen für Kunden-Designs, Failure Analysis Reports, 
technische Vergleichsstudien, Design Guidelines für Leistungshalbleiter.

---

## 3. HR Business Partner für Global Operations (Verwaltung & Personal)

```markdown
Ich möchte mit einem HR Business Partner sprechen, der für die Standorte 
Ipoh und Penang (Malaysia) zuständig ist und dabei Talentakquise für 
Photonik-Ingenieure koordiniert, Onboarding-Programme entwickelt und 
Mitarbeiterentwicklungspläne erstellt, während er kulturelle Diversität 
fördert und Coherent's I CARE Werte kommuniziert.
```

**Anwendungsfall:** Job Descriptions für spezialisierte Rollen 
(InP-Prozessingenieure), Onboarding-Materialien für internationale Teams, 
Performance Review Templates, Diversity & Inclusion Kommunikation, 
Training-Programme zu technischen Standards.

---

## 4. Product Marketing Manager für Laser Systems (Vertrieb & Marketing)

```markdown
Ich möchte mit einem Product Marketing Manager sprechen, der 
Ultrakurzpulslaser für Halbleiter-BEOL-Anwendungen vermarktet und dabei 
Go-to-Market-Strategien entwickelt, Produktpositionierung gegen 
Wettbewerber definiert und technische Inhalte für verschiedene 
Stakeholder aufbereitet, während er Markttrends in der Advanced Packaging 
Industrie analysiert.
```

**Anwendungsfall:** Produktlaunch-Pläne, Competitive Intelligence Reports, 
Kundenpräsentationen für C-Level, Value Proposition Dokumente, 
Content-Marketing-Strategien für LinkedIn/Fachmedien, Messekommunikation.

---

## 5. IT Support Specialist für Global Infrastructure (Verwaltung & IT)

```markdown
Ich möchte mit einem IT Support Specialist sprechen, der globale 
IT-Systeme für 130+ Standorte betreut und dabei Incident-Management 
koordiniert, Wissensdatenbank-Artikel erstellt und Anwender-Support 
leistet, während er IT-Sicherheitsrichtlinien durchsetzt und 
System-Dokumentation pflegt.
```

**Anwendungsfall:** Incident-Dokumentationen, IT-Sicherheitsrichtlinien in 
verständlicher Sprache, Benutzerhandbücher für interne Tools, 
Eskalations-Prozeduren, FAQ-Artikel für Helpdesk, Technische Mitteilungen 
an Endanwender.

---

## 6. Optical Communications Specialist für Telecom Products (Engineering & Technik)

```markdown
Ich möchte mit einem Optical Communications Specialist sprechen, der 
kohärente 400G/800G Transceiver für Metro- und Langstrecken-Netze 
entwickelt und dabei DSP-Algorithmen optimiert, Link-Budgets berechnet 
und Field-Trial-Ergebnisse analysiert, während er IEEE-Standards 
interpretiert und technische Kundenanfragen beantwortet.
```

**Anwendungsfall:** Technische Spezifikationsdokumente, 
Link-Budget-Kalkulationen, Test-Reports für Feldversuche, 
Standards-Compliance-Dokumentation, technische Präsentationen für 
Telco-Kunden, Engineering Change Notices.

---

## 7. Executive Assistant für VP Corporate Communications (Verwaltung)

```markdown
Ich möchte mit einer Executive Assistant sprechen, die den VP Corporate 
Communications unterstützt und dabei Meeting-Koordination für globale 
Teams managt, Reiseplanung optimiert und interne Kommunikation vorbereitet, 
während sie Stakeholder-Management unterstützt und vertrauliche 
Informationen mit höchster Diskretion behandelt.
```

**Anwendungsfall:** Meeting-Agenden und Protokolle, Reisekoordination mit 
Budget-Tracking, interne Ankündigungen und Newsletter, Executive Summaries 
für C-Level, Stakeholder-Kommunikation, Event-Organisation für 
Führungskräfte.

---

## 8. Content Marketing Manager für Corporate Brand (Vertrieb & Marketing)

```markdown
Ich möchte mit einem Content Marketing Manager sprechen, der Coherent's 
"Innovations That Resonate" Tagline zum Leben erweckt und dabei 
Thought-Leadership-Artikel verfasst, Social-Media-Kampagnen koordiniert 
und technische Success Stories entwickelt, während er Brand Voice 
Guidelines einhält und SEO-Optimierung betreibt.
```

**Anwendungsfall:** LinkedIn-Posts mit technischem Tiefgang, Blogartikel 
zu Photonik-Trends, Customer Success Stories, Pressemitteilungen, 
Newsletter-Content, Website-Texte, Social-Media-Kampagnen für 
Produktlaunches.

---

# 🔒 Sicherheitshinweise für KI-Nutzung bei Coherent

## Datenschutz & Compliance

**⚠️ Niemals in KI-Tools eingeben:**

* **Proprietäre Produktdaten**: Materialzusammensetzungen, Prozessparameter, Design-Spezifikationen mit Wettbewerbsrelevanz
* **Kundendaten**: Kundenspezifikationen, Vertragsdaten, Projektdetails, Angebotsinformationen
* **Fertigungsinformationen**: Produktionsprozesse, Yield-Daten, Supply-Chain-Details
* **Patentrelevante Informationen**: Erfindungsmeldungen, Patent-Drafts vor Anmeldung
* **Finanzdaten**: Interne Finanzberichte, Pricing-Strategien, Margen-Informationen
* **Mitarbeiterdaten**: Personenbezogene Informationen, Performance Reviews, Gehaltsdaten

**✅ Sicherer Umgang:**

* Verwenden Sie **anonymisierte oder fiktive Beispiele** für Demonstrationszwecke
* Bei technischen Fragen: Nutzen Sie **öffentlich verfügbare Standards und Spezifikationen** (IEEE, ISO)
* Formulieren Sie Anfragen **allgemein genug**, um keine Rückschlüsse auf proprietäre Technologien zu ermöglichen
* Beispiel gut: "Erkläre Vor- und Nachteile von InP vs. SiC für Hochfrequenzanwendungen"
* Beispiel schlecht: "Analysiere unseren internen SiC-Prozess in Fab 3 für Produkt XYZ"

## Qualitätssicherung – Human-in-the-Loop Prinzip

**🎯 Kritische Prüfung obligatorisch:**

KI-Assistenten können überzeugende, aber **technisch inkorrekte** Informationen generieren. Bei Coherent, wo wissenschaftliche Präzision und technische Exzellenz im Mittelpunkt stehen, ist es essentiell:

* **Jede technische Aussage** gegen verlässliche Quellen prüfen (Datasheets, Standards, Fachliteratur)
* **Physikalische Plausibilität** überprüfen – verletzt die KI-Antwort fundamentale Gesetze?
* **Quantitative Angaben** verifizieren (Wellenlängen, Leistungen, Temperaturbereiche, etc.)
* **Standards-Konformität** sicherstellen (IEEE, IEC, JEDEC, etc.)
* **Markenbotschaften** auf Konsistenz mit Corporate Identity prüfen

**Verantwortung:**

* **Sie** sind verantwortlich für die Richtigkeit aller Inhalte, die Sie aus KI-Tools übernehmen
* **Sie** müssen die Qualität eigenständig bewerten, bevor Sie Ergebnisse weiterleiten oder publizieren
* **Sie** tragen die Expertise – KI ist ein Werkzeug, kein Ersatz für fachliches Urteilsvermögen

---

# 💼 Abteilungsspezifische Best Practices

## Engineering & R&D

**Prompt-Struktur für technische Dokumentation:**
```
"Rolle: [Photonics Engineer/Materials Scientist/
         Laser Systems Architect]
Kontext: [Technologiebereich, z.B. InP-Optoelektronik, SiC-Epitaxie]
Aufgabe: [Spezifikation/Analyse/Konzept]
Technische Basis: [Relevante Standards: IEEE 802.3, JEDEC, ISO]
Constraints: [Performance-Anforderungen, physikalische Grenzen]
Format: [Datenblatt/Testbericht/Design Document]
Quellen: [Peer-reviewed Papers, Standards-Dokumente]"
```

**Typische Use Cases:**
* Technische Spezifikationen und Datasheets
* Test- und Validierungsberichte
* Design Reviews und Engineering Documentation
* Failure Mode & Effects Analysis (FMEA)
* Patent-Recherche und Prior Art Analysis
* Technische Präsentationen für Peer Reviews

---

## Vertrieb & Sales Engineering

**Prompt-Struktur für technischen Vertrieb:**
```
"Rolle: Technical Sales Engineer bei Coherent Corp.
Zielgruppe: [CTO/VP Engineering/Procurement bei 
            Hyperscaler/Telco/Automotive OEM]
Kontext: [Kundenherausforderung, z.B. Datacenter-Skalierung auf 1.6T]
Aufgabe: Value Proposition entwickeln
Kriterien: Technisch fundiert, ROI-fokussiert, 
           Differenzierung zu Wettbewerb
Kontrolle: Max. 200 Wörter, mit quantifizierbaren Metriken, 1 CTA"
```

**Typische Use Cases:**
* Technische Verkaufspräsentationen und Pitch-Decks
* ROI-Berechnungen und Total-Cost-of-Ownership-Analysen
* Antworten auf technische RFP/RFQ-Anforderungen
* Competitive Positioning und Differenzierungsdokumente
* Customer Success Stories und Case Studies
* Technische Whitepapers für Lead-Generierung

---

## Marketing & Communications

**Prompt-Struktur für technisches Marketing:**
```
"Rolle: Product Marketing Manager / Technical Content Manager
Zielgruppe: [Engineering Decision Makers / C-Level / Fachmedien]
Kanal: [LinkedIn/Website/Whitepaper/Pressemitteilung]
Thema: [Produktlaunch/Technologie-Trend/Thought Leadership]
Ton: Wissenschaftlich präzise, innovativ, vertrauenswürdig, 
     zugänglich (Coherent Brand Voice)
Format: [Blogartikel/Social Post/Pressemitteilung/
        Produktbeschreibung]
Länge: [Wortanzahl]
Technischer Tiefgang: [Engineering-Level vs. Business-Level]"
```

**Typische Use Cases:**
* Produktlaunch-Materialien und Go-to-Market-Kampagnen
* Thought-Leadership-Artikel zu Photonik-Trends
* Social-Media-Content (LinkedIn, X, YouTube)
* Pressemitteilungen und Medien-Briefings
* SEO-optimierte Website-Texte
* Customer Success Stories und Testimonials
* Webinar- und Event-Promotions

---

## Verwaltung, Admin & HR

**Prompt-Struktur für administrative Aufgaben:**
```
"Rolle: [HR Business Partner/Executive Assistant/
        Operations Coordinator]
Kontext: [Standort/Abteilung, z.B. Global Operations, Ipoh Fab]
Aufgabe: [Dokument-Typ, z.B. Job Description, Onboarding-Plan, 
         Meeting-Agenda]
Kriterien: Klar strukturiert, I CARE Werte integriert, 
           kulturell sensitiv
Zielgruppe: [Mitarbeiter/Management/Kandidaten]
Format: [Dokument-Typ]
Compliance: [HR-Richtlinien, lokale Arbeitsgesetze beachten]"
```

**Typische Use Cases:**
* Job Descriptions für spezialisierte Engineering-Rollen
* Onboarding-Programme und Welcome-Materialien
* Performance Review Templates und Entwicklungspläne
* Interne Kommunikation und Ankündigungen
* Meeting-Agenden und Protokolle
* HR-Richtlinien in verständlicher Sprache
* Training-Programme und Schulungsmaterialien

---

## IT & Operations

**Prompt-Struktur für IT-Support:**
```
"Rolle: IT Support Specialist / Systems Administrator
Kontext: [IT-Infrastruktur-Bereich, z.B. Datacenter, Network, 
         Security]
Aufgabe: [Incident-Dokumentation/User Guide/IT-Policy]
Zielgruppe: [End-User/IT-Team/Management]
Technisches Level: [Nicht-technisch/Technisch/Expert]
Format: [FAQ/Anleitung/Ticket-Dokumentation/Policy]
Sicherheit: Keine System-Details, Credentials oder 
            Netzwerk-Topologien"
```

**Typische Use Cases:**
* IT-Incident-Dokumentationen und Root-Cause-Analysen
* Benutzerhandbücher und IT-Self-Service-Guides
* IT-Sicherheitsrichtlinien in verständlicher Sprache
* Wissensdatenbank-Artikel für Helpdesk
* IT-Change-Management-Dokumentation
* System-Mitteilungen und User-Kommunikation

---

# 🎯 Branchenspezifische Prompts

## Hyperscale Datacenters & Cloud

**AI-Infrastruktur & Networking:**
```
"Erstelle [technisches Dokument] für Hyperscaler.
WICHTIG: 
- Fokus auf AI-Cluster-Architektur (800G/1.6T/3.2T Roadmap)
- Power-Effizienz und TCO quantifizieren
- Latenz- und Bandbreiten-Anforderungen für GPU-Interconnects
- IEEE 802.3 Compliance hervorheben
- Vertikal integrierte Supply-Chain-Vorteile betonen
- Co-Packaged Optics (CPO) und Optical Switching erwähnen"
```

## Automotive & Elektromobilität

**SiC für EV-Leistungselektronik:**
```
"Erstelle [Produktinformation] für Automotive OEMs.
WICHTIG:
- SiC-Vorteile für Traction Inverters und On-Board-Chargers
- AEC-Q101/Q102 Qualifizierung hervorheben
- Thermisches Management und Zuverlässigkeit (MTBF)
- Supply-Chain-Resilienz und lokale Verfügbarkeit
- 150mm/200mm Wafer-Skalierung
- ADAS und LiDAR-Anwendungen (VCSEL-Technologie)"
```

## Telekommunikation & 5G

**Kohärente Optik & Glasfaser:**
```
"Erstelle [technisches Whitepaper] für Telco-Betreiber.
WICHTIG:
- Metro/Long-Haul/Submarine Netzwerk-Anforderungen
- Kohärente 400G/800G ZR/ZR+ Transceiver
- DWDM und Wellenlängen-Management
- 5G Fronthaul/Backhaul/Midhaul
- ITU-T Standards (G.698.x, G.metro)
- Power-Budget und Reichweiten-Optimierung"
```

## Consumer Electronics & 3D-Sensing

**VCSEL für Face Recognition & AR:**
```
"Erstelle [Produktpräsentation] für Consumer Electronics OEMs.
WICHTIG:
- VCSEL-Arrays für strukturiertes Licht (3D-Sensing)
- Smartphone Face Recognition und AR-Anwendungen
- Niedrige Leistungsaufnahme (<2mW/Kanal)
- Vertikal integrierte Fertigung (Sherman, TX)
- Apple-Partnership als Referenz (ohne Details)
- Time-of-Flight (ToF) vs. strukturiertes Licht"
```

## Halbleiter-Industrie & Advanced Packaging

**Ultrakurzpulslaser für BEOL:**
```
"Erstelle [Anwendungsnotiz] für Semiconductor Equipment Hersteller.
WICHTIG:
- Präzisions-Laser-Dicing und Via-Bohren
- Advanced Packaging (2.5D/3D-IC, Chiplets)
- Femtosekunden-Laser für Low-k Dielectric Processing
- Thermisches Management (kalte Ablation)
- Durchsatz und Cost-per-Die Optimierung
- Integration mit Pick-and-Place-Systemen"
```

---

# 💡 Tipps für den Alltag

## Wissenschaftliche Präzision wahren

**DO's:**
* Quantifizieren Sie Aussagen wo möglich (Wellenlängen, Leistungen, Datenraten)
* Referenzieren Sie etablierte Standards (IEEE, ISO, JEDEC)
* Nutzen Sie Fachterminologie korrekt (z.B. "kohärent" vs. "inkohärent")
* Fordern Sie Quellenangaben für technische Claims

**DON'Ts:**
* Vermeiden Sie Marketing-Superlative ohne technische Basis
* Keine Übertreibungen ("revolutionär", "weltweit einzigartig")
* Keine ungenauen Vergleiche ("deutlich besser", "viel effizienter")

## Coherent Brand Voice in Prompts integrieren

```
"Ton: Wissenschaftlich präzise, innovativ, vertrauenswürdig, zugänglich.
Stil: Aktive Formulierungen, technische Metaphern 
      (atomare Strukturen, Kohärenz).
Werte: I CARE (Integrity, Collaboration, Accountability, 
       Respect, Enthusiasm).
Tagline-Spirit: 'Innovations That Resonate' – 
                Fokus auf transformative Wirkung."
```

## Iteratives Verfeinern

**Best Practice:**
1. Erster Prompt: Breite Anfrage, um Richtung zu erkunden
2. Zweiter Prompt: Spezifizierung basierend auf Output
3. Dritter Prompt: Feinschliff (Format, Tonalität, Länge)
4. **Human Review**: Kritische Prüfung auf technische Korrektheit

**Beispiel:**
```
Prompt 1: "Erkläre Vorteile von Silizium-Photonik für Datacom."
→ KI gibt breiten Überblick

Prompt 2: 
"Fokussiere auf Power-Effizienz. Vergleiche mit InP-Technologie. 
Max. 100 Wörter."
→ KI spezifiziert

Prompt 3: "Ergänze quantitative Metriken (Watt/Gbps). Coherent Brand Voice."
→ Finaler Output

Review: Prüfe IEEE-Konformität, verifiziere Zahlen gegen Datasheets
```

---

# 🧪 Übungsteil (für das Seminar)

### Ü1 – Produktankündigung (5 Min)

```
Thema: "Neue 1.6T-DR8 Transceiver-Module für AI-Datacenter"
Erzeuge 5 Betreffvarianten für technische Pressemitteilung 
(≤70 Zeichen).
Ton: Innovativ, technisch fundiert, Coherent Brand Voice.
```

### Ü2 – Executive Summary (10 Min)

```
Kontext: C-Level benötigt Kurzlage zu "Coherent SiC-Strategie 2026".
Aufgabe: 5 Sätze, je ≤20 Wörter, am Ende 1 strategische Empfehlung.
Kriterien: Faktenbasiert, Markttrends integrieren, 
           I CARE Werte erkennbar.
```

### Ü3 – Technische Problemanalyse (10 Min)

```
Eingabe: (Trainer-Text: Kundenanfrage zu Performance-Problemen)
Ausgabe: Root Cause (3 Sätze), 3 technische Lösungsansätze, 
         Empfehlung mit Begründung.
Format: Tabelle, technisch präzise.
```

### Ü4 – QA-Check (5 Min)

```
Prüfe Ü2 gegen Coherent Quality-Checkliste:
- Wissenschaftliche Präzision
- Brand Voice Konformität
- I CARE Werte erkennbar
- Keine Marketing-Floskeln
Nenne nur Abweichungen + Korrekturvorschlag.
```

### Ü5 – Abteilungsspezifische Anwendung (15 Min)

**Technical Sales:**
```
Erstelle Elevator Pitch (30 Sekunden) für 800G ZR+ Transceiver 
bei Hyperscalern.
Zielgruppe: VP Network Engineering. 
Fokus: Business Value, TCO-Optimierung.
```

**Product Marketing:**
```
Entwickle LinkedIn-Post-Konzept zu 
"50 Jahre Coherent Photonik-Innovation".
3 Post-Varianten mit technischem Storytelling-Element und 
Call-to-Action.
```

**R&D Engineering:**
```
Verfasse Design Review Summary für neuartigen InP-Prozess.
5 Key Findings, technische Risiken, Next Steps mit Meilensteinen.
```

**HR:**
```
Erstelle Job Description für "Senior Photonics Application Engineer".
Rolle, Anforderungen, I CARE Werte, Coherent USPs als Arbeitgeber.
```

**IT Support:**
```
Verfasse Knowledge Base Artikel: "VPN-Setup für Remote-Mitarbeiter".
Schritt-für-Schritt, nicht-technische Sprache, 
Troubleshooting-Sektion.
```

---

# 📎 Schnellstart-Karten (zum Ausdrucken)

**1) 4-K-Formel für technische Präzision**

```
Kontext (Technologie/Anwendung) | Konkrete Aufgabe (Spezifikation) | 
Kriterien (Standards/Tiefgang) | Kontrolle (Format/Metriken)
```

**2) Standard-Kontrollsätze**

```
"Keine proprietären Daten, nur öffentlich verfügbare Informationen."
"IEEE/ISO-Standards referenzieren; sonst 'keine Standards-Basis'."
"Ausgabe als Tabelle, max. [Länge], quantitative Metriken."
"Technische Präzision prüfen, keine ungenauen Aussagen."
"Coherent Brand Voice: wissenschaftlich, innovativ, vertrauenswürdig, 
 zugänglich."
"I CARE Werte integrieren: Integrity, Collaboration, Accountability, 
 Respect, Enthusiasm."
```

**3) Technischer Sales-Prompt**

```
"Executive Summary [Technologie] für [Kundentyp]:
5 Sätze, technisch fundiert, Business-Value-Fokus, 
1 quantifizierbare Metrik, 1 CTA."
```

**4) Branchen-Prompts**

```
Datacenters: "AI-Cluster-Anforderungen, Power-Effizienz, 
              IEEE 802.3 Compliance."
Automotive: "AEC-Q Qualifizierung, MTBF, Supply-Chain-Resilienz."
Telco: "ITU-T Standards, Metro/Long-Haul, kohärente Optik."
Consumer: "Niedrige Leistung, Miniaturisierung, Massenproduktion."
Semiconductor: "Präzision, Durchsatz, Advanced Packaging."
```

---

# 📚 Glossar (Coherent-spezifisch)

* **Completion** – KI-Antwort auf einen Prompt
* **Kontextfenster** – „Arbeitsgedächtnis" der KI (Token-Limit)
* **Few-Shot** – KI durch Beispiele anleiten
* **Halluzination** – Erfundene technische „Fakten" (kritisch zu prüfen!)
* **Prompt** – Ihre Anweisung an die KI
* **Temperature** – Kreativitätsparameter (niedrig = deterministischer)
* **Token** – kleinste Recheneinheit für Text
* **InP** – Indiumphosphid (Halbleitermaterial für Optoelektronik)
* **VCSEL** – Vertical-Cavity Surface-Emitting Laser
* **SiC** – Siliziumkarbid (Wide-Bandgap Halbleiter)
* **CPO** – Co-Packaged Optics (Integration von Optik und Elektronik)
* **ZR/ZR+** – Kohärente Transceiver-Standards für Datacom/Telco
* **USP** – Ultrakurzpulslaser (Femtosekunden-/Pikosekunden-Laser)

---

## ✅ Zusammenfassung: Die goldenen Regeln für Coherent

- **Strukturierte Prompts** nutzen – keine "Quick & Dirty"-Anfragen, vor allem bei technischen Specs
- **Quellen einfordern** – jede Zahl, jedes Fakt belegen lassen 
- **Temperature bewusst wählen** – faktenbasiert niedrig (0.1-0.3), kreativ höher (0.6-0.8)
- **Bias aktiv reduzieren** – Perspektivenwechsel und Gegenprüfung (Devil's Advocate)
- **Technologie-Neutralität** – keine automatische Bevorzugung bestimmter Plattformen ohne Begründung
- **Menschliche Validierung** – bei kritischen/kundenbezogenen Inhalten Pflicht (Human-in-the-Loop)
- **Datenschutz wahren** – KEINE proprietären Daten, Kundenprojekte oder NDA-Informationen eingeben
- **Compliance beachten** – Qualitätsstandards, regulatorische Anforderungen
- **Dokumentation & Wissensaustausch** – erfolgreiche Prompts teilen, aus Fehlern lernen

---


**@ HPI - 2025 | KI-Praxisworkshop Tutorials**
