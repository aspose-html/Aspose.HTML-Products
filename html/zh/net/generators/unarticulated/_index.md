---
translation: true
title: Underline text HTML 生成器 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: 生成下划线 HTML 标记，预览结果并将生成的 HTML 和 C# 代码复制到您的网站。
url: /net/generators/underline/
platformtag: net
family: html
generator: Underline Text HTML Generator
element: Underline HTML tag
tag: underline
---

{{<section banner>}}
---
h1: Underline text HTML 生成器
h2: 为带下划线的 HTML 标记生成 HTML 和 C# 代码，并在您的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 即时生成下划线 HTML 标签！
---

`<u>` HTML 标记表示一些样式与普通文本不同的文本，例如拼写错误的单词。 `<u>` 标签内的内容通常以简单的实线下划线显示。 <br>
避免使用可能与超链接混淆的 `<u>` 元素！因此，除非您确实需要，否则不建议在文本下划线。如果您需要[emphasize text](/html/{{lang.url-fragment}}net/generators/emphasize/)，请使用 `<em>` 标签。使用 `<strong>` 标记为文本赋予 [strong Importance](/html/{{lang.url-fragment}}net/generators/strong/)。这些元素是专门为这些目的而创建的，浏览器通常会相应地呈现这些文本。

{{<section plugin>}}

{{< app/html/generator name="unarticulated" >}}

<br>
<h2> Create Underline HTML Tag in C#</h2>

[Aspose.HTML for .NET](/html/{{lang.url-fragment}}net/) API 支持一组在 HTML 标准中定义的 HTML 元素，以及有关如何嵌套元素的规则。您可以通过添加新元素、删除或编辑现有节点的内容来修改文档。如果您想在产品中使用 HTML 编辑功能或以编程方式添加下划线 HTML 标记，请参阅下面的 C# 示例。您可以使用几行代码创建所需的元素：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建下划线 HTML 标记的步骤
---

1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建一个`<u>`元素。 Document.CreateElement() 方法创建由 tagName 指定的 HTML 元素，在我们的例子中 tagName 是“u”。
2. 使用 [CreateTextNode()](https://reference.aspose.com/html/net/aspose.html.dom/document/createtextnode/) 方法创建文本内容。
3. 使用 [AppendChild()](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) 方法将文本内容添加到 HTML `<u>` 元素中。
4. 复制下划线 HTML 标记的代码并在您的 C# 项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用 HTML 生成器构建高度可定制的 HTML 元素，无需编码！清晰、安全、简单！"
---