---
translation: true
title: HTML Radio Button 发电机 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: 为您的网站生成 HTML Radio Button。您可以预览单选按钮并复制生成的 HTML 和 C# 代码。
url: /net/generators/radio/
platformtag: net
generator: HTML Radio Button 发电机
element: HTML Radio Button
tag: radio
---

{{<section banner>}}
---
h1: HTML Radio Button 发电机
h2: 为 HTML HTML Radio Button生成 HTML 和 C# 代码，并在您自己的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 即时生成 HTML Radio Button！
---

[input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) 类型 `radio` 用于创建单选按钮。它们被称为单选按钮，因为它们的外观和工作方式与旧收音机上的按钮相同。单选按钮通常用于指示组项目。一次只能选择组中的一个单选按钮。单选按钮通常显示为小圆圈，在选中时会填充或突出显示。
复选框类似于单选按钮，但单选按钮旨在从一组中选择单个值，而复选框允许您打开和关闭单个值。

{{<section plugin>}}

{{< app/html/generator name="radio" >}}

<br>
<h2> Attributes </h2>

您可以通过选择 `name`、`id`、`checked` 等属性来生成 HTML Radio Button输入标记和 C# 代码。

- `name` 属性通过为组中的每个单选按钮提供相同的名称来定义单选按钮组。
- `id` 属性指定一个唯一值，用于唯一标识组中的单个单选按钮。
- `checked` 布尔属性，如果存在，则表明此单选按钮是组中默认选中的单选按钮。
<br><br>

<h2> 在 C# 中创建单选按钮</h2>

Aspose.HTML for .NET API 支持一组在 HTML 标准中定义的 HTML 元素，以及关于如何嵌套元素的规则。您可以通过添加新元素、删除或编辑现有节点的内容来修改文档。如果您想在产品中使用 HTML 编辑功能或以编程方式添加单选按钮，请参阅下面的 C# 代码示例。您可以使用几行 C# 代码创建所需的元素：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML Radio Button的步骤
---
1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建[HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) 它创建由 tagName 指定的 HTML 元素。
1. 设置 [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/)、[Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/)、[Id](https://reference.aspose.com/html/net/aspose.html/htmlelement/id/) 和[Checked](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/checked/) 属性。
1. 创建 [HTMLLabelElement](https://reference.aspose.com/html/net/aspose.html/htmllabelelement/) 并设置所需属性。
1. 复制 HTML Radio Button的 C# 代码并在您的 C# 项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用这些 HTML 生成器，您已经完成了所有艰苦的工作。您所要做的就是复制和粘贴。清晰、安全、简单！"
---