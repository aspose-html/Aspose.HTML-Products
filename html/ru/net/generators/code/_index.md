---
translation: true
title: Генератор <code> тегов HTML — онлайн инструмент и C# код
template: /templates/_template-generators-child.md
description: Создайте HTML code tag, просмотрите результат и скопируйте сгенерированный код HTML и C# на свой веб-сайт.
url: /net/generators/code/
platformtag: net
family: html
generator: HTML code Tag Генератор
element: HTML code tag
tag: code
---

{{<section banner>}}
---
h1: HTML code Tag Генератор
h2: Создайте код HTML и C# для HTML `<code>` элемента и используйте его на своем веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Генерируйте <code> теги HTML легко!
---

HTML-элемент `<code>` используется для определения фрагмента компьютерного кода. По умолчанию текст содержимого отображается с использованием стандартного моноширинного шрифта браузера. Этот элемент может включать только глобальные атрибуты.

{{<section plugin>}}

{{< app/html/generator name="code" >}}

<br><br>
<h2> Создать HTML code Tag на C#</h2>

Aspose.HTML for .NET API поддерживает набор элементов HTML, определенных в стандарте HTML, а также правила вложения элементов. Вы можете изменить документ, добавив новые элементы, удалив или отредактировав содержимое существующих узлов. Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить HTML тег `<code>`, рассмотрите приведенный ниже пример C#. Вы можете создать нужный элемент с помощью нескольких строк кода:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги по созданию  code тега HTML на C#
---

1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания элемента `<code>`. В HTML-документе метод Document.CreateElement() создает HTML-элемент, указанный в tagName, в нашем случае tagName — это «code».
2. Создайте текстовое содержимое с помощью метода [CreateTextNode().](https://reference.aspose.com/html/net/aspose.html.dom/document/createtextnode/)
3. Используйте метод [AppendChild(),](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) чтобы добавить текстовое содержимое в элемент `<code>`.

{{<section other-generators>}}
---
title: Другие поддерживаемые Генераторы HTML
subTitle: "Используйте HTML Генераторы для создания настраиваемых HTML элементов без программирования! Ясно, безопасно и просто!"
---