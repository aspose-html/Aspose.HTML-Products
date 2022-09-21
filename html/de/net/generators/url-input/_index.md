---
translation: true
title: HTML-URL-Eingabegenerator – Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: Erstellen Sie eine HTML-URL-Eingabe für Ihre Website. Überprüfen Sie die URL-Eingabe, kopieren und verwenden Sie generierten HTML- und C#-Code in Ihrem Projekt!
url: /net/generators/url-input/
platformtag: net
generator: HTML-URL-Eingabegenerator
element: HTML-URL-Eingabe
tag: URL-Eingabe
---

{{<section banner>}}
---
h1: HTML-URL-Eingabegenerator
h2: Generieren Sie HTML- und C#-Code für eine HTML-URL-Eingabe und verwenden Sie ihn in Ihrer eigenen Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie ganz einfach eine HTML-URL-Eingabe!
---

Eine [Eingabe](https://html.spec.whatwg.org/multipage/input.html#the-input-element) mit `type='url'` definiert ein Feld zur Eingabe einer URL. Es akzeptiert nur null oder eine gültige URL. Dieser Eingabewert wird automatisch validiert, bevor das Formular gesendet wird. Der HTML-URL-Eingabegenerator hilft Ihnen, Code zu generieren, der in HTML eingefügt werden kann. Wählen Sie einfach Optionen aus und generieren Sie die URL-Eingabe im Handumdrehen!

{{<section plugin>}}

{{< app/html/generator name="url-input" >}}

<br>
<h2> Attributes </h2>

- Das Attribut „Größe“ ist ein numerischer Wert, der angibt, wie viele Zeichen das Eingabefeld enthalten kann.
- Das Attribut „Platzhalter“ ist eine Zeichenfolge, die dem Benutzer einen kurzen Hinweis darauf gibt, welche Informationen in dem Feld erwartet werden.
- Das Attribut „pattern“, sofern angegeben, ist ein regulärer Ausdruck, dem der Eingabewert entsprechen muss, damit der Wert die Validierung besteht.

Mit dem Eingabeelement `type='url'` können Sie Attribute wie *name*, *id*, *size*, *pattern*, *placeholder*, *list*, *maxlength*, *minlength* usw. verwenden .
<br><br>

<h2> URL-Eingabe in C# erstellen</h2>

Aspose.HTML für die .NET-API funktioniert als Headless-Browser, mit dem Sie vorhandene HTML-Dokumente aus verschiedenen Quellen erstellen oder öffnen können, um Bearbeitungsvorgänge wie das Entfernen, Anhängen und Ersetzen von HTML-Knoten durchzuführen. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem C#-Produkt verwenden oder programmgesteuert eine HTML-URL-Eingabe hinzufügen möchten, sehen Sie sich das folgende C#-Codebeispiel an:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen einer URL-Eingabe in C#
---
1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/)
1. Legen Sie Werte für [Typ](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/), [Name](https://reference.aspose.com/html/ net/aspose.html/htmlinputelement/name/) und [Size](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/size/) Attribute.
1. Verwenden Sie die Methode [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/), um „placeholder“, „pattern“ oder andere unterstützte Attribute hinzuzufügen ihre Werte.
1. Kopieren Sie den Code für die HTML-URL-Eingabe und verwenden Sie ihn in Ihrem C#-Projekt.



{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Mit HTML-Code-Generatoren wurde die ganze harte Arbeit bereits für Sie erledigt. Alles, was Sie tun müssen, ist Kopieren und Einfügen!"
---