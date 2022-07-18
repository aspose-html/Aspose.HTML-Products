---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie XHTML in C# in PDF - Online XHTML to PDF Converter
description: Konvertieren Sie XHTML in C# in PDF. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie kostenlos online XHTML to PDF Converter aus!
url: /net/conversion/xhtml-to-pdf/
family: html
platformtag: net
feature: conversion
informat: XHTML
outformat: PDF
otherformats: XPS DOCX GIF JPEG PNG TIFF BMP HTML MHTML MD
---

{{<section banner>}}
---
h1: Konvertieren Sie XHTML in PDF über C#
h2: Generieren Sie PDF aus einer XHTML-Quellseite mit der .NET-API. Konvertieren Sie XHTML sofort in das PDF-Format mit unserem kostenlosen Online-Konverter!
---

{{<section overview>}}
---
h2: Konvertieren Sie XHTML in PDF mit C#
---

Das Konvertieren von XHTML in PDF ist häufig erforderlich, um Dokumente vor ungewollter Bearbeitung und Kopieren zu schützen, um Dokumente zum Drucken oder Versenden per E-Mail vorzubereiten usw. Mit [Aspose.HTML for .NET](https://products.aspose.com/ html/net/) API können Sie XHTML programmgesteuert in PDF konvertieren, mit voller Kontrolle über die Konvertierungsparameter. Jede Konvertierung, die Sie durchführen möchten, beinhaltet das Laden eines XHTML-Dokuments und das Speichern im PDF-Format. Mit der leistungsstarken C#-API können Sie XHTML schnell und in hoher Qualität in PDF konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der Konvertierung von XHTML in PDF direkt in Ihrem Browser! Bitte laden Sie eine XHTML-Datei aus dem lokalen Dateisystem, wählen Sie das gewünschte Ausgabeformat aus der Liste und führen Sie das Beispiel aus. Es ist schnell, einfach, sicher und völlig kostenlos! Die Konvertierung von XHTML in PDF erfolgt mit den Standardspeicheroptionen. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie also schnell jede Webseite oder XHTML in das PDF-Format online!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter XHTML PDF BMP TIFF PNG "JPG|JPEG" GIF PDF XPS DOCX MHTML MD >}}
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
h2: Schritte zum Konvertieren von XHTML in PDF in C#
---

Wenn Sie XHTML programmgesteuert in PDF konvertieren möchten, sehen Sie sich bitte das obige C#-Codebeispiel an oder lesen Sie das Kapitel Dokumentation. In allen Fällen erfordert jede Konvertierung von XHTML in PDF einige obligatorische Schritte:
1. Laden Sie eine XHTML-Datei mit einem der HTMLDocument()-Konstruktoren der Klasse [HTMLDocument](https://apireference.aspose.com/html/net/aspose.html/htmldocument).
1. Erstellen Sie ein neues [PdfSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions)-Objekt.
1. Verwenden Sie die Methode [ConvertHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) der Converter-Klasse, um XHTML als PDF-Datei zu speichern.
1. Die PDF-Datei wird im angegebenen Pfad gespeichert.




{{<section documentation>}}
---
h2: (X)HTML-Konvertierung in der Dokumentation
---

Die Konvertierung von XHTML in PDF ist häufig erforderlich, um einen eingeschränkten Zugriff auf die Bearbeitung oder das Kopieren von Dokumenten einzurichten, offizielle Dokumente zu erstellen oder bestimmte Informationen zu versenden, beispielsweise per E-Mail. Mit Aspose.HTML für .NET API können Sie (X)HTML schnell und in hoher Qualität in andere gängige Formate konvertieren. Bitte besuchen Sie das Dokumentationskapitel <a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">Converting between Formats</a>, um mehr über die API zu erfahren Konvertierungsfunktionen. Das Kapitel beschreibt beliebte Konverter sowie C#-Beispiele für die gängigsten Konvertierungsszenarien.

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