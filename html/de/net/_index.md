---
translation: true
template: /templates/_template-net.md
title: C#-HTML-Parser – .NET-API für die Verarbeitung von HTML-Dateien
weight: 20
url: /net/
description: C# .NET-API zum Lesen, Schreiben, Ändern, Bearbeiten, Zusammenführen und Konvertieren von HTML, XHTML, MHTML, EPUB, Markdown und SVG.
---

{{<section banner>}}
---
h1: C#-API zum Analysieren von HTML-Dateien
h2: Klassenbibliothek zum Arbeiten mit realem HTML. Erstellen, bearbeiten, extrahieren Sie Daten, führen Sie HTML-Seiten zusammen und konvertieren Sie sie in PDF-, DOCX-, XPS-, Bilder- und andere Formate.
---

{{<section overview>}}
---
item1: <a href="https://docs.aspose.com/html/net/working-with-documents/creating-a-document/" target="_blank">Erstellen oder laden Sie HTML-basierte Dokumente</a> von eine Datei, eine URL, eine Zeichenfolge oder ein Stream.
item2: <a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">Konvertieren Sie Dokumente</a> zwischen gängigen Formaten.
item3: <a href="https://docs.aspose.com/html/net/message-handlers/" target="_blank">Erstellen Sie benutzerdefinierte Nachrichtenhandler</a>, um eine bestimmte Aufgabe auszuführen.
item4: <a href="https://docs.aspose.com/html/net/how-to-articles/how-to-use-xpath/" target="_blank">In HTML-Dokumenten navigieren</a> mit XPath-Abfrage oder CSS-Selektor.
item5: <a href="https://docs.aspose.com/html/net/working-with-documents/editing-a-document/" target="_blank">HTML-Dateien bearbeiten</a> durch Einfügen neuer Knoten, Entfernen oder Bearbeiten des Inhalts bestehender Knoten.
item6: <a href="https://docs.aspose.com/html/net/converting-between-formats/fine-tuning-converters/" target="_blank">Rendern Sie Dokumente</a> mit hoher Qualität,
item7: und mehr.
---

Aspose.HTML für .NET ist eine fortschrittliche HTML-Verarbeitungs-API zur Durchführung einer breiten Palette von Verwaltungs- und Manipulationsaufgaben in plattformübergreifenden Anwendungen. Die API wurde zum Erstellen, Ändern, Extrahieren von Daten, Konvertieren und Rendern von HTML-Dokumenten ohne externe Software entwickelt. Außerdem unterstützt es gängige Dateiformate wie EPUB, MHTML, XML, SVG und Markdown sowie das Rendern in PDF-, DOCX-, XPS- und Bilddateiformate. Aspose.HTML für .NET ist vollständig in C# geschrieben und kann verwendet werden, um jede Art von 32-Bit- oder 64-Bit-.NET-Anwendung zu erstellen, einschließlich ASP.NET, WCF, WinForms und .NET Core.<br><br>

Darüber hinaus ist das HTML Document Object Model mit eingebetteten Formaten und Spezifikationen wie CSS, HTML Canvas, SVG, XPath und JavaScript sofort einsatzbereit, die die Manipulationsfunktion und die Wiedergabequalität erweitern. Die vollständige Liste der Funktionen von Aspose.HTML finden Sie in unserer <a href="https://docs.aspose.com/html/net/getting-started/" target="_blank">Dokumentation</a>. Mit der Aspose.HTML-C#-Bibliothek in Ihrem Projekt können Sie die folgenden Aufgaben ausführen:


{{<section glance>}}
---
h3: Auf einen Blick
description: Eine Übersicht über Aspose.HTML für die .NET-API.
---

{{<section platform>}}
---
h3: Plattformunabhängigkeit
description: Aspose.HTML für .NET unterstützt das .NET-Framework und den .NET-Standard.
---

