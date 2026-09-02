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

<p align="justify">
CrystalScopeX erweckt Kristall&shy;strukturen in einer flüssigen, visuell
eindrucksvollen wissen&shy;schaftlichen Arbeits&shy;umgebung zum Leben.
Erkunden Sie vollständige kristallo&shy;graphische Modelle interaktiv in 3D,
von kleinen Molekülen über symmetrie&shy;erzeugte Komponenten, Fehlordnung und
Verzwillingung bis zu anisotropen Auslenkungs&shy;parametern. Messen,
bearbeiten, verfeinern und gestalten Sie publikations&shy;reife Ergebnisse in
einer fokussierten Oberfläche, die Ideen voranbringt.
</p>

## Installation

<div align="justify">

Version **0.3.6 (Build 9)** ist für arm64-Systeme mit macOS 26.0 oder neuer und Metal-Unterstützung vorgesehen.

</div>

<div align="justify">

Laden Sie das DMG aus dem [Release v0.3.6](https://github.com/DrWXB/CrystalScopeX-Releases/releases/tag/v0.3.6) herunter und prüfen Sie die [SHA-256-Prüfsumme](SHA256SUMS.txt).

</div>

<div align="justify">

Dieser Build ist ad hoc codesigniert, aber **weder mit einer Developer ID signiert noch notarisiert**. Folgen Sie der [Installationsanleitung](INSTALLATION.md) für das übliche Verfahren **Datenschutz & Sicherheit → Dennoch öffnen**. Deaktivieren Sie Gatekeeper nicht systemweit.

</div>

## Demo

![CrystalScopeX-Arbeitsbereich zur Strukturverfeinerung](media/Demo3_png.png)

## Entwicklerprotokoll 0.3.6

<div align="justify">

- Ein vollständig neuer nativer arm64-Workflow zur Kristall&shy;struktur&shy;verfeinerung wurde ergänzt. Die Kompa&shy;tibilität mit SHELXL<sup>1</sup>-Semantik und -Anweisungen wird aktiv entwickelt; die Funktion bleibt im Beta-Stadium. Die aktuelle Beta hat Kompi&shy;lierungs&shy;tests mit mehr als 5.000 kristallo&shy;graphischen Fällen bestanden.
- Ersetzung, Nummerierung, Reihenfolge und Koordinaten der Q-Peaks bei wiederholter Verfeinerung wurden korrigiert. Jede Peak-Liste bleibt dabei an die zugehörige RES-Struktur und Differenzdichtekarte gebunden.
- Der Zugriff auf Operationen, Details und Periodensystem aus Refine wurde wiederhergestellt. Die optionale externe SHELXL-Anbindung und ihre Einstellungen sind vorübergehend entfernt; der integrierte CRC-2026-Verfeinerungsworkflow bleibt verfügbar.

</div>

## Release-Informationen

- [Änderungsprotokoll](CHANGELOG.md)
- [Installationsanleitung](INSTALLATION.md)
- [Hinweise zu Drittanbietern](THIRD-PARTY-NOTICES.md)
- [Lizenz](LICENSE.md)

<div align="justify">

ORCA<sup>2,3</sup> und SHELXL (temporarily removed) sind optionale, separat lizenzierte und vom Benutzer bereit&shy;gestellte Programme. Sie sind nicht in CrystalScopeX enthalten. Dieses öffentliche Repository enthält ausschließlich Release-Materialien; privater Quellcode, Forschungs&shy;daten und lokale Entwicklungs&shy;pfade werden nicht veröffentlicht. Das erste ARM64-native Kleinmolekül-Verfeinerungsprogramm für Apple Silicon wird in Kürze als eigenständiges Open-Source-Projekt veröffentlicht.

</div>

## Literaturangaben

1. Sheldrick, G. M. A short history of *SHELX*. *Acta Crystallogr. A* **2008**, *64*, 112–122. DOI: [10.1107/S0108767307043930](https://doi.org/10.1107/S0108767307043930).
2. Neese, F. The ORCA program system. *WIREs Comput. Mol. Sci.* **2012**, *2*, 73–78. DOI: [10.1002/wcms.81](https://doi.org/10.1002/wcms.81).
3. Neese, F. Software update: The ORCA program system, version 6.0. *WIREs Comput. Mol. Sci.* **2025**, *15* (2), e70019. DOI: [10.1002/wcms.70019](https://doi.org/10.1002/wcms.70019).
