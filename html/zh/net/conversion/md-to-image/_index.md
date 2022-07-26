---
translation: true
template: /templates/_template-conversion-child.md
title: 将 MD 转换为图像
description: 用于 MD 到图像转换的示例 C# 代码。在 ASP.NET 或任何 .NET 应用程序中轻松使用转换器 API。免费试用在线 MD 到图像转换器！
url: /net/conversion/md-to-image/
family: html
platformtag: net
feature: conversion
informat: MD
outformat: Image
otherformats: PDF DOCX XPS JPEG BMP GIF PNG TIFF HTML
---

{{<section banner>}}
---
h1: 通过 C# 将 MD 转换为图像
h2: 使用服务器端 .NET API 进行高保真 MD 到图像的转换。使用我们的免费在线转换器立即将 MD 转换为图像格式！
---

{{<section overview>}}
---
h2: 使用 C# 将 MD 转换为图像
---

为了将 MD 转换为 Image，我们将使用 [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API，它是一个功能丰富、功能强大且易于使用的文档用于 C# 平台的操作和转换 API。从 Markdown 到其他格式的转换经过 Markdown 到 HTML 转换阶段。 .NET 开发人员只需几行代码即可轻松加载 MD 并将其转换为 Image。强大的 C# API 可让您快速、高质量地将 MD 转换为流行格式！

{{<section demos>}}
---
h2: 免费在线转换器现场演示
---

在您的浏览器中测试 MD 到图像转换的质量！它快速、简单、安全且完全免费！以下 C# 示例演示如何转换 MD 文档。我们描述了从文件中读取 MD，然后使用默认保存选项将 MD 转换为光栅图像的源代码。请从本地文件系统加载 MD，选择输出格式并运行示例。您将立即将结果作为单独的文件获得。

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MD "JPG|JPEG" GIF BMP XPS TIFF PNG PDF DOCX >}}
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
h2: 在 C# 中将 MD 转换为图像的步骤
---
1. 指定源 Markdown 文件的路径。
1. 将 Markdown 转换为 HTML。使用 [ConvertMarkdown(`sourcePath`)](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertmarkdown/#convertmarkdown_4) 方法将 Markdown 保存为 HTML 文档。
1. 新建一个[ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/)对象并指定ImageFormat。默认情况下，格式属性为 [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/)。
1. 使用 [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) 方法将中间 HTML 文档渲染为 Image。您需要将 HTMLDocument、ImageSaveOptions 和输出文件路径传递给 ConvertHTML() 方法。

{{<section documentation>}}
---
h2: 文档中的 MD 到图像转换
---

Markdown 是一种普遍接受的标记语言，通常用作文档和自述文件的格式。使用 Aspose.HTML .NET 库，您可以通过 C# 将 Markdown 转换为 JPG、PNG、GIF、TIFF 和 BMP 等图像格式。请访问文档文章 [Convert Markdown to Image](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) 了解有关 API 转换功能的更多信息并考虑最常见的 MD 到图像转换方案的 C# 示例。在本文中，您将找到有关如何使用 ConvertMarkdown() 方法将 Markdown 转换为 Image 以及如何应用 ImageSaveOptions 的信息。

 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/#convert-markdown-to-jpg" target="_blank">将 Markdown 转换为JPG</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/#convert-markdown-to-png" target="_blank">将 Markdown 转换为PNG</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/#convert-markdown-to-bmp" target="_blank">将 Markdown 转换为BMP</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/#convert-markdown-to-gif" target="_blank">将 Markdown 转换为动图</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/#convert-markdown-to-tiff" target="_blank">将 Markdown 转换为TIFF</a>

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