# 🎯 **JSON Prompting Guide für KI-Bildgenerierung**
## Coherent Corp. – Photonik-Kommunikation für alle Abteilungen

---

## 📘 1. Grundprinzipien

### Was ist JSON-Prompting und warum sollte ich es nutzen?

**JSON-Prompting** ist eine strukturierte Methode, um KI-Bildgeneratoren präzise Anweisungen zu geben. Statt lange, unstrukturierte Sätze zu schreiben, teilst du deine Wünsche in klare, logische Blöcke auf – ähnlich wie eine Checkliste.

**Warum ist das wichtig?**
- Du erhältst **konsistentere und professionellere Ergebnisse**
- Deine Bilder passen besser zur **Coherent Brand Identity** (Neptune Blue, wissenschaftliche Ästhetik)
- Du kannst Vorlagen **wiederverwenden und anpassen** – das spart Zeit
- Die Ergebnisse sind **besser reproduzierbar** für Team-Projekte

**Keine Sorge:** Du musst kein Programmierer sein! JSON ist nur eine strukturierte Art, deine Ideen aufzuschreiben. Wir erklären dir jeden Schritt.

---

### Warum strukturierte Prompts bei Coherent?

Bei Coherent Corp. arbeiten wir mit hochpräziser Photonik-Technologie – unsere Kommunikation sollte diese Präzision widerspiegeln. JSON-Prompts helfen dir dabei, Bilder zu erstellen, die:
- **Wissenschaftlich präzise** wirken (wie kohärentes Licht!)
- **Innovativ und zukunftsorientiert** sind
- **Vertrauenswürdig und professionell** aussehen
- **Für alle verständlich** sind (von HR bis Engineering)

💡 **Wichtig:** Verwende immer **generische Begriffe** wie "KI-Tool" oder "Bildgenerator" statt spezifischer Produktnamen. Achte auf Datenschutz und nutze keine proprietären Coherent-Daten in deinen Prompts!

---

## ⚙️ 2. Grundstruktur eines JSON-Prompts (Schritt für Schritt erklärt)

Ein JSON-Prompt besteht aus **acht Hauptblöcken**. Stell dir vor, du füllst ein Formular aus – jeder Block beschreibt einen anderen Aspekt deines Bildes:

```json
{
  "meta": {},           ← Zweck und Prioritäten (Warum erstellst du dieses Bild?)
  "subject": {},        ← Hauptmotiv (Was/wer ist zu sehen?)
  "style": {},          ← Visueller Stil (Wie soll es aussehen?)
  "technical": {},      ← Kamera-Einstellungen (Wie würde ein Fotograf das Bild machen?)
  "materials": {},      ← Texturen und Oberflächen (Wie fühlt sich das Bild an?)
  "environment": {},    ← Umgebung (Wo spielt das Bild?)
  "composition": {},    ← Bildaufbau (Wie ist das Bild angeordnet?)
  "quality": {}         ← Qualität und Vermeidungen (Was soll rein/nicht rein?)
}
```

### Was bedeuten die einzelnen Blöcke? (Einfach erklärt)

1. **meta**: Der "Briefing-Block" – Was ist der Zweck des Bildes? Für LinkedIn? Für eine Präsentation? Für eine E-Mail?
2. **subject**: Das "Hauptthema" – Zeigst du Menschen? Technologie? Ein Produkt? Eine Szene?
3. **style**: Die "Stimmung" – Soll es modern, wissenschaftlich, warm, futuristisch wirken?
4. **technical**: Die "Kamera-Einstellungen" – Wie scharf? Wie nah? Welche Perspektive?
5. **materials**: Die "Haptik" – Glatte Oberflächen? Mattes Metall? Klares Glas?
6. **environment**: Der "Ort" – Wo findet das Bild statt? Labor? Büro? Produktionshalle?
7. **composition**: Der "Bildaufbau" – Wo ist der Fokus? Wie ist das Bild arrangiert?
8. **quality**: Die "Checkliste" – Was soll auf jeden Fall dabei sein? Was soll vermieden werden?

💡 **Tipp für Anfänger:** Du musst nicht alle Blöcke auf einmal ausfüllen! Starte mit den wichtigsten (subject, style, quality) und experimentiere dann weiter.

---

## 🎯 3. Template #1 – Coherent Teamwork & Networking Solutions

Dieses Template zeigt ein typisches Coherent-Szenario: Ein Team arbeitet an optischen Netzwerklösungen. **Perfekt für:** Marketing-Materialien, LinkedIn-Posts, interne Präsentationen, Website-Content.

### 🇩🇪 Deutsche Version (Empfohlen für Anfänger)

