---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie MD in GIF – C#
description: C#-Beispielcode für die Umwandlung von MD in GIF. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie den Online-MD-zu-GIF-Konverter kostenlos aus!
url: /net/conversion/md-to-gif/
family: html
platformtag: net
feature: conversion
informat: MD
outformat: GIF
otherformats: PDF DOCX XPS BMP JPEG PNG TIFF HTML
howto: howtoMd
---

{{<section banner>}}
---
h1: Konvertieren Sie MD in GIF über C#
h2: High-Fidelity-MD-zu-GIF-Konvertierung mit serverseitigen .NET-APIs. Konvertieren Sie mit unserem kostenlosen Online-Konverter sofort MD in das GIF-Format!
---

{{<section overview>}}
---
h2: Konvertieren Sie MD in GIF mit C#
---

Um MD in GIF umzuwandeln, verwenden wir die API [Aspose.HTML for .NET](https://products.aspose.com/html/net/), ein funktionsreiches, leistungsstarkes und benutzerfreundliches Dokument Manipulations- und Konvertierungs-API für die C#-Plattform. Konvertierungen von Markdown in andere Formate durchlaufen die Markdown-zu-HTML-Konvertierungsphase. .NET-Entwickler können MD in nur wenigen Codezeilen einfach laden und in GIF konvertieren. Mit der leistungsstarken C#-API können Sie MD schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der Umwandlung von MD in GIF direkt in Ihrem Browser! Es ist schnell, einfach, sicher und völlig kostenlos! Das folgende C#-Beispiel zeigt, wie ein MD-Dokument konvertiert wird. Wir beschreiben den Quellcode zum Lesen von MD aus einer Datei und zum anschließenden Konvertieren von MD in GIF mit Standardspeicheroptionen. Bitte laden Sie MD aus dem lokalen Dateisystem, wählen Sie das Ausgabeformat und führen Sie das Beispiel aus. Das Ergebnis erhalten Sie sofort als separate Datei.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MD GIF BMP XPS TIFF PNG PDF "JPG|JPEG" DOCX >}}
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
h2: Schritte zum Konvertieren von MD in GIF in C#
---
1. Geben Sie einen Pfad zu einer Markdown-Quelldatei an.
1. Konvertieren Sie Markdown in HTML. Verwenden Sie die Methode [ConvertMarkdown(`sourcePath`)](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertmarkdown/#convertmarkdown_4), um Markdown als HTML-Dokument zu speichern.
1. Erstellen Sie ein neues [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/)-Objekt mit GIF ImageFormat. Standardmäßig ist die Format-Eigenschaft [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/).
1. Verwenden Sie die Methode [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/), um das zwischengeschaltete HTML-Dokument in ein GIF-Bild zu rendern. Sie müssen HTMLDocument, ImageSaveOptions und den Ausgabedateipfad an die ConvertHTML()-Methode übergeben.

{{<section documentation>}}
---
h2: Konvertierung von MD in GIF in der Dokumentation
---

GIF ist ein beliebtes Bildformat, das häufig beim Web-Publishing verwendet wird. Die MD-zu-GIF-Konvertierung ermöglicht es Ihnen, ein Markdown-Dokument als GIF-Bild zu speichern. Bitte besuchen Sie den Dokumentationsartikel [Markdown in Bild konvertieren](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/), um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und um C#-Beispiele für die gängigsten MD-zu-GIF-Konvertierungsszenarien zu betrachten. In dem Artikel finden Sie Informationen zum <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/#convert-markdown-to-gif " target="_blank">Konvertiere Markdown in GIF</a> mit ConvertMarkdown()-Methoden und wie man ImageSaveOptions anwendet.

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