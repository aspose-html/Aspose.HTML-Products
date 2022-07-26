---
translation: true
template: /templates/_template-conversion-child.md
title: 将 HTML 转换为 MD
description: 在 C# 中将 HTML 转换为 MD。在 ASP.NET 或任何 .NET 应用程序中轻松使用转换器 API。免费试用在线 HTML 到 MD 转换器！
url: /net/conversion/html-to-md/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: MD
otherformats: PDF DOCX XPS GIF JPEG PNG TIFF BMP XHTML MHTML
---

{{<section banner>}}
---
h1: 通过 C# 将 HTML 转换为 MD
h2: 使用 .NET API 从 HTML 源页面生成 MD。使用我们的免费在线转换器立即将 HTML 转换为 MD 格式。
---

{{<section overview>}}
---
h2: 使用 C# 将 HTML 转换为 MD
---

Markdown 是一种具有纯文本格式语法的标记语言。它的设计使其可以轻松转换为多种输出格式，但最初创建它只是为了转换为 HTML。 Aspose.HTML 类库提供了从 HTML 到 Markdown 的反向转换。使用 [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API，您可以以编程方式将 HTML 转换为 MD，并完全控制各种转换参数。 HTML 到 MD 的转换有多种情况，例如从文件、URL、WYSISYG 编辑器、字符串或流中读取 HTML。强大的 C# API 允许您快速、高质量地将 HTML 转换为流行格式！

{{<section demos>}}
---
h2: 免费在线转换器现场演示
---

在您的浏览器中测试 HTML 到 MD 转换的质量！请从本地文件系统加载 HTML 文件，从列表中选择所需的输出格式并运行示例。它快速、简单、安全且完全免费！ HTML 到 MD 的转换将使用默认的保存选项完成。您将立即将结果作为单独的文件获得。所以，在线快速将任何网页或 HTML 转换为 MD 格式！

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML MD PDF "JPG|JPEG" GIF DOCX BMP XPS TIFF PNG MHTML >}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new HTMLDocument("document.{{input lower}}");
{{#if_output 'PDF'}}
    var options = new PdfSaveOptions();
{{/if_output}}
{{#if_output 'MHTML'}}
    var options = new MHTMLSaveOptions();
{{/if_output}}
{{#if_output 'DOCX'}}
    var options = new DocSaveOptions();
{{/if_output}}
{{#if_output 'XPS'}}
    var options = new XpsSaveOptions();
{{/if_output}}
{{#if_output 'MD'}}
    var options = new MarkdownSaveOptions();
{{/if_output}}
{{#if_output 'BMP' 'JPG' 'GIF' 'PNG' 'TIFF'}}
    var options = new ImageSaveOptions(ImageFormat.{{output param2 camel}});
{{/if_output}}
    Converter.ConvertHTML(document, options, "output.{{output lower}}");   
{{< /app/html/converter>}} 


{{<section steps>}}
---
h2: 在 C# 中将 HTML 转换为 MD 的步骤
---

如果您想在您的产品中考虑转换功能，或者您想以编程方式将 HTML 转换为 MD，请参阅上面的 C# 代码示例或学习文档章节。在所有情况下，任何转换都需要一些强制性步骤：
1. 使用 [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/) 构造函数之一加载 HTML 文档。您可以从文件、HTML 代码、流或 URL 加载 HTML。
1. 新建一个[MarkdownSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions/)对象。
1. 使用Converter类的[ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/)方法将HTML保存为Markdown文件。您需要将 HTMLDocument、MarkdownSaveOptions 和输出文件路径传递给 ConvertHTML() 方法。
1. MD文件将保存到指定路径。

{{<section documentation>}}
---
h2: 文档中的 HTML 到 Markdown 的转换
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#html-to-markdown-by-a-few-lines-of-code " target="_blank">HTML 转 Markdown 几行代码</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-in-c-using-markdownsaveoptions" target="_blank">使用 MarkdownSaveOptions 将 HTML 转换为 Markdown</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#limitation" target="_blank">转换限制</a>

请访问文档文章 [将 HTML 转换为 Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/) 以了解有关 Aspose.HTML for .NET API 的更多信息转换功能，并考虑最常见的 HTML 到 MD 转换方案的 C# 示例。在本文中，您可以找到有关如何使用 ConvertHTML() 方法将 HTML 转换为 MD 以及如何应用 MarkdownSaveOptions 和 ICreateStreamProvider 参数的信息。

{{<section online-converters>}}
---
h2: 免费在线转换器
---

{{<section get-started>}}
---
h2: 如何为 .NET 库安装 Aspose.HTML
---

{{<section other-conversions>}}
---
title: 其他支持的 HTML 转换
subTitle: "您还可以将 HTML 转换为许多其他文件格式："
---