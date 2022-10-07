---
translation: true
title: Генератор HTML Superscript & Subscript — онлайн инструмент и C# код
template: /templates/_template-generators-child.md
description: Создайте тег HTML Superscript & Subscript, просмотрите результат и скопируйте сгенерированный код HTML и C# на свой веб-сайт.
url: /net/generators/superscript-subscript/
platformtag: net
family: html
generator: Superscript & Subscript HTML Generator
element: Superscript or Subscript HTML tag
tag: superscript-subscript
---

{{<section banner>}}
---
h1: Генератор верхнего и нижнего индекса Superscript & Subscript HTML
h2: Создайте код HTML и C# для тега HTML `<sup>` или `<sub>` и используйте его на своем веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Генерируйте тег верхнего <sup> и нижнего <sub> индекса HTML на лету!
---

HTML-тег `<sup>` используется для добавления надстрочного текста в HTML-документ. Верхние индексы обычно отображаются с приподнятой базовой линией, используя меньший текст. Надстрочный текст появляется на полсимвола выше обычной строки и обычно используется для сносок.

HTML-тег `<sub>` определяет встроенный текст, который должен отображаться как нижний индекс по чисто типографским причинам. Подстрочные индексы обычно отображаются с более низкой базовой линией, используя меньший текст. Подстрочный текст отображается на полсимвола ниже обычной строки и может использоваться, например, для химических формул.

{{<section plugin>}}

{{< app/html/generator name="superscript-subscript" >}}

<br>
<h2> Как создать HTML Superscript & Subscript Tags на C#</h2>

Aspose.HTML for .NET API поддерживает набор элементов HTML, определенных в стандарте HTML, а также правила вложения элементов. Вы можете изменить документ, добавив новые элементы, удалив или отредактировав содержимое существующих узлов. Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить теги HTML Superscript и Subscript, рассмотрите приведенный ниже пример C#. Вы можете создать `<sup>` или `<sub>` элемент с помощью нескольких строк кода:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги по созданию тега верхнего индекса Superscript HTML на C#
---

1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания элемента `<sup>`. В HTML-документе метод Document.CreateElement() создает HTML-элемент, указанный в tagName, в нашем случае tagName — «sup».
2. Создайте текстовое содержимое с помощью метода [CreateTextNode().](https://reference.aspose.com/html/net/aspose.html.dom/document/createtextnode/)
3. Используйте метод [AppendChild(),](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) чтобы добавить текстовое содержимое в элемент `<sup>`.
4. Скопируйте код C# для тега HTML Superscript и используйте его в своем проекте.

{{<section other-generators>}}
---
title: Другие поддерживаемые Генераторы HTML
subTitle: "Используйте HTML Генераторы для создания настраиваемых HTML-элементов без программирования! Ясно, безопасно и просто!"
---