---
translation: true
title: HTML Audio Generator - Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: HTML Audio Generator erstellt HTML- und C#-Code für ein Audioelement. Sie können es auf Ihrer Website oder in Ihrem C#-Projekt verwenden.
url: /net/generators/audio/
platformtag: net
generator: HTML-Audio-Generator
element: HTML-Audio
tag: audio
---

{{<section banner>}}
---
h1: HTML-Audio-Generator
h2: Generieren Sie HTML- und C#-Code für ein HTML Audio element und verwenden Sie es in Ihrer Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie ganz einfach HTML-Audio-Tags!
---

Das HTML-Element [audio](https://html.spec.whatwg.org/multipage/media.html#the-audio-element) wird verwendet, um Musik oder andere Toninhalte in ein HTML-Dokument einzubetten. Das Element `<audio>` kann ein oder mehrere `<source>`-Tags mit unterschiedlichen Audioquellen enthalten. Der Browser wählt die erste Quelle, die er unterstützt. Die Unterstützung für das Element `<audio>` variiert je nach Browser. Fügen Sie mit diesem HTML-Audiogenerator Sounds zu Ihrer Webseite hinzu!

{{<section plugin>}}

{{< app/html/generator name="audio" >}}

<br>
<h2> Attributes </h2>

Im HTML Audio Generator stehen viele Optionen zur Verfügung, mit denen Sie HTML-Audio-Tag-Code generieren und ihn dann kopieren und in Ihre eigene Website einfügen können. Hauptattribute, die vom Audioelement unterstützt werden, sind `controls`, `autoplay`, `loop`, `preload` und `src`.
 - Das Audio-`preload`-Attribut gibt an, dass die Audiodatei geladen werden soll, wenn die Seite geladen wird.
 - Das Attribut `src` gibt die URL des einzubettenden Audios an. Dies ist jedoch optional. Stattdessen können Sie das Element `<source>` im Audioblock verwenden, um das einzubettende Audio anzugeben.
 - Das boolesche Attribut `Autoplay`, falls angegeben, beginnt automatisch mit der Wiedergabe.
 - Das Audio-`controls`-Attribut gibt an, ob Controls in Ihrem Browser angezeigt werden sollen oder nicht. Wenn Sie beispielsweise die Audiosteuerung deaktiviert haben und Ihre Autoplay-Einstellung aktiviert ist, wird Audio wiedergegeben, ist aber im Browser nicht sichtbar.
 - Das boolesche Attribut `loop`, falls angegeben, sucht automatisch zum Anfang zurück, wenn das Ende des Audios erreicht ist.
 - Das boolesche Attribut `muted` gibt, falls angegeben, an, ob der Ton anfänglich stumm geschaltet wird. Sein Standardwert ist false.
<br><br>

<h2> HTML-Audioelement in C# erstellen</h2>

Aspose.HTML für die .NET-API unterstützt eine Reihe von HTML-Elementen, die im HTML-Standard definiert sind, zusammen mit Regeln darüber, wie die Elemente verschachtelt werden können. Sie können das Dokument ändern, indem Sie neue Elemente anhängen, den Inhalt vorhandener Knoten entfernen oder bearbeiten. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert ein `<audio>`-Element hinzufügen möchten, sehen Sie sich das folgende C#-Codebeispiel an:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen von HTML-Audioelementen in C#
---
1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um ein Audioelement zu erstellen. In einem HTML-Dokument erstellt die Methode Document.CreateElement() das durch tagName angegebene HTML-Element, in unserem Fall ist tagName "audio".
2. Verwenden Sie die Methode [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/), um `controls` und andere erforderliche Attribute hinzuzufügen.
3. Erstellen Sie ein oder mehrere `<source>`-Elemente und legen Sie die erforderlichen Attribute für sie fest. Verwenden Sie die CreateElement()-Methode mit "source" tagName.
4. Verwenden Sie die Methode [AppendChild()](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/), um `<source>`-Elemente in das `<audio>`-Element einzufügen.
5. Kopieren Sie den C#-Code für das HTML-Audioelement und verwenden Sie ihn in Ihrem C#-Projekt.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Verwenden Sie HTML-Generatoren, um hochgradig anpassbare HTML-Elemente ohne Programmierung zu erstellen! Klar, sicher und einfach!"
---