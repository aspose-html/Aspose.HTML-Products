---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie MD in PDF – C#
description: C#-Beispielcode für die Umwandlung von MD in PDF. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie den Online-MD-zu-PDF-Konverter kostenlos aus!
url: /net/conversion/md-to-pdf/
family: html
platformtag: net
feature: conversion
informat: MD
outformat: PDF
otherformats: XPS DOCX JPEG BMP GIF PNG TIFF HTML
---

{{<section banner>}}
---
h1: Konvertieren Sie MD in PDF über C#
h2: High-Fidelity-MD-zu-PDF-Konvertierung mit serverseitigen .NET-APIs. Konvertieren Sie mit unserem kostenlosen Online-Konverter MD sofort in das PDF-Format!
---

{{<section overview>}}
---
h2: Konvertieren Sie MD in PDF mit C#
---

Um MD in PDF zu konvertieren, verwenden wir die API [Aspose.HTML for .NET](https://products.aspose.com/html/net/), die ein funktionsreiches, leistungsstarkes und einfach zu verwendendes Dokument ist Manipulations- und Konvertierungs-API für die C#-Plattform. Konvertierungen von Markdown in andere Formate durchlaufen die Markdown-zu-HTML-Konvertierungsphase. .NET-Entwickler können MD in nur wenigen Codezeilen einfach laden und in PDF konvertieren. Mit der leistungsstarken C#-API können Sie MD schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der Umwandlung von MD in PDF direkt in Ihrem Browser! Es ist schnell, einfach, sicher und völlig kostenlos! Das folgende C#-Beispiel zeigt, wie ein MD-Dokument konvertiert wird. Wir beschreiben den Quellcode zum Lesen von MD aus einer Datei und zum anschließenden Konvertieren von MD in PDF mit Standardspeicheroptionen. Bitte laden Sie MD aus dem lokalen Dateisystem, wählen Sie das Ausgabeformat und führen Sie das Beispiel aus. Das Ergebnis erhalten Sie sofort als separate Datei.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MD PDF DOCX "JPG|JPEG" GIF BMP XPS TIFF PNG >}}
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
h2: Schritte zum Konvertieren von MD in PDF in C#
---
1. Geben Sie einen Pfad zu einer Markdown-Quelldatei an.
1. Konvertieren Sie Markdown in HTML. Verwenden Sie die Methode [ConvertMarkdown(`sourcePath`)](https://apireference.aspose.com/html/net/aspose.html.converters.converter/convertmarkdown/methods/4), um Markdown als HTML-Dokument zu speichern.
1. Erstellen Sie ein neues [PdfSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions)-Objekt.
1. Verwenden Sie die Methode [ConvertHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/converthtml/), um das Zwischen-HTML-Dokument in eine PDF-Datei zu rendern. Sie müssen HTMLDocument, DocSaveOptions und den Ausgabedateipfad an die ConvertHTML()-Methode übergeben.




{{<section documentation>}}
---
h2: MD-zu-PDF-Konvertierung in der Dokumentation
---

Markdown wird häufig als Format für Dokumentationen und Readme-Dateien verwendet, da es das Schreiben in einem leicht lesbaren und leicht zu schreibenden Stil ermöglicht. Die Konvertierung von MD in PDF ist häufig erforderlich, um das PDF-Format für bestimmte Aufgaben zu nutzen. Bitte besuchen Sie den Dokumentationsartikel [Markdown in PDF konvertieren](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-pdf/), um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und C#-Beispiele für die gängigsten MD-zu-PDF-Konvertierungsszenarien zu betrachten. In dem Artikel finden Sie Informationen zum Konvertieren von Markdown in PDF mit ConvertMarkdown()-Methoden und zum Anwenden von PdfSaveOptions.
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-pdf/#convert-markdown-to-pdf" target="_blank">Markdown konvertieren in PDF</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-pdf/#convert-markdown-to-pdf-using-pdfsaveoptions" target="_blank" >Konvertieren Sie Markdown mit PdfSaveOptions in PDF</a>



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