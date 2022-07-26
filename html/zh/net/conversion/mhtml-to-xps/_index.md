---
translation: true
template: /templates/_template-conversion-child.md
title: 将 MHTML 转换为 XPS
description: 在 C# 中将 MHTML 转换为 XPS。在 ASP.NET 或任何 .NET 应用程序中轻松使用转换器 API。免费试用在线 MHTML 到 XPS 转换器！
url: /net/conversion/mhtml-to-xps/
family: html
platformtag: net
feature: conversion
informat: MHTML
outformat: XPS
otherformats: DOCX PDF GIF JPEG PNG TIFF BMP
---

{{<section banner>}}
---
h1: 通过 C# 将 MHTML 转换为 XPS
h2: 使用 .NET API 进行高保真 MHTML 到 XPS 的转换。使用我们的免费在线转换器立即将 MHTML 转换为 XPS 格式。
---

{{<section overview>}}
---
h2: 使用 C# 将 MHTML 转换为 XPS
---

要将 MHTML 转换为 XPS，我们将使用 [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API，这是一个功能丰富、功能强大且易于使用的文档操作和C# 平台的转换 API。 MHTML 转换通常需要利用其他格式。使用我们的高速库，您可以通过完全控制各种转换参数以编程方式将 MHTML 转换为 XPS。强大的 C# API 允许您快速、高质量地将 MHTML 转换为流行格式！

{{<section demos>}}
---
h2: 免费在线转换器现场演示
---

在您的浏览器中测试 MHTML 到 XPS 转换的质量！请从本地文件系统加载 MHTML 文件，从列表中选择所需的输出格式并运行示例。它快速、简单、安全且完全免费！ MHTML 到 XPS 的转换将使用默认保存选项完成。您将立即将结果作为单独的文件获得。因此，在线快速将任何网页或 MHTML 转换为 XPS 格式！

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MHTML XPS PDF DOCX "JPG|JPEG" GIF BMP TIFF PNG >}}
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
h2: 在 C# 中将 MHTML 转换为 XPS 的步骤
---

如果您想以编程方式将 MHTML 转换为 XPS，请执行几个必需的步骤：

1. 打开现有的 MHTML 文件。
1. 创建[XpsSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/xpssaveoptions/)类的实例。
1. 使用 Converter 的 [ConvertMHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertmhtml/#convertmhtml_29)方法 类将 MHTML 保存为 XPS 文件。您需要将 MHTML 文件流、XpsSaveOptions 和输出文件路径传递给 ConvertMHTML() 方法。
1. XPS文件将保存到指定路径。

{{<section documentation>}}
---
h2: 文档中的 MHTML 到 XPS 转换
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#mhtml-to-xps-by-two-lines-of-code" target="_blank">MHTML 转 XPS 两行代码</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#convert-mhtml-to-xps-using-xpssaveoptions" target="_blank" >使用 XpsSaveOptions 将 MHTML 转换为 XPS</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#output-stream-providers" target="_blank">使用将 MHTML 转换为 XPS MemoryStreamProvider</a>

XPS 是微软开发的一种文档存储和查看格式。它具有一系列支持安全功能的优势，例如提供更高文档安全性的数字签名等。请访问文档文章 [将 MHTML 转换为 XPS](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) 以了解有关 Aspose.HTML for .NET API 的更多信息转换功能，并考虑最常见的 MHTML 到 XPS 转换方案的 C# 示例。在本文中，您将找到有关如何使用 ConvertMHTML() 方法将 MHTML 转换为 XPS 以及如何应用 XpsSaveOptions 或 ICreateStreamProvider 参数的信息。

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