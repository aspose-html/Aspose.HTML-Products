---
translation: true
template: /templates/_template-conversion.md
title: 使用 C# 转换 HTML、XHTML、Markdown、MHTML、EPUB 和 SVG
url: /net/conversion/
description: 通过 .NET 库使用几行 C# 代码将 HTML 转换为 XHTML、PDF、DOCX、XPS、Markdown、MHTML 和图像。免费在线查看 HTML 转换器！
---

{{<section banner>}}
---
h1: 通过 C# 进行 HTML 转换
h2: 将超文本标记语言 HTML 转换为 XHTML、MHTML、Markdown、PDF、XPS、DOCX 和图像，包括 BMP、JPG、PNG、TIFF，以构建跨平台的 .NET 应用程序
---

{{<section overview>}}
---
h2: 如何使用 C# 转换 HTML
---

超文本标记语言 HTML 是 Web 的语言。目前，大多数信息都以网页的形式呈现在网站上。因此，将这种基于 HTML 的信息转换为其他格式，如 PDF、XPS、Microsoft® Word、Markdown 和图像格式是一种常见的情况。 [.NET HTML API](https://products.aspose.com/html/net/) 使开发人员的转换过程更容易。它使用 HTMLDocument 类加载文件，创建相关的保存选项对象并使用 [Converter 类](https://reference.aspose.com/html/net/aspose.html.converters/converter) 相关的转换方法。<br><br>
您要执行的任何转换都涉及加载 HTML 文档并将其保存为支持的格式。它可以是不同的场景，但可以通过几个必要的步骤来完成：<br>
 1. 使用 [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument) 构造函数之一将 HTML 文档加载到 Document 对象中。您可以从文件、HTML 代码、流或 URL 加载 HTML。
 2. 创建一个保存选项对象。
 3. 调用 [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) 方法之一并将所需的参数传递给它。

{{<section demos>}}
---
h2: HTML 转换器现场演示
---

您可以使用 Aspose.HTML for .NET API 实时转换 HTML。以下 C# 示例演示了如何转换 HTML 文档。请从本地文件系统加载文件，选择输出格式并运行示例。您将立即得到结果。您可以在<a href="https://products.aspose.app/html/conversion/html" rel="opener noopener noreferrer" target="_blank">这里尝试免费在线转换器。</a>

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML PDF DOCX MD BMP "JPG|JPEG" PNG GIF TIFF XPS>}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new HTMLDocument("input.{{input lower}}");
{{#if_output 'PDF'}}
    var options = new PdfSaveOptions();
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
    var options = new ImageSaveOptions(ImageFormat.{{output camel}});
{{/if_output}}
    Converter.ConvertHTML(document, options, "output.{{output lower}}");
{{< /app/html/converter>}}

{{<section documentation>}}
---
h2: ''
article1: 将 HTML 转换为 PDF
article2: 将 HTML 转换为 XPS
article3: 将 HTML 转换为 DOCX
article4: 将 HTML 转换为 MHTML
article5: 将 HTML 转换为 Markdown
article6: 将 HTML 转换为 BMP
article7: 将 HTML 转换为 PNG
article8: 将 HTML 转换为 JPG
article9: 将 HTML 转换为 TIFF
---

Aspose.HTML .NET API 的主要亮点是转换功能。出于各种原因，需要在格式之间进行转换：以熟悉、方便的格式工作，或利用不同格式完成特定任务。 [Aspose.Html.Converters](https://reference.aspose.com/html/net/aspose.html.converters) 命名空间实现了对转换方法的轻松访问。它提供广泛的 HTML 到流行格式的转换，例如 PDF、XPS、DOCX、JPEG、PNG、BMP、TIFF、GIF、MHTML 和 MD。请访问文档章节 [Converting Between Formats](https://docs.aspose.com/html/net/converting-between-formats/) 了解有关 Aspose.HTML for .NET API 转换功能的更多信息。

{{<section installing>}}
---
h2: 为 .NET 库安装 Aspose.HTML
---

该库支持解析 HTML5、CSS3、SVG 和 HTML Canvas，以构建基于 WHATWG DOM 标准的文档对象模型 (DOM)。您可以使用多种方法在您的系统上安装适用于 .NET 的 Aspose.HTML 库：</br>

1. 使用 NuGet 包管理器 GUI。
2. 使用包管理器控制台。
3. 通过 MSI 安装 Aspose.HTML for .NET。</br>

有关 C# 库安装的更多详细信息，请参阅 [Aspose.HTML 文档](https://docs.aspose.com/html/net/getting-started/installation/)。

{{<section other-conversions>}}
---
h2: 其他支持的转换
---

您还可以将 HTML、XHTML、MHTML、EPUB、Markdown 和 SVG 文件转换为许多其他文件格式，包括下面列出的几种文件格式：