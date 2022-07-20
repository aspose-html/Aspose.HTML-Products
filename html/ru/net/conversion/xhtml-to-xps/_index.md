---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать XHTML в XPS в C# - Онлайн-конвертер XHTML в XPS
description: Преобразование XHTML в XPS на C#. Легко используйте API в любом приложении .NET. Попробуйте онлайн-конвертер XHTML в XPS бесплатно!
url: /net/conversion/xhtml-to-xps/
family: html
platformtag: net
feature: conversion
informat: XHTML
outformat: XPS
otherformats: PDF DOCX GIF JPEG PNG TIFF BMP HTML MHTML MD
---

{{<section banner>}}
---
h1: Конвертировать XHTML в XPS на C#
h2: Создание XPS из исходной страницы XHTML с помощью .NET API. Мгновенно конвертируйте формат XHTML в XPS онлайн!
---

{{<section overview>}}
---
h2: Преобразование XHTML в XPS с помощью C#
---

Главной изюминкой [Aspose.HTML .NET](https://products.aspose.com/html/net/) API является функция преобразования. Используя нашу мощную библиотеку, вы можете программно преобразовать XHTML в XPS с полным контролем над различными параметрами преобразования. Формат файла XPS обеспечивает управление правами доступа и позволяет создавать высококачественные документы для печати. Любое преобразование, которое вы хотите выполнить, включает в себя загрузку документа XHTML и его сохранение в поддерживаемом формате. Мощный C# API позволяет быстро и качественно конвертировать XHTML в XPS!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации XHTML
---

Проверьте качество преобразования XHTML в XPS прямо в браузере! Пожалуйста, загрузите файл XHTML из локальной файловой системы, выберите требуемый выходной формат из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование XHTML в XPS будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или XHTML в формат XPS онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter XHTML XPS TIFF PNG "JPG|JPEG" GIF BMP PDF DOCX MD MHTML>}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new HTMLDocument("document.{{input lower}}");
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
h2: Действия по преобразованию XHTML в XPS в C#
---

Любое преобразование, которое вы хотите выполнить, включает загрузку документа XHTML и его сохранение в формате XPS. Чтобы преобразовать XHTML в XPS, необходимо выполнить несколько обязательных шагов:
1. Загрузите документ XHTML, используя один из конструкторов [HTMLDocument()](https://apireference.aspose.com/html/net/aspose.html/htmldocument).
1. Создайте новый объект [XpsSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions).
1. Используйте метод [ConvertHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/converthtml/), чтобы сохранить XHTML в виде файла XPS. Вам необходимо передать HTMLDocument, XpsSaveOptions и путь к выходному файлу методу ConvertHTML().
1. Файл XPS будет сохранен по указанному пути.

{{<section documentation>}}
---
h2: Конвертация (X)HTML в документации
---

XPS — это формат хранения и просмотра документов, разработанный Microsoft. Он имеет ряд преимуществ, которые поддерживают функции безопасности, такие как цифровые подписи для обеспечения большей безопасности документов и многое другое. Посетите главу документации <a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">Преобразование между форматами</a>, чтобы узнать больше об API. В главе описываются популярные преобразования, а также примеры C# для наиболее распространенных сценариев преобразования.

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