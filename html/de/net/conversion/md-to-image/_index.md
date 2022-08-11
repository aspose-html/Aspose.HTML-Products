---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie MD in Image
description: C#-Beispielcode für die Umwandlung von MD in Bild. Probieren Sie den Online-MD-zu-Bild-Konverter kostenlos aus!
url: /net/conversion/md-to-image/
family: html
platformtag: net
feature: conversion
informat: MD
outformat: Image
otherformats: PDF DOCX XPS JPEG BMP GIF PNG TIFF HTML
howto: howtoMd
---

{{<section banner>}}
---
h1: Konvertieren Sie MD über C# in ein Bild
h2: High-Fidelity-MD-zu-Bild-Konvertierung mit serverseitigen .NET-APIs. Konvertieren Sie mit unserem kostenlosen Online-Konverter sofort MD in das Bildformat!
---

{{<section overview>}}
---
h2: Konvertieren Sie MD in ein Image mit C#
---

Um MD in Image umzuwandeln, verwenden wir die API [Aspose.HTML for .NET](https://products.aspose.com/html/net/), die ein funktionsreiches, leistungsstarkes und benutzerfreundliches Dokument ist Manipulations- und Konvertierungs-API für die C#-Plattform. Konvertierungen von Markdown in andere Formate durchlaufen die Markdown-zu-HTML-Konvertierungsphase. .NET-Entwickler können MD in nur wenigen Codezeilen einfach laden und in Image konvertieren. Mit der leistungsstarken C#-API können Sie MD schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der MD-zu-Bild-Konvertierung direkt in Ihrem Browser! Es ist schnell, einfach, sicher und völlig kostenlos! Das folgende C#-Beispiel zeigt, wie ein MD-Dokument konvertiert wird. Wir beschreiben den Quellcode zum Lesen von MD aus einer Datei und zum anschließenden Konvertieren von MD in ein Rasterbild mit Standardspeicheroptionen. Bitte laden Sie MD aus dem lokalen Dateisystem, wählen Sie das Ausgabeformat und führen Sie das Beispiel aus. Das Ergebnis erhalten Sie sofort als separate Datei.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MD "JPG|JPEG" GIF BMP XPS TIFF PNG PDF DOCX >}}
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
h2: Schritte zum Konvertieren von MD in ein Bild in C#
---
1. Geben Sie einen Pfad zu einer Markdown-Quelldatei an.
1. Konvertieren Sie Markdown in HTML. Verwenden Sie die Methode [ConvertMarkdown(`sourcePath`)](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertmarkdown/#convertmarkdown_4), um Markdown als HTML-Dokument zu speichern.
1. Erstellen Sie ein neues [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/)-Objekt und geben Sie ImageFormat an. Standardmäßig ist die Format-Eigenschaft [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/).
1. Verwenden Sie die Methode [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/), um das zwischengeschaltete HTML-Dokument in ein Bild zu rendern. Sie müssen HTMLDocument, ImageSaveOptions und den Ausgabedateipfad an die ConvertHTML()-Methode übergeben.

{{<section documentation>}}
---
h2: MD-zu-Bild-Konvertierung in der Dokumentation
---

Markdown ist eine allgemein anerkannte Auszeichnungssprache, die häufig als Format für Dokumentationen und Readme-Dateien verwendet wird. Mit der Aspose.HTML .NET-Bibliothek können Sie Markdown über C# in Bildformate wie JPG, PNG, GIF, TIFF und BMP konvertieren. Bitte besuchen Sie den Dokumentationsartikel [Markdown in Bild konvertieren,](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) um mehr über die API-Konvertierungsfunktionen zu erfahren und zu berücksichtigen C#-Beispiele für die gängigsten MD-zu-Image-Konvertierungsszenarien. In dem Artikel finden Sie Informationen zum Konvertieren von Markdown in Bild mithilfe von ConvertMarkdown()-Methoden und zum Anwenden von ImageSaveOptions.
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/#convert-markdown-to-jpg" target="_blank">Markdown konvertieren in JPG</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/#convert-markdown-to-png" target="_blank">Markdown konvertieren in PNG</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/#convert-markdown-to-bmp" target="_blank">Markdown konvertieren in BMP</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/#convert-markdown-to-gif" target="_blank">Markdown konvertieren in GIF</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/#convert-markdown-to-tiff" target="_blank">Markdown konvertieren in TIFF</a>



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