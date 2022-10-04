---
translation: true
title: HTML iFrame Generator - Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: Erstellen Sie HTML- und C#-Code für ein Iframe-Element. Sie können es auf Ihrer Website oder in Ihrem C#-Projekt verwenden.
url: /net/generators/iframe/
platformtag: net
generator: HTML-iFrame-Generator
element: HTML-Iframe
tag: iframe
---

{{<section banner>}}
---
h1: HTML-iFrame-Generator
h2: Generieren Sie HTML- und C#-Code für ein HTML-iFrame-Element und verwenden Sie es in Ihrer eigenen Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie HTML iFrame on the fly!
---

Das HTML-Element [iframe](https://html.spec.whatwg.org/multipage/iframe-embed-object.html#the-iframe-element) stellt einen [verschachtelten Browserkontext;](https://html.spec.whatwg.org/multipage/browsers.html#nested-browsing-context) wird verwendet, um ein anderes Dokument in das aktuelle HTML-Dokument einzubetten. Mit dem HTML-iFrame-Generator können Sie ein `<iframe>`-Tag erstellen und an Ihre Anforderungen anpassen. Sie können Breite und Höhe sowohl in Prozent als auch in Pixeln angeben, den Namen vergeben, Scrolling und Ränder festlegen.

{{<section plugin>}}

{{< app/html/generator name="iframe" >}}

<br>
<h2> Attributes </h2>

 - Das Attribut `src` ist erforderlich und definiert die URL der verschachtelten Webseite.
 - Das Attribut `name` gibt den Zielnamen eines Iframes an.
 - Die Attribute `width` und `height` geben die Breite und Höhe eines Iframes an. Die Standardbreite beträgt 300 Pixel und die Standardhöhe 150 Pixel.
 - Das Attribut `scrolling` gibt an, wann der Browser eine Scrollbar für den Frame bereitstellen soll.
 <br><br>

<h2> HTML-iFrame in C# erstellen</h2>

Aspose.HTML für die .NET-API unterstützt eine Reihe von HTML-Elementen, die im HTML-Standard definiert sind, zusammen mit Regeln darüber, wie die Elemente verschachtelt werden können. Sie können das Dokument ändern, indem Sie neue Elemente anhängen, den Inhalt vorhandener Knoten entfernen oder bearbeiten. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert ein `<iframe>`-Element hinzufügen möchten, sehen Sie sich das folgende C#-Codebeispiel an:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen von HTML-iFrame in C#
---

1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um ein [HTMLIFrameElement.](https://reference.aspose.com/html/net/aspose.html/htmliframeelement/)
2. Legen Sie Werte für [Src](https://reference.aspose.com/html/net/aspose.html/htmliframeelement/src/), [Name](https://reference.aspose.com/html/net/aspose.html/htmliframeelement/name/), [Height](https://reference.aspose.com/html/net/aspose.html/htmliframeelement/height/) und [Width](https://reference.aspose.com/html/net/aspose.html/htmliframeelement/width/)-Attribute.
3. Kopieren Sie den C#-Code für den HTML-iFrame und verwenden Sie ihn in Ihrem Projekt.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Verwenden Sie HTML-Generatoren, um hochgradig anpassbare HTML-Elemente ohne Programmierung zu erstellen! Klar, sicher und einfach!"
---