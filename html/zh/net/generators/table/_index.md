---
translation: true
title: HTML Table 发电机 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: HTML Table 发电机为表格元素创建 HTML 和 C# 代码。您可以生成代码并在您自己的网站或 C# 项目中使用它。
url: /net/generators/table/
platformtag: net
generator: HTML Table Generator
element: HTML table
tag: table
---

{{<section banner>}}
---
h1: HTML Table 发电机
h2: 为 HTML 表格元素生成 HTML 和 C# 代码，并在您自己的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 轻松生成 HTML 表格！
---

[HTML 表格元素](https://html.spec.whatwg.org/multipage/tables.html#the-table-element) 定义了一个 HTML 表格。它表示在二维表中呈现的信息，该表由包含数据的单元格的行和列组成。 HTML 表格由一个 `<table>` 元素和一个或多个 `<tr>`、`<th>` 和 `<td>` 元素组成，这些元素定义了表格行、表格标题和表格单元格。

{{<section plugin>}}

{{< app/html/generator name="table" >}}

<br>
<h2> Attributes </h2>

`<table>` 元素可以包含全局属性，例如 `style`、`border`、`align`、`width` 等。
 - `border` 属性指定边框宽度。 “0”值表示无边框。
 - `align` 属性指示表格必须如何在包含的文档中对齐。它可能具有以下值：左、中、右。
 - `width` 属性指定表格的宽度。
 <br><br>

<h2> 在 C# 中创建 HTML 表格</h2>

Aspose.HTML for .NET API 支持一组在 HTML 标准中定义的 HTML 元素，以及关于如何嵌套元素的规则。您可以通过添加新元素、删除或编辑现有节点的内容来修改文档。如果您想在产品中使用 HTML 编辑功能或以编程方式添加 `<table>` 元素，请参阅下面的 C# 代码示例：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML 表的步骤
---

1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建一个[HTMLTableElement.](https://reference.aspose.com/html/net/aspose.html/htmltableelement/)
2. 设置[Style](https://reference.aspose.com/html/net/aspose.html/htmlelement/style/)、[Align](https://reference.aspose.com/html/net/aspose.html/htmltableelement/align/), [Border](https://reference.aspose.com/html/net/aspose.html/htmltableelement/border/) 属性等。
3. 使用 [InsertRow()](https://reference.aspose.com/html/net/aspose.html/htmltableelement/insertrow/) 和 [InsertCell()](https://reference.aspose.com/html/net/aspose.html/htmltablerowelement/insertcell/) 方法为 HTML 表格添加行和列。
4. 复制 HTML 表的 C# 代码并在您的项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用 HTML 生成器构建高度可定制的 HTML 元素，无需编码！清晰、安全、简单！"
---