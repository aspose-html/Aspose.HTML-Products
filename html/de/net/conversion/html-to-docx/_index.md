---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie HTML in DOCX in C# .NET
description: Konvertieren Sie HTML in C# in DOCX. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie den Online-HTML-zu-DOCX-Konverter kostenlos aus!
url: /net/conversion/html-to-docx/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: DOCX
otherformats: PDF XPS GIF JPEG PNG TIFF BMP XHTML MHTML MD
---

{{<section banner>}}
---
h1: Konvertieren Sie HTML in DOCX über C#
h2: Generieren Sie DOCX aus der HTML-Quellseite mit der .NET-API. Konvertieren Sie mit unserem kostenlosen Online-Konverter sofort HTML in das DOCX-Format.
---

{{<section overview>}}
---
h2: Konvertieren Sie HTML in DOCX mit C#
---

Das DOCX-Dateiformat ist eines der am häufigsten verwendeten und ist in zahlreichen Programmen verfügbar. Die DOCX-Datei ist in hohem Maße bearbeitbar, einfach zu verwenden und in der Größe überschaubar. Es kann mit MS Word oder einem anderen Word Viewer & Editor angezeigt, bearbeitet, durchsucht und gedruckt werden. Mit der API [Aspose.HTML for .NET](https://products.aspose.com/html/net/) können Sie HTML programmgesteuert in DOCX umwandeln und dabei die volle Kontrolle über eine Vielzahl von Konvertierungsparametern haben. Es gibt verschiedene Fälle für die HTML-zu-DOCX-Konvertierung, z. B. das Lesen aus einer Datei, einer URL, einem WYSISYG-Editor, einer Zeichenfolge oder einem Stream. Mit der leistungsstarken C#-API können Sie HTML schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der HTML-zu-DOCX-Konvertierung direkt in Ihrem Browser! Bitte laden Sie eine HTML-Datei aus dem lokalen Dateisystem, wählen Sie das gewünschte Ausgabeformat aus der Liste und führen Sie das Beispiel aus. Es ist schnell, einfach, sicher und völlig kostenlos! Die HTML-zu-DOCX-Konvertierung erfolgt mit den Standardspeicheroptionen. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie also schnell jede Webseite oder HTML in das DOCX-Format online!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML DOCX PDF MD "JPG|JPEG" GIF BMP XPS TIFF PNG MHTML >}}
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
h2: Schritte zum Konvertieren von HTML in DOCX in C#
---

Wenn Sie die Konvertierungsfunktionalität in Ihrem Produkt in Betracht ziehen oder HTML programmgesteuert in DOCX konvertieren möchten, sehen Sie sich bitte das obige C#-Codebeispiel an oder lesen Sie das Kapitel Dokumentation. In allen Fällen erfordert jede Konvertierung einige obligatorische Schritte:
1. Laden Sie ein HTML-Dokument mit einem der [HTMLDocument()](https://apireference.aspose.com/html/net/aspose.html/htmldocument)-Konstruktoren. Sie können HTML aus einer Datei, einem HTML-Code, einem Stream oder einer URL laden.
1. Erstellen Sie ein neues [DocSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/docsaveoptions)-Objekt.
1. Verwenden Sie die Methode [ConvertHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) der Converter-Klasse, um HTML als DOCX-Datei zu speichern. Sie müssen HTMLDocument, DocSaveOptions und den Ausgabedateipfad an die ConvertHTML()-Methode übergeben.
1. Die DOCX-Datei wird im angegebenen Pfad gespeichert.




{{<section documentation>}}
---
h2: HTML-zu-DOCX-Konvertierung in der Dokumentation
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#html-to-docx-durch-eine-einzelne-codezeile " target="_blank">Konvertieren Sie HTML in DOCX mit einer einzigen Codezeile</a>
  - Ziel <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-in-c-using-docsaveoptions" target="_blank">HTML mit DocSaveOptions in DOCX konvertieren</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#output-stream-providers" target="_blank">Konvertieren Sie HTML in DOCX mit MemoryStreamProvider</a>

Die Konvertierung von HTML in DOCX ist häufig erforderlich, um das DOCX-Format für bestimmte Aufgaben zu nutzen. Dieses Format ist beliebt, weil es eine Vielzahl von Formatierungsfunktionen unterstützt und Benutzern eine Vielzahl von Optionen bietet, um jede Art von Dokument zu schreiben. Bitte besuchen Sie den Dokumentationsartikel [Convert HTML to DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/), um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und zur Betrachtung von C#-Beispielen für die häufigsten Konvertierungsszenarien von HTML in DOCX. In diesem Artikel finden Sie Informationen zum Konvertieren von HTML in DOCX mithilfe von ConvertHTML()-Methoden und zum Anwenden von DocSaveOptions- und ICreateStreamProvider-Parametern.

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