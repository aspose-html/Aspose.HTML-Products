---
translation: true
title: Генератор checkbox HTML - онлайн-инструмент и C# код 
template: /templates/_template-generators-child.md
description: Генератор checkbox создавет HTML checkbox для вашего веб-сайта. Вы можете просмотреть checkbox и скопировать сгенерированный код HTML и C#.
url: /net/generators/checkbox/
platformtag: net
generator: Генератор Checkbox HTML
element: checkbox
tag: checkbox
---

{{<section banner>}}
---
h1: Генератор Сheckbox HTML
h2: Создайте код HTML и C# для элемента checkbox HTML и используйте его на своем собственном веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Создавайте HTML Checkbox на лету!
---

Элемент [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) с `type="checkbox"` определяет checkbox. Checkbox — это поле ввода, представляющее двоичный выбор. Точный внешний вид checkbox зависит от конфигурации операционной системы, в которой работает браузер. Обычно он квадратный, но может иметь закругленные углы. Это элемент формы, который позволяет пользователям выбирать один или несколько параметров из заданных параметров.<br> Генератор checkbox HTML позволяет создавать элементы checkbox для вашего веб-сайта. Вы можете просмотреть checkbox и скопировать или загрузить сгенерированный HTML-код.

{{<section plugin>}}

{{< app/html/generator name="checkbox" >}}

<br>
<h2> Attributes </h2>

Checkbox обычно содержит атрибуты «name» и «value». Эта пара атрибутов будет отправлена ​​на сервер при отправке формы. Если атрибут `value` не указан, то сообщается значение по умолчанию "on".<br>
Вы можете сгенерировать HTML-тег ввода checkbox и код C# для него, выбрав такие атрибуты, как `name`, `checked`, `id` и т. д. Каждый checkbox связан с элементом `label`, обернутым вокруг checkbox. Пожалуйста, всегда добавляйте тег `<label>` для лучшей доступности!<br><br>

<h2> Создать checkbox HTML на C#</h2>

Aspose.HTML для .NET API поддерживает набор элементов HTML, определенных в стандарте HTML, а также правила вложения элементов. Вы можете изменить документ, добавив новые элементы, удалив или отредактировав содержимое существующих узлов. Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить checkbox, см. приведенный выше пример кода C#. Это можно сделать с помощью нескольких строк кода C#:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги по созданию Сheckbox HTML в C#
---
1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) Он создает элемент HTML, указанный в tagName.
1. Установите значения для [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/), [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/), [Id](https://reference.aspose.com/html/net/aspose.html/htmlelement/id/) и [Checked](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/checked/).
1. Создайте [HTMLLabelElement](https://reference.aspose.com/html/net/aspose.html/htmllabelelement/) и установите необходимые атрибуты.
1. Скопируйте код C# для checkbox и используйте его в своем проекте C#.

{{<section other-generators>}}
---
title: Другие поддерживаемые Генераторы HTML
subTitle: "С этими Генераторами HTML кода вся тяжелая работа уже сделана за вас. Все, что вам нужно сделать, это скопировать и вставить. Ясно, безопасно и просто!"
---