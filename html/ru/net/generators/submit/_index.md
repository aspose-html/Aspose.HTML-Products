---
translation: true
title: Генератор HTML Submit Input — Онлайн инструмент и C# код
template: /templates/_template-generators-child.md
description: Создайте HTML Submit Input для своего веб-сайта. Просмотрите кнопку отправки, скопируйте и используйте код HTML и C# в своем проекте!
url: /net/generators/submit/
platformtag: net
generator: Генератор HTML Submit Input
element: HTML submit input
tag: submit
---

{{<section banner>}}
---
h1: Генератор HTML Submit Input
h2: Создайте код HTML и C# для элемента HTML Submit Input и используйте его на своем веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Создавайте HTML Submit Input легко!
---

Элемент [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) с `type='submit'` отображается как кнопка отправки, которая отсылает форму в сервер. Когда пользователь нажимает кнопку, пользовательский агент пытается отправить форму на сервер. Генератор HTML Submit Input поможет вам генерировать код, который можно вставить в HTML документ. Просто выберите параметры и создайте кнопку отправки на лету!

{{<section plugin>}}

{{< app/html/generator name="submit" >}}

<br>
<h2> Атрибуты </h2>

Атрибут `value` содержит строку, которая отображается как метка кнопки. В противном случае, если вы не укажете значение, кнопка будет иметь метку по умолчанию, выбранную пользовательским агентом. Если вы хотите отключить кнопку отправки, установите для нее атрибут `disabled`.<br><br>

<h2> Создать HTML Submit Input на C#</h2>

Aspose.HTML for .NET API работает как автономный браузер, который позволяет создавать или открывать существующие HTML-документы из различных источников для выполнения операций редактирования, таких как удаление, добавление и замена узлов HTML. Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить кнопку отправки, рассмотрите приведенный ниже пример. Вы можете создать входной тег HTML submit input с помощью нескольких строк кода C#:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги по созданию HTML Submit Input на C#
---
1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) Он создает элемент HTML, указанный в tagName.
1. Установите значения для [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/) и [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) атрибутов.
1. Используйте метод [SetAttribute(),](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/) чтобы добавить `value`, `disabled` или другие поддерживаемые атрибуты.
1. Скопируйте код C# для HTML submit input и используйте его в своем проекте.

{{<section other-generators>}}
---
title: Другие поддерживаемые Генераторы HTML
subTitle: "С помощью Генераторов HTML-кода вся тяжелая работа уже сделана за вас. Все, что вам нужно сделать, это скопировать и вставить. Ясно, безопасно и просто!"
---