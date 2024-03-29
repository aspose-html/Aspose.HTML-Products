﻿---
translation: true
template: /templates/_template-conversion-child.md
title: 将 XHTML 转换为 PDF
description: 在 C# 中将 XHTML 转换为 PDF。在 ASP.NET 或任何 .NET 应用程序中轻松使用转换器 API。免费试用在线 XHTML 到 PDF 转换器！
url: /net/conversion/xhtml-to-pdf/
family: html
platformtag: net
feature: conversion
informat: XHTML
outformat: PDF
otherformats: XPS DOCX GIF JPEG PNG TIFF BMP HTML MHTML MD
howto: howtoXhtml
---

{{<section banner>}}
---
h1: 通过 C# 将 XHTML 转换为 PDF
h2: 使用 .NET API 从 XHTML 源页面生成 PDF。使用我们的免费在线转换器立即将 XHTML 转换为 PDF 格式！
---

{{<section overview>}}
---
h2: 使用 C# 将 XHTML 转换为 PDF
---

通常需要将 XHTML 转换为 PDF 以保护文档免受不必要的编辑和复制，准备文档以打印或通过电子邮件发送等。使用 [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API，您可以以编程方式将 XHTML 转换为 PDF，并完全控制转换参数。您要执行的任何转换都涉及加载 XHTML 文档并将其保存为 PDF 格式。强大的 C# API 允许您快速、高质量地将 XHTML 转换为 PDF！

{{<section demos>}}
---
h2: 免费在线转换器现场演示
---

直接在您的浏览器中测试 XHTML 到 PDF 转换的质量！请从本地文件系统加载 XHTML 文件，从列表中选择所需的输出格式并运行示例。它快速、简单、安全且完全免费！ XHTML 到 PDF 的转换将使用默认的保存选项完成。您将立即将结果作为单独的文件获得。因此，在线快速将任何网页或 XHTML 转换为 PDF 格式！

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter XHTML PDF BMP TIFF PNG "JPG|JPEG" GIF PDF XPS DOCX MHTML MD >}}
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
h2: 在 C# 中将 XHTML 转换为 PDF 的步骤
---

如果您想以编程方式将 XHTML 转换为 PDF，请参阅上面的 C# 代码示例或学习文档章节。在所有情况下，任何 XHTML 到 PDF 的转换都需要一些强制性步骤：

1. 使用 [HTMLDocument](https://reference.aspose.com/html/net/aspose.html/htmldocument/) 类的 HTMLDocument() 构造函数之一加载 XHTML 文件。
1. 创建一个新的 [PdfSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions/) 对象。
1. 使用Converter类的[ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/)方法将XHTML保存为PDF文件。
1. PDF文件将保存到指定路径。

{{<section documentation>}}
---
h2: 文档中的HTML转换
---

XHTML 到 PDF 转换通常需要建立对文档编辑或复制的有限访问权限，以生成官方文档或发送一些信息，例如通过电子邮件。 Aspose.HTML for .NET API 允许您快速、高质量地将 (X)HTML 转换为其他流行格式。请访问文档章节 <a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">Converting Between Formats</a> 了解有关 API 的更多信息转换功能。本章描述了流行的转换器，以及最常见的转换场景的 C# 示例。

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