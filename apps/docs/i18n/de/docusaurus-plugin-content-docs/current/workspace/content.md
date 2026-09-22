---
sidebar_position: 3
---

# Inhalt

Auf der Seite **Inhalt** liegen Ihre Projekte, Datensätze und Vorlagen. Alles, worauf Sie zugreifen können, ist in **Bereiche** gegliedert: Ihren eigenen, die Ihrer Teams und den Ihrer Organisation. Inhalte gehören damit zu einem Bereich und nicht zu einer Person, und sie bleiben dort, wenn jemand hinzukommt oder das Team verlässt.

Auf der Seite Inhalt können Sie:

- **Alles in einem Bereich durchsuchen**, in Ordnern, die Sie selbst anlegen
- **Sehen, was andere mit Ihnen geteilt haben**, und was Sie zuletzt geöffnet haben
- **Teilen, verschieben, umbenennen, übertragen oder löschen**, wofür Sie verantwortlich sind
- **Wiederherstellen**, was Sie versehentlich gelöscht haben

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center' }}>
  <img src={require('/img/workspace/content/content_general_de.webp').default} alt="Die Seite Inhalt in GOAT" style={{ maxHeight: "auto", maxWidth: "100%"}}/>
</div>

## Bereiche

Es gibt drei Arten von Bereichen:

- **Meine Inhalte** gehören Ihnen. Was Sie erstellen, landet hier, sofern Sie es nicht woanders ablegen.
- **Team-Bereiche**, einer je Team, dem Sie angehören. Alle im Team können auf die Inhalte zugreifen.
- **Organisation**, freigegeben für alle in Ihrer Organisation.

Drei weitere Ansichten durchsuchen alle Bereiche zugleich, sodass Sie nicht wissen müssen, wo etwas liegt: **Mit mir geteilt** für alles, wozu andere Ihnen Zugriff gegeben haben, **Zuletzt bearbeitet** für das, was Sie zuletzt geöffnet haben, und **Papierkorb** für Gelöschtes, das sich noch zurückholen lässt.

Wenn Sie einen Bereich öffnen, sehen Sie seine Inhalte nach Art gruppiert: **Ordner**, **Projekte**, **Vorlagen** und **Datensätze**. Jede Gruppe zeigt eine Anzahl und lässt sich einklappen, eine leere Gruppe wird weggelassen, und mit `Mehr laden` holen Sie den Rest einer langen Gruppe.

