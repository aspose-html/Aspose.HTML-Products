---
translation: true
title: HTML Search Input 发电机 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: 生成 HTML 搜索输入、预览结果并将生成的 HTML 和 C# 代码复制到您的网站。
url: /net/generators/search/
platformtag: net
generator: HTML Search Input 发电机
element: HTML Search Input
tag: search
---

{{<section banner>}}
---
h1: HTML Search Input 发电机
h2: 为 HTML 搜索输入元素生成 HTML 和 C# 代码，并在您自己的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 轻松生成 HTML 搜索输入！
---

带有 `type='search'` 的 [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) 元素定义了一个为用户输入搜索查询而设计的文本字段进入。搜索框在每个网站上无处不在。这对于查找特定数据很有用。 HTML 搜索输入生成器可帮助您生成可以粘贴到 HTML 中的代码。只需选择选项并即时生成搜索框！

{{<section plugin>}}

{{< app/html/generator name="search" >}}

<br>
<h2> Attributes </h2>

- `name` 属性是必需的。如果没有为搜索字段提供名称，则不会提交任何内容。
- `size` 属性是一个数值，表示输入字段中可以包含多少个字符。
- `spellcheck` 是一个属性，用于指示是否对元素启用拼写检查。
- `placeholder` 属性是一个字符串，它为用户提供有关字段中预期信息的简要提示。<br><br>

<h2> 在 C# 中创建 HTML 搜索输入</h2>

Aspose.HTML for .NET API 支持一组在 HTML 标准中定义的 HTML 元素，以及关于如何嵌套元素的规则。您可以通过添加新元素、删除或编辑现有节点的内容来修改文档。如果您想在产品中使用 HTML 编辑功能或以编程方式添加搜索输入标签，请参见下面的示例。您可以使用几行 C# 代码创建搜索输入元素：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML 搜索输入的步骤
---

1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建[HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) 它创建由 tagName 指定的 HTML 元素。
1. 设置 [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/) 和 [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) 属性。
1. 使用 [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/) 方法添加`size`、`spellcheck`和`placeholder`属性他们的价值观。
1. 复制 HTML 搜索输入的代码并在您的 C# 项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用这些 HTML 生成器，您已经完成了所有艰苦的工作。您所要做的就是复制和粘贴。清晰、安全、简单！"
---