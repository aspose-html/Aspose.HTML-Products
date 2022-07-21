---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать XHTML в PNG
description: Преобразование XHTML в PNG на C#. Легко используйте API в любом приложении .NET. Попробуйте онлайн-конвертер XHTML в PNG бесплатно!
url: /net/conversion/xhtml-to-png/
family: html
platformtag: net
feature: conversion
informat: XHTML
outformat: PNG
otherformats: PDF DOCX XPS GIF JPEG PNG TIFF BMP HTML MHTML MD
---

{{<section banner>}}
---
h1: Конвертировать XHTML в PNG через C#
h2: Создайте изображение PNG из исходной страницы XHTML с помощью .NET API. Мгновенно конвертируйте формат XHTML в PNG онлайн!
---

{{<section overview>}}
---
h2: Конвертировать XHTML в PNG с помощью C#
---

Главной изюминкой [Aspose.HTML .NET](https://products.aspose.com/html/net/) API является функция преобразования. Используя нашу мощную библиотеку, вы можете программно преобразовать формат XHTML в PNG с полным контролем над различными параметрами преобразования. Любое преобразование, которое вы хотите выполнить, включает в себя загрузку документа XHTML и его сохранение в поддерживаемом формате. Мощный C# API позволяет быстро и качественно конвертировать XHTML в популярные форматы!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации XHTML
---

Проверьте качество преобразования XHTML в PNG прямо в браузере! Пожалуйста, загрузите файл XHTML из локальной файловой системы, выберите требуемый выходной формат из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование XHTML в PNG будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или XHTML в формат PNG онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter XHTML PNG BMP TIFF "JPG|JPEG" GIF PDF XPS DOCX MD MHTML>}}
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
h2: Шаги по преобразованию XHTML в PNG в C#
---

Если вы хотите программно преобразовать XHTML в PNG, см. приведенный выше пример кода C# или изучите главу «Документация». Во всех случаях любое преобразование XHTML требует некоторых обязательных шагов:
1. Загрузите документ XHTML, используя один из конструкторов [HTMLDocument().](https://reference.aspose.com/html/net/aspose.html/htmldocument)
1. Создайте новый объект [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions). По умолчанию свойство Format имеет значение [PNG.](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat)
1. Используйте метод [ConvertHTML(),](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) чтобы сохранить XHTML как изображение PNG. Вам необходимо передать HTMLDocument, ImageSaveOptions и путь к выходному файлу методу ConvertHTML().
1. Файл PNG будет сохранен по указанному пути.

{{<section documentation>}}
---
h2: Конвертация (X)HTML в документации
---

Преобразование между форматами требуется по разным причинам: для работы в привычном, удобном формате или для использования преимуществ разных форматов для конкретных задач. Aspose.HTML for .NET API позволяет быстро и качественно конвертировать (X)HTML в другие популярные форматы. Пожалуйста, посетите главу документации <a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">Преобразование между форматами</a>, чтобы узнать больше об Aspose.HTML for .NET API. В главе описываются популярные преобразователи, а также примеры C# для наиболее распространенных сценариев преобразования.

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