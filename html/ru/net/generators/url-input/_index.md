---
translation: true
title: Генератор HTML URL Input — Онлайн инструмент и C# код
template: /templates/_template-generators-child.md
description: Создайте HTML URL Input для вашего веб-сайта. Просмотрите ввод URL, скопируйте и используйте сгенерированный код HTML и C# в своем проекте!
url: /net/generators/url-input/
platformtag: net
generator: Генератор HTML URL Input
element: HTML URL Input
tag: url-input
---

{{<section banner>}}
---
h1: Генератор HTML URL Input
h2: Создайте код HTML и C# для HTML URL Input и используйте его на своем собственном веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Создавайте HTML URL Input легко!
---

Элемент [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) с `type='url'` определяет поле для ввода URL. Он принимает только null или действительный URL. Это входное значение автоматически проверяется перед отправкой формы. Генератор HTML URL Input поможет вам генерировать код, который можно вставить в HTML документ. Просто выберите параметры и сгенерируйте HTML URL Input на лету!

{{<section plugin>}}

{{< app/html/generator name="url-input" >}}

<br>
<h2> Атрибуты </h2>

С элементом input `type='url'` вы можете использовать такие атрибуты, как *name*, *id*, *size*, *pattern*, *placeholder*, *list*, *maxlength*, *minlength* и т. д. 

- Атрибут `size` представляет собой числовое значение, указывающее, во сколько символов щириной должно быть в поле ввода.
- Атрибут `placeholder` представляет собой строку, которая дает пользователю краткую подсказку о том, какая информация ожидается в поле.
- Атрибут `pattern`, если он указан, является регулярным выражением, которому входное значение должно соответствовать, чтобы значение прошло проверку.
<br><br>

<h2> Создать HTML URL Input в C#</h2>

Aspose.HTML for .NET API работает как автономный браузер, который позволяет создавать или открывать существующие HTML-документы из различных источников для выполнения операций редактирования, таких как удаление, добавление и замена узлов HTML. Если вы хотите использовать функции редактирования HTML в своем продукте C# или программно добавить HTML URL Input, рассмотрите приведенный ниже пример кода C#:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги по созданию HTML URL Input на C#
---
1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/)
1. Установите значения для атрибутов [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/), [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) и [Size.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/size/)
1. Используйте метод [SetAttribute(),](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/) чтобы добавить `placeholder`, `pattern` или другие поддерживаемые атрибуты.
1. Скопируйте код для HTML URL Input и используйте его в своем проекте C#.

{{<section other-generators>}}
---
title: Другие поддерживаемые Генераторы HTML
subTitle: "С Генераторами HTML-кода вся тяжелая работа уже сделана за вас. Все, что вам нужно сделать, это скопировать и вставить!"
---