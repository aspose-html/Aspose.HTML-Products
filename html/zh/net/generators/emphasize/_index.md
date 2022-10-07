---
translation: true
title: 强调文本 HTML 生成器 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: 强调文本 HTML 生成器创建一个 HTML em 标签。预览、复制生成的 HTML 和 C# 代码并在您的网站或 C# 项目中使用它！
url: /net/generators/emphasize/
platformtag: net
family: html
generator: Emphasize Text HTML Generator
element: HTML em tag
tag: emphasize
---

{{<section banner>}}
---
h1: 强调文本 HTML 生成器
h2: 为 HTML 强调文本元素生成 HTML 和 C# 代码，并在您的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 即时生成强调文本 HTML 标记！
---

`<em>` 标签用于定义强调的文本。换句话说，它是用于与周围文本相比强调强调的短语。这个词组通常仅限于一个词或几个词，并影响句子的含义。 `<em>` 标签内的内容通常以斜体显示。屏幕阅读器将使用语言重音来强调 `<em>` 中的单词的发音。

{{<section plugin>}}

{{< app/html/generator name="emphasize" >}}

<br><br>
<h2> 在 C# 中创建 HTML em 标签</h2>

[Aspose.HTML for .NET](/html/{{lang.url-fragment}}net/) API 支持一组在 HTML 标准中定义的 HTML 元素，以及有关如何嵌套元素的规则。您可以通过添加新元素、删除或编辑现有节点的内容来修改文档。如果您想在您的产品中使用 HTML 编辑功能或以编程方式添加强调文本 HTML 标记，请参阅下面的 C# 示例。您可以使用几行代码创建所需的元素：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建强调文本 HTML 标记的步骤
---

1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建一个`<em>`元素。在 HTML 文档中，Document.CreateElement() 方法创建由 tagName 指定的 HTML 元素，在我们的例子中 tagName 是“em”。
2. 使用 [CreateTextNode()](https://reference.aspose.com/html/net/aspose.html.dom/document/createtextnode/) 方法创建文本内容。
3. 使用 [AppendChild()](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) 方法将文本内容添加到`<em>`元素中。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用 HTML 生成器构建高度可定制的 HTML 元素，无需编码！清晰、安全、简单！"
---