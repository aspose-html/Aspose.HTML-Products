---
translation: true
title: HTML Telephone Input 发电机 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: 为您的网站创建 HTML 电话输入。 Р查看电话输入，复制并在您的项目中使用生成的 HTML 和 C# 代码！
url: /net/generators/telephone/
platformtag: net
generator: HTML Telephone Input 发电机
element: HTML Telephone Input
tag: telephone
---

{{<section banner>}}
---
h1: HTML Telephone Input 发电机
h2: 为 HTML Telephone Input 元素生成 HTML 和 C# 代码，并在您自己的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 即时生成 HTML 电话输入！
---

带有 `type='tel'` 的 [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) 元素用于让用户输入和编辑电话号码.此输入值不会自动验证，因为世界各地的电话号码格式差异很大。从功能上讲，这对于移动浏览器来说很方便，因为智能手机通常会识别输入类型并更改键盘以显示数字小键盘。请注意，不支持 `type='tel'` 的浏览器会退回到标准文本输入。

{{<section plugin>}}

{{< app/html/generator name="telephone" >}}

<br>
<h2> Attributes </h2>

通过输入 `type='tel'` 元素，您可以使用 *name*、*size*、*placeholder*、*list*、*maxlength*、*minlength* 等属性。

- `size` 属性是一个数值，表示输入字段中可以包含多少个字符。
- `placeholder` 属性是一个字符串，它为用户提供有关字段中预期信息的简要提示。
<br><br>

<h2> 在 C# 中创建 HTML 电话输入</h2>

Aspose.HTML for .NET API 用作无头浏览器，允许您从各种来源创建或打开现有 HTML 文档，以执行编辑操作，例如删除、附加和替换 HTML 节点。如果您想在产品中使用 HTML 编辑功能或以编程方式添加电话输入，请参阅下面的 C# 代码示例：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML 电话输入的步骤
---

1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建[HTMLInputElement.](https://参考.aspose.com/html/net/aspose.html/htmlinputelement/)
1. 设置 [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/)、[Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) 和 [Size](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/size/) 属性。
1. 使用 [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/) 方法添加 `placeholder` 或其他支持的属性及其值。
1. 复制 HTML 电话输入的 C# 代码并在您的 C# 项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用这些 HTML 代码生成器，您已经完成了所有艰苦的工作。您所要做的就是复制和粘贴！"
---