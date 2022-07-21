---
translation: true
template: /templates/_template-conversion-child.md
title: 将 EPUB 转换为 BMP
description: EPUB 到 BMP C# 转换的示例代码。在 ASP.NET 或任何 .NET 应用程序中轻松使用转换器 API。免费试用在线 EPUB 到 BMP 转换器！
url: /net/conversion/epub-to-bmp/
family: html
platformtag: net
feature: conversion
informat: EPUB
outformat: BMP
otherformats: PDF DOCX XPS GIF JPEG PNG TIFF
---

{{<section banner>}}
---
h1: 通过 C# 将 EPUB 转换为 BMP
h2: 使用 .NET API 从 EPUB 源文件生成 BMP。使用我们的免费在线转换器立即将 EPUB 转换为 BMP 格式！
p: 使用我们的免费在线转换器立即将 EPUB 转换为 BMP 格式！
---

{{<section overview>}}
---
h2: 使用 C# 将 EPUB 转换为 BMP
---

为了将 EPUB 转换为 BMP，我们将使用 [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API，它是一个功能丰富、功能强大且易于使用的文档C# 平台的操作和转换 API。 EPUB 是一种基于 XML 的开放格式，用于数字图书和出版物，可以在各种设备上查看和阅读。 EPUB 转换通常需要利用其他格式。您可以通过对各种转换参数的完全控制，以编程方式将 EPUB 转换为 BMP。强大的 C# API 允许您快速、高质量地将 EPUB 转换为流行格式！

{{<section demos>}}
---
h2: 免费在线转换器现场演示
---

直接在您的浏览器中测试 EPUB 到 BMP 转换的质量！它快速、简单、安全且完全免费！以下 C# 示例演示了如何转换 EPUB 文档。我们描述了从文件中读取 EPUB 并使用默认保存选项将 EPUB 转换为 BMP 的源代码。请从本地文件系统加载 EPUB，选择输出格式并运行示例。您将立即将结果作为单独的文件获得。

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter EPUB BMP PDF DOCX "JPG|JPEG" PNG GIF TIFF XPS >}}
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
h2: 在 C# 中将 EPUB 转换为 BMP 的步骤
---

如果您想在您的产品中考虑转换功能，或者您想以编程方式将 EPUB 转换为 BMP，请参阅上面的 C# 代码示例或学习文档章节。在所有情况下，任何转换都需要一些强制性步骤：
1. 打开现有的 EPUB 文件。
1. 使用 BMP ImageFormat 创建一个新的 [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions) 对象。默认情况下，格式属性为 [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat)。
1. 使用Converter类的[ConvertEPUB()](https://reference.aspose.com/html/net/aspose.html.converters.converter/convertepub/methods/27)方法将EPUB保存为BMP图片.您需要将 EPUB 文件流、ImageSaveOptions 和输出文件路径传递给 ConvertEPUB() 方法以进行 EPUB 到 BMP 的转换。
1. BMP文件将保存到指定路径。

{{<section documentation>}}
---
h2: 文档中的 EPUB 到 BMP 转换
---

BMP 文件是用于存储高质量位图数字图像的位图图像文件。因此，有时可能需要将 EPUB 转换为 BMP。请访问文档文章 [将 EPUB 转换为 BMP](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) 了解更多关于 Aspose.HTML for .NET API转换功能并考虑最常见的 EPUB 到 BMP 转换方案的 C# 示例。在本文中，您可以找到有关如何使用 ConvertEPUB() 方法将 EPUB 转换为 BMP 以及如何应用 ImageSaveOptions 和 ICreateStreamProvider 参数的信息。
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/#convert-epub-to-bmp" target="_blank">将 EPUB 转换为BMP</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/#convert-epub-to-bmp-using-imagesaveoptions" target="_blank" >使用 ImageSaveOptions 将 EPUB 转换为 BMP</a>



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