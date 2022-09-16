---
translation: true
title: HTML Email Input 发电机 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: 生成 HTML 电子邮件输入、预览结果并将生成的 HTML 和 C# 代码复制到您的网站。
url: /net/generators/email/
platformtag: net
generator: HTML Email Input 发电机
element: HTML 电子邮件输入
tag: email
---

{{<section banner>}}
---
h1: HTML Email Input 发电机
h2: 为 HTML 电子邮件输入生成 HTML 和 C# 代码，并在您自己的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: HTML Email Input 发电机
---

带有 `type='email'` 的 [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) 元素用于允许用户输入和编辑电子邮件地址或电子邮件地址列表。输入值会自动验证，以确保它是格式正确的电子邮件地址。

{{<section plugin>}}

{{< app/html/generator name="email" >}}

HTML Email Input 发电机通过选择 `name`、`placeholder`、`size`、`multiple`、`required` 和 `pattern` 等属性，帮助生成带有 `type='email'` 的输入标签的 HTML 代码。

- `placeholder` 属性是一个字符串，它为用户提供有关字段中预期信息的简要提示。
- `size` 属性是一个数值，表示输入字段中应包含多少个字符。默认值为 20。
- `multiple` 布尔属性指定用户可以输入多个用逗号分隔的电子邮件地址。
- `pattern` 属性是一个正则表达式，输入值必须匹配才能使值通过约束验证。如果指定的模式未指定或无效，则不应用正则表达式并完全忽略此属性。
<br>

<h2> 在 C# 中创建 HTML 电子邮件输入</h2>

Aspose.HTML for .NET API 支持一组在 HTML 标准中定义的 HTML 元素，以及关于如何嵌套元素的规则。您可以通过添加新元素、删除或编辑现有节点的内容来修改文档。如果您想在产品中使用 HTML 编辑功能或以编程方式添加 HTML 电子邮件输入，请参阅下面的 C# 代码示例。您可以使用几行 C# 代码创建所需的元素：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML 电子邮件输入的步骤
---
1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建[HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) 它创建由 tagName 指定的 HTML 元素。
1. 设置 [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/)、[Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) 和 [Size](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/size/) 属性。
1. 使用 [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/) 方法添加`multiple`、`required`和`pattern`属性.
1. 复制 HTML 电子邮件输入的 C# 代码并在您的 C# 项目中使用它。



{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用这些 HTML 生成器，您已经完成了所有艰苦的工作。清晰、安全、简单！"
---