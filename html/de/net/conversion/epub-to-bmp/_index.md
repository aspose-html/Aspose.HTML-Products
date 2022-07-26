---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie EPUB in BMP
description: Beispielcode für die Umwandlung von EPUB in BMP C#. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie den Online-EPUB-zu-BMP-Konverter kostenlos aus!
url: /net/conversion/epub-to-bmp/
family: html
platformtag: net
feature: conversion
informat: EPUB
outformat: BMP
otherformats: PDF DOCX XPS GIF JPEG PNG TIFF
---

{{<section banner>}}
---
h1: Konvertieren Sie EPUB in BMP über C#
h2: Generieren Sie BMP aus der EPUB-Quelldatei mit der .NET-API. Wandeln Sie EPUB mit unserem kostenlosen Online-Konverter sofort in das BMP-Format um!
---

{{<section overview>}}
---
h2: Konvertieren Sie EPUB in BMP mit C#
---

Um EPUB in BMP zu konvertieren, verwenden wir die API [Aspose.HTML for .NET,](https://products.aspose.com/html/{{lang.url-fragment}}net/) ein funktionsreiches, leistungsstarkes und benutzerfreundliches Dokument Manipulations- und Konvertierungs-API für die C#-Plattform. EPUB ist ein offenes XML-basiertes Format für digitale Bücher und Publikationen, die auf einer Vielzahl von Geräten angezeigt und gelesen werden können. EPUB-Konvertierungen sind oft erforderlich, um andere Formate nutzen zu können. Sie können EPUB programmgesteuert in BMP umwandeln und dabei die volle Kontrolle über eine Vielzahl von Konvertierungsparametern haben. Mit der leistungsstarken C#-API können Sie EPUB schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der EPUB-zu-BMP-Konvertierung direkt in Ihrem Browser! Es ist schnell, einfach, sicher und völlig kostenlos! Das folgende C#-Beispiel zeigt, wie ein EPUB-Dokument konvertiert wird. Wir beschreiben den Quellcode für das Lesen von EPUB aus einer Datei und das anschließende Konvertieren von EPUB in BMP mit Standardspeicheroptionen. Bitte laden Sie EPUB aus dem lokalen Dateisystem, wählen Sie das Ausgabeformat und führen Sie das Beispiel aus. Das Ergebnis erhalten Sie sofort als separate Datei.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter EPUB BMP PDF DOCX "JPG|JPEG" PNG GIF TIFF XPS >}}
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
h2: Schritte zum Konvertieren von EPUB in BMP in C#
---

Wenn Sie die Konvertierungsfunktionalität in Ihrem Produkt in Betracht ziehen oder EPUB programmgesteuert in BMP konvertieren möchten, sehen Sie sich bitte das obige C#-Codebeispiel an oder lesen Sie das Kapitel Dokumentation. In allen Fällen erfordert jede Konvertierung einige obligatorische Schritte:
1. Öffnen Sie eine vorhandene EPUB-Datei.
1. Erstellen Sie ein neues [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/)-Objekt mit BMP ImageFormat. Standardmäßig ist die Format-Eigenschaft [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/).
1. Verwenden Sie die Methode [ConvertEPUB()](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertepub/) der Converter-Klasse, um EPUB als BMP-Bild zu speichern . Sie müssen den EPUB-Dateistream, ImageSaveOptions und den Ausgabedateipfad an die ConvertEPUB()-Methode für die EPUB-zu-BMP-Konvertierung übergeben.
1. Die BMP-Datei wird im angegebenen Pfad gespeichert.




{{<section documentation>}}
---
h2: EPUB-zu-BMP-Konvertierung in der Dokumentation
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/#convert-epub-to-bmp" target="_blank">Konvertiere EPUB in BMP</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/#convert-epub-to-bmp-using-imagesaveoptions" target="_blank" >Konvertieren Sie EPUB in BMP mit ImageSaveOptions</a>

BMP-Dateien sind Bitmap-Bilddateien, die zum Speichern hochwertiger digitaler Bitmap-Bilder verwendet werden. Daher kann es manchmal notwendig sein, EPUB in BMP zu konvertieren. Bitte besuchen Sie den Dokumentationsartikel [Convert EPUB to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/), um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und um C#-Beispiele für die gängigsten EPUB-zu-BMP-Konvertierungsszenarien zu betrachten. In diesem Artikel finden Sie Informationen zum Konvertieren von EPUB in BMP mithilfe von ConvertEPUB()-Methoden und zum Anwenden von ImageSaveOptions- und ICreateStreamProvider-Parametern.

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