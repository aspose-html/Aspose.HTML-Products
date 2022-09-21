---
translation: true
title: HTML Range Input Generator – Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: Erstellen Sie eine HTML-Range-Eingabe für Ihre Website. Überprüfen Sie die Bereichseingabe, kopieren und verwenden Sie generierten HTML- und C#-Code in Ihrem Projekt!
url: /net/generators/range/
platformtag: net
generator: HTML-Range-Input-Generator
element: HTML-Bereichseingabe
tag: Angebot
---

{{<section banner>}}
---
h1: HTML-Range-Input-Generator
h2: Generieren Sie HTML- und C#-Code für eine HTML-Range-Eingabe und verwenden Sie ihn in Ihrer eigenen Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie ganz einfach HTML-Bereichseingaben!
---

Ein [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element)-Element mit `type="range"` oder Range-Schieberegler ermöglicht es Ihnen, einen numerischen Wert anzugeben, der erforderlich ist nicht weniger als oder nicht mehr als der angegebene Wert sein. Der Standardbereich liegt zwischen 0 und 100. Der genaue Wert wird jedoch nicht als wichtig erachtet. Normalerweise finden Sie den Bereichsschieberegler, wenn Sie die Lautstärke- oder Helligkeitsregler auf Ihrem Computer manipulieren.

{{<section plugin>}}

{{< app/html/generator name="range" >}}

<br>
<h2> Attributes </h2>

- Um den Bereich anzuzeigen, verwenden Sie die Attribute „min“ und „max“ mit dem Eingabetyp „Bereich“.
- Das Attribut „Schritt“ ist die zulässige Anzahl von Intervallen im Bereich. Der Standardwert ist 1.
- Das Attribut "Wert" enthält einen Startpunkt des Bereichs. Dies ist der Wert, auf den der Schieberegler standardmäßig eingestellt ist, sobald die Seite geladen ist. Der Standardwert liegt in den meisten Fällen in der Mitte zwischen der minimalen und der maximalen Anzahl, aber Sie haben immer die Möglichkeit, den Wert beliebig zu ändern.

Die Bereichseingabe enthält normalerweise die Attribute „name“, „value“, „min“, „max“ und „step“.
<br><br>

<h2> HTML-Bereichseingabe in C# erstellen</h2>

Aspose.HTML für die .NET-API funktioniert als Headless-Browser, mit dem Sie vorhandene HTML-Dokumente aus verschiedenen Quellen erstellen oder öffnen können, um Bearbeitungsvorgänge wie das Entfernen, Anhängen und Ersetzen von HTML-Knoten durchzuführen. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert eine Bereichseingabe hinzufügen möchten, sehen Sie sich das folgende C#-Codebeispiel an:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen einer HTML-Bereichseingabe in C#
---
1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) Erstellt das durch tagName angegebene HTML-Element.
1. Legen Sie Werte für [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/) und [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) Attribute.
1. Verwenden Sie die Methode [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/), um `value`, `min`, `max` und hinzuzufügen `step`-Attribute mit ihren Werten.
1. Kopieren Sie den Code für die HTML-Bereichseingabe und verwenden Sie ihn in Ihrem C#-Projekt.



{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Mit diesen HTML-Generatoren wurde die ganze harte Arbeit bereits für Sie erledigt. Alles, was Sie tun müssen, ist Kopieren und Einfügen. Klar, sicher und einfach!"
---