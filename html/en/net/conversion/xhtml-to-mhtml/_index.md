---
title: Convert XHTML to MHTML via C# 
url: /net/conversion/xhtml-to-mhtml/ 
description: Convert XHTML to MHTML using C# or VB.NET. Easily use XHTML to MHTML converter API within ASP.NET or any .NET application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Convert XHTML to MHTML via C#" h2="High-fidelity conversion of XHTML pages as MHTML using server-side .NET APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/html/aspose_html-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="MHTML" pfName="Aspose.HTML" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="HTML" fileiconsmall4="XML" fileiconsmall5="XHTML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Html " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/html/aspose_html-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-html" liveDemosLink="#lviv.app" docsLink="https://docs.aspose.com/html/net" installationsDocsLink="https://docs.aspose.com/html/net" nugetLink="https://www.nuget.org/packages/aspose.html" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/html/net" learnAsLink="#lviv.doc" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Convert XHTML to MHTML Using C#" %}}

 The advantage of saving (X)HTML as MHTML is that all of the web page elements are kept intact in a single file. MHTML contains an underlying (X)HTML document and its embedded images, media, and other resources. With [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API, you can convert XHTML to MHTML programmatically with full control over conversion parameters. Any conversion you want to perform involves loading an XHTML document and saving it in MHTML format. You should take some mandatory steps:</br></br>

<h2> Steps to Convert XHTML to MHTML via C# </h2>

1.  Load an XHTML file using one of HTMLDocument() constructors of the [HTMLDocument](https://apireference.aspose.com/html/net/aspose.html/htmldocument) class.
1.  Create a new [MHTMLSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/mhtmlsaveoptions) object. 
1.  Use the [ConvertHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) method of the Converter class to save XHTML as an MHTML file.
1.  The MHTML file will be saved to the specified path.</br></br>

<a id=lviv.app />
<h2> Free Online Converter Live Demos </h2>
<p>Test the quality of XHTML to MHTML conversion right in your browser! The following C# example demonstrates how to convert an XHTML document. We describe the source code for reading XHTML from a file and then converting XHTML to MHTML with default saving options. Please load XHTML from the local file system, select the output format and run the example. You will immediately get the result as a separate file.</p>
{{% /blocks/products/pf/agp/content %}}

{{< app/html/converter XHTML MHTML MD "JPG|JPEG" GIF BMP XPS TIFF PNG PDF DOCX>}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new HTMLDocument("document.{{input lower}}");
{{#if_output 'MHTML'}}
    var options = new MHTMLSaveOptions();
{{/if_output}}
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

{{% blocks/products/pf/agp/content  %}}
<p>Aspose.HTML offers free online <a href="https://products.aspose.app/html/conversion" target="_blank">Converters</a> for converting <a href="https://products.aspose.app/html/conversion/html" target="_blank">HTML</a>, <a href="https://products.aspose.app/html/conversion/xhtml" target="_blank">XHTML</a>, <a href="https://products.aspose.app/html/conversion/mhtml" target="_blank">MHTML</a>, <a href="https://products.aspose.app/html/conversion/epub" target="_blank">EPUB</a>, <a href="https://products.aspose.app/html/conversion/xml" target="_blank">XML</a> or <a href="https://products.aspose.app/html/conversion/md" target="_blank">Markdown</a> documents to PDF, XPS, DOCX, JPG, PNG, BMP, TIFF, GIF, Markdown and other formats. Just upload, convert your documents and get results in a few seconds. You don't need any additional software. Powerful C# API allows converting between popular formats with high speed and high quality. Try our forceful online Converters for free now!</p>
{{% /blocks/products/pf/agp/content  %}}

<a id=lviv.doc />
{{% blocks/products/pf/agp/content h2="XHTML to MHTML Conversion in Documentation" %}}

MHTML combines normal (X)HTML with external resources like images, animations, audio, etc., into one file with the .mht file extension. Aspose.HTML for .NET API allows you to convert (X)HTML to other popular formats quickly and with high quality. Please visit the documentation chapter <a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">Converting Between Formats</a> to learn more about the API conversion features. The chapter describes popular converters, as well as C# examples for the most common conversion scenarios.

{{% /blocks/products/pf/agp/content %}}   
	
<!-- aboutfile Starts -->
	
    {{< blocks/products/pf/agp/about-file-section >}}     
    {{< blocks/products/pf/agp/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/xhtml/" >}}
XHTML (eXtensible HyperText Markup Language) is a text-based file format with markup in the XML, using a reformulation of HTML 4.0. These files are well suited to be opened or viewed in a web browser. The XHTML was designed to be more structured, less scripting, generic and device-independent. It uses all the existing XML facilities and more. The XHTML provides a generally worthwhile set of elements and attributes, with extension options combined with style sheets. XHTML provides flexibility and accessibility by subordinating all HTML presentation elements to style sheets. Specifications for HTML 4.01, HTML5 and XHTML are being dynamically developed by the World Wide Web Consortium (W3C).
    {{< /blocks/products/pf/agp/about-file-text >}}
    
        {{< blocks/products/pf/agp/about-file-text fileFormat="MHTML" readMoreLink="https://docs.fileformat.com/web/mhtml/" >}}
Files with MHTML extension represent a web page archive format that can be created by a number of different applications. The format is known as archive format because it saves the web HTML code and associated resources in a single file. These resources include anything linked to the webpage such as images, applets, animations, audio files and so on. MHTML files can be opened in a variety of applications such as Internet Explorer and Microsoft Word. The MHTML file format encodes the page contents similar to specifications defined in message/rfc822 which are plain text email related specifications. The actual specifications of the format are as detailed by RFC 2557.
    {{< /blocks/products/pf/agp/about-file-text >}} 
	{{< /blocks/products/pf/agp/about-file-section >}}		

<!-- aboutfile Ends -->

{{% blocks/products/pf/agp/content h2="How to Install Aspose.HTML for .NET library" %}}

You can use several ways to install the Aspose.HTML library for .NET on your system:
1. Install a <a href="https://www.nuget.org/packages/aspose.html" target="_blank">NuGet Package</a> using the NuGet Package Manager GUI.
2. Install a NuGet Package using the Package Manager Console.
3. Install Aspose.HTML for .NET through MSI.</br>  

This library supports parsing of HTML5, CSS3, SVG and HTML Canvas to construct a Document Object Model (DOM) based on the WHATWG DOM Standard. Aspose.HTML for .NET is written completely in C# and can be used to build any type of 32-bit or 64-bit .NET application including ASP.NET, WCF, WinForms & .NET Core. Before running the .NET conversion example code, make sure that you have OS like Microsoft Windows or a compatible with .NET Framework or .NET Standard, and the development environment like Microsoft Visual Studio.
  For more details about C# library installation and system requirements, please refer to [Aspose.HTML Documentation](https://docs.aspose.com/html/net/getting-started/).

{{% /blocks/products/pf/agp/content  %}}

{{< blocks/products/pf/agp/other-supported-section title="Other Supported XHTML Conversions" subTitle="You can convert XHTML to many other file formats:" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/html/net/conversion/xhtml-to-image/" name="XHTML TO IMAGE" description="Image formats" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/html/net/conversion/xhtml-to-jpeg/" name="XHTML TO JPEG" description="JPEG Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/html/net/conversion/xhtml-to-bmp/" name="XHTML TO BMP" description="Bitmap Image" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/html/net/conversion/xhtml-to-gif/" name="XHTML TO GIF" description="Graphical Interchange Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/html/net/conversion/xhtml-to-png/" name="XHTML TO PNG" description="Portable Network Graphics" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/html/net/conversion/xhtml-to-tiff/" name="XHTML TO TIFF" description="Tagged Image Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/html/net/conversion/xhtml-to-xps/" name="XHTML TO XPS" description="XML Paper Specifications" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/html/net/conversion/xhtml-to-pdf/" name="XHTML TO PDF" description="Portable Document Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/html/net/conversion/xhtml-to-docx/" name="XHTML TO DOCX" description="Microsoft Word" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/html/net/conversion/xhtml-to-md/" name="XHTML TO MD" description="Markdown Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/html/net/conversion/xhtml-to-mhtml/" name="XHTML TO MHTML" description="Web Page Archive Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/html/net/conversion/xhtml-to-html/" name="XHTML TO HTML" description="HyperText Markup Language" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}    
{{< /blocks/products/pf/main-wrap-class >}}