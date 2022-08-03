---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать MD в изображение
description: Пример кода C# для преобразования MD в изображение. Легко используйте API в любом приложении .NET. Попробуйте онлайн MD to Image Converter бесплатно!
url: /net/conversion/md-to-image/
family: html
platformtag: net
feature: conversion
informat: MD
outformat: Image
otherformats: PDF DOCX XPS JPEG BMP GIF PNG TIFF HTML
howto: howtoMd
---

{{<section banner>}}
---
h1: Конвертировать MD в изображение на C#
h2: Преобразование MD в изображение с использованием серверных .NET API. Мгновенно конвертируйте MD в формат изображения онлайн!
---

{{<section overview>}}
---
h2: Преобразование MD в изображение с помощью C#
---

Чтобы преобразовать MD в изображение, мы будем использовать API [Aspose.HTML для .NET](https://products.aspose.com/html/net/), который представляет собой многофункциональный, мощный и простой в использовании документ. API манипуляции и преобразования для платформы C#. Преобразования из Markdown в другие форматы проходят этап преобразования Markdown в HTML. Разработчики .NET могут легко загружать и преобразовывать MD в изображение, написав всего несколько строк кода. Мощный C# API позволяет быстро и качественно конвертировать MD в популярные форматы!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации MD
---

Проверьте качество преобразования MD в изображение прямо в браузере! Это быстро, просто, безопасно и совершенно бесплатно! В следующем примере C# показано, как преобразовать документ MD. Мы описываем исходный код для чтения MD из файла и последующего преобразования MD в растровое изображение с параметрами сохранения по умолчанию. Пожалуйста, загрузите MD из локальной файловой системы, выберите выходной формат и запустите пример. Вы сразу получите результат в виде отдельного файла.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MD "JPG|JPEG" GIF BMP XPS TIFF PNG PDF DOCX >}}
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
h2: Шаги по преобразованию MD в изображение на C#
---

1. Укажите путь к исходному файлу Markdown.
1. Конвертируйте Markdown в HTML. Используйте метод [ConvertMarkdown(`sourcePath`)](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertmarkdown/#convertmarkdown_4), чтобы сохранить Markdown как документ HTML.
1. Создайте новый объект [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) и укажите ImageFormat. По умолчанию свойство Format имеет значение [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/).
1. Используйте метод [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) для преобразования промежуточного документа HTML в изображение. Вам необходимо передать HTMLDocument, ImageSaveOptions и путь к выходному файлу методу ConvertHTML().

{{<section documentation>}}
---
h2: Преобразование MD в изображение в документации
---

Markdown — общепринятый язык разметки, который часто используется в качестве формата для документации и файлов readme. Используя библиотеку Aspose.HTML .NET, вы можете конвертировать Markdown в форматы изображений, такие как JPG, PNG, GIF, TIFF и BMP, через C#. Пожалуйста, посетите статью документации [Преобразование Markdown в изображение](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/), чтобы узнать больше о функциях преобразования API и принять во внимание Примеры C# для наиболее распространенных сценариев преобразования MD в изображение. В статье вы найдете информацию о том, как преобразовать Markdown в изображение с помощью методов ConvertMarkdown() и как применить ImageSaveOptions.

 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/#convert-markdown-to-jpg" target="_blank">Преобразовать Markdown в JPG</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/#convert-markdown-to-png" target="_blank">Преобразовать Markdown в PNG</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/#convert-markdown-to-bmp" target="_blank">Преобразовать Markdown в BMP</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/#convert-markdown-to-gif" target="_blank">Преобразовать Markdown в GIF</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-image/#convert-markdown-to-tiff" target="_blank">Преобразовать Markdown в TIFF</a>

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