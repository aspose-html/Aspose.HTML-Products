---
translation: true
template: /templates/_template-conversion-child.md
title: Convert HTML to JPEG
description: Convert HTML to JPEG in C#. Easily use converter API within ASP.NET or any .NET application. Try online HTML to JPEG Converter for free!
url: /net/conversion/html-to-jpeg/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: JPEG
otherformats: PDF DOCX XPS GIF PNG TIFF BMP XHTML MHTML MD 
---

{{<section banner>}}
---
h1: Convert HTML to JPEG via C#
h2: Generate JPEG from HTML source page using .NET API. Instantly convert HTML to JPEG format with our free online converter!
---

{{<section overview>}}
---
h2: Convert HTML to JPEG Using C#
---

HTML files are frequently used to create, edit, or communicate a lot of information. If you need to include HTML files in a PowerPoint presentation or send them by email, please convert them to the appropriate image format and use as you want! With [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API, you can transform HTML to JPEG programmatically with full control over a wide range of conversion parameters. There are various cases for HTML to JPEG conversion like reading from a file, URL, WYSISYG Editor, string, or stream. Powerful C# API allows you to convert HTML to popular formats quickly and in high quality!

{{<section demos>}}
---
h2: Free Online Converter Live Demos
---

Test the quality of HTML to JPEG conversion right in your browser! Please load an HTML file from the local file system, select the required output format from the list and run the example. It's fast, easy, secure and completely free! The HTML to JPEG conversion will be done with the default save options. You will immediately get the result as a separate file. So, quickly convert any webpage or HTML to JPEG format online!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML "JPG|JPEG" BMP PDF MD  GIF DOCX XPS TIFF PNG MHTML >}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new HTMLDocument("document.{{input lower}}");
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
h2: Steps to Convert HTML to JPEG in C#
---

If you would like to consider conversion functionality in your product or you want to convert HTML to JPEG programmatically, please see the C# code example above or learn the Documentation chapter. In all cases, any conversion requires some mandatory steps:

1.  Load an HTML document using one of [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument) constructors. You can load HTML from a file, HTML code, stream, or URL.
1.  Create a new [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions) object with JPEG ImageFormat. By default, the Format property is PNG.
1.  Use the [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) method of the Converter class to save HTML as a JPEG file. You need to pass the HTMLDocument, ImageSaveOptions, and output file path to the ConvertHTML() method.
1.  The JPEG file will be saved to the specified path.


{{<section documentation>}}
---
h2: HTML to JPEG Conversion in Documentation
---

JPEG is one of the most commonly used image formats. Its uniqueness is the controlled loss of quality during compression. This compression feature allows you to quickly and efficiently share JPG images and use them widely on the Web, computers, and mobile devices. Converting HTML files to the JPG image may be required, for example, if you want to add a web page in a PowerPoint presentation or send it by e-mail. Please visit the documentation article [Convert HTML to JPEG](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpeg/) to learn more about Aspose.HTML for .NET API conversion features and to consider C# examples for the most common HTML to JPEG conversion scenarios. In the article, you find information on how to convert HTML to JPEG using ConvertHTML() methods, and how to apply ImageSaveOptions and ICreateStreamProvider parameters.
  -  <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#html-to-jpg-by-a-single-line-of-code" target="_blank">HTML to JPG by a single line of code</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#convert-html-to-jpg-using-imagesaveoptions" target="_blank">Convert HTML to JPG using ImageSaveOptions</a>
   - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#output-stream-providers" target="_blank">Convert HTML to JPG using MemoryStreamProvider</a>  

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
title: Other Supported HTML Conversions
subTitle: "You can also convert HTML to many other file formats:"
---