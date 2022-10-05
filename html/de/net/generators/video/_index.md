---
translation: true
title: HTML Video Generator – Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: HTML Video Generator erstellt HTML- und C#-Code für ein Videoelement. Sie können es in Ihrer Website oder Ihrem C#-Projekt verwenden.
url: /net/generators/video/
platformtag: net
generator: HTML-Video-Generator
element: HTML-Video
tag: video
---

{{<section banner>}}
---
h1: HTML-Video-Generator
h2: Generieren Sie HTML- und C#-Code für ein HTML-Video element und verwenden Sie es in Ihrer eigenen Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie ganz einfach HTML-Video-Tags!
---

Das HTML-Element [video](https://html.spec.whatwg.org/multipage/media.html#the-video-element) wird verwendet, um einen Mediaplayer einzubetten, der die Videowiedergabe in einem Dokument unterstützt. Das `<video>`-Tag kann ein oder mehrere `<source>`-Tags mit unterschiedlichen Videoquellen enthalten. Der Browser wählt die erste Quelle, die er unterstützt. Sie können verschiedene Attribute aktivieren oder deaktivieren, um Informationen anzugeben, wie z. B. die Breite und Höhe des Videos, ob es automatisch abgespielt und wiederholt werden soll, ob Sie Videosteuerelemente standardmäßig im Browser anzeigen möchten und vieles mehr.

{{<section plugin>}}

{{< app/html/generator name="video" >}}

<br>
<h2> Attributes </h2>

Im HTML Video Generator stehen viele Optionen zur Verfügung, mit denen Sie HTML-Video-Tag-Code generieren und ihn dann kopieren und in Ihre eigene Website einfügen können. Sie können verschiedene Optionen wie Videosteuerung, Autoplay, Schleife, Vorabladen usw. aktivieren oder deaktivieren.

 - Das Attribut `preload` des Videos gibt an, dass die Videodatei geladen werden soll, wenn die Seite geladen wird.
 - Das Attribut `src` gibt die URL des einzubettenden Videos an. Dies ist jedoch optional. Stattdessen können Sie das Element `<source>` im Videoblock verwenden, um das einzubettende Video anzugeben.
 - Die Attribute `height` und `width` definieren die Höhe und Breite des Videoanzeigebereichs in CSS-Pixeln.
 - Das boolesche Attribut `autoplay`, falls angegeben, beginnt automatisch mit der Wiedergabe.
 - Das Attribut `controls` des Videos gibt an, ob Steuerelemente in Ihrem Browser angezeigt werden sollen oder nicht. Wenn Sie beispielsweise die Videosteuerung deaktiviert haben und Ihre Autoplay-Einstellung aktiviert ist, wird das Video abgespielt, ist aber nicht im Browser sichtbar.
 - Das boolesche Attribut `loop`, falls angegeben, sucht automatisch zurück zum Anfang, wenn das Ende des Videos erreicht ist.
 - Das boolesche Attribut `muted` gibt, falls angegeben, an, ob das Video anfänglich stumm geschaltet wird. Sein Standardwert ist false.
<br><br>

<h2> HTML-Video element in C# erstellen</h2>

Aspose.HTML für die .NET-API unterstützt eine Reihe von HTML-Elementen, die im HTML-Standard definiert sind, zusammen mit Regeln darüber, wie die Elemente verschachtelt werden können. Sie können das Dokument ändern, indem Sie neue Elemente anhängen, den Inhalt vorhandener Knoten entfernen oder bearbeiten. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert ein `<video>`-Element hinzufügen möchten, sehen Sie sich das folgende C#-Codebeispiel an:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen eines HTML-Video elements in C#
---
1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um ein Videoelement zu erstellen. In einem HTML-Dokument erstellt die Methode Document.CreateElement() das durch tagName angegebene HTML-Element, in unserem Fall ist tagName "video".
2. Verwenden Sie die Methode [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/), um `controls` und andere erforderliche Attribute hinzuzufügen.
3. Erstellen Sie ein `<source>`-Element und legen Sie die erforderlichen Attribute dafür fest. Verwenden Sie die CreateElement()-Methode mit "source" tagName.
4. Verwenden Sie die Methode [AppendChild()](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/), um das Element `<source>` zum video element hinzuzufügen.
5. Kopieren Sie den C#-Code für das HTML-Videoelement und verwenden Sie ihn in Ihrem Projekt.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Verwenden Sie HTML-Generatoren, um hochgradig anpassbare HTML-Elemente ohne Programmierung zu erstellen! Klar, sicher und einfach!"
---