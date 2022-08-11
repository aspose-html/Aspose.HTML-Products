---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie HTML in GIF
description: Konvertieren Sie HTML in GIF mit C#. HTML-Seite als GIF-Bild in C#-Code speichern. Probieren Sie den Online-HTML-zu-GIF-Konverter kostenlos aus!
url: /net/conversion/html-to-gif/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: GIF
otherformats: PDF DOCX XPS JPEG PNG TIFF BMP XHTML MHTML MD
---

{{<section banner>}}
---
h1: Konvertieren Sie HTML in GIF über C#
h2: Generieren Sie GIF aus der HTML-Quellseite mit der .NET-API. Konvertieren Sie HTML sofort in das GIF-Format mit unserem kostenlosen Online-Konverter!
---

{{<section overview>}}
---
h2: Konvertieren Sie HTML in GIF mit C#
---

HTML-Dateien werden häufig verwendet, um viele Informationen zu erstellen, zu bearbeiten oder zu kommunizieren. Wenn Sie HTML-Dateien in eine PowerPoint-Präsentation einfügen oder per E-Mail versenden möchten, konvertieren Sie sie bitte in das entsprechende Bildformat und verwenden Sie sie wie Sie möchten! Mit der API [Aspose.HTML for .NET](https://products.aspose.com/html/net/) können Sie HTML programmgesteuert in GIF umwandeln und dabei die volle Kontrolle über eine Vielzahl von Konvertierungsparametern haben. Es gibt verschiedene Fälle für die HTML-zu-GIF-Konvertierung, z. B. das Lesen aus einer Datei, einer URL, einem WYSISYG-Editor, einer Zeichenfolge oder einem Stream. Mit der leistungsstarken C#-API können Sie HTML schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der HTML-zu-GIF-Konvertierung direkt in Ihrem Browser! Bitte laden Sie eine HTML-Datei aus dem lokalen Dateisystem, wählen Sie das gewünschte Ausgabeformat aus der Liste und führen Sie das Beispiel aus. Es ist schnell, einfach, sicher und völlig kostenlos! Die HTML-zu-GIF-Konvertierung erfolgt mit den Standardspeicheroptionen. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie also schnell jede Webseite oder HTML in das GIF-Format online!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML GIF BMP PDF MD "JPG|JPEG" DOCX XPS TIFF PNG MHTML >}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new HTMLDocument("document.{{input lower}}");
{{#if_output 'PDF'}}
    var options = new PdfSaveOptions();
{{/if_output}}
{{#if_output 'MHTML'}}
    var options = new MHTMLSaveOptions();
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
    var options = new ImageSaveOptions(ImageFormat.{{output param2 camel}});
{{/if_output}}
    Converter.ConvertHTML(document, options, "output.{{output lower}}");   
{{< /app/html/converter>}} 


{{<section steps>}}
---
h2: Schritte zum Konvertieren von HTML in GIF in C#
---

Wenn Sie die Konvertierungsfunktionalität in Ihrem Produkt in Betracht ziehen oder HTML programmgesteuert in GIF konvertieren möchten, sehen Sie sich bitte das obige C#-Codebeispiel an oder lesen Sie das Kapitel Dokumentation. In allen Fällen erfordert jede Konvertierung einige obligatorische Schritte:
1. Laden Sie ein HTML-Dokument mit einem der [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/)-Konstruktoren. Sie können HTML aus einer Datei, einem HTML-Code, einem Stream oder einer URL laden.
1. Erstellen Sie ein neues [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/)-Objekt mit GIF ImageFormat. Standardmäßig ist die Format-Eigenschaft PNG.
1. Verwenden Sie die Methode [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) der Converter-Klasse, um HTML als GIF-Datei zu speichern. Sie müssen HTMLDocument, ImageSaveOptions und den Ausgabedateipfad an die ConvertHTML()-Methode übergeben.
1. Die GIF-Datei wird im angegebenen Pfad gespeichert.

{{<section documentation>}}
---
h2: HTML-zu-GIF-Konvertierung in der Dokumentation
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/#convert-html-to-gif" target="_blank">HTML konvertieren in GIF</a>
  - Ziel <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/#convert-html-to-gif-in-c-using-imagesaveoptions" target="_blank">HTML in GIF konvertieren mit ImageSaveOptions</a>

GIF ist ein beliebtes Bildformat, das animierte Bilder unterstützt und häufig beim Web-Publishing verwendet wird. Die HTML-zu-GIF-Konvertierung ermöglicht Ihnen, ein HTML-Dokument als GIF-Bild zu speichern. Bitte besuchen Sie den Dokumentationsartikel [Convert HTML to GIF,](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und um C#-Beispiele für die gängigsten HTML-zu-GIF-Konvertierungsszenarien zu betrachten. In diesem Artikel finden Sie Informationen zum Konvertieren von HTML in GIF mithilfe von ConvertHTML()-Methoden und zum Anwenden von ImageSaveOptions- und ICreateStreamProvider-Parametern.

{{<section online-converters>}}
---
h2: Kostenlose Online-Konverter
---

{{<section get-started>}}
---
h2: So installieren Sie Aspose.HTML für die .NET-Bibliothek
---

{{<section other-conversions>}}
---
title: Andere unterstützte HTML-Konvertierungen
subTitle: "Sie können HTML auch in viele andere Dateiformate konvertieren:"
---