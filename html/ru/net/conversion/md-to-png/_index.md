---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать MD в PNG
description: Пример кода C# для преобразования MD в PNG. Легко используйте API в любом приложении .NET. Попробуйте онлайн Конвертер MD в PNG бесплатно!
url: /net/conversion/md-to-png/
family: html
platformtag: net
feature: conversion
informat: MD
outformat: PNG
otherformats: PDF DOCX XPS BMP GIF JPEG TIFF HTML
---

{{<section banner>}}
---
h1: Конвертировать MD в PNG на C#
h2: Преобразование MD в PNG с использованием серверных .NET API. Мгновенно конвертируйте формат MD в PNG онлайн!
---

{{<section overview>}}
---
h2: Преобразование MD в PNG с помощью C#
---

Чтобы преобразовать MD в PNG, мы будем использовать API [Aspose.HTML для .NET](https://products.aspose.com/html/net/), который представляет собой многофункциональный, мощный и простой в использовании документ. API манипуляции и преобразования для платформы C#. Преобразования из Markdown в другие форматы проходят этап преобразования Markdown в HTML. Разработчики .NET могут легко загружать и конвертировать MD в PNG, написав всего несколько строк кода. Мощный C# API позволяет быстро и качественно конвертировать MD в популярные форматы!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации MD
---

Проверьте качество преобразования MD в PNG прямо в браузере! Это быстро, просто, безопасно и совершенно бесплатно! В следующем примере C# показано, как преобразовать документ MD. Мы описываем исходный код для чтения MD из файла и последующего преобразования MD в PNG с параметрами сохранения по умолчанию. Пожалуйста, загрузите MD из локальной файловой системы, выберите выходной формат и запустите пример. Вы сразу получите результат в виде отдельного файла.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MD PNG "JPG|JPEG" GIF BMP XPS TIFF PDF DOCX >}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = Converter.ConvertMarkdown("input.md");
{{#if_output 'PDF'}}
    var options = new PdfSaveOptions();
{{/if_output}}
{{#if_output 'DOCX'}}
    var options = new DocSaveOptions();
{{/if_output}}
{{#if_output 'XPS'}}
    var options = new XpsSaveOptions();
{{/if_output}}
{{#if_output 'BMP' 'JPG' 'GIF' 'PNG' 'TIFF'}}
    var options = new ImageSaveOptions(ImageFormat.{{output param2 camel}});
{{/if_output}}
    Converter.ConvertHTML(document, options, "output.{{output lower}}");   
{{< /app/html/converter>}}


{{<section steps>}}
---
h2: Шаги по преобразованию MD в PNG в C#
---

1. Укажите путь к исходному файлу Markdown.
1. Конвертируйте Markdown в HTML. Используйте метод [ConvertMarkdown(`sourcePath`)](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertmarkdown/#convertmarkdown_4), чтобы сохранить Markdown как документ HTML.
1. Создайте новый объект [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/). По умолчанию свойство Format имеет значение [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/).
1. Используйте метод [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) для преобразования промежуточного документа HTML в изображение PNG. Вам необходимо передать HTMLDocument, ImageSaveOptions и путь к выходному файлу методу ConvertHTML().

{{<section documentation>}}
---
h2: Преобразование MD в PNG в документации
---

PNG — один из наиболее часто используемых форматов файлов изображений. Он поддерживает сжатие изображений без потерь, что делает его популярным среди пользователей. Таким образом, иногда может возникнуть необходимость конвертировать MD в изображение PNG. Пожалуйста, посетите статью документации [Преобразование Markdown в изображение,](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/) чтобы узнать больше о функциях преобразования Aspose.HTML for .NET API и рассмотреть примеры C# для наиболее распространенных сценариев преобразования MD в PNG. В статье вы найдете информацию о том, как <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/#convert-markdown-to-png " target="_blank">Преобразование Markdown в PNG</a> с помощью методов ConvertMarkdown() и способов применения ImageSaveOptions.

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
title: Другие поддерживаемые преобразования MD
subTitle: "Вы также можете конвертировать MD во многие другие форматы файлов:"
---