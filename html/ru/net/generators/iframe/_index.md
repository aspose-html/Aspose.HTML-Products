---
translation: true
title: Генератор HTML iFrame — онлайн инструмент и C# код
template: /templates/_template-generators-child.md
description: Генератор HTML iFrame создает код HTML и C# для элемента iframe. Просмотрите результат и скопируйте сгенерированный код на свой сайт.
url: /net/generators/iframe/
platformtag: net
generator: HTML iFrame Генератор
element: HTML iframe
tag: iframe
---

{{<section banner>}}
---
h1: HTML iFrame Генератор
h2: Создайте код HTML и C# для элемента HTML iFrame и используйте его на своем веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Создавайте HTML iFrame на лету!
---

Элемент HTML [iframe](https://html.spec.whatwg.org/multipage/iframe-embed-object.html#the-iframe-element) представляет [вложенный контекст просмотра](https://html.spec.whatwg.org/multipage/browsers.html#nested-browsing-context) и используется для встраивания другого документа в текущий документ HTML. С помощью Генератора HTML iFrame вы можете создавать `<iframe>` элемент и настраивать его в соответствии со своими требованиями. Вы можете указать его ширину и высоту в процентах, а также в пикселях, дать имя, установить прокрутку и границы.

{{<section plugin>}}

{{< app/html/generator name="iframe" >}}

<br>
<h2> Атрибуты </h2>

 - Атрибут `src` является обязательным и определяет URL-адрес вложенной веб-страницы.
 - Атрибут `name` указывает целевое имя iframe.
 - Атрибуты `width` и `height` определяют ширину и высоту iframe. Ширина по умолчанию составляет 300 пикселей, а высота по умолчанию — 150 пикселей.
 - Атрибут `scrolling` указывает, когда браузер должен предоставить полосу прокрутки для фрейма.
 <br>

<h2> Как создать HTML iFrame на C#</h2>

Aspose.HTML for .NET API поддерживает набор элементов HTML, определенных в стандарте HTML, а также правила вложения элементов. Вы можете изменить документ, добавив новые элементы, удалив или отредактировав содержимое существующих узлов. Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить элемент `<iframe>`, рассмотрите приведенный ниже пример кода C#:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги по созданию HTML iFrame на C#
---
1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания [HTMLIFrameElement.](https://reference.aspose.com/html/net/aspose.html/htmliframeelement/)
2. Установите значения для [Src](https://reference.aspose.com/html/net/aspose.html/htmliframeelement/src/), [Name](https://reference.aspose.com/html/net/aspose.html/htmliframeelement/name/), [Height](https://reference.aspose.com/html/net/aspose.html/htmliframeelement/height/) и [Width](https://reference.aspose.com/html/net/aspose.html/htmliframeelement/width/) атрибутов.
3. Скопируйте код C# для HTML iFrame и используйте его в своем проекте.

{{<section other-generators>}}
---
title: Другие поддерживаемые генераторы HTML
subTitle: "Используйте HTML Генераторы для создания настраиваемых HTML элементов без программирования! Ясно, безопасно и просто!"
---