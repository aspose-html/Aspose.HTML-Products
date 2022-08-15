---
translation: true
template: /templates/_template-conversion-child.md
title: 在 C# 中将 EPUB 转换为 TIFF - 在线 EPUB 到 TIFF 转换器
description: EPUB 到 TIFF C# 转换的示例代码。在 ASP.NET 或任何 .NET 应用程序中轻松使用转换器 API。免费试用在线 EPUB 到 TIFF 转换器！
url: /net/conversion/epub-to-tiff/
family: html
platformtag: net
feature: conversion
informat: EPUB
outformat: TIFF
otherformats: PDF DOCX XPS BMP JPEG PNG TIFF GIF
---

{{<section banner>}}
---
h1: 通过 C# 将 EPUB 转换为 TIFF
h2: 使用 .NET API 从 EPUB 源文件生成 TIFF。使用我们的免费在线转换器立即将 EPUB 转换为 TIFF 格式！
---

{{<section overview>}}
---
h2: 使用 C# 将 EPUB 转换为 TIFF
---

为了将 EPUB 转换为 TIFF，我们将使用 [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API，这是一个功能丰富、功能强大且易于使用的文档C# 平台的操作和转换 API。 EPUB 是一种基于 XML 的开放格式，用于数字图书和出版物，可以在各种设备上查看和阅读。 EPUB 转换通常需要利用其他格式。强大的 C# API 允许您快速、高质量地将 EPUB 转换为流行格式！

{{<section demos>}}
---
h2: 免费在线转换器现场演示
---

直接在您的浏览器中测试 EPUB 到 TIFF 转换的质量！它快速、简单、安全且完全免费！以下 C# 示例演示了如何转换 EPUB 文档。我们描述了从文件中读取 EPUB 并使用默认保存选项将 EPUB 转换为 TIFF 的源代码。请从本地文件系统加载 EPUB，选择输出格式并运行示例。您将立即将结果作为单独的文件获得。

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter EPUB TIFF GIF PDF DOCX "JPG|JPEG" PNG BMP XPS >}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var stream = File.OpenRead(DataDir + "input.epub");
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
    Converter.ConvertEPUB(stream, options, "output.{{output lower}}");   
{{< /app/html/converter>}}


{{<section steps>}}
---
h2: 在 C# 中将 EPUB 转换为 TIFF 的步骤
---

如果您想在您的产品中考虑转换功能，或者您想以编程方式将 EPUB 转换为 TIFF，请参阅上面的 C# 代码示例或学习文档章节。您可以完全控制各种转换参数，将 EPUB 转换为 TIFF。它可以是不同的场景，但任何 EPUB 转换都可以通过几个必需的步骤进行：

1. 打开现有的 EPUB 文件。
1. 使用 TIFF ImageFormat 创建一个新的 [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) 对象。默认情况下，格式属性为 [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/)。
1. 使用Converter类的[ConvertEPUB()](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertepub/)方法将EPUB保存为TIFF图片.您需要将 EPUB 文件流、ImageSaveOptions 和输出文件路径传递给 ConvertEPUB() 方法以进行 EPUB 到 TIFF 的转换。
1. TIFF 文件将被保存到指定路径。




{{<section documentation>}}
---
h2: 文档中的 EPUB 到 TIFF 转换
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/#convert-epub-to-tiff" target="_blank">将 EPUB 转换为TIFF</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/#convert-epub-to-tiff-using-imagesaveoptions" target="_blank" >使用 ImageSaveOptions 将 EPUB 转换为 TIFF</a>

EPUB 格式作为基于 XML 的电子书格式而广受欢迎，旨在使内容的呈现方式适应阅读器设备。有时，需要获取图像而不是 EPUB 文档，例如使其可移植并易于在各种设备上共享，将电子书保存为 TIFF 中的图片等。请访问文档文章 [将 EPUB 转换为 TIFF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) 了解更多关于 Aspose.HTML 的 .NET API 转换功能并考虑最常见 EPUB 的 C# 示例TIFF 转换方案。在本文中，您可以找到有关如何使用 ConvertEPUB() 方法将 EPUB 转换为 TIFF 以及如何应用 ImageSaveOptions 的信息。

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
title: 其他支持的 EPUB 转换
subTitle: "您还可以将 EPUB 转换为许多其他文件格式："
---