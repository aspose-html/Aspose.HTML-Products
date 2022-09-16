---
translation: true
title: Генератор HTML File Input - онлайн инструмент и C# код
template: /templates/_template-generators-child.md
description: Создайте HTML File Input, просмотрите результат и скопируйте сгенерированный код HTML и C# на свой веб-сайт.
url: /net/generators/file/
platformtag: net
generator: Генератор HTML File Input
element: HTML file input
tag: file
---

{{<section banner>}}
---
h1: Генератор HTML File Input
h2: Создавайте код HTML и C# для HTML File Input и используйте его на своем веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Создавайте HTML File Input легко!
---

Элемент [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) с `type="file"` позволяет пользователю выбрать один или несколько файлов на своем устройстве. После выбора файлы можно загрузить на сервер с помощью отправки формы или манипулировать ими с помощью кода JavaScript и File API. Легко генерируйте тег HTML File Input с синтаксисом HTML!

{{<section plugin>}}

{{< app/html/generator name="file" >}}

<br>
<h2> Attributes </h2>

Генератор HTML File Input помогает генерировать HTML-код для входного тега с `type='file'`, выбирая такие атрибуты, как `name`, `accept` и `multiple`.

 - Значением атрибута `accept` является строка, содержащая один или несколько уникальных спецификаторов типа файла, разделенных запятыми. Это могут быть расширения файлов, включая точку, например .jpg, .png, .pdf, или строки типа MIME без расширений, например audio/* — принимаются любые аудиофайлы. Если значение атрибута оставить пустым, принимаются все типы файлов.
 - Когда установлен логический атрибут `multiple`, входной файл позволяет пользователю выбрать более одного файла.
<br><br>

<h2> Создать HTML File Input на C#</h2>

Aspose.HTML for .NET API поддерживает набор элементов HTML, определенных в стандарте HTML, а также правила вложения элементов. Вы можете изменить документ, добавив новые элементы, удалив или отредактировав содержимое существующих узлов. Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить HTML file input, рассмотрите приведенный ниже пример кода C#:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги для создания HTML File Input на C#
---
1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания [HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) Он создает элемент HTML, указанный в tagName.
1. Установите значения для [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/), [Name](https://reference.aspose.com/html/ net/aspose.html/htmlinputelement/name/) и [Accept](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/accept/) атрибутов.
1. Используйте метод [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/), чтобы добавить `multiple` атрибут.
1. Скопируйте код HTML File Input и используйте его в своем проекте C#.

{{<section other-generators>}}
---
title: Другие поддерживаемые Генераторы HTML
subTitle: "С Генераторами HTML вся тяжелая работа уже сделана за вас. Все, что вам нужно сделать, это скопировать и вставить код. Ясно, безопасно и просто!"
---