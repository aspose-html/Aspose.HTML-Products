﻿---
translation: true
template: /templates/_template-conversion-child.md
title: 将 MHTML 转换为 TIFF
description: 在 C# 中将 MHTML 转换为 TIFF。在 ASP.NET 或任何 .NET 应用程序中轻松使用转换器 API。免费试用在线 MHTML 到 TIFF 转换器！
url: /net/conversion/mhtml-to-tiff/
family: html
platformtag: net
feature: conversion
informat: MHTML
outformat: TIFF
otherformats: DOCX PDF XPS BMP GIF JPEG PNG
---

{{<section banner>}}
---
h1: 通过 C# 将 MHTML 转换为 TIFF
h2: 使用 .NET API 进行高保真 MHTML 到 TIFF 的转换。使用我们的免费在线转换器立即将 MHTML 转换为 TIFF 格式。
---

{{<section overview>}}
---
h2: 使用 C# 将 MHTML 转换为 TIFF
---

要将 MHTML 转换为 TIFF，我们将使用 [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API，这是一个功能丰富、功能强大且易于使用的文档操作和C# 平台的转换 API。 MHTML 转换通常需要利用其他格式。使用我们的高速库，您可以以编程方式将 MHTML 转换为 TIFF，并完全控制各种转换参数。强大的 C# API 允许您快速、高质量地将 MHTML 转换为流行格式！

{{<section demos>}}
---
h2: 免费在线转换器现场演示
---

在您的浏览器中测试 MHTML 到 TIFF 转换的质量！请从本地文件系统加载 MHTML 文件，从列表中选择所需的输出格式并运行示例。它快速、简单、安全且完全免费！ MHTML 到 TIFF 的转换将使用默认保存选项完成。您将立即将结果作为单独的文件获得。因此，在线快速将任何网页或 MHTML 转换为 TIFF 格式！

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MHTML TIFF GIF BMP "JPG|JPEG" PNG DOCX PDF XPS >}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var stream = File.OpenRead("sample.mht");
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
    Converter.ConvertMHTML(stream, options, "output.{{output lower}}");   
{{< /app/html/converter>}} 


{{<section steps>}}
---
h2: 在 C# 中将 MHTML 转换为 TIFF 的步骤
---

如果您想以编程方式将 MHTML 转换为 TIFF，请执行几个必需的步骤：

1. 打开现有的 MHTML 文件。
1. 使用 TIFF ImageFormat 创建一个新的 [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) 对象。默认情况下，格式属性为 [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/)。
1. 使用Converter类的[ConvertMHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertmhtml/)方法将MHTML保存为TIFF图像。
1. TIFF 文件将被保存到指定路径。

{{<section documentation>}}
---
h2: 文档中的 MHTML 到 TIFF 转换
---

MHTML 到 TIFF 转换允许您将 MHTML 文档另存为 TIFF 图像。请访问文档文章 [Convert MHTML to Image](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-image/) 了解更多关于 Aspose.HTML for .NET API转换功能并考虑最常见的 MHTML 到 TIFF 转换方案的 C# 示例。在本文中，您将找到有关如何 <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-image/#convert-mhtml-to-tiff " target="_blank">使用 ConvertMHTML() 方法将 MHTML 转换为 TIFF</a> 以及如何应用 ImageSaveOptions。

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
title: 其他支持的 MHTML 转换
subTitle: "您还可以将 MHTML 转换为许多其他文件格式："
---