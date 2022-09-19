---
translation: true
title: HTML Color Input Generator – Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: Generieren Sie eine HTML Color Input, sehen Sie sich das Ergebnis in der Vorschau an und kopieren Sie HTML- und C#-Code auf Ihre Website
url: /net/generators/color/
platformtag: net
generator: HTML Color Input Generator
tag: color
element: HTML Color Input
---

{{<section banner>}}
---
h1: HTML Color Input Generator
h2: Generieren Sie HTML- und C#-Code für eine HTML Color Input und verwenden Sie ihn in Ihrer eigenen Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie ganz einfach HTML Color Input!
---

Ein [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element)-Element mit `type="color"` definiert eine Farbauswahl. Es stellt ein Benutzerschnittstellenelement bereit, das es einem Benutzer ermöglicht, eine Farbe festzulegen, entweder über eine visuelle Farbauswahlschnittstelle oder durch Eingeben der Farbe in ein Textfeld im Hexadezimalformat #RRGGBB. Der HTML-Farbeingabecode-Generator hilft beim Generieren von HTML-Eingabefarbcodes, die in HTML eingefügt werden können.<br>
Die Steuerung besteht aus einem kleinen Knopf, in dem die aktuelle Farbe angezeigt wird. Klicken Sie auf die Farbschaltfläche, um die Farbauswahl mit einem Anfangswert zu öffnen. Innerhalb des Steuerelements wird eine Vorschau der ausgewählten Farbe angezeigt.

{{<section plugin>}}

{{< app/html/generator name="color" >}}
<br>
<h2> Attributes </h2>

Eine Anfangsfarbe kann mit dem Attribut `value` angegeben werden, das hexadezimale Farbwerte akzeptiert. Es dürfen nur einfache Farben ohne Alphakanal verwendet werden. Der `value` muss in siebenstelliger Hexadezimalschreibweise angegeben werden. Der `value` ist nie leer. Wenn Sie keinen Wert angeben, ist der Standardwert #000000, was Schwarz bedeutet.

Sie können ein HTML-Farbeingabe-Tag und einen C#-Code für die Farbauswahl generieren, indem Sie Attribute wie `name` und `value` auswählen. <br><br>

<h2> HTML-Farbeingabe in C# erstellen</h2>

Aspose.HTML für die .NET-API unterstützt eine Reihe von HTML-Elementen, die im HTML-Standard definiert sind, zusammen mit Regeln darüber, wie die Elemente verschachtelt werden können. Sie können das Dokument ändern, indem Sie neue Elemente anhängen, den Inhalt vorhandener Knoten entfernen oder bearbeiten. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert eine Farbauswahl hinzufügen möchten, sehen Sie sich das folgende C#-Codebeispiel an:
{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen von Farbeingaben in C#
---
1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) Erstellt das durch tagName angegebene HTML-Element.
1. Legen Sie Werte für [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/) und [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) Attribute.
1. Verwenden Sie die Methode [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/), um das Attribut `value` und seinen Wert im Hexadezimalformat hinzuzufügen.
1. Kopieren Sie den C#-Code für die HTML-Farbeingabe und verwenden Sie ihn in Ihrem C#-Projekt.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Mit diesen HTML-Generatoren wurde die ganze harte Arbeit bereits für Sie erledigt. Alles, was Sie tun müssen, ist Kopieren und Einfügen. Klar, sicher und einfach!"
---