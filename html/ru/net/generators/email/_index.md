---
translation: true
title: Генератор HTML Email Input - онлайн инструмент и C# код 
template: /templates/_template-generators-child.md
description: Создайте HTML Email Input, просмотрите результат и скопируйте сгенерированный код HTML и C# на свой веб-сайт.
url: /net/generators/email/
platformtag: net
generator: Генератор HTML Email Input
element: HTML Email Input
tag: email
---

{{<section banner>}}
---
h1: Генератор HTML Email Input
h2: Создайте код HTML и C# для ввода электронной почты и используйте его на своем веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Генератор HTML ввода электронной почты
---

Элемент [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) с `type='email'` используется, чтобы позволить пользователю вводить и редактировать адрес электронной почты или список адресов электронной почты. Введенное значение автоматически проверяется, чтобы убедиться, что это правильно отформатированный адрес электронной почты.

{{<section plugin>}}

{{< app/html/generator name="email" >}}

Генератор HTML Email Input помогает генерировать HTML код для входного тега с `type='email'`, выбирая такие атрибуты, как `name`, `placeholder`, `size`, `multiple`, `required` и `pattern`.

- Атрибут `placeholder` представляет собой строку, которая дает пользователю краткую подсказку о том, какая информация ожидается в поле.
- Атрибут `size` представляет собой числовое значение, указывающее, сколько символов должно быть в поле ввода. Значение по умолчанию — 20.
- Логический атрибут `multiple` указывает, что пользователь может ввести несколько адресов электронной почты, разделенных запятыми.
- Атрибут `pattern` представляет собой регулярное выражение, которому входное значение должно соответствовать, чтобы значение прошло проверку. Если указанный шаблон не указан или недействителен, регулярное выражение не применяется и этот атрибут полностью игнорируется.
<br>

<h2> Создать HTML Email Input на C#</h2>

Aspose.HTML for .NET API поддерживает набор элементов HTML, определенных в стандарте HTML, а также правила вложения элементов. Вы можете изменить документ, добавив новые элементы, удалив или отредактировав содержимое существующих узлов. Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить ввод электронной почты в формате HTML, рассмотрите приведенный ниже пример кода C#:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги по созданию HTML Email Input на C#
---
1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) Он создает элемент HTML, указанный в tagName.
1. Установите значения для [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/), [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) и [Size](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/size/) атрибутов.
1. Используйте метод [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/), чтобы добавить атрибуты `multiple`, `required` и `pattern`.
1. Скопируйте код для HTML Email Input и используйте его в своем проекте C#.



{{<section other-generators>}}
---
title: Другие поддерживаемые Генераторы HTML
subTitle: "С этими Генераторами HTML вся тяжелая работа уже сделана за вас. Ясно, безопасно и просто!"
---