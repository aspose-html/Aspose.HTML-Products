---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie EPUB in DOCX in C# - Online-EPUB-zu-DOCX-Konverter
description: Beispielcode für die Umwandlung von EPUB in DOCX C#. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie den Online-EPUB-zu-DOCX-Konverter kostenlos aus!
url: /net/conversion/epub-to-docx/
family: html
platformtag: net
feature: conversion
informat: EPUB
outformat: DOCX
otherformats: PDF DOCX XPS GIF JPEG PNG TIFF BMP
---

{{<section banner>}}
---
h1: Konvertieren Sie EPUB in DOCX über C#
h2: Generieren Sie DOCX aus der EPUB-Quelldatei mit der .NET-API. Wandeln Sie EPUB mit unserem kostenlosen Online-Konverter sofort in das DOCX-Format um!
---

{{<section overview>}}
---
h2: Konvertieren Sie EPUB in DOCX mit C#
---

Um EPUB in DOCX zu konvertieren, verwenden wir die API [Aspose.HTML for .NET](https://products.aspose.com/html/net/), die ein funktionsreiches, leistungsstarkes und benutzerfreundliches Dokument ist Manipulations- und Konvertierungs-API für die C#-Plattform. EPUB ist ein offenes XML-basiertes Format für digitale Bücher und Publikationen, die auf einer Vielzahl von Geräten angezeigt und gelesen werden können. DOCX ist ein bekanntes Format für Microsoft Word-Dokumente. Dieses Format ist beliebt, weil es eine Vielzahl von Formatierungsfunktionen unterstützt und Benutzern eine Vielzahl von Optionen bietet, um jede Art von Dokument zu schreiben. .NET-Entwickler können EPUB in nur wenigen Codezeilen einfach laden und in DOCX konvertieren.

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der Umwandlung von EPUB in DOCX direkt in Ihrem Browser! Es ist schnell, einfach, sicher und völlig kostenlos! Das folgende C#-Beispiel zeigt, wie ein EPUB-Dokument konvertiert wird. Wir beschreiben den Quellcode für das Lesen von EPUB aus einer Datei und das anschließende Konvertieren von EPUB in DOCX mit Standardspeicheroptionen. Bitte laden Sie EPUB aus dem lokalen Dateisystem, wählen Sie das Ausgabeformat und führen Sie das Beispiel aus. Das Ergebnis erhalten Sie sofort als separate Datei.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter EPUB DOCX PDF "JPG|JPEG" PNG GIF TIFF XPS BMP >}}
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
h2: Schritte zum Konvertieren von EPUB in DOCX in C#
---

Wenn Sie die Konvertierungsfunktion in Ihrem Produkt in Betracht ziehen oder EPUB programmgesteuert in DOCX konvertieren möchten, sehen Sie sich bitte das obige C#-Codebeispiel an oder lesen Sie das Kapitel Dokumentation. In allen Fällen erfordert jede Konvertierung einige obligatorische Schritte:
1. Öffnen Sie eine vorhandene EPUB-Datei.
1. Erstellen Sie ein neues [DocSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/docsaveoptions)-Objekt.
1. Verwenden Sie die Methode [ConvertEPUB()](https://apireference.aspose.com/html/net/aspose.html.converters.converter/convertepub/methods/27) der Converter-Klasse, um EPUB als DOCX-Datei zu speichern . Sie müssen den EPUB-Dateistream, DocSaveOptions und den Ausgabedateipfad an die ConvertEPUB()-Methode für die EPUB-zu-DOCX-Konvertierung übergeben.
1. Die DOCX-Datei wird im angegebenen Pfad gespeichert.




{{<section documentation>}}
---
h2: EPUB-zu-DOCX-Konvertierung in der Dokumentation
---

  - Ziel <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#epub-to-docx-by-two-lines-of-code". ="_blank">EPUB zu DOCX durch zwei Codezeilen</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#convert-epub-to-docx-using-docsaveoptions" target="_blank" >Konvertieren Sie EPUB in DOCX mit DocSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers" target="_blank">Konvertieren Sie EPUB in DOCX mit MemoryStreamProvider</a>

Das EPUB-Format hat als XML-basiertes E-Book-Format an Popularität gewonnen und wurde entwickelt, um die Darstellung der Inhalte an das Lesegerät anzupassen. Eine EPUB-zu-DOCX-Konvertierung ist oft erforderlich, um das DOCX-Format für bestimmte Benutzeraufgaben zu nutzen. Bitte besuchen Sie den Dokumentationsartikel [Convert EPUB to DOCX](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/), um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und um C#-Beispiele für die gängigsten EPUB-zu-DOCX-Konvertierungsszenarien zu betrachten. In diesem Artikel finden Sie Informationen zum Konvertieren von EPUB in DOCX mit ConvertEPUB()-Methoden und zum Anwenden von DocSaveOptions- und ICreateStreamProvider-Parametern.

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