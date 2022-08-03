---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie XHTML in MD
description: Konvertieren Sie XHTML in MD in C#. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie kostenlos online XHTML to MD Converter aus!
url: /net/conversion/xhtml-to-md/
family: html
platformtag: net
feature: conversion
informat: XHTML
outformat: MD
otherformats: PDF XPS DOCX GIF JPEG PNG TIFF BMP HTML MHTML
howto: howtoXhtml
---

{{<section banner>}}
---
h1: Konvertieren Sie XHTML über C# in MD
h2: Generieren Sie MD aus der XHTML-Quellseite mit der .NET-API. Konvertieren Sie mit unserem kostenlosen Online-Konverter sofort XHTML in das MD-Format!
---

{{<section overview>}}
---
h2: Konvertieren Sie XHTML in MD mit C#
---

Markdown ist eine Auszeichnungssprache mit einer Nur-Text-Formatierungssyntax. Sein Design ermöglicht eine einfache Konvertierung in viele Ausgabeformate, aber ursprünglich wurde es nur für die Konvertierung in HTML erstellt. Die Aspose.HTML-Klassenbibliothek bietet eine umgekehrte Konvertierung von (X)HTML nach Markdown. Mit der API [Aspose.HTML for .NET](https://products.aspose.com/html/net/) können Sie XHTML programmgesteuert in MD umwandeln, wobei Sie die Konvertierungsparameter vollständig steuern können. Jede Konvertierung, die Sie durchführen möchten, beinhaltet das Laden eines XHTML-Dokuments und das Speichern im Markdown-Format. Mit der leistungsstarken C#-API können Sie XHTML schnell und in hoher Qualität in MD konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der Konvertierung von XHTML in MD direkt in Ihrem Browser! Bitte laden Sie eine XHTML-Datei aus dem lokalen Dateisystem, wählen Sie das gewünschte Ausgabeformat aus der Liste und führen Sie das Beispiel aus. Es ist schnell, einfach, sicher und völlig kostenlos! Die Konvertierung von XHTML in MD erfolgt mit den Standardspeicheroptionen. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie also schnell jede Webseite oder XHTML in das MD-Format online!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter XHTML MD BMP TIFF PNG "JPG|JPEG" GIF PDF XPS DOCX MHTML >}}
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
h2: Schritte zum Konvertieren von XHTML in MD in C#
---

Wenn Sie XHTML programmgesteuert in MD konvertieren möchten, sehen Sie sich bitte das obige C#-Codebeispiel an oder lesen Sie das Kapitel Dokumentation. In allen Fällen erfordert jede Konvertierung von XHTML in MD einige obligatorische Schritte:

1. Laden Sie eine XHTML-Datei mit einem der HTMLDocument()-Konstruktoren der Klasse [HTMLDocument](https://reference.aspose.com/html/net/aspose.html/htmldocument/).
1. Erstellen Sie ein neues [MarkdownSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions/)-Objekt.
1. Verwenden Sie die Methode [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) der Converter-Klasse, um XHTML als Markdown-Datei zu speichern.
1. Die MD-Datei wird im angegebenen Pfad gespeichert.

{{<section documentation>}}
---
h2: (X)HTML-Konvertierung in der Dokumentation
---

Mit Aspose.HTML für .NET API können Sie (X)HTML schnell und mit hoher Qualität in andere gängige Formate konvertieren. Bitte besuchen Sie das Dokumentationskapitel <a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">Converting between Formats</a>, um mehr über die API zu erfahren Konvertierungsfunktionen. Das Kapitel beschreibt beliebte Konverter sowie C#-Beispiele für die gängigsten Konvertierungsszenarien.

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