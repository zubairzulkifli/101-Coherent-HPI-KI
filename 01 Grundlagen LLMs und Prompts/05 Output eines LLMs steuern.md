# Tutorial: KI-Ausgaben strukturieren und optimieren

**Von der Rohausgabe zum präzisen Ergebnis in Photonik und Engineering**

---

## Einführung: Was Sie in diesem Tutorial lernen

Dieses Tutorial zeigt Ihnen Schritt für Schritt, wie Sie KI-Ausgaben so steuern, dass sie **strukturiert, wissenschaftlich präzise und sofort einsetzbar** sind – z. B. für technische Spezifikationen, Produktdokumentationen, Kundenpräsentationen, technische Whitepapers oder Engineering-Berichte.

**Nach diesem Tutorial können Sie:**

* KI-Ausgaben klar strukturieren und effizient nachbearbeiten
* Tonalität, Stil und technische Präzision gezielt steuern
* Inhalte für unterschiedliche Zielgruppen (Kunden, Management, Engineering-Teams) optimieren
* Typische Fehler erkennen und beheben
* Ihre Prompt-Effizienz um bis zu **80 %** steigern
* Ausgaben datenschutzkonform und sicherheitsbewusst gestalten

**⏱️ Zeitaufwand:** 30-40 Minuten | **📚 Niveau:** Anfänger | **🎯 Ziel:** Professionelle, strukturierte KI-Ausgaben erstellen

---

## Teil 1: Grundlagen der Ausgabestruktur

### 1.1 Das Struktur-Framework für Photonik-Profis

Jede gute KI-Ausgabe beginnt mit einer klaren Struktur. Diese besteht aus drei Ebenen:

**1. Container** – Hauptabschnitte (z. B. Technischer Hintergrund, Spezifikationen, Anwendungsszenarien)
**2. Komponenten** – Unterelemente (z. B. Optische Eigenschaften, Performance-Metriken, Integration)
**3. Constraints** – Einschränkungen (z. B. Wortanzahl, Stil, Zielgruppe)

#### Beispiel: Produktbeschreibung für 800G-Transceiver

**Version 1 (Basis):**

```
Schreibe über die Vorteile von 800G optischen Transceivern für KI-Rechenzentren.
```

*Ergebnis: Unstrukturierter Fließtext – schwer weiterverwendbar, zu allgemein.*

---

**Version 2 (Mit Container):**

```
Schreibe über 800G-Transceiver für KI-Rechenzentren mit folgenden Abschnitten:
- Executive Summary
- Technische Spezifikationen
- Performance und Effizienz
- Business Value
```

*Ergebnis: Bessere Struktur, aber noch zu allgemein für technische Entscheider.*

---

**Version 3 (Mit Komponenten und Photonik-Fokus):**

```
Erstelle eine strukturierte Produktbeschreibung für 800G-Transceiver im AI-Datacenter-Bereich:

[Executive Summary]
- 3 Hauptargumente für Netzwerk-Architekten und IT-Entscheider
- 1 Satz Zusammenfassung mit messbarem Performance-Nutzen
- Positionierung gegenüber 400G-Lösungen

[Technische Spezifikationen]
- Silizium-Photonik-basierte Architektur mit Marvell® Ara 3 nm DSP
- 8x100G PAM4-Modulation für maximale Bandbreiteneffizienz
- DR8-Interface mit MMF (Multi-Mode Fiber) für kurze Reichweiten
- Power Consumption: <15W typisch (30% effizienter als Generation 1)
- Form-Faktor: QSFP-DD, IEEE 802.3ck konform

[Performance und Effizienz]
- Latenz: <100ns (kritisch für GPU-to-GPU Kommunikation)
- Bit Error Rate (BER): <10^-12 ohne Forward Error Correction
- Temperaturbereich: 0°C bis +70°C (Operating)
- MTBF: >2 Millionen Stunden
- 99,999% Link-Verfügbarkeit in hochdichten AI-Clustern

[Anwendungsszenarien]
- Backend-Konnektivität in NVIDIA DGX SuperPODs
- Spine-Leaf-Architekturen für hyperscale AI-Training
- Storage-Area-Networks mit NVMe-over-Fabrics
- High-Performance Computing Cluster (wissenschaftliche Simulationen)

[Business Value]
- TCO-Optimierung: 40% geringere Kosten/Gbit durch Bandbreitenkonsolidierung
- Zukunftssicherheit: Migration zu 1.6T durch Software-Upgrade möglich
- Energieeffizienz: PUE-Verbesserung von Rechenzentren um 0,05
- Vertikale Integration: Supply-Chain-Stabilität durch Coherent In-House Fertigung
```

*Ergebnis: 75 % bessere Nutzbarkeit, sofort als Basis für technische Präsentationen oder Whitepapers verwendbar.*

---

### 💡 Praxis-Tipp für Coherent-Teams

**Für Vertrieb & Technical Sales:** Verwenden Sie strukturierte Ausgaben als Basis für technische Kundenworkshops. Die klare Gliederung erleichtert die Abstimmung mit Application Engineers und beschleunigt die Angebotserstellung.

**Für Marketing & Communications:** Strukturierte Content-Vorlagen lassen sich schnell in verschiedene Formate überführen (Technical Blog, LinkedIn Thought Leadership, Case Studies, Whitepapers).

**Für Engineering & R&D:** Nutzen Sie das Framework für Design-Dokumentationen, Requirement-Spezifikationen und technische Reports – die Struktur beschleunigt Peer-Reviews.

---

### Übung 1: Struktur entwickeln

**Aufgabe:** Nehmen Sie ein eigenes Thema aus Ihrem Arbeitsbereich (z. B. Laser-Spezifikation, Transceiver-Dokumentation, SiC-Material-Charakterisierung) und entwickeln Sie es in drei Versionen wie oben gezeigt.

