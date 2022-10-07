---
translation: true
title: HTML-<code>-Tag-Generator - Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: Code HTML Generator erstellt ein HTML-code-Tag. Kopieren und verwenden Sie generierten HTML- und C#-Code in Ihrem eigenen Projekt!
url: /net/generators/code/
platformtag: net
family: html
generator: HTML-code-Tag-Generator
element: HTML-code-tag
tag: code
---

{{<section banner>}}
---
h1: HTML-Code-Tag-Generator
h2: Generieren Sie HTML- und C#-Code für ein HTML-`<code>`-Element und verwenden Sie es in Ihrer Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie ganz einfach HTML-<code>-Tags!
---

Das HTML-Element `<code>` wird verwendet, um ein Stück Computercode zu definieren. Standardmäßig wird der Inhaltstext mit der Standard-Monospace-Schriftart des Browsers angezeigt. Dieses Element kann nur globale Attribute enthalten.

{{<section plugin>}}

{{< app/html/generator name="code" >}}

<br><br>
<h2> HTML-code-Tag in C# erstellen</h2>

[Aspose.HTML for .NET](/html/{{lang.url-fragment}}net/) API unterstützt eine Reihe von HTML-Elementen, die in HTML Standard definiert sind, zusammen mit Regeln, wie die Elemente verschachtelt werden können. Sie können das Dokument ändern, indem Sie neue Elemente anhängen, den Inhalt vorhandener Knoten entfernen oder bearbeiten. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert ein HTML-Code-Tag hinzufügen möchten, sehen Sie sich das C#-Beispiel unten an. Mit wenigen Codezeilen können Sie das gewünschte Element erstellen:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen von HTML-code-Tags in C#
---

1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um ein `<code>`-Element zu erstellen. In einem HTML-Dokument erstellt die Methode Document.CreateElement() das durch tagName angegebene HTML-Element, in unserem Fall ist tagName "code".
2. Erstellen Sie Textinhalte mit der Methode [CreateTextNode().](https://reference.aspose.com/html/net/aspose.html.dom/document/createtextnode/)
3. Verwenden Sie die Methode [AppendChild(),](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) um Textinhalt in das Element `<code>` einzufügen.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Verwenden Sie HTML-Generatoren, um hochgradig anpassbare HTML-Elemente ohne Programmierung zu erstellen! Klar, sicher und einfach!"
---