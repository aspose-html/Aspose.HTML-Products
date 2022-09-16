---
translation: true
title: HTML Radio Button Generator – Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: Generieren Sie HTML-Radiobuttons für Ihre Website. Sie können Optionsfelder in der Vorschau anzeigen und HTML- und C#-Code kopieren
url: /net/generators/radio/
platformtag: net
generator: HTML-Radio-Button-Generator
element: HTML-Radiobutton
tag: radio
---

{{<section banner>}}
---
h1: HTML-Radio-Button-Generator
h2: Generieren Sie HTML- und C#-Code für einen HTML-HTML-Radio-Button und verwenden Sie ihn in Ihrer eigenen Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie HTML-Optionsschaltflächen im Handumdrehen!
---

Der [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element)-type `radio` wird zum Erstellen von Optionsfeldern verwendet. Sie werden Radiobuttons genannt, weil sie genauso aussehen und funktionieren wie die Knöpfe an alten Radios. Optionsfelder werden normalerweise verwendet, um ein Gruppenelement anzuzeigen. Es kann immer nur ein Optionsfeld in einer Gruppe ausgewählt werden. Optionsfelder werden normalerweise als kleine Kreise angezeigt, die sich füllen oder hervorheben, wenn sie ausgewählt werden.
Kontrollkästchen ähneln Optionsfeldern, aber Optionsfelder dienen dazu, einen einzelnen Wert aus einem Satz auszuwählen, während Sie mit Kontrollkästchen einzelne Werte ein- und ausschalten können.

{{<section plugin>}}

{{< app/html/generator name="radio" >}}

<br>
<h2> Attributes </h2>

Sie können ein Eingabe-Tag für HTML-Optionsfelder und C#-Code generieren, indem Sie Attribute wie `name`, `id`, `checked` usw. auswählen.

- Das Attribut `name` definiert eine Gruppe von Optionsfeldern, indem es jedem Optionsfeld in der Gruppe den gleichen Namen gibt.
- Das Attribut `id` gibt einen eindeutigen Wert an, der ein einzelnes Optionsfeld in der Gruppe eindeutig identifiziert.
- Das boolesche Attribut `checked`, falls vorhanden, zeigt an, dass dieses Optionsfeld das standardmäßig ausgewählte in der Gruppe ist.
<br><br>

<h2> Optionsfeld in C# erstellen</h2>

Aspose.HTML für die .NET-API unterstützt eine Reihe von HTML-Elementen, die im HTML-Standard definiert sind, zusammen mit Regeln darüber, wie die Elemente verschachtelt werden können. Sie können das Dokument ändern, indem Sie neue Elemente anhängen, den Inhalt vorhandener Knoten entfernen oder bearbeiten. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert ein Optionsfeld hinzufügen möchten, sehen Sie sich das C#-Codebeispiel unten an. Mit wenigen Zeilen C#-Code erstellen Sie das gewünschte Element:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen von HTML-Optionsschaltflächen in C#
---
1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) Erstellt das durch tagName angegebene HTML-Element.
1. Legen Sie Werte für [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/), [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/), [Id](https://reference.aspose.com/html/net/aspose.html/htmlelement/id/) und [Checked](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/checked/) Attribute.
1. Erstellen Sie das [HTMLLabelElement](https://reference.aspose.com/html/net/aspose.html/htmllabelelement/) und legen Sie die erforderlichen Attribute fest.
1. Kopieren Sie den C#-Code für das HTML-Optionsfeld und verwenden Sie ihn in Ihrem C#-Projekt.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Mit diesen HTML-Generatoren wurde die ganze harte Arbeit bereits für Sie erledigt. Alles, was Sie tun müssen, ist Kopieren und Einfügen. Klar, sicher und einfach!"
---