---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie EPUB in TIFF in C# - Online-Konverter von EPUB in TIFF
description: Beispielcode für die Umwandlung von EPUB in TIFF C#. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie den Online-EPUB-zu-TIFF-Konverter kostenlos aus!
url: /net/conversion/epub-to-tiff/
family: html
platformtag: net
feature: conversion
informat: EPUB
outformat: TIFF
otherformats: PDF DOCX XPS BMP JPEG PNG TIFF GIF
---

{{<section banner>}}
---
h1: Konvertieren Sie EPUB in TIFF über C#
h2: Generieren Sie TIFF aus EPUB-Quelldatei mit .NET API. Wandeln Sie EPUB mit unserem kostenlosen Online-Konverter sofort in das TIFF-Format um!
---

{{<section overview>}}
---
h2: Konvertieren Sie EPUB in TIFF mit C#
---

Um EPUB in TIFF zu konvertieren, verwenden wir die API [Aspose.HTML for .NET](https://products.aspose.com/html/net/), ein funktionsreiches, leistungsstarkes und benutzerfreundliches Dokument Manipulations- und Konvertierungs-API für die C#-Plattform. EPUB ist ein offenes XML-basiertes Format für digitale Bücher und Publikationen, die auf einer Vielzahl von Geräten angezeigt und gelesen werden können. EPUB-Konvertierungen sind oft erforderlich, um andere Formate nutzen zu können. Mit der leistungsstarken C#-API können Sie EPUB schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der Umwandlung von EPUB in TIFF direkt in Ihrem Browser! Es ist schnell, einfach, sicher und völlig kostenlos! Das folgende C#-Beispiel zeigt, wie ein EPUB-Dokument konvertiert wird. Wir beschreiben den Quellcode zum Lesen von EPUB aus einer Datei und zum anschließenden Konvertieren von EPUB in TIFF mit Standardspeicheroptionen. Bitte laden Sie EPUB aus dem lokalen Dateisystem, wählen Sie das Ausgabeformat und führen Sie das Beispiel aus. Das Ergebnis erhalten Sie sofort als separate Datei.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter EPUB TIFF GIF PDF DOCX "JPG|JPEG" PNG BMP XPS >}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var stream = File.OpenRead(DataDir + "input.epub");
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
    Converter.ConvertEPUB(stream, options, "output.{{output lower}}");   
{{< /app/html/converter>}}


{{<section steps>}}
---
h2: Schritte zum Konvertieren von EPUB in TIFF in C#
---

Wenn Sie die Konvertierungsfunktion in Ihrem Produkt in Betracht ziehen oder EPUB programmgesteuert in TIFF konvertieren möchten, sehen Sie sich bitte das obige C#-Codebeispiel an oder lesen Sie das Kapitel Dokumentation. Sie können EPUB in TIFF umwandeln und dabei die volle Kontrolle über eine Vielzahl von Konvertierungsparametern haben. Es können verschiedene Szenarien sein, aber jede EPUB-Konvertierung kann mit ein paar erforderlichen Schritten durchgeführt werden:
1. Öffnen Sie eine vorhandene EPUB-Datei.
1. Erstellen Sie ein neues [ImageSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions)-Objekt mit TIFF ImageFormat. Standardmäßig ist die Format-Eigenschaft [PNG](https://apireference.aspose.com/html/net/aspose.html.rendering.image/imageformat).
1. Verwenden Sie die Methode [ConvertEPUB()](https://apireference.aspose.com/html/net/aspose.html.converters.converter/convertepub/methods/27) der Converter-Klasse, um EPUB als TIFF-Bild zu speichern . Sie müssen den EPUB-Dateistream, ImageSaveOptions und den Ausgabedateipfad an die ConvertEPUB()-Methode für die EPUB-zu-TIFF-Konvertierung übergeben.
1. Die TIFF-Datei wird im angegebenen Pfad gespeichert.




{{<section documentation>}}
---
h2: EPUB-zu-TIFF-Konvertierung in der Dokumentation
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/#convert-epub-to-tiff" target="_blank">Konvertiere EPUB in TIFF</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/#convert-epub-to-tiff-using-imagesaveoptions" target="_blank" >Konvertieren Sie EPUB in TIFF mit ImageSaveOptions</a>

Das EPUB-Format hat als XML-basiertes E-Book-Format an Popularität gewonnen und wurde entwickelt, um die Darstellung der Inhalte an das Lesegerät anzupassen. Manchmal ist es erforderlich, ein Bild anstelle von EPUB-Dokumenten zu erhalten, z. B. um sie portabel zu machen und einfach auf verschiedenen Geräten zu teilen, E-Books als Bilder in TIFF zu speichern usw. Bitte besuchen Sie den Dokumentationsartikel [EPUB in TIFF konvertieren](https ://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/), um mehr über Aspose.HTML für .NET-API-Konvertierungsfunktionen zu erfahren und C#-Beispiele für die gängigsten EPUB-Dateien zu betrachten TIFF-Konvertierungsszenarien. In diesem Artikel finden Sie Informationen zum Konvertieren von EPUB in TIFF mit ConvertEPUB()-Methoden und zum Anwenden von ImageSaveOptions.

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
title: Andere unterstützte EPUB-Konvertierungen
subTitle: "Sie können EPUB auch in viele andere Dateiformate konvertieren:"
---