---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie SVG in PDF
description: Konvertieren Sie SVG in C# in PDF. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie den Online-SVG-zu-PDF-Konverter kostenlos aus!
url: /net/conversion/svg-to-pdf/
family: html
platformtag: net
feature: conversion
informat: SVG
outformat: PDF
otherformats: XPS GIF JPEG PNG TIFF BMP
---

{{<section banner>}}
---
h1: Konvertieren Sie SVG in PDF über C#
h2: High-Fidelity-SVG-zu-PDF-Konvertierung mit serverseitigen .NET-APIs. Konvertieren Sie mit unserem kostenlosen Online-Konverter SVG sofort in das PDF-Format!
---

{{<section overview>}}
---
h2: Konvertieren Sie SVG in PDF mit C#
---

SVG ist eine XML-Sprache zum Erstellen von zweidimensionalen Vektor- und gemischten Vektor-/Rastergrafiken. Um SVG in PDF zu konvertieren, verwenden wir die API [Aspose.HTML for .NET](https://products.aspose.com/html/net/), die eine funktionsreiche, leistungsstarke und einfach zu verwendende Dokumentbearbeitung ist und Konvertierungs-API für die C#-Plattform. Eine SVG-Konvertierung ist oft erforderlich, um andere Formate nutzen zu können. Mit unserer Dokumentverarbeitungsbibliothek können Sie SVG mit nur wenigen Codezeilen programmgesteuert in PDF konvertieren und dabei die volle Kontrolle über verschiedene Konvertierungsoptionen haben.

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der Konvertierung von SVG in PDF direkt in Ihrem Browser! Das folgende C#-Beispiel zeigt, wie ein SVG-Dokument konvertiert wird. Wir beschreiben den Quellcode zum Lesen von SVG aus einer Datei und zum anschließenden Konvertieren von SVG in PDF mit Standardspeicheroptionen. Bitte laden Sie SVG aus dem lokalen Dateisystem, wählen Sie das Ausgabeformat und führen Sie das Beispiel aus. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie SVG also schnell online in das PDF-Format!

{{<section "app-pluging" i18n-exclude>}}

{{< app/svg/converter SVG PDF  XPS TIFF PNG BMP "JPG|JPEG" GIF>}}
using Aspose.Html;
using Aspose.Html.Dom.Svg;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new SVGDocument("image.svg");
{{#if_output 'PDF'}}
    var options = new PdfSaveOptions();
{{/if_output}}
{{#if_output 'XPS'}}
    var options = new XpsSaveOptions();
{{/if_output}}
{{#if_output 'BMP' 'JPG' 'GIF' 'PNG' 'TIFF'}}
    var options = new ImageSaveOptions(ImageFormat.{{output param2 camel}});
{{/if_output}}
    Converter.ConvertSVG(document, options, "output.{{output lower}}");   
{{< /app/svg/converter>}}


{{<section steps>}}
---
h2: Schritte zum Konvertieren von SVG in PDF in C#
---
1. Laden Sie eine SVG-Datei mit einem der SVGDocument()-Konstruktoren der [SVGDocument](https://apireference.aspose.com/html/net/aspose.html.dom.svg/svgdocument)-Klasse.
1. Erstellen Sie ein neues [PdfSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions)-Objekt.
1. Verwenden Sie die Methode [ConvertSVG()](https://apireference.aspose.com/html/net/aspose.html.converters.converter/convertsvg/methods/3), um SVG als PDF-Datei zu speichern. Sie müssen das SVGDocument, PdfSaveOptions und den Ausgabedateipfad an die Methode ConvertSVG() übergeben.




{{<section documentation>}}
---
h2: SVG-zu-PDF-Konvertierung in der Dokumentation
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#svg-to-pdf-durch-eine-einzelne-codezeile " target="_blank">SVG zu PDF durch eine einzige Codezeile</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#convert-svg-to-pdf-using-pdfsaveoptions" target="_blank" >Konvertieren Sie SVG in PDF mit PdfSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#output-stream-providers" target="_blank">Konvertieren Sie SVG in PDF mit MemoryStreamProvider</a>

Die Konvertierung von SVG in PDF ist häufig erforderlich, um einen eingeschränkten Zugriff auf die Bearbeitung oder das Kopieren von Dokumenten einzurichten, offizielle Dokumente zu erstellen oder bestimmte Informationen beispielsweise per E-Mail zu versenden. Bitte besuchen Sie den Dokumentationsartikel [SVG in PDF konvertieren](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/), um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und um C#-Beispiele für die gängigsten Konvertierungsszenarien von SVG in PDF zu betrachten. In dem Artikel finden Sie Informationen zum Konvertieren von SVG in PDF mit ConvertSVG()-Methoden und zum Anwenden von PdfSaveOptions.

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
title: Andere unterstützte SVG-Konvertierungen
subTitle: "Sie können SVG auch in viele andere Dateiformate konvertieren:"
---