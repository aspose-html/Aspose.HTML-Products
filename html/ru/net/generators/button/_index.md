---
translation: true
title: HTML Button Генератор - онлайн инструмент и C# код 
template: /templates/_template-generators-child.md
description: Генератор создает кнопку HTML и код C# для этого элемента. Генерируйте код и используйте его на своем веб-сайте или в проекте C#.
url: /net/generators/button/
platformtag: net
generator: HTML Button Генератор
element: HTML кнопка
tag: button
---

{{<section banner>}}
---
h1: Генератор HTML кнопок
h2: Создайте код HTML и C# для элемента кнопки HTML и используйте его на своем веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Создайте HTML кнопку на лету!
---

Элемент `<button>` [HTML](https://html.spec.whatwg.org/multipage/form-elements.html#the-button-element) — это интерактивный элемент, определяющий кнопку, на которую можно нажать. Вы можете активировать кнопку HTML с помощью мыши, клавиатуры, голосовой команды или других вспомогательных технологий. `<button>` – это тип элемента формы, который используется для отправки, сброса [формы](https://html.spec.whatwg.org/multipage/forms.html#the-form-element) или открытия диалогового окна. После активации он выполняет запрограммированное действие.

{{<section plugin>}}

{{< app/html/generator name="button" >}}

<br>
<h2> Attributes </h2>

Атрибуты элемента `<button>` включают: *name*, *type*, *value*, *autofocus*, *form*, *disabled*, *formaction* и т. д. Но все эти атрибуты являются необязательными. Однако вы всегда должны указывать атрибут *type* для элемента `<button>`, чтобы сообщить браузеру, какой это тип кнопки, поскольку разные браузеры используют разные *type* по умолчанию для элемента кнопки. Внутри тега `<button>` вы можете поместить текст и добавить значки к вашей кнопке, чтобы сделать ее уникальной.
<br><br>

<h2> Создать HTML кнопку на C#</h2>

Aspose.HTML for .NET API поддерживает набор элементов HTML, определенных в стандарте HTML, а также правила вложения элементов. Вы можете изменить документ, добавив новые элементы, удалив или отредактировав содержимое существующих узлов. Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить элемент `<button>`, см. приведенный ниже пример кода C#. Создать HTML кнопку можно с помощью нескольких строк кода C#:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги по созданию HTML кнопки на C#
---
1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания [HTMLButtonElement.](https://reference.aspose.com/html/net/aspose.html/htmlbuttonelement/) 
2. Установите значения для [Type](https://reference.aspose.com/html/net/aspose.html/htmlbuttonelement/type/), [Name](https://reference.aspose.com/html/net/aspose.html/htmlbuttonelement/name/), [TextContent](https://reference.aspose.com/html/net/aspose.html.dom/element/textcontent/) и [Disabled.](https://reference.aspose.com/html/net/aspose.html/htmlbuttonelement/disabled/)
3. Скопируйте код для кнопки HTML и используйте его в своем проекте C#.



{{<section other-generators>}}
---
title: Другие поддерживаемые Генераторы HTML
subTitle: "С Генераторами HTML вся тяжелая работа уже сделана за вас. Все, что вам нужно сделать, это скопировать и вставить код. Ясно, безопасно и просто!"
---