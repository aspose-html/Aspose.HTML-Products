---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie MHTML in PDF
description: Konvertieren Sie MHTML in PDF über C#-Code. Speichern Sie MHTML als PDF-Datei. Probieren Sie kostenlos online MHTML to PDF Converter aus!
url: /net/conversion/mhtml-to-pdf/
family: html
platformtag: net
feature: conversion
informat: MHTML
outformat: PDF
otherformats: DOCX XPS GIF JPEG PNG TIFF BMP
---

{{<section banner>}}
---
h1: Konvertieren Sie MHTML in PDF über C#
h2: High-Fidelity-Konvertierung von MHTML in PDF mithilfe der .NET-API. Konvertieren Sie mit unserem kostenlosen Online-Konverter MHTML sofort in das PDF-Format.
---

{{<section overview>}}
---
h2: Konvertieren Sie MHTML in PDF mit C#
---

Um MHTML in PDF zu konvertieren, verwenden wir die API [Aspose.HTML for .NET](https://products.aspose.com/html/net/), die eine funktionsreiche, leistungsstarke und einfach zu verwendende Dokumentbearbeitung ist Konvertierungs-API für die C#-Plattform. MHTML-Konvertierungen sind oft erforderlich, um andere Formate nutzen zu können. Mit unserer Hochgeschwindigkeitsbibliothek können Sie MHTML programmgesteuert in PDF konvertieren, wobei Sie die volle Kontrolle über verschiedene Konvertierungsparameter haben. Mit der leistungsstarken C#-API können Sie MHTML schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der Konvertierung von MHTML in PDF direkt in Ihrem Browser! Bitte laden Sie eine MHTML-Datei aus dem lokalen Dateisystem, wählen Sie das gewünschte Ausgabeformat aus der Liste und führen Sie das Beispiel aus. Es ist schnell, einfach, sicher und völlig kostenlos! Die Konvertierung von MHTML in PDF erfolgt mit den Standardspeicheroptionen. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie also schnell jede Webseite oder MHTML in das PDF-Format online!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MHTML PDF "JPG|JPEG" GIF DOCX BMP XPS TIFF PNG >}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var stream = File.OpenRead("sample.mht");
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
    Converter.ConvertMHTML(stream, options, "output.{{output lower}}");   
{{< /app/html/converter>}} 


{{<section steps>}}
---
h2: Schritte zum Konvertieren von MHTML in PDF in C#
---

Wenn Sie MHTML programmgesteuert in PDF konvertieren möchten, befolgen Sie bitte einige erforderliche Schritte:
1. Öffnen Sie eine vorhandene MHTML-Datei.
1. Erstellen Sie eine Instanz der Klasse [PdfSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions/).
1. Verwenden Sie die Methode [ConvertMHTML()](https://reference.aspose.com/html/net/aspose.html.converters.converter/convertmhtml/methods/29) des [Converter](https://reference.aspose.com/html/net/aspose.html.converters/converter/) zum Speichern von MHTML als PDF-Datei. Sie müssen den MHTML-Dateistream, PdfSaveOptions und den Ausgabedateipfad an die Methode ConvertMHTML() übergeben.
1. Die PDF-Datei wird im angegebenen Pfad gespeichert.

{{<section documentation>}}
---
h2: MHTML-zu-PDF-Konvertierung in der Dokumentation
---

  - Ziel <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#mhtml-to-pdf-by-two-lines-of-code" target="_blank">MHTML zu PDF durch zwei Codezeilen</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#convert-mhtml-to-pdf-using-pdfsaveoptions" target="_blank" >Konvertieren Sie MHTML in PDF mit PdfSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#output-stream-providers" target="_blank">Konvertieren Sie MHTML in PDF mit MemoryStreamProvider</a>

Die Konvertierung von MHTML in PDF ist häufig erforderlich, um einen eingeschränkten Zugriff auf die Bearbeitung oder das Kopieren von Dokumenten einzurichten, offizielle Dokumente zu erstellen oder bestimmte Informationen zu versenden, beispielsweise per E-Mail. Bitte besuchen Sie den Dokumentationsartikel [MHTML in PDF konvertieren](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und um C#-Beispiele für die gängigsten MHTML-in-PDF-Konvertierungsszenarien zu betrachten. In dem Artikel finden Sie Informationen zum Konvertieren von MHTML in PDF mithilfe von ConvertMHTML()-Methoden und zum Anwenden von PdfSaveOptions- oder ICreateStreamProvider-Parametern.

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
title: Andere unterstützte MHTML-Konvertierungen
subTitle: "Sie können MHTML auch in viele andere Dateiformate konvertieren:"
---