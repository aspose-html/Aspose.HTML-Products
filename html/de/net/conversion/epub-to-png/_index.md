---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie EPUB in PNG - C#
description: Beispielcode für die Umwandlung von EPUB in PNG C#. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie den Online-EPUB-zu-PNG-Konverter kostenlos aus!
url: /net/conversion/epub-to-png/
family: html
platformtag: net
feature: conversion
informat: EPUB
outformat: PNG
otherformats: PDF DOCX XPS BMP JPEG GIF TIFF
---

{{<section banner>}}
---
h1: Konvertieren Sie EPUB in PNG über C#
h2: Generieren Sie PNG aus einer EPUB-Quelldatei mit der .NET-API. Wandeln Sie EPUB mit unserem kostenlosen Online-Konverter sofort in das PNG-Format um!
---

{{<section overview>}}
---
h2: Konvertieren Sie EPUB in PNG mit C#
---

Um EPUB in PNG zu konvertieren, verwenden wir die API [Aspose.HTML for .NET](https://products.aspose.com/html/net/), ein funktionsreiches, leistungsstarkes und benutzerfreundliches Dokument Manipulations- und Konvertierungs-API für die C#-Plattform. EPUB ist ein offenes XML-basiertes Format für digitale Bücher und Publikationen, die auf einer Vielzahl von Geräten angezeigt und gelesen werden können. EPUB-Konvertierungen sind oft erforderlich, um andere Formate nutzen zu können. Sie können EPUB programmgesteuert in PNG umwandeln und dabei die volle Kontrolle über eine Vielzahl von Konvertierungsparametern haben. Mit der leistungsstarken C#-API können Sie EPUB schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der Umwandlung von EPUB in PNG direkt in Ihrem Browser! Es ist schnell, einfach, sicher und völlig kostenlos! Das folgende C#-Beispiel zeigt, wie ein EPUB-Dokument konvertiert wird. Wir beschreiben den Quellcode zum Lesen von EPUB aus einer Datei und zum anschließenden Konvertieren von EPUB in PNG mit Standardspeicheroptionen. Bitte laden Sie EPUB aus dem lokalen Dateisystem, wählen Sie das Ausgabeformat und führen Sie das Beispiel aus. Das Ergebnis erhalten Sie sofort als separate Datei.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter EPUB PNG GIF PDF DOCX "JPG|JPEG" BMP TIFF XPS >}}
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
h2: Schritte zum Konvertieren von EPUB in PNG in C#
---

Wenn Sie die Konvertierungsfunktion in Ihrem Produkt in Betracht ziehen oder EPUB programmgesteuert in PNG konvertieren möchten, sehen Sie sich bitte das obige C#-Codebeispiel an oder lesen Sie das Kapitel Dokumentation. Es können verschiedene Szenarien sein, aber jede EPUB-Konvertierung kann mit ein paar erforderlichen Schritten durchgeführt werden:
1. Öffnen Sie eine vorhandene EPUB-Datei.
1. Erstellen Sie ein neues [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/)-Objekt. Standardmäßig ist die Format-Eigenschaft [PNG.](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/)
1. Verwenden Sie die Methode [ConvertEPUB()](https://reference.aspose.com/html/net/aspose.html.converters.converter/convertepub/) der Converter-Klasse, um EPUB als PNG-Bild zu speichern. Sie müssen den EPUB-Dateistream, ImageSaveOptions und den Ausgabedateipfad an die ConvertEPUB()-Methode für die EPUB-zu-PNG-Konvertierung übergeben.
1. Die PNG-Datei wird im angegebenen Pfad gespeichert.




{{<section documentation>}}
---
h2: EPUB-zu-PNG-Konvertierung in der Dokumentation
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#epub-to-png-by-a-single-line-of-code " target="_blank">EPUB in PNG durch eine einzige Codezeile</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#convert-epub-to-png-using-imagesaveoptions" target="_blank" >Konvertieren Sie EPUB in PNG mit ImageSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#output-stream-providers" target="_blank">Konvertieren Sie EPUB in PNG mit MemoryStreamProvider</a>

Das EPUB-Format hat als XML-basiertes E-Book-Format an Popularität gewonnen und wurde entwickelt, um die Darstellung der Inhalte an das Lesegerät anzupassen. Manchmal ist es erforderlich, ein Bild anstelle von EPUB-Dokumenten zu erhalten, z. B. um sie portabel zu machen und einfach auf verschiedenen Geräten zu teilen, eine Bildergalerie aus eBooks zu erstellen usw. Das PNG-Dateiformat unterstützt verlustfreie Bildkomprimierung, was es bei seinen Benutzern beliebt macht. Bitte besuchen Sie den Dokumentationsartikel [Convert EPUB to PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/), um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und um C#-Beispiele für die gängigsten EPUB-zu-PNG-Konvertierungsszenarien zu betrachten. In diesem Artikel finden Sie Informationen zum Konvertieren von EPUB in PNG mithilfe von ConvertEPUB()-Methoden und zum Anwenden von ImageSaveOptions- und ICreateStreamProvider-Parametern.

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