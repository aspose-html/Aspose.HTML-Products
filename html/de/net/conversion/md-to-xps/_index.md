---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie MD in XPS
description: C#-Beispielcode für die Konvertierung von MD in XPS. Probieren Sie den Online-MD-zu-XPS-Konverter kostenlos aus!
url: /net/conversion/md-to-xps/
family: html
platformtag: net
feature: conversion
informat: MD
outformat: XPS
otherformats: PDF DOCX JPEG BMP GIF PNG TIFF HTML
howto: howtoMd
---

{{<section banner>}}
---
h1: Konvertieren Sie MD über C# in XPS
h2: High-Fidelity-MD-zu-XPS-Konvertierung mit serverseitigen .NET-APIs. Konvertieren Sie MD sofort in das XPS-Format mit unserem kostenlosen Online-Konverter!
---

{{<section overview>}}
---
h2: Konvertieren Sie MD in XPS mit C#
---

Um MD in XPS zu konvertieren, verwenden wir die API [Aspose.HTML for .NET](https://products.aspose.com/html/net/), die ein funktionsreiches, leistungsstarkes und benutzerfreundliches Dokument ist Manipulations- und Konvertierungs-API für die C#-Plattform. Konvertierungen von Markdown in andere Formate durchlaufen die Markdown-zu-HTML-Konvertierungsphase. .NET-Entwickler können MD in nur wenigen Codezeilen einfach laden und in XPS konvertieren. Mit der leistungsstarken C#-API können Sie MD schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der Umwandlung von MD in XPS direkt in Ihrem Browser! Es ist schnell, einfach, sicher und völlig kostenlos! Das folgende C#-Beispiel zeigt, wie ein MD-Dokument konvertiert wird. Wir beschreiben den Quellcode zum Lesen von MD aus einer Datei und zum anschließenden Konvertieren von MD in XPS mit Standardspeicheroptionen. Bitte laden Sie MD aus dem lokalen Dateisystem, wählen Sie das Ausgabeformat und führen Sie das Beispiel aus. Das Ergebnis erhalten Sie sofort als separate Datei.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MD XPS DOCX "JPG|JPEG" GIF BMP TIFF PNG PDF >}}
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
h2: Schritte zum Konvertieren von MD in XPS in C#
---
1. Geben Sie einen Pfad zu einer Markdown-Quelldatei an.
1. Konvertieren Sie Markdown in HTML. Verwenden Sie die Methode [ConvertMarkdown(`sourcePath`)](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertmarkdown/#convertmarkdown_4), um Markdown als HTML-Dokument zu speichern.
1. Erstellen Sie ein neues [XpsSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/xpssaveoptions/)-Objekt.
1. Verwenden Sie die Methode [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/), um das Zwischen-HTML-Dokument in eine XPS-Datei zu rendern. Sie müssen HTMLDocument, DocSaveOptions und den Ausgabedateipfad an die ConvertHTML()-Methode übergeben.

{{<section documentation>}}
---
h2: MD-zu-XPS-Konvertierung in der Dokumentation
---

 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-xps/#convert-markdown-to-xps" target="_blank">Markdown konvertieren in XPS</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-xps/#convert-markdown-to-xps-using-xpssaveoptions" target="_blank" >Konvertieren Sie Markdown mit XpsSaveOptions in XPS</a>

Markdown wird häufig als Format für Dokumentationen und Readme-Dateien verwendet, da es das Schreiben in einem leicht lesbaren und leicht zu schreibenden Stil ermöglicht. XPS ist ein von Microsoft entwickeltes Format zum Speichern und Anzeigen von Dokumenten. Es hat eine Reihe von Vorteilen, die Sicherheitsfunktionen unterstützen, wie z. B. digitale Signaturen für mehr Dokumentensicherheit und mehr. Die Konvertierung von MD in XPS ist oft erforderlich, um das XPS-Format für bestimmte Aufgaben zu nutzen. Bitte besuchen Sie den Dokumentationsartikel [Markdown in XPS konvertieren](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-xps/), um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und C#-Beispiele für die gängigsten MD-zu-XPS-Konvertierungsszenarien zu betrachten. In dem Artikel finden Sie Informationen zum Konvertieren von Markdown in XPS mithilfe von ConvertMarkdown()-Methoden und zum Anwenden von XpsSaveOptions.

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