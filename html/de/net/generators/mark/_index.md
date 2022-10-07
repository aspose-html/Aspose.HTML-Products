---
translation: true
title: HTML-mark-Tag-(Highlight)-Generator – Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: Generieren Sie ein HTML-mark-Tag (Highlight) und kopieren Sie den generierten HTML- und C#-Code auf Ihre Website oder in Ihr C#-Projekt!
url: /net/generators/mark/
platformtag: net
family: html
generator: HTML-mark-Tag-Generator
element: HTML-mark-tag
tag: mark
---

{{<section banner>}}
---
h1: Generator für HTML-mark-Tags (Highlight).
h2: Generieren Sie HTML- und C#-Code für ein HTML-Highlight und verwenden Sie es in Ihrer Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie HTML <mark> Tag on the fly!
---

Das HTML-Element `<mark>` definiert den Text, der markiert oder hervorgehoben werden soll. Das `<mark>`-Tag gibt einen Teil des Inhalts des Dokuments an, den Sie für interessant halten, beispielsweise um die Wörter anzugeben, die mit einem Suchvorgang übereinstimmen.

{{<section plugin>}}

{{< app/html/generator name="mark" >}}

<br>
<h2> HTML-mark-Tag in C# erstellen</h2>

[Aspose.HTML for .NET](/html/{{lang.url-fragment}}net/) API unterstützt eine Reihe von HTML-Elementen, die in HTML Standard definiert sind, zusammen mit Regeln, wie die Elemente verschachtelt werden können. Sie können das Dokument ändern, indem Sie neue Elemente anhängen, den Inhalt vorhandener Knoten entfernen oder bearbeiten. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert ein HTML-Markierungs-Tag hinzufügen möchten, sehen Sie sich das folgende C#-Beispiel an:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen von HTML-Highlight in C#
---

1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um ein `<mark>`-Element zu erstellen. In einem HTML-Dokument erstellt die Methode Document.CreateElement() das durch tagName angegebene HTML-Element, in unserem Fall ist tagName "mark".
2. Erstellen Sie Textinhalte mit der Methode [CreateTextNode().](https://reference.aspose.com/html/net/aspose.html.dom/document/createtextnode/)
3. Verwenden Sie die Methode [AppendChild(),](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) um Textinhalt zum Element `<mark>` hinzuzufügen.
4. Kopieren Sie den C#-Code für das Tag `<mark>` und verwenden Sie ihn in Ihrem C#-Projekt.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Verwenden Sie HTML-Generatoren, um hochgradig anpassbare HTML-Elemente ohne Programmierung zu erstellen! Klar, sicher und einfach!"
---