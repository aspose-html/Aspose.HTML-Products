---
translation: true
template: /templates/_template-conversion-child.md
title: 将 MD 转换为 PDF - C#
description: 用于 MD 到 PDF 转换的示例 C# 代码。在 ASP.NET 或任何 .NET 应用程序中轻松使用转换器 API。免费试用在线 MD to PDF Converter！
url: /net/conversion/md-to-pdf/
family: html
platformtag: net
feature: conversion
informat: MD
outformat: PDF
otherformats: XPS DOCX JPEG BMP GIF PNG TIFF HTML
howto: howtoMd
---

{{<section banner>}}
---
h1: 通过 C# 将 MD 转换为 PDF
h2: 使用服务器端 .NET API 进行高保真 MD 到 PDF 的转换。使用我们的免费在线转换器立即将 MD 转换为 PDF 格式！
---

{{<section overview>}}
---
h2: 使用 C# 将 MD 转换为 PDF
---

为了将 MD 转换为 PDF，我们将使用 [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API，这是一个功能丰富、功能强大且易于使用的文档C# 平台的操作和转换 API。从 Markdown 到其他格式的转换经过 Markdown 到 HTML 转换阶段。 .NET 开发人员只需几行代码即可轻松加载 MD 并将其转换为 PDF。强大的 C# API 可让您快速、高质量地将 MD 转换为流行格式！

{{<section demos>}}
---
h2: 免费在线转换器现场演示
---

在您的浏览器中测试 MD 到 PDF 转换的质量！它快速、简单、安全且完全免费！以下 C# 示例演示如何转换 MD 文档。我们描述了从文件中读取 MD，然后使用默认保存选项将 MD 转换为 PDF 的源代码。请从本地文件系统加载 MD，选择输出格式并运行示例。您将立即将结果作为单独的文件获得。

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MD PDF DOCX "JPG|JPEG" GIF BMP XPS TIFF PNG >}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = Converter.ConvertMarkdown("input.md");
{{#if_output 'PDF'}}
    var options = new PdfSaveOptions();
{{/if_output}}
{{#if_output 'DOCX'}}
    var options = new DocSaveOptions();
{{/if_output}}
{{#if_output 'XPS'}}
    var options = new XpsSaveOptions();
{{/if_output}}
{{#if_output 'BMP' 'JPG' 'GIF' 'PNG' 'TIFF'}}
    var options = new ImageSaveOptions(ImageFormat.{{output param2 camel}});
{{/if_output}}
    Converter.ConvertHTML(document, options, "output.{{output lower}}");   
{{< /app/html/converter>}}


{{<section steps>}}
---
h2: 在 C# 中将 MD 转换为 PDF 的步骤
---
1. 指定源 Markdown 文件的路径。
1. 将 Markdown 转换为 HTML。使用 [ConvertMarkdown(`sourcePath`)](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertmarkdown/#convertmarkdown_4) 方法将 Markdown 保存为 HTML 文档。
1. 创建一个新的 [PdfSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions/) 对象。
1. 使用 [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) 方法将中间 HTML 文档渲染为 PDF 文件。您需要将 HTMLDocument、DocSaveOptions 和输出文件路径传递给 ConvertHTML() 方法。

{{<section documentation>}}
---
h2: 文档中的 MD 到 PDF 转换
---

Markdown 通常用作文档和自述文件的格式，因为它允许以易于阅读和易于编写的风格进行编写。 MD 到 PDF 的转换通常需要利用 PDF 格式来完成特定任务。请访问文档文章 [Convert Markdown to PDF](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-pdf/) 了解更多关于 Aspose.HTML for .NET API转换功能，并考虑最常见的 MD 到 PDF 转换方案的 C# 示例。在本文中，您将找到有关如何使用 ConvertMarkdown() 方法将 Markdown 转换为 PDF 以及如何应用 PdfSaveOptions 的信息。

 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-pdf/#convert-markdown-to-pdf" target="_blank">将 Markdown 转换为PDF</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-pdf/#convert-markdown-to-pdf-using-pdfsaveoptions" target="_blank" >使用 PdfSaveOptions 将 Markdown 转换为 PDF</a>

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
title: 其他支持的 MD 转换
subTitle: "您还可以将 MD 转换为许多其他文件格式："
---