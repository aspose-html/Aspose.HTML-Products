---
translation: true
title: Генератор HTML Image Input - онлайн инструмент и C# код
template: /templates/_template-generators-child.md
description: Создайте HTML Image Input, просмотрите результат и скопируйте сгенерированный код HTML и C# на свой веб-сайт.
url: /net/generators/image-input/
platformtag: net
generator: Генератор HTML Image Input
element: HTML image input
tag: image-input
---

{{<section banner>}}
---
h1: Генератор HTML Image Input
h2: Создайте код HTML и C# для HTML Image Input и используйте его на своем веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Создать HTML Image Input
---

Элемент [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) с `type='image'` используется для создания графической кнопки отправки, которая принимает форму изображения, а не текста. Генератор HTML Image Input помогает генерировать HTML-код для графической кнопки отправки, выбирая такие атрибуты, как `name`, `src`, `alt`, `width`, `height` и `autofocus`. Легко создавайте тег кнопки с помощью синтаксиса HTML!

{{<section plugin>}}

{{< app/html/generator name="image-input" >}}

- Атрибут `src` указывает URL-адрес файла изображения, который будет отображаться для представления графической кнопки отправки.
- Атрибуты `width` и `height` задают числа, которые указывают ширину и высоту для отрисовки изображения на кнопке в пикселях CSS.
- Атрибут `alt` предоставляет альтернативный текст для использования в качестве метки кнопки, если изображение не может быть отображено.
- Логический атрибут `autofocus`, если он присутствует, указывает, что элемент `<input>` должен автоматически получать фокус при загрузке страницы.
<br>

<h2> Создать HTML Image Input на C#</h2>

Aspose.HTML for .NET API поддерживает набор элементов HTML, определенных в стандарте HTML, а также правила вложения элементов. Вы можете изменить документ, добавив новые элементы, удалив или отредактировав содержимое существующих узлов. Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить графическую кнопку, рассмотрите приведенный ниже пример кода C#:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги по созданию HTML Image Input на C#
---
1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) Он создает элемент HTML, указанный в tagName.
1. Установите значения для [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/), [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) и [Src](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/src/) атрибутов.
1. Используйте метод [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/), чтобы добавить `alt`, `width`, `height` и `autofocus` атрибуты.
1. Скопируйте код для HTML Image Input и используйте его в своем проекте C#.

{{<section other-generators>}}
---
title: Другие поддерживаемые Генераторы HTML
subTitle: "С этими Генераторами HTML вся тяжелая работа уже сделана за вас. Все, что вам нужно сделать, это скопировать и вставить код. Ясно, безопасно и просто!"
---