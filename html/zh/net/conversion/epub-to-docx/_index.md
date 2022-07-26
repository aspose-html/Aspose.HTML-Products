---
translation: true
template: /templates/_template-conversion-child.md
title: 将 EPUB 转换为 DOCX
description: EPUB 到 DOCX C# 转换的示例代码。在 ASP.NET 或任何 .NET 应用程序中轻松使用转换器 API。免费试用在线 EPUB 到 DOCX 转换器！
url: /net/conversion/epub-to-docx/
family: html
platformtag: net
feature: conversion
informat: EPUB
outformat: DOCX
otherformats: PDF DOCX XPS GIF JPEG PNG TIFF BMP
---

{{<section banner>}}
---
h1: 通过 C# 将 EPUB 转换为 DOCX
h2: 使用 .NET API 从 EPUB 源文件生成 DOCX。使用我们的免费在线转换器立即将 EPUB 转换为 DOCX 格式！
---

{{<section overview>}}
---
h2: 使用 C# 将 EPUB 转换为 DOCX
---

为了将 EPUB 转换为 DOCX，我们将使用 [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API，这是一个功能丰富、功能强大且易于使用的文档C# 平台的操作和转换 API。 EPUB 是一种基于 XML 的开放格式，用于数字图书和出版物，可以在各种设备上查看和阅读。 DOCX 是一种众所周知的 Microsoft Word 文档格式。这种格式很受欢迎，因为它支持广泛的格式设置功能，并为用户提供了多种选项来编写任何类型的文档。 .NET 开发人员只需几行代码即可轻松加载 EPUB 并将其转换为 DOCX。

{{<section demos>}}
---
h2: 免费在线转换器现场演示
---

直接在您的浏览器中测试 EPUB 到 DOCX 转换的质量！它快速、简单、安全且完全免费！以下 C# 示例演示了如何转换 EPUB 文档。我们描述了从文件中读取 EPUB 并使用默认保存选项将 EPUB 转换为 DOCX 的源代码。请从本地文件系统加载 EPUB，选择输出格式并运行示例。您将立即将结果作为单独的文件获得。

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter EPUB DOCX PDF "JPG|JPEG" PNG GIF TIFF XPS BMP >}}
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
h2: 在 C# 中将 EPUB 转换为 DOCX 的步骤
---

如果您想在您的产品中考虑转换功能，或者您想以编程方式将 EPUB 转换为 DOCX，请参阅上面的 C# 代码示例或学习文档章节。在所有情况下，任何转换都需要一些强制性步骤：

1. 打开现有的 EPUB 文件。
1. 创建一个新的 [DocSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/docsaveoptions/) 对象。
1. 使用Converter类的[ConvertEPUB()](https://reference.aspose.com/html/net/aspose.html.converters.converter/convertepub/)方法将EPUB保存为DOCX文件.您需要将 EPUB 文件流、DocSaveOptions 和输出文件路径传递给 ConvertEPUB() 方法以进行 EPUB 到 DOCX 的转换。
1. DOCX 文件将保存到指定路径。

{{<section documentation>}}
---
h2: 文档中的 EPUB 到 DOCX 转换
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#epub-to-docx-by-two-lines-of-code" target="_blank">两行代码EPUB转DOCX</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#convert-epub-to-docx-using-docsaveoptions" target="_blank" >使用 DocSaveOptions 将 EPUB 转换为 DOCX</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers" target="_blank">使用将 EPUB 转换为 DOCX MemoryStreamProvider</a>

EPUB 格式作为基于 XML 的电子书格式而广受欢迎，旨在使内容的呈现方式适应阅读器设备。 EPUB 到 DOCX 的转换通常需要利用 DOCX 格式来完成特定的用户任务。请访问文档文章 [将 EPUB 转换为 DOCX](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) 以了解有关 Aspose.HTML for .NET API 的更多信息转换功能并考虑最常见的 EPUB 到 DOCX 转换方案的 C# 示例。在本文中，您可以找到有关如何使用 ConvertEPUB() 方法将 EPUB 转换为 DOCX 以及如何应用 DocSaveOptions 和 ICreateStreamProvider 参数的信息。

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