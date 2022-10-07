---
translation: true
title: HTML <code> 标签生成器 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: Code HTML Generator 创建一个 HTML 代码标签。预览、复制生成的 HTML 和 C# 代码并在您的网站或 C# 项目中使用它！
url: /net/generators/code/
platformtag: net
family: html
generator: HTML code Tag Generator
element: HTML code tag
tag: code
---

{{<section banner>}}
---
h1: HTML 代码标签生成器
h2: 为 HTML `<code>` 元素生成 HTML 和 C# 代码，并在您的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 轻松生成 HTML <code> 标签！
---

`<code>` HTML 元素用于定义一段计算机代码。默认情况下，内容文本使用浏览器的默认等宽字体显示。此元素只能包含全局属性。

{{<section plugin>}}

{{< app/html/generator name="code" >}}

<br><br>
<h2> 在 C# 中创建 HTML 代码标签</h2>

[Aspose.HTML for .NET](/html/{{lang.url-fragment}}net/) API 支持一组在 HTML 标准中定义的 HTML 元素，以及有关如何嵌套元素的规则。您可以通过添加新元素、删除或编辑现有节点的内容来修改文档。如果您想在产品中使用 HTML 编辑功能或以编程方式添加 HTML 代码标记，请参阅下面的 C# 示例。您可以使用几行代码创建所需的元素：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML 代码标记的步骤
---

1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建一个`<code>`元素。在 HTML 文档中，Document.CreateElement() 方法创建由 tagName 指定的 HTML 元素，在我们的例子中 tagName 是“代码”。
2. 使用 [CreateTextNode()](https://reference.aspose.com/html/net/aspose.html.dom/document/createtextnode/) 方法创建文本内容。
3. 使用 [AppendChild()](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) 方法将文本内容添加到`<code>`元素中。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用 HTML 生成器构建高度可定制的 HTML 元素，无需编码！清晰、安全、简单！"
---