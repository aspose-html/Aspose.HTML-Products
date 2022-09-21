---
translation: true
title: HTML Submit Input 发电机 - 在线工具和 C# 代码
template: /templates/_template-generators-child.md
description: 为您的网站创建 HTML 提交输入。 Р查看提交按钮，复制并在您的项目中使用生成的 HTML 和 C# 代码！
url: /net/generators/submit/
platformtag: net
generator: HTML Submit Input 发电机
element: HTML Submit Input
tag: submit
---

{{<section banner>}}
---
h1: HTML Submit Input 发电机
h2: 为 HTML 提交输入元素生成 HTML 和 C# 代码，并在您自己的网站或 C# 项目中使用它。
---

{{<section overview>}}
---
h2: 轻松生成 HTML 提交输入！
---

带有 `type='submit'` 的 [input](https://html.spec.whatwg.org/multipage/input.html#the-input-element) 元素呈现为提交按钮，该按钮将表单提交到服务器。当用户单击按钮时，用户代理会尝试将表单提交到服务器。 HTML 提交输入生成器可帮助您生成可以粘贴到 HTML 中的代码。只需选择选项并即时生成提交按钮！

{{<section plugin>}}

{{< app/html/generator name="submit" >}}

<br>
<h2> Attributes </h2>

`value` 属性包含显示为按钮标签的字符串。否则，如果您未指定值，则该按钮将具有用户代理选择的默认标签。如果要禁用提交按钮，请将 `disabled` 属性设置为它。<br><br>

<h2> 在 C# 中创建 HTML 提交输入</h2>

Aspose.HTML for .NET API 用作无头浏览器，允许您从各种来源创建或打开现有 HTML 文档，以执行编辑操作，例如删除、附加和替换 HTML 节点。如果您想在产品中使用 HTML 编辑功能或以编程方式添加提交按钮，请参阅下面的 C# 代码示例。您可以使用几行创建提交输入标签：

{{< /app/html/generator >}}

{{<section steps>}}
---
h2: 在 C# 中创建 HTML 提交输入的步骤
---

1. 使用Document类的[CreateElement()](https://reference.aspose.com/html/net/aspose.html.dom/document/createelement/)方法创建[HTMLInputElement.](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/) 它创建由 tagName 指定的 HTML 元素。
1. 设置 [Type](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/type/) 和 [Name](https://reference.aspose.com/html/net/aspose.html/htmlinputelement/name/) 属性。
1. 使用 [SetAttribute()](https://reference.aspose.com/html/net/aspose.html.dom/element/setattribute/) 方法添加 `value`、`disabled` 或其他支持的属性他们的价值观。
1. 复制提交按钮的 C# 代码并在您的项目中使用它。

{{<section other-generators>}}
---
title: 其他支持的 HTML 生成器
subTitle: "使用这些 HTML 代码生成器，您已经完成了所有艰苦的工作。您所要做的就是复制和粘贴。清晰、安全、简单！"
---