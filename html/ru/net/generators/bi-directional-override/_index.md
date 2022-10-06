---
translation: true
title: Bi-Directional Override HTML Генератор — онлайн инструмент и C# код
template: /templates/_template-generators-child.md
description: Генератор HTML BDO создает код HTML и C# для HTML bdo тега. Генерируйте код и используйте его на своем веб-сайте или в проекте C#.
url: /net/generators/bdo/
platformtag: net
generator: HTML BDO Генератор
element: HTML bdo tag
tag: bdo
---

{{<section banner>}}
---
h1: Bi-Directional Override (BDO) HTML Генератор
h2: Создайте код HTML и C# для элемента HTML bdo и используйте его на своем веб-сайте или в проекте C#.
---

{{<section overview>}}
---
h2: Легко создавайте HTML <bdo> Тег!
---

HTML-элемент [bdo](https://html.spec.whatwg.org/multipage/text-level-semantics.html#the-bdo-element) переопределяет текущее направление текста, поэтому текст внутри отображается в другом направлении. BDO расшифровывается как Bi-Directional Override. HTML `<bdo>` тег определяет направление содержимого внутри него, которое будет отображаться в браузере слева направо или справа налево. Тег `<bdo>` полезен для языков с письмом справа налево, таких как арабский, персидский и иврит.

{{<section plugin>}}

{{< app/html/generator name="bi-directional-override" >}}

<br>
<h2> Attributes </h2>

Генератор HTML BDO помогает генерировать HTML-тег bdo, выбирая такие атрибуты, как `dir`, `spellcheck` и т. д. Атрибут `dir` является обязательным. Он определяет направление, в котором текст должен отображаться в содержимом этого элемента. Возможные значения: *rtl* и *ltr*.
<br><br>

<h2> Создать HTML BDO Тег на C#</h2>

Если вы хотите использовать функции редактирования HTML в своем продукте или программно добавить элемент HTML `<bdo>` в HTML документ, рассмотрите приведенный ниже пример C#. Вы можете создать нужный элемент с помощью всего нескольких строк кода:

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: Шаги по созданию HTML BDO элемента на C#
---

1. Используйте метод [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) класса Document для создания элемента `<bdo>`. В HTML-документе метод Document.CreateElement() создает HTML-элемент, указанный в tagName, в нашем случае tagName - "bdo".
2. Используйте метод [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/), чтобы добавить `dir` и другие необходимые атрибуты.
3. Создайте текстовое содержимое с помощью метода [CreateTextNode().](https://reference.aspose.com/html/net/aspose.html.dom/document/createtextnode/)
4. Используйте метод [AppendChild(),](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) чтобы добавить текстовое содержимое в элемент `<bdo>`.
5. Скопируйте код C# для элемента HTML `<bdo>` и используйте его в своем проекте C#.

{{<section other-generators>}}
---
title: Другие поддерживаемые генераторы HTML
subTitle: "Используйте HTML Генераторы для создания настраиваемых HTML-элементов без программирования! Ясно, безопасно и просто!"
---