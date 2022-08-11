---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie EPUB in PDF
description: Beispielcode für die Umwandlung von EPUB in PDF C#. Probieren Sie den Online-EPUB-zu-PDF-Konverter kostenlos aus!
url: /net/conversion/epub-to-pdf/
family: html
platformtag: net
feature: conversion
informat: EPUB
outformat: PDF
otherformats: DOCX XPS GIF JPEG PNG TIFF BMP
---

{{<section banner>}}
---
h1: Konvertieren Sie EPUB in PDF über C#
h2: Generieren Sie PDF aus EPUB-Quelldatei mit .NET API. Wandeln Sie EPUB mit unserem kostenlosen Online-Konverter sofort in das PDF-Format um!
---

{{<section overview>}}
---
h2: Konvertieren Sie EPUB in PDF mit C#
---

Um EPUB in PDF zu konvertieren, verwenden wir die API [Aspose.HTML for .NET](https://products.aspose.com/html/net/), ein funktionsreiches, leistungsstarkes und benutzerfreundliches Dokument Manipulations- und Konvertierungs-API für die C#-Plattform. EPUB ist ein offenes XML-basiertes Format für digitale Bücher und Publikationen, die auf einer Vielzahl von Geräten angezeigt und gelesen werden können. EPUB-zu-PDF-Konvertierung ist oft erforderlich, um das PDF-Format nutzen zu können. .NET-Entwickler können EPUB in nur wenigen Codezeilen einfach laden und in PDF konvertieren. Mit der leistungsstarken C#-API können Sie EPUB schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der Umwandlung von EPUB in PDF direkt in Ihrem Browser! Es ist schnell, einfach, sicher und völlig kostenlos! Das folgende C#-Beispiel zeigt, wie ein EPUB-Dokument konvertiert wird. Wir beschreiben den Quellcode zum Lesen von EPUB aus einer Datei und anschließendes Konvertieren von EPUB in PDF mit Standardspeicheroptionen. Bitte laden Sie EPUB aus dem lokalen Dateisystem, wählen Sie das Ausgabeformat und führen Sie das Beispiel aus. Das Ergebnis erhalten Sie sofort als separate Datei.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter EPUB PDF DOCX "JPG|JPEG" PNG GIF TIFF XPS BMP >}}
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
h2: Schritte zum Konvertieren von EPUB in PDF in C#
---

Wenn Sie die Konvertierungsfunktion in Ihrem Produkt in Betracht ziehen oder EPUB programmgesteuert in PDF konvertieren möchten, sehen Sie sich bitte das obige C#-Codebeispiel an oder lesen Sie das Kapitel Dokumentation. API können Sie EPUB in PDF umwandeln und dabei die volle Kontrolle über eine Vielzahl von Konvertierungsparametern haben. Es können verschiedene Szenarien sein, aber jede EPUB-Konvertierung kann mit ein paar erforderlichen Schritten durchgeführt werden:
1. Öffnen Sie eine vorhandene EPUB-Datei.
1. Erstellen Sie ein neues [PdfSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions/)-Objekt.
1. Verwenden Sie die Methode [ConvertEPUB()](https://reference.aspose.com/html/net/aspose.html.converters.converter/convertepub/) der Converter-Klasse, um EPUB als PDF-Datei zu speichern. Sie müssen den EPUB-Dateistream, PdfSaveOptions und den Ausgabedateipfad an die ConvertEPUB()-Methode für die EPUB-in-PDF-Konvertierung übergeben.
1. Die PDF-Datei wird im angegebenen Pfad gespeichert.




{{<section documentation>}}
---
h2: EPUB-zu-PDF-Konvertierung in der Dokumentation
---

  - Ziel <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#epub-to-pdf-by-two-lines-of-code" target="_blank">EPUB zu PDF durch zwei Codezeilen</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#convert-epub-to-pdf-using-pdfsaveoptions" target="_blank" >EPUB mit PdfSaveOptions in PDF umwandeln</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers" target="_blank">Konvertieren Sie EPUB in PDF mit MemoryStreamProvider</a>

Das EPUB-Format hat als XML-basiertes E-Book-Format an Popularität gewonnen und wurde entwickelt, um die Darstellung der Inhalte an das Lesegerät anzupassen. Manchmal müssen Sie PDF-Dokumente anstelle von EPUB erhalten, z. B. um sie druckoptimiert und sicher zu machen, Kopien von EPUB-Dokumenten zu erstellen usw. Bitte besuchen Sie den Dokumentationsartikel [EPUB in PDF konvertieren](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/), um mehr über Aspose.HTML für .NET-API-Konvertierungsfunktionen zu erfahren und C#-Beispiele für die gängigsten EPUB-zu-PDF-Konvertierungsszenarien zu betrachten. In diesem Artikel finden Sie Informationen zum Konvertieren von EPUB in PDF mit ConvertEPUB()-Methoden und zum Anwenden von PdfSaveOptions- und ICreateStreamProvider-Parametern.

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