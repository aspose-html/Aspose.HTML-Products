---
translation: true
title: HTML iFrame  发电机 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: HTML iFrame  发电机 为 iframe 元素创建 HTML 和 C# 代码。预览结果并将生成的代码复制到您的网站。
url: /net/generators/iframe/
platformtag: net
generator: HTML iFrame  发电机
element: HTML iframe
tag: iframe
---

{{<section banner>}}
---
h1: HTML iFrame 生成器
h2: 为 HTML iFrame 元素生成 HTML 和 C# 代码，并在您自己的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 即时生成 HTML iFrame！
---

HTML [iframe](https://html.spec.whatwg.org/multipage/iframe-embed-object.html#the-if​​rame-element) 元素表示 [嵌套浏览上下文；](https://html.spec.whatwg.org/multipage/browsers.html#nested-browsing-context)它用于在当前 HTML 文档中嵌入另一个文档。使用 HTML iFrame 生成器，您可以创建一个 `<iframe>` 标记并根据您的要求对其进行自定义。您可以以百分比和像素为单位指定其宽度和高度，给出名称，设置滚动和边框。

{{<section plugin>}}

{{< app/html/generator name="iframe" >}}

<br>
<h2> Attributes </h2>

 - `src` 属性是必需的，它定义了嵌套网页的 URL。
 - `name` 属性指定 iframe 的可定位名称。
 - `width` 和 `height` 属性指定 iframe 的宽度和高度。默认宽度为 300 像素，默认高度为 150 像素。
 - `scrolling` 属性指定浏览器何时应为框架提供滚动条。
 <br><br>

<h2> 在 C# 中创建 HTML iFrame</h2>

Aspose.HTML for .NET API 支持一组在 HTML 标准中定义的 HTML 元素，以及关于如何嵌套元素的规则。您可以通过添加新元素、删除或编辑现有节点的内容来修改文档。如果您想在产品中使用 HTML 编辑功能或以编程方式添加 `<iframe>` 元素，请参阅下面的 C# 代码示例：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML iFrame 的步骤
---

1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建一个[HTMLIFrameElement.](https://reference.aspose.com/html/net/aspose.html/htmliframeelement/)
2. 为 [Src](https://reference.aspose.com/html/net/aspose.html/htmliframeelement/src/)、[Name](https://reference.aspose.com/html/net/aspose.html/htmliframeelement/name/)、[Height](https://reference.aspose.com/html/net/aspose.html/htmliframeelement/height/)和[Width](https://reference.aspose.com/html/net/aspose.html/htmliframeelement/width/) 属性。
3. 复制 HTML iFrame 的 C# 代码并在您的项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用 HTML 生成器构建高度可定制的 HTML 元素，无需编码！清晰、安全、简单！"
---