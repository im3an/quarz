# Szenario Perspektiven

## Unsere Herangehensweise

Anstatt uns auf eines der [vorgegebenen Szenarien](https://cnoss.github.io/entwicklungsprojekt/szenario-ep-2025/) zu beschränken, haben wir uns entschieden, einen eigenständigen Weg zu gehen. Wir glauben, dass Innovation oft dann entsteht, wenn man etablierte Pfade verlässt und neue Perspektiven einnimmt.

Das vorgegebene Szenario bietet zweifelsohne wertvolle Rahmenwerk, doch für unser spezifisches Nutzungsproblem und unsere Vision erschien es uns sinnvoller, eine maßgeschneiderte Szenario-Perspektive zu entwickeln. Diese ermöglicht es uns, authentischer auf die tatsächlichen Bedürfnisse unserer Stakeholder einzugehen und einen Prototyp zu schaffen, der sich nicht in vorgegebene Muster zwängen muss.

## Unsere Szenario-Ideen

Im Folgenden präsentieren wir verschiedene Szenario-Perspektiven, die wir für unser Projekt in Betracht ziehen. Jedes Szenario wird hinsichtlich seiner Machbarkeit, Relevanz und des potenziellen Impact evaluiert.

### Szenario 1: [[./Szenario Perspektiven/Emotional wall.md | Emotional Wall]]

**Problemstellung:**
Menschen haben oft Schwierigkeiten, ihre Emotionen auszudrücken oder zu teilen – besonders in öffentlichen Räumen. Es fehlt an kreativen, anonymen Wegen, Gefühle sichtbar zu machen und kollektiv zu erleben.

**Zielgruppe:**
Eventbesucher:innen, Festivalgäste, Museums- oder Galeriebesucher:innen – alle, die spontan und anonym Emotionen teilen wollen.

**Lösungsansatz:**
Eine interaktive Wand, auf der Besucher:innen ihre Gefühle eingeben oder einsprechen können. Das System verwandelt diese Emotionen in abstrakte, animierte Visuals und passende Klänge, die großflächig projiziert werden. So entsteht ein lebendiges Stimmungsbild aller Anwesenden.

**Technische Herausforderungen:**

- Emotionserkennung aus Text oder Stimme (ML / Sentiment Analysis)
- Echtzeit-Visualisierung (Canvas / WebGL / SVG-Animation)
- Skalierbare Projektion & Performance im Browser

**Bewertungskriterien aus Fachperspektive:**

- **Interaktionsdesign:** intuitive, niedrigschwellige Nutzung
- **Technische Umsetzung:** stabile Echtzeitverarbeitung
- **Ästhetik & Ausdruck:** überzeugende emotionale Übersetzung

---


### Szenario 2: [[./Szenario Perspektiven/Interactive Study Chooser.md| Interactive Study Chooser]]

**Problemstellung:**
Studieninteressierte haben oft Schwierigkeiten, den passenden Studiengang zu finden – Informationsseiten sind trocken und unpersönlich.

**Zielgruppe:**
Schüler:innen, Studieninteressierte, Messebesucher:innen.

**Lösungsansatz:**
Ein interaktiver Bildschirm mit Kamera und AR-Elementen: Nutzer beantworten kurze Fragen, während das System mit visuellen Filtern, Mimik-Feedback und spielerischen Animationen reagiert. Am Ende wird ein passender Studiengang vorgeschlagen – emotional, immersiv und unterhaltsam.

**Technische Herausforderungen:**

- Gesichtserkennung & Emotionstracking (z. B. TensorFlow.js)
- Echtzeit-AR-Filter und Animationen
- Personalisierte Empfehlung basierend auf Antworten

**Bewertungskriterien aus Fachperspektive:**

- **Usability:** intuitiv und motivierend
- **Technik:** stabile Echtzeitverarbeitung
- **Kreativität:** Verbindung von Beratung und AR-Erlebnis

---

### Szenario 3: [[./Szenario Perspektiven/Whos Watching.md| Who’s Watching? - Privacy & Behavioral Change ]]

Who’s Watching? | Privacy & Behavioral Change

**Problemstellung:**
Menschen verhalten sich online unterschiedlich, je nachdem, ob sie sich beobachtet fühlen. Wie beeinflusst wahrgenommene Überwachung Ehrlichkeit und Ausdrucksverhalten?

**Zielgruppe:**
Studierende, Online-Communitys, Datenschutz-Interessierte.

**Lösungsansatz:**
Ein Webportal für anonyme Posts (z. B. Studiengeständnisse oder Tipps). Nutzer:innen erhalten zufällige Hinweise zur Sichtbarkeit ihres Beitrags (“sichtbar für 50 Personen”) — tatsächlich bleibt alles anonym. Das System analysiert, wie sich die wahrgenommene Öffentlichkeit auf Schreibstil und Offenheit auswirkt.

**Technische Herausforderungen:**

- Aufbau eines anonymen Post-Systems mit Datenanalyse
- Textanalyse (Ton, Länge, Emotion)
- Datenschutz & ethische Datenerfassung

**Bewertungskriterien aus Fachperspektive:**

- **Interaktivität:** niedrigschwellig, emotional
- **Technik:** solide Backend-Architektur, Sentiment-Analyse
- **Kreativität:** sozialpsychologisches Experiment als Webkunst

---

### Szenario 4: [[./Szenario Perspektiven/The Bias Interface.md | The Bias Interface]]

**Problemstellung:**
Nutzer:innen treffen Entscheidungen oft unbewusst beeinflusst durch Design-Elemente. Wie stark manipulieren Farben, Layouts oder Wortwahl unsere Entscheidungen online?

**Zielgruppe:**
Studierende, UX/UI-Designer:innen, Forschende in Kognitions- und Verhaltenspsychologie.

**Lösungsansatz:**
Eine simulierte Plattform (z. B. für Stipendien oder Abstimmungen), bei der kleine UI-Variationen (Button-Farben, Größe, Position) getestet werden. Das System misst, wie Designentscheidungen Nutzerverhalten beeinflussen.

**Technische Herausforderungen:**

- A/B-Test-System für UI-Varianten
- Datenerfassung und -auswertung von Nutzerentscheidungen
- Visualisierung der Bias-Ergebnisse

**Bewertungskriterien aus Fachperspektive:**

- **Interaktivität:** direkt erlebbarer Effekt von Designentscheidungen
-  **Technik:** präzise Tracking- und Analysetools
-  **Kreativität:** reflektiert ethische Fragen im UX-Design

---

### Szenario 5: [[./Szenario Perspektiven/Mosaic Generator.md | Mosaic Generator]]

**Problemstellung:**  
Kollektive digitale Kunst ist meist statisch oder von einzelnen Künstler:innen geschaffen. Wie kann Technologie es ermöglichen, dass viele Nutzer:innen gleichzeitig an einem sich ständig entwickelnden, ästhetisch harmonischen Kunstwerk teilnehmen?  

**Zielgruppe:**  
Kunstschaffende, digitale Designer:innen, Entwickler:innen, Community-Plattformen und interaktive Medienprojekte.  

**Lösungsansatz:**  
Eine kollaborative digitale Plattform, auf der jedes von Nutzer:innen hochgeladene Bild zu einem „Pixel“ in einem ständig wachsenden Mosaik wird. Die Position jedes Bildes wird anhand seiner dominanten Farbe berechnet und automatisch in eine größere Zielgrafik (z. B. ein Gemälde oder Logo) integriert. Beim Hovern oder Zoomen werden die ursprünglichen Fotos sichtbar und offenbaren die Vielfalt der Beiträge.  

**Technische Herausforderungen:**  

- Bildanalyse zur Extraktion der dominanten Farbe (z. B. via *color-thief* oder *k-means clustering*)  
- Echtzeit-Rendering und dynamische Aktualisierung des Mosaiks bei neuen Uploads  
- Performante Speicherung und Verwaltung großer Bildmengen (Cloudinary, Firebase, AWS S3)  
- Implementierung flüssiger Zoom- und Hover-Effekte (Canvas, WebGL oder Pixi.js)  
- Farb-Matching-Algorithmus zur optimalen Platzierung der Bilder innerhalb des Zielmotivs  

**Bewertungskriterien aus Fachperspektive:**  

- **Interaktivität:** gemeinschaftliches, sich permanent veränderndes Kunstwerk  
- **Technik:** nahtlose Integration von Frontend, Backend und Farbanalyse  
- **Kreativität:** ästhetisches Zusammenspiel aus Algorithmen, Design und Community  

## Entscheidungsmatrix

| Kriterium | Szenario 1 | Szenario 2 | Szenario 3 | Szenario 4 | Szenario 5 |
|-----------|------------|------------|------------|------------|------------|
| **Machbarkeit** (1-5) | 5 | 4 | 4 | 5 | 3 |
| **Innovation** (1-5) | 3 | 3 | 5 | 3 | 2 |
| **User Impact** (1-5) | 4 | 5 | 4 | 4 | 1 |
| **Fachliche Relevanz** (1-5) | 5 | 5 | 5 | 5 | 4 |
| **Team-Interesse** (1-5) | 2 | 3 | 3 | 4 | 1 |
| **Gesamt** | 19 | 20 | 21 | 21 | 11 |

## Finale Entscheidung

> 🎯 **Gewähltes Szenario:** [Wird nach Team-Diskussion eingetragen]

**Begründung:**
[Warum haben wir uns für dieses Szenario entschieden?]

**Nächste Schritte:**
1. [Schritt 1]
2. [Schritt 2]
3. [Schritt 3]

## Reflexion & Feedback

Dieser Abschnitt wird während des Projektverlaufs aktualisiert, um zu dokumentieren, ob unsere Entscheidung für ein eigenes Szenario sich als richtig erwiesen hat.

**Update [Datum]:**
[Lessons Learned, Herausforderungen, Erfolge]

---

<div align="center">

**Stand:** [Datum einfügen]  
**Status:** 🚧 In Diskussion | ✅ Entschieden

</div>