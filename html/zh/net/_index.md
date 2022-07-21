---
translation: true
template: /templates/_template-net.md
title: C# HTML Parser - 用于 HTML 文件处理的 .NET API
weight: 20
url: /net/
description: C# .NET API 用于读取、写入、修改、编辑、合并和转换 HTML、XHTML、MHTML、EPUB、Markdown 和 SVG。
---

{{<section banner>}}
---
h1: 用于解析 HTML 文件的 C# API
h2: 用于处理真实世界 HTML 的类库。创建、编辑、提取数据、合并 HTML 页面并将其转换为 PDF、DOCX、XPS、图像和其他格式。
---

{{<section overview>}}
---
item1: <a href="https://docs.aspose.com/html/net/working-with-documents/creating-a-document/" target="_blank">创建或加载基于 HTML 的文档</a>文件、URL、字符串或流。
item2: 在流行格式之间<a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">转换文档</a>。
item3: <a href="https://docs.aspose.com/html/net/message-handlers/" target="_blank">创建自定义消息处理程序</a>以执行特定任务。
item4: <a href="https://docs.aspose.com/html/net/how-to-articles/how-to-use-xpath/" target="_blank">使用 XPath 查询导航 HTML 文档</a>或 CSS 选择器。
item5: <a href="https://docs.aspose.com/html/net/working-with-documents/editing-a-document/" target="_blank">编辑 HTML 文件</a> 通过插入新节点，删除或编辑现有节点的内容。
item6: <a href="https://docs.aspose.com/html/net/converting-between-formats/fine-tuning-converters/" target="_blank">高质量渲染文档</a>，
item7: 和更多。
---

Aspose.HTML for .NET 是一种高级 HTML 处理 API，用于在跨平台应用程序中执行广泛的管理和操作任务。 API 旨在创建、修改、提取数据、转换和呈现 HTML 文档，而无需任何外部软件。此外，它还支持流行的文件格式，如 EPUB、MHTML、XML、SVG 和 Markdown，以及呈现为 PDF、DOCX、XPS 和图像文件格式。 Aspose.HTML for .NET 完全用 C# 编写，可用于构建任何类型的 32 位或 64 位 .NET 应用程序，包括 ASP.NET、WCF、WinForms 和 .NET Core。<br><br>

此外，HTML 文档对象模型集成了嵌入式格式和规范，例如 CSS、HTML Canvas、SVG、XPath 和 JavaScript，开箱即用，扩展了操作功能和渲染质量。您可以在我们的<a href="https://docs.aspose.com/html/net/getting-started/" target="_blank">文档</a>中查看完整的 Aspose.HTML 功能列表。在您的项目中使用 Aspose.HTML C# 库允许您执行以下任务：


{{<section glance>}}
---
h3: 乍看上去
description: Aspose.HTML for .NET API 概述。
---

{{<section platform>}}
---
h3: 平台独立性
description: Aspose.HTML for .NET 支持 .NET 框架和 .NET 标准。
---

