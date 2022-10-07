---
translation: true
template: /templates/_template-conversion-child.md
title: 将 HTML 转换为 GIF
description: 在 C# 中将 HTML 转换为 GIF。在 ASP.NET 或任何 .NET 应用程序中轻松使用转换器 API。免费试用在线 HTML 到 GIF 转换器！
url: /net/conversion/html-to-gif/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: GIF
otherformats: PDF DOCX XPS JPEG PNG TIFF BMP XHTML MHTML MD
---

{{<section banner>}}
---
h1: 通过 C# 将 HTML 转换为 GIF
h2: 使用 .NET API 从 HTML 源页面生成 GIF。使用我们的免费在线转换器立即将 HTML 转换为 GIF 格式！
---

{{<section overview>}}
---
h2: 使用 C# 将 HTML 转换为 GIF
---

HTML 文件经常用于创建、编辑或传达大量信息。如果您需要在 PowerPoint 演示文稿中包含 HTML 文件或通过电子邮件发送它们，请将它们转换为适当的图像格式并根据需要使用！使用 [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API，您可以以编程方式将 HTML 转换为 GIF，并完全控制各种转换参数。 HTML 到 GIF 的转换有多种情况，例如从文件、URL、WYSISYG 编辑器、字符串或流中读取。强大的 C# API 允许您快速、高质量地将 HTML 转换为流行格式！

{{<section demos>}}
---
h2: 免费在线转换器现场演示
---

在您的浏览器中测试 HTML 到 GIF 转换的质量！请从本地文件系统加载 HTML 文件，从列表中选择所需的输出格式并运行示例。它快速、简单、安全且完全免费！ HTML 到 GIF 的转换将使用默认保存选项完成。您将立即将结果作为单独的文件获得。因此，在线快速将任何网页或 HTML 转换为 GIF 格式！

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML GIF BMP PDF MD "JPG|JPEG" DOCX XPS TIFF PNG MHTML >}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new HTMLDocument("{{input lower}}");
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
h2: 在 C# 中将 HTML 转换为 GIF 的步骤
---

如果您想在您的产品中考虑转换功能，或者您想以编程方式将 HTML 转换为 GIF，请参阅上面的 C# 代码示例或学习文档章节。在所有情况下，任何转换都需要一些强制性步骤：

1. 使用 [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/) 构造函数之一加载 HTML 文档。您可以从文件、HTML 代码、流或 URL 加载 HTML。
1. 使用 GIF ImageFormat 创建一个新的 [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) 对象。默认情况下，格式属性为 PNG。
1. 使用Converter类的[ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/)方法将HTML保存为GIF文件。您需要将 HTMLDocument、ImageSaveOptions 和输出文件路径传递给 ConvertHTML() 方法。
1. GIF 文件将被保存到指定路径。

{{<section documentation>}}
---
h2: 文档中的 HTML 到 GIF 转换
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/#convert-html-to-gif" target="_blank">将 HTML 转换为动图</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/#convert-html-to-gif-in-c-using-imagesaveoptions" target="_blank">使用 ImageSaveOptions 将 HTML 转换为 GIF</a>

GIF 是一种流行的图像格式，它支持动画图像，并且经常用于网络发布。 HTML 到 GIF 转换允许您将 HTML 文档另存为 GIF 图像。请访问文档文章 [将 HTML 转换为 GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/) 了解更多关于 Aspose.HTML for .NET API转换功能并考虑最常见的 HTML 到 GIF 转换方案的 C# 示例。在本文中，您可以找到有关如何使用 ConvertHTML() 方法将 HTML 转换为 GIF 以及如何应用 ImageSaveOptions 和 ICreateStreamProvider 参数的信息。

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