**Ziel:** Ihre Nachbearbeitungszeit sinkt von Version 1 zu 3 um mindestens 50 %.

**Beispielthemen:**
- Vertrieb: VCSEL-Array für 3D-Sensing in Automotive ADAS
- Marketing: Landing Page für Co-Packaged Optics (CPO) Lösungen
- Engineering: Design-Spezifikation für Ultrakurzpulslaser (USP)
- Application Engineering: Integration Guide für InP-basierte kohärente Transceiver
- Materials: SiC-Substrat-Charakterisierung für EV-Leistungselektronik

---

## Teil 2: Format-Kontrolle für technische Dokumentation

### 2.1 Die Format-Palette für Photonik-Profis

| Format       | Verwendung                             | Beispiel-Prompt                                                           |
| ------------ | -------------------------------------- | ------------------------------------------------------------------------- |
| **Tabelle**  | Produktvergleiche, Specification Sheets | "Erstelle eine Vergleichstabelle mit Spalten: Parameter, 400G, 800G, 1.6T" |
| **Liste**    | Requirements, Design Checklisten        | "Nummerierte Liste mit max. 8 optischen Parametern, priorisiert nach Performance-Impact"                                    |
| **Template** | Test-Protokolle, Application Notes      | "Verwende Platzhalter in {{geschweiften Klammern}} für variable Messwerte"                       |
| **Markdown** | Engineering Docs, READMEs              | "Formatiere in Markdown mit H2-Überschriften und Formel-Notation"                             |
| **JSON**     | API-Specs, Konfigurationsdateien        | "Ausgabe als JSON-Struktur mit Schema für optische Parameter"                                   |
| **Diagramm-Code** | Systemarchitektur, Optical Layouts | "Erstelle Mermaid-Syntax für Transceiver-Block-Diagramm" |

---

### 2.2 Beispiel: Onboarding-Dokumentation für neue Application Engineers

**Iteration 1 – Einfache Liste:**

```
Liste die wichtigsten Schritte für neue Application Engineers im Networking-Segment auf.
```

**Iteration 2 – Strukturierte Tabelle:**

```
Erstelle eine Onboarding-Tabelle für Application Engineers (Optical Communications):
| Woche | Aufgabe | Verantwortlich | Tools/Systeme | Status |
```

**Iteration 3 – Technische Checkliste mit System-Zugriffen:**

```
Onboarding-Checkliste für neue Application Engineers (Coherent Networking Segment):

## Woche 1: Grundlagen und Labor-Setup
[ ] Zugang zu PLM-System (Produktdatenmanagement) eingerichtet  
[ ] VPN-Zugang und Security-Token (IT-Sicherheit) konfiguriert  
[ ] Labor-Zugriff und ESD-Schulung absolviert  
[ ] Einweisung in optische Messtechnik (OSA, BERT, Power Meter)  
[ ] Knowledge Base durchgearbeitet (Top 20 Transceiver-Specs)

## Woche 2–4: Produktvertiefung und Kundenprojekte
[ ] Shadowing bei erfahrenem AE (min. 2 Kundenmeetings)  
[ ] Erste eigenständige Application Note erstellen (z.B. Link-Budget-Kalkulation)  
[ ] Schulung: Silizium-Photonik Grundlagen (Coherent University)  
[ ] Zugang zu Simulation-Tools (Lumerical, OptiSystem)  
[ ] Teilnahme am wöchentlichen Engineering-Sync und technischem Review

## Woche 5–8: Spezialisierung und Qualifizierung
[ ] Technische Kundenberatung (Level 2) durch Manager freigegeben  
[ ] Vertiefung in spezifische Produktfamilien (z.B. 800G DR8, kohärente 400ZR)  
[ ] Erste Field-Trial-Begleitung bei Hyperscaler-Kunden  
[ ] Beitrag zu Design-Win-Strategie und RFQ-Responses

Format:
- Checkboxen [ ] für Tracking im Confluence
- Zeitrahmen fett markiert  
- Max. 5 Punkte pro Abschnitt (Fokus auf Wesentliches)
- Am Ende jeder Phase: Technisches Gespräch mit Mentor und Manager
- Links zu internen Wikis in {{Platzhaltern}}, z.B. {{WIKI_TRANSCEIVER_BASICS}}
```

**Ergebnis:** Übersichtlicher, kontrollierbarer Prozess – auch als Vorlage für verschiedene Engineering-Disziplinen nutzbar (Lasers, Materials).

---

### 🔒 Sicherheitshinweis: Sensible Daten in Prompts

**Wichtig für alle Coherent-Mitarbeitenden:**

**🔒 Datenschutz & Compliance:**
- Geben Sie KEINE **proprietären Produktdaten**, Patentinformationen oder unveröffentlichte Forschungsergebnisse ein
- Keine **Kundennamen** oder vertrauliche Projektinformationen (z.B. Apple-Partnerschaften, spezifische Hyperscaler-Projekte, Angebotsdetails)
- Keine **Fertigungsprozesse**, Epitaxie-Rezepte, Laser-Cavity-Designs oder technische Spezifikationen mit Wettbewerbsrelevanz
- Keine **Roadmap-Informationen** oder unangekündigte Produktgenerationen (z.B. 3.2T-Transceiver)
- Bei Beispielen immer **anonymisierte oder fiktive Daten** verwenden ("Kunde A", "Hyperscaler X", "Generische 800G-Architektur")

