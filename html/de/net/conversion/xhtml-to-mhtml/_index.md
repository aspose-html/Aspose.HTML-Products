---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie XHTML in MHTML
description: Konvertieren Sie XHTML in C# in MHTML. Probieren Sie kostenlos online XHTML to MHTML Converter aus!
url: /net/conversion/xhtml-to-mhtml/
family: html
platformtag: net
feature: conversion
informat: XHTML
outformat: MHTML
otherformats: PDF XPS DOCX GIF JPEG PNG TIFF BMP HTML MD
howto: howtoXhtml
---

{{<section banner>}}
---
h1: Konvertieren Sie XHTML über C# in MHTML
h2: Generieren Sie MHTML aus einer XHTML-Quellseite mit der .NET-API. Konvertieren Sie mit unserem kostenlosen Online-Konverter sofort XHTML in das MHTML-Format!
---

{{<section overview>}}
---
h2: Konvertieren Sie XHTML in MHTML mit C#
---

Der Vorteil des Speicherns von (X)HTML als MHTML besteht darin, dass alle Webseitenelemente in einer einzigen Datei erhalten bleiben. MHTML enthält ein zugrunde liegendes (X)HTML-Dokument und seine eingebetteten Bilder, Medien und anderen Ressourcen. Mit der API [Aspose.HTML for .NET](https://products.aspose.com/html/net/) können Sie XHTML programmgesteuert in MHTML konvertieren und dabei die vollständige Kontrolle über die Konvertierungsparameter behalten. Jede Konvertierung, die Sie durchführen möchten, beinhaltet das Laden eines XHTML-Dokuments und das Speichern im MHTML-Format. Mit der leistungsstarken C#-API können Sie XHTML schnell und in hoher Qualität in MHTML konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der Konvertierung von XHTML in MHTML direkt in Ihrem Browser! Bitte laden Sie eine XHTML-Datei aus dem lokalen Dateisystem, wählen Sie das gewünschte Ausgabeformat aus der Liste und führen Sie das Beispiel aus. Es ist schnell, einfach, sicher und völlig kostenlos! Die Konvertierung von XHTML in MHTML erfolgt mit den Standardspeicheroptionen. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie also schnell jede Webseite oder XHTML in das MHTML-Format online!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter XHTML MHTML BMP TIFF PNG "JPG|JPEG" GIF PDF XPS DOCX MD >}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new HTMLDocument("document.{{input lower}}");
{{#if_output 'PDF'}}
    var options = new PdfSaveOptions();
{{/if_output}}
{{#if_output 'DOCX'}}
    var options = new DocSaveOptions();
{{/if_output}}
{{#if_output 'XPS'}}
    var options = new XpsSaveOptions();
{{/if_output}}
{{#if_output 'MD'}}
    var options = new MarkdownSaveOptions();
{{/if_output}}
{{#if_output 'MHTML'}}
    var options = new MHTMLSaveOptions();
{{/if_output}}
{{#if_output 'BMP' 'JPG' 'GIF' 'PNG' 'TIFF'}}
    var options = new ImageSaveOptions(ImageFormat.{{output param2 camel}});
{{/if_output}}
    Converter.ConvertHTML(document, options, "output.{{output lower}}");   
{{< /app/html/converter>}} 


{{<section steps>}}
---
h2: Schritte zum Konvertieren von XHTML in MHTML in C#
---

Wenn Sie XHTML programmgesteuert in MHTML konvertieren möchten, sehen Sie sich bitte das obige C#-Codebeispiel an oder lesen Sie das Kapitel Dokumentation. In allen Fällen erfordert jede Konvertierung von XHTML in MHTML einige obligatorische Schritte:

1. Laden Sie eine XHTML-Datei mit einem der HTMLDocument()-Konstruktoren der Klasse [HTMLDocument](https://reference.aspose.com/html/net/aspose.html/htmldocument/).
1. Erstellen Sie ein neues [MHTMLSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/mhtmlsaveoptions/)-Objekt.
1. Verwenden Sie die Methode [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) der Converter-Klasse, um XHTML als MHTML-Datei zu speichern.
1. Die MHTML-Datei wird im angegebenen Pfad gespeichert.

{{<section documentation>}}
---
h2: (X)HTML-Konvertierung in der Dokumentation
---

MHTML kombiniert normales (X)HTML mit externen Ressourcen wie Bildern, Animationen, Audio usw. in einer Datei mit der Dateierweiterung .mht. Mit Aspose.HTML für .NET API können Sie (X)HTML schnell und mit hoher Qualität in andere gängige Formate konvertieren. Bitte besuchen Sie das Dokumentationskapitel <a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">Converting between Formats</a>, um mehr über die API zu erfahren Konvertierungsfunktionen. Das Kapitel beschreibt beliebte Konverter sowie C#-Beispiele für die gängigsten Konvertierungsszenarien.

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
title: Andere unterstützte XHTML-Konvertierungen
subTitle: "Sie können XHTML auch in viele andere Dateiformate konvertieren:"
---