```json
{
  "meta": {
    "prompt_purpose": "Bild für Coherent Networking-Kommunikation (Optical Transceivers, Datacenter Solutions)",
    "priority": ["subject", "style", "composition", "lighting", "environment", "quality"],
    "weights": {
      "subject": 1.0,
      "style": 0.9,
      "composition": 0.85,
      "lighting": 0.8,
      "environment": 0.7,
      "quality": 0.7
    },
    "notes": "Professionelle, technisch versierte Darstellung nach Coherent Corporate Design (Neptune Blue, wissenschaftlich-innovativ)."
  },

  "subject": {
    "what": "Meeting von Coherent-Mitarbeitenden, die an Hochgeschwindigkeits-Transceivern für KI-Rechenzentren arbeiten",
    "participants": ["5–6 Personen, gemischtes Geschlecht und Alter, Photonik-Experten"],
    "actions": ["Diskussion am modernen Arbeitstisch", "zeigen auf optische Komponenten, Netzwerk-Diagramme und Tablets mit Datenvisualisierungen"],
    "expression_mood": "engagiert, wissenschaftlich, innovativ, fokussiert, lösungsorientiert",
    "dress_code": "Business-Casual in Coherent-Farben (Neptune Blue, WeiÃŸ, dezente Grautöne)"
  },

  "style": {
    "primary": "dokumentarisch-realistisch mit wissenschaftlicher Ãsthetik",
    "secondary": ["Tech Editorial", "authentische Photonik-Reportage", "Design-Sprache der Wissenschaft"],
    "mood": ["innovativ", "vertrauenswürdig", "wissenschaftlich exzellent", "zukunftsorientiert", "Innovations That Resonate"],
    "color_palette": ["Neptune Blue (#2E5D9D)", "helles Cyan (#00A3E0)", "WeiÃŸ (#FFFFFF)", "warme neutrale Töne", "Akzent-Dunkelblau (#1F4FA1)"],
    "rendering_quality": ["8k Details", "natürliche Hauttöne", "realistische Kontraste", "professionelle Photonik-Atmosphäre", "kohärentes Licht"]
  },

  "technical": {
    "camera_settings": {
      "lens": "35mm",
      "aperture": "f/4",
      "iso": "200",
      "shutter": "1/125"
    },
    "focus": "Gesichter und Gesten scharf, optische Komponenten erkennbar, Hintergrund leicht weich für Tiefe",
    "lighting_setup": "weiches Tageslicht durch Fenster, dezente Aufhellung, moderne Laborbeleuchtung mit subtilen blauen Akzenten",
    "postprocessing": ["minimale Retusche", "echte Farben mit Neptune Blue Akzenten", "leichte Vignette", "wissenschaftlich-professionell"]
  },

  "materials": {
    "skin_and_faces": "authentische Texturen, natürliche Imperfektionen",
    "fabrics": "Baumwolle, Business-Casual-Stoffe – sichtbar realistische Stoffstruktur",
    "surfaces": "mattes Tischholz oder Metall, optische Komponenten (glänzende Glasfaser-Elemente), moderne Displays",
    "special": "feine Papierstruktur auf technischen Dokumenten, moderne Tablet- und Monitor-Displays mit Netzwerk-Visualisierungen, atomare Struktur-Grafiken im Hintergrund"
  },

  "environment": {
    "location": "moderner Konferenzraum oder Photonics Lab bei Coherent Corp.",
    "background_elements": ["Glaswände", "dezentes Coherent-Logo im Hintergrund", "moderne Photonik-Infrastruktur", "optische Komponenten oder Laser-Visualisierungen im Hintergrund"],
    "lighting_conditions": "Tageslicht mit professioneller, innovativer Grundstimmung (subtile blaue Akzente)",
    "decor": ["moderne Technik", "reduziertes, wissenschaftliches Design", "ergonomische Möbel", "dezente Photonik-Symbolik (atomare Strukturen)"],
    "time_of_day": "später Vormittag"
  },

  "composition": {
    "shot_type": "Halbtotale",
    "perspective": "Augenhöhe mit leichtem Winkel für Tiefe",
    "framing": ["Drittelregel", "harmonische Gruppierung"],
    "subject_placement": "Team in leichter Bogenform um den Tisch mit Sicht auf optische Komponenten und technische Displays",
    "leading_lines": "Tischkanten und Lichtlinien führen zu optischen Transceivern und Netzwerk-Visualisierungen",
    "avoid": ["unruhiger Hintergrund", "überbelichtete Fenster", "angeschnittene Köpfe", "stereotype Tech-Klischees", "veraltete IT-Symbolik"]
  },

  "quality": {
    "include": [
      "authentische Photonik-Teamarbeit",
      "natürliche Beleuchtung",
      "professioneller Coherent-Stil",
      "wissenschaftliche Ausstrahlung",
      "moderne Arbeitsumgebung",
      "Neptune Blue als Leitfarbe"
    ],
    "avoid": [
      "gestellte Posen",
      "überschärfte Haut",
      "künstliche HDR-Effekte",
      "sterile Rechenzentrumsatmosphäre",
      "Hacker-Klischees mit Hoodies",
      "veraltete Laser-Symbolik"
    ],
    "reference": ["Coherent Corporate Design Manual", "moderne Photonik-Kommunikation", "Enterprise Tech-Kampagnen"],
    "safety": "Markenrechte respektieren; KEINE proprietären Coherent-Produktdaten, Patentinformationen oder Kundenspezifikationen; DSGVO-konform; keine sensiblen Fertigungsdaten"
  }
}
```

### 🇬🇧 English Version

```json
{
  "meta": {
    "prompt_purpose": "Corporate image for Coherent Corp. Networking communication (Optical Transceivers, Datacenter Solutions)",
    "priority": ["subject", "style", "composition", "lighting", "environment", "quality"],
    "weights": {
      "subject": 1.0,
      "style": 0.9,
      "composition": 0.85,
      "lighting": 0.8,
      "environment": 0.7,
      "quality": 0.7
    },
    "notes": "Professional and technically proficient depiction in Coherent corporate design style (Neptune Blue, scientifically innovative)."
  },

  "subject": {
    "what": "meeting of Coherent employees working on high-speed transceivers for AI datacenters",
    "participants": ["5–6 photonics professionals of mixed gender and age"],
    "actions": ["discussing around a modern worktable", "pointing at optical components, network diagrams, and tablets with data visualizations"],
    "expression_mood": "engaged, scientific, innovative, focused, solution-oriented",
    "dress_code": "business-casual in Coherent brand colors (Neptune Blue, white, subtle greys)"
  },

  "style": {
    "primary": "documentary photorealism with scientific aesthetics",
    "secondary": ["tech editorial", "authentic photonics reportage", "design language of science"],
    "mood": ["innovative", "trustworthy", "scientifically excellent", "future-focused", "Innovations That Resonate"],
    "color_palette": ["Neptune Blue (#2E5D9D)", "bright cyan (#00A3E0)", "white (#FFFFFF)", "warm neutral tones", "accent dark blue (#1F4FA1)"],
    "rendering_quality": ["8k detail", "natural skin tones", "realistic contrast", "professional photonics atmosphere", "coherent light"]
  },

  "technical": {
    "camera_settings": {
      "lens": "35mm",
      "aperture": "f/4",
      "iso": "200",
      "shutter": "1/125"
    },
    "focus": "faces and gestures sharp, optical components recognizable, background softly defocused for depth",
    "lighting_setup": "soft daylight through windows, balanced fill, modern lab lighting with subtle blue accents",
    "postprocessing": ["minimal retouching", "true color balance with Neptune Blue accents", "slight vignette", "scientifically professional"]
  },

  "materials": {
    "skin_and_faces": "authentic textures, natural imperfections",
    "fabrics": "cotton, business-casual fabrics with visible structure",
    "surfaces": "matte wooden or metal table, optical components (shiny fiber-optic elements), modern displays",
    "special": "fine paper texture visible on technical documents, modern tablet and monitor displays with network visualizations, atomic structure graphics in background"
  },

  "environment": {
    "location": "modern Coherent Corp. conference room or Photonics Lab",
    "background_elements": ["glass walls", "subtle Coherent logo presence", "modern photonics infrastructure", "optical components or laser visualizations in background"],
    "lighting_conditions": "daylight with professional, innovative tone (subtle blue accents)",
    "decor": ["modern technology", "minimalist scientific design", "ergonomic furniture", "subtle photonics symbolism (atomic structures)"],
    "time_of_day": "late morning"
  },

  "composition": {
    "shot_type": "medium wide shot",
    "perspective": "eye-level with slight angle for depth",
    "framing": ["rule of thirds", "balanced team layout"],
    "subject_placement": "team arranged in gentle arc around table with view of optical components and technical displays",
    "leading_lines": "table edges guide viewer toward optical transceivers and network visualizations",
    "avoid": ["cluttered background", "overexposed windows", "cropped heads", "stereotypical tech clichés", "outdated IT symbolism"]
  },

  "quality": {
    "include": [
      "authentic photonics teamwork",
      "natural lighting",
      "professional Coherent style",
      "scientific presence",
      "modern work environment",
      "Neptune Blue as guiding color"
    ],
    "avoid": [
      "staged poses",
      "oversharpened skin",
      "artificial HDR effects",
      "sterile datacenter atmosphere",
      "hacker clichés with hoodies",
      "outdated laser symbolism"
    ],
    "reference": ["Coherent Corporate Design Manual", "modern photonics communication", "Enterprise Tech campaigns"],
    "safety": "respect brand rights; NO proprietary Coherent product data, patent information, or customer specifications; GDPR-compliant; no sensitive manufacturing data"
  }
}
```

