---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie HTML in PDF
description: Konvertieren Sie HTML in PDF mit C#. HTML-Seite als PDF in C#-Code speichern. Probieren Sie den Online-HTML-zu-PDF-Konverter kostenlos aus!
url: /net/conversion/html-to-pdf/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: PDF
otherformats: DOCX XPS GIF JPEG PNG TIFF BMP XHTML MHTML MD
---

{{<section banner>}}
---
h1: Konvertieren Sie HTML in PDF über C#
h2: Generieren Sie PDF aus einer HTML-Quellseite mit der .NET-API. Konvertieren Sie mit unserem kostenlosen Online-Konverter HTML sofort in das PDF-Format.
---

{{<section overview>}}
---
h2: Konvertieren Sie HTML in PDF mit C#
---

HTML-Dateien werden häufig verwendet, um viele Informationen zu erstellen, zu bearbeiten oder zu kommunizieren. Das Konvertieren von HTML in PDF ist häufig erforderlich, um Dokumente vor unerwünschtem Bearbeiten und Kopieren zu schützen, Dokumente zum Drucken oder Versenden per E-Mail vorzubereiten usw. Mit [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API können Sie HTML programmgesteuert in PDF umwandeln und dabei die volle Kontrolle über eine Vielzahl von Konvertierungsparametern haben. Es gibt verschiedene Fälle für die Konvertierung von HTML in PDF, z. B. das Lesen aus einer Datei, einer URL, einem WYSISYG-Editor, einer Zeichenfolge oder einem Stream. Mit der leistungsstarken C#-API können Sie HTML schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der Konvertierung von HTML in PDF direkt in Ihrem Browser! Bitte laden Sie eine HTML-Datei aus dem lokalen Dateisystem, wählen Sie das gewünschte Ausgabeformat aus der Liste und führen Sie das Beispiel aus. Es ist schnell, einfach, sicher und völlig kostenlos! Die HTML-zu-PDF-Konvertierung erfolgt mit den Standardspeicheroptionen. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie also schnell jede Webseite oder HTML in das PDF-Format online!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML PDF MD "JPG|JPEG" GIF DOCX BMP XPS TIFF PNG MHTML >}}
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
h2: Schritte zum Konvertieren von HTML in PDF in C#
---

Wenn Sie die Konvertierungsfunktionalität in Ihrem Produkt in Betracht ziehen oder HTML programmgesteuert in PDF konvertieren möchten, sehen Sie sich bitte das obige C#-Codebeispiel an oder lesen Sie das Kapitel Dokumentation. In allen Fällen erfordert jede Konvertierung einige obligatorische Schritte:
1. Laden Sie ein HTML-Dokument mit einem der [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/)-Konstruktoren. Sie können HTML aus einer Datei, einem HTML-Code, einem Stream oder einer URL laden.
1. Erstellen Sie ein neues [PdfSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions/)-Objekt.
1. Verwenden Sie die Methode [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) der Converter-Klasse, um HTML als PDF-Datei zu speichern. Sie müssen HTMLDocument, PdfSaveOptions und den Ausgabedateipfad an die ConvertHTML()-Methode übergeben.
1. Die PDF-Datei wird im angegebenen Pfad gespeichert.

{{<section documentation>}}
---
h2: HTML-zu-PDF-Konvertierung in der Dokumentation
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#html-to-pdf-durch-eine-einzelne-codezeile " target="_blank">Konvertieren Sie HTML in PDF mit einer einzigen Codezeile</a>
  - Ziel <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-in-c-using-pdfsaveoptions" target="_blank">HTML in PDF konvertieren mit PdfSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#output-stream-providers" target="_blank">HTML in PDF konvertieren mit MemoryStreamProvider</a>

HTML-Dateien werden häufig verwendet, um viele Informationen zu erstellen, zu bearbeiten oder zu kommunizieren. Die Konvertierung von HTML in PDF ist häufig erforderlich, um Dokumente vor unerwünschtem Bearbeiten oder Kopieren zu schützen, offizielle Dokumentationen zu erstellen, Dateien zum Drucken oder Versenden per E-Mail vorzubereiten usw. Bitte besuchen Sie den Dokumentationsartikel [HTML in PDF konvertieren,](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) um mehr über Aspose.HTML für .NET-API-Konvertierungsfunktionen zu erfahren und C#-Beispiele für die gängigsten HTML-zu-PDF-Konvertierungsszenarien zu betrachten. In diesem Artikel finden Sie Informationen zum Konvertieren von HTML in PDF mithilfe von ConvertHTML()-Methoden und zum Anwenden von PdfSaveOptions- und ICreateStreamProvider-Parametern.

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