**✅ Qualitätssicherung:**
- Bitte prüfen Sie alle KI-generierten Ergebnisse eigenverantwortlich, bevor Sie sie weitergeben oder veröffentlichen
- Das **Human-in-the-Loop-Prinzip** ist essentiell – verlassen Sie sich nie ausschließlich auf automatisierte Ausgaben
- Nutzen Sie Ihr Fachwissen zur kritischen Bewertung und finalen Qualitätskontrolle
- Bei technischen Spezifikationen: Immer Peer-Review durch erfahrene Kollegen
- Bei Unsicherheit: Rücksprache mit Ihrem Manager, Legal Department oder Corporate Communications

---

## Teil 3: Stil und Tonalität für technisch-wissenschaftliche Kommunikation steuern

### 3.1 Das Stil-Spektrum für Photonik-Leader

```
Stil-Parameter für Coherent-Dokumentation:
- Formalität: [wissenschaftlich-präzise | business-technisch | kundenorientiert-beratend]
- Komplexität: [executive summary | standard engineering | deep-dive research]
- Perspektive: [wir/Coherent | Sie/Kunde | neutral-technisch]
- Detailgrad: [C-Level Overview | System Architect | Component Engineer]
- Tonalität: [sachlich-faktenbasiert | lösungsorientiert | innovativ-visionär]
```

**Coherent Brand Voice Prinzipien:**
- **Wissenschaftlich**: Technisch fundiert, präzise Terminologie, messbare Fakten
- **Innovativ**: Zukunftsweisend, technologieführend, transformativ
- **Vertrauenswürdig**: Substanziell, erfahren, verlässlich (50+ Jahre Photonik-Expertise)
- **Zugänglich**: Klar verständlich, ohne unnötigen Jargon, kundenorientiert

---

### 3.2 Zielgruppenprofile für Coherent

**Beispiel A: Technische Dokumentation (Engineering-Teams)**

```
ZIELGRUPPE:
- Empfänger: Optical Engineers, System Architects, R&D Scientists, Product Managers
- Fokus: Technische Präzision, Reproduzierbarkeit, wissenschaftliche Korrektheit

STIL:
- Tonalität: Wissenschaftlich präzise, objektiv, faktenbasiert, peer-reviewed
- Länge: 500-800 Wörter (je nach Komplexität der Photonik-Systeme)
- Struktur: Prinzip → Design → Charakterisierung → Performance-Validierung
- Format: Markdown mit Formeln (LaTeX), Messdaten, Diagrammen

TABUS:
- Keine Marketing-Superlative oder ungenauen Behauptungen
- Keine vereinfachten oder falschen physikalischen Beschreibungen
- Keine Vermischung von Anforderungen (Requirements) und Implementierung (Design)
- Keine veralteten technischen Standards oder Normen

MUST-HAVES:
- Spezifikationsnummern, relevante IEEE/IEC-Standards (z.B. IEEE 802.3ck)
- Konkrete Messwerte mit Einheiten und Toleranzen (z.B. "BER < 10^-12")
- Verlinkung zu Application Notes, Datasheets, White Papers
- Kohärente Terminologie (z.B. "kohärente Optik" vs. "direct detection")
```

---

**Beispiel B: Kundenpräsentation (Technical Sales / Business Development)**

```
ZIELGRUPPE:
- Netzwerk-Architekten, IT-Entscheider, Datacenter-Betreiber bei Hyperscalern
- Fokus: Business Value, TCO, technologische Differenzierung, Roadmap-Alignment

STIL:
- Tonalität: Beratend, lösungsorientiert, technisch fundiert, vertrauenswürdig
- Länge: 600-800 Wörter (präsentationsgeeignet)
- Struktur: Herausforderung → Coherent-Lösung → Technische Vorteile → Business Impact → Next Steps
- Format: Executive-taugliche Slides mit Key Takeaways

TABUS:
- Keine Übertreibungen oder aggressive Wettbewerbsvergleiche
- Keine unrealistischen Performance-Versprechungen
- Keine vertraulichen Kundenreferenzen ohne Freigabe
- Keine technischen Details ohne Business-Kontext

MUST-HAVES:
- Messbare Business-Metriken (TCO-Reduktion, Power Efficiency, Skalierbarkeit)
- Referenz auf Coherent's vertikale Integration als Differentiator
- Alignment mit Kunden-Roadmap (z.B. NVIDIA GPU-Generationen, Cloud-Provider-Standards)
- Call-to-Action: Design-Win-Support, Field Trial, Executive Briefing
```

---

**Beispiel C: Thought Leadership (Corporate Communications / Marketing)**

```
ZIELGRUPPE:
- Branchenmedien, Konferenz-Teilnehmer, Investoren, Analyst Community
- Fokus: Markttrends, technologische Vision, Coherent als Innovationsführer

STIL:
- Tonalität: Visionär, aber substanziell; autoritativ, ohne arrogant zu wirken
- Länge: 800-1200 Wörter (LinkedIn-Artikel, Blog, Press Release)
- Struktur: Trend → Herausforderung → Innovation → Impact → Coherent's Rolle
- Format: Narrative mit Daten, Experten-Zitaten, zukunftsweisenden Insights

TABUS:
- Keine hohlen Marketing-Phrasen ("revolutionär", "game-changing") ohne Substanz
- Keine Überfokussierung auf Produkte (Thought Leadership, nicht Produktwerbung)
- Keine defensiven oder negativen Aussagen über Wettbewerber
- Keine Spekulation über unangekündigte Produkte

MUST-HAVES:
- Coherent-Tagline einbinden: "Innovations That Resonate"
- Bezug auf globale Megatrends (KI-Skalierung, Cloud-Evolution, Energieeffizienz)
- Zitate von Coherent-Executives (CEO Jim Anderson, CTO Dr. Julie Sheridan Eng)
- Quantitative Marktdaten (z.B. "65 Milliarden USD Total Addressable Market")
- Abschluss mit kundenorientierter Perspektive (Empowerment, Partnership)
```

---

### 💡 Coherent Tonalität: Wissenschaftliche Metaphern nutzen

