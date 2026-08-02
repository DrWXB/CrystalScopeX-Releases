# CrystalScopeX 0.3.2

[English](README.md) | **Deutsch**

<p align="center">
  <a href="https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.3.2/CrystalScopeX-0.3.2-macOS-arm64.dmg">
    <img src="media/CrystalScopeX-icon.png" alt="CrystalScopeX-App-Symbol" width="144">
  </a>
</p>

<p align="center">
  <strong><a href="https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.3.2/CrystalScopeX-0.3.2-macOS-arm64.dmg">CrystalScopeX 0.3.2 für Apple Silicon herunterladen (.dmg)</a></strong>
</p>

CrystalScopeX ist eine native macOS-Arbeitsumgebung zum Erkunden von
Kristallstrukturen, Molekülen, Verfeinerungsanweisungen, Trajektorien und
volumetrischen Berechnungsdaten auf Apple-Silicon-Macs.

Version **0.3.2 (Build 5)** ist die stabile öffentliche Version der
0.3-Generation. Sie verbindet den Molekülbetrachter mit einem 3D-Editor,
Strukturvergleich, Messebenen, einer integrierten SHELXL-Arbeitsumgebung,
optionalen lokalen Berechnungswerkzeugen und publikationsfertigem
Orbital-Medienexport.

## Herunterladen und loslegen

Laden Sie
**[CrystalScopeX 0.3.2 für Apple Silicon](https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.3.2/CrystalScopeX-0.3.2-macOS-arm64.dmg)**
aus dem Release `v0.3.2` herunter. Vergleichen Sie das Image vor dem Öffnen mit
den veröffentlichten [SHA-256-Prüfsummen](SHA256SUMS.txt).

Sie benötigen:

- einen Mac mit Apple Silicon
- macOS 26.0 oder neuer
- eine Metal-fähige GPU

## Ein kurzer Hinweis vor dem ersten Start

CrystalScopeX 0.3.2 ist ad hoc codesigniert, aber **nicht mit einer Apple
Developer ID signiert und nicht von Apple notarisiert**. Daher wird macOS den
ersten regulären Start voraussichtlich blockieren.

Wenn der Download aus diesem Repository stammt und seine SHA-256-Prüfsumme
übereinstimmt, führt Sie die [Installationsanleitung](INSTALLATION.md)
Schritt für Schritt durch das übliche Verfahren
**Datenschutz & Sicherheit → Dennoch öffnen**.

Es ist nicht erforderlich, Gatekeeper systemweit zu deaktivieren oder
Terminal-Befehle von Drittanbieter-Websites auszuführen.

## Präsentationen aus 0.3.2 in 4K mit 120 Bildern pro Sekunde

### Demo1-Referenzdrehung

[![CrystalScopeX Demo1-Referenzdrehung](media/CrystalScopeX-0.3.2-Demo1-gold-standard-preview.png)](https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.3.2/CrystalScopeX-0.3.2-Demo1-gold-standard-4K120.mp4)

**[Demo1-Referenzvideo in 4K mit 120 Bildern pro Sekunde ansehen oder herunterladen](https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.3.2/CrystalScopeX-0.3.2-Demo1-gold-standard-4K120.mp4)**

Dies ist die geschützte, nicht erneut komprimierte Demo1-Referenz: eine saubere
horizontale HEVC-Drehung mit 3840 × 2160 Pixeln und 120 Bildern pro Sekunde.
Die akzeptierte 4,8-Sekunden-Bewegung beginnt sanft, wird in der Mitte
schneller und endet wieder sanft.

### Mg0-Sequenz der Grenzorbitale

[![CrystalScopeX Mg0-Sequenz der Grenzorbitale](media/CrystalScopeX-0.3.2-Mg0-orbital-sequence-preview.png)](https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.3.2/CrystalScopeX-0.3.2-Mg0-orbital-sequence-4K120.mp4)

**[Mg0-Orbitalsequenz in 4K mit 120 Bildern pro Sekunde ansehen oder herunterladen](https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.3.2/CrystalScopeX-0.3.2-Mg0-orbital-sequence-4K120.mp4)**

