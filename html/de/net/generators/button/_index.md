---
translation: true
title: HTML Button Generator – Online-Plugin und C#-Code
template: /templates/_template-generators-child.md
description: Generieren Sie HTML- und C#-Code für das HTML-Button-Element und verwenden Sie es in Ihrer eigenen Website oder Ihrem C#-Projekt.
url: /net/generators/button/
platformtag: net
generator: HTML-Button-Generator
element: HTML-Button
tag: button
---

{{<section banner>}}
---
h1: HTML-Button-Generator
h2: Generieren Sie HTML- und C#-Code für ein HTML-Schaltflächenelement und verwenden Sie es in Ihrer eigenen Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie HTML-Button im Handumdrehen!
---

Das `<button>` [HTML](https://html.spec.whatwg.org/multipage/form-elements.html#the-button-element)-Element ist ein interaktives Element, das eine anklickbare Schaltfläche definiert. Sie können die HTML-Schaltfläche mit Maus, Tastatur, Sprachbefehl oder anderen Hilfstechnologien aktivieren. Die `<button>` ist eine Art Formularelement, das zum Senden, Zurücksetzen eines [form](https://html.spec.whatwg.org/multipage/forms.html#the-form-element) oder Öffnen verwendet wird ein Dialogfeld. Einmal aktiviert, führt es eine programmierbare Aktion aus.

{{<section plugin>}}

{{< app/html/generator name="button" >}}

<br>
<h2> Attributes </h2>

Zu den Attributen des `<button>`-Elements gehören: *name*, *type*, *value*, *autofocus*, *form*, *disabled*, *formaction*, etc. Alle diese Attribute sind jedoch optional. Sie sollten jedoch immer das Attribut *type* für ein `<button>`-Element angeben, um Browsern mitzuteilen, um welche Art von Schaltfläche es sich handelt, da verschiedene Browser unterschiedliche Standard-*type* für das Schaltflächenelement verwenden.
Innerhalb eines `<button>`-Tags können Sie Text einfügen und Ihrem Button Symbole hinzufügen, um ihn einzigartig zu machen.
<br><br>

<h2> HTML-Schaltfläche in C# erstellen</h2>

Aspose.HTML for .NET API unterstützt eine Reihe von HTML-Elementen, die im HTML-Standard definiert sind, zusammen mit Regeln darüber, wie die Elemente verschachtelt werden können. Sie können das Dokument ändern, indem Sie neue Elemente anhängen, den Inhalt vorhandener Knoten entfernen oder bearbeiten. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert ein `<button>`-Element hinzufügen möchten, sehen Sie sich das C#-Codebeispiel unten an. Sie können eine Schaltfläche mit ein paar Zeilen C#-Code erstellen:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen einer HTML-Schaltfläche in C#
---
1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um [HTMLButtonElement.](https://reference.aspose.com/html/net/aspose.html/htmlbuttonelement/) Erstellt das durch tagName angegebene HTML-Element oder ein HTMLUnknownElement, wenn tagName nicht erkannt wird.
2. Legen Sie Werte für [Type](https://reference.aspose.com/html/net/aspose.html/htmlbuttonelement/type/), [Name](https://reference.aspose.com/html/net/aspose.html/htmlbuttonelement/name/), [TextContent](https://reference.aspose.com/html/net/aspose.html.dom/element/textcontent/) und [Disabled](https://reference.aspose.com/html/net/aspose.html/htmlbuttonelement/disabled/) Attribute.
3. Kopieren Sie den C#-Code für die HTML-Schaltfläche und verwenden Sie ihn in Ihrem C#-Projekt.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Mit diesen HTML-Generatoren wurde die ganze harte Arbeit bereits für Sie erledigt. Alles, was Sie tun müssen, ist Kopieren und Einfügen. Klar, sicher und einfach!"
---