Coherent nutzt Metaphern aus der Photonik und Wissenschaft, um komplexe Ideen zugänglich zu machen:

✅ **"Bringing light to data"** – für optische Kommunikation
✅ **"From materials to systems"** – für vertikale Integration
✅ **"Coherence in innovation"** – für harmonische Technologieentwicklung
✅ **"Resonating with customers"** – für Kundenorientierung (Tagline-Alignment)
✅ **"The photon is the fundamental building block"** – für Grundlagentechnologie
✅ **"Enabling the next evolution"** – für transformative Wirkung

**Vermeiden Sie:**
❌ "Disruptive game-changer" (zu abgenutzt)
❌ "Best-in-class solution" (zu generisch)
❌ "Cutting-edge breakthrough" (Übertreibung ohne Substanz)

---

## Teil 4: Abteilungsspezifische Prompt-Vorlagen

### Engineering & Technik: Laser-Spezifikation dokumentieren

```
Dokumentiere die technischen Spezifikationen eines Ultrakurzpulslasers (USP) für die Halbleiter-Materialbearbeitung:

FORMAT: Markdown mit Abschnitten und Formeln

[Laser Overview]
- Lasertyp: Mode-locked Nd:YAG mit SESAM (Semiconductor Saturable Absorber Mirror)
- Wellenlänge: 1064 nm (fundamental), 532 nm (SHG), 355 nm (THG optional)
- Anwendungsbereich: BEOL-Prozesse (Back-End-of-Line), Advanced Packaging, Via-Drilling

[Key Performance Parameters]
- Pulsdauer: <10 ps (typisch 8 ps FWHM)
- Repetitionsrate: 50 kHz – 500 kHz (variabel)
- Pulsenergie: 100 µJ @ 100 kHz
- Durchschnittliche Leistung: 10 W @ 100 kHz
- Strahlqualität: M² < 1.3 (near-diffraction-limited)
- Leistungsstabilität: <2% RMS (über 8 Stunden)

[Optical Specifications]
- Strahldurchmesser: 2 mm (1/e²) am Ausgang
- Divergenz: <2 mrad
- Polarisation: Linear, >100:1 Extinktionsverhältnis
- Beam Pointing Stability: <50 µrad

[Applications in Semiconductor Manufacturing]
1. Via-Drilling in Redistribution Layers (RDL) für Advanced Packaging
2. Dice-Before-Grind (DBG) für ultradünne Wafer (<50 µm)
3. Selective Laser Ablation für 3D-IC-Packaging
4. Trim-Prozesse für HBM (High Bandwidth Memory)

[System Integration]
- Schnittstellen: RS-232, Ethernet (Modbus TCP), Digital I/O
- Kühlung: Closed-Loop Wasserkühlung, 1.5 kW Wärmeabfuhr
- Betriebstemperatur: 18–25°C (±0.5°C für stabile Performance)
- Footprint: 600 mm × 400 mm × 200 mm (Laser Head)

[Safety & Compliance]
- Laserklasse: 4 gemäß IEC 60825-1:2014
- CE-Zertifizierung, FDA-konform (Class IV Laser Product)
- Erforderliche Sicherheitsmaßnahmen: Interlock-System, Beam Dump, Schutzgehäuse

STIL: Wissenschaftlich präzise, für Prozessingenieure und Equipment-Hersteller
ZIELGRUPPE: Semiconductor Fabs, OEMs für Laser-Systeme
LÄNGE: 600-800 Wörter
```

---

### Vertrieb & Technical Sales: Kundenvorschlag erstellen

```
Erstelle einen technischen Vorschlag für die Integration von 800G-DR8-Transceivern in ein bestehendes Hyperscale-Rechenzentrum:

KUNDE: Hyperscaler X (anonymisiert), AI-Training-Cluster-Erweiterung
HERAUSFORDERUNG: Bandbreite-Engpass zwischen GPU-Servern (NVIDIA DGX H100), Migration von 400G auf 800G

STRUKTUR:
[Executive Summary] (max. 150 Wörter)
- Business Value in einem Satz: "Verdopplung der KI-Training-Throughput bei 40% TCO-Reduktion"
- Hauptvorteile gegenüber 400G (3 Punkte): Bandbreite, Energieeffizienz, Zukunftssicherheit
- Empfohlene Lösung: Coherent 800G-DR8 mit Silizium-Photonik

[Technical Solution] (300-400 Wörter)
- Architektur: Spine-Leaf-Topologie mit 800G Uplinks (Clos-Netzwerk)
- Transceiver-Spezifikation: QSFP-DD, 8×100G PAM4, MMF (OM4/OM5), <100 m Reichweite
- Performance: <100 ns Latenz, 99.999% Link Availability, BER <10^-12
- Integration: Kompatibel mit Arista 7800R3, Cisco Nexus 9000, Broadcom Tomahawk 4
- Thermal Management: <15W pro Port, passive Kühlung im vorhandenen Switch-Design

[Business Case] (200 Wörter)
- TCO-Vergleich über 5 Jahre:
  * 400G: 2× Ports notwendig → höhere Switch-Kosten, doppelter Platzbedarf
  * 800G: Konsolidierung auf die Hälfte der Ports → 35% CAPEX-Einsparung
  * OPEX: 30% geringere Energie-Kosten durch verbesserte Watt/Gbit-Effizienz
- Skalierbarkeit: Software-Upgrade auf 1.6T möglich (2026 Roadmap-Alignment)
- Supply Chain: Coherent's vertikale Integration garantiert Liefersicherheit (InP-Fertigung in Sherman, TX)

[Implementation Roadmap] (150 Wörter)
- Phase 1 (Q2 2025): Proof-of-Concept in Test-Pod (32× 800G Links)
- Phase 2 (Q3 2025): Rollout in Production-Cluster (500+ Links)
- Phase 3 (Q4 2025): Full Migration (2000+ Links)
- Support: Dedicated Coherent FAE (Field Application Engineer) während Deployment

[Next Steps] (50 Wörter)
- Technical Deep-Dive Workshop bei Kunde (2 Tage, mit Coherent CTO-Office)
- Sample-Bereitstellung: 10× Transceiver für internen Qualifikationstest
- NDA-geschützter Zugang zu Coherent Roadmap (1.6T, CPO-Technologie)

STIL: Beratend, technisch fundiert, Business-Value-orientiert
TONALITÄT: Professionell, vertrauenswürdig, ohne Overselling
VERMEIDEN: Aggressive Wettbewerbsvergleiche, spekulative Roadmap-Aussagen
LÄNGE: Max. 2 A4-Seiten (ca. 900 Wörter)
```

