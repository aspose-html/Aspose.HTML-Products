---
title: C# HTML Conversion including HTML to Word PDF and Images
url: /net/conversion/
description: Convert hypertext markup language HTML to PDF Word and Images with few lines of C# code via .NET library.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="HTML Conversion Via C#" h2="Convert hypertext markup language HTML to PDF, Word DOC, DOCX and Images including BMP, JPG, PNG, TIFF to build cross-platform .NET applications." >}}

{{% blocks/products/pf/feature-page-summary %}}
Hypertext markup language HTML is the language of web. Currently mostly information is present on websites in form of webpages. So converting this HTML based information into other formats like Microsoft<sup>&reg;</sup> Word , PDF and image formats is common scenario. **.NET HTML API** makes the conversion process easier for developers. It loads the file using [HTMLDocument class](https://apireference.aspose.com/html/net/aspose.html/htmldocument), create the relevant save options object and use the [converter class](https://apireference.aspose.com/html/net/aspose.html.converters/converter) relevant conversion method.


{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="HTML to PDF Conversion" %}}

HTML to PDF conversion is one of famous scenario among different scenarios. Process of conversion is, load an HTML file using one of the HTMLDocument class having source file as parameter. Create a [PdfSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions) object and define the relevant properties. Finally call the ConvertHTML method having HTMLDocument object, PDF options and output document path. 


{{% blocks/products/pf/feature-page-code h3="C# Code for HTML to PDF Conversion" %}}

{{< gist "aspose-com-gists" "9534bd8bfc93d54e18432b1ea0f2acc8" "convert-html-to-pdf.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert HTML to Images JPG, PNG, BMP, TIFF and more" %}}

Just like PDF conversion, process of converting HTML to image formats is almost same, other than API provides [ImageSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions) for specific image settings such as BackgroundColor, HorizontalResolution, SmoothingMode that enables to set the rendering quality for the image and more. 

{{% blocks/products/pf/feature-page-code h3="C# Code for Converting HTML to Image Formats" %}}

{{< gist "aspose-com-gists" "9534bd8bfc93d54e18432b1ea0f2acc8" "convert-html-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="html-to-bmp html-to-png html-to-jpeg html-to-tiff html-to-gif" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert HTML to Word DOC / DOCX File" %}}

.NET API is capable of HTML to Microsoft Word formats DOC / DOCX conversion. Developers can use [DocSaveOptions Class](https://apireference.aspose.com/html/net/aspose.html.saving/docsaveoptions) for the word settings. Remaining process is almost similar to above cases, that is loading the source file and using Converter.ConvertHTML method.

{{% blocks/products/pf/feature-page-code h3="C# Code for HTML to Word Conversion" %}}

{{< gist "aspose-com-gists" "9534bd8bfc93d54e18432b1ea0f2acc8" "convert-html-to-word.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="html-to-xps html-to-svg html-to-epub" >}}