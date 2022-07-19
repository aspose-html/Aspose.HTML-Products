---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie HTML in BMP
description: Konvertieren Sie HTML in C# in BMP. Verwenden Sie einfach die Konverter-API innerhalb von ASP.NET oder einer beliebigen .NET-Anwendung. Probieren Sie den Online-HTML-zu-BMP-Konverter kostenlos aus!
url: /net/conversion/html-to-bmp/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: BMP
otherformats: PDF DOCX XPS GIF JPEG PNG TIFF BMP XHTML MHTML MD
---

{{<section banner>}}
---
h1: Konvertieren Sie HTML in BMP über C#
h2: Generieren Sie BMP aus der HTML-Quellseite mit der .NET-API. Konvertieren Sie HTML sofort in das BMP-Format mit unserem kostenlosen Online-Konverter!
---

{{<section overview>}}
---
h2: Konvertieren Sie HTML in BMP mit C#
---

HTML-Dateien werden häufig verwendet, um viele Informationen zu erstellen, zu bearbeiten oder zu kommunizieren. Wenn Sie HTML-Dateien in eine PowerPoint-Präsentation einfügen oder per E-Mail versenden möchten, konvertieren Sie sie bitte in das entsprechende Bildformat und verwenden Sie sie wie Sie möchten! Mit der API [Aspose.HTML for .NET](https://products.aspose.com/html/net/) können Sie HTML programmgesteuert in BMP umwandeln und dabei die volle Kontrolle über eine Vielzahl von Konvertierungsparametern haben. Es gibt verschiedene Fälle für die HTML-zu-BMP-Konvertierung, z. B. das Lesen aus einer Datei, einer URL, einem WYSISYG-Editor, einer Zeichenfolge oder einem Stream. Mit der leistungsstarken C#-API können Sie HTML schnell und in hoher Qualität in gängige Formate konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der HTML-zu-BMP-Konvertierung direkt in Ihrem Browser! Bitte laden Sie eine HTML-Datei aus dem lokalen Dateisystem, wählen Sie das gewünschte Ausgabeformat aus der Liste und führen Sie das Beispiel aus. Es ist schnell, einfach, sicher und völlig kostenlos! Die HTML-zu-BMP-Konvertierung erfolgt mit den Standardspeicheroptionen. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie also schnell jede Webseite oder HTML in das BMP-Format online!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML BMP PDF MD "JPG|JPEG" GIF DOCX XPS TIFF PNG MHTML >}}
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
h2: So konvertieren Sie HTML in BMP in C#
---

Wenn Sie die Konvertierungsfunktionalität in Ihrem Produkt in Betracht ziehen oder HTML programmgesteuert in BMP konvertieren möchten, sehen Sie sich bitte das obige C#-Codebeispiel an oder lesen Sie das Kapitel Dokumentation. In allen Fällen erfordert jede Konvertierung einige obligatorische Schritte:
1. Laden Sie ein HTML-Dokument mit einem der [HTMLDocument()](https://apireference.aspose.com/html/net/aspose.html/htmldocument)-Konstruktoren. Sie können HTML aus einer Datei, einem HTML-Code, einem Stream oder einer URL laden.
1. Erstellen Sie ein neues [ImageSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions)-Objekt mit BMP ImageFormat. Standardmäßig ist die Format-Eigenschaft PNG.
1. Verwenden Sie die Methode [ConvertHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) der Converter-Klasse, um HTML als BMP-Datei zu speichern. Sie müssen HTMLDocument, ImageSaveOptions und den Ausgabedateipfad an die ConvertHTML()-Methode übergeben.
1. Die BMP-Datei wird im angegebenen Pfad gespeichert.



<script class="ld-howto" type="application/ld+json">{"@context":"http://schema.org/","@type":"HowTo","name":"How to create color palette","image":"https://products.aspose.app/img/howto.png","totalTime":"PT1M","estimatedCost":{"@type":"MonetaryAmount","currency":"USD","value":"0"},"supply":[{"@type":"HowToSupply","name":"Create color combinations and save palettes with HEX color codes."}],"tool":[{"@type":"HowToTool","name":"Color Wheel"}],"step":[{"@type":"HowToStep","name":"Drag and click your cursor inside the Color Wheel area to highlight the color. Click the Color Wheel area again to generate a new one. Create paints as many as you need.","text":"Drag and click your cursor inside the Color Wheel area to highlight the color. Click the Color Wheel area again to generate a new one. Create paints as many as you need.","image":"https://products.aspose.app/html/assets/howto/color-wheel/step0.png","url":"html/color-wheel#howto"},{"@type":"HowToStep","name":"You can set the contrast and brightness for the selected color to achieve the desired result.","text":"You can set the contrast and brightness for the selected color to achieve the desired result.","image":"https://products.aspose.app/html/assets/howto/color-wheel/step1.png","url":"html/color-wheel#howto"},{"@type":"HowToStep","name":"To create a palette, click on the “Add to palette“ button: the chosen color will appear in the palette area. If you want to delete a paint, click the “Remove“ button.","text":"To create a palette, click on the “Add to palette“ button: the chosen color will appear in the palette area. If you want to delete a paint, click the “Remove“ button.","image":"https://products.aspose.app/html/assets/howto/color-wheel/step2.png","url":"html/color-wheel#howto"},{"@type":"HowToStep","name":"Color Wheel app generates a set of paints in HEX color codes. You can save HEX codes of the palette as HTML, CSS or JSON files.","text":"Color Wheel app generates a set of paints in HEX color codes. You can save HEX codes of the palette as HTML, CSS or JSON files.","image":"https://products.aspose.app/html/assets/howto/color-wheel/step3.png","url":"html/color-wheel#howto"}]}</script>

{{<section documentation>}}
---
h2: HTML-zu-BMP-Konvertierung in der Dokumentation
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/#convert-html-to-bmp" target="_blank">HTML konvertieren in BMP</a>
  - Ziel <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/#convert-html-to-bmp-in-c-using-imagesaveoptions" target="_blank">HTML in BMP konvertieren mit ImageSaveOptions</a>

BMP-Dateien sind Bitmap-Bilddateien, die zum Speichern hochwertiger digitaler Bitmap-Bilder verwendet werden. Daher kann es manchmal notwendig sein, HTML in BMP umzuwandeln. Bitte besuchen Sie den Dokumentationsartikel [Convert HTML to BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/), um mehr über Aspose.HTML für die .NET-API zu erfahren Konvertierungsfeatures und zur Betrachtung von C#-Beispielen für die gängigsten HTML-zu-BMP-Konvertierungsszenarien. In diesem Artikel finden Sie Informationen zum Konvertieren von HTML in BMP mithilfe von ConvertHTML()-Methoden und zum Anwenden von ImageSaveOptions- und ICreateStreamProvider-Parametern.

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