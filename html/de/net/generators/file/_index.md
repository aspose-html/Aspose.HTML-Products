---
translation: true
title: HTML File Input Generator – Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: Generieren Sie HTML- und C#-Code für die HTML File Input und verwenden Sie ihn in Ihrer eigenen Website oder Ihrem C#-Projekt.
url: /net/generators/file/
platformtag: net
generator: HTML File Input Generator
element: HTML File Input
tag: file
---

{{<section banner>}}
---
h1: HTML File Input Generator
h2: Generieren Sie HTML- und C#-Code für eine HTML File Input und verwenden Sie ihn in Ihrer eigenen Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie einfach eine Dateieingabe!
---

Ein [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element)-Element mit `type="file"` ermöglicht es dem Benutzer, eine oder mehrere Dateien von seinem Gerät auszuwählen Lagerung. Nach der Auswahl können die Dateien mithilfe der Formularübermittlung auf einen Server hochgeladen oder mithilfe von JavaScript-Code und der Datei-API bearbeitet werden. Einfaches Generieren von Dateieingabe-Tags mit HTML-Syntax!

{{<section plugin>}}

{{< app/html/generator name="file" >}}

<br>
<h2> Attributes </h2>

Der HTML-Datei-Eingabegenerator hilft beim Generieren von HTML-Code für Eingabe-Tags mit `type='file'`, indem Attribute wie `name`, `accept` und `multiple` ausgewählt werden.

 - Der Wert des Attributs `accept` ist eine Zeichenfolge, die einen oder mehrere eindeutige Dateitypbezeichner enthält, die durch Kommas getrennt sind. Dies können Dateierweiterungen sein, die einen Punkt enthalten, wie z. B. .jpg, .png, .pdf, oder Zeichenfolgen vom MIME-Typ ohne Erweiterungen, wie z. B. audio/* - jede Audiodatei wird akzeptiert. Wenn der Attributwert leer gelassen wird, werden alle Dateitypen akzeptiert.
 - Wenn das boolesche Attribut `multiple` gesetzt ist, erlaubt die Dateieingabe dem Benutzer, mehr als eine Datei auszuwählen.
<br><br>

<h2> HTML-Dateieingabe in C# erstellen</h2>

Aspose.HTML für die .NET-API unterstützt eine Reihe von HTML-Elementen, die im HTML-Standard definiert sind, zusammen mit Regeln darüber, wie die Elemente verschachtelt werden können. Sie können das Dokument ändern, indem Sie neue Elemente anhängen, den Inhalt vorhandener Knoten entfernen oder bearbeiten. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert eine HTML-Dateieingabe hinzufügen möchten, sehen Sie sich das C#-Codebeispiel unten an. Mit wenigen Zeilen C#-Code erstellen Sie das gewünschte Element:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen einer HTML-Dateieingabe in C#
---
1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) Erstellt das durch tagName angegebene HTML-Element.
1. Legen Sie Werte für [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/), [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) und [Accept](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/accept/) Attribute.
1. Verwenden Sie die Methode [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/), um das Attribut `multiple` hinzuzufügen.
1. Kopieren Sie den C#-Code für die Eingabe der HTML-Datei und verwenden Sie ihn in Ihrem C#-Projekt.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Mit diesen HTML-Generatoren wurde die ganze harte Arbeit bereits für Sie erledigt. Alles, was Sie tun müssen, ist Kopieren und Einfügen. Klar, sicher und einfach!"
---