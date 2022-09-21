---
translation: true
title: Генератор HTML Range Input — Онлайн инструмент и C# код
template: /templates/_template-generators-child.md
description: Создайте HTML Range Input для вашего сайта. Просмотрите Range Input, скопируйте и используйте сгенерированный код HTML и C# в своем проекте!
url: /net/generators/range/
platformtag: net
generator: Генератор HTML Range Input
element: HTML range input
tag: range
---

{{<section banner>}}
---
h1: Генератор HTML Range Input
h2: Создайте код HTML и C# для HTML Range Input и используйте его на своем собственном веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Создавайте HTML Range Input легко!
---

Элемент [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) с `type="range"` или ползунок диапазона позволяет указать числовое значение, которое должно быть не меньше или не больше заданного значения. Диапазон по умолчанию — от 0 до 100. Однако точное значение не считается важным. Обычно вы можете найти ползунок диапазона при манипулировании регуляторами громкости или яркости на вашем компьютере.

{{<section plugin>}}

{{< app/html/generator name="range" >}}

<br>
<h2> Атрибуты </h2>

HTML range input обычно содержит атрибуты `name`, `value`, `min`, `max` и `step`.

- Чтобы показать диапазон допустимых значений для ползунка, используйте атрибуты `min` и `max`.
- Атрибут `step` устанавливает допустимое количество интервалов в диапазоне. Значение по умолчанию — 1.
- Атрибут `value` содержит начальную точку диапазона. Это значение, на которое ползунок устанавливается по умолчанию после загрузки страницы. Значение по умолчанию в большинстве случаев находится посередине между минимальным и максимальным числом, но у вас всегда есть возможность изменить значение на любое другое.
<br><br>

<h2> Создание HTML Range Input на C#</h2>

Aspose.HTML for .NET API работает как автономный браузер, который позволяет создавать или открывать существующие HTML-документы из различных источников для выполнения операций редактирования, таких как удаление, добавление и замена узлов HTML. Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить HTML range input, рассмотрите приведенный ниже пример кода C#:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги для создания HTML Range Input на C#
---
1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) Он создает элемент HTML, указанный в tagName.
1. Установите значения для атрибутов [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/) и [Name.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) 
1. Используйте метод [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/), чтобы добавить `value`, `min`, `max`, `step` атрибуты и их значения.
1. Скопируйте код для HTML range input и используйте его в своем проекте C#.

{{<section other-generators>}}
---
title: Другие поддерживаемые Генераторы HTML
subTitle: "С Генераторами HTML вся тяжелая работа уже сделана за вас. Все, что вам нужно сделать, это скопировать и вставить. Ясно, безопасно и просто!"
---