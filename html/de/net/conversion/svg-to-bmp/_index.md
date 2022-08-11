---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie SVG in BMP
description: Konvertieren Sie SVG in BMP mit C#. SVG als BMP-Bild in C#-Code speichern. Probieren Sie den Online-SVG-zu-BMP-Konverter kostenlos aus!
url: /net/conversion/svg-to-bmp/
family: html
platformtag: net
feature: conversion
informat: SVG
outformat: BMP
otherformats: PDF XPS GIF JPEG PNG TIFF
---

{{<section banner>}}
---
h1: Konvertieren Sie SVG in BMP über C#
h2: High-Fidelity-SVG-zu-BMP-Konvertierung mit serverseitigen .NET-APIs. Konvertieren Sie mit unserem kostenlosen Online-Konverter sofort SVG in das BMP-Format!
---

{{<section overview>}}
---
h2: Konvertieren Sie SVG in BMP mit C#
---

SVG ist eine XML-Sprache zum Erstellen von zweidimensionalen Vektor- und gemischten Vektor-/Rastergrafiken. Um SVG in BMP umzuwandeln, verwenden wir die API [Aspose.HTML for .NET](https://products.aspose.com/html/net/), die eine funktionsreiche, leistungsstarke und einfach zu verwendende Dokumentbearbeitung ist und Konvertierungs-API für die C#-Plattform. Eine SVG-Konvertierung ist oft erforderlich, um andere Formate nutzen zu können. Mit unserer Dokumentverarbeitungsbibliothek können Sie SVG mit nur wenigen Codezeilen programmgesteuert in BMP-Bilder konvertieren und dabei die volle Kontrolle über verschiedene Konvertierungsoptionen haben.

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der SVG-zu-BMP-Konvertierung direkt in Ihrem Browser! Das folgende C#-Beispiel zeigt, wie ein SVG-Dokument konvertiert wird. Wir beschreiben den Quellcode zum Lesen von SVG aus einer Datei und zum anschließenden Konvertieren von SVG in BMP mit Standardspeicheroptionen. Bitte laden Sie SVG aus dem lokalen Dateisystem, wählen Sie das Ausgabeformat und führen Sie das Beispiel aus. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie SVG also schnell online in das BMP-Format!

{{<section "app-pluging" i18n-exclude>}}

{{< app/svg/converter SVG BMP XPS TIFF PNG PDF "JPG|JPEG" GIF>}}
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
h2: Schritte zum Konvertieren von SVG in BMP in C#
---
1. Laden Sie eine SVG-Datei mit einem der SVGDocument()-Konstruktoren der [SVGDocument](https://reference.aspose.com/html/net/aspose.html.dom.svg/svgdocument)-Klasse.
1. Erstellen Sie ein neues [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/)-Objekt mit BMP ImageFormat. Standardmäßig ist die Format-Eigenschaft [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/).
1. Verwenden Sie die Methode [ConvertSVG()](https://reference.aspose.com/html/net/aspose.html.converters.converter/convertsvg/methods/3), um SVG als BMP-Bild zu speichern. Sie müssen das SVGDocument, die ImageSaveOptions und den Pfad der Ausgabedatei an die Methode ConvertSVG() übergeben.

{{<section documentation>}}
---
h2: SVG-zu-BMP-Konvertierung in der Dokumentation
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/#convert-svg-to-bmp" target="_blank">SVG konvertieren in BMP</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/#convert-svg-to-bmp-using-imagesaveoptions" target="_blank" >Konvertieren Sie SVG in BMP mit ImageSaveOptions</a>

BMP-Dateien sind Bitmap-Bilddateien, die zum Speichern hochwertiger digitaler Rasterbilder verwendet werden, und manchmal kann es erforderlich sein, SVG in BMP zu konvertieren. Bitte besuchen Sie den Dokumentationsartikel [SVG in BMP konvertieren](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/), um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und C#-Beispiele für die gängigsten SVG-zu-BMP-Konvertierungsszenarien zu betrachten. In dem Artikel finden Sie Informationen zum Konvertieren von SVG in BMP mithilfe von ConvertSVG()-Methoden und zum Anwenden von ImageSaveOptions.

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