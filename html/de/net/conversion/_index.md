---
translation: true
template: /templates/_template-conversion.md
title: Konvertieren Sie HTML, XHTML, Markdown, MHTML, EPUB und SVG mit C#
url: /net/conversion/
description: Konvertieren Sie HTML in XHTML, PDF, DOCX, XPS, Markdown, MHTML und Bilder mit wenigen Zeilen C#-Code über die .NET-Bibliothek. Überprüfen Sie kostenlos den Online-HTML-Konverter!
---

{{<section banner>}}
---
h1: HTML-Konvertierung über C#
h2: Konvertieren Sie HTML der Hypertext-Markup-Sprache in XHTML, MHTML, Markdown, PDF, XPS, DOCX und Bilder, einschließlich BMP, JPG, PNG, TIFF, um plattformübergreifende .NET-Anwendungen zu erstellen
---

{{<section overview>}}
---
h2: So konvertieren Sie HTML mit C#
---

 1. Laden Sie ein HTML-Dokument mithilfe eines der [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument)-Konstruktoren in ein Document-Objekt. Sie können HTML aus einer Datei, einem HTML-Code, einem Stream oder einer URL laden.
 2. Erstellen Sie ein Objekt zum Speichern von Optionen.
 3. Rufen Sie eine der Methoden [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) auf und übergeben Sie ihr die erforderlichen Parameter.

Hypertext-Markup-Sprache HTML ist die Sprache des Webs. Derzeit sind die meisten Informationen auf Websites in Form von Webseiten vorhanden. Daher ist die Konvertierung dieser HTML-basierten Informationen in andere Formate wie PDF, XPS, Microsoft® Word, Markdown und Bildformate ein gängiges Szenario. [.NET HTML API](https://products.aspose.com/html/net/) vereinfacht den Konvertierungsprozess für Entwickler. Es lädt die Datei mithilfe der HTMLDocument-Klasse, erstellt das relevante Speicheroptionsobjekt und verwendet die [Converter-Klasse](https://reference.aspose.com/html/net/aspose.html.converters/converter) relevante Konvertierungsmethode.</ br></br>
Jede Konvertierung, die Sie durchführen möchten, beinhaltet das Laden eines HTML-Dokuments und das Speichern im unterstützten Format. Es können verschiedene Szenarien sein, aber es kann mit ein paar erforderlichen Schritten erstellt werden:</br>

{{<section demos>}}
---
h2: HTML Converter Live-Demos
---

Sie können HTML mit Aspose.HTML für die .NET-API in Echtzeit konvertieren. Das folgende C#-Beispiel zeigt, wie ein HTML-Dokument konvertiert wird. Bitte laden Sie eine Datei aus dem lokalen Dateisystem, wählen Sie das Ausgabeformat und führen Sie das Beispiel aus. Sie erhalten sofort das Ergebnis. Sie können kostenlose Online-Konverter <a href="https://products.aspose.app/html/conversion/html" rel="opener noopener noreferrer" target="_blank">hier</a> ausprobieren

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML PDF DOCX MD BMP "JPG|JPEG" PNG GIF TIFF XPS>}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new HTMLDocument("input.{{input lower}}");
{{#if_output 'PDF'}}
    var options = new PdfSaveOptions();
{{/if_output}}
{{#if_output 'DOCX'}}
    var options = new DocSaveOptions();
{{/if_output}}
{{#if_output 'XPS'}}
    var options = new XpsSaveOptions();
{{/if_output}}
{{#if_output 'MD'}}
    var options = new MarkdownSaveOptions();
{{/if_output}}
{{#if_output 'BMP' 'JPG' 'GIF' 'PNG' 'TIFF'}}
    var options = new ImageSaveOptions(ImageFormat.{{output camel}});
{{/if_output}}
    Converter.ConvertHTML(document, options, "output.{{output lower}}");
{{< /app/html/converter>}}

{{<section documentation>}}
---
h2: ''
article1: Konvertieren Sie HTML in PDF
article2: Konvertieren Sie HTML in XPS
article3: Konvertieren Sie HTML in DOCX
article4: Konvertieren Sie HTML in MHTML
article5: Konvertieren Sie HTML in Markdown
article6: Konvertieren Sie HTML in BMP
article7: Konvertieren Sie HTML in PNG
article8: Konvertieren Sie HTML in JPG
article9: Konvertieren Sie HTML in TIFF
---

Das wichtigste Highlight der Aspose.HTML .NET API ist eine Konvertierungsfunktion. Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um verschiedene Formate für bestimmte Aufgaben zu nutzen. Der Namespace [Aspose.Html.Converters](https://reference.aspose.com/html/net/aspose.html.converters) implementiert einen einfachen Zugriff auf Konvertierungsmethoden. Es bietet eine breite Palette von HTML-Konvertierungen in gängige Formate wie PDF, XPS, DOCX, JPEG, PNG, BMP, TIFF, GIF, MHTML und MD. Bitte besuchen Sie das Dokumentationskapitel [Converting Between Formats](https://docs.aspose.com/html/net/converting-between-formats/), um mehr über Aspose.HTML für .NET-API-Konvertierungsfunktionen zu erfahren.

{{<section installing>}}
---
h2: Installieren von Aspose.HTML für die .NET-Bibliothek
---

Diese Bibliothek unterstützt das Parsen von HTML5, CSS3, SVG und HTML Canvas, um ein Document Object Model (DOM) basierend auf dem WHATWG DOM-Standard zu erstellen. Sie haben mehrere Möglichkeiten, die Aspose.HTML-Bibliothek für .NET auf Ihrem System zu installieren:</br>
1. Verwenden der NuGet Package Manager-GUI.
2. Verwenden der Paket-Manager-Konsole.
3. Installieren von Aspose.HTML für .NET über MSI.</br>



Weitere Einzelheiten zur Installation der C#-Bibliothek finden Sie in der [Aspose.HTML-Dokumentation](https://docs.aspose.com/html/net/getting-started/installation/).

{{<section other-conversions>}}
---
h2: Andere unterstützte Konvertierungen
---

Sie können auch HTML-, XHTML-, MHTML-, EPUB-, Markdown- und SVG-Dateien in viele andere Dateiformate konvertieren, darunter einige der unten aufgeführten: