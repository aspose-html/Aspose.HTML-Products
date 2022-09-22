---
translation: true
title: HTML Text Input Generator – Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: Generieren Sie HTML- und C# Code für HTML Text Input und verwenden Sie ihn in Ihrer eigenen Website oder im C#-Projekt.
url: /net/generators/text/
platformtag: net
generator: HTML Text Input Generator
element: HTML Text Input
tag: text
---

{{<section banner>}}
---
h1: HTML Text Input Generator
h2: Generieren Sie HTML- und C#-Code für ein HTML Text Input element und verwenden Sie es in Ihrer eigenen Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie ganz einfach HTML Text Input!
---

HTML [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element)-Elemente mit `type='text'` erstellen einfache einzeilige Texteingaben. Verwenden Sie sie, wenn Sie möchten, dass Benutzer einen einzelnen Zeilenwert eingeben. Wenn Sie ein Smartphone oder Tablet verwenden, wird eine Bildschirmtastatur angezeigt. Mit diesem HTML Text Input Generator können Sie Code erstellen, der in HTML eingefügt werden kann. Wählen Sie einfach Optionen aus und erhalten Sie die Texteingabe im Handumdrehen!

<b>Hinweis:</b> Textfelder werden in zwei Typen eingeteilt: Textfelder und [textarea.](/html/{{lang.url-fragment}}net/generators/textarea/) Diese beiden Textfelder dienen für unterschiedliche Zwecke und helfen Benutzern zu verstehen, was sie in das Textfeld eingeben sollten. Ein HTML-Tag `<textarea>` definiert einen Bereich, in den Sie mehrere Textzeilen eingeben können.

{{<section plugin>}}

{{< app/html/generator name="text" >}}

<br>
<h2> Attributes </h2>

Mit dem Eingabeelement `type='text'` können Sie Attribute wie *name*, *size*, *placeholder*, *list*, *required*, *spellcheck*, *maxlength*, *minlength* usw. verwenden .

- Das Attribut `size` ist ein numerischer Wert, der angibt, wie viele Zeichen im Eingabefeld enthalten sein sollen. Die Standardbreite des Textfeldes beträgt 20 Zeichen.
- Das Attribut `placeholder` ist eine Zeichenfolge, die dem Benutzer einen kurzen Hinweis darauf gibt, welche Informationen in dem Feld erwartet werden.
- Die `spellcheck` ist ein Attribut, das verwendet wird, um anzugeben, ob die Rechtschreibprüfung für ein Element aktiviert werden soll.
- Fügen Sie ein `required` Attribut hinzu, um sicherzustellen, dass Benutzer dieses Feld ausfüllen.
<br><br>

<h2> HTML Text Input in C# erstellen</h2>

Aspose.HTML for .NET API funktioniert als Headless-Browser, mit dem Sie vorhandene HTML-Dokumente aus verschiedenen Quellen erstellen oder öffnen können, um Bearbeitungsvorgänge wie das Entfernen, Anhängen und Ersetzen von HTML-Knoten durchzuführen. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert eine Texteingabe hinzufügen möchten, sehen Sie sich das folgende C#-Codebeispiel an:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen von Texteingaben in C#
---
1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) Erstellt das durch tagName angegebene HTML-Element.
1. Legen Sie Werte für [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/), [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) und die Attribute [Size.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/size/)
1. Verwenden Sie die Methode [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/), um `placeholder`, `spellcheck` oder andere unterstützte Attribute hinzuzufügen Werte.
1. Kopieren Sie den C#-Code für die HTML Text Input und verwenden Sie ihn in Ihrem Projekt.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Mit diesen HTML-Code-Generatoren wurde die ganze harte Arbeit bereits für Sie erledigt. Alles, was Sie tun müssen, ist Kopieren und Einfügen. Klar, sicher und einfach!"
---