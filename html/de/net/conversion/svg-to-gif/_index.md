---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie SVG in GIF
description: Konvertieren Sie SVG in C# in GIF. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie den Online-SVG-zu-GIF-Konverter kostenlos aus!
url: /net/conversion/svg-to-gif/
family: html
platformtag: net
feature: conversion
informat: SVG
outformat: GIF
otherformats: PDF XPS BMP JPEG PNG TIFF
---

{{<section banner>}}
---
h1: Konvertieren Sie SVG in GIF über C#
h2: High-Fidelity-SVG-zu-GIF-Konvertierung mit serverseitigen .NET-APIs. Konvertieren Sie mit unserem kostenlosen Online-Konverter sofort SVG in das GIF-Format!
---

{{<section overview>}}
---
h2: Konvertieren Sie SVG in GIF mit C#
---

SVG ist eine XML-Sprache zum Erstellen von zweidimensionalen Vektor- und gemischten Vektor-/Rastergrafiken. Um SVG in GIF umzuwandeln, verwenden wir die API [Aspose.HTML for .NET](https://products.aspose.com/html/net/), die eine funktionsreiche, leistungsstarke und einfach zu verwendende Dokumentbearbeitung ist und Konvertierungs-API für die C#-Plattform. Eine SVG-Konvertierung ist oft erforderlich, um andere Formate nutzen zu können. Mit unserer Dokumentverarbeitungsbibliothek können Sie mit nur wenigen Codezeilen programmgesteuert SVG in GIF-Bilder konvertieren und dabei die volle Kontrolle über verschiedene Konvertierungsoptionen haben.

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der Umwandlung von SVG in GIF direkt in Ihrem Browser! Das folgende C#-Beispiel zeigt, wie ein SVG-Dokument konvertiert wird. Wir beschreiben den Quellcode zum Lesen von SVG aus einer Datei und zum anschließenden Konvertieren von SVG in GIF mit Standardspeicheroptionen. Bitte laden Sie SVG aus dem lokalen Dateisystem, wählen Sie das Ausgabeformat und führen Sie das Beispiel aus. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie SVG also schnell online in das GIF-Format!

{{<section "app-pluging" i18n-exclude>}}

{{< app/svg/converter SVG GIF XPS PDF TIFF PNG "JPG|JPEG" BMP>}}
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
h2: Schritte zum Konvertieren von SVG in GIF in C#
---
1. Laden Sie eine SVG-Datei mit einem der SVGDocument()-Konstruktoren der [SVGDocument](https://apireference.aspose.com/html/net/aspose.html.dom.svg/svgdocument)-Klasse.
1. Erstellen Sie ein neues [ImageSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions)-Objekt mit GIF ImageFormat. Standardmäßig ist die Format-Eigenschaft [PNG](https://apireference.aspose.com/html/net/aspose.html.rendering.image/imageformat).
1. Verwenden Sie die Methode [ConvertSVG()](https://apireference.aspose.com/html/net/aspose.html.converters.converter/convertsvg/methods/3), um SVG als GIF-Bild zu speichern. Sie müssen das SVGDocument, die ImageSaveOptions und den Pfad der Ausgabedatei an die Methode ConvertSVG() übergeben.




{{<section documentation>}}
---
h2: SVG-zu-GIF-Konvertierung in der Dokumentation
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/#svg-to-gif-durch-eine-einzelne-codezeile " target="_blank">SVG zu GIF durch eine einzige Codezeile</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/#convert-svg-to-gif-using-imagesaveoptions" target="_blank" >Konvertieren Sie SVG in GIF mit ImageSaveOptions</a>

GIF ist ein beliebtes Bildformat, das häufig im Web-Publishing verwendet wird, und manchmal kann es erforderlich sein, SVG in GIF zu konvertieren. Bitte besuchen Sie den Dokumentationsartikel [Convert SVG to GIF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/), um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und um C#-Beispiele für die gängigsten SVG-zu-GIF-Konvertierungsszenarien zu betrachten. In dem Artikel finden Sie Informationen zum Konvertieren von SVG in GIF mit ConvertSVG()-Methoden und zum Anwenden von ImageSaveOptions.

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