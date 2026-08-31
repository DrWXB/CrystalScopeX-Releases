# CrystalScopeX 0.3.6

[English](README.md) | **Deutsch**

<p align="center">
  <a href="https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.3.6/CrystalScopeX-0.3.6-macOS-arm64.dmg">
    <img src="media/CrystalScopeX-icon.png" alt="CrystalScopeX-App-Symbol" width="144">
  </a>
</p>

<p align="center">
  <strong><a href="https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.3.6/CrystalScopeX-0.3.6-macOS-arm64.dmg">CrystalScopeX 0.3.6 für macOS arm64 herunterladen</a></strong>
</p>

CrystalScopeX ist eine native wissenschaftliche Arbeitsumgebung für
Kristallstrukturen und molekulare Daten. Vollständige kristallographische
Modelle, einschließlich Ionen, Lösungsmittelmolekülen, symmetrieerzeugten
Komponenten, Fehlordnung und anisotropen Auslenkungsparametern, werden
dargestellt. Interaktive 3D-Inspektion,
Messungen, Strukturbearbeitung, Verfeinerungsanweisungen und
publikationsorientierte Ausgabe sind in einer klaren Oberfläche verbunden.

## Installation

Version **0.3.6 (Build 9)** ist für arm64-Systeme mit macOS 26.0 oder neuer und
Metal-Unterstützung vorgesehen.

Laden Sie das DMG aus dem [Release v0.3.6](https://github.com/DrWXB/CrystalScopeX-Releases/releases/tag/v0.3.6)
herunter und prüfen Sie die [SHA-256-Prüfsumme](SHA256SUMS.txt).

Dieser Build ist ad hoc codesigniert, aber **weder mit einer Developer ID
signiert noch notarisiert**. Folgen Sie der
[Installationsanleitung](INSTALLATION.md) für das übliche Verfahren
**Datenschutz & Sicherheit → Dennoch öffnen**. Deaktivieren Sie Gatekeeper
nicht systemweit.

## Demo

[![CrystalScopeX-Demo](media/CrystalScopeX-0.3.2-Demo1-gold-standard-preview.png)](https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.3.2/CrystalScopeX-0.3.2-Demo1-gold-standard-4K120.mp4)

**[Demo-Video in 4K mit 120 Bildern pro Sekunde ansehen oder herunterladen](https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.3.2/CrystalScopeX-0.3.2-Demo1-gold-standard-4K120.mp4)**

## Entwicklerprotokoll 0.3.6

- Ein vollständig neuer nativer arm64-Workflow zur Kristallstrukturverfeinerung
  wurde ergänzt. Die Kompatibilität mit SHELXL-Semantik und -Anweisungen wird
  aktiv entwickelt; die Funktion bleibt im Beta-Stadium. Die aktuelle Beta hat
  Kompilierungstests mit mehr als 5.000 kristallographischen Fällen bestanden.

## Release-Informationen

- [Änderungsprotokoll](CHANGELOG.md)
- [Installationsanleitung](INSTALLATION.md)
- [Hinweise zu Drittanbietern](THIRD-PARTY-NOTICES.md)
- [Lizenz](LICENSE.md)

ORCA und SHELXL sind optionale, separat lizenzierte und vom Benutzer
bereitgestellte Programme. Sie sind nicht in CrystalScopeX enthalten. Dieses
öffentliche Repository enthält ausschließlich Release-Materialien; privater
Quellcode, Forschungsdaten und lokale Entwicklungspfade werden nicht
veröffentlicht.

## Wissenschaftliche Herkunft

Das oben gezeigte Mg0-Beispiel verwendet ein Strukturmodell, das aus der von
Rösch et al. veröffentlichten Kristallstruktur abgeleitet wurde.<sup>1</sup>
Die Molekülorbitale wurden über den lokalen CrystalScopeX-Arbeitsablauf
berechnet und von CrystalScopeX dargestellt. Die Orbitaldaten wurden nicht aus
der zitierten Publikation übernommen.

- **DOI:** [10.1038/s41586-021-03401-w](https://doi.org/10.1038/s41586-021-03401-w)
- **Artikel:** [Strongly reducing magnesium(0) complexes](https://www.nature.com/articles/s41586-021-03401-w)

**Literaturangaben**

1. Rösch, B.; Gentner, T. X.; Eyselein, J.; Langer, J.; Elsen, H.; Harder, S.
   Strongly Reducing Magnesium(0) Complexes. *Nature* **2021**, *592*, 717–721.
   DOI: [10.1038/s41586-021-03401-w](https://doi.org/10.1038/s41586-021-03401-w).
2. Neese, F. The ORCA Program System. *WIREs Comput. Mol. Sci.* **2012**, *2*,
   73–78. DOI: [10.1002/wcms.81](https://doi.org/10.1002/wcms.81).
3. Neese, F. Software Update: The ORCA Program System, Version 6.0.
   *WIREs Comput. Mol. Sci.* **2025**, *15* (2), e70019. DOI:
   [10.1002/wcms.70019](https://doi.org/10.1002/wcms.70019).
