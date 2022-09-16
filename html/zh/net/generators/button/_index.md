---
translation: true
title: HTML Button 发电机 - 在线插件和 C# 代码
template: /templates/_template-generators-child.md
description: HTML Button 发电机为此元素创建 HTML 按钮和 C# 代码。您可以生成代码并在您自己的网站或 C# 项目中使用它。
url: /net/generators/button/
platformtag: net
generator: HTML Button 发电机
element: HTML Button
tag: button
---

{{<section banner>}}
---
h1: HTML Button 发电机
h2: 为 HTML Button元素生成 HTML 和 C# 代码，并在您自己的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 即时生成 HTML Button！
---

`<button>` [HTML](https://html.spec.whatwg.org/multipage/form-elements.html#the-button-element) 元素是定义可点击按钮的交互式元素。您可以使用鼠标、键盘、语音命令或其他辅助技术激活 HTML 按钮。 `<button>` 是一种表单元素，用于提交、重置 [form](https://html.spec.whatwg.org/multipage/forms.html#the-form-element) 或打开一个对话框。一旦被激活，它就会执行一个可编程的动作。

{{<section plugin>}}

{{< app/html/generator name="button" >}}

<br>
<h2> Attributes </h2>

`<button>` 元素的属性包括：*name*、*type*、*value*、*autofocus*、*form*、*disabled*、*formaction* 等。但所有这些属性都是可选的。但是，您应该始终为 `<button>` 元素指定 *type* 属性，以告诉浏览器它是什么类型的按钮，因为不同的浏览器对按钮元素使用不同的默认 *type*。
在 `<button>` 标记内，您可以将文本和图标添加到您的按钮，使其独一无二。
<br><br>

<h2> 在 C# 中创建 HTML Button</h2>

Aspose.HTML for .NET API 支持一组在 HTML 标准中定义的 HTML 元素，以及关于如何嵌套元素的规则。您可以通过添加新元素、删除或编辑现有节点的内容来修改文档。如果您想在产品中使用 HTML 编辑功能或以编程方式添加 `<button>` 元素，请参阅下面的 C# 代码示例。您可以使用几行 C# 代码创建一个按钮：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML Button的步骤
---
1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建[HTMLButtonElement.](https://reference.aspose.com/html/net/aspose.html/htmlbuttonelement/) 它创建由 tagName 指定的 HTML 元素，如果无法识别 tagName，则创建 HTMLUnknownElement。
2. 设置 [Type](https://reference.aspose.com/html/net/aspose.html/htmlbuttonelement/type/)、[Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/)、[TextContent](https://reference.aspose.com/html/net/aspose.html.dom/element/textcontent/) 和[禁用](https://reference.aspose.com/html/net/aspose.html/htmlbuttonelement/disabled/) 属性。
3. 复制 HTML Button的 C# 代码并在您的 C# 项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用这些 HTML 生成器，您已经完成了所有艰苦的工作。您所要做的就是复制和粘贴。清晰、安全、简单！"
---