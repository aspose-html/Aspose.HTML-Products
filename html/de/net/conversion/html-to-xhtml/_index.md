---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie HTML in XHTML
description: Konvertieren Sie HTML in C# in XHTML. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie kostenlos den Online-HTML-zu-XHTML-Konverter aus!
url: /net/conversion/html-to-xhtml/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: XHTML
otherformats: DOCX PDF XPS GIF JPEG PNG TIFF BMP MHTML MD
---

{{<section banner>}}
---
h1: Konvertieren Sie HTML über C# in XHTML
h2: Generieren Sie XHTML aus einer HTML-Quellseite mit der .NET-API. Konvertieren Sie mit unserem kostenlosen Online-Konverter sofort HTML in das XHTML-Format.
---

{{<section overview>}}
---
h2: Konvertieren Sie HTML in XHTML mit C#
---

XHTML wurde so konzipiert, dass es strukturierter, weniger Skripting und generisch ist, alle vorhandenen Möglichkeiten von XML nutzt und geräteunabhängiger ist. Um HTML in XHTML zu konvertieren, verwenden wir die API [Aspose.HTML for .NET](https://products.aspose.com/html/net/), die eine funktionsreiche, leistungsstarke und benutzerfreundliche Dokumentbearbeitung ist und Konvertierungs-API für die C#-Plattform. Sie können HTML programmgesteuert in XHTML umwandeln und dabei die volle Kontrolle über eine Vielzahl von Konvertierungsparametern haben. Es gibt verschiedene Fälle für die HTML-zu-XHTML-Konvertierung, z. B. das Lesen aus einer Datei, einer URL, einem WYSISYG-Editor, einer Zeichenfolge oder einem Stream. Mit der leistungsstarken C#-API können Sie HTML schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: So konvertieren Sie HTML in XHTML in C#
---

Das folgende C#-Beispiel zeigt, wie ein HTML-Dokument konvertiert wird. Es gibt verschiedene Fälle für die HTML-zu-XHTML-Konvertierung, z. B. das Lesen von einer URL / Webseite, von WYSISYG-Editor generiertem HTML oder von einer gespeicherten Datei. Wir beschreiben den Quellcode für das Lesen von HTML aus einer Datei und das anschließende Konvertieren von HTML in XHTML mit der Methode Save().

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML XHTML MHTML PDF MD "JPG|JPEG" GIF DOCX BMP XPS TIFF PNG>}}
using Aspose.Html;
using Aspose.Html.Saving;

    using var document = new HTMLDocument("document.{{input lower}}");
{{#if_output 'PDF'}}
    var options = new PdfSaveOptions();
{{/if_output}}
{{#if_output 'MHTML'}}
    var options = new MHTMLSaveOptions();
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
{{#if_output 'BMP' 'JPG' 'GIF' 'PNG' 'TIFF'}}
    var options = new ImageSaveOptions(ImageFormat.{{output param2 camel}});
{{/if_output}}
{{#if_output 'BMP' 'JPG' 'GIF' 'PNG' 'TIFF' 'PDF' 'MHTML' 'MD' 'XPS' 'DOCX'}}
    Aspose.Html.Converters.Converter.ConvertHTML(document, options, "output.{{output lower}}"); 
{{/if_output}}
{{#if_output 'XHTML'}} 
    document.Save("output.xhtml", new HTMLSaveOptions() { DocumentType = HTMLSaveOptions.XHTML}); 
{{/if_output}}     
{{< /app/html/converter>}} 

{{<section steps>}}
---
h2: Schritte zum Konvertieren von HTML in XHTML in C#
---

Wenn Sie die Konvertierungsfunktionalität in Ihrem Produkt in Betracht ziehen oder HTML programmgesteuert in XHTML konvertieren möchten, sehen Sie sich bitte das obige C#-Codebeispiel an oder lesen Sie das Kapitel Dokumentation. Bitte führen Sie die folgenden obligatorischen Schritte aus:
1. Laden Sie ein HTML-Dokument mithilfe des Konstruktors [HTMLDocument(`string`)](https://reference.aspose.com/html/net/aspose.html/htmldocument/htmldocument/) in ein Document-Objekt. Sie können HTML aus einer Datei, einem HTML-Code, einem Stream oder einer URL laden.
1. Rufen Sie die Methode [Save(`string`, `HTMLSaveOptions`)](https://reference.aspose.com/html/net/aspose.html/htmldocument/save/) auf.
1. Übergeben Sie den Ausgabedateipfad mit der XHTML-Dateierweiterung.
1. Die XHTML-Datei wird im angegebenen Pfad gespeichert.

{{<section documentation>}}
---
h2: HTML-Konvertierung in der Dokumentation
---

Das Konvertieren zwischen Formaten ist aus verschiedenen Gründen erforderlich: um in einem vertrauten, bequemen Format zu arbeiten oder um verschiedene Formate für bestimmte Aufgaben zu nutzen. Mit Aspose.HTML für .NET API können Sie HTML schnell und in hoher Qualität in andere gängige Formate konvertieren. Bitte besuchen Sie das Dokumentationskapitel <a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">Converting between Formats</a>, um mehr über Aspose zu erfahren. HTML für .NET-API-Konvertierungsfunktionen. Das Kapitel beschreibt beliebte Konverter sowie C#-Beispiele für die gängigsten Konvertierungsszenarien.

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
title: Andere unterstützte HTML-Konvertierungen
subTitle: "Sie können HTML auch in viele andere Dateiformate konvertieren:"
---