---
translation: true
title: Генератор HTML Search Input - Онлайн инструмент и C# код
template: /templates/_template-generators-child.md
description: Создайте HTML search input для вашего сайта. Просмотрите search input, скопируйте и используйте сгенерированный код HTML и C# в своем проекте!
url: /net/generators/search/
platformtag: net
generator: Генератор HTML Search Input
element: HTML search input
tag: search
---

{{<section banner>}}
---
h1: Генератор HTML Search Input
h2: Создайте код HTML и C# для элемента HTML Search Input и используйте его на своем собственном веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Создавайте HTML Search Input легко!
---

Элемент [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) с `type='search'` определяет текстовое поле, предназначенное для ввода пользователем поисковых запросов. Поисковые окна присутствуют на каждом веб-сайте. Они полезны для поиска конкретных данных. Генератор HTML Search Input поможет вам генерировать код, который можно вставить в HTML. Просто выберите параметры и создайте окно поиска на лету!

{{<section plugin>}}

{{< app/html/generator name="search" >}}

<br>
<h2> Атрибуты </h2>

- Атрибут `name` обязателен. Если для поля поиска не указано имя, ничего не будет отправлено.
- Атрибут `size` представляет собой числовое значение, указывающее, сколько символов может содержать поле ввода.
- `spellcheck` — это атрибут, который используется для указания, следует ли включать проверку орфографии для элемента.
- Атрибут `placeholder` – это строка, которая дает пользователю краткую подсказку о том, какая информация ожидается в поле.<br><br>

<h2> Создание HTML Search Input на C#</h2>

Aspose.HTML for .NET API поддерживает набор элементов HTML, определенных в стандарте HTML, а также правила вложения элементов. Вы можете изменить документ, добавив новые элементы, удалив или отредактировав содержимое существующих узлов. Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить тег HTML search input, рассмотрите приведенный ниже пример кода C#. Вы можете создать окно поиска с помощью нескольких строк:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги по созданию HTML Search Input на C#
---
1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) Он создает элемент HTML, указанный в tagName.
1. Установите значения для атрибутов [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/) и [Name.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/)
1. Используйте метод [SetAttribute(),](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/) чтобы добавить атрибуты `size`, `spellcheck` и `placeholder` с их значениями.
1. Скопируйте код HTML Search Input и используйте его в своем проекте C#.

{{<section other-generators>}}
---
title: Другие поддерживаемые Генераторы HTML
subTitle: "С Генераторами HTML кода вся тяжелая работа уже сделана за вас. Все, что вам нужно сделать, это скопировать и вставить. Ясно, безопасно и просто!"
---