---

## 🎯 4. Template #2 – Coherent Materials Division (SiC & Advanced Packaging)

Dieses Template zeigt die **Materials-Abteilung** bei der Arbeit mit Siliziumkarbid (SiC) für Elektrofahrzeuge und Halbleiterproduktion. **Perfekt für:** Technische Präsentationen, LinkedIn-Posts, Recruiting-Materialien.

### 🇩🇪 Deutsche Version (Vereinfacht für Anfänger)

```json
{
  "meta": {
    "prompt_purpose": "Bild für Coherent Materials-Kommunikation (SiC, Advanced Packaging, Halbleiter)",
    "priority": ["subject", "technical", "materials", "style", "quality"],
    "weights": {
      "subject": 1.0,
      "technical": 0.9,
      "materials": 0.9,
      "style": 0.85,
      "quality": 0.8
    },
    "notes": "Technisch präzise, wissenschaftlich, fokussiert auf Materialien und Halbleiter-Innovation."
  },

  "subject": {
    "what": "Coherent Materials Engineers bei der Arbeit mit SiC-Wafern und Advanced Packaging-Technologien",
    "participants": ["3–4 Personen in Reinraumkleidung, gemischtes Team, konzentriert"],
    "actions": ["Inspektion von SiC-Substraten unter Mikroskop", "Analyse von Wafer-Daten auf Tablets", "Präzisionsmessung mit hochmodernen Instrumenten"],
    "expression_mood": "fokussiert, wissenschaftlich exakt, innovativ, professionell",
    "dress_code": "Reinraumkleidung (weiÃŸ oder hellblau) mit Coherent-Logo, Schutzbrillen"
  },

  "style": {
    "primary": "technisch-dokumentarisch, präzise, wissenschaftlich",
    "secondary": ["High-Tech Fotografie", "Cleanroom Editorial", "Materialwissenschaft-Ãsthetik"],
    "mood": ["präzise", "innovativ", "hochmodern", "vertrauenswürdig", "wissenschaftlich exzellent"],
    "color_palette": ["WeiÃŸ (Reinraum)", "Neptune Blue (Akzente)", "metallisches Silber (SiC)", "Cyan-Highlights", "warme Labor-Beleuchtung"],
    "rendering_quality": ["8k Ultra-Details", "scharfe Texturen", "realistische Materialien", "professionelle Cleanroom-Atmosphäre"]
  },

  "technical": {
    "camera_settings": {
      "lens": "50mm Makro",
      "aperture": "f/2.8",
      "iso": "400",
      "shutter": "1/250"
    },
    "focus": "SiC-Wafer und Hände im Fokus, Hintergrund mit Reinraum-Equipment leicht verschwommen",
    "lighting_setup": "helles, gleichmäÃŸiges Reinraumlicht, subtile blaue LED-Akzente, keine harten Schatten",
    "postprocessing": ["präzise Schärfe", "natürliche Farben mit Neptune Blue Akzenten", "High-Tech-Look", "wissenschaftlich-professionell"]
  },

  "materials": {
    "skin_and_faces": "teilweise verdeckt durch Schutzkleidung, authentische Augen sichtbar",
    "fabrics": "glatte Reinraum-Textilien (antistatisch), sichtbare Struktur",
    "surfaces": "glänzende SiC-Wafer (metallisch-grau), mattes Edelstahl-Equipment, moderne Touch-Displays",
    "special": "kristalline Struktur von SiC sichtbar, feine Details auf Wafern, hochpräzise Instrumente"
  },

  "environment": {
    "location": "Coherent Cleanroom-Facility (Reinraum Klasse 100 oder besser)",
    "background_elements": ["Reinraum-Equipment", "SiC-Produktionsanlagen im Hintergrund", "subtiles Coherent-Logo", "moderne Messgeräte"],
    "lighting_conditions": "helles, steriles Reinraumlicht mit subtilen blauen Akzenten",
    "decor": ["minimalistisch", "hochmodern", "funktional", "wissenschaftlich präzise"],
    "time_of_day": "zeitlos (Reinraum)"
  },

  "composition": {
    "shot_type": "Nahaufnahme bis mittlere Totale",
    "perspective": "leicht von oben (45° Winkel) für Sicht auf Wafer und Hände",
    "framing": ["Goldener Schnitt", "Wafer als Fokuspunkt"],
    "subject_placement": "Hände und Wafer zentral, Team im Hintergrund erkennbar",
    "leading_lines": "Tischkanten und Equipment führen zum Wafer",
    "avoid": ["Unschärfe auf wichtigen Details", "sterile Kälte", "zu dunkel", "Klischee-Laborszenen"]
  },

  "quality": {
    "include": [
      "authentische Reinraum-Arbeit",
      "präzise technische Details",
      "professioneller Coherent-Stil",
      "wissenschaftliche Exzellenz",
      "moderne Materialwissenschaft",
      "Neptune Blue als Akzentfarbe"
    ],
    "avoid": [
      "unscharfe Wafer-Details",
      "übertriebene Sterile",
      "künstliche Effekte",
      "stereotype Labor-Klischees",
      "veraltete Equipment-Darstellung"
    ],
    "reference": ["Coherent Materials Kommunikation", "Halbleiter-Industrie-Standards", "High-Tech-Editorial-Fotografie"],
    "safety": "KEINE proprietären Fertigungsprozesse, Materialzusammensetzungen oder Kundenspezifikationen; DSGVO-konform; keine sensiblen SiC-Produktionsdaten"
  }
}
```

---

## 🎯 5. Template #3 – Coherent Laser Applications (Industrial & Medical)

Dieses Template zeigt **Laser-Anwendungen** in der Industrie oder Medizin. **Perfekt für:** Produktpräsentationen, Case Studies, Website-Content, Fachkommunikation.

### 🇩🇪 Deutsche Version (Vereinfacht)

