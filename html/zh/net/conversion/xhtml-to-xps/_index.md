﻿---
translation: true
template: /templates/_template-conversion-child.md
title: 在 C# 中将 XHTML 转换为 XPS - 在线 XHTML 到 XPS 转换器
description: 在 C# 中将 XHTML 转换为 XPS。在 ASP.NET 或任何 .NET 应用程序中轻松使用转换器 API。免费试用在线 XHTML 到 XPS 转换器！
url: /net/conversion/xhtml-to-xps/
family: html
platformtag: net
feature: conversion
informat: XHTML
outformat: XPS
otherformats: PDF DOCX GIF JPEG PNG TIFF BMP HTML MHTML MD
howto: howtoXhtml
---

{{<section banner>}}
---
h1: 通过 C# 将 XHTML 转换为 XPS
h2: 使用 .NET API 从 XHTML 源页面生成 XPS。使用我们的免费在线转换器立即将 XHTML 转换为 XPS 格式！
---

{{<section overview>}}
---
h2: 使用 C# 将 XHTML 转换为 XPS
---

[Aspose.HTML .NET](https://products.aspose.com/html/net/) API 的主要亮点是转换功能。使用我们强大的库，您可以通过完全控制各种转换参数以编程方式将 XHTML 转换为 XPS。 XPS 文件格式提供访问权限管理并提供高质量的可打印文档。您要执行的任何转换都涉及加载 XHTML 文档并将其保存为支持的格式。强大的 C# API 允许您快速、高质量地将 XHTML 转换为 XPS！

{{<section demos>}}
---
h2: 免费在线转换器现场演示
---

直接在您的浏览器中测试 XHTML 到 XPS 转换的质量！请从本地文件系统加载 XHTML 文件，从列表中选择所需的输出格式并运行示例。它快速、简单、安全且完全免费！ XHTML 到 XPS 的转换将使用默认保存选项完成。您将立即将结果作为单独的文件获得。因此，在线快速将任何网页或 XHTML 转换为 XPS 格式！

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter XHTML XPS TIFF PNG "JPG|JPEG" GIF BMP PDF DOCX MD MHTML>}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new HTMLDocument("{{input lower}}");
{{#if_output 'PDF'}}
    var options = new PdfSaveOptions();
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
{{#if_output 'MHTML'}}
    var options = new MHTMLSaveOptions();
{{/if_output}}
{{#if_output 'BMP' 'JPG' 'GIF' 'PNG' 'TIFF'}}
    var options = new ImageSaveOptions(ImageFormat.{{output param2 camel}});
{{/if_output}}
    Converter.ConvertHTML(document, options, "output.{{output lower}}");   
{{< /app/html/converter>}} 


{{<section steps>}}
---
h2: 在 C# 中将 XHTML 转换为 XPS 的步骤
---

您要执行的任何转换都涉及加载 XHTML 文档并将其保存为 XPS 格式。要将 XHTML 转换为 XPS，您应该采取一些强制性步骤：

1. 使用 [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/) 构造函数之一加载 XHTML 文档。
1. 创建一个新的 [XpsSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/xpssaveoptions/) 对象。
1. 使用 [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) 方法将 XHTML 保存为 XPS 文件。您需要将 HTMLDocument、XpsSaveOptions 和输出文件路径传递给 ConvertHTML() 方法。
1. XPS文件将保存到指定路径。

{{<section documentation>}}
---
h2: 文档中的HTML转换
---

XPS 是微软开发的一种文档存储和查看格式。它具有一系列支持安全功能的优势，例如提供更高文档安全性的数字签名等。请访问文档章节 <a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">Converting Between Formats</a> 了解有关 API 的更多信息转换功能。本章描述了流行的转换器，以及最常见的转换场景的 C# 示例。

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
title: 其他支持的 XHTML 转换
subTitle: "您还可以将 XHTML 转换为许多其他文件格式："
---