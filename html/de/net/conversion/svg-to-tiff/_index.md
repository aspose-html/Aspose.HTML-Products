---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie SVG in TIFF
description: Konvertieren Sie SVG in TIFF mit C#. SVG als TIFF-Bild in C#-Code speichern. Probieren Sie den Online-SVG-zu-TIFF-Konverter kostenlos aus!
url: /net/conversion/svg-to-tiff/
family: html
platformtag: net
feature: conversion
informat: SVG
outformat: TIFF
otherformats: PDF XPS GIF JPEG PNG BMP
---

{{<section banner>}}
---
h1: Konvertieren Sie SVG in TIFF über C#
h2: High-Fidelity-SVG-zu-TIFF-Konvertierung mit serverseitigen .NET-APIs. Konvertieren Sie mit unserem kostenlosen Online-Konverter sofort SVG in das TIFF-Format!
---

{{<section overview>}}
---
h2: Konvertieren Sie SVG in TIFF mit C#
---

SVG ist eine XML-Sprache zum Erstellen von zweidimensionalen Vektor- und gemischten Vektor-/Rastergrafiken. Um SVG in TIFF umzuwandeln, verwenden wir die API [Aspose.HTML for .NET](https://products.aspose.com/html/net/), die eine funktionsreiche, leistungsstarke und einfach zu verwendende Dokumentbearbeitung ist und Konvertierungs-API für die C#-Plattform. Eine SVG-Konvertierung ist oft erforderlich, um andere Formate nutzen zu können. Mit unserer Dokumentverarbeitungsbibliothek können Sie mit nur wenigen Codezeilen SVG-Dateien programmgesteuert in TIFF-Bilder konvertieren und dabei die volle Kontrolle über verschiedene Konvertierungsoptionen behalten.

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der SVG-zu-TIFF-Konvertierung direkt in Ihrem Browser! Das folgende C#-Beispiel zeigt, wie ein SVG-Dokument konvertiert wird. Wir beschreiben den Quellcode zum Lesen von SVG aus einer Datei und zum anschließenden Konvertieren von SVG in TIFF mit Standardspeicheroptionen. Bitte laden Sie SVG aus dem lokalen Dateisystem, wählen Sie das Ausgabeformat und führen Sie das Beispiel aus. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie SVG also schnell online in das TIFF-Format!

{{<section "app-pluging" i18n-exclude>}}

{{< app/svg/converter SVG TIFF BMP PNG "JPG|JPEG" GIF XPS PDF>}}
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
h2: Schritte zum Konvertieren von SVG in TIFF in C#
---
1. Laden Sie eine SVG-Datei mit einem der SVGDocument()-Konstruktoren der [SVGDocument](https://reference.aspose.com/html/net/aspose.html.dom.svg/svgdocument/)-Klasse.
1. Erstellen Sie ein neues [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/)-Objekt mit TIFF ImageFormat. Standardmäßig ist die Format-Eigenschaft [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/).
1. Verwenden Sie die Methode [ConvertSVG()](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertsvg/), um SVG als TIFF-Bild zu speichern. Sie müssen das SVGDocument, die ImageSaveOptions und den Pfad der Ausgabedatei an die Methode ConvertSVG() übergeben.

{{<section documentation>}}
---
h2: SVG-zu-TIFF-Konvertierung in der Dokumentation
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/#svg-to-tiff-durch-eine-einzelne-codezeile " target="_blank">SVG zu TIFF durch eine einzige Codezeile</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/#convert-svg-to-tiff-using-imagesaveoptions" target="_blank" >Konvertieren Sie SVG in TIFF mit ImageSaveOptions</a>

TIFF ist ein Format zum Speichern von Rastergrafikbildern mit einer breiten Farbpalette. Es wird häufig für Polygrafie und Zeitschriften-Offsetdruck verwendet. Manchmal kann es notwendig sein, SVG in TIFF umzuwandeln. Bitte besuchen Sie den Dokumentationsartikel [SVG in TIFF konvertieren](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/), um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und um C#-Beispiele für die gängigsten SVG-zu-TIFF-Konvertierungsszenarien zu betrachten. In dem Artikel finden Sie Informationen zum Konvertieren von SVG in TIFF mit ConvertSVG()-Methoden und zum Anwenden von ImageSaveOptions.

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