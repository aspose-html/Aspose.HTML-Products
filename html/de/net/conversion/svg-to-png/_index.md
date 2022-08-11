---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie SVG in PNG
description: Konvertieren Sie SVG in PNG mit C#. SVG als PNG-Bild in C#-Code speichern. Probieren Sie den Online-SVG-zu-PNG-Konverter kostenlos aus!
url: /net/conversion/svg-to-png/
family: html
platformtag: net
feature: conversion
informat: SVG
outformat: PNG
otherformats: PDF XPS GIF JPEG BMP TIFF
---

{{<section banner>}}
---
h1: Konvertieren Sie SVG in PNG über C#
h2: Hochgenaue SVG-zu-PNG-Konvertierung mit serverseitigen .NET-APIs. Konvertieren Sie mit unserem kostenlosen Online-Konverter sofort SVG in das PNG-Format!
---

{{<section overview>}}
---
h2: Konvertieren Sie SVG in PNG mit C#
---

SVG ist eine XML-Sprache zum Erstellen von zweidimensionalen Vektor- und gemischten Vektor-/Rastergrafiken. Um SVG in PNG zu konvertieren, verwenden wir die API [Aspose.HTML for .NET](https://products.aspose.com/html/net/), die eine funktionsreiche, leistungsstarke und einfach zu verwendende Dokumentbearbeitung ist und Konvertierungs-API für die C#-Plattform. Eine SVG-Konvertierung ist oft erforderlich, um andere Formate nutzen zu können. Mit unserer Dokumentverarbeitungsbibliothek können Sie mit nur wenigen Codezeilen SVG-Bilder programmgesteuert in PNG-Bilder konvertieren und dabei die volle Kontrolle über verschiedene Konvertierungsoptionen behalten.

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der SVG-zu-PNG-Konvertierung direkt in Ihrem Browser! Das folgende C#-Beispiel zeigt, wie ein SVG-Dokument konvertiert wird. Wir beschreiben den Quellcode zum Lesen von SVG aus einer Datei und zum anschließenden Konvertieren von SVG in PNG mit Standardspeicheroptionen. Bitte laden Sie SVG aus dem lokalen Dateisystem, wählen Sie das Ausgabeformat und führen Sie das Beispiel aus. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie also schnell SVG in das PNG-Format online!

{{<section "app-pluging" i18n-exclude>}}

{{< app/svg/converter SVG PNG PDF XPS TIFF BMP "JPG|JPEG" GIF>}}
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
h2: Schritte zum Konvertieren von SVG in PNG in C#
---
1. Laden Sie eine SVG-Datei mit einem der SVGDocument()-Konstruktoren der [SVGDocument](https://reference.aspose.com/html/net/aspose.html.dom.svg/svgdocument/)-Klasse.
1. Erstellen Sie ein neues [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/)-Objekt. Standardmäßig ist die Format-Eigenschaft [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/).
1. Verwenden Sie die Methode [ConvertSVG()](https://reference.aspose.com/html/net/aspose.html.converters.converter/convertsvg/methods/3), um SVG als PNG-Bild zu speichern. Sie müssen das SVGDocument, die ImageSaveOptions und den Pfad der Ausgabedatei an die Methode ConvertSVG() übergeben.

{{<section documentation>}}
---
h2: SVG-zu-PNG-Konvertierung in der Dokumentation
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/#svg-to-png-durch-eine-einzelne-codezeile " target="_blank">SVG zu PNG durch eine einzige Codezeile</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/#convert-svg-to-png-using-imagesaveoptions" target="_blank" >Konvertieren Sie SVG in PNG mit ImageSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/#output-stream-providers" target="_blank">Konvertieren Sie SVG in PNG mit MemoryStreamProvider</a>

Das PNG-Dateiformat unterstützt die verlustfreie Bildkomprimierung, was es bei seinen Benutzern beliebt macht. Bitte besuchen Sie den Dokumentationsartikel [SVG in PNG konvertieren](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/), um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und um C#-Beispiele für die gängigsten Konvertierungsszenarien von SVG in PNG zu betrachten. In dem Artikel finden Sie Informationen zum Konvertieren von SVG in PNG mithilfe von ConvertSVG()-Methoden und zum Anwenden von ImageSaveOptions.

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