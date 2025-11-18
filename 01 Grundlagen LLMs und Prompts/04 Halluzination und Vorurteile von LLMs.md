# Halluzinationen & Bias bei KI-Sprachmodellen vermeiden
## Ein praxisorientierter Leitfaden für Coherent Corp.

---

## 📚 Teil 1: Grundlagen – Warum "halluzinieren" KI-Sprachmodelle?

### Was bedeutet "Halluzination" bei KI-Sprachmodellen – und warum ist das im Photonik-Kontext kritisch?

KI-Sprachmodelle erzeugen sprachlich plausible Antworten auf Basis von Wahrscheinlichkeiten – nicht auf Basis von echtem "Verstehen". Im professionellen Umfeld eines globalen Photonik-Marktführers wie Coherent führt das zu besonderen Risiken:

* 📄 **Mustervervollständigung:** Fehlende Fakten (z. B. zu technischen Spezifikationen optischer Transceiver oder Lasersystemparametern) werden glaubwürdig "ergänzt".
* 📊 **Überanpassung:** Aus einzelnen Fachpublikationen werden allgemeine Photonik-Branchenaussagen abgeleitet.
* 🎯 **Kontext-Drift:** Fragen zu aktuellen Technologien (z. B. 800G/1.6T Datacom) vermischen sich mit veralteten Informationen.
* ⚡ **Temperatur-Parameter:** Höhere Kreativität erhöht das Risiko falscher, aber überzeugender Antworten.

**Coherent-spezifische Folgen:** Fehlerhafte Kundenpräsentationen über optische Systeme, inkorrekte technische Dokumentation von Laserspezifikationen, falsche Angebotsinhalte für Halbleitermaterialien, unzulässige Produktversprechen bei VCSEL-Arrays, Reputationsrisiken bei Kunden und Partnern im High-Tech-Bereich.

### Warum entsteht Bias – und wie zeigt er sich in der Photonik-Industrie?

Bias (systematische Verzerrung) spiegelt unausgewogene Trainingsdaten wider:

* 🛡️ **Technologie-Bias:** Dominanz bestimmter Photonik-Plattformen oder Laser-Typen in Trainingsdaten.
* 🌍 **Kultur-/Sprach-Bias:** Englische/US-Perspektive dominiert, europäische Photonik-Landschaft und DACH-spezifische Anforderungen unterrepräsentiert.
* 👥 **Rollen-Bias:** Veraltete Stereotype zu technischen Berufen (z. B. "Optical Engineer = rein männlich", "Customer Support = weniger technisch").
* ✅ **Confirmation Bias:** Modell bestätigt vermutete Trends (z. B. "Silizium-Photonik = immer besser als InP"), ohne spezifische Kundenanforderungen zu prüfen.

---

## 🎯 Teil 2: Halluzinationen erkennen & vermeiden – für alle Bereiche bei Coherent

### 2.1 Struktur-Prompts statt "kurzer Frage"

**❌ Fehleranfälliger Prompt (generisch):**

```
Wie ist die aktuelle Marktlage bei optischen Transceivern und was bedeutet das für unsere Vertriebsstrategie?
```

**✅ Belastbarer Prompt mit "Step-by-Step" (Coherent-Kontext):**

```
Erstelle eine faktenbasierte Kurzlage (max. 10 Sätze) zur Entwicklung des optischen Transceiver-Marktes für KI-Rechenzentren und Auswirkungen auf Coherent's Datacom-Vertriebsstrategie.

1) QUELLEN:
- Nutze NUR verifizierte Quellen (z. B. LightCounting, Dell'Oro Group, Yole Intelligence, IEEE Photonics Society, Fachmedien wie Laser Focus World, Photonics Spectra).
- Keine Blogs oder Foren ohne redaktionelle Verantwortung.

2) AKTUALITÄT:
- Nenne das genaue Datum der verwendeten Zahlen.
- Markiere Informationen älter als 6 Monate mit [Veraltet].

3) INHALT:
- Nenne aktuelle Marktvolumina und Wachstumsraten für 800G/1.6T Transceiver.
- Skizziere Auswirkungen auf Coherent's Networking-Segment (Datacom, Telecom, Kabel).
- Führe Unsicherheiten und Szenarien (Best-/Base-/Worst-Case) separat auf.

4) KENNZEICHNUNG:
- Jede Zahl mit [Quelle, Jahr].
- Eigene Ableitungen als [Einschätzung] markieren.

5) OUTPUT-FORMAT:
- Bullet-Point-Briefing + 3 Handlungspunkte für Vertriebsleitung Networking.
```

