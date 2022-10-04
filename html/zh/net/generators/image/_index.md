---
translation: true
title: HTML Image 发电机 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: HTML 图像生成器为 HTML 图像元素创建 HTML 和 C# 代码。您可以生成代码并在您自己的网站或 C# 项目中使用它。
url: /net/generators/image/
platformtag: net
generator: HTML Image 发电机
element: HTML image
tag: image
---

{{<section banner>}}
---
h1: HTML 图像生成器
h2: 为 HTML 图像元素生成 HTML 和 C# 代码，并在您的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 轻松生成 HTML <img> 标签！
---

`<img>` 标签用于在 HTML 页面中嵌入图像。使用 HTML 图像元素肯定会使您的网页更有趣。从技术上讲，图像并未插入网页，但图像链接到网页。 `<img>` 标签为引用的图像创建一个保存空间。

{{<section plugin>}} 

{{< app/html/generator name="image" >}}

<br>
<h2> Attributes </h2>

 - `src` 属性是必需的，包括图像到特定文档的路径。换句话说，它用于链接 HTML 文档中的图像。
 - `alt` 属性是可选的，但对可访问性非常有用。如果由于某种原因无法加载图像，它包含在页面上显示的图像的文本描述。
 - 建议始终指定图像的“宽度”和“高度”。如果未指定这些属性，则在加载图像时页面可能会闪烁。
<br><br>

<h2> 在 C# 中创建 HTML 图像元素</h2>

Aspose.HTML for .NET API 支持一组在 HTML 标准中定义的 HTML 元素，以及关于如何嵌套元素的规则。您可以通过添加新元素、删除或编辑现有节点的内容来修改文档。如果您想在产品中使用 HTML 编辑功能或以编程方式添加 `<img>` 元素，请参阅下面的 C# 代码示例：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML 图像元素的步骤
---

1. 使用 Document 类的 [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) 方法创建图像元素。在 HTML 文档中，Document.CreateElement() 方法创建由 tagName 指定的 HTML 元素，在我们的例子中 tagName 是“img”。
2. 为所需的 `src` 属性设置值。
3. 复制 HTML 图像元素的 C# 代码并在您的项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用 HTML 生成器构建高度可定制的 HTML 元素，无需编码！清晰、安全、简单！"
---