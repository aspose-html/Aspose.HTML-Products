---
translation: true
title: HTML Telephone Input Generator – Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: Generieren Sie HTML- und C# Code für HTML Telephone Input und verwenden Sie ihn in Ihrer eigenen Website oder im C#-Projekt.
url: /net/generators/telephone/
platformtag: net
generator: HTML Telephone Input Generator
element: HTML Telephone Input
tag: telephone
---

{{<section banner>}}
---
h1: HTML Telephone Input Generator
h2: Generieren Sie HTML- und C#-Code für ein HTML Telephone Input element und verwenden Sie es in Ihrer eigenen Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie spontan eine HTML Telephone Input!
---

Ein [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element)-Element mit `type='tel'` wird verwendet, damit der Benutzer eine Telefonnummer eingeben und bearbeiten kann . Dieser Eingabewert wird nicht automatisch validiert, da die Telefonnummernformate weltweit sehr unterschiedlich sind. Funktional ist das bei mobilen Browsern praktisch, da Smartphones meist die Art der Eingabe erkennen und die Tastatur auf einen Ziffernblock umstellen. Beachten Sie, dass Browser, die `type='tel'` nicht unterstützen, auf die Standardtexteingabe zurückgreifen.

{{<section plugin>}}

{{< app/html/generator name="telephone" >}}

<br>
<h2> Attributes </h2>

Mit dem Eingabeelement `type='tel'` können Sie Attribute wie *name*, *size*, *placeholder*, *list*, *maxlength*, *minlength* usw. verwenden.

- Das Attribut `size` ist ein numerischer Wert, der angibt, wie viele Zeichen das Eingabefeld enthalten kann.
- Das Attribut `placeholder` ist eine Zeichenfolge, die dem Benutzer einen kurzen Hinweis darauf gibt, welche Informationen in dem Feld erwartet werden.
<br><br>

<h2> HTML Telephone Input in C# erstellen</h2>

Aspose.HTML for .NET API funktioniert als Headless-Browser, mit dem Sie vorhandene HTML-Dokumente aus verschiedenen Quellen erstellen oder öffnen können, um Bearbeitungsvorgänge wie das Entfernen, Anhängen und Ersetzen von HTML-Knoten durchzuführen. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert eine Telefoneingabe hinzufügen möchten, sehen Sie sich das folgende C#-Codebeispiel an:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen von HTML Telephone Input in C#
---
1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/)
1. Legen Sie Werte für [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/), [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) und die Attribute [Size.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/size/)
1. Verwenden Sie die Methode [SetAttribute(),](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/) um `placeholder` oder andere unterstützte Attribute mit ihren Werten hinzuzufügen.
1. Kopieren Sie den C#-Code für die HTML Telephone Input und verwenden Sie ihn in Ihrem C#-Projekt.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Mit diesen HTML-Code-Generatoren wurde die ganze harte Arbeit bereits für Sie erledigt. Alles, was Sie tun müssen, ist Kopieren und Einfügen!"
---