**🎯 Wirkung:** Nachvollziehbar, datengesichert, klar getrennt zwischen Fakt & Einschätzung – im Einklang mit Coherent's wissenschaftlicher Präzision.

### 2.2 Temperatur & Top-P sinnvoll einstellen

```
Für technische/faktische Inhalte (Laserparameter, Wellenlängen, Materialspezifikationen, Compliance):
- Temperature: 0.1–0.3
- Top-P: 0.1–0.5

Für Ideation (Marketing-Kampagnen für Photonik-Lösungen, Produktnamen, Messestands-Konzepte):
- Temperature: 0.6–0.8 (Fakten gesondert prüfen)
- Top-P: 0.7–0.95
```

### 2.3 Eingebaute Faktenprüfung (Fact-Checking)

**✅ Prompt-Template (Coherent-Kontext):**

```
Erstelle ein Management-Briefing (max. 1 Seite) zur Entwicklung im optischen Kommunikationsmarkt mit Fokus auf KI-Rechenzentren.

VALIDIERUNG:
1) Nutze nur verifizierte Primärquellen (z. B. LightCounting Market Reports, Dell'Oro Quarterly Updates, IEEE Publications, Herstellerangaben von Hyperscalern).
2) Markiere pro Aussage:
   - [Quelle: Name, Link/Publikation, Datum]
   - [Einschätzung] für interne Ableitungen
   - [Keine Daten verfügbar] falls Lücke
3) Weise explizit auf Datenstand + Unsicherheiten hin.
4) Füge am Ende eine Prüfliste "Was intern bei Coherent Labs zu verifizieren ist" hinzu.
```

---

## 🔍 Teil 3: Bias erkennen & reduzieren – typische Coherent-Fälle

### 3.1 Häufige Bias-Arten im Photonik-Umfeld

| Bias-Typ | Coherent-Beispiel | Erkennung |
|----------|-------------------|-----------|
| **Technologie-Bias** | "Silizium-Photonik ist immer besser als InP-basierte Lösungen." | Gegentest mit anwendungsspezifischen Performance-Studien (Datacom vs. Telecom) |
| **Markt-Bias** | Überbewertung von Hyperscaler-Trends, Vernachlässigung von Telecom/Enterprise | Ausgewogene Analyse aller Coherent-Zielmärkte (Industrial, Communications, Electronics, Instrumentation) |
| **Rollen-Bias** | "Optical Engineer = nur männlich" oder "Sales = weniger technisch als R&D" | Kompetenzprofile aller Rollen bei Coherent gleichwertig darstellen, Diversität betonen |
| **Quellen-Bias** | "US-Datacenter-Trends = global gültig" | EMEA/APAC-Quellen gegenprüfen, regionale Unterschiede in Netzwerkarchitekturen beachten |
| **Kunden-Bias** | "KMU-Kunden brauchen keine hochperformanten optischen Systeme" | Kundenindividuelle Anforderungsanalyse ohne Vorurteile |

### 3.2 A/B-Prompting gegen Bias

**Prompt A (riskant):**

```
Beschreibe den typischen Coherent-Kunden für 800G Transceiver.
```

**Prompt B (besser):**

