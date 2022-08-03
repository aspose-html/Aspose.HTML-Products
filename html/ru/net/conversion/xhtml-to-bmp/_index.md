---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать XHTML в BMP
description: Преобразование XHTML в BMP на C#. Легко используйте API в любом приложении .NET. Попробуйте онлайн-конвертер XHTML в BMP бесплатно!
url: /net/conversion/xhtml-to-bmp/
family: html
platformtag: net
feature: conversion
informat: XHTML
outformat: BMP
otherformats: PDF DOCX XPS GIF JPEG PNG TIFF BMP HTML MHTML MD
howto: howtoXhtml
---

{{<section banner>}}
---
h1: Конвертировать XHTML в BMP на C#
h2: Создайте BMP из исходной страницы XHTML с помощью .NET API. Мгновенно конвертируйте XHTML в формат BMP онлайн!
---

{{<section overview>}}
---
h2: Конвертировать XHTML в BMP с помощью C#
---

Главной изюминкой [Aspose.HTML .NET](https://products.aspose.com/html/net/) API является функция преобразования. Используя нашу мощную библиотеку, вы можете программно преобразовать XHTML в формат BMP с полным контролем над различными параметрами преобразования. Любое преобразование, которое вы хотите выполнить, включает в себя загрузку документа XHTML и его сохранение в поддерживаемом формате. Мощный C# API позволяет быстро и качественно конвертировать XHTML в популярные форматы!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации XHTML
---

Проверьте качество преобразования XHTML в BMP прямо в браузере! Пожалуйста, загрузите файл XHTML из локальной файловой системы, выберите требуемый выходной формат из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование XHTML в BMP будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или XHTML в формат BMP онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter XHTML BMP TIFF PNG "JPG|JPEG" GIF PDF XPS DOCX MD MHTML>}}
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
h2: Шаги по преобразованию XHTML в BMP на C#
---

Если вы хотите программно преобразовать XHTML в BMP, см. приведенный выше пример кода C# или изучите главу «Документация». Во всех случаях любое преобразование XHTML требует некоторых обязательных шагов:
1. Загрузите документ XHTML, используя один из конструкторов [HTMLDocument().](https://reference.aspose.com/html/net/aspose.html/htmldocument/)
1. Создайте новый объект [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) с форматом изображения BMP. По умолчанию свойство Format имеет значение [PNG.](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/)
1. Используйте метод [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/), чтобы сохранить XHTML в виде файла BMP. Вам необходимо передать HTMLDocument, ImageSaveOptions и путь к выходному файлу методу ConvertHTML().
1. Файл BMP будет сохранен по указанному пути.

{{<section documentation>}}
---
h2: Преобразование (X)HTML в документации
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