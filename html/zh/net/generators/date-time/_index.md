---
translation: true
title: HTML Date & Time Input 发电机 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: 生成 HTML 日期和时间输入、预览结果并将生成的 HTML 和 C# 代码复制到您的网站。
url: /net/generators/date-time/
platformtag: net
generator: HTML Date & Time Input 发电机
element: HTML Date & Time Input
tag: date-time
---

{{<section banner>}}
---
h1: HTML Date & Time Input 发电机
h2: 为 HTML 日期和时间输入生成 HTML 和 C# 代码，并在您自己的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 即时生成日期和时间输入！
---

带有 `type='date'` 或 `type='time'` 的 [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) 元素创建输入字段允许用户输入日期或时间，可以使用验证输入的文本框或特殊的日期和时间选择器界面。日期和时间选择器被广泛用于帮助用户快速轻松地选择所需的日期或时间。

{{<section plugin>}}

{{< app/html/generator name="dateTime" >}}

<br>
<h2> Attributes </h2>

如果您选择输入类型 `type='date'`，您将创建一个允许用户输入日期的输入字段。结果值包括年、月和日。
`type='month'` 输入类型创建一个输入字段，允许用户输入月份和年份。输入 `type='week'` 创建一个输入字段，允许用户快速选择一年加上该年的周数，可以是从第 1 周到第 52 周或第 53 周。输入 `type='time'` 是用于创建允许用户快速输入时间的输入字段 - 小时和分钟，有时是秒。

HTML Date & Time Input 发电机有助于生成可以插入 HTML 的 HTML 日期和时间输入代码。选择选项并创建日期和时间选择器！<br><br>

<h2> 在 C# 中创建 HTML 日期和时间输入</h2>

Aspose.HTML for .NET API 支持一组在 HTML 标准中定义的 HTML 元素，以及关于如何嵌套元素的规则。您可以通过添加新元素、删除或编辑现有节点的内容来修改文档。如果您想在产品中使用 HTML 编辑功能或以编程方式添加 HTML 日期和时间输入，请参阅下面的 C# 代码示例。您可以使用几行 C# 代码创建所需的元素：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML 日期和时间输入的步骤
---
1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建[HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) 它创建由 tagName 指定的 HTML 元素。
1. 设置 [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/) 和 [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) 属性。
1. 使用[SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/)方法添加`value`属性及其值来指定日期、时间、周或月。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用这些 HTML 生成器，您已经完成了所有艰苦的工作。您所要做的就是复制和粘贴。清晰、安全、简单！"
---