```
Beschreibe die Vielfalt der Coherent-Kunden für optische 800G/1.6T Transceiver:
- Marktsegmente (Hyperscale Data Centers, Telco Cloud, Enterprise Networks, High-Performance Computing)
- Unternehmensgrößen (Global Tech Giants bis mittelständische Netzwerkbetreiber)
- Geografische Unterschiede (Nordamerika, EMEA, APAC)
- Verschiedene Architekturanforderungen (DR8, FR4, ZR/ZR+, LR4)
- Unterschiedliche Integrationsgrade (vertikal integrierte OEMs vs. Systemintegratoren)
- Regionale Besonderheiten (z.B. europäische Datenschutz-Anforderungen)
Vermeide Stereotype. Nutze inklusive und kundenorientierte Sprache gemäß Coherent's I CARE Werten (Respect).
```

### 3.3 Perspektivenwechsel für ausgewogene Lösungskonzepte

```
Analysiere Anforderungen für eine optische Netzwerk-Upgrade-Lösung aus DREI Blickwinkeln:

1) Kunden-Management (Datacenter Operator):
- TCO, Energieeffizienz, Skalierbarkeit, Zukunftssicherheit

2) Endanwender (Netzwerk-Engineering-Team beim Kunden):
- Performance, Kompatibilität, Diagnostik-Features, Implementierungsaufwand

3) Coherent Technical Sales & Application Engineering:
- Produktverfügbarkeit, Customization-Möglichkeiten, Support-Komplexität, Wettbewerbsposition

SYNTHESE:
- Überschneidungen, Zielkonflikte, Quick Wins (30/60/90 Tage)
- Risikominimierung und Erfolgsfaktoren
- Alignment mit "Innovations That Resonate"
```

### 3.4 "Devil's Advocate" verpflichtend

```
Nach jeder Technologie-Empfehlung (z.B. Transceiver-Plattform, Laser-Typ, Material-Auswahl):
- Was spricht GEGEN diese Lösung aus technischer Sicht?
- Welche Kundengruppen könnten Nachteile haben (z.B. Legacy-Kompatibilität)?
- Gibt es physikalische Limitierungen oder Umgebungsbedingungen, die kritisch sind?
- Welche unbeabsichtigten Effekte drohen operativ (z.B. Thermal Management)?
- Welche Alternativen sollten in Betracht gezogen werden (z.B. andere Modulationsformate)?
- Wie steht unsere Lösung im Vergleich zum Wettbewerb?
```

---

## 🛠️ Teil 4: Praktische Techniken für verschiedene Coherent-Bereiche

### 4.1 Selbst-Validierungs-Checkliste (Coherent-Version)

```markdown
## Kundenunterlagen / Interne Dokumente – KI-Validierung bei Coherent

☑ TECHNISCHE DATEN
- Optische Spezifikationen (Wellenlängen, Leistungspegel, Extinction Ratio) plausibel?
- Produktbezeichnungen, Teilenummern, Firmware-Versionen korrekt?
- Kompatibilitäten mit Standards (IEEE 802.3, MSA-Specs) verifiziert?
- Physikalische Parameter (Temperatur, Feuchte, mechanische Abmessungen) korrekt?

☑ COMPLIANCE & QUALITÄT
- Relevante Standards referenziert (ISO 9001, TL 9000, IEC, RoHS)?
- Export-Control-Aspekte berücksichtigt (EAR, ITAR)?
- Keine verbindliche Rechtsberatung formuliert?
- Qualitätsversprechen im Einklang mit Coherent's Qualitätsmanagementsystem?

☑ BIAS-CHECK
- Technologieneutrale Darstellung (kein automatischer Bias für/gegen bestimmte Plattformen)?
- Verschiedene Kundentypen und Marktsegmente berücksichtigt?
- Sprache professionell, inklusiv und im Einklang mit I CARE-Werten?

☑ QUELLEN
- Herstellerdokumentation, IEEE Papers, MSA Specs, offizielle Datasheets?
- Aktualität ≤ 12 Monate (falls älter: [Veraltet] markieren)
- Eigene Einschätzungen klar als [Coherent Engineering Assessment] gekennzeichnet?

☑ VERTRAULICHKEIT
- Keine kundensensiblen Projektdaten (z.B. Custom Design Details)?
- Keine proprietären Fertigungsprozesse oder Materialzusammensetzungen?
- NDA-geschützte Informationen geschützt?
- Keine Weitergabe interner Roadmap-Informationen ohne Freigabe?
```

