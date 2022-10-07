---
translation: true
title: Генератор Quote & Blockquote HTML - онлайн инструмент и C# код
template: /templates/_template-generators-child.md
description: Генерируйте HTML-тег для Quote & Blockquote, просмотрите результат и скопируйте сгенерированный код HTML и C# на свой веб-сайт.
url: /net/generators/quote-blockquote/
platformtag: net
family: html
generator: Quote & Blockquote HTML Генератор
element: Quote or Blockquote HTML tag
tag: quote-blockquote
---

{{<section banner>}}
---
h1: Quote & Blockquote HTML Генератор
h2: Создайте код HTML и C# для тегов HTML Quote & Blockquote и используйте их на своем веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Генерируйте HTML-теги Quote и Blockquote на лету!
---

HTML-тег `<q>` — это стандартный тег цитаты, используемый для коротких цитат, не требующих разрывов абзаца. Большинство современных браузеров реализуют это, заключая текст в кавычки. HTML-элемент `<blockquote>` указывает, что заключенный в нем текст является расширенной цитатой. Обычно это визуализируется с помощью отступов. URL-адрес источника цитаты может быть указан с использованием атрибута `cite`.


{{<section plugin>}}

{{< app/html/generator name="quote-blockquote" >}}

<br>
<h2> Attributes </h2>

Атрибут `cite` указывает исходный URL цитаты. Этот атрибут предназначен для указания на информацию, объясняющую контекст или ссылку на цитату.
<br><br>

<h2> Как создать HTML Quote и Blockquote теги на C#</h2>

Aspose.HTML for .NET API поддерживает набор элементов HTML, определенных в стандарте HTML, а также правила вложения элементов. Вы можете изменить документ, добавив новые элементы, удалив или отредактировав содержимое существующих узлов. Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить HTML-теги Quote и Blockquote, рассмотрите приведенный ниже пример C#:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги по созданию HTML-тега Quote на C#
---

1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания HTML-элемента `<q>`. Метод Document.CreateElement() создает [HTMLQuoteElement](https://reference.aspose.com/html/net/aspose.html/htmlquoteelement/), указанный в tagName, в нашем случае tagName "q".
2. Установите значение атрибута [Cite.](https://reference.aspose.com/html/net/aspose.html/htmlquoteelement/cite/)
3. Создайте текстовое содержимое с помощью метода [CreateTextNode().](https://reference.aspose.com/html/net/aspose.html.dom/document/createtextnode/)
4. Используйте метод [AppendChild(),](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) чтобы добавить текстовое содержимое в элемент `<q>`.
5. Скопируйте код C# для HTML-тега `<q>` и используйте его в своем проекте C#.

{{<section other-generators>}}
---
title: Другие поддерживаемые Генераторы HTML
subTitle: "Используйте HTML Генераторы для создания настраиваемых HTML-элементов без программирования! Ясно, безопасно и просто!"
---