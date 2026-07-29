# CrystalScopeX 0.2.2

[English](README.md) | **Deutsch**

<p align="center">
  <a href="https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.2.2/CrystalScopeX-0.2.2-macOS-arm64.dmg">
    <img src="media/CrystalScopeX-icon.png" alt="CrystalScopeX-App-Symbol" width="144">
  </a>
</p>

<p align="center">
  <strong><a href="https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.2.2/CrystalScopeX-0.2.2-macOS-arm64.dmg">CrystalScopeX 0.2.2 für Apple Silicon direkt herunterladen (.dmg)</a></strong>
</p>

Willkommen bei CrystalScopeX — einer nativen macOS-App zum Erkunden von
Kristallstrukturen und Molekülen auf Apple-Silicon-Macs.

CrystalScopeX öffnet CIF-, XYZ-, Extended-XYZ-, MOL- sowie SHELXL-RES/INS-Dateien
und stellt sie in einer interaktiven 3D-Arbeitsumgebung dar. Sie können
Kristallgeometrien, thermische Ellipsoide, Orbitaloberflächen, Trajektorien und
Messungen untersuchen oder hochauflösende wissenschaftliche Abbildungen
exportieren. Importierte Strukturen bleiben dabei stets schreibgeschützt.

Version **0.2.2 (Build 7)** ist die letzte stabile Version der
0.2-Generation.

## Jetzt ansehen: 4K-Entwicklungsvorschau

[![CrystalScopeX Entwicklungsvorschau zur Molekülvisualisierung](media/CrystalScopeX-0.2.2-demo-preview.png)](https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.2.2/CrystalScopeX-0.2.2-demo-4K.mp4)

**[Unveränderte 4K-Entwicklungsvorschau ansehen oder herunterladen](https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.2.2/CrystalScopeX-0.2.2-demo-4K.mp4)**

> **Hinweis zum Video:** Das Video gibt einen frühen Einblick in Funktionen,
> die sich noch in aktiver Entwicklung befinden. Diese Vorschaufunktionen
> gehören nicht zum stabilen Funktionsumfang von 0.2.2 und sind für diese
> Version nicht zugesichert.

Das Video liegt unverändert im ursprünglichen HEVC-Format mit 3840 × 2160
Pixeln vor. Es wurde weder neu komprimiert noch in der Auflösung reduziert.

## Herunterladen und loslegen

Laden Sie
**[CrystalScopeX 0.2.2 für Apple Silicon](https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.2.2/CrystalScopeX-0.2.2-macOS-arm64.dmg)**
aus dem Release `v0.2.2` herunter. Vergleichen Sie das Image vor dem Öffnen mit
den veröffentlichten [SHA-256-Prüfsummen](SHA256SUMS.txt).

Sie benötigen:

- einen Mac mit Apple Silicon
- macOS 26.0 oder neuer
- eine Metal-fähige GPU

## Ein kurzer Hinweis vor dem ersten Start

CrystalScopeX 0.2.2 ist ad hoc codesigniert, aber **nicht mit einer Apple
Developer ID signiert und nicht von Apple notarisiert**. Daher wird macOS den
ersten regulären Start voraussichtlich blockieren.

Wenn der Download aus diesem Repository stammt und die SHA-256-Prüfsumme
übereinstimmt, führt Sie die [Installationsanleitung](INSTALLATION.md)
Schritt für Schritt durch das übliche Verfahren
**Datenschutz & Sicherheit → Dennoch öffnen**.

Es ist nicht erforderlich, Gatekeeper systemweit zu deaktivieren oder
Terminal-Befehle von Drittanbieter-Websites auszuführen.

## Das können Sie erkunden

- Native, GPU-beschleunigte Molekül- und Kristallvisualisierung.
- Kugel-Stab-, Kalotten- und Drahtgitterdarstellung.
- Elementarzellen, Symmetrie, Besetzungsfaktoren, Fehlordnung, Beschriftungen
  und thermische Ellipsoide.
- Messung von Abständen, Winkeln und Diederwinkeln.
- Wiedergabe von XYZ- und Extended-XYZ-Trajektorien.
- Schreibgeschützter Import von Gaussian-Cube-Dateien mit positiven und
  negativen Orbital-Isosurfaces.
- Export hochauflösender wissenschaftlicher PNG-Dateien, auch mit
  transparentem Hintergrund.
- Tastaturnavigation, VoiceOver, größerer Text und reduzierte Bewegung.
- Lokale Nutzung ohne Telemetrie, Werbung, Analysedienste oder Cloud-Konto.

## Unterstützte Dateiformate

| Format | Stabiler Funktionsumfang in 0.2.2 |
| --- | --- |
| CIF | CIF 1.1 und verbreitete CIF-2.0-Syntax, Elementarzellen, Symmetrie, Besetzungsfaktoren, Fehlordnung, anisotrope Auslenkungsparameter und Bindungen über periodische Zellgrenzen |
| XYZ | Standard-XYZ-Strukturen und aneinandergereihte Trajektorien |
| Extended XYZ | Gitter, Eigenschaften, Periodizität, Energie, Kräfte, Geschwindigkeiten, Ladungen, magnetische Momente und weitere typisierte Eigenschaften |
| MDL Molfile | Einzelstrukturen mit V2000- und V3000-Koordinaten, Bindungsordnungen, Ladungen und Bezeichnern |
| SHELXL RES/INS | Zelle, Gitter, Symmetrie, SFAC, FVAR/PART-Besetzung, Koordinaten sowie isotrope oder anisotrope Auslenkungsparameter |
| Gaussian Cube | Schreibgeschütztes Berechnungsergebnis für Skalarfeld- und Molekülorbital-Isosurfaces |

