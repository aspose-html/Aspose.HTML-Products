---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie XHTML in DOCX
description: Konvertieren Sie XHTML  in DOCX in C#. Speichern Sie XHTML als DOC-Datei. Probieren Sie XHTML to DOCX Converter kostenlos online aus!
url: /net/conversion/xhtml-to-docx/
family: html
platformtag: net
feature: conversion
informat: XHTML
outformat: DOCX
otherformats: PDF XPS GIF JPEG PNG TIFF BMP HTML MHTML MD
howto: howtoXhtml
---

{{<section banner>}}
---
h1: Konvertieren Sie XHTML über C# in DOCX
h2: Generieren Sie DOCX aus einer XHTML-Quellseite mit der .NET-API. Konvertieren Sie mit unserem kostenlosen Online-Konverter sofort XHTML in das DOCX-Format!
---

{{<section overview>}}
---
h2: Konvertieren Sie XHTML in DOCX mit C#
---

Das DOCX-Dateiformat ist eines der am häufigsten verwendeten und ist in zahlreichen Programmen verfügbar. Die DOCX-Datei ist in hohem Maße bearbeitbar, einfach zu verwenden und in der Größe überschaubar. Es kann mit MS Word oder einem anderen Word Viewer & Editor angezeigt, bearbeitet, durchsucht und gedruckt werden. Mit der [Aspose.HTML .NET](https://products.aspose.com/html/net/)-API können Sie XHTML programmgesteuert in DOCX konvertieren und dabei die vollständige Kontrolle über die Konvertierungsparameter behalten. Jede Konvertierung, die Sie durchführen möchten, beinhaltet das Laden eines XHTML-Dokuments und das Speichern im unterstützten Format. Mit der leistungsstarken C#-API können Sie XHTML schnell und in hoher Qualität in DOCX konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der Konvertierung von XHTML in DOCX direkt in Ihrem Browser! Bitte laden Sie eine XHTML-Datei aus dem lokalen Dateisystem, wählen Sie das gewünschte Ausgabeformat aus der Liste und führen Sie das Beispiel aus. Es ist schnell, einfach, sicher und völlig kostenlos! Die Konvertierung von XHTML in DOCX erfolgt mit den Standardspeicheroptionen. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie also schnell jede Webseite oder XHTML in das DOCX-Format online!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter XHTML DOCX BMP TIFF PNG "JPG|JPEG" GIF PDF XPS MD MHTML>}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new HTMLDocument("{{input lower}}");
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
h2: Schritte zum Konvertieren von XHTML in DOCX in C#
---

Wenn Sie XHTML programmgesteuert in DOCX konvertieren möchten, sehen Sie sich bitte das obige C#-Codebeispiel an oder lesen Sie das Kapitel Dokumentation. In allen Fällen erfordert jede XHTML-Konvertierung einige obligatorische Schritte:

1. Laden Sie eine XHTML-Datei mit einem der HTMLDocument()-Konstruktoren der Klasse [HTMLDocument](https://reference.aspose.com/html/net/aspose.html/htmldocument/).
1. Erstellen Sie ein neues [DocSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/docsaveoptions/)-Objekt.
1. Verwenden Sie die Methode [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) der Converter-Klasse, um XHTML als DOCX-Datei zu speichern.
1. Die DOCX-Datei wird im angegebenen Pfad gespeichert.

{{<section documentation>}}
---
h2: (X)HTML-Konvertierung in der Dokumentation
---

Die Konvertierung von XHTML in DOCX ist häufig erforderlich, um das DOCX-Format für bestimmte Aufgaben zu nutzen. Das DOCX-Format ist beliebt, weil es eine Vielzahl von Formatierungsfunktionen unterstützt und Benutzern eine Vielzahl von Optionen bietet, um jede Art von Dokument zu schreiben. Mit Aspose.HTML für .NET API können Sie (X)HTML schnell und mit hoher Qualität in andere gängige Formate konvertieren. Bitte besuchen Sie das Dokumentationskapitel <a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">Converting between Formats</a>, um mehr über die API zu erfahren Konvertierungsfunktionen. Das Kapitel beschreibt beliebte Konverter sowie C#-Beispiele für die gängigsten Konvertierungsszenarien.

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