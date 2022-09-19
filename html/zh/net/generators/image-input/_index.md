---
translation: true
title: HTML Image Input 发电机 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: 生成 HTML 图像按钮，预览结果并将生成的 HTML 和 C# 代码复制到您的网站。
url: /net/generators/image-input/
platformtag: net
generator: HTML Image Input 发电机
element: HTML Image Input
tag: image-input
---

{{<section banner>}}
---
h1: HTML Image Input 发电机
h2: 为 HTML 图像输入生成 HTML 和 C# 代码，并在您自己的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 生成 HTML 图像按钮
---

带有 `type='image'` 的 [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) 元素用于创建采用以下形式的图形提交按钮图像而不是文本。 HTML Image Input 发电机通过选择 `name`、`src`、`alt`、`width`、`height`和`autofocus`等属性来帮助为图像提交按钮生成 HTML 代码。使用 HTML 语法轻松生成图像按钮标签！

{{<section plugin>}}

{{< app/html/generator name="image-input" >}}

- `src` 属性指定要显示的图像文件的 URL，以表示图形提交按钮。
- `width` 和 `height` 属性指定以 CSS 像素为单位绘制图像的宽度和高度的数字。
- 如果图像无法显示，`alt` 属性提供了可用作按钮标签的替代文本。
- `autofocus` 布尔属性(如果存在)指定 `<input>` 元素应在页面加载时自动获得焦点。
<br>

<h2> 在 C# 中创建图像按钮</h2>

Aspose.HTML for .NET API 支持一组在 HTML 标准中定义的 HTML 元素，以及关于如何嵌套元素的规则。您可以通过添加新元素、删除或编辑现有节点的内容来修改文档。如果您想在产品中使用 HTML 编辑功能或以编程方式添加图像按钮，请参见下面的 C# 代码示例：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML 图像输入的步骤
---
1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建[HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) 它创建由 tagName 指定的 HTML 元素。
1. 设置 [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/)、[Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) 和 [Src](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/src/) 属性。
1. 使用 [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/) 方法添加`alt`、`width`、`height` 和`autofocus`属性。
1. 复制图像按钮的 C# 代码并在您的 C# 项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用这些 HTML 生成器，您已经完成了所有艰苦的工作。您所要做的就是复制和粘贴。清晰、安全、简单！"
---