---
translation: true
title: HTML-Table-Generator – Online-Tool und C#-Code
template: /templates/_template-generators-child.md
description: Der HTML-Table-Generator erstellt HTML- und C#-Code für ein Tabellenelement. Verwenden Sie es in Ihrer eigenen Website oder Ihrem C#-Projekt
url: /net/generators/table/
platformtag: net
generator: HTML-Table-Generator
element: HTML-Table
tag: table
---

{{<section banner>}}
---
h1: HTML-Table-Generator
h2: Generieren Sie HTML- und C#-Code für ein HTML-Table element und verwenden Sie es in Ihrer eigenen Website oder Ihrem C#-Projekt.
---

{{<section overview>}}
---
h2: Generieren Sie ganz einfach eine HTML-Table!
---

Das [HTML-Table](https://html.spec.whatwg.org/multipage/tables.html#the-table-element) element definiert eine HTML-Tabelle. Es stellt die Informationen dar, die in einer zweidimensionalen Tabelle präsentiert werden, die aus Zeilen und Spalten von Zellen besteht, die Daten enthalten. Eine HTML-Tabelle besteht aus einem `<table>`-Element und einem oder mehreren `<tr>`, `<th>`- und `<td>`-Elementen, die eine Tabellenzeile, einen Tabellenkopf und eine Tabellenzelle definieren.

{{<section plugin>}}

{{< app/html/generator name="table" >}}

<br>
<h2> Attributes </h2>

Das `<table>`-Element kann globale Attribute wie `style`, `border`, `align`, `width` usw. enthalten.

 - Das Attribut `border` gibt die Rahmenbreite an. Ein Wert von "0" bedeutet kein Rand.
 - Das Attribut `align` gibt an, wie die Tabelle innerhalb des enthaltenden Dokuments ausgerichtet werden muss. Es kann die folgenden Werte haben: left, center, right.
 - Das Attribut `width` gibt die Breite der Tabelle an.
 <br><br>

<h2> HTML-Table in C# erstellen</h2>

Aspose.HTML für die .NET-API unterstützt eine Reihe von HTML-Elementen, die im HTML-Standard definiert sind, zusammen mit Regeln darüber, wie die Elemente verschachtelt werden können. Sie können das Dokument ändern, indem Sie neue Elemente anhängen, den Inhalt vorhandener Knoten entfernen oder bearbeiten. Wenn Sie die HTML-Bearbeitungsfunktionen in Ihrem Produkt verwenden oder programmgesteuert ein `<table>`-Element hinzufügen möchten, sehen Sie sich das folgende C#-Codebeispiel an:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Schritte zum Erstellen einer HTML-Table in C#
---
1. Verwenden Sie die Methode [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) der Document-Klasse, um ein [HTMLTableElement.](https://reference.aspose.com/html/net/aspose.html/htmltableelement/)
2. Legen Sie Werte für [Style](https://reference.aspose.com/html/net/aspose.html/htmlelement/style/), [Align](https://reference.aspose.com/html/net/aspose.html/htmltableelement/align/), [Border](https://reference.aspose.com/html/net/aspose.html/htmltableelement/border/) Attribute usw.
3. Verwenden Sie [InsertRow()](https://reference.aspose.com/html/net/aspose.html/htmltableelement/insertrow/) und [InsertCell()](https://reference.aspose.com/html/net/aspose.html/htmltablerowelement/insertcell/) Methoden, um Zeilen und Spalten für die HTML-Tabelle hinzuzufügen.
3. Kopieren Sie den C#-Code für die HTML-Table und verwenden Sie ihn in Ihrem Projekt.

{{<section other-generators>}}
---
title: Andere unterstützte HTML-Generatoren
subTitle: "Verwenden Sie HTML-Generatoren, um hochgradig anpassbare HTML-Elemente ohne Programmierung zu erstellen! Klar, sicher und einfach!"
---