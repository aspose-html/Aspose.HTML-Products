---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie HTML in PNG
description: Konvertieren Sie HTML in C# in PNG. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie kostenlos den Online-HTML-zu-PNG-Konverter aus!
url: /net/conversion/html-to-png/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: PNG
otherformats: PDF DOCX XPS JPEG GIF PNG TIFF BMP XHTML MHTML MD
---

{{<section banner>}}
---
h1: Konvertieren Sie HTML in PNG über C#
h2: Generieren Sie PNG aus der HTML-Quellseite mit der .NET-API. Konvertieren Sie mit unserem kostenlosen Online-Konverter sofort HTML in das PNG-Format!
---

{{<section overview>}}
---
h2: Konvertieren Sie HTML in PNG mit C#
---

HTML-Dateien werden häufig verwendet, um viele Informationen zu erstellen, zu bearbeiten oder zu kommunizieren. Wenn Sie HTML-Dateien in eine PowerPoint-Präsentation einfügen oder per E-Mail versenden möchten, konvertieren Sie sie bitte in das entsprechende Bildformat und verwenden Sie sie wie Sie möchten! Mit der API [Aspose.HTML for .NET](https://products.aspose.com/html/net/) können Sie HTML programmgesteuert in PNG umwandeln und dabei die volle Kontrolle über eine Vielzahl von Konvertierungsparametern haben. Es gibt verschiedene Fälle für die HTML-zu-PNG-Konvertierung, z. B. das Lesen aus einer Datei, einer URL, einem WYSISYG-Editor, einer Zeichenfolge oder einem Stream. Mit der leistungsstarken C#-API können Sie HTML schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der HTML-zu-PNG-Konvertierung direkt in Ihrem Browser! Bitte laden Sie eine HTML-Datei aus dem lokalen Dateisystem, wählen Sie das gewünschte Ausgabeformat aus der Liste und führen Sie das Beispiel aus. Es ist schnell, einfach, sicher und völlig kostenlos! Die HTML-zu-PNG-Konvertierung erfolgt mit den Standardspeicheroptionen. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie also schnell jede Webseite oder HTML in das PNG-Format online!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML PNG "JPG|JPEG" BMP PDF MD GIF DOCX XPS TIFF MHTML >}}
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
h2: Schritte zum Konvertieren von HTML in PNG in C#
---

Wenn Sie die Konvertierungsfunktionalität in Ihrem Produkt in Betracht ziehen oder HTML programmgesteuert in PNG konvertieren möchten, sehen Sie sich bitte das obige C#-Codebeispiel an oder lesen Sie das Kapitel Dokumentation. In allen Fällen erfordert jede Konvertierung einige obligatorische Schritte:
1. Laden Sie ein HTML-Dokument mit einem der [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/)-Konstruktoren. Sie können HTML aus einer Datei, einem HTML-Code, einem Stream oder einer URL laden.
1. Erstellen Sie ein neues [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/)-Objekt.
1. Verwenden Sie die Methode [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) der Converter-Klasse, um HTML als PNG-Datei zu speichern. Sie müssen HTMLDocument, ImageSaveOptions und den Ausgabedateipfad an die ConvertHTML()-Methode übergeben.
1. Die PNG-Datei wird im angegebenen Pfad gespeichert.

{{<section documentation>}}
---
h2: HTML-zu-PNG-Konvertierung in der Dokumentation
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-png/#html-to-png-durch-eine-einzelne-codezeile " target="_blank">HTML in PNG durch eine einzige Codezeile</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-png/#convert-html-to-png-using-imagesaveoptions" target="_blank" >Konvertieren Sie HTML in PNG mit ImageSaveOptions</a>
   - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-png/#output-stream-providers" target="_blank">HTML in PNG konvertieren mit MemoryStreamProvider</a>

PNG ist eines der am häufigsten verwendeten Bilddateiformate. Es unterstützt verlustfreie Bildkomprimierung, was es bei seinen Benutzern beliebt macht. Das Konvertieren von HTML-Dateien in das PNG-Bild kann beispielsweise erforderlich sein, wenn Sie eine Webseite in eine PowerPoint-Präsentation einfügen, in einen Blog für Ihre Leser einfügen oder per E-Mail versenden möchten. Bitte besuchen Sie den Dokumentationsartikel [Convert HTML to PNG,](https://docs.aspose.com/html/net/converting-between-formats/html-to-png/) um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und um C#-Beispiele für die gängigsten HTML-zu-PNG-Konvertierungsszenarien zu betrachten. In diesem Artikel finden Sie Informationen zum Konvertieren von HTML in PNG mithilfe von ConvertHTML()-Methoden und zum Anwenden von ImageSaveOptions- und ICreateStreamProvider-Parametern.

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