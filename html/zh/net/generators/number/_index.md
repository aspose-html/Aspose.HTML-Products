---
translation: true
title: HTML Number Input 发电机 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: 为您的网站创建 HTML 数字输入。 Р查看数字输入，复制并在您的项目中使用生成的 HTML 和 C# 代码！
url: /net/generators/number/
platformtag: net
generator: HTML Number Input 发电机
element: HTML Number Input
tag: number
---

{{<section banner>}}
---
h1: HTML Number Input 发电机
h2: 为 HTML 数字输入生成 HTML 和 C# 代码，并在您自己的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 即时生成 HTML 数字输入！
---

带有 `type="number"` 的 [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) 元素定义了一个用于输入数字的字段。它包括用于拒绝非数字条目的内置检查。您还可以对接受的号码设置限制。 HTML 数字输入生成器可帮助您生成可以粘贴到 HTML 中的 HTML 数字输入代码。只需选择选项并即时生成数字输入框！

{{<section plugin>}}

{{< app/html/generator name="number" >}}

<br>
<h2> Attributes </h2>

HTML 数字输入通常包含 `name`、`value`、`min`、`max` 和 `step` 属性。

- 使用 `min` 和 `max` 属性，您可以设置最小值和最大值。
- `step` 属性是一个表示粒度的数字。默认步长值为 1。
- `placeholder` 属性是一个字符串，它为用户提供有关字段中预期信息的简要提示。例如，“2 的倍数”。<br><br>

<h2> 在 C# 中创建数字输入</h2>

Aspose.HTML for .NET API 用作无头浏览器，允许您从各种来源创建或打开现有 HTML 文档，以执行编辑操作，例如删除、附加和替换 HTML 节点。如果您想在产品中使用 HTML 编辑功能或以编程方式添加数字输入，请参阅下面的 C# 代码示例：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML 数字输入的步骤
---

1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建[HTMLInputElement.](https://参考.aspose.com/html/net/aspose.html/htmlinputelement/)
1. 设置 [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/) 和 [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) 属性。
1. 使用[SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/)方法添加`value`, `min`, `max`, ` placeholder` 和 `step` 属性及其值。
1. 复制 HTML 数字输入的 C# 代码并在您的 C# 项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用这些 HTML 代码生成器，您已经完成了所有艰苦的工作。您所要做的就是复制和粘贴。清晰、安全、简单！"
---