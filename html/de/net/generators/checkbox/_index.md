---
translation: true
title: HTML Checkbox Generator – Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: Generieren Sie HTML- und C#-Code für die HTML-Checkbox und verwenden Sie ihn in Ihrer eigenen Website oder Ihrem C#-Projekt.
url: /net/generators/checkbox/
platformtag: net
generator: HTML-Checkbox-Generator
element: HTML-Checkbox
tag: checkbox
---

{{<section banner>}}
---
h1: HTML-Checkbox-Generator
h2: Generieren Sie HTML- und C#-Code für ein HTML-Checkbox-Element und verwenden Sie es in Ihrer eigenen Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie HTML Checkbox on the fly!
---

Das Element [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) mit `type="checkbox"` definiert ein Kontrollkästchen. Das Kontrollkästchen ist ein Eingabefeld, das eine binäre Auswahl darstellt. Das genaue Aussehen des Kontrollkästchens hängt von der Konfiguration des Betriebssystems ab, auf dem der Browser ausgeführt wird. Es ist normalerweise quadratisch, kann aber abgerundete Ecken haben. Dies ist ein Formularelement, mit dem Benutzer eine oder mehrere Optionen aus den angegebenen Optionen auswählen können.<br> Mit dem HTML-Checkbox-Generator können Sie Kontrollkästchen-Elemente für Ihre Website erstellen. Sie können das Kontrollkästchen in der Vorschau anzeigen und den generierten HTML-Code kopieren oder herunterladen.

{{<section plugin>}}

{{< app/html/generator name="checkbox" >}}

<br>
<h2> Attributes </h2>

Das Kontrollkästchen enthält normalerweise ein `name`- und ein `value`-Attribut. Dieses Name/Wert-Paar wird beim Absenden des Formulars an den Server gesendet. Wenn das Attribut "value" nicht angegeben ist, ist der gemeldete Standardwert "on".<br>
Sie können ein HTML-Checkbox-Eingabe-Tag und einen Checkbox-C#-Code generieren, indem Sie Attribute wie `name`, `checked`, `id` usw. auswählen. Jedes Kontrollkästchen ist mit einem `label`-Element verknüpft, das um das Kontrollkästchen gewickelt ist. Bitte fügen Sie für eine bessere Zugänglichkeit immer ein `<label>`-Tag hinzu!<br><br>

<h2> HTML-Kontrollkästchen in C# erstellen</h2>

Aspose.HTML für die .NET-API unterstützt eine Reihe von HTML-Elementen, die im HTML-Standard definiert sind, zusammen mit Regeln darüber, wie die Elemente verschachtelt werden können. Sie können das Dokument ändern, indem Sie neue Elemente anhängen, den Inhalt vorhandener Knoten entfernen oder bearbeiten. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert ein Kontrollkästchen hinzufügen möchten, sehen Sie sich das C#-Codebeispiel unten an. Sie können ein Kontrollkästchen mit ein paar Zeilen C#-Code erstellen:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen eines HTML-Kontrollkästchens in C#
---
1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) Erstellt das durch tagName angegebene HTML-Element.
1. Legen Sie Werte für [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/), [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/), [Id](https://reference.aspose.com/html/net/aspose.html/htmlelement/id/) und [Checked](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/checked/) Attribute.
1. Erstellen Sie das [HTMLLabelElement](https://reference.aspose.com/html/net/aspose.html/htmllabelelement/) und legen Sie die erforderlichen Attribute fest.
1. Kopieren Sie den C#-Code für das HTML-Kontrollkästchen und verwenden Sie ihn in Ihrem C#-Projekt.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Mit diesen HTML-Generatoren wurde die ganze harte Arbeit bereits für Sie erledigt. Alles, was Sie tun müssen, ist Kopieren und Einfügen. Klar, sicher und einfach!"
---