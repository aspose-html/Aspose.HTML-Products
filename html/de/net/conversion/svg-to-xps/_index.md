---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie SVG in XPS in C# - Online-Konverter von SVG in XPS
description: Konvertieren Sie SVG in C# in XPS. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie den Online-SVG-zu-XPS-Konverter kostenlos aus!
url: /net/conversion/svg-to-xps/
family: html
platformtag: net
feature: conversion
informat: SVG
outformat: XPS
otherformats: PDF BMP GIF JPEG PNG TIFF
---

{{<section banner>}}
---
h1: Konvertieren Sie SVG über C# in XPS
h2: High-Fidelity-Konvertierung von SVG in XPS mit serverseitigen .NET-APIs. Konvertieren Sie mit unserem kostenlosen Online-Konverter sofort SVG in das XPS-Format!
---

{{<section overview>}}
---
h2: Konvertieren Sie SVG in XPS mit C#
---

SVG ist eine XML-Sprache zum Erstellen von zweidimensionalen Vektor- und gemischten Vektor-/Rastergrafiken. Um SVG in XPS zu konvertieren, verwenden wir die API [Aspose.HTML for .NET](https://products.aspose.com/html/net/), die eine funktionsreiche, leistungsstarke und einfach zu verwendende Dokumentbearbeitung ist und Konvertierungs-API für die C#-Plattform. Eine SVG-Konvertierung ist oft erforderlich, um andere Formate nutzen zu können. Das XPS-Dateiformat ermöglicht die Verwaltung von Zugriffsrechten und liefert qualitativ hochwertige druckbare Dokumente. Mit unserer Dokumentverarbeitungsbibliothek können Sie SVG mit nur wenigen Codezeilen programmgesteuert in XPS-Bilder konvertieren und dabei die volle Kontrolle über verschiedene Konvertierungsoptionen haben.

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der Umwandlung von SVG in XPS direkt in Ihrem Browser! Das folgende C#-Beispiel zeigt, wie ein SVG-Dokument konvertiert wird. Wir beschreiben den Quellcode zum Lesen von SVG aus einer Datei und zum anschließenden Konvertieren von SVG in XPS mit Standardspeicheroptionen. Bitte laden Sie SVG aus dem lokalen Dateisystem, wählen Sie das Ausgabeformat und führen Sie das Beispiel aus. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie SVG also schnell online in das XPS-Format!

{{<section "app-pluging" i18n-exclude>}}

{{< app/svg/converter SVG  XPS PDF TIFF BMP PNG "JPG|JPEG" GIF>}}
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
h2: Schritte zum Konvertieren von SVG in XPS in C#
---
1. Laden Sie eine SVG-Datei mit einem der SVGDocument()-Konstruktoren der [SVGDocument](https://apireference.aspose.com/html/net/aspose.html.dom.svg/svgdocument)-Klasse.
1. Erstellen Sie ein neues [XpsSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions)-Objekt.
1. Verwenden Sie die Methode [ConvertSVG()](https://apireference.aspose.com/html/net/aspose.html.converters.converter/convertsvg/methods/3), um SVG als XPS-Datei zu speichern. Sie müssen das SVGDocument, XpsSaveOptions und den Ausgabedateipfad an die Methode ConvertSVG() übergeben.




{{<section documentation>}}
---
h2: SVG-zu-XPS-Konvertierung in der Dokumentation
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#svg-to-xps-by-a-single-line-of-code " target="_blank">SVG zu XPS durch eine einzige Codezeile</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#convert-svg-to-xps-using-xpssaveoptions" target="_blank" >Konvertieren Sie SVG in XPS mit XpsSaveOptions</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#output-stream-providers" target="_blank">Konvertieren Sie SVG in XPS mit MemoryStreamProvider</a>

XPS ist ein von Microsoft entwickeltes Format zum Speichern und Anzeigen von Dokumenten. Es hat eine Reihe von Vorteilen, die Sicherheitsfunktionen unterstützen, wie z. B. digitale Signaturen für mehr Dokumentensicherheit und mehr. Bitte besuchen Sie den Dokumentationsartikel [SVG in XPS konvertieren](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und um C#-Beispiele für die gängigsten Konvertierungsszenarien von SVG in XPS zu betrachten. In diesem Artikel finden Sie Informationen zum Konvertieren von SVG in XPS mithilfe von ConvertSVG()-Methoden und zum Anwenden von XpsSaveOptions.

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