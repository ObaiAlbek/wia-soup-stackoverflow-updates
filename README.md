# WIA – SOUP: Automatisiertes Aktualisieren von Stack-Overflow-Posts

Dieses Repository enthält die Seminararbeit aus dem Kurs  
**„Wissenschaftliches Arbeiten (WIA)”** zum Thema:

> **Kommentare als Signalquelle für automatisierte Aktualisierung von Stack-Overflow-Antworten  
> – Fallstudie: SOUP (Stack Overflow Update Pipeline)**

Die Arbeit untersucht:

- Obsoleszenz von Antworten auf Stack Overflow  
- die Rolle von Kommentaren als Wartungssignal  
- das Framework **SOUP**, das mittels LLMs Kommentar–Edit-Beziehungen nutzt, um automatische Updates vorzuschlagen  
- Chancen und Grenzen hybrider Pflegeprozesse (KI + menschliche Review-Prozesse)

---

## 📂 Projektstruktur

```text
.
├── main.tex            # Hauptdokument (LaTeX)
├── preambel.tex        # Präambel / Einstellungen der Hochschule
├── literatur.bib       # BibTeX-Literaturdatenbank
├── img/                # Abbildungen (z.B. SOUP-Pipeline)
├── IEEEtran.cls        # Dokumentklasse (IEEE-Konferenzstil)
├── .gitignore
└── README.md
````

Build-Artefakte wie `.aux`, `.log`, `.out` usw. werden über `.gitignore` ausgeschlossen.

---

## 🔧 Kompilieren

Voraussetzungen:

* LaTeX-Distribution (z.B. TeX Live oder MiKTeX)
* optional: `latexmk`

Kompilieren auf der Kommandozeile:

```bash
latexmk -pdf main.tex
```

Die fertige PDF wird im Projektverzeichnis erzeugt.

---

## 📘 Seminararbeit (PDF)

Wenn du die fertige PDF im Repo ablegst (z.B. als `WIA_SOUP_Seminararbeit.pdf`), kannst du sie hier direkt verlinken:

[📄 Seminararbeit lesen (PDF)](Obai_Albek_Seminararbeit_StackOverflow_Updates.pdf)

---
