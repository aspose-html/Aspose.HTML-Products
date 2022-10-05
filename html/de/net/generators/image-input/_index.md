---
translation: true
title: HTML-Image-Input-Generator – Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: Generieren Sie HTML- und C#-Code für HTML Image Input und verwenden Sie ihn in Ihrer eigenen Website oder Ihrem C#-Projekt.
url: /net/generators/image-input/
platformtag: net
generator: HTML-Image-Input-Generator
element: HTML-Image-Input
tag: image-input
---

{{<section banner>}}
---
h1: HTML-Image-Input-Generator
h2: Generieren Sie HTML- und C#-Code für eine HTML-Image-Input und verwenden Sie ihn in Ihrer eigenen Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie ganz einfach eine HTML-Image-Input!
---

Ein [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element)-Element mit `type='image'` wird verwendet, um eine grafische Senden-Schaltfläche zu erstellen, die die Form von hat ein Bild statt Text. Der HTML-Image-Input-Generator hilft beim Generieren von HTML-Code für eine Schaltfläche zum Senden eines Bilds, indem Attribute wie `name`, `src`, `alt`, `width`, `height` und `autofocus`. ausgewählt werden. Generieren Sie ganz einfach Bildschaltflächen-Tags mit HTML-Syntax!

{{<section plugin>}}

{{< app/html/generator name="image-input" >}}

- Das `src`-Attribut gibt die URL der Bilddatei an, die angezeigt werden soll, um die grafische Senden-Schaltfläche darzustellen.
- Die Attribute `width` und `height` geben Zahlen an, die die Breite und Höhe angeben, um das Bild in CSS-Pixeln zu zeichnen.
- Das Attribut `alt` bietet alternativen Text, der als Beschriftung der Schaltfläche verwendet werden kann, wenn das Bild nicht angezeigt werden kann.
- Das boolesche Attribut `autofocus`, falls vorhanden, gibt an, dass das Element `<input>` automatisch den Fokus erhalten soll, wenn die Seite geladen wird.
<br>

<h2> Erstellen Sie eine HTML-Image-Input in C#</h2>

Aspose.HTML for .NET API unterstützt eine Reihe von HTML-Elementen, die im HTML-Standard definiert sind, zusammen mit Regeln darüber, wie die Elemente verschachtelt werden können. Sie können das Dokument ändern, indem Sie neue Elemente anhängen, den Inhalt vorhandener Knoten entfernen oder bearbeiten. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert eine Bildschaltfläche hinzufügen möchten, sehen Sie sich das folgende C#-Codebeispiel an:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen einer HTML-Image-Input in C#
---

1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) Erstellt das durch tagName angegebene HTML-Element.
1. Legen Sie Werte für [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/), [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) und [Src](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/src/) Attribute.
1. Verwenden Sie die Methode [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/), um `alt`, `width`, `height` und hinzuzufügen `autofocus`-Attribute.
1. Kopieren Sie den C#-Code für die Bildschaltfläche und verwenden Sie ihn in Ihrem C#-Projekt.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Mit diesen HTML-Generatoren wurde die ganze harte Arbeit bereits für Sie erledigt. Alles, was Sie tun müssen, ist Kopieren und Einfügen. Klar, sicher und einfach!"
---