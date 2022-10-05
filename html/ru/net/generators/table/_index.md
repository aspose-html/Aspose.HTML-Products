---
translation: true
title: Генератор Tаблиц HTML - онлайн инструмент и C# код
template: /templates/_template-generators-child.md
description: Генератор таблиц HTML создает код HTML и C# для элемента таблицы. Вы можете сгенерировать код и использовать его на своем веб-сайте или в проекте C#.
url: /net/generators/table/
platformtag: net
generator: HTML Table Генератор
element: HTML table
tag: table
---

{{<section banner>}}
---
h1: Генератор HTML Таблиц
h2: Создайте код HTML и C# для элемента таблицы HTML и используйте его на своем веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Создавайте HTML Таблицы легко!
---

Элемент HTML [table](https://html.spec.whatwg.org/multipage/tables.html#the-table-element) определяет таблицу HTML. Он содержит информацию, представленную в двумерной таблице, состоящей из строк и столбцов ячеек, содержащих данные. Таблица HTML состоит из одного элемента `<table>` и одного или нескольких элементов `<tr>`, `<th>` и `<td>`, которые определяют строку, заголовок и ячейку таблицы.

{{<section plugin>}}

{{< app/html/generator name="table" >}}

<br>
<h2> Атрибуты </h2>

Элемент `<table>` может включать глобальные атрибуты, такие как `style`, `border`, `align`, `width` и т. д.
 - Атрибут `border` указывает ширину границы для таблицы. Значение «0» означает отсутствие границы.
 - Атрибут `align` указывает, как таблица должна быть выровнена внутри содержащего ее документа. Может принимать следующие значения: left, center, right.
 - Атрибут `width` указывает ширину таблицы.
 <br><br>

<h2> Создать HTML-таблицу на C#</h2>

Aspose.HTML for .NET API поддерживает набор элементов HTML, определенных в стандарте HTML, а также правила вложения элементов. Вы можете изменить документ, добавив новые элементы, удалив или отредактировав содержимое существующих узлов. Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить элемент `<table>`, рассмотрите приведенный ниже пример кода C#:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги по созданию HTML таблицы на C#
---
1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания [HTMLTableElement.](https://reference.aspose.com/html/net/aspose.html/htmltableelement/)
2. Установите значения для атрибутов [Style](https://reference.aspose.com/html/net/aspose.html/htmlelement/style/), [Align](https://reference.aspose.com/html/net/aspose.html/htmltableelement/align/), [Border](https://reference.aspose.com/html/net/aspose.html/htmltableelement/border/) и т. д.
3. Используйте методы [InsertRow()](https://reference.aspose.com/html/net/aspose.html/htmltableelement/insertrow/) и [InsertCell()](https://reference.aspose.com/html/net/aspose.html/htmltablerowelement/insertcell/) для добавления строк и столбцов в HTML-таблицу.
3. Скопируйте код C# для таблицы HTML и используйте его в своем проекте.

{{<section other-generators>}}
---
title: Другие поддерживаемые генераторы HTML
subTitle: "Используйте HTML Генераторы для создания настраиваемых HTML элементов без программирования! Ясно, безопасно и просто!"
---