---
translation: true
title: HTML File Input 发电机 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: 生成 HTML File Input、预览结果并将生成的 HTML 和 C# 代码复制到您的网站。
url: /net/generators/file/
platformtag: net
generator: HTML File Input 发电机
element: HTML File Input
tag: file
---

{{<section banner>}}
---
h1: HTML File Input 发电机
h2: 为 HTML File Input生成 HTML 和 C# 代码，并在您自己的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 轻松生成文件输入！
---

带有 `type="file"` 的 [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) 元素允许用户从其设备的贮存。选择后，可以使用表单提交将文件上传到服务器，或使用 JavaScript 代码和 File API 进行操作。使用 HTML 语法轻松生成文件输入标签！

{{<section plugin>}}

{{< app/html/generator name="file" >}}

<br>
<h2> Attributes </h2>

HTML File Input 发电机通过选择 `name`、`accept` 和 `multiple` 等属性来帮助生成带有 `type='file'` 的输入标签的 HTML 代码。

 - `accept` 属性的值是一个字符串，包含一个或多个用逗号分隔的唯一文件类型说明符。这些可以是包含点的文件扩展名，例如 .jpg、.png、.pdf 或不带扩展名的 MIME 类型字符串，例如 audio/* - 接受任何音频文件。如果属性值留空，则接受所有文件类型。
 - 当设置了`multiple`布尔属性时，文件输入允许用户选择多个文件。
<br><br>

<h2> 在 C# 中创建 HTML File Input</h2>

Aspose.HTML for .NET API 支持一组在 HTML 标准中定义的 HTML 元素，以及关于如何嵌套元素的规则。您可以通过添加新元素、删除或编辑现有节点的内容来修改文档。如果您想在产品中使用 HTML 编辑功能或以编程方式添加 HTML File Input，请参阅下面的 C# 代码示例。您可以使用几行 C# 代码创建所需的元素：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML File Input的步骤
---
1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建[HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) 它创建由 tagName 指定的 HTML 元素。
1. 设置 [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/)、[Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) 和 [Accept](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/accept/) 属性。
1. 使用 [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/) 方法添加`multiple`属性。
1. 复制 HTML File Input的 C# 代码并在 C# 项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用这些 HTML 生成器，您已经完成了所有艰苦的工作。您所要做的就是复制和粘贴。清晰、安全、简单！"
---