```json
{
  "meta": {
    "prompt_purpose": "Bild für Coherent Laser-Kommunikation (Industrielle Fertigung, Medizintechnik, Präzisionsbearbeitung)",
    "priority": ["subject", "style", "lighting", "technical", "quality"],
    "weights": {
      "subject": 1.0,
      "style": 0.9,
      "lighting": 0.9,
      "technical": 0.85,
      "quality": 0.8
    },
    "notes": "Dynamisch, präzise, fokussiert auf Laser-Technologie und ihre Anwendungen."
  },

  "subject": {
    "what": "Coherent Laser-System in Aktion (z.B. PrÃ¤zisionsschneiden, SchweiÃŸen oder medizinische Anwendung)",
    "participants": ["1–2 Personen (optional), Fokus auf Laser-Prozess", "oder: kein Mensch, nur Maschine und Material"],
    "actions": ["Laser-Strahl schneidet/schweiÃŸt Material", "Funken und Lichteffekte", "Präzisionsarbeit", "Material-Transformation"],
    "expression_mood": "präzise, kraftvoll, innovativ, hochmodern, kontrolliert",
    "dress_code": "Schutzkleidung (falls Menschen), moderne Arbeitskleidung in neutralen Farben"
  },

  "style": {
    "primary": "dynamisch-technisch, High-Tech, energetisch",
    "secondary": ["Industrial Photography", "Laser Action Shot", "High-Speed-Fotografie"],
    "mood": ["kraftvoll", "präzise", "innovativ", "zukunftsweisend", "wissenschaftlich exzellent"],
    "color_palette": ["intensives Laser-Licht (Blau/Grün/Rot je nach Laser)", "Neptune Blue (Akzente)", "WeiÃŸ (Funken)", "dunkler Hintergrund für Kontrast"],
    "rendering_quality": ["8k Ultra-Details", "scharfe Lichteffekte", "realistische Materialbearbeitung", "dynamische Atmosphäre"]
  },

  "technical": {
    "camera_settings": {
      "lens": "50mm oder 85mm",
      "aperture": "f/2.8 bis f/4",
      "iso": "800",
      "shutter": "1/500 (um Bewegung einzufrieren)"
    },
    "focus": "Laser-Interaktionspunkt scharf, Funken und Material im Fokus, Hintergrund leicht weich",
    "lighting_setup": "Laser als Hauptlichtquelle, dramatische Beleuchtung, minimale Zusatzbeleuchtung für Kontext",
    "postprocessing": ["präzise Schärfe auf Laser-Punkt", "natürliche Farben mit intensiven Laser-Highlights", "dynamische Kontraste", "High-Tech-Look"]
  },

  "materials": {
    "skin_and_faces": "falls sichtbar: authentisch, mit Schutzbrille",
    "fabrics": "Schutzkleidung (falls Menschen), glatte Texturen",
    "surfaces": "Metall (wird bearbeitet), glühende Schnittkanten, Funken, Rauch",
    "special": "Laser-Strahl sichtbar (leichter Nebel), glühende Materialränder, funkelnde Partikel, präzise Schnittkanten"
  },

  "environment": {
    "location": "moderne Fertigungshalle oder medizinisches Labor mit Coherent Laser-System",
    "background_elements": ["Laser-Equipment im Hintergrund", "moderne Maschinen", "subtiles Coherent-Logo", "technische Infrastruktur"],
    "lighting_conditions": "dramatisch, Laser als Hauptlichtquelle, dunkler Hintergrund für Kontrast",
    "decor": ["industriell", "hochmodern", "funktional", "technisch präzise"],
    "time_of_day": "zeitlos (Innenraum)"
  },

  "composition": {
    "shot_type": "Nahaufnahme bis mittlere Totale",
    "perspective": "leicht seitlich oder von oben für beste Sicht auf Laser-Prozess",
    "framing": ["Goldener Schnitt", "Laser-Interaktionspunkt als Fokus"],
    "subject_placement": "Laser-Strahl und Material zentral, Equipment im Hintergrund",
    "leading_lines": "Laser-Strahl führt zum Bearbeitungspunkt, Funken strahlen nach auÃŸen",
    "avoid": ["unscharfe Laser-Details", "überbelichtete Bereiche", "zu dunkler Gesamteindruck", "stereotype Industrie-Klischees"]
  },

  "quality": {
    "include": [
      "authentischer Laser-Prozess",
      "dynamische Lichteffekte",
      "präzise technische Details",
      "professioneller Coherent-Stil",
      "innovative Atmosphäre",
      "Neptune Blue als Akzentfarbe (wo passend)"
    ],
    "avoid": [
      "unscharfe Laser-Strahlen",
      "übertriebene Effekte",
      "unrealistische Funken",
      "stereotype Industrie-Darstellung",
      "veraltete Laser-Symbolik"
    ],
    "reference": ["Coherent Laser-Produktkommunikation", "Industrial High-Tech-Fotografie", "Precision Manufacturing Editorial"],
    "safety": "KEINE proprietären Laser-Spezifikationen, Kundenspezifikationen oder sensiblen Fertigungsprozesse; DSGVO-konform"
  }
}
```

---

## 📝 6. So verwendest du die Templates (Schritt-für-Schritt für Anfänger)

### Schritt 1: Wähle das passende Template
- **Template #1 (Teamwork)**: Für Marketing, HR, allgemeine Kommunikation
- **Template #2 (Materials)**: Für technische Präsentationen, Recruiting in Engineering
- **Template #3 (Laser)**: Für Produktkommunikation, Case Studies, Fachkommunikation

### Schritt 2: Kopiere das Template in deinen KI-Bildgenerator
- Öffne deinen KI-Bildgenerator (z.B. DALL-E, Midjourney, Stable Diffusion)
- Kopiere das **gesamte JSON-Template** (von `{` bis `}`)
- Füge es in das Prompt-Feld ein

### Schritt 3: Passe das Template an deine Bedürfnisse an
- **Ändere "prompt_purpose"**: Was ist dein konkretes Ziel? (z.B. "LinkedIn-Post für Networking-Team")
- **Ändere "participants"**: Wie viele Personen? Welches Team?
- **Ändere "actions"**: Was machen die Personen konkret?
- **Ändere "location"**: Wo spielt die Szene? (z.B. "Coherent Lab in Ipoh, Malaysia")

### Schritt 4: Generiere das Bild
- Klicke auf "Generate" oder "Erstellen"
- Warte auf das Ergebnis (ca. 30-60 Sekunden)

### Schritt 5: Verfeinere das Ergebnis
- **Nicht perfekt?** Ändere einzelne Parameter und generiere erneut
- **Zu dunkel?** Passe "lighting_setup" an
- **Falsche Farben?** Prüfe "color_palette"
- **Nicht der richtige Fokus?** Ändere "subject_placement"

💡 **Tipp:** Speichere erfolgreiche Prompts in einer Datei, damit du sie wiederverwenden kannst!

---

## 🎨 7. Coherent-spezifische Farben und Stil-Elemente (Wichtig!)

### Die Coherent-Farbpalette (Immer verwenden!)

| Farbname | Hex-Code | Verwendung | Beispiel |
|----------|----------|------------|----------|
| **Neptune Blue** | #2E5D9D | Hauptfarbe für Akzente, Logos, Überschriften | Hintergrund-Elemente, Team-Kleidung |
| **Helles Cyan** | #00A3E0 | Sekundärfarbe für Highlights | Lichtakzente, moderne Displays |
| **Akzent-Dunkelblau** | #1F4FA1 | Für Tiefe und Kontrast | Dunklere Hintergründe, Schatten |
| **WeiÃŸ** | #FFFFFF | Reinheit, Präzision, Klarheit | Reinraumkleidung, HintergrÃ¼nde |
| **Dunkelgrau** | #2C2C2C | FlieÃŸtext, subtile Elemente | Textfarbe, dunkle Flächen |

