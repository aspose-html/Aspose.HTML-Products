---
translation: true
template: /templates/_template-conversion-child.md
title: 将 SVG 转换为 PNG
description: 在 C# 中将 SVG 转换为 PNG。在 ASP.NET 或任何 .NET 应用程序中轻松使用转换器 API。免费试用在线 SVG 到 PNG 转换器！
url: /net/conversion/svg-to-png/
family: html
platformtag: net
feature: conversion
informat: SVG
outformat: PNG
otherformats: PDF XPS GIF JPEG BMP TIFF
---

{{<section banner>}}
---
h1: 通过 C# 将 SVG 转换为 PNG
h2: 使用服务器端 .NET API 进行高保真 SVG 到 PNG 的转换。使用我们的免费在线转换器立即将 SVG 转换为 PNG 格式！
---

{{<section overview>}}
---
h2: 使用 C# 将 SVG 转换为 PNG
---

SVG 是一种用于创建二维矢量和混合矢量/光栅图形的 XML 语言。为了将 SVG 转换为 PNG，我们将使用 [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API，这是一个功能丰富、功能强大且易于使用的文档操作和 C# 平台的转换 API。 SVG 转换通常需要利用其他格式。使用我们的文档处理库，您可以以编程方式将 SVG 转换为 PNG 图像，只需几行代码即可完全控制各种转换选项。

{{<section demos>}}
---
h2: 免费在线转换器现场演示
---

在您的浏览器中测试 SVG 到 PNG 转换的质量！以下 C# 示例演示了如何转换 SVG 文档。我们描述了从文件中读取 SVG 并使用默认保存选项将 SVG 转换为 PNG 的源代码。请从本地文件系统加载 SVG，选择输出格式并运行示例。您将立即将结果作为单独的文件获得。所以，在线快速将 SVG 转换为 PNG 格式！

{{<section "app-pluging" i18n-exclude>}}

{{< app/svg/converter SVG PNG PDF XPS TIFF BMP "JPG|JPEG" GIF>}}
using Aspose.Html;
using Aspose.Html.Dom.Svg;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new SVGDocument("image.svg");
{{#if_output 'PDF'}}
    var options = new PdfSaveOptions();
{{/if_output}}
{{#if_output 'XPS'}}
    var options = new XpsSaveOptions();
{{/if_output}}
{{#if_output 'BMP' 'JPG' 'GIF' 'PNG' 'TIFF'}}
    var options = new ImageSaveOptions(ImageFormat.{{output param2 camel}});
{{/if_output}}
    Converter.ConvertSVG(document, options, "output.{{output lower}}");   
{{< /app/svg/converter>}}


{{<section steps>}}
---
h2: 在 C# 中将 SVG 转换为 PNG 的步骤
---
1. 使用 [SVGDocument](https://reference.aspose.com/html/net/aspose.html.dom.svg/svgdocument/) 类的 SVGDocument() 构造函数之一加载 SVG 文件。
1. 创建一个新的 [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) 对象。默认情况下，格式属性为 [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/)。
1. 使用[ConvertSVG()](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertsvg/#convertsvg_3)方法将SVG保存为PNG图片。您需要将 SVGDocument、ImageSaveOptions 和输出文件路径传递给 ConvertSVG() 方法。

{{<section documentation>}}
---
h2: 文档中的 SVG 到 PNG 转换
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/#svg-to-png-by-a-single-line-of-code " target="_blank">SVG 到 PNG 通过一行代码</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/#convert-svg-to-png-using-imagesaveoptions" target="_blank" >使用 ImageSaveOptions 将 SVG 转换为 PNG</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/#output-stream-providers" target="_blank">使用将 SVG 转换为 PNG MemoryStreamProvider</a>

PNG 文件格式支持无损图像压缩，使其在用户中很受欢迎。请访问文档文章 [将 SVG 转换为 PNG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/) 以了解有关 Aspose.HTML for .NET API 的更多信息转换功能，并考虑最常见的 SVG 到 PNG 转换方案的 C# 示例。在本文中，您将找到有关如何使用 ConvertSVG() 方法将 SVG 转换为 PNG 以及如何应用 ImageSaveOptions 的信息。

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
title: 其他支持的 SVG 转换
subTitle: "您还可以将 SVG 转换为许多其他文件格式："
---