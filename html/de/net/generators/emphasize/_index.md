---
translation: true
title: Betonen Sie den Text-HTML-Generator – Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: Emphasize-Text-HTML-Generator erstellt ein HTML-em-Tag. Sehen Sie sich den generierten HTML- und C#-Code an, kopieren Sie ihn und verwenden Sie ihn in Ihrer Website oder Ihrem C#-Projekt!
url: /net/generators/emphasize/
platformtag: net
family: html
generator: Emphasize-Text-HTML-Generator
element: HTML-em-tag
tag: emphasize
---

{{<section banner>}}
---
h1: Emphasize-Text-HTML-Generator
h2: Generieren Sie HTML- und C#-Code für ein HTML-Emphasize-Text-Tag und verwenden Sie es in Ihrer Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie Emphasize-Text-HTML-Tags im Handumdrehen!
---

Das `<em>`-Tag wird verwendet, um hervorgehobenen Text zu definieren. Mit anderen Worten, es handelt sich um einen Satz mit betonter Betonung im Vergleich zum umgebenden Text. Dieser Satz ist oft auf ein Wort oder wenige Wörter beschränkt und wirkt sich auf die Bedeutung des Satzes aus. Der Inhalt innerhalb des `<em>`-Tags wird normalerweise kursiv dargestellt. Ein Bildschirmleser verwendet verbale Betonung, um die Wörter in `<em>` mit einer Betonung auszusprechen.

{{<section plugin>}}

{{< app/html/generator name="emphasize" >}}

<br><br>
<h2> HTML-em-Tag in C# erstellen</h2>

[Aspose.HTML for .NET](/html/{{lang.url-fragment}}net/) API unterstützt eine Reihe von HTML-Elementen, die in HTML Standard definiert sind, zusammen mit Regeln, wie die Elemente verschachtelt werden können. Sie können das Dokument ändern, indem Sie neue Elemente anhängen, den Inhalt vorhandener Knoten entfernen oder bearbeiten. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert ein Emphasize-Text-HTML-Tag hinzufügen möchten, sehen Sie sich das C#-Beispiel unten an. Mit wenigen Codezeilen können Sie das gewünschte Element erstellen:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen des Emphasize-Text-HTML-Tags in C#
---
1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um ein `<em>`-Element zu erstellen. In einem HTML-Dokument erstellt die Methode Document.CreateElement() das durch tagName angegebene HTML-Element, in unserem Fall ist tagName "em".
2. Erstellen Sie Textinhalte mit der Methode [CreateTextNode().](https://reference.aspose.com/html/net/aspose.html.dom/document/createtextnode/)
3. Verwenden Sie die Methode [AppendChild(),](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) um Textinhalt in das Element `<em>` einzufügen.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Verwenden Sie HTML-Generatoren, um hochgradig anpassbare HTML-Elemente ohne Programmierung zu erstellen! Klar, sicher und einfach!"
---