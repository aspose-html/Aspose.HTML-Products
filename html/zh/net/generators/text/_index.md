---
translation: true
title: HTML Text Input 发电机 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: 为您的网站创建 HTML 文本输入。 Р查看文本框，复制并在您的项目中使用生成的 HTML 和 C# 代码！
url: /net/generators/text/
platformtag: net
generator: HTML Text Input 发电机
element: HTML Text Input
tag: text
---

{{<section banner>}}
---
h1: HTML Text Input 发电机
h2: 为 HTML 文本输入元素生成 HTML 和 C# 代码，并在您自己的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 轻松生成 HTML 文本输入！
---

带有 `type='text'` 的 HTML [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) 元素创建基本的单行文本输入。如果您希望用户输入单行值，请使用它们。如果您使用的是智能手机或平板电脑，则会出现一个屏幕键盘。您可以使用这个 HTML 文本输入生成器来创建可以粘贴到 HTML 中的代码。只需选择选项并即时获取文本输入！

<b>注意：</b> 文本框分为两种类型：文本字段和[textarea](/html/{{lang.url-fragment}}net/generators/textarea/) 这两种文本框服务于不同的目的并帮助用户了解他们应该在文本字段中输入的内容。 HTML `<textarea>` 标签定义了一个可以输入多行文本的区域。

{{<section plugin>}}

{{< app/html/generator name="text" >}}

<br>
<h2> Attributes </h2>

通过输入 `type='text'` 元素，您可以使用 *name*、*size*、*placeholder*、*list*、*required*、*spellcheck*、*maxlength*、*minlength* 等属性.

- `size` 属性是一个数值，表示输入字段中应包含多少个字符。文本字段的默认宽度为 20 个字符。
- `placeholder` 属性是一个字符串，它为用户提供有关字段中预期信息的简要提示。
- `spellcheck` 是一个属性，用于指示是否对元素启用拼写检查。
- 添加“必需”属性以确保用户填写此字段。
<br><br>

<h2> 在 C# 中创建 HTML 文本输入</h2>

Aspose.HTML for .NET API 用作无头浏览器，允许您从各种来源创建或打开现有 HTML 文档，以执行编辑操作，例如删除、附加和替换 HTML 节点。如果您想在产品中使用 HTML 编辑功能或以编程方式添加文本输入，请参阅下面的 C# 代码示例：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建文本输入的步骤
---

1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建[HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) 它创建由 tagName 指定的 HTML 元素。
1. 设置 [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/)、[Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) 和 [Size](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/size/) 属性。
1. 使用 [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/) 方法添加 `placeholder`、`spellcheck` 或其他支持的属性及其价值观。
1. 复制 HTML 文本输入的 C# 代码并在您的项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用这些 HTML 代码生成器，您已经完成了所有艰苦的工作。您所要做的就是复制和粘贴。清晰、安全、简单！"
---