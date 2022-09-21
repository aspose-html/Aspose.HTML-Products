---
translation: true
title: HTML Range Input 发电机 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: 为您的网站创建 HTML 范围输入。 Р查看范围输入，复制并在您的项目中使用生成的 HTML 和 C# 代码！
url: /net/generators/range/
platformtag: net
generator: HTML Range Input 发电机
element: HTML Range Input
tag: range
---

{{<section banner>}}
---
h1: HTML Range Input 发电机
h2: 为 HTML 范围输入生成 HTML 和 C# 代码，并在您自己的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 轻松生成 HTML 范围输入！
---

带有 `type='range'` 或范围滑块的 [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) 元素允许您指定一个数值，该数值必须不小于或不大于给定值。默认范围是 0 到 100。但是，确切的值并不重要。在计算机上操作音量或亮度控件时，您通常可以找到范围滑块。

{{<section plugin>}}

{{< app/html/generator name="range" >}}

<br>
<h2> Attributes </h2>

范围输入通常包含 `name`、`value`、`min`、`max` 和 `step` 属性。

- 要显示范围，请使用范围输入类型的 `min` 和 `max` 属性。
- `step` 属性是范围内允许的间隔数。默认值为 1。
- `value` 属性包含范围的起点。这是页面加载后滑块默认设置的值。在大多数情况下，默认值介于最小值和最大值之间，但您始终可以选择将值更改为您想要的任何值。
<br><br>

<h2> 在 C# 中创建 HTML 范围输入</h2>

Aspose.HTML for .NET API 用作无头浏览器，允许您从各种来源创建或打开现有 HTML 文档，以执行编辑操作，例如删除、附加和替换 HTML 节点。如果您想在产品中使用 HTML 编辑功能或以编程方式添加范围输入，请参阅下面的 C# 代码示例：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML 范围输入的步骤
---

1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建[HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) 它创建由 tagName 指定的 HTML 元素。
1. 设置 [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/) 和 [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) 属性。
1. 使用 [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/) 方法添加`value`、`min`、`max`和`step` 属性及其值。
1. 复制 HTML 范围输入的代码并在您的 C# 项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用这些 HTML 生成器，您已经完成了所有艰苦的工作。您所要做的就是复制和粘贴。清晰、安全、简单！"
---