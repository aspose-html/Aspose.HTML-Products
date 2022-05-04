---
title: Convert HTML to XHTML, PDF, DOCX, XPS, Markdown, MHTML and Images Using C#
url: /net/conversion/
description: Convert hypertext markup language HTML to XHTML, PDF, DOCX, XPS, Markdown, MHTML and Images with few lines of C# code via .NET library.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="HTML Conversion Via C#" h2="Convert hypertext markup language HTML to XHTML, MHTML, Markdown, PDF, XPS, DOC, DOCX and Images including BMP, JPG, PNG, TIFF to build cross-platform .NET applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

Hypertext markup language HTML is the language of the Web. Currently, most information is present on websites in form of webpages. So converting this HTML based information into other formats like PDF, XPS, Microsoft® Word, Markdown and image formats is a common scenario. **.NET HTML API** makes the conversion process easier for developers. It loads the file using [HTMLDocument class](https://apireference.aspose.com/html/net/aspose.html/htmldocument), creates the relevant save options object and uses the [Converter class](https://apireference.aspose.com/html/net/aspose.html.converters/converter) relevant conversion method.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="How to Convert HTML" %}}
The main highlight of Aspose.HTML .NET API is a conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The [Aspose.Html.Converters](https://apireference.aspose.com/html/net/aspose.html.converters) namespace implements easy access to conversion methods. </br></br>
Any conversion you want to perform involves loading an HTML document and saving it in the supported format. It can be different scenarios, but it can be made with a few required steps:</br></br>
1. Load an HTML document into a Document object using one of [HTMLDocument()](https://apireference.aspose.com/html/net/aspose.html/htmldocument) constructors. You can load HTML from a file, HTML code, stream, or URL.</br>
2. Create a Save Options object.</br>
3. Invoke one of the [ConvertHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/methods/converthtml/index) methods and pass the required parameters to it.
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C# code example" %}}
HTML to PDF conversion is one of famous scenario among different scenarios. Process of conversion is, load an HTML file using one of the HTMLDocument class having source file as parameter. Create a PdfSaveOptions object and define the relevant properties. Finally call the ConvertHTML method having HTMLDocument object, PDF options and output document path.

The following C# example demonstrates how to convert an HTML document. Please load a file from the local file system, select the output format and run the example. </br></br>

```cs
using System.IO;
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;
using System.Drawing;
using Aspose.Html.Drawing;
//add above namespaces at the top of your class
    
// Initialize an HTML document from the file
var htmltopdf = new HTMLDocument("sourcefilewithpath.html");
    
// Initialize PdfSaveOptions. Set up the page-size, margins, 
// resolutions and background color 

var pdfOptions = new PdfSaveOptions(){                
        HorizontalResolution = 200,
        VerticalResolution = 200,
        JpegQuality = 100,
        BackgroundColor = Color.AliceBlue                
    };
pdfOptions.PageSetup.AnyPage = new Page(new Aspose.Html.Drawing.Size(600, 300), new Margin(20, 10, 10, 10));     
    
// Convert HTML to PDF
Converter.ConvertHTML(htmltopdf, pdfOptions, "outputfilewithpath.pdf");
```
You can also convert HTML into many other file formats including few listed below:
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="html-to-pdf html-to-xps html-to-md html-to-xhtml html-to-mhtml html-to-bmp html-to-png html-to-jpeg html-to-tiff html-to-gif" >}}


{{% blocks/products/pf/feature-page-section  h2="Popular HTML Conversions" %}}

The [Aspose.Html.Converters](https://apireference.aspose.com/html/net/aspose.html.converters) namespace implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as PDF, XPS, DOCX, JPEG, PNG, BMP, TIFF, GIF, MHTML, and MD. Please visit the documentation chapter [Converting Between Formats](https://docs.aspose.com/html/net/converting-between-formats/) to learn more about Aspose.HTML for .NET API conversion features.

<div class="row">
	<div class="col-md-3">
		<h4>Convert HTML to PDF, XPS</h4>				
		<ul>
			<li><a href="/html/net/converting-between-formats/html-to-pdf/">Convert HTML to PDF</a></li>
			<li><a href="/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions">Convert HTML to PDF using PdfSaveOptions</a></li>
			<li><a href="/html/net/converting-between-formats/html-to-pdf/#output-stream-providers">Convert HTML to PDF using MemoryStreamProvider</a></li>
			<li><a href="/html/net/converting-between-formats/html-to-xps/">Convert HTML to XPS</a></li>					
		</ul>
	</div>
	<div class="col-md-3">
		<h4>Convert HTML to Word</h4>	
		<ul>
			<li><a href="/html/net/converting-between-formats/html-to-docx/">Convert HTML to DOCX</a></li>
			<li><a href="/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions">Convert HTML to DOCX using DocSaveOptions</a></li>
			<li><a href="/html/net/converting-between-formats/html-to-docx/#output-stream-providers">Convert HTML to DOCX using MemoryStreamProvider</a></li>
	</div>
	<div class="col-md-3">
		<h4>Convert HTML to Image</h4>	
		</ul>
		<ul>
			<li><a href="/html/net/converting-between-formats/html-to-jpg/">Convert HTML to JPG</a></li>
			<li><a href="/html/net/converting-between-formats/html-to-png/">Convert HTML to PNG</a></li>
			<li><a href="/html/net/converting-between-formats/html-to-bmp/">Convert HTML to BMP</a></li>
			<li><a href="/html/net/converting-between-formats/html-to-gif/">Convert HTML to GIF</a></li>
			<li><a href="/html/net/converting-between-formats/html-to-tiff/">Convert HTML to TIFF</a></li>						
		</ul>
	</div>
	<div class="col-md-3">
		<h4>Convert HTML to Web Formats</h4>
		<ul>
			<li><a href="/html/net/converting-between-formats/html-to-markdown/">Convert HTML to Markdown</a></li>
			<li><a href="/html/net/converting-between-formats/html-to-mhtml/">Convert HTML to MHTML</a></li>			
		</ul>
	</div>	
</div>

 <h4 >
You can try online HTML Converter 
    <a href="https://products.aspose.app/html/conversion/html" rel="opener noopener noreferrer" target="_blank"> 
     here.
    </a>
    </h4>

{{% /blocks/products/pf/feature-page-section %}}
