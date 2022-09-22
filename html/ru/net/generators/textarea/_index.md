---
translation: true
title: HTML Textarea Generator - Онлайн инструмент и C# код
template: /templates/_template-generators-child.md
description: Создайте элемент HTML Textarea для своего сайта. Просмотрите текстовое поле, скопируйте и используйте код HTML и C# в своем проекте!
url: /net/generators/textarea/
platformtag: net
generator: Генератор HTML Textarea
element: HTML Textarea
tag: textarea
---

{{<section banner>}}
---
h1: Генератор HTML Textarea
h2: Создайте код HTML и C# для элемента HTML Textarea и используйте его на своем веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Создавайте HTML Textarea на лету!
---

HTML-элемент [textarea](https://html.spec.whatwg.org/multipage/form-elements.html#the-textarea-element) определяет область, в которую можно ввести несколько строк текста. Это многострочный элемент редактирования простого текста, который позволяет пользователям вводить большие объемы текста в произвольной форме, например, обзоры, комментарии или формы обратной связи.

<b>Примечание.</b> Текстовые поля делятся на два типа: text и text area. Эти два текстовых поля служат разным целям и помогают пользователям понять, что они должны вводить в текстовое поле. Текстовая область определяется тегом `<textarea>`. Вы можете определить небольшое поле [text,](/html/{{lang.url-fragment}}net/generators/text/) используя HTML-элементы `<input>` с `type='text'`.

{{<section plugin>}}

{{< app/html/generator name="textarea" >}}

<br>
<h2> Атрибуты </h2>

- Атрибут `name` указывает имя для текстовой области. Это необходимо для ссылки на данные формы после отправки.
- Атрибут `placeholder` — это строка, которая дает пользователю краткую подсказку о том, какая информация ожидается в поле.
- `spellcheck` – это атрибут, который используется для указания, следует ли включать проверку орфографии для элемента.
- Атрибуты `minlength` и `maxlength` определяют минимальное и максимальное количество символов, которое может ввести пользователь.
<br><br>

<h2> Создание HTML Textarea на C#</h2>

Aspose.HTML for .NET API работает как автономный браузер, который позволяет создавать или открывать существующие HTML-документы из различных источников для выполнения операций редактирования, таких как удаление, добавление и замена узлов HTML. Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить элемент HTML `<textarea>`, рассмотрите приведенный ниже пример C#. Вы можете создать текстовую область с помощью нескольких строк кода:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги по созданию HTML Textarea на C#
---
1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания [HTMLTextareaElement.](https://reference.aspose.com/html/net/aspose.html/htmltextareaelement/) 
1. Установите значения для атрибутов [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/), [Cols](https://reference.aspose.com/html/net/aspose.html/htmltextareaelement/cols/) и [Rows](https://reference.aspose.com/html/net/aspose.html/htmltextareaelement/rows/).
1. Используйте метод [SetAttribute(),](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/) чтобы добавить `placeholder`, `spellcheck`, `minlength`, ` maxlength` или другие поддерживаемые атрибуты с их значениями.
1. Скопируйте код C# для элемента textarea HTML и используйте его в своем проекте.

{{<section other-generators>}}
---
title: Другие поддерживаемые Генераторы HTML
subTitle: "С Генераторами HTML вся тяжелая работа уже сделана за вас. Все, что вам нужно сделать, это скопировать и вставить код. Ясно, безопасно и просто!"
---