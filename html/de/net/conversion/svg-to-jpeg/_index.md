---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie SVG in JPEG
description: Konvertieren Sie SVG in C# in JPEG. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie den Online-SVG-zu-JPEG-Konverter kostenlos aus!
url: /net/conversion/svg-to-jpeg/
family: html
platformtag: net
feature: conversion
informat: SVG
outformat: JPEG
otherformats: PDF XPS GIF BMP PNG TIFF
---

{{<section banner>}}
---
h1: Konvertieren Sie SVG in JPEG über C#
h2: High-Fidelity-Konvertierung von SVG in JPEG mit serverseitigen .NET-APIs. Konvertieren Sie mit unserem kostenlosen Online-Konverter sofort SVG in das JPEG-Format!
---

{{<section overview>}}
---
h2: Konvertieren Sie SVG in JPEG mit C#
---

SVG ist eine XML-Sprache zum Erstellen von zweidimensionalen Vektor- und gemischten Vektor-/Rastergrafiken. Um SVG in JPEG zu konvertieren, verwenden wir die API [Aspose.HTML for .NET](https://products.aspose.com/html/net/), die eine funktionsreiche, leistungsstarke und einfach zu verwendende Dokumentbearbeitung ist und Konvertierungs-API für die C#-Plattform. Eine SVG-Konvertierung ist oft erforderlich, um andere Formate nutzen zu können. Mit unserer Dokumentverarbeitungsbibliothek können Sie mit nur wenigen Codezeilen SVG-Bilder programmgesteuert in JPEG-Bilder konvertieren und dabei die volle Kontrolle über verschiedene Konvertierungsoptionen behalten.

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der SVG-zu-JPEG-Konvertierung direkt in Ihrem Browser! Das folgende C#-Beispiel zeigt, wie ein SVG-Dokument konvertiert wird. Wir beschreiben den Quellcode zum Lesen von SVG aus einer Datei und zum anschließenden Konvertieren von SVG in JPEG mit Standardspeicheroptionen. Bitte laden Sie SVG aus dem lokalen Dateisystem, wählen Sie das Ausgabeformat und führen Sie das Beispiel aus. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie also schnell SVG in das JPEG-Format online!

{{<section "app-pluging" i18n-exclude>}}

{{< app/svg/converter SVG "JPG|JPEG" BMP TIFF PNG GIF XPS PDF>}}
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
h2: Schritte zum Konvertieren von SVG in JPEG in C#
---
1. Laden Sie eine SVG-Datei mit einem der SVGDocument()-Konstruktoren der [SVGDocument](https://reference.aspose.com/html/net/aspose.html.dom.svg/svgdocument/)-Klasse.
1. Erstellen Sie ein neues [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/)-Objekt mit JPEG ImageFormat. Standardmäßig ist die Format-Eigenschaft [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/).
1. Verwenden Sie die Methode [ConvertSVG()](https://reference.aspose.com/html/net/aspose.html.converters.converter/convertsvg/methods/3), um SVG als JPEG-Bild zu speichern. Sie müssen das SVGDocument, die ImageSaveOptions und den Pfad der Ausgabedatei an die Methode ConvertSVG() übergeben.

{{<section documentation>}}
---
h2: SVG-zu-JPEG-Konvertierung in der Dokumentation
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/#svg-to-jpg-durch-eine-einzelne-codezeile " target="_blank">SVG zu JPG durch eine einzige Codezeile</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/#convert-svg-to-jpg-using-imagesaveoptions" target="_blank" >Konvertieren Sie SVG in JPG mit ImageSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/#output-stream-providers" target="_blank">Konvertieren Sie SVG in JPG mit MemoryStreamProvider</a>

JPG ist eines der am häufigsten verwendeten Bildformate. Seine Einzigartigkeit ist der kontrollierte Qualitätsverlust während der Komprimierung. Daher wird es häufig zum Speichern und Versenden von grafischen digitalen Inhalten (Fotos, gescannte Kopien, digitalisierte Bilder) über das Internet verwendet. Daher kann es manchmal notwendig sein, SVG in JPEG zu konvertieren. Bitte besuchen Sie den Dokumentationsartikel [Convert SVG to JPG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und um C#-Beispiele für die gängigsten Konvertierungsszenarien von SVG in JPG zu betrachten. In dem Artikel finden Sie Informationen zum Konvertieren von SVG in JPG mit ConvertSVG()-Methoden und zum Anwenden von ImageSaveOptions.

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