---
translation: true
title: HTML-Image-Tag-Generator – Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: HTML Image Generator erstellt HTML- und C#-Code für ein HTML-Bildelement. Verwenden Sie es auf Ihrer Website oder in Ihrem C#-Projekt.
url: /net/generators/image/
platformtag: net
generator: HTML-Image-Tag-Generator
element: HTML-Image
tag: image
---

{{<section banner>}}
---
h1: HTML-Image-Tag-Generator
h2: Generieren Sie HTML- und C#-Code für ein HTML-Image element und verwenden Sie es in Ihrer Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie ganz einfach HTML-<img>-Tags!
---

Das `<img>`-Tag wird verwendet, um ein Bild in eine HTML-Seite einzubetten. Die Verwendung eines HTML-Bildelements wird Ihre Webseite sicherlich interessanter machen. Bilder werden nicht technisch in eine Webseite eingefügt, sondern Bilder werden mit Webseiten verlinkt. Das `<img>`-Tag erstellt einen Haltebereich für das referenzierte Bild.

{{<section plugin>}} 

{{< app/html/generator name="image" >}}

<br>
<h2> Attributes </h2>

 - Das Attribut `src` ist erforderlich und enthält den Pfad eines Bildes zu einem bestimmten Dokument. Mit anderen Worten, es wird verwendet, um Bilder in HTML-Dokumenten zu verlinken.
 - Das Attribut `alt` ist optional, aber unglaublich nützlich für die Zugänglichkeit. Es enthält eine Textbeschreibung des Bildes, die auf der Seite angezeigt wird, wenn das Bild aus irgendeinem Grund nicht geladen werden kann.
 - Es wird empfohlen, immer die `width` und `height` des Bildes anzugeben. Wenn diese Attribute nicht angegeben werden, kann die Seite flackern, während das Bild geladen wird.
<br><br>

<h2> HTML-Image element in C# erstellen</h2>

Aspose.HTML für die .NET-API unterstützt eine Reihe von HTML-Elementen, die im HTML-Standard definiert sind, zusammen mit Regeln darüber, wie die Elemente verschachtelt werden können. Sie können das Dokument ändern, indem Sie neue Elemente anhängen, den Inhalt vorhandener Knoten entfernen oder bearbeiten. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert ein `<img>`-Element hinzufügen möchten, sehen Sie sich das folgende C#-Codebeispiel an:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen eines HTML-Image elements in C#
---
1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um ein Bildelement zu erstellen. In einem HTML-Dokument erstellt die Methode Document.CreateElement() das durch tagName angegebene HTML-Element, in unserem Fall ist tagName "img".
2. Legen Sie den Wert für das erforderliche `src`-Attribut fest.
3. Kopieren Sie den C#-Code für das HTML-Bildelement und verwenden Sie ihn in Ihrem Projekt.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Verwenden Sie HTML-Generatoren, um hochgradig anpassbare HTML-Elemente ohne Programmierung zu erstellen! Klar, sicher und einfach!"
---