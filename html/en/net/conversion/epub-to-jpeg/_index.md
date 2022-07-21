---
translation: true
template: /templates/_template-conversion-child.md
title: Convert EPUB to JPEG - C#
description: Sample C# code for EPUB to JPEG conversion. Easily use converter API within ASP.NET or any .NET application. Try online EPUB to JPEG Converter for free!
url: /net/conversion/epub-to-jpeg/
family: html
platformtag: net
feature: conversion
informat: EPUB
outformat: JPEG
otherformats: PDF DOCX XPS BMP GIF PNG TIFF
---

{{<section banner>}}
---
h1: Convert EPUB to JPEG via C#
h2: Generate JPEG from EPUB source file using .NET API. Instantly convert EPUB to JPEG format with our free online converter!
---

{{<section overview>}}
---
h2: Convert EPUB to JPEG Using C#
---

In order to convert EPUB to JPEG, we’ll use [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API which is a feature-rich, powerful and easy to use document manipulation and conversion API for the C# platform. EPUB is an open XML-based format for digital books and publications that can be viewed and read on a variety of devices. EPUB conversions are often required to take advantage of other formats. You can transform EPUB to JPEG programmatically with full control over a wide range of conversion parameters. Powerful C# API allows you to convert EPUB to popular formats quickly and in high quality!

{{<section demos>}}
---
h2: Free Online Converter Live Demos
---

Test the quality of EPUB to JPEG conversion right in your browser! It's fast, easy, secure and completely free! The following C# example demonstrates how to convert an EPUB document. We describe the source code for reading EPUB from a file and then converting EPUB to JPEG with default saving options. Please load EPUB from the local file system, select the output format and run the example. You will immediately get the result as a separate file.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter EPUB "JPG|JPEG" GIF PDF DOCX PNG BMP TIFF XPS >}}
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
h2: Steps to Convert EPUB to JPEG in C#
---

If you would like to consider conversion functionality in your product or you want to convert EPUB to JPEG programmatically, please see the C# code example above or learn the Documentation chapter. It can be different scenarios, but any EPUB conversion can be made with a few required steps:

1.  Open an existing EPUB file.
1.  Create a new [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions) object with JPEG ImageFormat. By default, the Format property is [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat).
1.  Use the [ConvertEPUB()](https://reference.aspose.com/html/net/aspose.html.converters.converter/convertepub/methods/27) method of the Converter class to save EPUB as a JPEG image. You need to pass the EPUB file stream, ImageSaveOptions, and output file path to the ConvertEPUB() method for EPUB to JPEG conversion.
1.  The JPEG file will be saved to the specified path.


{{<section documentation>}}
---
h2: EPUB to JPEG Conversion in Documentation
---

The EPUB format has gained popularity as an XML-based e-book format and is designed to adapt the content’s presentation to the reader device. Sometimes, it is required to get an image instead of EPUB documents, such as making them portable and easily shared on various devices, creating a picture gallery from eBooks, etc. Please visit the documentation article [Convert EPUB to JPG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/) to learn more about Aspose.HTML for .NET API conversion features and to consider C# examples for the most common EPUB to JPG conversion scenarios. In the article, you find information on how to convert EPUB to JPG using ConvertEPUB() methods, and how to apply ImageSaveOptions and ICreateStreamProvider parameters.
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#epub-to-jpg-by-two-lines-of-code" target="_blank">EPUB to JPG by two lines of code</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#convert-epub-to-jpg-using-imagesaveoptions" target="_blank">Convert EPUB to JPG using ImageSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers" target="_blank">Convert EPUB to JPG using MemoryStreamProvider</a>  

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
title: Other Supported EPUB Conversions
subTitle: "You can also convert EPUB to many other file formats:"
---