---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie Markdown in BMP
description: C#-Beispielcode für die Konvertierung von MD in BMP. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie den Online-MD-zu-BMP-Konverter kostenlos aus!
url: /net/conversion/md-to-bmp/
family: html
platformtag: net
feature: conversion
informat: MD
outformat: BMP
otherformats: PDF DOCX XPS GIF JPEG PNG TIFF HTML
---

{{<section banner>}}
---
h1: Konvertieren Sie MD über C# in BMP
h2: High-Fidelity-MD-zu-BMP-Konvertierung mit serverseitigen .NET-APIs. Konvertieren Sie MD sofort in das BMP-Format mit unserem kostenlosen Online-Konverter!
---

{{<section overview>}}
---
h2: Konvertieren Sie MD in BMP mit C#
---

Um MD in BMP umzuwandeln, verwenden wir die API [Aspose.HTML for .NET,](https://products.aspose.com/html/net/) die ein funktionsreiches, leistungsstarkes und benutzerfreundliches Dokument ist Manipulations- und Konvertierungs-API für die C#-Plattform. Konvertierungen von Markdown in andere Formate durchlaufen die Markdown-zu-HTML-Konvertierungsphase. .NET-Entwickler können MD in nur wenigen Codezeilen einfach laden und in BMP konvertieren. Mit der leistungsstarken C#-API können Sie MD schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der MD-zu-BMP-Konvertierung direkt in Ihrem Browser! Es ist schnell, einfach, sicher und völlig kostenlos! Das folgende C#-Beispiel zeigt, wie ein MD-Dokument konvertiert wird. Wir beschreiben den Quellcode zum Lesen von MD aus einer Datei und anschließendes Konvertieren von MD in BMP mit Standardspeicheroptionen. Bitte laden Sie MD aus dem lokalen Dateisystem, wählen Sie das Ausgabeformat und führen Sie das Beispiel aus. Das Ergebnis erhalten Sie sofort als separate Datei.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MD BMP XPS TIFF PNG PDF "JPG|JPEG" GIF DOCX >}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = Converter.ConvertMarkdown("input.md");
{{#if_output 'PDF'}}
    var options = new PdfSaveOptions();
{{/if_output}}
{{#if_output 'DOCX'}}
    var options = new DocSaveOptions();
{{/if_output}}
{{#if_output 'XPS'}}
    var options = new XpsSaveOptions();
{{/if_output}}
{{#if_output 'BMP' 'JPG' 'GIF' 'PNG' 'TIFF'}}
    var options = new ImageSaveOptions(ImageFormat.{{output param2 camel}});
{{/if_output}}
    Converter.ConvertHTML(document, options, "output.{{output lower}}");   
{{< /app/html/converter>}}


{{<section steps>}}
---
h2: Schritte zum Konvertieren von MD in BMP in C#
---
1. Geben Sie einen Pfad zu einer Markdown-Quelldatei an.
1. Konvertieren Sie Markdown in HTML. Verwenden Sie die Methode [ConvertMarkdown(`sourcePath`)](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertmarkdown/#convertmarkdown_4), um Markdown als HTML-Dokument zu speichern.
1. Erstellen Sie ein neues [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/)-Objekt mit BMP ImageFormat. Standardmäßig ist die Format-Eigenschaft [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/).
1. Verwenden Sie die Methode [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/), um das zwischengeschaltete HTML-Dokument in ein BMP-Bild zu rendern. Sie müssen HTMLDocument, ImageSaveOptions und den Ausgabedateipfad an die ConvertHTML()-Methode übergeben.

{{<section documentation>}}
---
h2: MD-zu-BMP-Konvertierung in der Dokumentation
---

BMP-Dateien sind Bitmap-Bilddateien, die zum Speichern hochwertiger digitaler Bitmap-Bilder verwendet werden. Daher kann es manchmal notwendig sein, MD in ein BMP-Bild zu konvertieren. Bitte besuchen Sie den Dokumentationsartikel [Markdown in Bild konvertieren](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/), um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und um C#-Beispiele für die gängigsten MD-zu-BMP-Konvertierungsszenarien zu betrachten. In dem Artikel finden Sie Informationen zum <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/#convert-markdown-to-bmp " target="_blank">Konvertieren Sie Markdown in BMP</a> mit ConvertMarkdown()-Methoden und wie Sie ImageSaveOptions anwenden.

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
title: Andere unterstützte MD-Konvertierungen
subTitle: "Sie können MD auch in viele andere Dateiformate konvertieren:"
---