---
translation: true
title: Генератор Date & Time Input - онлайн инструмент и C# код 
template: /templates/_template-generators-child.md
description: Создайте ввод даты и времени в формате HTML, просмотрите результат и скопируйте сгенерированный код HTML и C# на свой веб-сайт.
url: /net/generators/date-time/
platformtag: net
generator: Генератор Date & Time Input HTML
element: Date & Time Input HTML
tag: date-time
---

{{<section banner>}}
---
h1: Генератор Date & Time Input HTML
h2: Создайте код HTML и C# для ввода даты и времени в формате HTML и используйте его на своем веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Создавайте ввод даты и времени на лету!
---

Элементы [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) с `type='date'` или `type='time'` создают поля ввода которые позволяют пользователю вводить дату или время либо с помощью текстового поля, проверяющего ввод, либо с помощью специального интерфейса выбора даты и времени. Средства выбора даты и времени широко используются, чтобы помочь пользователям быстро и легко выбрать нужную дату или время.

{{<section plugin>}}

{{< app/html/generator name="dateTime" >}}

<br>
<h2> Attributes </h2>

Если вы выбираете тип ввода `type='date'`, вы создаете поле ввода, которое позволяет пользователям вводить дату. Полученное значение включает год, месяц и день.
Тип ввода `type='month'` создает поле ввода, которое позволяет пользователям вводить месяц и год. Ввод `type='week'` создает поле ввода, которое позволяет пользователям быстро выбрать год и номер недели для этого года, который может быть от недели 1 до 52 или 53. Ввод `type='time'` используется для создания поля ввода, которое позволяет пользователям быстро вводить время - часы и минуты, иногда секунды.

Генератор Date & Time Input HTML помогает генерировать код ввода даты и времени HTML, который можно вставить в HTML. Выберите параметры и создайте средство выбора даты и времени!<br><br>

<h2> Как создать Date & Time Input HTML на C#</h2>

Aspose.HTML for .NET API поддерживает набор элементов HTML, определенных в стандарте HTML, а также правила вложения элементов. Вы можете изменить документ, добавив новые элементы, удалив или отредактировав содержимое существующих узлов. Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить ввод даты и времени в формате HTML, рассмотрите приведенный ниже пример кода C#:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги по созданию Date & Time Input HTML на C#
---
1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) Он создает элемент HTML, указанный в tagName.
1. Установите значения для [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/) и [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) атрибутов.
1. Используйте метод [SetAttribute(),](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/) чтобы добавить атрибут `value` и его значение для указания даты и времени, недели или месяца.

{{<section other-generators>}}
---
title: Другие поддерживаемые Генераторы HTML
subTitle: "С Генераторами HTML вся тяжелая работа уже сделана за вас. Все, что вам нужно сделать, это скопировать и вставить код. Ясно, безопасно и просто!"
---