---
translation: true
title: Генератор Color Input HTML - онлайн-инструмент и C# код 
template: /templates/_template-generators-child.md
description: Создайте Color Input HTML, просмотрите результат и скопируйте сгенерированный код HTML и C# на свой веб-сайт.
url: /net/generators/color/
platformtag: net
generator: Генератор Color Input HTML
tag: color
element: сolor input HTML
---

{{<section banner>}}
---
h1: Генератор Color Input HTML
h2: Создайте код HTML и C# для color input HTML и используйте его на своем веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Создавайте Color Input HTML легко!
---

Элемент [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) с `type="color"` определяет палитру цветов. Он предоставляет элемент пользовательского интерфейса, который позволяет пользователю указать цвет либо с помощью интерфейса визуальной палитры цветов, либо путем ввода цвета в текстовое поле в шестнадцатеричном формате #RRGGBB. Генератор Color Input HTML помогает генерировать код color input, который можно вставить на веб страницу.<br>
Элемент управления состоит из небольшой кнопки, внутри которой отображается текущий цвет. Нажмите кнопку цвета, чтобы открыть палитру цветов с начальным значением. Предварительный просмотр выбранного цвета отображается внутри элемента управления.

{{<section plugin>}}

{{< app/html/generator name="color" >}}
<br>
<h2> Attributes </h2>

Начальный цвет можно указать с помощью атрибута `value`, который принимает шестнадцатеричные значения цвета. Разрешается использовать только простые цвета без альфа-канала. «value» должно быть представлено в семисимвольном шестнадцатеричном представлении. Значение никогда не бывает пустым. Если вы не укажете значение, по умолчанию используется #000000, что означает черный цвет.

Вы можете сгенерировать HTML-тег color input и код C# средства выбора цвета, выбрав такие атрибуты, как `name` и `value`. <br><br>

<h2> Создание Color Input HTML на C#</h2>

Aspose.HTML for .NET API поддерживает набор элементов HTML, определенных в стандарте HTML, а также правила вложения элементов. Вы можете изменить документ, добавив новые элементы, удалив или отредактировав содержимое существующих узлов. Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить color input, рассмотрите приведенный ниже пример кода C#. Добавить сolor input можно с помощью нескольких строк кода C#:
{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги по созданию Color Input на C#
---
1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) Он создает элемент HTML, указанный в tagName.
1. Установите значения для [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/) и [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) атрибутов.
1. Используйте метод [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/), чтобы добавить атрибут `value` и его значение в шестнадцатеричном формате.
1. Скопируйте код C# для ввода цвета HTML и используйте его в своем проекте C#.

{{<section other-generators>}}
---
title: Другие поддерживаемые Генераторы HTML
subTitle: "С Генераторами HTML вся тяжелая работа уже сделана за вас. Все, что вам нужно сделать, это скопировать и вставить код. Ясно, безопасно и просто!"
---