---
translation: true
title: HTML Textarea Generator - Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: Erstellen Sie ein HTML-Textarea-Element für Ihre Website. Prüfen Sie den Textbereich, kopieren und verwenden Sie generierten HTML- und C#-Code in Ihrem Projekt!
url: /net/generators/textarea/
platformtag: net
generator: HTML-Textarea-Generator
element: HTML-Textbereich
tag: Textbereich
---

{{<section banner>}}
---
h1: HTML-Textarea-Generator
h2: Generieren Sie HTML- und C#-Code für ein HTML-Textarea-Element und verwenden Sie es in Ihrer eigenen Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie HTML Textarea on the fly!
---

Das HTML-Element [textarea](https://html.spec.whatwg.org/multipage/form-elements.html#the-textarea-element) definiert einen Bereich, in den Sie mehrere Textzeilen eingeben können. Dies ist ein mehrzeiliges Klartext-Bearbeitungselement, das es Benutzern ermöglicht, große Textmengen in beliebiger Form einzugeben, z. B. Bewertungen, Kommentare oder Feedback-Formulare.

<b>Hinweis:</b> Textfelder werden in zwei Typen eingeteilt: Textfelder und Textbereiche. Diese beiden Textfelder dienen verschiedenen Zwecken und helfen Benutzern zu verstehen, was sie in das Textfeld eingeben sollten. Ein Textbereich wird durch ein `<textarea>`-Tag definiert. Sie können eine kleine [Texteingabe](/html/{{lang.url-fragment}}net/generators/text/)-Box definieren, indem Sie HTML-`<input>`-Elemente mit `type='text'` verwenden.

{{<section plugin>}}

{{< app/html/generator name="textarea" >}}

<br>
<h2> Attributes </h2>

Ein Textbereich ist ein großes Textfeld, in das Sie mehrere Textzeilen eingeben können, z. B. Beschreibungen, Absätze usw.
- Ein "name"-Attribut gibt einen Namen für einen Textbereich an. Es wird benötigt, um auf die Formulardaten zu verweisen, nachdem das Formular gesendet wurde.
- Ein „Platzhalter“-Attribut ist eine Zeichenfolge, die dem Benutzer einen kurzen Hinweis darauf gibt, welche Informationen in dem Feld erwartet werden.
- Eine „Rechtschreibprüfung“ ist ein Attribut, das verwendet wird, um anzugeben, ob die Rechtschreibprüfung für ein Element aktiviert werden soll.
- Die Attribute "minlength" und "maxlength" definieren die minimale und maximale Anzahl von Zeichen, die der Benutzer eingeben kann.


<br><br>

<h2> HTML-Textbereich in C# erstellen</h2>

Aspose.HTML für die .NET-API funktioniert als Headless-Browser, mit dem Sie vorhandene HTML-Dokumente aus verschiedenen Quellen erstellen oder öffnen können, um Bearbeitungsvorgänge wie das Entfernen, Anhängen und Ersetzen von HTML-Knoten durchzuführen. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert ein HTML-„<textarea>“-Element hinzufügen möchten, sehen Sie sich das C#-Beispiel unten an. Sie können einen Textbereich mit ein paar Zeilen Code erstellen:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen von HTML-Textareas in C#
---
1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um [HTMLTextareaElement.](https://reference.aspose.com/html/net/aspose.html/htmltextareaelement/) Erstellt das durch tagName angegebene HTML-Element.
1. Legen Sie Werte für [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/), [Cols](https://reference.aspose.com/html/ net/aspose.html/htmltextareaelement/cols/) und [Rows](https://reference.aspose.com/html/net/aspose.html/htmltextareaelement/rows/) Attribute.
1. Verwenden Sie die Methode [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/), um „placeholder“, „spellcheck“, „minlength“, „ maxlength` oder andere unterstützte Attribute mit ihren Werten.
1. Kopieren Sie den C#-Code für das HTML-Element textarea und verwenden Sie ihn in Ihrem Projekt.



{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Mit diesen HTML-Generatoren wurde die ganze harte Arbeit bereits für Sie erledigt. Alles, was Sie tun müssen, ist Kopieren und Einfügen. Klar, sicher und einfach!"
---