### 4.2 Prompt-Vorlagen für typische Coherent-Aufgaben

**📊 Management-Briefing (faktenbasiert) – Networking Segment:**

```
Temperature: 0.2
Aufgabe: Erstelle ein 1-Seiten-Briefing zur Marktentwicklung im Bereich 800G/1.6T optische Transceiver für KI-Rechenzentren.

REGELN:
- Nutze NUR bereitgestellte Zahlen/Quellen [hier einfügen: LightCounting Q4 2024, Dell'Oro Reports].
- Keine Schätzungen ohne Kennzeichnung [Engineering Estimate].
- Nenne für jede Kennzahl: Zeitraum, Einheit, Quelle.
- Trenne "Marktfakten" und "Implikationen für Coherent's Datacom-Strategie".
- Ende: 3 priorisierte Handlungsempfehlungen (0–90 Tage) für Networking Leadership.
```

**📝 Technisches Lösungskonzept mit Risikoanalyse – Lasers Segment:**

```
Temperature: 0.3
Erstelle ein kompaktes Lösungskonzept (max. 12 Bullet Points) für eine Ultrakurzpuls-Laser-Anwendung in der Halbleiter-Fertigung (BEOL).

Abschnitte:
1) Kundenanforderungen & Anwendungsfall (z.B. Via-Drilling, Dicing)
2) Laser-Spezifikationen (Wellenlänge, Pulsdauer, Repetitionsrate, Strahlqualität)
3) Systemintegration & Beam Delivery
4) Prozess-Monitoring & Qualitätssicherung
5) TCO-Betrachtung (inkl. Uptime, Wartung, Betriebskosten)
6) Risiken (technisch, prozessbezogen, Lieferkette)
7) Alternativen + "Devil's Advocate" (andere Laser-Typen, andere Hersteller)
8) Implementierungsplan & Meilensteine
```

**💡 Marketing-Kampagne mit Zielgruppen-Diversität – Communications Market:**

```
Temperature: 0.7
Generiere 5 Kampagnenideen für die Bewerbung von Coherent's 800G ZR/ZR+ kohärenten Transceivern.

DIVERSITÄT:
- 2 Ideen für Hyperscale Datacenter Operators (Google, Meta, Microsoft)
- 2 Ideen für Telco Cloud & Service Provider (AT&T, Verizon, Deutsche Telekom)
- 1 Idee für Enterprise/Financial Services Networks
- Jede Idee: Online/Offline-Kanal, Zielgruppe, Kernbotschaft (mit Bezug zu "Innovations That Resonate")
- Budgetvarianten: klein (<50k USD) / mittel (50-200k USD) / groß (>200k USD)

TECHNISCHE POSITIONIERUNG:
- Vertikale Integration als USP (von InP-Chips bis fertiges Modul)
- Energieeffizienz & Thermal Management
- Supply Chain Resilience

BIAS-VERMEIDUNG:
- Keine Überbetonung von US-Märkten
- Europäische Datenschutz-Anforderungen erwähnen
- APAC-Wachstumsmärkte berücksichtigen
```

---

## 🎭 Teil 5: Personas – Praxisbeispiele aus verschiedenen Coherent-Bereichen

Die folgenden Persona-Beispiele nutzen die bewährte "20-Wörter-Methode", um KI-Assistenten optimal auf spezifische Rollen bei Coherent einzustellen. Jede Persona beginnt mit "Ich möchte mit..." und definiert klar Rolle, Kontext und Anforderungen.

