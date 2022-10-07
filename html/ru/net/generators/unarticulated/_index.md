---
translation: true
title: Генератор HTML Underline Text - онлайн инструмент и C# код
template: /templates/_template-generators-child.md
description: Создайте тег Underline HTML, просмотрите результат и скопируйте сгенерированный код HTML и C# на свой веб-сайт.
url: /net/generators/underline/
platformtag: net
family: html
generator: Underline Text HTML Генератор
element: Underline HTML tag
tag: underline
---

{{<section banner>}}
---
h1: Генератор HTML Underline Text
h2: Создайте код HTML и C# для HTML-тега подчеркивания текста HTML Underline Text и используйте его на своем веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Создавайте тег Underline HTML на лету!
---

HTML-тег `<u>` представляет некоторый текст, стиль которого отличается от обычного текста, например слова с ошибками. Содержимое внутри тега `<u>` обычно отображается с простым сплошным подчеркиванием. <br>
Избегайте использования элемента `<u>`, где его можно спутать с гиперссылкой! Поэтому не рекомендуется подчеркивать текст, если он вам действительно не нужен. Если вам нужно выделить текст [Еmphasize Text,](/html/{{lang.url-fragment}}net/generators/emphasize/) используйте тег `<em>`. Используйте тег `<strong>`, чтобы придать тексту высокую важность [Strong Importance.](/html/{{lang.url-fragment}}net/generators/strong/) Эти элементы были созданы специально для этих целей, и браузеры обычно отображают этот текст соответствующим образом.

{{<section plugin>}}

{{< app/html/generator name="unarticulated" >}}

<br>
<h2> Как создать Underline HTML Tag на C#</h2>

Aspose.HTML for .NET API поддерживает набор элементов HTML, определенных в стандарте HTML, а также правила вложения элементов. Вы можете изменить документ, добавив новые элементы, удалив или отредактировав содержимое существующих узлов. Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить HTML-тег подчеркивания текста `<u>`, рассмотрите приведенный ниже пример C#:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги по созданию HTML-тега подчеркивания на C#
---
1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания элемента `<u>`. Метод Document.CreateElement() создает элемент HTML, указанный в tagName, в нашем случае tagName — «u».
2. Создайте текстовое содержимое с помощью метода [CreateTextNode().](https://reference.aspose.com/html/net/aspose.html.dom/document/createtextnode/)
3. Используйте метод [AppendChild(),](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) чтобы добавить текстовое содержимое в HTML-элемент `<u>`.
4. Скопируйте код HTML-тега подчеркивания `<u>` и используйте его в своем проекте C#.

{{<section other-generators>}}
---
title: Другие поддерживаемые Генераторы HTML
subTitle: "Используйте HTML Генераторы для создания настраиваемых HTML-элементов без программирования! Ясно, безопасно и просто!"
---