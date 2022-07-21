---
translation: true
template: /templates/_template-conversion-child.md
title: 将 MHTML 转换为 DOCX
description: 在 C# 中将 MHTML 转换为 DOCX。在 ASP.NET 或任何 .NET 应用程序中轻松使用转换器 API。免费试用在线 MHTML 到 DOCX 转换器！
url: /net/conversion/mhtml-to-docx/
family: html
platformtag: net
feature: conversion
informat: MHTML
outformat: DOCX
otherformats: PDF XPS GIF JPEG PNG TIFF BMP
---

{{<section banner>}}
---
h1: 通过 C# 将 MHTML 转换为 DOCX
h2: 使用 .NET API 进行高保真 MHTML 到 DOCX 的转换。使用我们的免费在线转换器立即将 MHTML 转换为 DOCX 格式。
---

{{<section overview>}}
---
h2: 使用 C# 将 MHTML 转换为 DOCX
---

要将 MHTML 转换为 DOCX，我们将使用 [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API，这是一个功能丰富、功能强大且易于使用的文档操作和C# 平台的转换 API。 MHTML 转换通常需要利用其他格式。使用我们的高速库，您可以以编程方式将 MHTML 转换为 DOCX，并完全控制各种转换参数。强大的 C# API 允许您快速、高质量地将 MHTML 转换为流行格式！

{{<section demos>}}
---
h2: 免费在线转换器现场演示
---

在您的浏览器中测试 MHTML 到 DOCX 转换的质量！请从本地文件系统加载 MHTML 文件，从列表中选择所需的输出格式并运行示例。它快速、简单、安全且完全免费！ MHTML 到 DOCX 的转换将使用默认保存选项完成。您将立即将结果作为单独的文件获得。因此，在线快速将任何网页或 MHTML 转换为 DOCX 格式！

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MHTML DOCX PDF "JPG|JPEG" GIF BMP XPS TIFF PNG >}}
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
h2: 在 C# 中将 MHTML 转换为 DOCX 的步骤
---

如果您想以编程方式将 MHTML 转换为 DOCX，请执行几个必要的步骤：

1. 打开现有的 MHTML 文件。
1. 创建 [DocSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/docsaveoptions) 类的实例。
1. 使用[Converter](https://reference)的[ConvertMHTML()](https://reference.aspose.com/html/net/aspose.html.converters.converter/convertmhtml/methods/29)方法.aspose.com/html/net/aspose.html.converters/converter) 类将 MHTML 保存为 DOCX 文件。您需要将 MHTML 文件流、DocSaveOptions 和输出文件路径传递给 ConvertMHTML() 方法。
1. DOCX 文件将保存到指定路径。

{{<section documentation>}}
---
h2: 文档中的 MHTML 到 DOCX 转换
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#mhtml-to-docx-by-two-lines-of-code" target="_blank">MHTML 转 DOCX 两行代码</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#convert-mhtml-to-docx-using-docsaveoptions" target="_blank" >使用 DocSaveOptions 将 MHTML 转换为 DOCX</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#output-stream-providers" target="_blank">使用将 MHTML 转换为 DOCX MemoryStreamProvider</a>

MHTML 到 DOCX 的转换通常需要利用 DOCX 格式来完成特定任务。 DOCX 格式很受欢迎，因为它支持广泛的格式设置功能，并为用户提供了多种选项来编写任何类型的文档。请访问文档文章 [将 MHTML 转换为 DOCX](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/) 以了解有关 Aspose.HTML for .NET API 的更多信息转换功能，并考虑最常见的 MHTML 到 DOCX 转换方案的 C# 示例。在本文中，您将找到有关如何使用 ConvertMHTML() 方法将 MHTML 转换为 DOCX 以及如何应用 DocSaveOptions 或 ICreateStreamProvider 参数的信息。

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