Eine fünfte Gruppe, **Verknüpfungen**, erscheint erst, wenn etwas aus dem Bereich übertragen wurde. Siehe [Teilen und Übertragen](#teilen-und-übertragen-sind-zweierlei).

## Sich zurechtfinden

Die Werkzeugleiste über den Inhalten bietet:

- **Suche** innerhalb des Bereichs, in dem Sie sich befinden
- Ansicht als **Kacheln** oder **Liste**
- **Filtern** nach Inhaltstyp
- **Sortieren**, etwa nach `Zuletzt aktualisiert`
- **Einzelheiten**, öffnet eine Leiste mit Angaben zum ausgewählten Element
- **Neu**, um ein Projekt anzulegen, einen Datensatz hochzuladen oder einen Ordner hinzuzufügen

## Inhalte verwalten

Wählen Sie ein Element aus, oder mehrere, um damit zu arbeiten. Das Menü auf einer Karte und die Aktionsleiste bieten:

| Aktion | Was sie bewirkt |
|--------|-----------------|
| **Teilen** | Gibt anderen Zugriff. Sie bleiben Besitzer. |
| **Verschieben** | Legt das Element in einen anderen Ordner. |
| **Umbenennen** | Ändert den Namen. |
| **Rechte übertragen** | Übergibt das Element dauerhaft an jemand anderen. |
| **Löschen** | Verschiebt es in den Papierkorb. |

### Teilen und Übertragen sind zweierlei

**Teilen** gewährt Zugriff, während Sie Besitzer bleiben. Das ist sinnvoll, wenn Kolleginnen und Kollegen etwas sehen oder bearbeiten sollen, das weiterhin in Ihrer Verantwortung liegt.

**Rechte übertragen** verschiebt das Element dauerhaft in den Bereich einer anderen Person. Das ist der richtige Weg, wenn ein Projekt tatsächlich den Besitzer wechselt, etwa bei einer Übergabe vor dem Wechsel aus einem Team.

Im Ursprungsbereich bleibt eine **Verknüpfung** zurück, als solche gekennzeichnet und mit dem echten Namen des Elements. Sie ist ein Verweis: Ein Klick darauf führt Sie zum Element an seinem neuen Ort.

:::info Wer was sehen kann
Ein Element zeigt seine **Sichtbarkeit**: privat, mit einzelnen Personen geteilt, mit einem Team oder der Organisation geteilt, oder öffentlich. Ordner und Datenpakete können mit Teams und der Organisation geteilt werden.
:::

### Papierkorb und Wiederherstellen

Gelöschte Inhalte verschwinden nicht sofort: Sie landen im **Papierkorb**, aus dem der Besitzer sie **Wiederherstellen** kann. Sie bleiben dort, bis sie endgültig entfernt werden. Ein versehentliches Löschen lässt sich also rückgängig machen.

## Inhalte hinzufügen

`Neu` auf der Seite Inhalt bietet:

- **Neuer Ordner**, um Inhalte so zu gruppieren, wie es Ihnen passt
- **Leeres Projekt** oder **Projekt importieren**
- **Datensatz**, um eine Datei von Ihrem Gerät hochzuladen (GeoPackage, GeoJSON, Shapefile, KML, CSV, XLSX, Parquet sowie GTFS- und Overture-Archive) oder eine externe Quelle per URL zu verbinden (WFS, WMS, WMTS, XYZ-Kacheln oder COG)
- **Dokument hochladen**, für eine Datei, die zur Arbeit gehört, ohne selbst Daten zu sein

Ein Projekt lässt sich auch von der Startseite aus beginnen.

### Ein Projekt erstellen

<div class="step">
  <div class="step-number">1</div>
  <div class="content">Öffnen Sie über die Seitenleiste die Seite <code>Inhalt</code> und wechseln Sie in den Ordner, in dem das Projekt liegen soll.</div>
</div>

<div class="step">
  <div class="step-number">2</div>
  <div class="content">Klicken Sie auf <code>Neu</code> und wählen Sie <code>Leeres Projekt</code>.</div>
</div>

<div class="step">
  <div class="step-number">3</div>
  <div class="content">Geben Sie dem Projekt einen Namen und klicken Sie auf <code>Projekt erstellen</code>. Es wird in dem Ordner angelegt, den Sie gerade geöffnet haben, und öffnet sich direkt.</div>
</div>

### Ein Projekt importieren

Sie können ein Projekt importieren, das aus GOAT als `.zip`-Datei exportiert wurde.

<div class="step">
  <div class="step-number">1</div>
  <div class="content">Klicken Sie auf <code>Neu</code> und wählen Sie <code>Projekt importieren</code>.</div>
</div>

<div class="step">
  <div class="step-number">2</div>
  <div class="content">Wählen Sie die <code>.zip</code>-Datei aus.</div>
</div>

<div class="step">
  <div class="step-number">3</div>
  <div class="content">Geben Sie bei Bedarf einen <code>Projektnamen</code> ein, oder lassen Sie das Feld leer, um den exportierten Namen beizubehalten. Wählen Sie unter <code>Ziel</code> den Bereich und den <code>Ordner</code>.</div>
</div>

<div class="step">
  <div class="step-number">4</div>
  <div class="content">Klicken Sie auf <code>Importieren</code>. Der Import läuft im Hintergrund; den Fortschritt sehen Sie im Job-Menü.</div>
</div>

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center' }}>
  <img src={require('/img/workspace/projects/project_import.webp').default} alt="Ein Projekt in GOAT importieren" style={{ maxHeight: "auto", maxWidth: "100%", objectFit: "cover"}}/>
</div>

### Einen Datensatz hochladen

GOAT unterstützt mehrere Dateiformate zum Hochladen: **GeoPackage**, **GeoJSON**, **Shapefile**, **KML**, **CSV**, **XLSX**, **ZIP**, **Parquet** und **COG**-Dateien sowie **GTFS**-Archive (`gtfs.zip`) für [ÖPNV-Netze](../data/dataset_types.md#öpnv-netze) und **Overture**-Archive (`overture.zip`) für [Straßennetze](../data/dataset_types.md#straßennetze).

<div class="step">
  <div class="step-number">1</div>
  <div class="content">Öffnen Sie über die Seitenleiste die Seite <code>Inhalt</code>.</div>
</div>

<div class="step">
  <div class="step-number">2</div>
  <div class="content">Klicken Sie auf <code>Neu</code> und wählen Sie <code>Datensatz</code>.</div>
</div>

<div class="step">
  <div class="step-number">3</div>
  <div class="content">Im Schritt <strong>Datei auswählen</strong> wählen Sie die Datei von Ihrem lokalen Gerät aus. Die unterstützten Formate sind unten im Dialog aufgelistet. Klicken Sie auf <code>Weiter</code>.</div>
</div>

<div class="step">
  <div class="step-number">4</div>
  <div class="content"><strong>Nur für CSV- und XLSX-Dateien, Schritt Vorschau &amp; Konfiguration:</strong> GOAT zeigt eine Vorschau Ihrer tabellarischen Daten an, damit Sie diese vor dem Import überprüfen können.
    <ul>
      <li><code>Arbeitsblatt</code>: Bei XLSX-Dateien mit mehreren Blättern wählen Sie aus, welches Blatt importiert werden soll.</li>
      <li><code>Erste Zeile ist Kopfzeile</code>: Aktivieren (Standard), wenn die erste Zeile Ihrer Datei Spaltennamen enthält. Deaktivieren, wenn die erste Zeile Daten enthält. Spaltennamen werden dann automatisch generiert und können später in den Layer-Einstellungen umbenannt werden.</li>
    </ul>
    Die Vorschau-Tabelle zeigt die ersten Zeilen Ihrer Datei. Klicken Sie auf <code>Weiter</code>, wenn Sie fertig sind.
  </div>
</div>

<div class="step">
  <div class="step-number">5</div>
  <div class="content">Im Schritt <strong>Ziel &amp; Metadaten</strong> konfigurieren Sie Ihren Datensatz:
    <ul>
      <li><strong>Zielordner</strong>: Wählen Sie, wo Sie Ihren Datensatz organisieren möchten</li>
      <li><strong>Name</strong>: Geben Sie Ihrem Datensatz einen beschreibenden Namen</li>
      <li><strong>Beschreibung</strong> (optional): Fügen Sie Details über den Inhalt und Zweck Ihres Datensatzes hinzu</li>
    </ul>
    Klicken Sie auf <code>Weiter</code>.
  </div>
</div>

<div class="step">
  <div class="step-number">6</div>
  <div class="content">Überprüfen Sie Ihre Konfiguration im Schritt <strong>Bestätigung</strong> und klicken Sie auf <code>Hochladen</code>, um den Datensatz zu Ihrem Workspace hinzuzufügen.</div>
</div>

### Eine externe Quelle verbinden

Statt eine Datei hochzuladen, können Sie GOAT auf einen Dienst verweisen, der die Daten bereits veröffentlicht: **Web Feature Service (WFS)**, **Web Map Service (WMS)**, **Web Map Tile Service (WMTS)**, **XYZ-Kacheln** oder ein **Cloud Optimized GeoTIFF (COG)**.

<div class="step">
  <div class="step-number">1</div>
  <div class="content">Öffnen Sie über die Seitenleiste die Seite <code>Inhalt</code>.</div>
</div>

<div class="step">
  <div class="step-number">2</div>
  <div class="content">Klicken Sie auf <code>Neu</code> und wählen Sie <code>Datensatz</code>, dann die Option für eine externe Quelle.</div>
</div>

<div class="step">
  <div class="step-number">3</div>
  <div class="content">Geben Sie die URL des Dienstes ein.</div>
</div>

<div class="step">
  <div class="step-number">4</div>
  <div class="content">Wählen Sie aus den angebotenen Layern den gewünschten aus und klicken Sie auf <code>Weiter</code>.</div>
</div>

<div class="step">
  <div class="step-number">5</div>
  <div class="content">
  <p>Geben Sie dem Datensatz einen Namen, wählen Sie den Ordner, in dem er liegen soll, und ergänzen Sie bei Bedarf eine Beschreibung.</p>
  </div>
</div>

<div class="step">
  <div class="step-number">6</div>
  <div class="content">Prüfen Sie die Angaben und klicken Sie auf <code>Speichern</code>.</div>
</div>

### Einen Datensatz herunterladen

Beim Herunterladen eines räumlichen Datensatzes können Sie im Dialog Folgendes auswählen:

- **Download-Typ**: das Exportdateiformat (z. B. GeoPackage, GeoJSON, Shapefile).
- **Koordinatenreferenzsystem**: das KRS, in das die Daten vor dem Download umprojiziert werden. GOAT schlägt automatisch KRS-Optionen basierend auf der geografischen Ausdehnung des Datensatzes vor: Globale Optionen (WGS 84, Web Mercator) sind immer verfügbar, zusätzlich die passende UTM-Zone sowie relevante nationale oder regionale KRS. Der Standardwert ist **WGS 84 (EPSG:4326)**.

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center' }}>
  <img src={require('/img/workspace/datasets/managing_datasets_de.webp').default} alt="Datensatz-Verwaltungsoptionen" style={{ maxHeight: "auto", maxWidth: "100%"}}/>
</div>

### Datensatz-Metadaten und Vorschau

Klicken Sie auf den Namen eines Datensatzes, um ihn zu öffnen. Der Reiter `Zusammenfassung` beschreibt ihn und führt auf, was der Datengeber hinterlegt hat. Wenn der Datensatz Zeilen zum Anzeigen hat, enthält ein Reiter `Daten` eine Auswahl davon sowie die Spalten und ihre Typen.

<div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center'}}>
  <img src={require('/img/workspace/datasets/metadata.gif').default} alt="Metadaten der Datensätze im Workspace von GOAT" style={{ maxHeight: "auto", maxWidth: "auto", objectFit: "cover"}}/>
</div>