Die 24-sekündige HEVC-Präsentation hält eine feste wissenschaftliche Ansicht
und wechselt von HOMO−5 über HOMO sowie von LUMO bis LUMO+5. Jedes berechnete
Orbital bleibt genau zwei Sekunden sichtbar.

## Beibehaltene 4K-Vorschau aus dem Release 0.2.2

[![CrystalScopeX Entwicklungsvorschau zur Molekülvisualisierung](media/CrystalScopeX-0.2.2-demo-preview.png)](https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.2.2/CrystalScopeX-0.2.2-demo-4K.mp4)

**[Unveränderte 4K-Entwicklungsvorschau aus 0.2.2 ansehen oder herunterladen](https://github.com/DrWXB/CrystalScopeX-Releases/releases/download/v0.2.2/CrystalScopeX-0.2.2-demo-4K.mp4)**

Diese bereits veröffentlichte historische Vorschau bleibt ohne erneute
Komprimierung oder Auflösungsänderung im ursprünglichen HEVC-Format mit
3840 × 2160 Pixeln erhalten. Sie ist die akzeptierte visuelle Referenz des
Releases 0.2.2 und bleibt neben den oben vom Eigentümer freigegebenen
Präsentationsmedien aus 0.3.2 verfügbar.

## Kurzüberblick der Änderungen in 0.3.2

- **Strukturvergleich:** Zwei kompatible Strukturen können automatisch
  ausgerichtet oder anhand entsprechender Atome geführt zugeordnet werden,
  wenn eine manuelle wissenschaftliche Entscheidung geeigneter ist. Die
  verglichenen Strukturen bleiben visuell klar unterscheidbar.
- **Wissenschaftliche Messungen:** Abstände, Winkel und Diederwinkel lassen
  sich messen. Aus mindestens drei Atomen kann außerdem eine Ebene definiert
  und in weiteren Messungen verwendet werden.
- **Integrierte 3D-Bearbeitung:** Eine separate Molekülskizze lässt sich
  erstellen und verändern, während die geöffnete Quellstruktur unverändert
  bleibt.
- **SHELXL-Anweisungsbereich:** INS/RES-Anweisungen mit strukturellen Abständen,
  Zeilennummern, Syntaxdarstellung und PART-Sichtbarkeit bearbeiten; optional
  kann ein vom Benutzer bereitgestelltes SHELXL-Programm zur Verfeinerung
  verwendet werden.
- **Orbitalpräsentation:** Kompatible Gaussian-Cube-Ordner importieren,
  Grenzorbitale in wissenschaftlicher Reihenfolge durchsuchen, vorhandene
  Spinkanäle auswählen, einen gemeinsamen Isowert eingeben, die Transparenz
  einstellen, Rotationen vorab ansehen, jedes Orbital als 4K-PNG speichern und
  saubere HEVC-Orbitalvideos in 4K mit 120 Bildern pro Sekunde exportieren.
- **Bessere Tiefe und Kameraführung:** Depth Fade, verbesserte Beleuchtung,
  an Carl angepasste Einpassung, ein stabiler Drehpunkt und kamerastabiles
  Umschalten der Orbitale verbessern die räumliche Lesbarkeit, ohne die
  etablierten Gesten zu verändern.
- **Konzentrierte Darstellungssteuerung:** Wasserstoffatome können global
  ausgeblendet werden; über das Kontextmenü eines Nicht-Wasserstoffatoms lassen
  sich dessen benachbarte Atome vollständig einblenden.
- **Wiederhergestellter Arbeitsbereich:** Nützliche Fenster-, Inspektor-,
  Platzierungs- und Molekülansichtseinstellungen bleiben zwischen Starts
  erhalten.

Das [ausführliche Änderungsprotokoll](CHANGELOG.md) enthält die vollständige
öffentliche Übersicht zu Funktionen, Darstellung, Leistung, Kompatibilität und
Datensicherheit in 0.3.2.

## Aus 0.2.2 beibehaltene Kernfunktionen

- Native, GPU-beschleunigte Molekül- und Kristallvisualisierung.
- Kugel-Stab-, Kalotten- und Drahtgitterdarstellung.
- Elementarzellen, Symmetrie, Besetzung, Fehlordnung, Beschriftungen und
  thermische Ellipsoide.
- Wiedergabe von XYZ- und Extended-XYZ-Trajektorien.
- Messung von Abständen, Winkeln und Diederwinkeln, jetzt ergänzt um Ebenen.
- Schreibgeschützter Import von Gaussian-Cube-Dateien mit positiven und
  negativen Orbital-Isosurfaces.
- Export hochauflösender wissenschaftlicher PNG-Dateien, wo unterstützt auch
  mit transparentem Hintergrund.
- Tastaturnavigation, VoiceOver, größerer Text und reduzierte Bewegung.
- Lokale Nutzung ohne Telemetrie, Werbung, Analysedienste oder Cloud-Konto.

## Häufig verwendete Dateiformate

CrystalScopeX konzentriert seine Hauptoberfläche auf verbreitete
wissenschaftliche Formate. Die folgende Tabelle ist eine praktische Übersicht
und keine Zusage, dass jede mögliche Variante oder Dateiendung austauschbar ist.

| Format | Stabiler Funktionsumfang in 0.3.2 |
| --- | --- |
| CIF | CIF 1.1 und verbreitete CIF-2.0-Syntax, Elementarzellen, Symmetrie, Besetzung, Fehlordnung, anisotrope Auslenkungsdaten und periodische Geometrie |
| XYZ / Extended XYZ | Einzelstrukturen und Trajektorien mit verbreiteten Gitter-, Eigenschafts-, Kraft-, Geschwindigkeits-, Ladungs- und Magnetmomentfeldern |
| MDL MOL / SDF | V2000- und V3000-Koordinaten, Bindungsordnungen, Ladungen, Bezeichner und begrenzte SDF-Datensätze |
| PDB / PDBx-mmCIF | Molekülmodelle, verbreitete Konnektivität, mehrere Modelle, Elementarzellen und unterstützte anisotrope Datensätze |
| SHELXL INS / RES | Strukturinterpretation und integrierter Anweisungsbereich; Quelltexte werden durch das Öffnen nie überschrieben |
| Gaussian Cube | Schreibgeschützte Skalarfeld- und Molekülorbitaldaten mit positiven und negativen Isosurfaces |

## Ihre Dateien bleiben bei Ihnen

- Das Öffnen einer Struktur überschreibt niemals die Quelldatei.
- Die Dateiintegrität wird vor und nach dem Öffnen geprüft.
- Zuletzt verwendete Dateien nutzen sicherheitsbeschränkte,
  schreibgeschützte macOS-Lesezeichen.
- Bearbeitungen, Verfeinerungsergebnisse, Berechnungsdaten, Bilder und Videos
  werden nur nach einer ausdrücklichen Benutzeraktion als separate Ergebnisse
  geschrieben.
- Wissenschaftliche Bilder und Videos werden standardmäßig in sichtbaren,
  inhaltsbezogenen Strukturordnern unter `Documents/CrystalScopeX Exports`
  gespeichert.
- Die Präsentationsebene exportierter wissenschaftlicher Medien enthält keine
  lokalen Pfade, Kontoangaben oder Quelldateiorte.
- CrystalScopeX enthält keine Telemetrie, Werbung, Analysedienste oder
  Cloud-Konto-Pflicht.

## Optionale lokale wissenschaftliche Programme

CrystalScopeX kann kompatible ORCA- und SHELXL-Programme verwenden, die Sie
selbst beziehen, lizenzieren, installieren und lokal auswählen. Keines dieser
Programme ist in CrystalScopeX enthalten. CrystalScopeX lädt sie weder herunter
noch installiert, kopiert, unterlizenziert oder verteilt es sie.

CrystalScopeX ist eine unabhängige Anwendung eines Drittanbieters. Sie wird
weder von den ORCA- oder SHELXL-Entwicklern noch von deren verbundenen
Institutionen entwickelt, empfohlen, finanziert oder unterstützt. Die
ORCA-Abgrenzung und Literaturhinweise finden Sie in
[ORCA-NOTICE.md](ORCA-NOTICE.md).

Für beide optionalen Arbeitsabläufe müssen Sie das jeweilige Programm
unabhängig von seiner offiziellen Quelle beziehen, seine Lizenz akzeptieren
und die lokale Ausführungsdatei in CrystalScopeX auswählen. Ein Download oder
eine Lizenz von CrystalScopeX gewährt keine Rechte an Drittsoftware.

## Informationen zum Release

- [Installationsanleitung](INSTALLATION.md)
- [Ausführliches Änderungsprotokoll](CHANGELOG.md)
- [SHA-256-Prüfsummen](SHA256SUMS.txt)
- [ORCA-Hinweis](ORCA-NOTICE.md)
- [Hinweise zur Interoperabilität mit Drittsoftware](THIRD-PARTY-NOTICES.md)
- [Lizenz für akademische Nutzung](LICENSE.md)

Wenn CrystalScopeX für Ihre Forschung hilfreich ist, zitieren Sie bitte das
[CrystalScopeX-GitHub-Repository](https://github.com/DrWXB/CrystalScopeX-Releases).

Dieses Repository ist bewusst auf Release-Binärdateien, Prüfsummen und
Dokumentation für Anwenderinnen und Anwender beschränkt. Quellcode, Tests,
Entwicklungswerkzeuge und die private Entwicklungshistorie von CrystalScopeX
werden getrennt aufbewahrt und hier nicht veröffentlicht.

## Lizenz

CrystalScopeX 0.3.2 wird unter der
[CrystalScopeX Academic Use License 1.0](LICENSE.md) bereitgestellt:

- Nichtkommerzielle akademische Forschung, Lehre und Ausbildung sind ohne
  Lizenzgebühr gestattet.
- Eine kommerzielle Nutzung erfordert eine gesonderte schriftliche
  kommerzielle Lizenz.
- Änderungen, Reverse Engineering und Weiterverbreitung sind ohne vorherige
  schriftliche Genehmigung nicht gestattet, soweit das anwendbare Recht eine
  solche Einschränkung zulässt.

Es handelt sich um proprietäre Software für akademische Nutzung, nicht um
Open-Source-Software. Die Lizenz gewährt keine Rechte an ORCA, SHELXL oder
anderer Software beziehungsweise anderen Materialien Dritter. Bei
Widersprüchen ist der englische Lizenztext maßgeblich.

## Konkurrierende Interessen

Der Entwickler erklärt, dass kein konkurrierendes finanzielles Interesse
besteht.

## Wissenschaftliche Herkunft

Das im beibehaltenen MP4 aus 0.2.2 visualisierte Strukturmodell wurde aus der
von Rösch et al. veröffentlichten Kristallstruktur abgeleitet.<sup>1</sup> Die
in diesem Video gezeigten Molekülorbitale wurden über den lokalen
CrystalScopeX-Berechnungsablauf berechnet und von CrystalScopeX dargestellt;
die Orbitaldaten wurden nicht aus der zitierten Publikation übernommen.

- **DOI:** [10.1038/s41586-021-03401-w](https://doi.org/10.1038/s41586-021-03401-w)
- **Link zum Artikel:** [Strongly reducing magnesium(0) complexes](https://www.nature.com/articles/s41586-021-03401-w)

**Literaturangaben**

1. Rösch, B.; Gentner, T. X.; Eyselein, J.; Langer, J.; Elsen, H.; Harder, S.
   Strongly Reducing Magnesium(0) Complexes. *Nature* **2021**, *592*, 717–721.
   DOI: [10.1038/s41586-021-03401-w](https://doi.org/10.1038/s41586-021-03401-w).
2. Neese, F. The ORCA Program System. *WIREs Comput. Mol. Sci.* **2012**, *2*,
   73–78. DOI: [10.1002/wcms.81](https://doi.org/10.1002/wcms.81).
3. Neese, F. Software Update: The ORCA Program System—Version 6.0.
   *WIREs Comput. Mol. Sci.* **2025**, *15* (2), e70019. DOI:
   [10.1002/wcms.70019](https://doi.org/10.1002/wcms.70019).