### Coherent-Stil-Elemente (Für authentische Bilder)

1. **Atomare Strukturen**: Kreisförmige, orbital-ähnliche Grafiken im Hintergrund
2. **Geometrische Formen**: Präzise Kreise, Linien, Gitter (wissenschaftliche Genauigkeit)
3. **High-Contrast Graphics**: Starke Kontraste zwischen hell und dunkel
4. **Kohärentes Licht**: Subtile blaue Lichtakzente, die an Laser erinnern

💡 **Tipp:** Füge in dein JSON-Template unter "environment" > "background_elements" immer **"atomare Struktur-Grafiken"** oder **"dezentes Coherent-Logo"** hinzu!

---

## ⚠️ 8. Was du NICHT in deine Prompts schreiben solltest (Sicherheitshinweise)

### 🔒 Datenschutz & Compliance (SEHR WICHTIG!)

**❌ NIEMALS eingeben:**
- Proprietäre Coherent-Produktdaten (z.B. genaue Spezifikationen von Transceivern)
- Patentinformationen oder Forschungsergebnisse
- Kundendaten oder Projektinformationen (z.B. Kundenspezifikationen, Angebotsdaten)
- Fertigungsprozesse, Materialzusammensetzungen oder technische Spezifikationen mit Wettbewerbsrelevanz
- Namen oder Fotos realer Coherent-Mitarbeiter ohne Erlaubnis
- Sensible SiC-Produktionsdaten oder Halbleiter-Designs

**✅ STATTDESSEN verwenden:**
- Generische Begriffe wie "Hochgeschwindigkeits-Transceiver", "SiC-Wafer", "Laser-System"
- Anonymisierte oder fiktive Daten (z.B. "Team arbeitet an optischen Komponenten")
- Allgemeine Beschreibungen (z.B. "moderne Photonik-Infrastruktur")

### ✅ Qualitätssicherung (Human-in-the-Loop-Prinzip)

**Wichtig:** KI-generierte Bilder sind ein **Werkzeug**, kein Ersatz für dein Urteilsvermögen!

**Vor der Veröffentlichung:**
1. ✅ Prüfe, ob das Bild zur Coherent Brand Identity passt (Neptune Blue, wissenschaftlich, professionell)
2. ✅ Lass wichtige Bilder von Kollegen gegenchecken (z.B. Marketing-Team, Fachbereich)
3. ✅ Verifiziere, dass keine sensiblen Informationen sichtbar sind
4. ✅ Teste das Bild in verschiedenen Kontexten (Web, Print, Social Media)

💡 **Tipp:** Bei Unsicherheit lieber einmal mehr nachfragen als ein Bild veröffentlichen, das nicht passt!

---

## 🎯 9. Persona-Beispiele (70% Verwaltung, 30% Engineering)

Hier sind **sechs praxisnahe Persona-Beispiele** aus verschiedenen Abteilungen bei Coherent. Diese zeigen dir, wie unterschiedliche Rollen JSON-Prompts für ihre tägliche Arbeit nutzen können.

---

### 1. HR Business Partner für Employer Branding

```markdown
Ich möchte mit einem Bildgenerator authentische Fotos für unsere Coherent-Karriereseite erstellen. Die Bilder sollen zeigen, wie vielfältig unser Team ist und wie innovativ wir arbeiten. Sie sollen potenzielle Bewerber ansprechen und die Coherent-Kultur widerspiegeln: wissenschaftlich, aber zugänglich. Die Bilder werden auf LinkedIn, unserer Website und in Stellenausschreibungen verwendet. Ich möchte verschiedene Abteilungen zeigen – von Engineering über Marketing bis zu HR selbst. Die Bilder sollten Neptune Blue als Akzentfarbe haben und professionell, aber nicht steril wirken.
```

**Anwendungsfall:** 
- Erstellung von Karriereseiten-Content
- LinkedIn-Posts für Recruiting
- Stellenausschreibungs-Header
- Employer-Branding-Kampagnen
- Diversity & Inclusion Kommunikation

**Welches Template?** Template #1 (Teamwork) – anpassen für verschiedene Abteilungen

---

### 2. Marketing Content Specialist für Social Media

```markdown
Ich möchte mit einem Bildgenerator Eye-Catcher für unsere Social-Media-Kanäle (LinkedIn, Twitter/X, Instagram) erstellen. Die Bilder sollen unsere Coherent-Produkte (z.B. optische Transceiver, Laser-Systeme) in Aktion zeigen oder Teams bei der Arbeit darstellen. Sie müssen zur Coherent Brand Identity passen (Neptune Blue, wissenschaftlich-innovativ) und für verschiedene Formate funktionieren (quadratisch, hochkant). Ich brauche Bilder, die Engagement erzeugen, aber trotzdem professionell und B2B-gerecht sind. Platz für Text-Overlays sollte eingeplant sein.
```

**Anwendungsfall:**
- LinkedIn-Posts (Produktankündigungen, Thought Leadership)
- Instagram Stories (Behind-the-Scenes, Team-Updates)
- Twitter/X Graphics (News, Events)
- Newsletter-Header
- Blog-Artikelbilder

**Welches Template?** Template #1 oder #3, angepasst für Social Media (quadratisches Format, Platz für Text)

---

### 3. Sales Account Manager für Kundenpräsentationen

```markdown
Ich möchte mit einem Bildgenerator professionelle Bilder für meine Kundenpräsentationen erstellen. Die Bilder sollen zeigen, wie Coherent-Lösungen (z.B. Networking-Produkte für Rechenzentren, SiC für E-Mobilität) in der Praxis eingesetzt werden. Sie sollten Vertrauen erwecken und technische Kompetenz ausstrahlen, aber auch für nicht-technische Entscheider verständlich sein. Ich brauche Bilder für PowerPoint-Folien, die zur Coherent-Farbpalette (Neptune Blue) passen und genug Weißraum für Text haben. Die Bilder sollten verschiedene Anwendungsfälle abdecken: Rechenzentren, Automotive, Industriefertigung.
```

**Anwendungsfall:**
- PowerPoint-Präsentationen für Kundenmeetings
- Pitch Decks
- Produktbroschüren
- Case Study Illustrationen
- Solution-Design-Workshops

**Welches Template?** Alle drei Templates, je nach Produkt/Anwendungsfall

---

### 4. Executive Assistant / Operations Coordinator für interne Kommunikation

```markdown
Ich möchte mit einem Bildgenerator Bilder für interne Coherent-Kommunikation erstellen (z.B. Newsletter, Intranet, Management-Präsentationen). Die Bilder sollen verschiedene Bereiche unseres Unternehmens zeigen: Meetings, Teamarbeit, Produktionsstätten, Labore. Sie sollten motivierend wirken und unsere "I CARE"-Werte (Integrity, Collaboration, Accountability, Respect, Enthusiasm) widerspiegeln. Die Bilder müssen zur Coherent Brand Identity passen (Neptune Blue, professionell, wissenschaftlich) und für verschiedene interne Kanäle funktionieren. Ich brauche Bilder, die unsere Mitarbeiter ansprechen und Zusammengehörigkeit vermitteln.
```