SHELXL-Dateien werden ausschließlich zur Visualisierung interpretiert.
CrystalScopeX führt keine Verfeinerungsanweisungen aus und schreibt keine
Änderungen in `.res`- oder `.ins`-Dateien zurück.

## Ihre Dateien bleiben bei Ihnen

- Importierte Strukturdateien werden niemals überschrieben.
- Die Dateiintegrität wird vor und nach dem Öffnen geprüft.
- Zuletzt verwendete Dateien nutzen sicherheitsbeschränkte,
  schreibgeschützte macOS-Lesezeichen.
- Erzeugte Berechnungsdaten und exportierte Bilder werden getrennt von der
  Quellstruktur verwaltet.
- Exportierte PNG-Metadaten enthalten weder lokale Pfade noch Konto- oder
  Dateisystemangaben.
- CrystalScopeX enthält keine Telemetrie und keinen Netzwerk-Client.

## CrystalScopeX mit ORCA verwenden

Wenn Sie ORCA bereits verwenden, kann CrystalScopeX eine kompatible, von Ihnen
lokal ausgewählte Installation ansprechen. ORCA ist nicht enthalten.
CrystalScopeX lädt ORCA weder herunter noch installiert, kopiert, verändert,
unterlizenziert oder verteilt es.

Für den optionalen Berechnungsablauf müssen Sie ORCA unabhängig von der
offiziellen Quelle beziehen, die zugehörige Lizenz akzeptieren und die lokale
Installation in CrystalScopeX auswählen.

CrystalScopeX ist eine unabhängige Anwendung eines Drittanbieters. Sie wird
weder von den ORCA-Entwicklern noch von deren verbundenen Institutionen
entwickelt, empfohlen, finanziert oder unterstützt. Weitere Informationen
finden Sie im [ORCA-Hinweis](ORCA-NOTICE.md).

## Informationen zum Release

- [Installationsanleitung](INSTALLATION.md)
- [SHA-256-Prüfsummen](SHA256SUMS.txt)
- [ORCA-Hinweis](ORCA-NOTICE.md)
- [Lizenz für akademische Nutzung](LICENSE.md)

Wenn CrystalScopeX für Ihre Forschung hilfreich ist, zitieren Sie bitte das
[CrystalScopeX-GitHub-Repository](https://github.com/DrWXB/CrystalScopeX-Releases).

Dieses schlanke Repository konzentriert sich bewusst auf Downloads und
Dokumentation für Anwenderinnen und Anwender. Quellcode, Tests,
Entwicklungswerkzeuge und der private Entwicklungsverlauf werden getrennt
aufbewahrt.

## Lizenz

CrystalScopeX 0.2.2 wird unter der
[CrystalScopeX Academic Use License 1.0](LICENSE.md) bereitgestellt:

- Nichtkommerzielle akademische Forschung, Lehre und Ausbildung sind ohne
  Lizenzgebühr gestattet.
- Eine kommerzielle Nutzung erfordert eine gesonderte schriftliche
  kommerzielle Lizenz.
- Änderungen, Reverse Engineering und Weiterverbreitung sind ohne vorherige
  schriftliche Genehmigung nicht gestattet, soweit das anwendbare Recht eine
  solche Einschränkung zulässt.

Es handelt sich um proprietäre Software für akademische Nutzung, nicht um
Open-Source-Software. Die Lizenz gewährt keine Rechte an ORCA oder anderer
Software beziehungsweise anderen Materialien Dritter. Bei Widersprüchen ist
der englische Lizenztext maßgeblich.

## Konkurrierende Interessen

Der Entwickler erklärt, dass kein konkurrierendes finanzielles Interesse
besteht.

## Wissenschaftliche Herkunft

Das im MP4 visualisierte Strukturmodell wurde aus der von Rösch et al.
veröffentlichten Kristallstruktur abgeleitet.<sup>1</sup> Die im Video gezeigten
Molekülorbitale wurden von CrystalScopeX über den integrierten
Berechnungsablauf berechnet und von CrystalScopeX dargestellt; die Orbitaldaten
wurden nicht aus der zitierten Publikation übernommen.

- **DOI:** [10.1038/s41586-021-03401-w](https://doi.org/10.1038/s41586-021-03401-w)
- **Link zum Artikel:** [Strongly reducing magnesium(0) complexes](https://www.nature.com/articles/s41586-021-03401-w)

**Literaturangabe**

1. Rösch, B.; Gentner, T. X.; Eyselein, J.; Langer, J.; Elsen, H.; Harder, S.
   Strongly Reducing Magnesium(0) Complexes. *Nature* **2021**, *592*, 717–721.
   DOI: [10.1038/s41586-021-03401-w](https://doi.org/10.1038/s41586-021-03401-w).
