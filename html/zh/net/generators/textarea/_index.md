---
translation: true
title: HTML Textarea 发电机 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: 为您的网站创建 HTML Textarea 元素。 Р查看文本区域，复制并在您的项目中使用生成的 HTML 和 C# 代码！
url: /net/generators/textarea/
platformtag: net
generator: HTML Textarea 发电机
element: HTML Textarea
tag: textarea
---

{{<section banner>}}
---
h1: HTML Textarea 发电机
h2: 为 HTML Textarea 元素生成 HTML 和 C# 代码，并在您自己的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 即时生成 HTML 文本区域！
---

[textarea](https://html.spec.whatwg.org/multipage/form-elements.html#the-textarea-element) HTML 元素定义了一个可以输入多行文本的区域。这是一个多行纯文本编辑元素，允许用户以任意形式输入大量文本，例如评论、评论或反馈表单。

<b>注意：</b> 文本框分为两种类型：文本字段和文本区域。这两个文本框有不同的用途，可以帮助用户了解他们应该在文本字段中输入的内容。文本区域由 `<textarea>` 标签定义。您可以使用带有 `type='text'` 的 HTML `<input>` 元素定义一个小的 [text](/html/{{lang.url-fragment}}net/generators/text/) 框。

{{<section plugin>}}

{{< app/html/generator name="textarea" >}}

<br>
<h2> Attributes </h2>

文本区域是一个大文本框，您可以在其中输入多行文本，例如描述、段落等。

- `name` 属性指定文本区域的名称。表单提交后需要引用表单数据。
- `placeholder` 属性是一个字符串，它为用户提供有关字段中预期信息的简要提示。
- `spellcheck` 是一个属性，用于指示是否对元素启用拼写检查。
- `minlength` 和 `maxlength` 属性定义了用户可以输入的最小和最大字符数。
<br><br>

<h2> 在 C# 中创建 HTML 文本区域</h2>

Aspose.HTML for .NET API 用作无头浏览器，允许您从各种来源创建或打开现有 HTML 文档，以执行编辑操作，例如删除、附加和替换 HTML 节点。如果您想在产品中使用 HTML 编辑功能或以编程方式添加 HTML `<textarea>` 元素，请参阅下面的 C# 示例。您可以使用几行代码创建一个文本区域：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML 文本区域的步骤
---

1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建[HTMLTextareaElement.](https://reference.aspose.com/html/net/aspose.html/htmltextareaelement/) 它创建由 tagName 指定的 HTML 元素。
1. 为 [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/)、[Cols](https://reference.aspose.com/html/net/aspose.html/htmltextareaelement/cols/) 和 [Rows](https://reference.aspose.com/html/net/aspose.html/htmltextareaelement/rows/) 属性。
1.使用[SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/)方法添加`placeholder`, `spellcheck`, `minlength`, ` maxlength` 或其他受支持的属性及其值。
1. 复制 HTML textarea 元素的 C# 代码并在您的项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用这些 HTML 生成器，您已经完成了所有艰苦的工作。您所要做的就是复制和粘贴。清晰、安全、简单！"
---