**Anwendungsfall:**
- Interne Newsletter
- Intranet-Artikel
- Management-Updates
- Town Hall Präsentationen
- Mitarbeiter-Engagement-Kampagnen

**Welches Template?** Template #1 (Teamwork) – anpassen für verschiedene interne Szenarien

---

### 5. Photonics Application Engineer für technische Dokumentation

```markdown
Ich möchte mit einem Bildgenerator technische Illustrationen für Produktdatenblätter und Anwendungshinweise erstellen. Die Bilder sollen zeigen, wie unsere optischen Transceiver oder Laser-Systeme in realen Anwendungen funktionieren. Sie sollten technisch präzise sein, aber auch für Kunden verständlich. Ich brauche Bilder, die technische Details (z.B. Lichtstrahl, optische Komponenten, Netzwerk-Topologien) klar darstellen und zur Coherent-Ãsthetik passen (Neptune Blue, wissenschaftlich, High-Tech). Die Bilder werden in Datenblättern, Application Notes und technischen Präsentationen verwendet.
```

**Anwendungsfall:**
- Produktdatenblätter
- Application Notes
- Technische Präsentationen für Kunden
- White Papers
- Engineering-Blog-Artikel

**Welches Template?** Template #2 (Materials) oder #3 (Laser) – technischer Fokus

---

### 6. Customer Success Manager für Case Studies

```markdown
Ich möchte mit einem Bildgenerator Bilder für Coherent-Case-Studies erstellen. Die Bilder sollen zeigen, wie unsere Kunden (z.B. Hyperscaler-Rechenzentren, Automobilhersteller, Medizintechnik-Firmen) unsere Technologien erfolgreich einsetzen. Sie sollten professionell, aber nicht zu technisch wirken – auch Nicht-Techniker sollten sie verstehen. Ich brauche Bilder für PDF-Case-Studies, Website-Content und Präsentationen. Die Bilder müssen zur Coherent Brand Identity passen (Neptune Blue, innovativ, vertrauenswürdig) und verschiedene Branchen abdecken. Sie sollten Erfolgsgeschichten visualisieren und Kundenwert zeigen.
```

**Anwendungsfall:**
- Case Study PDFs
- Website-Content (Success Stories)
- Kundenpräsentationen
- Referenz-Materialien
- Solution-Showcase-Events

**Welches Template?** Alle drei Templates, je nach Kundenbranche und Anwendungsfall

---

## 🏢 10. Abteilungsspezifische Anwendungsfälle (Fokus: Verwaltung)

Da **70% unserer Nutzer aus Verwaltungs-Jobs** kommen, hier konkrete Beispiele, wie verschiedene Abteilungen JSON-Prompts nutzen können:

### HR & Talent Acquisition
- **Stellenausschreibungen**: Header-Bilder, die verschiedene Rollen zeigen (Engineer, Marketer, HR)
- **Employer Branding**: Authentische Team-Fotos für Karriereseite und LinkedIn
- **Onboarding-Materialien**: Welcome-Grafiken, Team-Vorstellungen
- **Diversity-Kampagnen**: Bilder, die Vielfalt bei Coherent zeigen

**Tipp:** Nutze Template #1 und variiere "participants" für verschiedene Rollen

---

### Marketing & Communications
- **Social Media**: LinkedIn-Posts, Instagram Stories, Twitter/X Graphics
- **Website-Content**: Hero-Images, Produktseiten, About-Us-Seiten
- **Newsletter**: Header-Bilder, Artikel-Illustrationen
- **Event-Marketing**: Messe-Grafiken, Webinar-Thumbnails
- **Kampagnen**: Launch-Visuals, Thought-Leadership-Content

**Tipp:** Alle Templates nutzbar – passe "composition" für verschiedene Formate an (quadratisch für Social Media, querformat für Website)

---

### Sales & Business Development
- **Kundenpräsentationen**: PowerPoint-Folien, Pitch Decks
- **Produktpräsentationen**: Hero-Images für Produkte, Anwendungsbeispiele
- **Competitive Analysis**: Visuelle Vergleiche (Achtung: keine negativen Darstellungen!)
- **Solution Workshops**: Visualisierung von Kundenszenarien
- **Proposal-Dokumente**: Professionelle Header, Szenario-Bilder

**Tipp:** Template #3 (Laser in Aktion) ist perfekt für Produktpräsentationen

---

### Finance & Controlling
- **Geschäftsberichte**: Professionelle Bilder für Annual Reports, Investor Relations
- **Budget-Präsentationen**: Visuelle Elemente für Finanz-Meetings
- **Stakeholder-Kommunikation**: Vertrauenswürdige, professionelle Bilder

**Tipp:** Nutze Template #1 mit besonders professioneller, seriöser Anmutung

---

### Compliance & Legal
- **Policy-Dokumente**: Header für Richtlinien, Compliance-Guidelines
- **Training-Materialien**: Visuelle Elemente für Compliance-Schulungen
- **Audit-Berichte**: Professionelle Grafiken

**Tipp:** Besonders auf "quality" > "safety" achten – keine sensiblen Daten!

---

### Training & Development
- **E-Learning-Plattformen**: Header-Bilder für Kurse
- **Schulungsmaterialien**: Visuelle Elemente für Präsentationen
- **Webinar-Content**: Thumbnails, Intro-Slides

**Tipp:** Template #1 (Teamwork) zeigt Lernszenarien gut

---

### Executive Assistants / Operations
- **Management-Präsentationen**: Professionelle Folien für CEO/CTO-Updates
- **Interne Kommunikation**: Newsletter, Intranet-Artikel
- **Town Halls**: Visuelle Elemente für All-Hands-Meetings
- **Event-Organisation**: Grafiken für interne Events

**Tipp:** Alle Templates nutzbar – fokussiere auf "professionell" und "vertrauenswürdig"

---

## 💡 11. Praktische Tipps für den Arbeitsalltag (Für Anfänger)

### Für Social Media (LinkedIn, Twitter/X, Instagram)
- ✅ **Quadratisches Format (1:1)** oder **Hochformat (9:16)** mitdenken
- ✅ Füge in "composition" > "framing" hinzu: "Platz für Text-Overlay oben oder unten"
- ✅ **Kompaktere Prompts** für schnellere Iterationen (du brauchst nicht alle 8 Blöcke!)
- ✅ **Emotionale Momente** betonen (Team-Erfolge, Innovation, Zusammenarbeit)
- ✅ Neptune Blue immer als Akzentfarbe

