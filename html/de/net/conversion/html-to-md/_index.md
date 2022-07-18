---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie HTML in MD in C# .NET - Online-Konverter von HTML in MD
description: Konvertieren Sie HTML in MD in C#. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie den Online-HTML-zu-MD-Konverter kostenlos aus!
url: /net/conversion/html-to-md/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: MD
otherformats: PDF DOCX XPS GIF JPEG PNG TIFF BMP XHTML MHTML
---

{{<section banner>}}
---
h1: Konvertieren Sie HTML in MD über C#
h2: Generieren Sie MD aus der HTML-Quellseite mithilfe der .NET-API. Konvertieren Sie mit unserem kostenlosen Online-Konverter sofort HTML in das MD-Format.
---

{{<section overview>}}
---
h2: Konvertieren Sie HTML in MD mit C#
---

Markdown ist eine Auszeichnungssprache mit einer Nur-Text-Formatierungssyntax. Sein Design ermöglicht eine einfache Konvertierung in viele Ausgabeformate, aber ursprünglich wurde es nur für die Konvertierung in HTML erstellt. Die Aspose.HTML-Klassenbibliothek bietet eine umgekehrte Konvertierung von HTML zu Markdown. Mit der API [Aspose.HTML for .NET](https://products.aspose.com/html/net/) können Sie HTML programmgesteuert in MD umwandeln und dabei die volle Kontrolle über eine Vielzahl von Konvertierungsparametern haben. Es gibt verschiedene Fälle für die HTML-zu-MD-Konvertierung, z. B. das Lesen von HTML aus einer Datei, einer URL, einem WYSISYG-Editor, einer Zeichenfolge oder einem Stream. Mit der leistungsstarken C#-API können Sie HTML schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der HTML-zu-MD-Konvertierung direkt in Ihrem Browser! Bitte laden Sie eine HTML-Datei aus dem lokalen Dateisystem, wählen Sie das gewünschte Ausgabeformat aus der Liste und führen Sie das Beispiel aus. Es ist schnell, einfach, sicher und völlig kostenlos! Die HTML-zu-MD-Konvertierung erfolgt mit den Standardspeicheroptionen. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie also schnell jede Webseite oder HTML in das MD-Format online!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML MD PDF "JPG|JPEG" GIF DOCX BMP XPS TIFF PNG MHTML >}}
using Aspose.Html;
using Aspose.Html.Converters;
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
    Converter.ConvertHTML(document, options, "output.{{output lower}}");   
{{< /app/html/converter>}} 


{{<section steps>}}
---
h2: Schritte zum Konvertieren von HTML in MD in C#
---

Wenn Sie die Konvertierungsfunktionalität in Ihrem Produkt in Betracht ziehen oder HTML programmgesteuert in MD konvertieren möchten, sehen Sie sich bitte das obige C#-Codebeispiel an oder lesen Sie das Kapitel Dokumentation. In allen Fällen erfordert jede Konvertierung einige obligatorische Schritte:
1. Laden Sie ein HTML-Dokument mit einem der [HTMLDocument()](https://apireference.aspose.com/html/net/aspose.html/htmldocument)-Konstruktoren. Sie können HTML aus einer Datei, einem HTML-Code, einem Stream oder einer URL laden.
1. Erstellen Sie ein neues [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions)-Objekt.
1. Verwenden Sie die Methode [ConvertHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) der Converter-Klasse, um HTML als Markdown-Datei zu speichern. Sie müssen HTMLDocument, MarkdownSaveOptions und den Ausgabedateipfad an die ConvertHTML()-Methode übergeben.
1. Die MD-Datei wird im angegebenen Pfad gespeichert.




{{<section documentation>}}
---
h2: Konvertierung von HTML zu Markdown in der Dokumentation
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#html-to-markdown-by-a-few-lines-of-code " target="_blank">HTML zu Markdown durch ein paar Codezeilen</a>
  - Ziel <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-in-c-using-markdownsaveoptions". ="_blank">HTML mit MarkdownSaveOptions in Markdown konvertieren</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#limitation" target="_blank">Konvertierungsbeschränkung</a>

Bitte besuchen Sie den Dokumentationsartikel [Convert HTML to Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/), um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und um C#-Beispiele für die gängigsten Konvertierungsszenarien von HTML in MD zu betrachten. In diesem Artikel finden Sie Informationen zum Konvertieren von HTML in MD mithilfe von ConvertHTML()-Methoden und zum Anwenden von MarkdownSaveOptions- und ICreateStreamProvider-Parametern.

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