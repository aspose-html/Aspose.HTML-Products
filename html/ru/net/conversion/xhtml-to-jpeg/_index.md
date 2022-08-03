---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать XHTML в JPEG
description: Конвертировать XHTML в JPEG на C#. Легко используйте API в любом приложении .NET. Попробуйте онлайн-конвертер XHTML в JPEG бесплатно!
url: /net/conversion/xhtml-to-jpeg/
family: html
platformtag: net
feature: conversion
informat: XHTML
outformat: JPEG
otherformats: PDF DOCX XPS GIF JPEG PNG TIFF BMP HTML MHTML MD
howto: howtoXhtml
---

{{<section banner>}}
---
h1: Конвертировать XHTML в JPEG через C#
h2: Создайте изображение JPEG из исходной страницы XHTML, используя .NET API. Мгновенно конвертируйте XHTML в формат JPEG онлайн!
---

{{<section overview>}}
---
h2: Конвертировать XHTML в JPEG с помощью C#
---

Главной изюминкой [Aspose.HTML .NET](https://products.aspose.com/html/net/) API является функция преобразования. Используя нашу мощную библиотеку, вы можете программно преобразовать формат XHTML в JPEG с полным контролем над различными параметрами преобразования. Любое преобразование, которое вы хотите выполнить, включает в себя загрузку документа XHTML и его сохранение в поддерживаемом формате. Мощный C# API позволяет быстро и качественно конвертировать HTML в популярные форматы!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации XHTML
---

Проверьте качество преобразования XHTML в JPEG прямо в браузере! Пожалуйста, загрузите файл XHTML из локальной файловой системы, выберите требуемый выходной формат из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование XHTML в JPEG будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или XHTML в формат JPEG онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter XHTML "JPG|JPEG" BMP TIFF PNG GIF PDF XPS DOCX MD MHTML>}}
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
h2: Шаги по преобразованию XHTML в JPEG в C#
---

Если вы хотите программно преобразовать XHTML в JPEG, см. приведенный выше пример кода C# или изучите главу «Документация». Во всех случаях любое преобразование XHTML требует некоторых обязательных шагов:
1. Загрузите документ XHTML, используя один из конструкторов [HTMLDocument().](https://reference.aspose.com/html/net/aspose.html/htmldocument/)
1. Создайте новый объект [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) с JPEG ImageFormat. По умолчанию свойство Format имеет значение [PNG.](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/)
1. Используйте метод [ConvertHTML(),](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) чтобы сохранить XHTML как изображение JPEG. Вам необходимо передать HTMLDocument, ImageSaveOptions и путь к выходному файлу методу ConvertHTML().
1. Файл JPEG будет сохранен по указанному пути.

{{<section documentation>}}
---
h2: Конвертация (X)HTML в документации
---

Преобразование между форматами требуется по разным причинам: для работы в привычном, удобном формате или для использования преимуществ разных форматов для конкретных задач. Aspose.HTML for .NET API позволяет быстро и качественно конвертировать (X)HTML в другие популярные форматы. Пожалуйста, посетите главу документации <a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">Преобразование между форматами</a>, чтобы узнать больше об Aspose.HTML for .NET API. В главе описываются популярные преобразования, а также примеры C# для наиболее распространенных сценариев преобразования.

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