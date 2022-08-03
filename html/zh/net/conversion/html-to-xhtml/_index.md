---
translation: true
template: /templates/_template-conversion-child.md
title: 将 HTML 转换为 XHTML
description: 在 C# 中将 HTML 转换为 XHTML。在 ASP.NET 或任何 .NET 应用程序中轻松使用转换器 API。免费试用在线 HTML 到 XHTML 转换器！
url: /net/conversion/html-to-xhtml/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: XHTML
otherformats: DOCX PDF XPS GIF JPEG PNG TIFF BMP MHTML MD
howto: howtoHtmlXhtml
---

{{<section banner>}}
---
h1: 通过 C# 将 HTML 转换为 XHTML
h2: 使用 .NET API 从 HTML 源页面生成 XHTML。使用我们的免费在线转换器立即将 HTML 转换为 XHTML 格式。
---

{{<section overview>}}
---
h2: 使用 C# 将 HTML 转换为 XHTML
---

XHTML 被设计为更加结构化、更少的脚本和通用性，使用所有现有的 XML 工具并且更加独立于设备。要将 HTML 转换为 XHTML，我们将使用 [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API，这是一个功能丰富、功能强大且易于使用的文档操作和 C# 平台的转换 API。您可以通过对各种转换参数的完全控制，以编程方式将 HTML 转换为 XHTML。 HTML 到 XHTML 的转换有多种情况，例如从文件、URL、WYSISYG 编辑器、字符串或流中读取。强大的 C# API 允许您快速、高质量地将 HTML 转换为流行格式！

{{<section demos>}}
---
h2: 如何在 C# 中将 HTML 转换为 XHTML
---

以下 C# 示例演示了如何转换 HTML 文档。 HTML 到 XHTML 的转换有多种情况，例如从 URL/网页读取、WYSISYG 编辑器生成的 HTML 或从保存的文件中读取。我们描述了从文件中读取 HTML 并使用 Save() 方法将 HTML 转换为 XHTML 的源代码。

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML XHTML MHTML PDF MD "JPG|JPEG" GIF DOCX BMP XPS TIFF PNG>}}
using Aspose.Html;
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
{{#if_output 'BMP' 'JPG' 'GIF' 'PNG' 'TIFF' 'PDF' 'MHTML' 'MD' 'XPS' 'DOCX'}}
    Aspose.Html.Converters.Converter.ConvertHTML(document, options, "output.{{output lower}}"); 
{{/if_output}}
{{#if_output 'XHTML'}} 
    document.Save("output.xhtml", new HTMLSaveOptions() { DocumentType = HTMLSaveOptions.XHTML}); 
{{/if_output}}     
{{< /app/html/converter>}} 

{{<section steps>}}
---
h2: 在 C# 中将 HTML 转换为 XHTML 的步骤
---

如果您想在您的产品中考虑转换功能，或者您想以编程方式将 HTML 转换为 XHTML，请参阅上面的 C# 代码示例或学习文档章节。请采取以下强制性步骤：
1. 使用 [HTMLDocument(`string`)](https://reference.aspose.com/html/net/aspose.html/htmldocument/htmldocument/) 构造函数将 HTML 文档加载到 Document 对象中。您可以从文件、HTML 代码、流或 URL 加载 HTML。
1. 调用[Save(`string`, `HTMLSaveOptions`)](https://reference.aspose.com/html/net/aspose.html/htmldocument/save/)方法。
1. 传递带有 XHTML 文件扩展名的输出文件路径。
1. XHTML 文件将被保存到指定路径。

{{<section documentation>}}
---
h2: 文档中的 HTML 转换
---

出于各种原因，需要在格式之间进行转换：以熟悉、方便的格式工作，或利用不同格式完成特定任务。 Aspose.HTML for .NET API 允许您快速、高质量地将 HTML 转换为其他流行格式。请访问文档章节<a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">转换格式</a>以了解有关 Aspose 的更多信息。用于 .NET API 转换功能的 HTML。本章描述了流行的转换器，以及最常见的转换场景的 C# 示例。

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