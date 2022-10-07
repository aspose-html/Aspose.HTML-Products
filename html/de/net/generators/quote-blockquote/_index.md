---
translation: true
title: Quote-und-Blockquote-HTML-Generator – Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: Generieren Sie ein Quote & Blockquote-HTML-Tag und kopieren Sie den generierten HTML- und C#-Code auf Ihre Website oder in Ihr C#-Projekt
url: /net/generators/quote-blockquote/
platformtag: net
family: html
generator: Quote-und-Blockquote-HTML-Generator
element: Quote or Blockquote HTML tag
tag: quote-blockquote
---

{{<section banner>}}
---
h1: Quote-und-Blockquote-HTML-Generator
h2: Generieren Sie HTML- und C#-Code für ein HTML-Quote- und Blockquote-Tag und verwenden Sie es in Ihrer Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generator-Quote- und Blockquote-HTML-Tags im Handumdrehen!
---

Das HTML-Tag `<q>` ist ein Standard-Quote-Tag, das für kurze Zitate verwendet wird, die keine Absatzumbrüche erfordern. Die meisten modernen Browser implementieren dies, indem sie den Text in Anführungszeichen setzen. Das HTML-Element `<blockquote>` zeigt an, dass es sich bei dem eingeschlossenen Text um ein erweitertes Zitat handelt. Üblicherweise wird dies visuell durch Einrückung wiedergegeben. Eine URL für die Quelle des Zitats kann mit dem Attribut `cite` angegeben werden.


{{<section plugin>}}

{{< app/html/generator name="quote-blockquote" >}}

<br>
<h2> Attributes </h2>

Das Attribut `cite` gibt die Quell-URL des Zitats an. Dieses Attribut soll auf Informationen hinweisen, die den Kontext oder die Referenz für das Zitat erläutern.
<br><br>

<h2> Erstellen Sie HTML-Quote- und BlockQuote-HTML-Tags in C#</h2>

[Aspose.HTML for .NET](/html/{{lang.url-fragment}}net/) API unterstützt eine Reihe von HTML-Elementen, die in HTML Standard definiert sind, zusammen mit Regeln, wie die Elemente verschachtelt werden können. Sie können das Dokument ändern, indem Sie neue Elemente anhängen, den Inhalt vorhandener Knoten entfernen oder bearbeiten. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert Quote- und Blockquote-HTML-Tags hinzufügen möchten, sehen Sie sich das folgende C#-Beispiel an:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen eines Quote-HTML-Tags in C#
---

1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Klasse Document, um ein HTML-Element `<q>` zu erstellen. In einem HTML-Dokument erstellt die Methode Document.CreateElement() das durch tagName angegebene [HTMLQuoteElement,](https://reference.aspose.com/html/net/aspose.html/htmlquoteelement/) in unserem Fall lautet tagName "q".
2. Legen Sie den Wert für das Attribut [Cite](https://reference.aspose.com/html/net/aspose.html/htmlquoteelement/cite/) fest.
2. Erstellen Sie Textinhalte mit der Methode [CreateTextNode().](https://reference.aspose.com/html/net/aspose.html.dom/document/createtextnode/)
3. Verwenden Sie die Methode [AppendChild(),](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) um Textinhalt in das Element `<q>` einzufügen.
4. Kopieren Sie den C#-Code für das HTML-Tag `<q>` und verwenden Sie ihn in Ihrem C#-Projekt.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Verwenden Sie HTML-Generatoren, um hochgradig anpassbare HTML-Elemente ohne Programmierung zu erstellen! Klar, sicher und einfach!"
---