---
translation: true
title: Quote & Blockquote HTML 生成器 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: 生成 Quote & Blockquote HTML 标签，预览结果并将生成的 HTML 和 C# 代码复制到您的网站。
url: /net/generators/quote-blockquote/
platformtag: net
family: html
generator: Quote & Blockquote HTML Generator
element: Quote or Blockquote HTML tag
tag: quote-blockquote
---

{{<section banner>}}
---
h1: Quote & Blockquote HTML 生成器
h2: 为 HTML Quote & Blockquote 标签生成 HTML 和 C# 代码，并在您的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 动态生成Quote & Blockquote HTML 标签！
---

`<q>` HTML 标签是一个标准的引号标签，用于不需要分句的短引用。大多数现代浏览器通过将文本括在引号中来实现这一点。 `<blockquote>` HTML 元素表明包含的文本是扩展引用。通常，这是通过缩进在视觉上呈现的。引用来源的 URL 可以使用 `cite` 属性给出。


{{<section plugin>}}

{{< app/html/generator name="quote-blockquote" >}}

<br>
<h2> Attributes </h2>

`cite` 属性指定引用的源 URL。此属性旨在指向解释上下文的信息或引用的引用。
<br><br>

<h2> 在 C# 中创建 HTML Quote & Blockquote HTML 标签</h2>

[Aspose.HTML for .NET](/html/{{lang.url-fragment}}net/) API 支持一组在 HTML 标准中定义的 HTML 元素，以及有关如何嵌套元素的规则。您可以通过添加新元素、删除或编辑现有节点的内容来修改文档。如果您想在您的产品中使用 HTML 编辑功能或以编程方式添加 Quote 和 Blockquote HTML 标签，请参阅下面的 C# 示例：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建引用 HTML 标记的步骤
---

1. 使用 Document 类的 [CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/) 方法创建一个 HTML `<q>` 元素。在 HTML 文档中，Document.CreateElement() 方法创建由 tagName 指定的 [HTMLQuoteElement](https://reference.aspose.com/html/net/aspose.html/htmlquoteelement/)，在我们的例子中 tagName 是 "问”。
2. 设置 [Cite](https://reference.aspose.com/html/net/aspose.html/htmlquoteelement/cite/) 属性的值。
2. 使用 [CreateTextNode()](https://reference.aspose.com/html/net/aspose.html.dom/document/createtextnode/) 方法创建文本内容。
3. 使用 [AppendChild()](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) 方法将文本内容添加到`<q>`元素中。
4. 复制 HTML `<q>` 标记的 C# 代码并在您的 C# 项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用 HTML 生成器构建高度可定制的 HTML 元素，无需编码！清晰、安全、简单！"
---