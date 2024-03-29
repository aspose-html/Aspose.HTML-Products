﻿---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie HTML in MHTML
description: Konvertieren Sie HTML in MHTML mit C#. HTML-Seite als MHTML in C#-Code speichern. Probieren Sie den Online-HTML-zu-MHTML-Konverter kostenlos aus!
url: /net/conversion/html-to-mhtml/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: MHTML
otherformats: DOCX PDF XPS GIF JPEG PNG TIFF BMP XHTML MD
---

{{<section banner>}}
---
h1: Konvertieren Sie HTML über C# in MHTML
h2: Generieren Sie MHTML aus einer HTML-Quellseite mithilfe der .NET-API. Konvertieren Sie mit unserem kostenlosen Online-Konverter sofort HTML in das MHTML-Format.
---

{{<section overview>}}
---
h2: Konvertieren Sie HTML in MHTML mit C#
---

HTML-Dateien werden häufig verwendet, um viele Informationen zu erstellen, zu bearbeiten oder zu kommunizieren. Der Vorteil des Speicherns von HTML als MHTML besteht darin, dass alle Webseitenelemente in einer einzigen Datei intakt bleiben. MHTML enthält ein zugrunde liegendes HTML-Dokument und seine eingebetteten Bilder, Medien und anderen Ressourcen. Mit der API [Aspose.HTML for .NET](https://products.aspose.com/html/net/) können Sie HTML programmgesteuert in MHTML umwandeln und dabei die volle Kontrolle über eine Vielzahl von Konvertierungsparametern haben. Es gibt verschiedene Fälle für die HTML-zu-MHTML-Konvertierung, z. B. das Lesen aus einer Datei, einer URL, einem WYSISYG-Editor, einer Zeichenfolge oder einem Stream. Mit der leistungsstarken C#-API können Sie HTML schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der HTML-zu-MHTML-Konvertierung direkt in Ihrem Browser! Bitte laden Sie eine HTML-Datei aus dem lokalen Dateisystem, wählen Sie das gewünschte Ausgabeformat aus der Liste und führen Sie das Beispiel aus. Es ist schnell, einfach, sicher und völlig kostenlos! Die HTML-zu-MHTML-Konvertierung erfolgt mit den Standardspeicheroptionen. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie also schnell jede Webseite oder HTML in das MHTML-Format online!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML MHTML PDF MD "JPG|JPEG" GIF DOCX BMP XPS TIFF PNG >}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new HTMLDocument("{{input lower}}");
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
h2: Schritte zum Konvertieren von HTML in MHTML in C#
---

Wenn Sie die Konvertierungsfunktionalität in Ihrem Produkt in Betracht ziehen oder HTML programmgesteuert in MHTML konvertieren möchten, sehen Sie sich bitte das obige C#-Codebeispiel an oder lesen Sie das Kapitel Dokumentation. In allen Fällen erfordert jede Konvertierung einige obligatorische Schritte:
1. Laden Sie ein HTML-Dokument mit einem der [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/)-Konstruktoren. Sie können HTML aus einer Datei, einem HTML-Code, einem Stream oder einer URL laden.
1. Erstellen Sie ein neues [MHTMLSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/mhtmlsaveoptions/)-Objekt.
1. Verwenden Sie die Methode [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) der Converter-Klasse, um HTML als MHTML-Datei zu speichern. Sie müssen HTMLDocument, MHTMLSaveOptions und den Ausgabedateipfad an die Methode ConvertHTML() übergeben.
1. Die MHTML-Datei wird im angegebenen Pfad gespeichert.

{{<section documentation>}}
---
h2: HTML-zu-MHTML-Konvertierung in der Dokumentation
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#html-to-mhtml-by-a-single-line-of-code " target="_blank">Konvertieren Sie HTML in MHTML mit einer einzigen Codezeile</a>
  - Ziel <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/#convert-html-to-mhtml-in-c-using-mhtmlsaveoptions" target="_blank">Konvertieren Sie HTML in MHTML mit MHTMLSaveOptions</a>

MHTML kombiniert normales HTML mit externen Ressourcen wie Bildern, Animationen, Audio usw. in einer Datei mit der Dateierweiterung .mht. Aspose.HTML für .NET API ermöglicht Ihnen, HTML schnell und mit hoher Qualität in das MHTML-Format zu konvertieren. Bitte besuchen Sie den Dokumentationsartikel [Convert HTML to MHTML,](https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/) um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und C#-Beispiele für die gängigsten HTML-zu-MHTML-Konvertierungsszenarien zu betrachten. In diesem Artikel finden Sie Informationen zum Konvertieren von HTML in MHTML mithilfe von ConvertHTML()-Methoden und zum Anwenden von MHTMLSaveOptions- und ICreateStreamProvider-Parametern.

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