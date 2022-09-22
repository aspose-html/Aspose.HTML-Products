---
translation: true
title: Генератор HTML Radio Button - онлайн инструмент и C# код
template: /templates/_template-generators-child.md
description: Создавайте радиокнопки HTML для веб-сайта. Вы можете предварительно просмотреть их и скопировать сгенерированный код HTML и C#.
url: /net/generators/radio/
platformtag: net
generator: Генератор HTML Radio Button
element: HTML radio button
tag: radio
---

{{<section banner>}}
---
h1: Генератор HTML Radio Button
h2: Создайте код HTML и C# для радиокнопок HTML и используйте его на своем веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Генерируйте радиокнопку HTML на лету!
---

Элемент [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) с атрибутом `type='radio'` используется для создания переключателей HTML radio button. Их называют радиокнопками, потому что они выглядят и работают так же, как кнопки на старых радиоприемниках. Радиокнопки обычно используются для обозначения элемента группы. Одновременно может быть выбрана только одна радиокнопка в группе. Радиокнопки обычно отображаются в виде маленьких кружков, которые заполняются или выделяются при выборе.
Checkboxes аналогичны HTML radio button, но переключатели radio button предназначены для выбора одного значения из набора, а флажки checkbox позволяют включать и выключать отдельные значения.

{{<section plugin>}}

{{< app/html/generator name="radio" >}}

<br>
<h2> Атрибуты </h2>

Вы можете сгенерировать HTML тег для переключателя radio button и код C#, выбрав такие атрибуты, как `name`, `id`, `checked` и т. д.

- Атрибут `name` определяет группу переключателей, присваивая каждому переключателю в группе одно и то же имя.
- Атрибут `id` указывает уникальное значение, которое однозначно идентифицирует отдельный переключатель в группе.
- Логический атрибут `checked`, если он присутствует, указывает, что этот переключатель является выбранным по умолчанию в группе.
<br><br>

<h2> Создать переключатель HTML radio button на C#</h2>

Aspose.HTML for .NET API поддерживает набор элементов HTML, определенных в стандарте HTML, а также правила вложения элементов. Вы можете изменить документ, добавив новые элементы, удалив или отредактировав содержимое существующих узлов. Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить переключатель HTML radio button, рассмотрите приведенный выше пример кода C#:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги по созданию радиокнопки HTML на C#
---
1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/)
1. Установите значения для атрибутов [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/), [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/), [Id](https://reference.aspose.com/html/net/aspose.html/htmlelement/id/) и [Checked](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/checked/).
1. Создайте элемент [HTMLLabelElement](https://reference.aspose.com/html/net/aspose.html/htmllabelelement/) и установите необходимые атрибуты.
1. Скопируйте код для переключателя HTML и используйте его в своем проекте C#.

{{<section other-generators>}}
---
title: Другие поддерживаемые Генераторы HTML
subTitle: "С Генераторами HTML вся тяжелая работа уже сделана за вас. Все, что вам нужно сделать, это скопировать и вставить код. Ясно, безопасно и просто!"
---