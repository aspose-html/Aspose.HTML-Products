---
translation: true
title: HTML URL Input 发电机 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: 为您的网站创建 HTML URL 输入。 Р查看 URL 输入，复制并在您的项目中使用生成的 HTML 和 C# 代码！
url: /net/generators/url-input/
platformtag: net
generator: HTML URL Input 发电机
element: HTML URL Input
tag: url-input
---

{{<section banner>}}
---
h1: HTML URL Input 发电机
h2: 为 HTML URL 输入生成 HTML 和 C# 代码，并在您自己的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 轻松生成 HTML URL 输入！
---

带有 `type='url'` 的 [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) 定义了用于输入 URL 的字段。它只接受 null 或有效的 URL。在提交表单之前会自动验证此输入值。 HTML URL 输入生成器可帮助您生成可以粘贴到 HTML 中的代码。只需选择选项并即时生成 URL 输入！

{{<section plugin>}}

{{< app/html/generator name="url-input" >}}

<br>
<h2> Attributes </h2>

通过输入 `type='url'` 元素，您可以使用 *name*、*id*、*size*、*pattern*、*placeholder*、*list*、*maxlength*、*minlength* 等属性.

- `size` 属性是一个数值，表示输入字段中可以包含多少个字符。
- `placeholder` 属性是一个字符串，它为用户提供有关字段中预期信息的简要提示。
- `pattern` 属性(如果指定)是一个正则表达式，输入值必须匹配才能使值通过验证。
<br><br>

<h2> 在 C# 中创建 URL 输入</h2>

Aspose.HTML for .NET API 用作无头浏览器，允许您从各种来源创建或打开现有 HTML 文档，以执行编辑操作，例如删除、附加和替换 HTML 节点。如果您想在您的 C# 产品中使用 HTML 编辑功能或以编程方式添加 HTML URL 输入，请参阅下面的 C# 代码示例：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 URL 输入的步骤
---

1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建[HTMLInputElement.](https://参考.aspose.com/html/net/aspose.html/htmlinputelement/)
1. 设置 [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/)、[Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) 和 [Size](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/size/) 属性。
1. 使用 [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/) 方法添加 `placeholder`、`pattern` 或其他支持的属性他们的价值观。
1. 复制 HTML URL 输入的代码并在您的 C# 项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用 HTML 代码生成器，所有繁重的工作都已为您完成。您所要做的就是复制和粘贴！"
---