{{<section formats>}}
---
h3: 支持的文件格式
description: Aspose.HTML for .NET [支持的格式](https://docs.aspose.com/html/net/supported-file-formats/) 如下所列。
---

{{<section feature>}}
---
title: 高级 .NET HTML API 功能
feature1: 从头开始创建 HTML 页面
feature2: 从文件、流或 URL 加载现有 HTML
feature3: 实施 W3C 规范
feature4: 使用模板合并实现模板
feature5: 用各种数据源填充模板
feature6: 将 HTML Canvas 2D 渲染为 PDF
feature7: 添加、替换或删除节点
feature8: 从 HTML 文档中提取数据
feature9: 加载 EPUB 和 MHTML 文件格式
feature10: 将 HTML 渲染为光栅图像格式
feature11: 一次渲染多个文档
feature12: <a href="/html/{{lang.url-fragment}}net/conversion/md-to-html">实现 Markdown 到 HTML 转换器</a>
feature13: 在 HTML 到 PDF 期间应用页眉和页脚
feature14: 使用 XPath 查询或 CSS 选择器导航 HTML
feature15: <a href="/html/{{lang.url-fragment}}net/conversion/">格式之间的广泛转换</a>
---

{{<section converter>}}
---
h2: 在 C# 中将 HTML 转换为 PDF、图像和其他格式
h3: 将 HTML 转换为 PDF - C#
---
   
C# API 只需几行代码就可以为您的 .NET 应用程序实现 HTML 到 PDF、HTML 到图像或任何其他转换。转换过程简单可靠，因此使 Aspose.HTML for .NET API 成为完美的选择。

{{<section "code" i18n-exclude>}}
     
using Aspose.HTML;
using Aspose.HTML.Saving;
using Aspose.HTML.Converters;
...
    
    // Load an HTML file to be converted
    using var document = new HTMLDocument("input.html")
    
    // Create an instance of the PdfSaveOptions class
    var pdfSaveOptions = new PdfSaveOptions();    
    
    // Convert HTML to PDF
    Converter.ConvertHTML(document, pdfSaveOptions, "output.pdf");
    

{{<section online-converters>}}

您可以在 <a href="https://products.aspose.app/html/conversion/html" rel="opener noopener noreferrer" target="_blank"> 此处尝试在线 HTML 转换器。</a>

{{<section other-converters>}}

您还可以将 HTML、XHTML、MHTML、Markdown、EPUB 或 SVG 转换为许多其他文件格式，包括下面列出的几种文件格式：

{{<section edit-html>}}
---
h2: 编辑 HTML 文档
---

Aspose.HTML for .NET 允许您使用文档对象模型 (DOM) 创建和编辑 HTML 文档。 DOM 是 HTML 文档的编程接口，将文档（作为节点和对象）表示为节点树，其中每个节点代表文档的一部分。 Aspose.HTML for .NET API 允许您连接到页面并可以更改文档结构、样式和内容。您可以通过插入新节点以及删除或编辑现有节点的内容来修改文档。<br><br>
    
 - 使用各种方法导航 HTML 文档，例如元素遍历、文档遍历、XPath 查询和 CSS 选择器查询，<br>
 - 删除和替换 HTML 节点，<br>
 - 从 HTML 中提取和编辑 CSS，<br>
 - 配置文档沙箱等。

.NET HTML API 帮助开发人员阅读、修改、导航和编辑 (X)HTML 文档。 Aspose.HTML for .NET API 可以执行的一些文件编辑功能如下：<br>

{{<section markdown>}}
---
h2: 降价支持
h3: 将 HTML 转换为 Markdown - C#
h3-md: 将 Markdown 转换为 HTML - C#
---

Markdown 是一种具有纯文本格式语法的标记语言。 Markdown 通常用作文档和自述文件的格式，因为它允许以易于阅读和易于编写的风格进行编写。 Aspose.HTML 提供了一个强大而灵活的 Markdown 转换器，可以双向转换从 Markdown 到 HTML 和从 HTML 到 Markdown。此外，转换器 API 具有一组预定义的规则，因此您可以使用正宗的 Markdown 语法、GitLab Flavored Markdown 修改将 HTML 转换为 Markdown，甚至可以根据需要配置规则。

{{<section markdown-reverse>}}

反向转换就是这么简单！在您的 C# 应用程序中使用 Aspose.HTML 类库，您只需一行代码即可轻松地将 Markdown 转换为 HTML 文件！

{{<section "code-markdown1" i18n-exclude>}}
     
using Aspose.Html;
using Aspose.HTML.Saving;
...
    
	// Load an HTML file
	using var document = new HTMLDocument("document.html");

	// Convert HTML to Markdown using a set of features supported by GitLab Flavored Markdown
	document.Save("output.md", MarkdownSaveOptions.Git);

{{<section "code-markdown2" i18n-exclude>}}
     
using Aspose.Html.Converters;
...	

	// Convert Markdown to HTML
	Converter.ConvertMarkdown("document.md", "output.html");

{{<section markdown-online>}}

您可以在 <a href="https://products.aspose.app/html/conversion/md" rel="opener noopener noreferrer" target="_blank"> 此处尝试在线 Markdown 转换器。</a> 您可以转换 Markdown转换为 PDF、XPS、DOCX、JPG、PNG、BMP、TIFF、GIF 和 MHTML。上传、转换您的文档并在几秒钟内获得结果。您不需要任何额外的软件。

{{<section epub-mhtml>}}
---
h2: 电子书和网络档案
h3-epub: 将 EPUB 转换为 PDF - C#
h3-mhtml: 将 MHTML 转换为 PDF - C#
---

Aspose.HTML for .NET 能够加载 ePub 和 MHTML 文件以执行各种操作，包括转换为固定布局和光栅图像格式。


{{<section "code-epub" i18n-exclude>}}
     
using Aspose.Html.Converters;
using Aspose.Html.Saving;
...
    
	// Open an existing EPUB file for reading
     using var stream = File.OpenRead("input.epub");     
    
     // Create an instance of PdfSaveOptions
     var options = new PdfSaveOptions();
    
     // Call the ConvertEPUB method to convert EPUB to PDF
     Converter.ConvertEPUB(stream, options, "output.pdf"); 	 

{{<section "code-mhtml" i18n-exclude>}}
     
using Aspose.Html.Converters;
using Aspose.Html.Saving;
...   
	
	 // Open an existing MHTML file for reading
     using var stream = File.OpenRead("input.mht");     
    
     // Create an instance of PdfSaveOptions
     var options = new PdfSaveOptions();
    
     // Call the ConvertMHTML method to convert MHTML to PDF
     Converter.ConvertMHTML(stream, options, output.pdf); 

{{<section epub-mhtml-online>}}

您可以在线尝试<a href="https://products.aspose.app/html/conversion/mhtml" rel="opener noopener noreferrer" target="_blank">MHTML Converter</a>和在线<a href= "https://products.aspose.app/html/conversion/epub" rel="opener noopener noreferrer" target="_blank"> EPUB 转换器。</a> 我们基于浏览器的转换工具适用于所有平台，包括 Windows 、Linux、Mac OS、Android 和 iOS。转换器与所有 PC 设备、智能手机和平板电脑兼容。

{{<section web-scraping>}}
---
h2: 网页抓取
h3: 简单的 Web 数据提取 - C#
---	
	
网络抓取，也称为网络收获、网络数据提取或网络爬虫，是一种从网站中提取数据的技术。 Aspose.HTML 不支持开箱即用的 Web Scraping 模块。但是，使用完全基于 W3C 规范并支持 XPath 和 CSS 选择器查询的 Aspose.HTML API，您可以轻松检查任何 HTML 文档的内容并创建自己的 Web Scraping 解决方案。

{{<section "code-web-scraping" i18n-exclude>}}
     
using Aspose.Html;
...

    // Create an instance of the HTML document with a website as a parameter
    using var document = new Aspose.Html.HTMLDocument("https://en.wikipedia.org/wiki/Aspose_API");

    // Get all anchor-elements
    var elements = document.QuerySelectorAll("a");

    // Dump the anchor-element data to the console
    elements.Cast&lt;HTMLAnchorElement&gt;().ToList().ForEach(x =&gt;
        {
            System.Console.WriteLine("[Href]: " + x.Href);
            System.Console.WriteLine("[Content]: " + x.TextContent);
        });

{{<section online-web-scraping>}}

Aspose.HTML 提供免费的在线 <a href="https://products.aspose.app/html/data-scrapers" rel="opener noopener noreferrer" target="_blank">Data Scrapers 应用程序</a>从网站获取数据的方法。我们的应用程序是安全的，可以在任何平台上运行，并且不需要安装任何软件。数据抓取器可用于图像提取、从网页中获取关键字等。它们使用简单明了，但功能强大且可靠。

{{<section learning>}}
---
tabTitle: 学习资源
name1: 文档
name2: 源代码
name3: API 参考
name4: 教程视频
---

{{<section support>}}
---
tabTitle: 产品支持
name1: 免费支持
name2: 付费支持
name3: 博客
name4: 发行说明
---

{{<section why>}}
---
tabTitle: 为什么 Aspose.HTML 用于 .NET？
name1: 客户名单
name2: 成功的故事
description: "Aspose.HTML 为其他流行的开发环境提供单独的 HTML 处理 API，如下所列："
---