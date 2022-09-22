---
translation: true
title: HTML Password Input 发电机 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: 为您的网站创建 HTML 密码输入。 Р查看密码输入，复制并在您的项目中使用生成的 HTML 和 C# 代码！
url: /net/generators/password/
platformtag: net
generator: HTML Password Input 发电机
element: HTML Password Input
tag: password
---

{{<section banner>}}
---
h1: HTML Password Input 发电机
h2: 为 HTML 密码输入生成 HTML 和 C# 代码，并在您自己的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 轻松生成 HTML 密码输入！
---

带有 `type='password'` 的 [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) 元素允许用户安全地输入密码。该元素表示为单行文本编辑器控件，其中的文本被屏蔽以使其无法读取，通常通过将每个字符替换为诸如星号 (*) 或句点 (•) 之类的字符。密码掩码字符取决于浏览器。

{{<section plugin>}}

{{< app/html/generator name="password" >}}

<br>
<h2> Attributes </h2>

密码输入通常包含 `name`、`size`、`placeholder` 和 `minlenght` 属性。您可以使用 `minlength` 和 `maxlength` 属性设置密码的最小或最大长度。 `placeholder` 属性是一个字符串，它为用户提供有关字段中预期信息的简要提示。<br><br>

<h2> 在 C# 中创建 HTML 密码输入</h2>

Aspose.HTML for .NET API 用作无头浏览器，允许您从各种来源创建或打开现有 HTML 文档，以执行编辑操作，例如删除、附加和替换 HTML 节点。如果您想在产品中使用 HTML 编辑功能或以编程方式添加 HTML 密码输入，请参阅下面的 C# 示例。您可以使用几行 C# 代码创建密码输入：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML 密码输入的步骤
---

1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建[HTMLInputElement.](https://参考.aspose.com/html/net/aspose.html/htmlinputelement/)
1. 设置 [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/) 和 [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) 属性。
1. 使用 [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/) 方法添加 `size` 和 `placeholder` 属性及其值。
1. 复制 HTML 密码输入的 C# 代码并在您的 C# 项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用这些 HTML 代码生成器，您已经完成了所有艰苦的工作。您所要做的就是复制和粘贴！"
---