---

### Marketing & Communications: Thought Leadership Artikel

```
Erstelle einen Thought Leadership Artikel über "Die Rolle von Silizium-Photonik in der KI-Ära":

ZIELGRUPPE: C-Level bei Cloud Service Providers, Netzwerk-Architekten, Tech-Medien (z.B. EE Times, Lightwave)
ZIEL: Coherent als Innovationsführer in optischer Kommunikation positionieren
LÄNGE: 1000-1200 Wörter

STRUKTUR:
[Hook] (100 Wörter)
- Aktuelle Herausforderung: Exponentielles Datenwachstum durch KI-Training (ChatGPT, Gemini, etc.)
- Statistik: "KI-Workloads verdoppeln alle 6 Monate – Netzwerke müssen Schritt halten"
- These: "Silizium-Photonik ist der Schlüssel zur Skalierung der KI-Infrastruktur"

[Was ist Silizium-Photonik?] (200 Wörter)
- Technische Erklärung (zugänglich): Integration optischer Komponenten auf Silizium-Chips
- Kernvorteil: Skalierbare Fertigung in etablierten CMOS-Fabs (ähnlich zu CPU-Produktion)
- Historischer Kontext: Entwicklung von 100G (2010) zu 800G (2024) zu 1.6T (2025+)
- Kohärente Optik vs. Direct Detection: Wann welche Technologie?

[Warum Silizium-Photonik für KI-Rechenzentren entscheidend ist] (300 Wörter)
- Herausforderung 1: GPU-Interconnects (NVIDIA NVLink, AMD Infinity Fabric) brauchen ultra-low-latency Optik
- Herausforderung 2: Energieeffizienz (Power Usage Effectiveness, PUE) – jedes Watt zählt
- Herausforderung 3: Kosten pro Gbit müssen sinken (Moore's Law für Photonik)
- Kohärente SiPho-Lösungen: 3 konkrete Beispiele
  * 800G-DR8 für Backend-Konnektivität
  * Kohärente 400ZR für Datacenter Interconnect (DCI)
  * Co-Packaged Optics (CPO): Optik direkt am Switch-ASIC

[Innovation-Spotlight: Coherent's vertikale Integration] (250 Wörter)
- Warum Kohärenz als Material-to-Systems-Leader einzigartig positioniert ist:
  * Eigene InP-Wafer-Fertigung (Sherman, TX) – weltweit erste 150-mm-Linie
  * Silizium-Photonik-Design und -Fertigung (Partnerschaft mit Globalfoundries)
  * VCSEL-Arrays (Sherman, TX) für Short-Reach-Datacom
  * Komplette Transceiver-Assembly (Penang, Malaysia)
- Supply-Chain-Resilienz: Unabhängigkeit von externen Bottlenecks
- Fallstudie (anonymisiert): "Hyperscaler-Kunde reduziert Time-to-Market um 6 Monate durch Coherent Co-Design"

[Ausblick: Die nächste Dekade der optischen Kommunikation] (200 Wörter)
- Technologie-Roadmap: 1.6T (2025), 3.2T (2027+), Co-Packaged Optics (2026-2028)
- Vision: "Photonen ersetzen Elektronen überall, wo Geschwindigkeit zählt"
- Coherent's Rolle: "Empowering market innovators to define the future" (Tagline-Integration)
- Nachhaltigkeit: Geringere CO2-Emissionen durch effizientere Rechenzentren
- Demokratisierung: KI-Infrastruktur wird zugänglicher durch sinkende Kosten

[Call-to-Action] (50 Wörter)
- Einladung: "Entdecken Sie, wie Coherent's Innovations That Resonate Ihre Netzwerk-Architektur transformieren können"
- Link zu Technical Resources: {{LINK_TO_800G_WHITEPAPER}}
- Kontakt: "Sprechen Sie mit unseren Application Engineers über Design-Win-Support"

STIL: Visionär, aber substanziell; wissenschaftlich fundiert, ohne akademisch zu wirken
COHERENT-WERTE: Innovation, Vertrauenswürdigkeit, Kundenorientierung
TONE: Autoritativ, aber nicht arrogant; inspirierend, aber realistisch
SEO-KEYWORDS: "Silizium-Photonik", "KI-Rechenzentren", "800G-Transceiver", "Optische Kommunikation"
ZITAT-VORSCHLAG: Dr. Julie Sheridan Eng (CTO): "Die Konvergenz von Silizium-Photonik und KI definiert die nächste Ära der Cloud-Infrastruktur neu."
```

---

### HR & Administration: Stellenbeschreibung erstellen

