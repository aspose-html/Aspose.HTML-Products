---
translation: true
title: Strikethrough-HTML-Generator – Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: Generieren Sie das HTML-Strikethrough-Tag. Kopieren und verwenden Sie generierten HTML- und C#-Code in Ihrem eigenen Projekt!
url: /net/generators/strikethrough/
platformtag: net
family: html
generator: Strikethrough-HTML-Generator
element: Strikethrough-HTML-tag
tag: strikethrough
---

{{<section banner>}}
---
h1: Strikethrough-HTML-Generator
h2: Generieren Sie HTML- und C#-Code für ein HTML-`<s>`-Tag und verwenden Sie es in Ihrer Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie ganz einfach HTML <s>-Tags!
---

Das HTML-Tag `<s>` gibt Text an, der nicht mehr korrekt, genau oder relevant ist. Der Text wird durchgestrichen angezeigt. Das `<s>`-Tag wird verwendet, wenn Sie versuchen, Dinge darzustellen, die nicht mehr relevant oder nicht mehr genau sind. `<s>` ist jedoch nicht geeignet, um Dokumentbearbeitungen anzuzeigen; Verwenden Sie dazu die Elemente `<del>` und `<ins>` nach Bedarf.

{{<section plugin>}}

{{< app/html/generator name="strikethrough" >}}

<br>
<h2> Strikethrough-HTML-Element in C# erstellen</h2>

[Aspose.HTML for .NET](/html/{{lang.url-fragment}}net/) API unterstützt eine Reihe von HTML-Elementen, die in HTML Standard definiert sind, zusammen mit Regeln, wie die Elemente verschachtelt werden können. Sie können das Dokument ändern, indem Sie neue Elemente anhängen, den Inhalt vorhandener Knoten entfernen oder bearbeiten. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert ein HTML-Tag `<s>` hinzufügen möchten, sehen Sie sich das folgende C#-Beispiel an:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen eines durchgestrichenen HTML-Tags in C#
---

1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um ein `<s>`-Element zu erstellen. In einem HTML-Dokument erstellt die Methode Document.CreateElement() das durch tagName angegebene HTML-Element, in unserem Fall ist tagName "s".
2. Erstellen Sie Textinhalte mit der Methode [CreateTextNode().](https://reference.aspose.com/html/net/aspose.html.dom/document/createtextnode/)
3. Verwenden Sie die Methode [AppendChild(),](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) um dem HTML-Element `<s>` Textinhalt hinzuzufügen.
4. Kopieren Sie den C#-Code für das HTML-Tag `<s>` und verwenden Sie ihn in Ihrem C#-Projekt.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Verwenden Sie HTML-Generatoren, um hochgradig anpassbare HTML-Elemente ohne Programmierung zu erstellen! Klar, sicher und einfach!"
---