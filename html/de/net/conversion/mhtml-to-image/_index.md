---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie MHTML in Bild
description: Konvertieren Sie MHTML in C# in Bild. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie den MHTML to Image Converter kostenlos online aus!
url: /net/conversion/mhtml-to-image/
family: html
platformtag: net
feature: conversion
informat: MHTML
outformat: Image
otherformats: DOCX PDF XPS BMP GIF JPEG PNG TIFF
---

{{<section banner>}}
---
h1: Konvertieren Sie MHTML in Bild über C#
h2: High-Fidelity-MHTML-zu-Bild-Konvertierung mit .NET-API. Konvertieren Sie mit unserem kostenlosen Online-Konverter MHTML sofort in das Bildformat.
---

{{<section overview>}}
---
h2: Konvertieren Sie MHTML in ein Bild mit C#
---

Um MHTML in Bild umzuwandeln, verwenden wir die API [Aspose.HTML for .NET](https://products.aspose.com/html/net/), die eine funktionsreiche, leistungsstarke und einfach zu verwendende Dokumentbearbeitung ist Konvertierungs-API für die C#-Plattform. MHTML-Konvertierungen sind oft erforderlich, um andere Formate nutzen zu können. Mit unserer Hochgeschwindigkeitsbibliothek können Sie MHTML programmgesteuert in Bild umwandeln, wobei Sie die volle Kontrolle über verschiedene Konvertierungsparameter haben. Mit der leistungsstarken C#-API können Sie MHTML schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der MHTML-zu-Bild-Konvertierung direkt in Ihrem Browser! Bitte laden Sie eine MHTML-Datei aus dem lokalen Dateisystem, wählen Sie das gewünschte Ausgabeformat aus der Liste und führen Sie das Beispiel aus. Es ist schnell, einfach, sicher und völlig kostenlos! Die MHTML-zu-Bild-Konvertierung erfolgt mit den Standardspeicheroptionen. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie also schnell jede Webseite oder MHTML in das Bildformat online!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MHTML "JPG|JPEG" GIF TIFF PNG BMP DOCX PDF XPS >}}
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
h2: Schritte zum Konvertieren von MHTML in Bild in C#
---

Wenn Sie MHTML programmgesteuert in Bild konvertieren möchten, befolgen Sie bitte einige erforderliche Schritte:
1. Öffnen Sie eine vorhandene MHTML-Datei.
1. Erstellen Sie ein neues [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions)-Objekt und geben Sie ImageFormat an. Standardmäßig ist die Format-Eigenschaft [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat).
1. Verwenden Sie die Methode [ConvertMHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertmhtml/) der Converter-Klasse, um MHTML als Bild zu speichern.
1. Die Rasterbilddatei wird im angegebenen Pfad gespeichert.




{{<section documentation>}}
---
h2: MHTML-zu-Bild-Konvertierung in der Dokumentation
---

Die MHTML-zu-Bild-Konvertierung ermöglicht Ihnen, ein MHTML-Dokument als Bilddatei zu speichern. Bitte besuchen Sie den Dokumentationsartikel [MHTML in Bild konvertieren](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-image/), um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und um C#-Beispiele für die gängigsten Konvertierungsszenarien zu betrachten. In diesem Artikel finden Sie Informationen zum Konvertieren von MHTML in Bilder mithilfe der ConvertMHTML()-Methoden und zum Anwenden von ImageSaveOptions oder [ICreateStreamProvider](https://reference.aspose.com/html/net/aspose.html.io/icreatestreamprovider) Parameter.

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