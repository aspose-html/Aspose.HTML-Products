---
translation: true
template: /templates/_template-conversion-child.md
title: Convert MD to PNG
description: Sample C# code for MD to PNG conversion. Easily use converter API within ASP.NET or any .NET application. Try online MD to PNG Converter for free!
url: /net/conversion/md-to-png/
family: html
platformtag: net
feature: conversion
informat: MD
outformat: PNG
otherformats: PDF DOCX XPS BMP GIF JPEG TIFF HTML
---

{{<section banner>}}
---
h1: Convert MD to PNG via C#
h2: High-fidelity MD to PNG conversion using server-side .NET APIs. Instantly convert MD to PNG format with our free online converter!
---

{{<section overview>}}
---
h2: Convert MD to PNG Using C#
---

In order to convert MD to PNG, we’ll use [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API which is a feature-rich, powerful and easy to use document manipulation and conversion API for the C# platform. Conversions from Markdown to other formats go through the Markdown to HTML conversion stage. .NET developers can easily load & convert MD to PNG in just a few lines of code. Powerful C# API allows you to convert MD to popular formats quickly and in high quality!

{{<section demos>}}
---
h2: Free Online Converter Live Demos
---

Test the quality of MD to PNG conversion right in your browser! It's fast, easy, secure and completely free! The following C# example demonstrates how to convert an MD document. We describe the source code for reading MD from a file and then converting MD to PNG with default saving options. Please load MD from the local file system, select the output format and run the example. You will immediately get the result as a separate file.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MD PNG "JPG|JPEG" GIF BMP XPS TIFF PDF DOCX >}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = Converter.ConvertMarkdown("input.md");
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
    Converter.ConvertHTML(document, options, "output.{{output lower}}");   
{{< /app/html/converter>}}


{{<section steps>}}
---
h2: Steps to Convert MD to PNG in C#
---

1.  Specify a path to a source Markdown file.
1.  Convert Markdown to HTML. Use the [ConvertMarkdown(`sourcePath`)](https://apireference.aspose.com/html/net/aspose.html.converters.converter/convertmarkdown/methods/4) method to save Markdown as an HTML document.
1.  Create a new [ImageSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions) object. By default, the Format property is [PNG](https://apireference.aspose.com/html/net/aspose.html.rendering.image/imageformat).
1.  Use the [ConvertHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) method to render the intermediary HTML document to a PNG image. You need to pass the HTMLDocument, ImageSaveOptions, and output file path to the ConvertHTML() method.


{{<section documentation>}}
---
h2: MD to PNG Conversion in Documentation
---

PNG is one of the most used image file formats. It supports lossless image compression that makes it popular among its users. Thus, it may sometimes be necessary to convert MD to PNG image. Please visit the documentation article [Convert Markdown to Image](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) to learn more about Aspose.HTML for .NET API conversion features and to consider C# examples for the most common MD to PNG conversion scenarios. In the article, you will find information on how to <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/#convert-markdown-to-png" target="_blank">Convert Markdown to PNG</a> using ConvertMarkdown() methods and how to apply ImageSaveOptions.

{{<section online-converters>}}
---
h2: Free Online Converters
---

{{<section get-started>}}
---
h2: How to Install Aspose.HTML for .NET library
---

{{<section other-conversions>}}
---
title: Other Supported MD Conversions
subTitle: "You can also convert MD to many other file formats:"
---