```
Erstelle eine Stellenbeschreibung für "Senior Optical Communications Engineer" im Networking-Segment:

POSITION: Senior Optical Communications Engineer (m/w/d)
STANDORT: Ipoh, Malaysia (Transceiver-Fertigung) oder Penang, Malaysia (R&D Center)
REPORTING: Manager, Product Engineering (Networking)

STRUKTUR:
[Unternehmensprofil] (100 Wörter)
- Coherent Corp. als globaler Photonik-Leader (kurz, inspirierend)
- Tagline: "Innovations That Resonate"
- Networking-Segment: Fokus auf 800G/1.6T-Transceiver für AI-Datacenter und Hyperscaler
- 28.000+ Mitarbeitende weltweit, 130+ Standorte, NYSE: COHR

[Ihre Rolle] (150 Wörter)
- Entwicklung und Qualifizierung von optischen Transceivern (QSFP-DD, OSFP) für Datacom-Anwendungen
- Design-for-Manufacturing (DFM): Zusammenarbeit mit Fertigungs-Teams in Ipoh
- Kunden-Support: Technische Beratung für Design-Wins bei Hyperscalern und OEMs
- Performance-Optimierung: Link-Budget-Analysen, BER-Tests, Thermal-Simulationen
- Cross-funktionale Kollaboration: R&D (Penang), Product Management (USA), Sales (global)

[Ihre Qualifikationen] (200 Wörter)
MUST-HAVE:
- M.Sc. oder Ph.D. in Elektrotechnik, Physik, Photonik oder verwandtem Fachgebiet
- 5+ Jahre Erfahrung in optischer Kommunikation (Transceiver, Photonik-Systeme)
- Tiefes Verständnis von PAM4-Modulation, DSP-basierter Signalverarbeitung, Kohärenter Optik
- Erfahrung mit IEEE-Standards (802.3bs, 802.3ck) und MSA-Spezifikationen (400G-DR4, 800G-DR8)
- Hands-on-Erfahrung mit Messtechnik: OSA, BERT, Sampling-Oszilloskop, Power Meter
- Programmierkenntnisse: Python, MATLAB (für Datenanalyse und Automatisierung)

NICE-TO-HAVE:
- Erfahrung mit Silizium-Photonik-Design oder VCSEL-Charakterisierung
- Kenntnisse in Lumerical (FDTD-Simulationen) oder OptiSystem (Link-Simulationen)
- Kundenprojekt-Erfahrung bei Cloud Service Providers oder Netzwerk-OEMs
- Publikationen in IEEE Photonics / OFC-Konferenz-Beiträge
- Fließende Englischkenntnisse (Arbeitssprache), Mandarin oder Bahasa Malaysia von Vorteil

[Was wir bieten] (150 Wörter)
- **Innovation**: Arbeit an cutting-edge 800G/1.6T-Technologien, die KI-Infrastruktur enablen
- **Impact**: Direkte Zusammenarbeit mit führenden Hyperscalern (anonymisiert: Cloud-Hyperscaler, Tech-Giganten)
- **Entwicklung**: Coherent University (interne Weiterbildung), Konferenz-Teilnahmen (OFC, ECOC)
- **Kultur**: I CARE-Werte (Integrity, Collaboration, Accountability, Respect, Enthusiasm)
- **Benefits**: Wettbewerbsfähiges Gehalt, Leistungsboni, umfassende Krankenversicherung, Altersvorsorge
- **Work-Life-Balance**: Flexible Arbeitszeiten, Hybrid-Modell (nach Absprache)
- **Relocation Support**: Falls zutreffend (Umzugskosten, Visa-Unterstützung)

[Bewerbungsprozess] (50 Wörter)
1. Online-Bewerbung über Coherent Careers Portal: {{LINK}}
2. Telefon-Screening mit HR (30 Min.)
3. Technisches Interview mit Hiring Manager (1 Std.)
4. Panel-Interview mit Engineering-Team (2 Std.)
5. Angebot und Onboarding

STIL: Professionell, einladend, technisch präzise (ohne abschreckend zu wirken)
TONALITÄT: Begeisternd, aber realistisch; Kohärenz zwischen Job-Anforderungen und Benefits
VERMEIDEN: Generische HR-Phrasen ("dynamic environment", "fast-paced"), hohle Versprechungen
LÄNGE: Max. 1 A4-Seite (ca. 650 Wörter)
```

---

## Teil 5: Praxisbeispiele – Coherent-spezifische Personas (mit 20-Wörter-Methode)

Die folgenden Beispiele zeigen, wie Sie KI-Assistenten durch präzise Persona-Definition optimal für Ihre spezifischen Aufgaben bei Coherent einsetzen können.

### 1. Photonics Application Engineer für Transceiver-Entwicklung

```markdown
Ich möchte, dass du als erfahrener Photonics Application Engineer mit 8+ Jahren Expertise in optischen Transceivern (PAM4, kohärente Optik) arbeitest, der für Coherent's Networking-Segment technische Kundenberatung leistet und Design-Wins bei Hyperscalern (z.B. Microsoft Azure, Google Cloud) unterstützt. Dein Fokus liegt auf Link-Budget-Analysen, BER-Optimierung und Integration von 800G/1.6T-Transceivern in komplexe Datacenter-Architekturen. Du kommunizierst technisch präzise, nutzt IEEE-Standards (802.3ck) als Referenz und erstellst Application Notes mit messbaren Performance-Daten.
```

**Anwendungsfall:** Erstellung technischer Whitepapers, Kunden-Präsentationen, Design-in-Support-Dokumentationen, RFQ-Responses

---

### 2. Technical Marketing Manager für Laser-Produkte

```markdown
Ich möchte, dass du als Technical Marketing Manager für Coherent's Lasers-Segment arbeitest, der komplexe Lasertechnologien (Ultrakurzpulslaser, Faserlaser, CO2-Laser) in überzeugende Customer-Value-Stories übersetzt. Du hast Erfahrung in B2B-Marketing für industrielle Anwendungen (Halbleiter-Fertigung, Materialbearbeitung, 3D-Sensing) und verstehst sowohl die technischen Grundlagen als auch Business-Metriken wie TCO und ROI. Dein Schreibstil ist technisch fundiert, aber zugänglich für Entscheider, und du integrierst Coherent's Brand Voice ("Innovations That Resonate") natürlich in deine Inhalte.
```

