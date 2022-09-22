---
translation: true
title: HTML Submit Input Generator – Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: Generieren Sie HTML- und C#-Code für HTML Submit Input und verwenden Sie ihn in Ihrer eigenen Website oder Ihrem C#-Projekt.
url: /net/generators/submit/
platformtag: net
generator: HTML Submit Input Generator
element: HTML Submit Input
tag: submit
---

{{<section banner>}}
---
h1: HTML Submit Input Generator
h2: Generieren Sie HTML- und C#-Code für ein HTML-Submit-Input element und verwenden Sie es in Ihrer eigenen Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie ganz einfach HTML Submit Input!
---

Ein [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element)-Element mit `type='submit'` wird als Senden-Schaltfläche gerendert, die das Formular an die übermittelt Server. Wenn der Benutzer auf die Schaltfläche geklickt hat, versucht der Benutzeragent, das Formular an den Server zu senden. HTML Submit Input Generator hilft Ihnen, Code zu generieren, der in HTML eingefügt werden kann. Wählen Sie einfach Optionen aus und generieren Sie die HTML Submit Input im Handumdrehen!

{{<section plugin>}}

{{< app/html/generator name="submit" >}}

<br>
<h2> Attributes </h2>

Ein `value`-Attribut enthält eine Zeichenkette, die als Beschriftung der Schaltfläche angezeigt wird. Andernfalls, wenn Sie keinen Wert angeben, hat die Schaltfläche eine Standardbezeichnung, die vom Benutzeragenten ausgewählt wird. Wenn Sie den Submit-Button deaktivieren möchten, setzen Sie das Attribut `disabled` darauf.<br><br>

<h2> HTML Submit Input in C# erstellen</h2>

Aspose.HTML for .NET API funktioniert als Headless-Browser, mit dem Sie vorhandene HTML-Dokumente aus verschiedenen Quellen erstellen oder öffnen können, um Bearbeitungsvorgänge wie das Entfernen, Anhängen und Ersetzen von HTML-Knoten durchzuführen. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert eine Senden-Schaltfläche hinzufügen möchten, sehen Sie sich das C#-Codebeispiel unten an. Sie können ein Submit-Input-Tag mit ein paar Zeilen erstellen:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen von HTML Submit Input in C#
---
1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) Erstellt das durch tagName angegebene HTML-Element.
1. Legen Sie Werte für [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/) und [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) Attribute.
1. Verwenden Sie die Methode [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/), um `value`, `disabled` oder andere unterstützte Attribute hinzuzufügen ihre Werte.
1. Kopieren Sie den C#-Code für die Senden-Schaltfläche und verwenden Sie ihn in Ihrem Projekt.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Mit diesen HTML-Code-Generatoren wurde die ganze harte Arbeit bereits für Sie erledigt. Alles, was Sie tun müssen, ist Kopieren und Einfügen. Klar, sicher und einfach!"
---