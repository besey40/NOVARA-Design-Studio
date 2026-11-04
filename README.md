# NOVARA Logic & Product DNA

### Research-driven product pages for Shopify — with a visual experience layer in development

**Deutsch:** NOVARA verbindet strukturierte Produktrecherche mit Käuferverständnis, Verkaufstexten, Bildplanung und automatisierter Shopify-Seitenerstellung. Product DNA erweitert diesen Ansatz um hochwertige Produktpräsentationen mit Scroll-Animationen und geprüften 3D-Medien.

**English:** NOVARA is a research-driven product-page system for Shopify. It connects product evidence, buyer research, copy, image planning and page assembly. Product DNA adds an evolving visual layer with Three.js, animation and media workflows. We are looking for potential development collaborators. This repository contains public documentation only; the application source remains private.

> **Entwicklungsstand: 4. November 2026.** Es existieren eine Shopify-App, reale Forschungsläufe und geprüfte Teilabläufe. Der aktuelle vollständige Weg vom neuen Upload über ein echtes KI-Produktmodell bis zur installierten 3D-Shopify-Seite ist noch nicht durchgehend nachgewiesen. Das Projekt ist noch nicht allgemein verfügbar.

## Warum ich NOVARA entwickle

Eine überzeugende Produktseite beginnt für mich mit dem Verständnis des Produkts und seiner Käufer. Welche Probleme haben sie? Was haben sie bereits versucht? Welche Einwände sind berechtigt? Welche Aussagen lassen sich über das konkrete Produkt belegen?

NOVARA soll diese Fragen systematisch bearbeiten und die Erkenntnisse anschließend automatisch in Texte, Bildaufgaben und eine Produktseite übersetzen. Der Kunde soll nicht nach jeder Forschungsphase neue Anweisungen schreiben oder Ergebnisse manuell zusammensetzen müssen.

Ich kann selbst nicht klassisch programmieren. Meine Arbeit liegt in der Forschungslogik, den Produktanforderungen, der Gestaltung der Abläufe und der Bewertung der Ergebnisse. Die vorhandene Software ist durch intensive KI-gestützte Entwicklung entstanden. Für die fachliche Weiterentwicklung und einen zuverlässigen kommerziellen Betrieb suche ich den Austausch mit erfahrenen Entwicklerinnen und Entwicklern.

## Der vorgesehene Ablauf

```text
Produkt-PDF + zwei echte Produktbilder
                  ↓
Produktidentität und Quellen erfassen
                  ↓
Produkt, Käufer, Einwände und Wettbewerb recherchieren
                  ↓
Angebotslogik, Verkaufstexte und Bildaufgaben entwickeln
                  ↓
Ergebnisse prüfen und geeignete Medien zuordnen
                  ↓
Produktseite zusammensetzen und zur Prüfung bereitstellen
                  ↓
Nach Freigabe in Shopify installieren
```

Diese Arbeitsschritte sind in unterschiedlichen Entwicklungszweigen unterschiedlich weit verbunden. Das Diagramm beschreibt den Zielablauf und ist keine Behauptung eines bereits vollständig nachgewiesenen Gesamtdurchlaufs.

## Was bereits vorhanden ist

| Bereich | Tatsächlicher Stand |
|---|---|
| Shopify-Anwendung | Eingebettete Oberfläche mit Upload, Auftragsliste, Status, Detailansichten und Ergebnissen |
| Automatisierung | Hintergrundverarbeitung, gespeicherte Zwischenstände, automatische Übergaben und definierte Fehlerzustände |
| Recherche | Produktspezifischer Forschungsauftrag, Quellenrollen, Käufer- und Angebotsanalyse; reale ältere Codex-Läufe dokumentiert |
| Qualitätskontrolle | Strukturprüfungen, Claim-Grenzen, Bild-QA und Bindung von Artefakten an Produkt und Auftrag |
| Bilder | Referenzgestützte Generierungs- und Korrekturlogik; nicht alle Studio-Bildfunktionen sind im aktiven Gesamtablauf angeschlossen |
| Shopify-Installation | Für die ursprüngliche App historisch dokumentiert; der aktuelle neue Gesamtpfad bleibt zu verifizieren |
| Product DNA | Bestehende animierte Kapitelvorlage, automatische Inhaltszuordnung und geprüfter HTML-/ZIP-Vorschau-Export |
| 3D und Video | Three.js, GSAP und Medienadapter vorhanden; technische Blender-Tests mit einem Testkörper durchgeführt |

