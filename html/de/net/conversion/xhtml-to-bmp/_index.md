---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie XHTML in BMP
description: Konvertieren Sie XHTML in C# in BMP. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie kostenlos online XHTML to BMP Converter aus!
url: /net/conversion/xhtml-to-bmp/
family: html
platformtag: net
feature: conversion
informat: XHTML
outformat: BMP
otherformats: PDF DOCX XPS GIF JPEG PNG TIFF BMP HTML MHTML MD
---

{{<section banner>}}
---
h1: Konvertieren Sie XHTML über C# in BMP
h2: Generieren Sie BMP aus einer XHTML-Quellseite mit der .NET-API. Konvertieren Sie mit unserem kostenlosen Online-Konverter sofort XHTML in das BMP-Format!
---

{{<section overview>}}
---
h2: Konvertieren Sie XHTML in BMP mit C#
---

Das wichtigste Highlight der [Aspose.HTML .NET](https://products.aspose.com/html/net/) API ist eine Konvertierungsfunktion. Mit unserer leistungsstarken Bibliothek können Sie XHTML programmgesteuert in das BMP-Format konvertieren, wobei Sie die volle Kontrolle über verschiedene Konvertierungsparameter haben. Jede Konvertierung, die Sie durchführen möchten, beinhaltet das Laden eines XHTML-Dokuments und das Speichern im unterstützten Format. Mit der leistungsstarken C#-API können Sie XHTML schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der Konvertierung von XHTML in BMP direkt in Ihrem Browser! Bitte laden Sie eine XHTML-Datei aus dem lokalen Dateisystem, wählen Sie das gewünschte Ausgabeformat aus der Liste und führen Sie das Beispiel aus. Es ist schnell, einfach, sicher und völlig kostenlos! Die Konvertierung von XHTML in BMP erfolgt mit den Standardspeicheroptionen. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie also schnell jede Webseite oder XHTML in das BMP-Format online!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter XHTML BMP TIFF PNG "JPG|JPEG" GIF PDF XPS DOCX MD MHTML>}}
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
h2: Schritte zum Konvertieren von XHTML in BMP in C#
---

Wenn Sie XHTML programmgesteuert in BMP konvertieren möchten, sehen Sie sich bitte das obige C#-Codebeispiel an oder lesen Sie das Kapitel Dokumentation. In allen Fällen erfordert jede XHTML-Konvertierung einige obligatorische Schritte:
1. Laden Sie ein XHTML-Dokument mit einem der [HTMLDocument()](https://apireference.aspose.com/html/net/aspose.html/htmldocument)-Konstruktoren.
1. Erstellen Sie ein neues [ImageSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions)-Objekt mit BMP ImageFormat. Standardmäßig ist die Format-Eigenschaft [PNG](https://apireference.aspose.com/html/net/aspose.html.rendering.image/imageformat).
1. Verwenden Sie die Methode [ConvertHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/converthtml/), um XHTML als BMP-Datei zu speichern. Sie müssen HTMLDocument, ImageSaveOptions und den Ausgabedateipfad an die ConvertHTML()-Methode übergeben.
1. Die BMP-Datei wird im angegebenen Pfad gespeichert.




{{<section documentation>}}
---
h2: (X)HTML-Konvertierung in der Dokumentation
---

Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um verschiedene Formate für bestimmte Aufgaben zu nutzen. Mit Aspose.HTML für .NET API können Sie (X)HTML schnell und mit hoher Qualität in andere gängige Formate konvertieren. Bitte besuchen Sie das Dokumentationskapitel <a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">Converting between Formats</a>, um mehr über Aspose zu erfahren. HTML für .NET-API-Konvertierungsfunktionen. Das Kapitel beschreibt beliebte Konverter sowie C#-Beispiele für die gängigsten Konvertierungsszenarien.

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