### 1. Optical Communications Application Engineer (Engineering & Technik)

```markdown
Ich möchte mit einem erfahrenen Optical Communications Application Engineer bei Coherent sprechen, der Kunden bei der Integration von 800G/1.6T Transceivern in Datacenter-Netzwerke unterstützt, technische Spezifikationen erklärt und Design-Empfehlungen gibt.
```

**Anwendungsfall:** Erstellung technischer Application Notes, Link-Budget-Berechnungen für Kunden, Troubleshooting-Guides für optische Übertragungsstrecken, Kundenworkshops zu kohärenter Optik.

---

### 2. HR Business Partner – Talent Development (Verwaltung, Admin, IT & Personalwesen)

```markdown
Ich möchte mit einem HR Business Partner bei Coherent sprechen, der Talent-Development-Programme für technische Mitarbeiter koordiniert, Karrierepfade im Engineering-Bereich gestaltet und die I CARE-Werte in Entwicklungsprogramme integriert.
```

**Anwendungsfall:** Erstellung von Schulungskonzepten für neue Technologien (z.B. Co-Packaged Optics), Onboarding-Programme für Optical Engineers, Performance-Review-Guidelines, Diversitäts- und Inklusionsinitiativen.

---

### 3. Technical Sales Engineer – Materials Segment (Vertrieb, Marketing & Sales)

```markdown
Ich möchte mit einem Technical Sales Engineer bei Coherent sprechen, der SiC-Substrate und Epitaxie-Wafer an Hersteller von Elektrofahrzeug-Leistungselektronik verkauft und technische Kundenanforderungen mit Produktspezifikationen abgleicht.
```

**Anwendungsfall:** Erstellung von Value Propositions für SiC-Materialien, technische Präsentationen für Automotive-OEMs, Antworten auf technische RFIs (Request for Information), ROI-Berechnungen für Kundenprojekte.

---

### 4. Laser Systems Scientist – R&D (Engineering & Technik)

```markdown
Ich möchte mit einem Laser Systems Scientist bei Coherent sprechen, der Ultrakurzpuls-Laser für Advanced Packaging in der Halbleiterindustrie entwickelt, Publikationen in peer-reviewed Journals verfasst und mit Forschungsinstituten kooperiert.
```

**Anwendungsfall:** Verfassen wissenschaftlicher Paper, Erstellung technischer Whitepapers zu neuartigen Laserprozessen, Patent-Disclosure-Dokumente, Konferenzbeiträge (z.B. SPIE Photonics West, CLEO).

---

### 5. IT Support Specialist – Global Operations (Verwaltung, Admin, IT & Personalwesen)

```markdown
Ich möchte mit einem IT Support Specialist bei Coherent sprechen, der interne IT-Systeme an über 130 Standorten weltweit unterstützt, Ticketing-Systeme verwaltet und IT-Dokumentationen für Endanwender erstellt.
```

**Anwendungsfall:** Erstellung von Knowledge Base-Artikeln für häufige IT-Probleme, Schritt-für-Schritt-Anleitungen für Software-Tools, FAQ-Dokumente für Mitarbeiter, IT-Security-Awareness-Materialien.

---

### 6. Product Marketing Manager – Networking (Vertrieb, Marketing & Sales)

```markdown
Ich möchte mit einem Product Marketing Manager bei Coherent sprechen, der Go-to-Market-Strategien für neue Transceiver-Plattformen entwickelt, Wettbewerbsanalysen durchführt und Content für Messen wie OFC erstellt.
```

**Anwendungsfall:** Erstellung von Produktbroschüren, technischen Landing Pages, Social-Media-Content (LinkedIn Posts über neue Produkt-Launches), Competitive Battle Cards, Kunden-Case-Studies, Video-Skripte für YouTube.

---

