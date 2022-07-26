---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie EPUB in XPS in C# - Online-Konverter von EPUB in XPS
description: Beispielcode für die Umwandlung von EPUB in XPS C#. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie den Online-EPUB-zu-XPS-Konverter kostenlos aus!
url: /net/conversion/epub-to-xps/
family: html
platformtag: net
feature: conversion
informat: EPUB
outformat: XPS
otherformats: DOCX PDF XPS GIF JPEG PNG TIFF BMP
---

{{<section banner>}}
---
h1: Konvertieren Sie EPUB in XPS über C#
h2: Generieren Sie XPS aus einer EPUB-Quelldatei mithilfe der .NET-API. Wandeln Sie EPUB mit unserem kostenlosen Online-Konverter sofort in das XPS-Format um!
---

{{<section overview>}}
---
h2: Konvertieren Sie EPUB in XPS mit C#
---

Um EPUB in XPS zu konvertieren, verwenden wir die API [Aspose.HTML for .NET,](https://products.aspose.com/html/net/) ein funktionsreiches, leistungsstarkes und benutzerfreundliches Dokument Manipulations- und Konvertierungs-API für die C#-Plattform. EPUB ist ein offenes XML-basiertes Format für digitale Bücher und Publikationen, die auf einer Vielzahl von Geräten angezeigt und gelesen werden können. Eine EPUB-zu-XPS-Konvertierung ist oft erforderlich, um das XPS-Format nutzen zu können. .NET-Entwickler können EPUB in nur wenigen Codezeilen einfach laden und in XPS konvertieren. Mit der leistungsstarken C#-API können Sie EPUB schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der Umwandlung von EPUB in XPS direkt in Ihrem Browser! Es ist schnell, einfach, sicher und völlig kostenlos! Das folgende C#-Beispiel zeigt, wie ein EPUB-Dokument konvertiert wird. Wir beschreiben den Quellcode für das Lesen von EPUB aus einer Datei und das anschließende Konvertieren von EPUB in XPS mit Standardspeicheroptionen. Bitte laden Sie EPUB aus dem lokalen Dateisystem, wählen Sie das Ausgabeformat und führen Sie das Beispiel aus. Das Ergebnis erhalten Sie sofort als separate Datei.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter EPUB  XPS PDF DOCX "JPG|JPEG" PNG GIF TIFF BMP >}}
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
h2: Schritte zum Konvertieren von EPUB in XPS in C#
---

Wenn Sie die Konvertierungsfunktion in Ihrem Produkt in Betracht ziehen oder EPUB programmgesteuert in XPS konvertieren möchten, sehen Sie sich bitte das obige C#-Codebeispiel an oder lesen Sie das Kapitel Dokumentation. API können Sie EPUB in XPS umwandeln und dabei die volle Kontrolle über eine Vielzahl von Konvertierungsparametern haben. Es können verschiedene Szenarien sein, aber jede EPUB-Konvertierung kann mit ein paar erforderlichen Schritten durchgeführt werden:
1. Öffnen Sie eine vorhandene EPUB-Datei.
1. Erstellen Sie ein neues [XpsSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/xpssaveoptions/)-Objekt.
1. Verwenden Sie die Methode [ConvertEPUB()](https://reference.aspose.com/html/net/aspose.html.converters.converter/convertepub/) der Converter-Klasse, um EPUB als XPS-Datei zu speichern. Sie müssen den EPUB-Dateistream, PdfSaveOptions und den Ausgabedateipfad an die ConvertEPUB()-Methode für die EPUB-zu-XPS-Konvertierung übergeben.
1. Die XPS-Datei wird im angegebenen Pfad gespeichert.

{{<section documentation>}}
---
h2: EPUB-zu-XPS-Konvertierung in der Dokumentation
---

  - Ziel <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#epub-to-xps-by-two-lines-of-code" target="_blank">EPUB zu XPS durch zwei Codezeilen</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#convert-epub-to-xps-using-xpssaveoptions" target="_blank" >Konvertieren Sie EPUB in XPS mit XpsSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers" target="_blank">Konvertieren Sie EPUB in XPS mit MemoryStreamProvider</a>

Das EPUB-Format hat als XML-basiertes E-Book-Format an Popularität gewonnen und wurde entwickelt, um die Darstellung der Inhalte an das Lesegerät anzupassen. Eine XPS-Datei stellt Seitenlayoutdateien dar, die auf von Microsoft erstellten XML-Papierspezifikationen basieren. Manchmal müssen Sie XPS-Dokumente anstelle von EPUB erhalten, um sie beispielsweise druckoptimiert, sicher und geschützt zu machen usw. Bitte besuchen Sie den Dokumentationsartikel [EPUB in XPS konvertieren,](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) um mehr über Aspose.HTML für .NET-API-Konvertierungsfunktionen zu erfahren und C#-Beispiele für die gängigsten EPUB-zu-XPS-Konvertierungsszenarien zu betrachten. In diesem Artikel finden Sie Informationen zum Konvertieren von EPUB in XPS mithilfe von ConvertEPUB()-Methoden und zum Anwenden von XpsSaveOptions- und ICreateStreamProvider-Parametern.

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