---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать HTML в PDF
description: Преобразование HTML в PDF на C#. Легко используйте API в любом приложении .NET. Попробуйте онлайн-конвертер HTML в PDF бесплатно!
url: /net/conversion/html-to-pdf/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: PDF
otherformats: DOCX XPS GIF JPEG PNG TIFF BMP XHTML MHTML MD
---

{{<section banner>}}
---
h1: Конвертировать HTML в PDF на C#
h2: Создание PDF-файла из исходной HTML-страницы с помощью .NET API. Мгновенно конвертируйте HTML в формат PDF онлайн.
---

{{<section overview>}}
---
h2: Преобразование HTML в PDF с помощью C#
---

Файлы HTML часто используются для создания, редактирования или передачи большого количества информации. Преобразование HTML в PDF часто требуется для защиты документов от нежелательного редактирования и копирования, для подготовки документов к печати или отправке по электронной почте и т. д. С помощью [Aspose.HTML для .NET](https://products.aspose.com/html/net/) API, вы можете программно преобразовывать HTML в PDF с полным контролем над широким диапазоном параметров преобразования. Существуют различные случаи преобразования HTML в PDF, такие как чтение из файла, URL-адреса, редактора WYSISYG, строки или потока. Мощный C# API позволяет быстро и качественно конвертировать HTML в популярные форматы!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации HTML
---

Проверьте качество преобразования HTML в PDF прямо в браузере! Пожалуйста, загрузите файл HTML из локальной файловой системы, выберите требуемый формат вывода из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование HTML в PDF будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или HTML в формат PDF онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML PDF MD "JPG|JPEG" GIF DOCX BMP XPS TIFF PNG MHTML >}}
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
h2: Шаги по преобразованию HTML в PDF на C#
---

Если вы хотели бы использовать функции преобразования в своем продукте или хотите программно преобразовать HTML в PDF, см. приведенный выше пример кода C# или изучите главу «Документация». Во всех случаях любое преобразование требует некоторых обязательных шагов:

1. Загрузите HTML-документ с помощью одного из конструкторов [HTMLDocument()](https://apireference.aspose.com/html/net/aspose.html/htmldocument). Вы можете загрузить HTML из файла, HTML-кода, потока или URL-адреса.
1. Создайте новый объект [PdfSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions).
1. Используйте метод [ConvertHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) класса Converter для сохранения HTML в виде файла PDF. Вам необходимо передать HTMLDocument, PdfSaveOptions и путь к выходному файлу методу ConvertHTML().
1. Файл PDF будет сохранен по указанному пути.

{{<section documentation>}}
---
h2: Преобразование HTML в PDF в документации
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#html-to-pdf-by-a-single-of-code " target="_blank">Преобразование HTML в PDF с помощью одной строки кода</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-in-c-using-pdfsaveoptions" target="_blank">Преобразование HTML в PDF с помощью PdfSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#output-stream-providers" target="_blank">Преобразование HTML в PDF с помощью MemoryStreamProvider</a>

Файлы HTML часто используются для создания, редактирования или передачи большого количества информации. Преобразование HTML в PDF часто требуется для защиты документов от нежелательного редактирования или копирования, создания официальной документации, подготовки файлов к печати или отправке по электронной почте и т. д. Пожалуйста, посетите статью документации [Преобразование HTML в PDF,](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/) чтобы узнать больше о функциях преобразования Aspose.HTML для .NET API и рассмотреть примеры C# для наиболее распространенных сценариев преобразования HTML в PDF. В статье вы найдете информацию о том, как преобразовать HTML в PDF с помощью методов ConvertHTML() и как применить параметры PdfSaveOptions и ICreateStreamProvider.

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
title: Другие поддерживаемые преобразования HTML
subTitle: "Вы также можете конвертировать HTML в другие форматы файлов:"
---