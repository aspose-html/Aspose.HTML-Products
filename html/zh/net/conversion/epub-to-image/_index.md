---
translation: true
template: /templates/_template-conversion-child.md
title: 将 EPUB 转换为图像 - C# - 在线 EPUB 到图像转换器
description: 用于 EPUB 到图像转换的示例 C# 代码。在 ASP.NET 或任何 .NET 应用程序中轻松使用转换器 API。免费试用在线 EPUB 到图像转换器！
url: /net/conversion/epub-to-image/
family: html
platformtag: net
feature: conversion
informat: EPUB
outformat: "Image"
otherformats: PDF DOCX XPS JPEG BMP GIF PNG TIFF
---

{{<section banner>}}
---
h1: 通过 C# 将 EPUB 转换为图像
h2: 使用 .NET API 从 EPUB 源文件生成图像。使用我们的免费在线转换器立即将 EPUB 转换为图像格式！
---

{{<section overview>}}
---
h2: 使用 C# 将 EPUB 转换为图像
---

为了将 EPUB 转换为图像，我们将使用 [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API，它是一个功能丰富、功能强大且易于使用的文档C# 平台的操作和转换 API。 EPUB 是一种基于 XML 的开放格式，用于数字图书和出版物，可以在各种设备上查看和阅读。 EPUB 转换通常需要利用其他格式。您可以通过对各种转换参数的完全控制，以编程方式将 EPUB 转换为图像格式。强大的 C# API 允许您快速、高质量地将 EPUB 转换为图像！

{{<section demos>}}
---
h2: 免费在线转换器现场演示
---

直接在您的浏览器中测试 EPUB 到图像转换的质量！它快速、简单、安全且完全免费！以下 C# 示例演示了如何转换 EPUB 文档。我们描述了从文件中读取 EPUB 并使用默认保存选项将 EPUB 转换为光栅图像格式的源代码。请从本地文件系统加载 EPUB，选择输出格式并运行示例。您将立即将结果作为单独的文件获得。

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter EPUB "JPG|JPEG" GIF PDF DOCX PNG BMP TIFF XPS >}}
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
h2: 在 C# 中将 EPUB 转换为图像的步骤
---

如果您想在您的产品中考虑转换功能，或者您想以编程方式将 EPUB 转换为图像，请参阅上面的 C# 代码示例或学习文档章节。它可以是不同的场景，但任何 EPUB 转换都可以通过几个必需的步骤进行：

1. 打开现有的 EPUB 文件。
1. 新建一个[ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/)对象并指定ImageFormat。默认情况下，格式属性为 [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/)。
1. 使用Converter类的[ConvertEPUB()](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertepub/)方法将EPUB保存为Image。您需要将 EPUB 文件流、ImageSaveOptions 和输出文件路径传递给 ConvertEPUB() 方法以进行 EPUB 到图像的转换。
1. 图像文件将被保存到指定路径。




{{<section documentation>}}
---
h2: 文档中的 EPUB 到图像转换
---

EPUB 格式作为基于 XML 的电子书格式而广受欢迎，旨在使内容的呈现方式适应阅读器设备。有时，需要获取图像而不是 EPUB 文档，例如使其可移植并在各种设备上轻松共享、从电子书创建图片库等。请访问文档章节 [格式之间转换](https:// docs.aspose.com/html/net/converting-between-formats/) 了解更多有关 Aspose.HTML for .NET API 转换功能的信息，并考虑最常见的 EPUB 到图像转换方案的 C# 示例。在文章中，您可以找到有关如何使用 ConvertEPUB() 方法将 EPUB 转换为 Image 以及如何应用 ImageSaveOptions 或 [ICreateStreamProvider](https://reference.aspose.com/html/net/aspose.html.io/) 的信息icreatestreamprovider) 参数。

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#epub-to-jpg-by-two-lines-of-code" target="_blank">EPUB转JPG两行代码</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#convert-epub-to-jpg-using-imagesaveoptions" target="_blank" >使用 ImageSaveOptions 将 EPUB 转换为 JPG</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers" target="_blank">使用将 EPUB 转换为 JPG MemoryStreamProvider</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/" target="_blank">将 EPUB 转换为 PNG</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/" target="_blank">将 EPUB 转换为 BMP</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/" target="_blank">将 EPUB 转换为 TIFF</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/" target="_blank">将 EPUB 转换为 GIF</a>



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