### 7. Finance Controller – Segment Reporting (Verwaltung, Admin, IT & Personalwesen)

```markdown
Ich möchte mit einem Finance Controller bei Coherent sprechen, der monatliche Segment-Reportings (Networking, Materials, Lasers) erstellt, Budgetabweichungen analysiert und Management-Präsentationen für Quartalsergebnisse vorbereitet.
```

**Anwendungsfall:** Erstellung von Executive Summaries zu Finanzkennzahlen, Visualisierung von Revenue/Margin-Trends, Kommentierung von Geschäftsentwicklungen für Investor Relations, Forecasting-Modelle.

---

### 8. Customer Success Manager – Lasers Segment (Vertrieb, Marketing & Sales)

```markdown
Ich möchte mit einem Customer Success Manager bei Coherent sprechen, der strategische Kunden im Bereich industrieller Lasersysteme betreut, Trainings koordiniert und proaktiv Optimierungspotenziale in Kundenprozessen identifiziert.
```

**Anwendungsfall:** Erstellung von Quarterly Business Reviews (QBRs) für Kunden, Training-Materialien zu Laser-Wartung und Optimierung, Best-Practice-Guides für spezifische Anwendungen (z.B. Laserschneiden, -schweißen), Eskalations-Dokumentationen.

---

## 🔒 Datenschutz & Compliance: Besondere Hinweise für Coherent

**Bei der Nutzung von KI-Sprachmodellen:**

✅ **Erlaubt:**
- Anonymisierte/pseudonymisierte Beispieldaten (z.B. "Kunde A benötigt 10.000 Transceiver/Jahr")
- Öffentlich verfügbare Informationen (z.B. Pressemitteilungen, Produktdatenblätter)
- Allgemeine technische Fragestellungen ohne spezifische Kundenprojekte
- Strukturierung und Formatierung von Inhalten

🚫 **Verboten – Keine Eingabe von:**
- **Kundensensiblen Daten**: Projektdetails, Kundenspezifikationen, Vertragskonditionen, Angebotsdaten
- **Proprietären Technologien**: Fertigungsprozesse, Materialzusammensetzungen, Design-Details von Custom-Produkten
- **Forschungsdaten**: Unveröffentlichte F&E-Ergebnisse, Patent-Anmeldungen vor Veröffentlichung
- **Mitarbeiterdaten**: Personenbezogene Daten, Performance-Reviews, Gehaltsinformationen
- **Vertrauliche Geschäftsdaten**: Umsatzzahlen einzelner Kunden, interne Roadmaps, Pricing-Strategien
- **Source Code mit Sicherheitsrelevanz**: Firmware, Kontrollsoftware, proprietäre Algorithmen
- **Informationen unter NDA**: Alle Daten, die durch Geheimhaltungsvereinbarungen geschützt sind

**Coherent-spezifische Compliance-Grundsätze:**
- **Export Control beachten**: Keine technischen Details eingeben, die EAR/ITAR-relevant sein könnten
- **I CARE-Wert "Integrity"**: Ehrlicher Umgang mit KI-Limitierungen gegenüber Kunden
- **Human-in-the-Loop-Prinzip**: Bitte prüfe alle KI-generierten Ergebnisse eigenverantwortlich, bevor du sie weitergibst oder veröffentlichst. Das Human-in-the-Loop-Prinzip ist essentiell – verlasse dich nie ausschließlich auf automatisierte Ausgaben, sondern nutze dein Fachwissen zur kritischen Bewertung und finalen Qualitätskontrolle.
- **Incident-Meldung**: Bei versehentlicher Eingabe sensibler Daten sofort IT-Security informieren

---

## 💡 Abteilungsspezifische Tipps

