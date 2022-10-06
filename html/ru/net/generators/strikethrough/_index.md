---
translation: true
title: Strikethrough HTML Генератор — онлайн инструмент и C# код
template: /templates/_template-generators-child.md
description: Генерируйте тег HTML Strikethrough, просмотрите результат и скопируйте сгенерированный код HTML и C# на свой веб-сайт.
url: /net/generators/strikethrough/
platformtag: net
family: html
generator: Strikethrough HTML Generator
element: Strikethrough HTML tag
tag: strikethrough
---

{{<section banner>}}
---
h1: Strikethrough HTML Генератор
h2: Создайте код HTML и C# для HTML-тега `<s>` и используйте его на своем веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Создавайте HTML-теги <s> легко!
---

Тег HTML `<s>` определяет текст, который больше не является правильным, точным или релевантным. Текст будет отображаться с перечеркнутой линией. Тег `<s>` используется, когда вы пытаетесь представить вещи, которые больше не актуальны или больше не соответствуют действительности. Однако `<s>` не подходит для обозначения редактирования документа; для этого используйте элементы `<del>` и `<ins>` соответственно.

{{<section plugin>}}

{{< app/html/generator name="strikethrough" >}}

<br>
<h2> Как создать Strikethrough HTML тег на C#</h2>

Aspose.HTML для .NET API поддерживает набор элементов HTML, определенных в стандарте HTML, а также правила вложения элементов. Вы можете изменить документ, добавив новые элементы, удалив или отредактировав содержимое существующих узлов. Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить HTML-тег `<s>`, рассмотрите приведенный ниже пример C#:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги по созданию перечеркнутого Strikethrough HTML-тега на C#
---
1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания элемента `<s>`. В HTML-документе метод Document.CreateElement() создает HTML-элемент, указанный в tagName, в нашем случае tagName — «s».
2. Создайте текстовое содержимое с помощью метода [CreateTextNode().](https://reference.aspose.com/html/net/aspose.html.dom/document/createtextnode/)
3. Используйте метод [AppendChild(),](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) чтобы добавить текстовое содержимое в HTML-элемент `<s>`.
4. Скопируйте код C# для тега HTML `<s>` и используйте его в своем проекте C#.

{{<section other-generators>}}
---
title: Другие поддерживаемые Генераторы HTML
subTitle: "Используйте HTML Генераторы для создания настраиваемых HTML-элементов без программирования! Ясно, безопасно и просто!"
---