**Anwendungsfall:** Produktbroschüren, Case Studies, Landing Pages, LinkedIn Thought Leadership, Konferenz-Abstracts

---

### 3. HR Business Partner für Engineering-Recruiting

```markdown
Ich möchte, dass du als HR Business Partner mit Spezialisierung auf Engineering-Recruiting im Photonik-Sektor arbeitest. Du verstehst die technischen Anforderungen für Rollen wie "Optical Engineer", "Materials Scientist" oder "Laser Systems Architect" und kannst attraktive, präzise Stellenbeschreibungen erstellen, die sowohl technische Expertise als auch Coherent's I CARE-Kultur widerspiegeln. Du kennst die Herausforderungen beim Recruiting in High-Tech-Märkten (z.B. Fachkräftemangel in Photonik, globale Talentsuche) und formulierst Jobanzeigen, die qualifizierte Kandidaten ansprechen, ohne generische HR-Phrasen zu verwenden.
```

**Anwendungsfall:** Stellenanzeigen, Candidate-Briefings, Onboarding-Materialien, Employer-Branding-Content

---

### 4. Materials Science Engineer für SiC-Entwicklung

```markdown
Ich möchte, dass du als Materials Science Engineer mit Fokus auf Siliziumkarbid (SiC) für Coherent's Materials-Segment arbeitest. Du hast fundierte Kenntnisse in SiC-Epitaxie, Kristallzüchtung und Charakterisierungsmethoden (XRD, Hall-Messungen, SIMS) und entwickelst SiC-Substrate für Leistungselektronik in Elektrofahrzeugen. Dein Schreibstil ist wissenschaftlich präzise, nutzt SI-Einheiten korrekt und basiert auf publizierten Forschungsergebnissen. Du vermeidest Spekulationen und unterscheidest klar zwischen experimentellen Daten und theoretischen Vorhersagen.
```

**Anwendungsfall:** Forschungsberichte, Technical Papers, Kunden-Spezifikationen, Patent-Entwürfe

---

### 5. Sales Operations Analyst für Vertriebsunterstützung

```markdown
Ich möchte, dass du als Sales Operations Analyst arbeitest, der das Vertriebsteam von Coherent's Networking-Segment mit datengetriebenen Insights unterstützt. Du analysierst CRM-Daten (Salesforce), erstellst Sales-Forecasts, identifizierst Pipeline-Bottlenecks und entwickelst Dashboards für regionale Account Manager. Du verstehst die Vertriebszyklen im Photonik-B2B-Geschäft (lange Qualifikationsphasen, Design-Win-Prozesse) und kommunizierst Erkenntnisse klar und actionable. Dein Fokus liegt auf Effizienzsteigerung und Revenue-Optimierung, nicht auf technischen Produktdetails.
```

**Anwendungsfall:** Sales-Reports, Territory-Analysen, Pricing-Modelle, Vertriebspräsentationen für Management

---

### 6. Customer Success Manager für Strategic Accounts

```markdown
Ich möchte, dass du als Customer Success Manager für strategische Hyperscaler-Kunden (z.B. AWS, Meta, Alibaba Cloud) bei Coherent arbeitest. Du bist die Schnittstelle zwischen Kunde, Technical Sales und Engineering, verstehst die Roadmaps der Kunden (z.B. NVIDIA GPU-Generationen, Cloud-Provider-Strategien) und antizipierst deren Bedarf an optischen Lösungen. Dein Schreibstil ist kundenorientiert, lösungsfokussiert und diplomatisch, da du komplexe Multi-Stakeholder-Beziehungen managst. Du erstellst Executive Summaries, Quarterly Business Reviews (QBRs) und Eskalations-Management-Dokumente, die sowohl technische Fakten als auch Business-Impact kommunizieren.
```

**Anwendungsfall:** QBR-Präsentationen, Customer-Health-Scorecards, Eskalations-Reports, Roadmap-Alignment-Dokumente

---

### 7. IT Support Specialist für interne Systeme

```markdown
Ich möchte, dass du als IT Support Specialist arbeitest, der Coherent-Mitarbeitende bei technischen Problemen (VPN-Zugang, PLM-System, Collaboration-Tools wie Teams) unterstützt. Du erstellst Troubleshooting-Guides, Self-Service-FAQs und Schritt-für-Schritt-Anleitungen für nicht-technische User. Dein Schreibstil ist klar, geduldig und vermeidet IT-Jargon, wo immer möglich. Du verstehst die Bedeutung von Datenschutz (keine Screenshots mit sensiblen Daten) und erstellst Dokumentationen, die sowohl für Office-Mitarbeitende als auch für Remote-Teams in globalen Zeitzonen funktionieren.
```

**Anwendungsfall:** Knowledge-Base-Artikel, IT-Ticket-Responses, Onboarding-IT-Guides, Incident-Kommunikation

---

### 8. Executive Assistant für C-Level Support

```markdown
Ich möchte, dass du als Executive Assistant für das Senior Leadership Team (CEO, CTO, CMO) von Coherent arbeitest. Du koordinierst komplexe Termine, bereitest Briefing-Materialien für Board-Meetings vor und erstellst strukturierte Executive Summaries aus umfangreichen technischen Reports. Dein Schreibstil ist professionell, prägnant und diskret. Du verstehst die Bedeutung von Vertraulichkeit (z.B. M&A-Diskussionen, strategische Partnerschaften) und filterst Informationen so, dass Executives in 2-3 Minuten die wesentlichen Entscheidungsgrundlagen erfassen können.
```

