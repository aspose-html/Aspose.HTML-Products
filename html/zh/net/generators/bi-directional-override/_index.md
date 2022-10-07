---
translation: true
title: 双向覆盖 HTML 生成器 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: HTML BDO 生成器为 HTML bdo 标签创建 HTML 和 C# 代码。您可以生成代码并在您自己的网站或 C# 项目中使用它。
url: /net/generators/bdo/
platformtag: net
generator: HTML BDO Generator
element: HTML bdo tag
tag: bdo
---

{{<section banner>}}
---
h1: 双向覆盖 HTML 生成器
h2: 为 HTML bdo 标签生成 HTML 和 C# 代码，并在您的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 轻松生成双向覆盖 HTML 标记！
---

[bdo](https://html.spec.whatwg.org/multipage/text-level-semantics.html#the-bdo-element) HTML 元素会覆盖文本的当前方向，从而使里面的文本呈现在一个不同的方向。 BDO 代表双向超控。 HTML `<bdo>` 标记指定其中内容在浏览器中从左到右或从右到左显示的方向。 `<bdo>` 标签对于从右到左的语言很有用，例如阿拉伯语、波斯语和希伯来语。

{{<section plugin>}}

{{< app/html/generator name="bi-directional-override" >}}

<br>
<h2> Attributes </h2>

HTML BDO Generator 通过选择 `dir`、`spellcheck` 等属性来帮助生成 HTML bdo 标签。`dir` 属性是必需的。它定义了应该在该元素的内容中呈现文本的方向。可能的值为：*rtl* 和 *ltr*。
<br><br>

<h2> 在 C# 中创建 HTML BDO 标签</h2>

如果您想在您的产品中使用 HTML 编辑功能或以编程方式添加 HTML `<bdo>` 标签，请参阅下面的 C# 示例。您可以使用几行代码创建所需的元素：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML BDO 标签的步骤
---

1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建一个`<bdo>`元素。在 HTML 文档中，Document.CreateElement() 方法创建由 tagName 指定的 HTML 元素，在我们的例子中 tagName 是“bdo”。
2. 使用 [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/) 方法添加`dir`和其他需要的属性。
3. 使用 [CreateTextNode()](https://reference.aspose.com/html/net/aspose.html.dom/document/createtextnode/) 方法创建文本内容。
4. 使用 [AppendChild()](https://reference.aspose.com/html/net/aspose.html.dom/node/appendchild/) 方法将文本内容添加到`<bdo>`元素中。
5. 复制 HTML bdo 标记的 C# 代码并在您的 C# 项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用 HTML 生成器构建高度可定制的 HTML 元素，无需编码！清晰、安全、简单！"
---