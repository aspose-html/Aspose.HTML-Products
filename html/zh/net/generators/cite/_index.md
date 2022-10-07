---
translation: true
title: HTML <cite> 标签生成器 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: 引文 HTML 生成器创建一个 HTML 引文标签。您可以预览、复制生成的 HTML 和 C# 代码并在您的网站或 C# 项目中使用它
url: /net/generators/cite/
platformtag: net
family: html
generator: Citation HTML Generator
element: HTML cite tag
tag: cite
---

{{<section banner>}}
---
h1: 引文 HTML 生成器
h2: 为 HTML `<cite>` 标签生成 HTML 和 C# 代码，并在您自己的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 轻松生成 HTML <cite> 标签！
---

`<cite>` HTML 元素用于描述对被引用创意作品的引用，例如书籍、诗歌、电影、电影、绘画、歌曲等。它必须包含被引用作品的标题，可能是根据既定要求以缩写形式。

{{<section plugin>}}

{{< app/html/generator name="cite" >}}

<br>
<h2> 在 C# 中创建 HTML cite 标签</h2>

[Aspose.HTML for .NET](/html/{{lang.url-fragment}}net/) API 支持一组在 HTML 标准中定义的 HTML 元素，以及有关如何嵌套元素的规则。您可以通过添加新元素、删除或编辑现有节点的内容来修改文档。如果您想在产品中使用 HTML 编辑功能或以编程方式添加 `<cite>` 元素，请参阅下面的 C# 代码示例：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML 引用标签的步骤
---

1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建一个`<cite>`元素。在 HTML 文档中，Document.CreateElement() 方法创建由 tagName 指定的 HTML 元素，在我们的例子中 tagName 是“cite”。
2. 使用 [CreateTextNode()](https://reference.aspose.com/html/net/aspose.html.dom/document/createtextnode/) 方法创建文本内容。
3. 使用 [AppendChild()](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) 方法将文本内容添加到`<cite>`元素中。
4. 复制 HTML Citation 元素的 C# 代码并在您的 C# 项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用这些 HTML 生成器，您已经完成了所有艰苦的工作。您所要做的就是复制和粘贴。清晰、安全、简单！"
---