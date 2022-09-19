---
translation: true
title: HTML Color Input 发电机 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: 生成 HTML 颜色输入、预览结果并将生成的 HTML 和 C# 代码复制到您的网站。
url: /net/generators/color/
platformtag: net
generator: HTML Color Input 发电机
tag: color
element: HTML color input
---

{{<section banner>}}
---
h1: HTML Color Input 发电机
h2: 为 HTML 颜色输入生成 HTML 和 C# 代码，并在您自己的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 轻松生成 HTML 颜色输入！
---

带有 `type="color"` 的 [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) 元素定义了一个颜色选择器。它提供了一个用户界面元素，允许用户通过可视颜色选择器界面或通过在十六进制格式#RRGGBB 的文本字段中键入颜色来指定颜色。 HTML 颜色输入代码生成器有助于生成可插入 HTML 的 HTML 输入颜色代码。<br>
该控件由一个小按钮组成，其中显示当前颜色。单击颜色按钮以打开具有初始值的颜色选择器。所选颜色的预览显示在控件内。

{{<section plugin>}}

{{< app/html/generator name="color" >}}
<br>
<h2> Attributes </h2>

可以使用接受十六进制颜色值的 `value` 属性指定初始颜色。只允许使用没有 alpha 通道的简单颜色。 `value` 必须是七个字符的十六进制表示法。 `value` 永远不会为空。如果不指定值，则默认为#000000，即黑色。

您可以通过选择`name`和`value`等属性来生成 HTML 颜色输入标签和颜色选择器 C# 代码。 <br><br>

<h2> 在 C# 中创建 HTML 颜色输入</h2>

Aspose.HTML for .NET API 支持一组在 HTML 标准中定义的 HTML 元素，以及关于如何嵌套元素的规则。您可以通过添加新元素、删除或编辑现有节点的内容来修改文档。如果您想在产品中使用 HTML 编辑功能或以编程方式添加颜色选择器，请参阅下面的 C# 代码示例：
{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建颜色输入的步骤
---
1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建[HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) 它创建由 tagName 指定的 HTML 元素。
1. 设置 [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/) 和 [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) 属性。
1. 使用 [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/) 方法添加 `value` 属性及其十六进制格式的值。
1. 复制 HTML 颜色输入的 C# 代码并在您的 C# 项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用这些 HTML 生成器，您已经完成了所有艰苦的工作。您所要做的就是复制和粘贴。清晰、安全、简单！"
---