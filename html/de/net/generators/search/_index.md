---
translation: true
title: HTML Search Input Generator – Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: Generieren Sie eine HTML Search Input, sehen Sie sich das Ergebnis in der Vorschau an und kopieren Sie den HTML- und C#-Code auf Ihre Website.
url: /net/generators/search/
platformtag: net
generator: HTML Search Input Generator
element: HTML Search Input
tag: search
---

{{<section banner>}}
---
h1: HTML Search Input Generator
h2: Generieren Sie HTML- und C#-Code für ein HTML Search Input element und verwenden Sie es in Ihrer eigenen Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie ganz einfach HTML Search Input!
---

Ein [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element)-Element mit `type='search'` definiert ein Textfeld, das dem Benutzer zur Eingabe von Suchanfragen dient hinein. Suchfelder sind auf jeder Website allgegenwärtig. Dies ist nützlich, um bestimmte Daten zu finden. Der HTML Search Input Generator hilft Ihnen, Code zu generieren, der in HTML eingefügt werden kann. Wählen Sie einfach Optionen aus und generieren Sie das Suchfeld im Handumdrehen!

{{<section plugin>}}

{{< app/html/generator name="search" >}}

<br>
<h2> Attributes </h2>

- Das Attribut `name` ist erforderlich. Wenn für das Suchfeld kein Name angegeben ist, wird nichts übermittelt.
- Das Attribut `size` ist ein numerischer Wert, der angibt, wie viele Zeichen das Eingabefeld enthalten kann.
- Die `spellcheck` ist ein Attribut, das verwendet wird, um anzugeben, ob die Rechtschreibprüfung für ein Element aktiviert werden soll.
- Das Attribut `placeholder` ist eine Zeichenfolge, die dem Benutzer einen kurzen Hinweis darauf gibt, welche Informationen in dem Feld erwartet werden.<br><br>

<h2> HTML Search Input in C# erstellen</h2>

Aspose.HTML for .NET API unterstützt eine Reihe von HTML-Elementen, die im HTML-Standard definiert sind, zusammen mit Regeln darüber, wie die Elemente verschachtelt werden können. Sie können das Dokument ändern, indem Sie neue Elemente anhängen, den Inhalt vorhandener Knoten entfernen oder bearbeiten. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert ein Sucheingabe-Tag hinzufügen möchten, sehen Sie sich das Beispiel unten an. Sie können ein Sucheingabeelement mit ein paar Zeilen C#-Code erstellen:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen von HTML Search Input in C#
---
1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) Erstellt das durch tagName angegebene HTML-Element.
1. Legen Sie Werte für [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/) und [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) Attribute.
1. Verwenden Sie die Methode [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/), um die Attribute `size`, `spellcheck` und `placeholder` hinzuzufügen ihre Werte.
1. Kopieren Sie den Code für die HTML Search Input und verwenden Sie ihn in Ihrem C#-Projekt.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Mit diesen HTML-Generatoren wurde die ganze harte Arbeit bereits für Sie erledigt. Alles, was Sie tun müssen, ist Kopieren und Einfügen. Klar, sicher und einfach!"
---