**Beispiel-Anpassung für LinkedIn (quadratisch):**
```json
"composition": {
  "shot_type": "quadratisches Format (1:1)",
  "framing": ["Platz für Text-Overlay im oberen Drittel", "Drittelregel"],
  "subject_placement": "Team zentral, Weißraum oben für Headline"
}
```

---

### Für Print-Materialien (Broschüren, Flyer, Poster)
- ✅ **Hochauflösende Qualität** betonen (8k, 300dpi minimum)
- ✅ **Querformat (16:9 oder 4:3)** bevorzugen
- ✅ **Ruhigere Kompositionen** für bessere Lesbarkeit
- ✅ **Ausreichend Weißraum** für Text und Logos einplanen

**Beispiel-Anpassung für Print:**
```json
"quality": {
  "include": ["8k Ultra-Details", "300dpi druckfähig", "ausreichend Weißraum für Text"],
  "rendering_quality": ["8k Details", "druckfertig", "hochauflösend"]
}
```

---

### Für Präsentationen (PowerPoint, Keynote)
- ✅ **Klare Fokuspunkte** setzen (ein Hauptmotiv, nicht zu überladen)
- ✅ **Genug Weißraum** für Texteinblendungen und Diagramme
- ✅ **Professioneller Look**, aber nicht zu technokratisch
- ✅ **Konsistente Farbpalette** durch alle Slides (Neptune Blue!)

**Beispiel-Anpassung für PowerPoint:**
```json
"composition": {
  "framing": ["Platz für Texteinblendungen rechts oder links", "Weißraum für Diagramme"],
  "subject_placement": "Hauptmotiv linksbündig, Weißraum rechts für Bulletpoints"
}
```

---

### Für Employer Branding & Recruiting
- ✅ **Authentizität vor Perfektion** (keine gestellten Posen!)
- ✅ **Vielfalt der Rollen** zeigen (nicht nur Engineers – auch HR, Marketing, Sales)
- ✅ **Moderne Arbeitsumgebung** realistisch darstellen
- ✅ **Work-Life-Balance** und Coherent-Kultur kommunizieren
- ✅ **Persönlichkeiten** der Mitarbeitenden durchscheinen lassen

**Beispiel-Anpassung für Recruiting:**
```json
"subject": {
  "participants": ["diverse Team aus verschiedenen Abteilungen (Engineering, Marketing, HR)", "gemischtes Geschlecht und Alter"],
  "expression_mood": "authentisch, enthusiastisch, kollegial, lösungsorientiert"
}
```

---

## 🚀 12. Schnellstart-Guide (5 Schritte zum perfekten Coherent-Bild)

### In 5 einfachen Schritten zum professionellen Bild:

1. **Ziel definieren**  
   → Was ist der Zweck? Welcher Kanal? Welche Zielgruppe?  
   *Beispiel: LinkedIn-Post für Networking-Team, Zielgruppe: IT-Entscheider*

2. **Template wählen**  
   → Passendes Beispiel aus diesem Guide auswählen  
   *Beispiel: Template #1 (Teamwork)*

3. **Anpassen**  
   → Spezifische Details ergänzen (Abteilung, Use Case, Kontext)  
   *Beispiel: "participants" ändern zu "Networking-Team bei Coherent", "location" ändern zu "Ipoh Lab, Malaysia"*

4. **Qualitätskontrolle**  
   → Checkliste durchgehen (Farben ✓, Datenschutz ✓, keine sensiblen Daten ✓)

5. **Generieren & Iterieren**  
   → Prompt in KI-Bildgenerator eingeben, Ergebnis prüfen, bei Bedarf anpassen

---

### Beispiel-Workflow (Konkret):

```
Aufgabe: LinkedIn-Post für neues 1.6T-Transceiver-Produkt
↓
Template #1 (IT-Strategiemeeting) wählen
↓
Anpassen: 
- "prompt_purpose": "LinkedIn-Post für 1.6T-Transceiver-Launch"
- "participants": "3 Networking-Engineers bei Coherent"
- "actions": "Inspektion von optischen Transceivern, Diskussion über Datenvisualisierungen"
- "composition": "quadratisches Format (1:1), Platz für Text-Overlay oben"
↓
Checkliste: 
- Neptune Blue Farben ✓
- Authentisch ✓
- Divers ✓ 
- Keine proprietären Daten ✓
↓
Generieren, Ergebnis prüfen, bei Bedarf iterieren, Kollegen feedback einholen
```

---

## 🔒 13. IT-Sicherheit & Compliance-Hinweise (Sehr wichtig!)

### DSGVO-Konformität

**❌ NIEMALS:**
- Personenbezogene Daten in generierten Bildern
- Erkennbare Gesichter realer Coherent-Mitarbeiter ohne schriftliche Einwilligung
- Kunden- oder Projektdaten sichtbar (z.B. Kundennamen auf Dokumenten)
- Namen, E-Mail-Adressen oder Kontaktdaten

**✅ STATTDESSEN:**
- Generische Personen ohne Namensnennung
- Anonymisierte oder fiktive Szenarien
- Allgemeine Darstellungen ohne identifizierbare Merkmale

---

### IT-Sicherheit & Proprietary Information

**❌ NIEMALS:**
- Credentials, Passwörter oder API-Keys
- Detaillierte Netzwerkdiagramme mit realen IPs oder Systemarchitekturen
- Sensible Coherent-Produktspezifikationen (z.B. genaue Wavelength-Daten, Leistungswerte)
- Kundenspezifikationen oder NDA-geschützte Informationen
- Fertigungsprozesse mit Wettbewerbsrelevanz (z.B. SiC-Epitaxie-Details)
- Informationen über Sicherheitslücken oder Schwachstellen

**✅ STATTDESSEN:**
- Generische Begriffe (z.B. "Hochgeschwindigkeits-Transceiver", "optische Komponenten")
- Allgemeine Netzwerk-Visualisierungen ohne Details
- Öffentlich verfügbare Informationen

---

### Branchenspezifische Anforderungen

**Finanzsektor:**  
- Besondere Vorsicht bei Banking-Daten, Transaktionen
- Keine Darstellung realer Finanzinstitute ohne Genehmigung

**Healthcare:**  
- Patientendaten müssen vollständig anonymisiert sein
- Keine medizinischen Geräte mit erkennbaren Markennamen (außer Coherent)

**Automotive:**  
- Keine detaillierten EV-Batterie-Designs oder Fertigungsprozesse
- Allgemeine Darstellung von E-Mobilität ist okay

---

## 💡 14. Best Practices für verschiedene Branchen (Coherent-Fokus)

Coherent bedient vier Hauptmärkte: **Industrial, Communications, Electronics, Instrumentation**. Hier sind Tipps, wie du Bilder für jede Branche anpassen kannst:

---

### Industrial (Fertigung, Automotive, Laser-Anwendungen)

**Stil:**  
- Kraftvoll, präzise, dynamisch
- Fokus auf Produktionsprozesse und Laser in Aktion

**Farben:**  
- Neptune Blue mit metallischen Akzenten (Silber, Stahl)
- Warme Lichtakzente (z.B. glühende Schnittkanten)