{{<section formats>}}
---
h3: Unterstützte Dateiformate
description: Aspose.HTML für .NET [unterstützte Formate](https://docs.aspose.com/html/net/supported-file-formats/) sind unten aufgeführt.
---

{{<section feature>}}
---
title: Erweiterte .NET-HTML-API-Funktionen
feature1: Erstellen Sie HTML-Seiten von Grund auf neu
feature2: Laden Sie vorhandenes HTML aus einer Datei, einem Stream oder einer URL
feature3: Implementieren Sie W3C-Spezifikationen
feature4: Implementieren Sie Vorlagen mithilfe der Vorlagenzusammenführung
feature5: Füllen Sie die Vorlage mit verschiedenen Datenquellen
feature6: Rendern Sie HTML Canvas 2D in PDF
feature7: Knoten hinzufügen, ersetzen oder entfernen
feature8: Daten aus HTML-Dokumenten extrahieren
feature9: Laden Sie die Dateiformate EPUB und MHTML
feature10: Rendern Sie HTML in Rasterbildformate
feature11: Rendern Sie mehrere Dokumente gleichzeitig
feature12: <a href="/html/{{lang.url-fragment}}net/conversion/md-to-html">Markdown-zu-HTML-Konverter implementieren</a>
feature13: Kopf- und Fußzeile während HTML auf PDF anwenden
feature14: Navigieren Sie durch HTML mit XPath Query oder CSS Selector
feature15: <a href="/html/{{lang.url-fragment}}net/conversion/">Große Auswahl an Konvertierungen zwischen Formaten</a>
---

{{<section converter>}}
---
h2: Konvertieren Sie HTML in PDF, Bild und andere Formate in C#
h3: HTML in PDF konvertieren – C#
---
   
Die C#-API ermöglicht mit nur wenigen Codezeilen die Implementierung von HTML in PDF, HTML in Bild oder jede andere Konvertierung für Ihre .NET-Anwendungen. Der Konvertierungsprozess ist einfach und zuverlässig, was Aspose.HTML für die .NET-API zur perfekten Wahl macht.

{{<section "code" i18n-exclude>}}
     
using Aspose.HTML;
using Aspose.HTML.Saving;
using Aspose.HTML.Converters;
...
    
    // Load an HTML file to be converted
    using var document = new HTMLDocument("input.html")
    
    // Create an instance of the PdfSaveOptions class
    var pdfSaveOptions = new PdfSaveOptions();    
    
    // Convert HTML to PDF
    Converter.ConvertHTML(document, pdfSaveOptions, "output.pdf");
    

{{<section online-converters>}}

Sie können den Online-HTML-Konverter <a href="https://products.aspose.app/html/conversion/html" rel="opener noopener noreferrer" target="_blank"> hier</a> ausprobieren

{{<section other-converters>}}

Sie können auch HTML, XHTML, MHTML, Markdown, EPUB oder SVG in viele andere Dateiformate konvertieren, darunter einige, die unten aufgeführt sind:

{{<section edit-html>}}
---
h2: Bearbeiten von HTML-Dokumenten
---

Mit Aspose.HTML für .NET können Sie HTML-Dokumente mit einem Document Object Model (DOM) erstellen und bearbeiten. Das DOM ist eine Programmierschnittstelle für HTML-Dokumente, die das Dokument (als Knoten und Objekte) als Knotenbaum darstellt, wobei jeder Knoten einen Teil des Dokuments darstellt. Mit Aspose.HTML für die .NET-API können Sie eine Verbindung zur Seite herstellen und die Dokumentstruktur, den Stil und den Inhalt ändern. Sie können das Dokument ändern, indem Sie neue Knoten einfügen und den Inhalt bestehender Knoten entfernen oder bearbeiten.<br><br>
    
 - Navigieren Sie in HTML-Dokumenten mithilfe verschiedener Methoden, wie z. B. Element-Traversal, Dokument-Traversal, XPath-Abfragen und CSS-Selektor-Abfragen,<br>
 - HTML-Knoten entfernen und ersetzen,<br>
 - CSS aus HTML extrahieren und bearbeiten, <br>
 - Konfigurieren Sie eine Dokumenten-Sandbox und mehr.

Die .NET-HTML-API unterstützt Entwickler beim Lesen, Ändern, Navigieren und Bearbeiten von (X)HTML-Dokumenten. Einige Dateibearbeitungsfunktionen, die die Aspose.HTML für .NET-API ausführen kann, sind die folgenden:<br>

{{<section markdown>}}
---
h2: Markdown-Unterstützung
h3: HTML in Markdown umwandeln – C#
h3-md: Konvertieren Sie Markdown in HTML – C#
---

Markdown ist eine Auszeichnungssprache mit einer Nur-Text-Formatierungssyntax. Markdown wird häufig als Format für Dokumentationen und Readme-Dateien verwendet, da es das Schreiben in einem leicht lesbaren und leicht zu schreibenden Stil ermöglicht. Aspose.HTML bietet einen leistungsstarken und flexiblen Markdown-Konverter, der in beide Richtungen von Markdown nach HTML und von HTML nach Markdown konvertieren kann. Darüber hinaus verfügt die Konverter-API über eine Reihe vordefinierter Regeln, sodass Sie HTML in Markdown konvertieren können, indem Sie die authentische Markdown-Syntax, GitLab Flavored Markdown-Modifikation verwenden oder sogar die Regeln für Ihre Bedürfnisse konfigurieren.

{{<section markdown-reverse>}}

So einfach ist die Rückumwandlung! Wenn Sie die Aspose.HTML-Klassenbibliothek in Ihrer C#-Anwendung verwenden, können Sie Markdown ganz einfach mit nur einer Codezeile in eine HTML-Datei konvertieren!

{{<section "code-markdown1" i18n-exclude>}}
     
using Aspose.Html;
using Aspose.HTML.Saving;
...
    
	// Load an HTML file
	using var document = new HTMLDocument("document.html");

	// Convert HTML to Markdown using a set of features supported by GitLab Flavored Markdown
	document.Save("output.md", MarkdownSaveOptions.Git);

{{<section "code-markdown2" i18n-exclude>}}
     
using Aspose.Html.Converters;
...	

	// Convert Markdown to HTML
	Converter.ConvertMarkdown("document.md", "output.html");

{{<section markdown-online>}}

Sie können Markdown Converter online <a href="https://products.aspose.app/html/conversion/md" rel="opener noopener noreferrer" target="_blank"> hier ausprobieren.</a> Sie können Markdown konvertieren in PDF, XPS, DOCX, JPG, PNG, BMP, TIFF, GIF und MHTML. Laden Sie Ihre Dokumente hoch, transformieren Sie sie und erhalten Sie Ergebnisse in wenigen Sekunden. Sie benötigen keine zusätzliche Software.

{{<section epub-mhtml>}}
---
h2: Elektronische Bücher und Webarchive
h3-epub: EPUB in PDF konvertieren – C#
h3-mhtml: Konvertieren Sie MHTML in PDF – C#
---

Aspose.HTML für .NET ist in der Lage, ePub- und MHTML-Dateien zu laden, um verschiedene Operationen durchzuführen, einschließlich der Konvertierung in Formate mit festem Layout und Rasterbild.


{{<section "code-epub" i18n-exclude>}}
     
using Aspose.Html.Converters;
using Aspose.Html.Saving;
...
    
	// Open an existing EPUB file for reading
     using var stream = File.OpenRead("input.epub");     
    
     // Create an instance of PdfSaveOptions
     var options = new PdfSaveOptions();
    
     // Call the ConvertEPUB method to convert EPUB to PDF
     Converter.ConvertEPUB(stream, options, "output.pdf"); 	 

{{<section "code-mhtml" i18n-exclude>}}
     
using Aspose.Html.Converters;
using Aspose.Html.Saving;
...   
	
	 // Open an existing MHTML file for reading
     using var stream = File.OpenRead("input.mht");     
    
     // Create an instance of PdfSaveOptions
     var options = new PdfSaveOptions();
    
     // Call the ConvertMHTML method to convert MHTML to PDF
     Converter.ConvertMHTML(stream, options, output.pdf); 

{{<section epub-mhtml-online>}}

Sie können <a href="https://products.aspose.app/html/conversion/mhtml" rel="opener noopener noreferrer" target="_blank">MHTML Converter</a> online und <a href= online ausprobieren "https://products.aspose.app/html/conversion/epub" rel="opener noopener noreferrer" target="_blank"> EPUB Converter.</a> Unsere browserbasierten Konvertierungstools funktionieren auf allen Plattformen, einschließlich Windows , Linux, MacOS, Android und iOS. Konverter sind mit allen PC-Geräten, Smartphones und Tablets kompatibel.

{{<section web-scraping>}}
---
h2: Web-Scraping
h3: Einfache Webdatenextraktion – C#
---	
	
Web Scraping, auch bekannt als Web Harvesting, Web Data Extraction oder Web Crawling, ist eine Technik zum Extrahieren von Daten aus einer Website. Aspose.HTML unterstützt standardmäßig kein Web-Scraping-Modul. Wenn Sie jedoch die Aspose.HTML-API verwenden, die vollständig auf der W3C-Spezifikation basiert und XPath- und CSS-Selector-Abfragen unterstützt, können Sie den Inhalt jedes beliebigen HTML-Dokuments problemlos überprüfen und Ihre eigene Web-Scraping-Lösung erstellen.

{{<section "code-web-scraping" i18n-exclude>}}
     
using Aspose.Html;
...

    // Create an instance of the HTML document with a website as a parameter
    using var document = new Aspose.Html.HTMLDocument("https://en.wikipedia.org/wiki/Aspose_API");

    // Get all anchor-elements
    var elements = document.QuerySelectorAll("a");

    // Dump the anchor-element data to the console
    elements.Cast&lt;HTMLAnchorElement&gt;().ToList().ForEach(x =&gt;
        {
            System.Console.WriteLine("[Href]: " + x.Href);
            System.Console.WriteLine("[Content]: " + x.TextContent);
        });

{{<section online-web-scraping>}}

Aspose.HTML bietet kostenlose Online-<a href="https://products.aspose.app/html/data-scrapers" rel="opener noopener noreferrer" target="_blank">Daten-Scraper-Apps</a>, die a Möglichkeit, Daten von Websites zu erhalten. Unsere Apps sind sicher, funktionieren auf jeder Plattform und erfordern keine Softwareinstallation. Data Scraper können zum Extrahieren von Bildern, zum Abrufen von Schlüsselwörtern von einer Webseite usw. verwendet werden. Sie sind einfach und klar zu verwenden, aber dennoch kraftvoll und zuverlässig.

{{<section learning>}}
---
tabTitle: Lernmittel
name1: Dokumentation
name2: Quellcode
name3: API-Referenzen
name4: Tutorial-Videos
---

{{<section support>}}
---
tabTitle: Produkt Support
name1: Kostenlose Unterstützung
name2: Bezahlte Unterstützung
name3: Bloggen
name4: Versionshinweise
---

{{<section why>}}
---
tabTitle: Warum Aspose.HTML für .NET?
name1: Kundenliste
name2: Erfolgsgeschichten
description: "Aspose.HTML bietet individuelle HTML-Verarbeitungs-APIs für andere beliebte Entwicklungsumgebungen, wie unten aufgeführt:"
---