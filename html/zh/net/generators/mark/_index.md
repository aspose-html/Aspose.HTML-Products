---
translation: true
title: HTML mark 标签（高亮）生成器 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: 生成 HTML 标记标签(突出显示)，预览结果并将生成的 HTML 和 C# 代码复制到您的网站。
url: /net/generators/mark/
platformtag: net
family: html
generator: HTML Mark Tag Generator
element: HTML mark tag
tag: mark
---

{{<section banner>}}
---
h1: HTML mark 标签（高亮）生成器
h2: 为 HTML Highlight 生成 HTML 和 C# 代码，并在您的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 即时生成 HTML <mark> 标签！
---

`<mark>` HTML 元素定义了应该被标记或突出显示的文本。 `<mark>` 标记表示您发现感兴趣的文档内容的一部分，例如，表示与搜索操作匹配的单词。

{{<section plugin>}}

{{< app/html/generator name="mark" >}}

<br>
<h2> 在 C# 中创建 HTML mark 标签</h2>

[Aspose.HTML for .NET](/html/{{lang.url-fragment}}net/) API 支持一组在 HTML 标准中定义的 HTML 元素，以及有关如何嵌套元素的规则。您可以通过添加新元素、删除或编辑现有节点的内容来修改文档。如果您想在产品中使用 HTML 编辑功能或以编程方式添加 HTML 标记标签，请参见下面的 C# 示例：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML 突出显示的步骤
---

1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建一个`<mark>`元素。在 HTML 文档中，Document.CreateElement() 方法创建由 tagName 指定的 HTML 元素，在我们的例子中 tagName 是“mark”。
2. 使用 [CreateTextNode()](https://reference.aspose.com/html/net/aspose.html.dom/document/createtextnode/) 方法创建文本内容。
3. 使用 [AppendChild()](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) 方法将文本内容添加到`<mark>`元素中。
4. 复制 `<mark>` 标记的 C# 代码并在您的 C# 项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用 HTML 生成器构建高度可定制的 HTML 元素，无需编码！清晰、安全、简单！"
---