**Fokus:**  
- Präzision, Innovation, Effizienz
- Laser-Schneiden, -Schweißen, -Bohren

**Vermeiden:**  
- Stereotype Industrie-Klischees (Funkenflug ohne Kontext)
- Unsichere Arbeitsumgebungen

**Template:** #3 (Laser Applications)

---

### Communications (Rechenzentren, Telekommunikation, Datacom)

**Stil:**  
- Modern, hochmodern, zukunftsweisend
- Fokus auf Netzwerktechnologie und Datenvisualisierungen

**Farben:**  
- Neptune Blue mit Cyan-Akzenten
- Weiß für Reinheit und Präzision

**Fokus:**  
- Hochgeschwindigkeits-Transceiver (800G, 1.6T)
- KI-Rechenzentren, Cloud-Infrastruktur
- Optische Netzwerke

**Vermeiden:**  
- Veraltete Server-Racks
- Stereotype "Hacker-Ästhetik"

**Template:** #1 (Teamwork) mit Fokus auf Networking-Equipment

---

### Electronics (Smartphones, Consumer Electronics, VCSEL-Anwendungen)

**Stil:**  
- Modern, consumer-freundlich, innovativ
- Fokus auf 3D-Sensing, Face Recognition, Consumer-Anwendungen

**Farben:**  
- Neptune Blue mit warmen Akzenten
- Cleane, moderne Ästhetik

**Fokus:**  
- VCSEL-Technologie (Face ID, AR)
- Smartphone-Komponenten
- Consumer-Anwendungen

**Vermeiden:**  
- Zu technisch/industriell
- Stereotype Smartphone-Klischees

**Template:** #1 (Teamwork) oder #2 (Materials) mit Consumer-Fokus

---

### Instrumentation (Medizin, Forschung, Life Sciences)

**Stil:**  
- Professionell, präzise, vertrauenswürdig
- Fokus auf medizinische Laser, Forschung, Diagnostik

**Farben:**  
- Neptune Blue mit frischen Grün-Akzenten (Gesundheit)
- Weiß für medizinische Umgebungen

**Fokus:**  
- Medizinische Laser (z.B. Urologie)
- Wissenschaftliche Forschung
- Präzisionsinstrumente

**Vermeiden:**  
- Klinische Kälte
- Sensible Patientendaten

**Template:** #3 (Laser) mit medizinischem Fokus

---

## 🎓 15. Weiterführende Tipps (Für Fortgeschrittene)

### Iteration und Verfeinerung

- ✅ **Generiere mehrere Varianten** mit leicht angepassten Prompts (z.B. verschiedene Perspektiven)
- ✅ **Teste verschiedene Kompositionen** (Nahaufnahme vs. Totale)
- ✅ **Passe Gewichtungen** in den `weights` an (z.B. `"style": 1.0` für mehr Fokus auf Stil)
- ✅ **Dokumentiere erfolgreiche Prompts** in einer Prompt-Bibliothek (z.B. Google Doc, Notion)

**Tipp:** Erstelle eine "Coherent Prompt Library" mit bewährten Beispielen für dein Team!

---

### Konsistenz wahren

- ✅ **Speichere bewährte Prompts** (z.B. in einer Team-Datei)
- ✅ **Verwende einheitliche Farbwerte** (Neptune Blue Hex-Codes!) über alle Generierungen hinweg
- ✅ **Achte auf konsistente Bildsprache** über Kampagnen hinweg (gleicher Stil, ähnliche Komposition)
- ✅ **Erstelle Prompt-Templates** für wiederkehrende Use Cases (z.B. "LinkedIn-Post-Template", "PowerPoint-Template")

---

### Qualitätssicherung (Human-in-the-Loop!)

- ✅ **Lass generierte Bilder von Kollegen gegenchecken** (z.B. Marketing-Team, Fachbereich)
- ✅ **Prüfe auf unbeabsichtigte sensible Informationen** (z.B. sichtbare Daten auf Displays)
- ✅ **Verifiziere Markenkonformität** (Farben, Stil, Tonalität)
- ✅ **Teste Bilder in verschiedenen Verwendungskontexten** (Web, Print, Social Media)

**Wichtig:** Bei Unsicherheit immer das Marketing-Team oder Corporate Communications kontaktieren!

---

## 📞 16. Support und Ressourcen

### Bei Fragen zu:

- **Corporate Design:** Coherent Marketing-Team (corporate.communications@coherent.com)
- **IT-Sicherheit:** Coherent Security-Team
- **DSGVO & Compliance:** Datenschutzbeauftragte
- **Markenrichtlinien:** Brand Management (Mark Lourie, VP Corporate Communications)

### Nützliche interne Ressourcen:

- Coherent Corporate Design Manual (verfügbar im Brand Portal)
- IT-Sicherheitsrichtlinien
- DSGVO-Compliance-Leitfaden
- Social Media Guidelines
- I CARE Werte-Dokument

---

## 🎯 Zusammenfassung: Die goldenen Regeln für Coherent

1. **Strukturierte JSON-Prompts nutzen** – klare Blöcke für konsistente Ergebnisse
2. **Neptune Blue konsequent einsetzen** – unsere Leitfarbe (#2E5D9D)
3. **Authentische Darstellung** – keine Klischees, echte Teams, realistische Szenarien
4. **DSGVO und IT-Sicherheit IMMER beachten** – keine proprietären Daten, keine Kundeninformationen
5. **Diversität und Professionalität kombinieren** – vielfältige Teams, aber immer professionell
6. **Branchenspezifische Anforderungen berücksichtigen** – Industrial, Communications, Electronics, Instrumentation
7. **Human-in-the-Loop-Prinzip leben** – KI ist ein Werkzeug, du triffst die finale Entscheidung
8. **Templates wiederverwenden und anpassen** – spare Zeit, bleibe konsistent
9. **Dokumentation & Wissensaustausch** – erfolgreiche Prompts teilen, aus Fehlern lernen
10. **Experimentieren erlaubt** – sei kreativ, aber bleibe markentreu (Innovations That Resonate!)

---

**Denken Sie daran:**
- ✅ KI-generierte Bilder sind ein **Werkzeug**, kein Ersatz für menschliches Urteilsvermögen
- ✅ Lassen Sie wichtige Visuals von Fachexperten überprüfen (Marketing, Compliance, Fachbereich)
- ✅ Dokumentieren Sie erfolgreiche Prompts für die Wiederverwendung (Team-Bibliothek!)
- ✅ Bleiben Sie experimentierfreudig, aber **markentreu** (Neptune Blue, wissenschaftlich, innovativ)
- ✅ Bei Unsicherheit: **Fragen stellen** ist besser als ein Fehler!

**Innovations That Resonate** – Eure Bilder sollten genau das tun: bei unseren Kunden, Partnern und Mitarbeitern ankommen und wirken! 🚀

---

**@ 2025 - HPI KI Workshops | Tutorials**
