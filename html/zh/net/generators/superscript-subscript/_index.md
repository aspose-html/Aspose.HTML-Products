---
translation: true
title: Superscript & Subscript HTML 生成器 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: 生成 HTML 上标和下标标记，预览结果并将生成的 HTML 和 C# 代码复制到您的网站。
url: /net/generators/superscript-subscript/
platformtag: net
family: html
generator: Superscript & Subscript HTML Generator
element: Superscript or Subscript HTML tag
tag: superscript-subscript
---

{{<section banner>}}
---
h1: Superscript & Subscript HTML 生成器
h2: 为 HTML `<sup>` 或 `<sub>` 标签生成 HTML 和 C# 代码，并在您的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: Superscript & Subscript HTML 生成器
---

`<sup>` HTML 标签用于向 HTML 文档添加上标文本。上标通常使用较小的文本以凸起的基线呈现。上标文本出现在法线上方半个字符，通常用于脚注。

`<sub>` HTML 标签定义了内联文本，出于纯粹的印刷原因，应该将其呈现为下标。下标通常以较低的基线显示，使用较小的文本。下标文本出现在法线下方半个字符，可用于化学式。

{{<section plugin>}}

{{< app/html/generator name="superscript-subscript" >}}

<br>
<h2> Create HTML Superscript & Subscript Tags in C#</h2>

[Aspose.HTML for .NET](/html/{{lang.url-fragment}}net/) API 支持一组在 HTML 标准中定义的 HTML 元素，以及有关如何嵌套元素的规则。您可以通过添加新元素、删除或编辑现有节点的内容来修改文档。如果您想在您的产品中使用 HTML 编辑功能或以编程方式添加 HTML 上标和下标标签，请参阅下面的 C# 示例。您可以使用几行代码创建所需的元素：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML 上标标记的步骤
---

1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建一个`<sup>`元素。在 HTML 文档中，Document.CreateElement() 方法创建由 tagName 指定的 HTML 元素，在我们的例子中 tagName 是“sup”。
2. 使用 [CreateTextNode()](https://reference.aspose.com/html/net/aspose.html.dom/document/createtextnode/) 方法创建文本内容。
3. 使用 [AppendChild()](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) 方法将文本内容添加到`<sup>`元素中。
4. 复制 HTML 上标标记的 C# 代码并在您的项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用 HTML 生成器构建高度可定制的 HTML 元素，无需编码！清晰、安全、简单！"
---