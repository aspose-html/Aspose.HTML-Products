---
title: Convert EPUB to PDF via C# 
weight: 940
url: /net/conversion/epub-to-pdf/ 
description: Sample code for EPUB to PDF C# conversion. Use API example code for batch EPUB files to PDF conversion within VB.NET, Asp.NET or any .NET based application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert EPUB to PDF via C#" h2="High-fidelity conversion of EPUB pages as PDF using server-side .NET APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/html/aspose_html-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="EPUB" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Html " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/html/aspose_html-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-html" liveDemosLink="#lviv.app" docsLink="https://docs.aspose.com/html/net" installationsDocsLink="https://docs.aspose.com/html/net" nugetLink="https://www.nuget.org/packages/aspose.html" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/html/net" learnAsLink="#lviv.doc" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Convert EPUB to PDF Using C#" %}}

In order to convert EPUB to PDF, we’ll use [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API which is a feature-rich, powerful and easy to use document manipulation and conversion API for the C# platform. EPUB is an open XML-based format for digital books and publications that can be viewed and read on a variety of devices. EPUB to PDF conversion is often required to take advantage of PDF format. .NET developers can easily load & convert EPUB to PDF in just a few lines of code.</br></br>

<h2> Steps to Convert EPUB to PDF via C# </h2>

1.  Open an existing EPUB file.
1.  Create an instance of [PdfSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions).
1.  Use the [ConvertEPUB()](https://apireference.aspose.com/html/net/aspose.html.converters.converter/convertepub/methods/29) method of the [Converter](https://apireference.aspose.com/html/net/aspose.html.converters/converter) class to save EPUB as a PDF file. You need to pass the EPUB file stream, PdfSaveOptions, and output file path to the ConvertEPUB() method to convert EPUB to PDF.
1.  The PDF file will be saved to the specified path.</br></br>

<a id=lviv.app />
<h2> Free Online Converter Live Demos </h2>
<p> Test the quality of EPUB to PDF conversion right in your browser! The following C# example demonstrates how to convert an EPUB document. We describe the source code for opening EPUB from a file and then converting EPUB to PDF with default saving options. Please load EPUB from the local file system, select the output format and run the example. You will immediately get the result as a separate file.</p>
{{% /blocks/products/pf/agp/content %}}

{{< app/html/converter EPUB PDF "JPG|JPEG" DOCX BMP MD PNG TIFF XPS>}}
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
{{#if_output 'MD'}}
    var options = new MarkdownSaveOptions();
{{/if_output}}
{{#if_output 'BMP' 'JPG' 'GIF' 'PNG' 'TIFF'}}
    var options = new ImageSaveOptions(ImageFormat.{{output param2 camel}});
{{/if_output}}
    Converter.ConvertEPUB(stream, options, "output.{{output lower}}");   
{{< /app/html/converter>}}

{{% blocks/products/pf/agp/content  %}}
<p>Aspose.HTML offers free online <a href="https://products.aspose.app/html/conversion" target="_blank">Converters</a> for converting <a href="https://products.aspose.app/html/conversion/html" target="_blank">HTML</a>, <a href="https://products.aspose.app/html/conversion/xhtml" target="_blank">XHTML</a>, <a href="https://products.aspose.app/html/conversion/mhtml" target="_blank">MHTML</a>, <a href="https://products.aspose.app/html/conversion/epub" target="_blank">EPUB</a>, <a href="https://products.aspose.app/html/conversion/xml" target="_blank">XML</a> or <a href="https://products.aspose.app/html/conversion/md" target="_blank">Markdown</a> documents to PDF, XPS, DOCX, JPEG, PNG, BMP, TIFF, GIF, Markdown and other formats. Just upload, convert your documents and get results in a few seconds. You don't need any additional software. Powerful C# API allows converting EPUB to popular formats with high speed and high quality. Try our forceful online Converters for free now!</p>

{{% /blocks/products/pf/agp/content  %}}

<a id=lviv.doc />
{{% blocks/products/pf/agp/content h2="EPUB to PDF Conversion in Documentation" %}}

The EPUB format has gained popularity as an XML-based e-book format and is designed to adapt the content’s presentation to the reader device. Sometimes you need to get PDF documents instead of EPUB, such as making them print-optimized, safe and secure, making copies of EPUB documents, etc. Please visit the documentation article [Convert EPUB to PDF](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) to learn more about Aspose.HTML for .NET API conversion features and to consider C# examples for the most common EPUB to PDF conversion scenarios. In the article, you find information on how to convert EPUB to PDF using ConvertEPUB() methods, and how to apply PdfSaveOptions and ICreateStreamProvider parameters.
<div>
	<ul>
		<li><a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#epub-to-pdf-by-two-lines-of-code" target="_blank">EPUB to PDF by two lines of code</a></li>
		<li><a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#convert-epub-to-pdf-using-pdfsaveoptions" target="_blank">Convert EPUB to PDF using PdfSaveOptions</a></li>
		<li><a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers" target="_blank">Convert EPUB to PDF using MemoryStreamProvider</a></li>
	</ul>		
</div>
{{% /blocks/products/pf/agp/content %}}   
	
<!-- aboutfile Starts -->
	
    {{< blocks/products/pf/agp/about-file-section >}}     
    {{< blocks/products/pf/agp/about-file-text fileFormat="EPUB" readMoreLink="https://docs.fileformat.com/ebook/epub/" >}}
EPUB is an e-book file format that provides a standard digital publication format for publishers and consumers. The format has been so common by now that it is supported by many e-readers and software applications. For example, on Mac OS, the pre-installed Books software provides support for opening such files. In addition, there is a lot of compatible software available for smartphones, tablets and computers. EPUB file standards are maintained by the International Digital Publishing Forum (IDPF).
    {{< /blocks/products/pf/agp/about-file-text >}}
    
        {{< blocks/products/pf/agp/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/pdf/" >}}
Portable Document Format (PDF) is a type of document created by Adobe back in 1990s. The purpose of this file format was to introduce a standard for the representation of documents and other reference material in a format independent of application software, hardware, and Operating System. The PDF file format can contain information like text, images, hyperlinks, form-fields, rich media, digital signatures, attachments, metadata, Geospatial features and 3D objects in it that can become part of a source document.
    {{< /blocks/products/pf/agp/about-file-text >}} 
	{{< /blocks/products/pf/agp/about-file-section >}}		

<!-- aboutfile Ends -->

{{% blocks/products/pf/agp/content h2="How to Install Aspose.HTML for .NET library" %}}

You can use several ways to install the Aspose.HTML library for .NET on your system:
1. Install a <a href="https://www.nuget.org/packages/aspose.html" target="_blank">NuGet Package</a> using the NuGet Package Manager GUI.
1. Install a NuGet Package using the Package Manager Console.
1. Install Aspose.HTML for .NET through MSI.</br>  

This library supports parsing of HTML5, CSS3, SVG and HTML Canvas to construct a Document Object Model (DOM) based on the WHATWG DOM Standard. Aspose.HTML for .NET is written completely in C# and can be used to build any type of 32-bit or 64-bit .NET application including ASP.NET, WCF, WinForms & .NET Core. Before running the .NET conversion example code, make sure that you have OS like Microsoft Windows or a compatible with .NET Framework or .NET Standard, and the development environment like Microsoft Visual Studio.
  For more details about C# library installation and system requirements, please refer to [Aspose.HTML Documentation](https://docs.aspose.com/html/net/getting-started/).

{{% /blocks/products/pf/agp/content  %}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported EPUB Conversions" subTitle="You can also convert EPUB to many other file formats including few listed below:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/html/net/conversion/epub-to-jpeg/" name="EPUB TO JPEG" description="JPEG Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/html/net/conversion/epub-to-xps/" name="EPUB TO XPS" description="XML Paper Specifications" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/html/net/conversion/epub-to-docx/" name="EPUB TO DOCX" description="Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/html/net/conversion/epub-to-image/" name="EPUB TO IMAGE" description="Image formats" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/html/net/conversion/epub-to-gif/" name="EPUB TO GIF" description="Graphical Interchange Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/html/net/conversion/epub-to-bmp/" name="EPUB TO BMP" description="Bitmap Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/html/net/conversion/epub-to-png/" name="EPUB TO PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/html/net/conversion/epub-to-tiff/" name="EPUB TO TIFF" description="Tagged Image Format" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}    
{{< /blocks/products/pf/main-wrap-class >}}