---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать HTML в XPS
description: Преобразование HTML в XPS на C#. Легко используйте API любом приложении .NET. Попробуйте онлайн-конвертер HTML в XPS бесплатно!
url: /net/conversion/html-to-xps/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: XPS
otherformats: PDF DOCX GIF JPEG PNG TIFF BMP XHTML MHTML MD
---

{{<section banner>}}
---
h1: Конвертировать HTML в XPS на C#
h2: Создание XPS из исходной HTML-страницы с помощью .NET API. Мгновенно конвертируйте HTML в формат XPS онлайн.
---

{{<section overview>}}
---
h2: Преобразование HTML в XPS с помощью C#
---

Файлы HTML часто используются для создания, редактирования или передачи большого количества информации. Преобразование HTML в XPS часто требуется для установления ограниченного доступа к редактированию или копированию документов. Формат файла XPS обеспечивает управление правами доступа и позволяет создавать высококачественные документы для печати. С помощью [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API вы можете программно преобразовывать HTML в XPS с полным контролем над широким диапазоном параметров преобразования. Существуют различные случаи преобразования HTML в XPS, такие как чтение из файла, URL-адреса, редактора WYSISYG, строки или потока. Мощный C# API позволяет быстро и качественно конвертировать HTML в популярные форматы!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации HTML
---

Проверьте качество преобразования HTML в XPS прямо в браузере! Пожалуйста, загрузите файл HTML из локальной файловой системы, выберите требуемый формат вывода из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование HTML в XPS будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или HTML в формат XPS онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML  XPS PDF MD "JPG|JPEG" GIF DOCX BMP TIFF PNG MHTML >}}
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
h2: Шаги по преобразованию HTML в XPS в C#
---

Если вы хотели бы использовать функции преобразования в своем продукте или хотите программно преобразовать HTML в XPS, см. приведенный выше пример кода C# или изучите главу «Документация». Во всех случаях любое преобразование требует некоторых обязательных шагов:

1. Загрузите HTML-документ с помощью одного из конструкторов [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). Вы можете загрузить HTML из файла, HTML-кода, потока или URL-адреса.
1. Создайте новый объект [XpsSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/xpssaveoptions/).
1. Используйте метод [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) класса Converter для сохранения HTML в виде файла XPS. Вам необходимо передать HTMLDocument, XpsSaveOptions и путь к выходному файлу методу ConvertHTML().
1. Файл XPS будет сохранен по указанному пути.

{{<section documentation>}}
---
h2: Преобразование HTML в XPS в документации
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#html-to-xps-by-a-single-of-code " target="_blank">Преобразование HTML в XPS с помощью одной строки кода</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#convert-html-to-xps-in-c-using-xpssaveoptions" target="_blank">Преобразование HTML в XPS с помощью XpsSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/#output-stream-providers" target="_blank">преобразование HTML в XPS с помощью MemoryStreamProvider</a>

XPS — это формат хранения и просмотра документов, разработанный Microsoft. Он имеет ряд преимуществ, которые поддерживают функции безопасности, такие как цифровые подписи для обеспечения большей безопасности документов и многое другое. Пожалуйста, посетите статью документации [Преобразование HTML в XPS](https://docs.aspose.com/html/net/converting-between-formats/html-to-xps/), чтобы узнать больше о функциях преобразования Aspose.HTML for .NET API и рассмотреть примеры C# для наиболее распространенных сценариев преобразования HTML в XPS. В статье вы найдете информацию о том, как преобразовать HTML в XPS с помощью методов ConvertHTML() и как применить параметры XpsSaveOptions и ICreateStreamProvider.

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
subTitle: "Вы также можете конвертировать HTML во многие другие форматы файлов:"
---