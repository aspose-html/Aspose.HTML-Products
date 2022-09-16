---
translation: true
title: HTML Checkbox 发电机 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: Checkbox 发电机 允许您为您的网站创建 HTML Checkbox。您可以预览checkbox并复制生成的 HTML 和 C# 代码。
url: /net/generators/checkbox/
platformtag: net
generator: HTML Checkbox 发电机
element: HTML Checkbox
tag: checkbox
---

{{<section banner>}}
---
h1: HTML Checkbox发电机
h2: 为 HTML Checkbox元素生成 HTML 和 C# 代码，并在您自己的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 即时生成 HTML Checkbox！
---

带有 `type="checkbox"` 的 [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) 元素定义了一个checkbox。Checkbox是表示二元选择的输入字段。checkbox的确切外观取决于运行浏览器的操作系统配置。它通常是方形的，但可能有圆角。这是一个表单元素，允许用户从给定选项中选择一个或多个选项。<br> HTML Checkbox Generator 让您可以为您的网站创建checkbox元素。您可以预览checkbox并复制或下载生成的 HTML 代码。

{{<section plugin>}}

{{< app/html/generator name="checkbox" >}}

<br>
<h2> Attributes </h2>

checkbox通常包含一个 `name` 和 `value` 属性。提交表单时，此名称/值对将发送到服务器。如果未指定 `value` 属性，则报告的默认值为`on`。<br>
您可以通过选择 `name`、`checked`、`id` 等属性来生成 HTML checkbox输入标记和checkbox C# 代码。每个checkbox都与围绕该checkbox的标签元素相关联。请始终包含 `<label>` 标签以获得更好的可访问性！<br><br>

<h2> 在 C# 中创建 HTML checkbox</h2>

Aspose.HTML for .NET API 支持一组在 HTML 标准中定义的 HTML 元素，以及关于如何嵌套元素的规则。您可以通过添加新元素、删除或编辑现有节点的内容来修改文档。如果您想在产品中使用 HTML 编辑功能或以编程方式添加checkbox，请参阅下面的 C# 代码示例。您可以使用几行 C# 代码创建一个checkbox：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML checkbox的步骤
---
1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建[HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) 它创建由 tagName 指定的 HTML 元素。
1. 设置 [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/)、[Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/)、[Id](https://reference.aspose.com/html/net/aspose.html/htmlelement/id/) 和[Checked](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/checked/) 属性。
1. 创建 [HTMLLabelElement](https://reference.aspose.com/html/net/aspose.html/htmllabelelement/) 并设置所需属性。
1. 复制 HTML checkbox的 C# 代码并在您的 C# 项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用这些 HTML 生成器，您已经完成了所有艰苦的工作。您所要做的就是复制和粘贴。清晰、安全、简单！"
---