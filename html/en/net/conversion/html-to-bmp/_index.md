---
translation: true
title: Convert HTML to BMP using C#
description: Convert HTML to BMP using C# or VB.NET. Easily use HTML to BMP converter API within ASP.NET or any .NET application.
url: /net/conversion/html-to-bmp/
---


{{<section banner>}}
---
h1: Convert HTML to BMP via C#
h2: High-fidelity conversion of HTML pages as BMP using server-side .NET APIs.
---


{{<section overview>}}
---
h2: How to Convert HTML to BMP Using C#
---

HTML files are frequently used to create, edit, or communicate a lot of information. If you need to include HTML files in a PowerPoint presentation or send them by email, please transform them to the appropriate image format and use them as you want! With [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API, you can convert HTML to BMP format programmatically with full control over a wide range of conversion parameters. It can be different scenarios, but it can be made with a few required steps:

### Steps to Convert HTML to BMP via C# 

1.  Load an HTML document using one of [HTMLDocument()](https://apireference.aspose.com/html/net/aspose.html/htmldocument) constructors. You can load HTML from a file, HTML code, stream, or URL.
1.  Create a new [ImageSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions) object with BMP ImageFormat. By default, the Format property is [PNG](https://apireference.aspose.com/html/net/aspose.html.rendering.image/imageformat).
1.  Use the [ConvertHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) method of the Converter class to save XHTML as a BMP file. You need to pass the HTMLDocument, ImageSaveOptions, and output file path to the ConvertHTML() method.
1.  The BMP file will be saved to the specified path.


{{<section "demos">}}
---
h2: Free Online Converter Live Demos
---

Test the quality of HTML to BMP conversion right in your browser! The following C# example demonstrates how to convert an HTML document. We describe the source code for reading HTML from a file and then converting HTML to BMP with default saving options. Please load HTML from the local file system, select the output format and run the example. You will immediately get the result as a separate file.

{{<section "demos.pluging" i18n-exclude>}}

{{< app/html/converter HTML BMP XPS TIFF PNG PDF "JPG|JPEG" GIF DOCX MD>}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new HTMLDocument("document.{{input lower}}");
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
    var options = new ImageSaveOptions(ImageFormat.{{output param2 camel}});
{{/if_output}}
    Converter.ConvertHTML(document, options, "output.{{output lower}}");   
{{< /app/html/converter>}}