## Was an der Umsetzung interessant ist

- **Quellen haben unterschiedliche Rollen.** Wettbewerberinformationen dürfen nicht ungeprüft als Eigenschaften des eigenen Produkts erscheinen.
- **Unbekanntes bleibt sichtbar.** Fehlende Produktdaten und Ansichten werden als Lücken behandelt.
- **Ergebnisse bauen aufeinander auf.** Käuferanalyse, Texte und Bildaufgaben verwenden gespeicherte Forschungsergebnisse.
- **Produkt und Auftrag bleiben gebunden.** Datei-Prüfsummen und Kennungen sollen verhindern, dass Medien eines anderen Laufs eingesetzt werden.
- **Automatisierung hat Stopppunkte.** Fehlende Nachweise, Qualitätsprobleme oder Kontingente können den Ablauf blockieren.

Diese Mechanismen reduzieren bestimmte Fehler. Sie garantieren weder die Wahrheit jeder KI-Aussage noch perfekte Bilder oder Geometrie.

## Technologie und Entwicklungsaufgaben

Die vorhandenen Komponenten verwenden unter anderem React, React Router, TypeScript/JavaScript, Node.js, Shopify App Bridge, Prisma/SQLite, Three.js, GSAP/ScrollTrigger und Blender. Die untersuchte Rechercheausführung verwendet Codex CLI. Es handelt sich um eine Orchestrierung vorhandener KI-Werkzeuge, nicht um ein selbst trainiertes Basismodell.

Die nächsten fachlichen Aufgaben liegen in der Zusammenführung der bestehenden Entwicklungsstände, der zuverlässigen Fehlerbehandlung, echter Produktmodell-Validierung, mobilen Performance und dem vollständigen Shopify-Kaufablauf. Ein Testwürfel oder eine Vorschau ersetzt keinen echten Produkt-End-to-End-Test.

## Interesse an einer Zusammenarbeit?

Besonders interessant wäre der Austausch mit Menschen mit Erfahrung in:

- Frontend-Entwicklung und hochwertigem E-Commerce-Design;
- Three.js, WebGL, GSAP und sinnvollen Scroll-Interaktionen;
- responsiven und barrierearmen Produktdarstellungen;
- Shopify-Integration und zuverlässigen Hintergrundprozessen;
- der Fertigstellung und späteren Vermarktung eines bestehenden Softwareprojekts.

Es gibt noch keine hier belegten Aussagen zu Umsätzen, Marktanteilen oder besseren Conversion-Raten. Eine mögliche Zusammenarbeit und ihre Bedingungen müssten wir persönlich besprechen.

**Kontakt:** Öffne gern ein [GitHub-Issue](https://github.com/besey40/NOVARA-Design-Studio/issues), wenn du grundsätzlich Interesse hast. Bitte dort keine vertraulichen Informationen oder Zugangsdaten veröffentlichen. Technische Details und eine mögliche Vorführung können wir anschließend besprechen.

## Umfang dieses öffentlichen Repositories

Dieses Repository dient der Projektvorstellung und dem Austausch. Es enthält keinen Anwendungscode, keine Zugangsdaten, keine Kundendaten und keine internen Rechercheunterlagen. Die Software ist hier nicht als Open-Source-Projekt veröffentlicht. Es wird keine Nutzungslizenz für die private Anwendung erteilt.