**Anwendungsfall:** Meeting-Agendas, Executive Briefs, Board-Präsentationen, interne Kommunikation

---

## Zusammenfassung: Ihr Workflow für strukturierte KI-Ausgaben bei Coherent

### Phase 1: Vorbereitung (2 Minuten)
1. Zielgruppe definieren (Engineering-Team, Kunde, Management?)
2. Zweck klären (Design-Dokumentation, Kundenpräsentation, Marketing-Content?)
3. Format festlegen (Markdown, Tabelle, Slide-Deck?)
4. Länge und Detailgrad bestimmen (Executive Summary vs. Deep-Dive)

### Phase 2: Prompt erstellen (3 Minuten)
1. Container definieren (Hauptabschnitte gemäß Coherent-Standards)
2. Komponenten spezifizieren (Technische Details, Business Value, etc.)
3. Constraints setzen (Stil = wissenschaftlich präzise, Tonalität = vertrauenswürdig)
4. Coherent-Kontext integrieren (Brand Voice, I CARE-Werte, Differenziatoren)

### Phase 3: Ausgabe generieren und prüfen (5 Minuten)
1. Prompt an KI-Assistent senden
2. Ausgabe gegen technische Korrektheit prüfen (Peer-Review bei kritischen Specs)
3. Coherent-Compliance checken (keine sensiblen Daten, korrekte Terminologie)
4. Human-in-the-Loop: Eigenverantwortliche Qualitätskontrolle

### Phase 4: Optimierung (2-5 Minuten)
1. Bei Bedarf: Iteratives Prompting für Feinabstimmung
2. Zielgruppenspezifischer Feinschliff (Executive vs. Engineering Language)
3. Coherent-Werte und Differenziatoren hervorheben ("vertikale Integration", "from materials to systems")
4. Finale Freigabe (bei kundensichtbaren Inhalten: Manager-Review)

**Gesamtzeit: 12-15 Minuten** statt 45-60 Minuten manuelle Erstellung

---

## Ihre nächsten Schritte

### ✅ Sofort umsetzbar:
1. Wählen Sie eine typische Aufgabe aus Ihrem Arbeitsalltag (z.B. Produktspezifikation, Kundenmail, Präsentation)
2. Erstellen Sie einen strukturierten Prompt nach dem Coherent-Framework
3. Testen Sie verschiedene Detaillierungsgrade (Version 1, 2, 3)
4. Dokumentieren Sie: Wie viel Zeit haben Sie gespart? Welche Qualitätsverbesserung haben Sie erzielt?

### 📚 Weiterführende Ressourcen:
- **Confluence**: Coherent KI-Guidelines und Best Practices ({{LINK_TO_WIKI}})
- **Slack/Teams**: KI-Community Channel für Fragen und Erfahrungsaustausch
- **Coherent University**: Vertiefende KI-Workshops und Trainings
- **Corporate Communications**: Freigabe-Prozesse für externe Inhalte

### 🎯 Übungsaufgaben für verschiedene Abteilungen:

**Engineering (Networking, Lasers, Materials):**
- Erstellen Sie eine Technical Specification nach IEEE-Standard
- Entwickeln Sie eine Application Note für ein Kundenintegrationsprojekt
- Dokumentieren Sie einen Design-Review-Report

**Vertrieb & Business Development:**
- Erstellen Sie eine strukturierte Competitive Analysis (Coherent vs. Wettbewerber X)
- Entwickeln Sie ein RFQ-Response-Template für Hyperscaler-Anfragen
- Planen Sie einen technischen Kunden-Workshop (Agenda + Materialien)

**Marketing & Communications:**
- Erstellen Sie einen Thought Leadership Artikel über Photonik-Trends
- Entwickeln Sie Social Media Content für LinkedIn (Professional Tone)
- Planen Sie eine Content-Serie über "KI und optische Kommunikation"

**HR & Administration:**
- Optimieren Sie eine Stellenbeschreibung für Senior-Level-Positionen
- Erstellen Sie einen Onboarding-Guide für neue Mitarbeitende
- Entwickeln Sie ein FAQ-Dokument für interne IT-Services

---

## Tipps für den Alltag bei Coherent

**✅ Best Practices:**
- Nutzen Sie die **Persona-Methode** (siehe Beispiele oben) für konsistente Ergebnisse
- Integrieren Sie **Coherent-Differenziatoren** in Ihre Prompts:
  * "Vertikale Integration von Materials to Systems"
  * "50+ Jahre Photonik-Expertise"
  * "Strategische Partnerschaften mit Apple, DENSO, etc."
  * "I CARE-Werte: Integrity, Collaboration, Accountability, Respect, Enthusiasm"
- Speichern Sie **erfolgreiche Prompts** in einem persönlichen Template-Repository
- Teilen Sie **Best Practices** mit Ihrem Team (Confluence, Slack)
- Nutzen Sie **iteratives Prompting**: Starten Sie einfach, verfeinern Sie schrittweise

**⚠️ Häufige Fehler vermeiden:**
- **Zu vage Prompts**: "Schreibe über Laser" → Spezifizieren Sie Lasertyp, Anwendung, Zielgruppe
- **Fehlende Constraints**: Ohne Stil-Vorgaben kann die KI Marketing-Sprache statt technischer Präzision liefern
- **Sensible Daten**: Niemals echte Kundennamen, Projektcodes oder proprietäre Specs eingeben
- **Blind Copy-Paste**: Immer kritisch prüfen – KI kann technische Fehler machen (z.B. falsche Wellenlängen, Standards)
- **Coherent-Tonalität ignorieren**: Marketing-Superlative passen nicht zu unserer wissenschaftlichen Brand Voice

---



**@ HPI - 2025 | KI-Praxisworkshop Tutorials**


