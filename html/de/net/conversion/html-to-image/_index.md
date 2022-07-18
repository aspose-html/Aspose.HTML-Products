---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie HTML in C# in ein Bild - Online-Konvertierer für HTML in Bilder
description: Konvertieren Sie HTML in C# in ein Bild. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie kostenlos den Online-HTML-zu-Bild-Konverter aus!
url: /net/conversion/html-to-image/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: Image
otherformats: PDF DOCX XPS JPEG GIF PNG TIFF BMP XHTML MHTML MD
---

{{<section banner>}}
---
h1: Konvertieren Sie HTML in Bild über C#
h2: Generieren Sie ein Bild aus einer HTML-Quellseite mit der .NET-API. Konvertieren Sie HTML sofort in Bildformate mit unserem kostenlosen Online-Konverter!
---

{{<section overview>}}
---
h2: Konvertieren Sie HTML mit C# in ein Bild
---

HTML-Dateien werden häufig verwendet, um viele Informationen zu erstellen, zu bearbeiten oder zu kommunizieren. Wenn Sie HTML-Dateien in eine PowerPoint-Präsentation einfügen oder per E-Mail versenden möchten, konvertieren Sie sie bitte in das entsprechende Bildformat und verwenden Sie sie wie Sie möchten! Mit der API [Aspose.HTML for .NET](https://products.aspose.com/html/net/) können Sie HTML programmgesteuert in Bilder umwandeln und dabei die volle Kontrolle über eine Vielzahl von Konvertierungsparametern haben. Es gibt verschiedene Fälle für die HTML-zu-Bild-Konvertierung, z. B. das Lesen von HTML aus einer Datei, einer URL, einem WYSISYG-Editor, einer Zeichenfolge oder einem Stream. Mit der leistungsstarken C#-API können Sie HTML schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der HTML-zu-Bild-Konvertierung direkt in Ihrem Browser! Bitte laden Sie eine HTML-Datei aus dem lokalen Dateisystem, wählen Sie das gewünschte Ausgabeformat aus der Liste und führen Sie das Beispiel aus. Es ist schnell, einfach, sicher und völlig kostenlos! Die HTML-zu-Bild-Konvertierung erfolgt mit den Standardspeicheroptionen. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie also schnell jede Webseite oder HTML in das Bildformat online!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML "JPG|JPEG" BMP PDF MD  GIF DOCX XPS TIFF PNG MHTML >}}
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
h2: Schritte zum Konvertieren von HTML in Bilder in C#
---

Wenn Sie die Konvertierungsfunktionalität in Ihrem Produkt in Betracht ziehen oder HTML programmgesteuert in Bild konvertieren möchten, sehen Sie sich bitte das obige C#-Codebeispiel an oder lesen Sie das Kapitel Dokumentation. In allen Fällen erfordert jede Konvertierung einige obligatorische Schritte:
1. Laden Sie ein HTML-Dokument mit einem der [HTMLDocument()](https://apireference.aspose.com/html/net/aspose.html/htmldocument)-Konstruktoren. Sie können HTML aus einer Datei, einem HTML-Code, einem Stream oder einer URL laden.
1. Erstellen Sie ein neues [ImageSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions)-Objekt und geben Sie ImageFormat an. Standardmäßig ist die Format-Eigenschaft PNG.
1. Verwenden Sie die Methode [ConvertHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) der Converter-Klasse, um HTML als Bilddatei zu speichern. Sie müssen HTMLDocument, ImageSaveOptions und den Ausgabedateipfad an die ConvertHTML()-Methode übergeben.
1. Die Bilddatei wird im angegebenen Pfad gespeichert.




{{<section documentation>}}
---
h2: HTML-zu-Bild-Konvertierung in der Dokumentation
---

 - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#html-to-jpg-durch-eine-einzelne-codezeile " target="_blank">HTML in JPG durch eine einzige Codezeile</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#convert-html-to-jpg-using-imagesaveoptions" target="_blank" >Konvertieren Sie HTML in JPG mit ImageSaveOptions</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers" target="_blank">HTML in JPG konvertieren mit MemoryStreamProvider</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-png/" target="_blank">HTML in PNG konvertieren</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/" target="_blank">HTML in BMP konvertieren</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/" target="_blank">HTML in TIFF konvertieren</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/" target="_blank">HTML in GIF konvertieren</a>

Bitte besuchen Sie das Dokumentationskapitel [Converting Between Formats](https://docs.aspose.com/html/net/converting-between-formats/), um mehr über Aspose.HTML für .NET-API-Konvertierungsfunktionen zu erfahren und C#-Beispiele zu betrachten für die gängigsten HTML-zu-Bild-Konvertierungsszenarien. In den Artikeln finden Sie Informationen zum Konvertieren von HTML in Bilder mithilfe von ConvertHTML()-Methoden und zum Anwenden von ImageSaveOptions oder [ICreateStreamProvider](https://apireference.aspose.com/html/net/aspose.html.io/ icreatestreamprovider)-Parameter.

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