---
translation: true
title: HTML-Email-Input-Generator – Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: Generieren Sie eine HTML-E-Mail-Eingabe, sehen Sie sich das Ergebnis in der Vorschau an und kopieren Sie den generierten HTML- und C#-Code auf Ihre Website.
url: /net/generators/email/
platformtag: net
generator: HTML-Email-Input-Generator
element: HTML-Email-Input 
tag: email
---

{{<section banner>}}
---
h1: HTML-Email-Input-Generator
h2: Generieren Sie HTML- und C#-Code für eine HTML-Email-Input und verwenden Sie ihn in Ihrer eigenen Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie einfach HTML-Email-Input!
---

Ein [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element)-Element mit `type='email'` wird verwendet, damit der Benutzer eine E-Mail eingeben und bearbeiten kann Adresse oder eine Liste mit E-Mail-Adressen. Der Eingabewert wird automatisch validiert, um sicherzustellen, dass es sich um eine richtig formatierte E-Mail-Adresse handelt.

{{<section plugin>}}

{{< app/html/generator name="email" >}}

Der HTML-E-Mail-Eingabegenerator hilft beim Generieren von HTML-Code für das Eingabe-Tag mit `type='email'`, indem Attribute wie `name`, `placeholder`, `size`, `multiple`, `required` und `pattern` ausgewählt werden.

- Das Attribut `placeholder` ist eine Zeichenfolge, die dem Benutzer einen kurzen Hinweis darauf gibt, welche Informationen in dem Feld erwartet werden.
- Das Attribut `size` ist ein numerischer Wert, der angibt, wie viele Zeichen im Eingabefeld enthalten sein sollen. Der Standardwert ist 20.
- Das boolesche Attribut `multiple` gibt an, dass der Benutzer mehrere durch Kommas getrennte E-Mail-Adressen eingeben kann.
- Das Attribut `pattern` ist ein regulärer Ausdruck, dem der Eingabewert entsprechen muss, damit der Wert die Beschränkungsvalidierung besteht. Wenn das angegebene Muster nicht angegeben oder ungültig ist, wird der reguläre Ausdruck nicht angewendet und dieses Attribut vollständig ignoriert.
<br>

<h2> HTML-Email-Input in C# Erstellen</h2>

Aspose.HTML für die .NET-API unterstützt eine Reihe von HTML-Elementen, die im HTML-Standard definiert sind, zusammen mit Regeln darüber, wie die Elemente verschachtelt werden können. Sie können das Dokument ändern, indem Sie neue Elemente anhängen, den Inhalt vorhandener Knoten entfernen oder bearbeiten. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert eine HTML-E-Mail-Eingabe hinzufügen möchten, sehen Sie sich das C#-Codebeispiel unten an. Mit wenigen Zeilen C#-Code erstellen Sie das gewünschte Element:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen von HTML-Email-Input in C#
---

1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) Erstellt das durch tagName angegebene HTML-Element.
1. Legen Sie Werte für [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/), [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) und [Size](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/size/) Attribute.
1. Verwenden Sie die Methode [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/), um die Attribute `multiple`, `required` und `pattern` hinzuzufügen.
1. Kopieren Sie den C#-Code für die HTML-E-Mail-Eingabe und verwenden Sie ihn in Ihrem C#-Projekt.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Mit diesen HTML-Generatoren wurde die ganze harte Arbeit bereits für Sie erledigt. Klar, sicher und einfach!"
---