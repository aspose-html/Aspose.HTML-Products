---
translation: true
title: Генератор HTML Text Input - Онлайн инструмент и C# код
template: /templates/_template-generators-child.md
description: Создайте HTML Text Input для вашего сайта. Просмотрите текстовое поле, скопируйте и используйте сгенерированный код HTML и C# в своем проекте!
url: /net/generators/text/
platformtag: net
generator: Генератор HTML Text Input
element: HTML Text Input
tag: text
---

{{<section banner>}}
---
h1: Генератор HTML Text Input
h2: Создайте код HTML и C# для элемента HTML Text Input и используйте его на своем веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Создавайте HTML Text Input легко!
---

Элементы HTML [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) с `type='text'` создают базовые однострочные вводы текста. Экранная клавиатура появится, если вы используете смартфон или планшет. Вы можете использовать Генератор HTML Text Input для создания кода, который можно вставить в HTML документ. Просто выберите параметры и получите ввод текста на лету!

<b>Примечание.</b> Текстовые поля подразделяются на два типа: text и [textarea.](/html/{{lang.url-fragment}}net/generators/textarea/) Эти текстовые элементы служат различным целям и призваны помочь пользователям понять, что они должны вводить в текстовое поле. Тег HTML `<textarea>` определяет область, в которую вы можете ввести несколько строк текста.

{{<section plugin>}}

{{< app/html/generator name="text" >}}

<br>
<h2> Атрибуты </h2>

С элементом input `type='text'` вы можете использовать такие атрибуты, как *name*, *size*, *placeholder*, *list*, *required*, *spellcheck*, *maxlength*, *minlength* и т. д. 

- Атрибут `size` представляет собой числовое значение, указывающее, во сколько символов шириной должно быть в поле ввода. Ширина текстового поля по умолчанию составляет 20 символов.
- Атрибут `placeholder` представляет собой строку, которая дает пользователю краткую подсказку о том, какая информация ожидается в поле.
- `spellcheck` — это атрибут, который используется для указания, следует ли включать проверку орфографии для элемента.
- Добавьте `required` атрибут, чтобы пользователи заполнили это поле.
<br><br>

<h2> Создание HTML Text Input на C#</h2>

Aspose.HTML for .NET API работает как автономный браузер, который позволяет создавать или открывать существующие HTML-документы из различных источников для выполнения операций редактирования, таких как удаление, добавление и замена узлов HTML. Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить HTML Text Input, рассмотрите приведенный ниже пример кода C#:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги по созданию HTML Text Input на C#
---
1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) Он создает элемент HTML, указанный в tagName.
1. Установите значения для [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/), [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) и [Size](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/size/) атрибутов.
1. Используйте метод [SetAttribute(),](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/) чтобы добавить `placeholder`, `spellcheck` или другие поддерживаемые атрибуты.
1. Скопируйте код C# для ввода текста HTML и используйте его в своем проекте.

{{<section other-generators>}}
---
title: Другие поддерживаемые Генераторы HTML
subTitle: "С помощью Генераторов HTML-кода вся тяжелая работа уже сделана за вас. Все, что вам нужно сделать, это скопировать и вставить. Ясно, безопасно и просто!"
---