### Vertrieb (Sales)
- **Kundenpräsentationen zu Photonik-Lösungen:** Immer Kundennutzen vor rein technischen Details
- **Angebote für optische Systeme:** Technische Specs gegen Coherent-Datasheets und MSA-Standards prüfen
- **Competitive Intelligence:** Faire, faktenbasierte Vergleiche (Devil's Advocate nutzen)
- **ROI-Berechnungen:** Konservative Annahmen für TCO (inkl. Energie, Wartung, Lifecycle), klar dokumentiert

### Marketing
- **Content Creation für Photonik-Themen:** Fachlich korrekt UND für Zielgruppe verständlich (Hyperscaler vs. Telcos vs. Enterprise)
- **Social Media (LinkedIn, YouTube):** Keine unrealistischen Performance-Versprechen
- **Kampagnen:** Diverse Zielgruppen und geografische Märkte berücksichtigen (Nordamerika, EMEA, APAC)
- **SEO für Photonik:** Keywords natürlich einbinden ("800G transceiver", "coherent optics", "VCSEL"), keine Keyword-Stuffing

### Product Management (Networking, Materials, Lasers)
- **User Stories für neue Features:** Aus echter Kundenperspektive formulieren
- **Technische Roadmaps:** Nur realistische Timelines, Risiken transparent machen
- **Release Notes:** Nur tatsächlich umgesetzte Features und Performance-Verbesserungen
- **Wettbewerbsanalysen:** Faktenbasiert, herstellerneutral, mit verifizierten Specs

### Application Engineering / Technical Support
- **Knowledge Base für optische Systeme:** Schritt-für-Schritt, für verschiedene Skill-Level (vom Network Engineer bis zum Datacenter Operator)
- **Troubleshooting-Guides:** Dokumentierte Lösungswege bevorzugen, klare Eskalationskriterien
- **Kundenkommunikation:** Verständlich, präzise Fachbegriffe nutzen aber bei Bedarf erklären
- **Eskalation:** Klare Kriterien, wann Coherent Labs oder R&D einzubinden sind

### R&D / Engineering
- **Spezifikationen für neue Produkte:** Nur verifizierte Daten, Messverfahren dokumentieren
- **Marktanalysen für Technologie-Trends:** Diverse Quellen (LightCounting, Yole, IEEE), regionale Besonderheiten
- **Testdokumentation:** Reproduzierbare Testszenarien, Umgebungsbedingungen protokollieren
- **Publikationen:** Peer-Review-Standards einhalten, keine voreiligen Performance-Claims



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

## 🚀 Nächste Schritte für Sie

**Diese Woche:**
1. Wählen Sie 3 Prompt-Templates aus diesem Tutorial, die zu Ihrer Rolle passen
2. Passen Sie sie an Ihre tägliche Arbeit bei Coherent an
3. Testen Sie diese in realen Szenarien (z.B. Kundenpräsentation, technische Dokumentation)
4. Teilen Sie Ihre Erfahrungen mit Kollegen (gemäß I CARE-Wert "Collaboration")

**Diesen Monat:**
1. Bauen Sie Ihre persönliche Prompt-Bibliothek für Ihren Coherent-Bereich auf
2. Identifizieren Sie einen Prozess, den KI verbessern kann (z.B. Datenblatt-Erstellung, Market Analysis)
3. Geben Sie Feedback zur KI-Nutzung an Ihr Team oder IT
4. Nehmen Sie an einem internen Tech Talk oder Best-Practice-Austausch teil

**Langfristig:**
1. Werden Sie KI-Champion in Ihrer Abteilung (Networking / Materials / Lasers / Sales / Marketing)
2. Teilen Sie Best Practices abteilungsübergreifend (z.B. Sales lernt von Engineering, Marketing von R&D)
3. Entwickeln Sie Coherent-spezifische Use Cases für KI (z.B. automatisierte Competitive Analysis, Predictive Maintenance-Dokumentation)
4. Tragen Sie zur kontinuierlichen Verbesserung der KI-Nutzung bei – im Einklang mit "Innovations That Resonate"

---

**@ HPI - 2025 | KI-Praxisworkshop Tutorials**

