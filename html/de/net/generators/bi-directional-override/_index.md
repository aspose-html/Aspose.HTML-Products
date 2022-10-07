---
translation: true
title: Bidirektionaler Override-HTML-Generator – Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: Der HTML-BDO-Generator erstellt HTML- und C#-Code für ein HTML-BDO-Tag. Sie können es auf Ihrer Website oder in Ihrem C#-Projekt verwenden.
url: /net/generators/bdo/
platformtag: net
generator: HTML-BDO-Generator
element: HTML-bdo-tag
tag: bdo
---

{{<section banner>}}
---
h1: Bidirektionaler Override-HTML-Generator
h2: Generieren Sie HTML- und C#-Code für ein HTML-bdo-Tag und verwenden Sie es in Ihrer Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie einfach ein bdo-HTML-Tag!
---

Das HTML-Element [bdo](https://html.spec.whatwg.org/multipage/text-level-semantics.html#the-bdo-element) überschreibt die aktuelle Textrichtung, sodass der darin enthaltene Text gerendert wird eine andere Richtung. BDO steht für Bi-Directional Override. Das HTML-Tag `<bdo>` gibt die Richtung des darin enthaltenen Inhalts an, der im Browser von links nach rechts oder von rechts nach links angezeigt werden soll. Das `<bdo>`-Tag ist nützlich für von rechts nach links geschriebene Sprachen wie Arabisch, Persisch und Hebräisch.

{{<section plugin>}}

{{< app/html/generator name="bi-directional-override" >}}

<br>
<h2> Attributes </h2>

Der HTML-BDO-Generator hilft beim Generieren eines HTML-BDO-Tags, indem Attribute wie `dir`, `spellcheck` usw. ausgewählt werden. Das Attribut `dir` ist erforderlich. Es definiert die Richtung, in der Text im Inhalt dieses Elements gerendert werden soll. Mögliche Werte sind: *rtl* und *ltr*.
<br><br>

<h2> HTML-BDO-Tag in C# erstellen</h2>

Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert ein HTML-Tag `<bdo>` hinzufügen möchten, sehen Sie sich das C#-Beispiel unten an. Mit wenigen Codezeilen können Sie das gewünschte Element erstellen:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen von HTML-BDO-Tags in C#
---

1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um ein `<bdo>`-Element zu erstellen. In einem HTML-Dokument erstellt die Methode Document.CreateElement() das durch tagName angegebene HTML-Element, in unserem Fall ist tagName "bdo".
2. Verwenden Sie die Methode [SetAttribute(),](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/) um `dir` und andere erforderliche Attribute hinzuzufügen.
3. Erstellen Sie Textinhalte mit der Methode [CreateTextNode().](https://reference.aspose.com/html/net/aspose.html.dom/document/createtextnode/)
4. Verwenden Sie die Methode [AppendChild(),](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) um Textinhalt zum Element `<bdo>` hinzuzufügen.
5. Kopieren Sie den C#-Code für das HTML-Tag bdo und verwenden Sie ihn in Ihrem C#-Projekt.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Verwenden Sie HTML-Generatoren, um hochgradig anpassbare HTML-Elemente ohne Programmierung zu erstellen! Klar, sicher und einfach!"
---