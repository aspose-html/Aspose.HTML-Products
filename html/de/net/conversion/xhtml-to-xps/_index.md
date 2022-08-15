---
translation: true
template: /templates/_template-conversion-child.md
title: Konvertieren Sie XHTML in XPS in C# - Online XHTML to XPS Converter
description: Konvertieren Sie XHTML in C# in XPS. Speichern Sie XHTML als XPS-Datei. Probieren Sie den Online XHTML to XPS Converter kostenlos aus!
url: /net/conversion/xhtml-to-xps/
family: html
platformtag: net
feature: conversion
informat: XHTML
outformat: XPS
otherformats: PDF DOCX GIF JPEG PNG TIFF BMP HTML MHTML MD
howto: howtoXhtml
---

{{<section banner>}}
---
h1: Konvertieren Sie XHTML über C# in XPS
h2: Generieren Sie XPS aus einer XHTML-Quellseite mit der .NET-API. Konvertieren Sie mit unserem kostenlosen Online-Konverter sofort XHTML in das XPS-Format!
---

{{<section overview>}}
---
h2: Konvertieren Sie XHTML in XPS mit C#
---

Das wichtigste Highlight der [Aspose.HTML .NET](https://products.aspose.com/html/net/) API ist eine Konvertierungsfunktion. Mit unserer leistungsstarken Bibliothek können Sie XHTML programmgesteuert in XPS konvertieren, wobei Sie die volle Kontrolle über verschiedene Konvertierungsparameter haben. Das XPS-Dateiformat ermöglicht die Verwaltung von Zugriffsrechten und liefert qualitativ hochwertige druckbare Dokumente. Jede Konvertierung, die Sie durchführen möchten, beinhaltet das Laden eines XHTML-Dokuments und das Speichern im unterstützten Format. Mit der leistungsstarken C#-API können Sie XHTML schnell und in hoher Qualität in XPS konvertieren!

{{<section demos>}}
---
h2: Kostenlose Online-Konverter-Live-Demos
---

Testen Sie die Qualität der Konvertierung von XHTML in XPS direkt in Ihrem Browser! Bitte laden Sie eine XHTML-Datei aus dem lokalen Dateisystem, wählen Sie das gewünschte Ausgabeformat aus der Liste und führen Sie das Beispiel aus. Es ist schnell, einfach, sicher und völlig kostenlos! Die Konvertierung von XHTML in XPS erfolgt mit den Standardspeicheroptionen. Das Ergebnis erhalten Sie sofort als separate Datei. Konvertieren Sie also schnell jede Webseite oder XHTML in das XPS-Format online!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter XHTML XPS TIFF PNG "JPG|JPEG" GIF BMP PDF DOCX MD MHTML>}}
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
h2: Schritte zum Konvertieren von XHTML in XPS in C#
---

Jede Konvertierung, die Sie durchführen möchten, beinhaltet das Laden eines XHTML-Dokuments und das Speichern im XPS-Format. Um XHTML in XPS zu konvertieren, sollten Sie einige obligatorische Schritte ausführen:

1. Laden Sie ein XHTML-Dokument mit einem der [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/)-Konstruktoren.
1. Erstellen Sie ein neues [XpsSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/xpssaveoptions/)-Objekt.
1. Verwenden Sie die Methode [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/), um XHTML als XPS-Datei zu speichern. Sie müssen HTMLDocument, XpsSaveOptions und den Ausgabedateipfad an die ConvertHTML()-Methode übergeben.
1. Die XPS-Datei wird im angegebenen Pfad gespeichert.

{{<section documentation>}}
---
h2: (X)HTML-Konvertierung in der Dokumentation
---

XPS ist ein von Microsoft entwickeltes Format zum Speichern und Anzeigen von Dokumenten. Es hat eine Reihe von Vorteilen, die Sicherheitsfunktionen unterstützen, wie z. B. digitale Signaturen für mehr Dokumentensicherheit und mehr. Bitte besuchen Sie das Dokumentationskapitel <a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">Converting between Formats</a>, um mehr über die API zu erfahren Konvertierungsfunktionen. Das Kapitel beschreibt beliebte Konverter sowie C#-Beispiele für die gängigsten Konvertierungsszenarien.

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