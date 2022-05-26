---
title: Convert HTML, XHTML, Markdown, MHTML, EPUB and SVG Using C#
url: /net/conversion/
description: Convert hypertext markup language HTML to XHTML, PDF, DOCX, XPS, Markdown, MHTML and Images with few lines of C# code via .NET library.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="HTML Conversion Via C#" h2="Convert hypertext markup language HTML to XHTML, MHTML, Markdown, PDF, XPS, DOCX and Images including BMP, JPG, PNG, TIFF to build cross-platform .NET applications." >}}

{{% blocks/products/pf/feature-page-section  h2="How to Convert HTML" %}}
Hypertext markup language HTML is the language of the Web. Currently, most information is present on websites in form of webpages. So converting this HTML based information into other formats like PDF, XPS, Microsoft® Word, Markdown and image formats is a common scenario. **.NET HTML API** makes the conversion process easier for developers. It loads the file using [HTMLDocument class](https://apireference.aspose.com/html/net/aspose.html/htmldocument), creates the relevant save options object and uses the [Converter class](https://apireference.aspose.com/html/net/aspose.html.converters/converter) relevant conversion method.</br></br> 
The main highlight of Aspose.HTML .NET API is a conversion feature. Converting between formats is required for various reasons: to work in a familiar, convenient format or to take advantage of different formats for specific tasks. The [Aspose.Html.Converters](https://apireference.aspose.com/html/net/aspose.html.converters) namespace implements easy access to conversion methods. </br>
Any conversion you want to perform involves loading an HTML document and saving it in the supported format. It can be different scenarios, but it can be made with a few required steps:</br>
1. Load an HTML document into a Document object using one of [HTMLDocument()](https://apireference.aspose.com/html/net/aspose.html/htmldocument) constructors. You can load HTML from a file, HTML code, stream, or URL.</br>
2. Create a Save Options object.</br>
3. Invoke one of the [ConvertHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) methods and pass the required parameters to it.
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C# code example" %}}
HTML to PDF conversion is one of famous scenario among different scenarios. Process of conversion is, load an HTML file using one of the HTMLDocument class having source file as parameter. Create a PdfSaveOptions object and define the relevant properties. Finally call the ConvertHTML method having HTMLDocument object, PDF options and output document path.

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

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Popular HTML Conversions Articles in Documentation" %}}

The [Aspose.Html.Converters](https://apireference.aspose.com/html/net/aspose.html.converters) namespace implements easy access to conversion methods. It provides a wide range of HTML conversions to popular formats, such as PDF, XPS, DOCX, JPEG, PNG, BMP, TIFF, GIF, MHTML, and MD. Please visit the **documentation** chapter [Converting Between Formats](https://docs.aspose.com/html/net/converting-between-formats/) to learn more about Aspose.HTML for .NET API conversion features.

<div class="row">
	<div class="col-md-3">
		<h4>Convert HTML to PDF, XPS</h4>				
		<ul>
			<li><a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/" target="_blank">Convert HTML to PDF</a></li>
			<li><a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions" target="_blank">Convert HTML to PDF using PdfSaveOptions</a></li>
			<li><a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#output-stream-providers" target="_blank">Convert HTML to PDF using MemoryStreamProvider</a></li>
			<li><a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/" target="_blank">Convert HTML to XPS</a></li>					
		</ul>
	</div>
	<div class="col-md-3">
		<h4>Convert HTML to Word</h4>	
		<ul>
			<li><a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/" target="_blank">Convert HTML to DOCX</a></li>
			<li><a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-using-docsaveoptions" target="_blank">Convert HTML to DOCX using DocSaveOptions</a></li>
			<li><a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#output-stream-providers" target="_blank">Convert HTML to DOCX using MemoryStreamProvider</a></li>
	</div>
	<div class="col-md-3">
		<h4>Convert HTML to Image</h4>	
		</ul>
		<ul>
			<li><a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/" target="_blank">Convert HTML to JPG</a></li>
			<li><a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-png/" target="_blank">Convert HTML to PNG</a></li>
			<li><a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/" target="_blank">Convert HTML to BMP</a></li>
			<li><a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/" target="_blank">Convert HTML to GIF</a></li>
			<li><a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-tiff/" target="_blank">Convert HTML to TIFF</a></li>						
		</ul>
	</div>
	<div class="col-md-3">
		<h4>Convert HTML to Web Formats</h4>
		<ul>
			<li><a href="https://docs.aspose.com/html//net/converting-between-formats/html-to-markdown/" target="_blank">Convert HTML to Markdown</a></li>
			<li><a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-mhtml/" target="_blank">Convert HTML to MHTML</a></li>			
		</ul>
	</div>	
</div>


 <h2><b>
You can try online HTML Converter 
    <a href="https://products.aspose.app/html/conversion/html" rel="opener noopener noreferrer" target="_blank"> 
     here
    </a>
    </b></h2>
	<p>You can convert HTML with Aspose.HTML for .NET API in real-time.  The following C# example demonstrates how to convert an HTML document. Please load a file from the local file system, select the output format and run the example. You will immediately get the result as a separate file.</p>
{{% /blocks/products/pf/feature-page-section %}}


{{< app/html/converter HTML PDF DOCX MD BMP "JPG|JPEG" PNG GIF TIFF XPS>}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;
using Aspose.Html.Rendering.Image;

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


{{% blocks/products/pf/feature-page-section  h2="Installing Aspose.HTML for .NET library" %}}

This library supports parsing of HTML5, CSS3, SVG and HTML Canvas to construct a Document Object Model (DOM) based on the WHATWG DOM Standard. You can use several ways to install the Aspose.HTML library for .NET on your system:</br>

1. Using the NuGet Package Manager GUI.
2. Using the Package Manager Console.
3. Installing Aspose.HTML for .NET through MSI.</br>  

  For more details about C# library installation, please refer to [Aspose.HTML Documentation](https://docs.aspose.com/html/net/getting-started/installation/).

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Other Supported Conversions" %}}
You can also convert HTML, XHTML, MHTML, EPUB, Markdown, and SVG files into many other file formats including few listed below:
{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/feature-page-options pairs="html-to-pdf html-to-docx html-to-xps html-to-md html-to-xhtml html-to-mhtml html-to-bmp html-to-png html-to-jpeg html-to-tiff html-to-gif html-to-image xhtml-to-pdf xhtml-to-docx xhtml-to-xps xhtml-to-html xhtml-to-md xhtml-to-mhtml xhtml-to-bmp xhtml-to-png xhtml-to-jpeg xhtml-to-tiff xhtml-to-gif xhtml-to-image mhtml-to-pdf mhtml-to-docx mhtml-to-xps mhtml-to-bmp mhtml-to-png mhtml-to-jpeg mhtml-to-tiff mhtml-to-gif mhtml-to-image epub-to-pdf epub-to-docx epub-to-xps epub-to-bmp epub-to-png epub-to-jpeg epub-to-tiff epub-to-gif epub-to-image md-to-html md-to-pdf md-to-docx md-to-xps md-to-bmp md-to-png md-to-jpeg md-to-tiff md-to-gif md-to-image svg-to-pdf svg-to-xps svg-to-bmp svg-to-png svg-to-jpeg svg-to-tiff svg-to-gif svg-to-image" >}}