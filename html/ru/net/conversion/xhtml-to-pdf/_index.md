---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать XHTML в PDF
description: Преобразование XHTML в PDF на C#. Легко используйте API в любом приложении .NET. Попробуйте онлайн-конвертер XHTML в PDF бесплатно!
url: /net/conversion/xhtml-to-pdf/
family: html
platformtag: net
feature: conversion
informat: XHTML
outformat: PDF
otherformats: XPS DOCX GIF JPEG PNG TIFF BMP HTML MHTML MD
howto: howtoXhtml
---

{{<section banner>}}
---
h1: Конвертировать XHTML в PDF с помощью C#
h2: Создание PDF-файла из исходной страницы XHTML с помощью .NET API. Мгновенно конвертируйте XHTML в формат PDF онлайн!
---

{{<section overview>}}
---
h2: Конвертировать XHTML в PDF с помощью C#
---

Преобразование XHTML в PDF часто требуется для защиты документов от нежелательного редактирования и копирования, для подготовки документов к печати или отправке по электронной почте и т. д. С помощью [Aspose.HTML для .NET](https://products.aspose.com/html/net/) API, вы можете программно конвертировать XHTML в PDF с полным контролем над параметрами конвертации. Любое преобразование, которое вы хотите выполнить, включает в себя загрузку документа XHTML и сохранение его в формате PDF. Мощный C# API позволяет быстро и качественно конвертировать XHTML в PDF!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации XHTML
---

Проверьте качество преобразования XHTML в PDF прямо в браузере! Пожалуйста, загрузите файл XHTML из локальной файловой системы, выберите требуемый выходной формат из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование XHTML в PDF будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или XHTML в формат PDF онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter XHTML PDF BMP TIFF PNG "JPG|JPEG" GIF PDF XPS DOCX MHTML MD >}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new HTMLDocument("{{input lower}}");
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
{{#if_output 'MHTML'}}
    var options = new MHTMLSaveOptions();
{{/if_output}}
{{#if_output 'BMP' 'JPG' 'GIF' 'PNG' 'TIFF'}}
    var options = new ImageSaveOptions(ImageFormat.{{output param2 camel}});
{{/if_output}}
    Converter.ConvertHTML(document, options, "output.{{output lower}}");   
{{< /app/html/converter>}} 


{{<section steps>}}
---
h2: Шаги по преобразованию XHTML в PDF на C#
---

Если вы хотите программно преобразовать XHTML в PDF, см. приведенный выше пример кода C# или изучите главу «Документация». Во всех случаях любое преобразование XHTML в PDF требует выполнения некоторых обязательных шагов:
1. Загрузите файл XHTML, используя один из конструкторов HTMLDocument() класса [HTMLDocument.](https://reference.aspose.com/html/net/aspose.html/htmldocument/)
1. Создайте новый объект [PdfSaveOptions.](https://reference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions/)
1. Используйте метод [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) класса Converter, чтобы сохранить XHTML в виде файла PDF.
1. Файл PDF будет сохранен по указанному пути.

{{<section documentation>}}
---
h2: Конвертация (X)HTML в документации
---

Преобразование XHTML в PDF часто требуется для установления ограниченного доступа к редактированию или копированию документов, для создания официальной документации или отправки какой-либо информации, например, по электронной почте. Aspose.HTML for .NET API позволяет быстро и качественно конвертировать (X)HTML в другие популярные форматы. Посетите главу документации <a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">Преобразование между форматами</a>, чтобы узнать больше об API. В главе описываются популярные преобразования, а также примеры C# для наиболее распространенных сценариев преобразования.

{{<section online-converters>}}
---
h2: Бесплатные онлайн-конвертеры
---

{{<section get-started>}}
---
h2: Как установить библиотеку Aspose.HTML для .NET
---

{{<section other-conversions>}}
---
title: Другие поддерживаемые преобразования XHTML
subTitle: "Вы также можете конвертировать XHTML во многие другие форматы файлов:"
---