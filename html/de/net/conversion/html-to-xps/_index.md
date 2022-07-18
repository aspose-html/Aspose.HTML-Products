---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie HTML in XPS - C# - Online-Konverter von HTML in XPS
description: Konvertieren Sie HTML in XPS in C#. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie kostenlos den Online-Konverter von HTML zu XPS aus!
url: /net/conversion/html-to-xps/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: XPS
otherformats: PDF DOCX GIF JPEG PNG TIFF BMP XHTML MHTML MD
---

{{<section banner>}}
---
h1: Konvertieren Sie HTML in XPS über C#
h2: Generieren Sie XPS aus einer HTML-Quellseite mithilfe der .NET-API. Konvertieren Sie mit unserem kostenlosen Online-Konverter sofort HTML in das XPS-Format.
---

{{<section overview>}}
---
h2: Konvertieren Sie HTML in XPS mit C#
---

HTML-Dateien werden häufig verwendet, um viele Informationen zu erstellen, zu bearbeiten oder zu kommunizieren. Die Konvertierung von HTML in XPS ist häufig erforderlich, um einen eingeschränkten Zugriff auf das Bearbeiten oder Kopieren von Dokumenten einzurichten. Das XPS-Dateiformat ermöglicht die Verwaltung von Zugriffsrechten und liefert qualitativ hochwertige druckbare Dokumente. Mit der API [Aspose.HTML for .NET](https://products.aspose.com/html/net/) können Sie HTML programmgesteuert in XPS umwandeln und dabei die volle Kontrolle über eine Vielzahl von Konvertierungsparametern haben. Es gibt verschiedene Fälle für die HTML-zu-XPS-Konvertierung, z. B. das Lesen aus einer Datei, einer URL, einem WYSISYG-Editor, einer Zeichenfolge oder einem Stream. Mit der leistungsstarken C#-API können Sie HTML schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der HTML-zu-XPS-Konvertierung direkt in Ihrem Browser! Bitte laden Sie eine HTML-Datei aus dem lokalen Dateisystem, wählen Sie das gewünschte Ausgabeformat aus der Liste und führen Sie das Beispiel aus. Es ist schnell, einfach, sicher und völlig kostenlos! Die HTML-zu-XPS-Konvertierung erfolgt mit den Standardspeicheroptionen. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie also schnell jede Webseite oder HTML in das XPS-Format online!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML  XPS PDF MD "JPG|JPEG" GIF DOCX BMP TIFF PNG MHTML >}}
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
h2: Schritte zum Konvertieren von HTML in XPS in C#
---

Wenn Sie die Konvertierungsfunktionalität in Ihrem Produkt in Betracht ziehen oder HTML programmgesteuert in XPS konvertieren möchten, sehen Sie sich bitte das obige C#-Codebeispiel an oder lesen Sie das Kapitel Dokumentation. In allen Fällen erfordert jede Konvertierung einige obligatorische Schritte:
1. Laden Sie ein HTML-Dokument mit einem der [HTMLDocument()](https://apireference.aspose.com/html/net/aspose.html/htmldocument)-Konstruktoren. Sie können HTML aus einer Datei, einem HTML-Code, einem Stream oder einer URL laden.
1. Erstellen Sie ein neues [XpsSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions)-Objekt.
1. Verwenden Sie die Methode [ConvertHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) der Converter-Klasse, um HTML als XPS-Datei zu speichern. Sie müssen HTMLDocument, XpsSaveOptions und den Ausgabedateipfad an die ConvertHTML()-Methode übergeben.
1. Die XPS-Datei wird im angegebenen Pfad gespeichert.




{{<section documentation>}}
---
h2: HTML-zu-XPS-Konvertierung in der Dokumentation
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#html-to-xps-by-a-single-line-of-code " target="_blank">Konvertieren Sie HTML in XPS mit einer einzigen Codezeile</a>
  - Ziel <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-in-c-using-xpssaveoptions". ="_blank">Konvertieren Sie HTML in XPS mit XpsSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#output-stream-providers" target="_blank">Konvertieren Sie HTML in XPS mit MemoryStreamProvider</a>

XPS ist ein von Microsoft entwickeltes Format zum Speichern und Anzeigen von Dokumenten. Es hat eine Reihe von Vorteilen, die Sicherheitsfunktionen unterstützen, wie z. B. digitale Signaturen für mehr Dokumentensicherheit und mehr. Bitte besuchen Sie den Dokumentationsartikel [Convert HTML to XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/), um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und C#-Beispiele für die häufigsten Konvertierungsszenarien von HTML in XPS. In diesem Artikel finden Sie Informationen zum Konvertieren von HTML in XPS mithilfe von ConvertHTML()-Methoden und zum Anwenden von XpsSaveOptions- und ICreateStreamProvider-Parametern.

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