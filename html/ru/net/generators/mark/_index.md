---
translation: true
title: Генератор HTML <mark> Tag (Highlight) — онлайн инструмент и C# код
template: /templates/_template-generators-child.md
description: Генерируйте HTML Mark Tag (Highlight), просмотрите результат и скопируйте сгенерированный код HTML и C# на свой веб-сайт.
url: /net/generators/mark/
platformtag: net
family: html
generator: HTML Mark Tag Генератор
element: HTML mark tag
tag: mark
---

{{<section banner>}}
---
h1: Генератор тегов HTML mark (Highlight)
h2: Создайте код HTML и C# для HTML mark элемента и используйте его на своем веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Генерируйте HTML <mark> теги на лету!
---

HTML-элемент `<mark>` определяет текст, который должен быть помечен или выделен (Highlight HTML Text). Тег `<mark>` указывает на интересующую вас часть содержимого документа, например, для обозначения слов, соответствующих операции поиска.

{{<section plugin>}}

{{< app/html/generator name="mark" >}}

<br>
<h2> Как создать HTML mark tag на C#</h2>

Aspose.HTML for .NET API поддерживает набор элементов HTML, определенных в стандарте HTML, а также правила вложения элементов. Вы можете изменить документ, добавив новые элементы, удалив или отредактировав содержимое существующих узлов. Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить mark тег для создания Highlight HTML Text, рассмотрим приведенный ниже пример C#:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги по созданию Highlight HTML Text на C#
---
1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания элемента `<mark>`. В HTML-документе метод Document.CreateElement() создает HTML-элемент, указанный в tagName, в нашем случае tagName — «mark».
2. Создайте текстовое содержимое с помощью метода [CreateTextNode().](https://reference.aspose.com/html/net/aspose.html.dom/document/createtextnode/)
3. Используйте метод [AppendChild(),](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) чтобы добавить текстовое содержимое в элемент `<mark>`.
4. Скопируйте код C# для тега `<mark>` и используйте его в своем проекте C#.

{{<section other-generators>}}
---
title: Другие поддерживаемые Генераторы HTML
subTitle: "Используйте HTML Генераторы для создания настраиваемых HTML-элементов без программирования! Ясно, безопасно и просто!"
---