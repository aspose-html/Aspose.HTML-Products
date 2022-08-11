---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie MHTML in DOCX
description: Konvertieren Sie MHTML in DOCX über C#-Code. Speichern Sie MHTML als DOCX-Datei. Probieren Sie kostenlos online MHTML to DOCX Converter aus!
url: /net/conversion/mhtml-to-docx/
family: html
platformtag: net
feature: conversion
informat: MHTML
outformat: DOCX
otherformats: PDF XPS GIF JPEG PNG TIFF BMP
---

{{<section banner>}}
---
h1: Konvertieren Sie MHTML in DOCX über C#
h2: High-Fidelity-MHTML-zu-DOCX-Konvertierung mit .NET-API. Konvertieren Sie mit unserem kostenlosen Online-Konverter MHTML sofort in das DOCX-Format.
---

{{<section overview>}}
---
h2: Konvertieren Sie MHTML in DOCX mit C#
---

Um MHTML in DOCX zu konvertieren, verwenden wir die API [Aspose.HTML for .NET](https://products.aspose.com/html/net/), die eine funktionsreiche, leistungsstarke und einfach zu verwendende Dokumentbearbeitung ist Konvertierungs-API für die C#-Plattform. MHTML-Konvertierungen sind oft erforderlich, um andere Formate nutzen zu können. Mit unserer Hochgeschwindigkeitsbibliothek können Sie MHTML programmgesteuert in DOCX konvertieren, wobei Sie die volle Kontrolle über verschiedene Konvertierungsparameter haben. Mit der leistungsstarken C#-API können Sie MHTML schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der Konvertierung von MHTML in DOCX direkt in Ihrem Browser! Bitte laden Sie eine MHTML-Datei aus dem lokalen Dateisystem, wählen Sie das gewünschte Ausgabeformat aus der Liste und führen Sie das Beispiel aus. Es ist schnell, einfach, sicher und völlig kostenlos! Die Konvertierung von MHTML in DOCX erfolgt mit den Standardspeicheroptionen. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie also schnell jede Webseite oder MHTML in das DOCX-Format online!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MHTML DOCX PDF "JPG|JPEG" GIF BMP XPS TIFF PNG >}}
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
h2: Schritte zum Konvertieren von MHTML in DOCX in C#
---

Wenn Sie MHTML programmgesteuert in DOCX konvertieren möchten, befolgen Sie bitte einige erforderliche Schritte:
1. Öffnen Sie eine vorhandene MHTML-Datei.
1. Erstellen Sie eine Instanz der Klasse [DocSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/docsaveoptions/).
1. Verwenden Sie die Methode [ConvertMHTML()](https://reference.aspose.com/html/net/aspose.html.converters.converter/convertmhtml/) des [Converter](https://reference.aspose.com/html/net/aspose.html.converters/converter/), um MHTML als DOCX-Datei zu speichern. Sie müssen den MHTML-Dateistream, DocSaveOptions und den Ausgabedateipfad an die Methode ConvertMHTML() übergeben.
1. Die DOCX-Datei wird im angegebenen Pfad gespeichert.

{{<section documentation>}}
---
h2: MHTML-zu-DOCX-Konvertierung in der Dokumentation
---

  - Ziel <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#mhtml-to-docx-by-two-lines-of-code" target="_blank">MHTML zu DOCX durch zwei Codezeilen</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#convert-mhtml-to-docx-using-docsaveoptions" target="_blank" >Konvertieren Sie MHTML in DOCX mit DocSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#output-stream-providers" target="_blank">MHTML in DOCX konvertieren mit MemoryStreamProvider</a>

Die Konvertierung von MHTML in DOCX ist häufig erforderlich, um das DOCX-Format für bestimmte Aufgaben zu nutzen. Das DOCX-Format ist beliebt, weil es eine Vielzahl von Formatierungsfunktionen unterstützt und Benutzern eine Vielzahl von Optionen bietet, um jede Art von Dokument zu schreiben. Bitte besuchen Sie den Dokumentationsartikel [MHTML in DOCX konvertieren](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und zur Betrachtung von C#-Beispielen für die gängigsten MHTML-zu-DOCX-Konvertierungsszenarien. In dem Artikel finden Sie Informationen zum Konvertieren von MHTML in DOCX mithilfe von ConvertMHTML()-Methoden und zum Anwenden von DocSaveOptions- oder ICreateStreamProvider-Parametern.

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