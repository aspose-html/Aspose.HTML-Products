---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать MD в PDF — C#
description: Пример кода C# для преобразования MD в PDF. Легко используйте API в любом приложении .NET. Попробуйте онлайн-конвертер MD в PDF бесплатно!
url: /net/conversion/md-to-pdf/
family: html
platformtag: net
feature: conversion
informat: MD
outformat: PDF
otherformats: XPS DOCX JPEG BMP GIF PNG TIFF HTML
howto: howtoMd
---

{{<section banner>}}
---
h1: Конвертировать MD в PDF на C#
h2: Преобразование MD в PDF с использованием серверных .NET API. Мгновенно конвертируйте формат MD в PDF онлайн!
---

{{<section overview>}}
---
h2: Преобразование MD в PDF с помощью C#
---

Чтобы преобразовать MD в PDF, мы будем использовать API [Aspose.HTML для .NET,](https://products.aspose.com/html/net/) который представляет собой многофункциональный, мощный и простой в использовании документ. API манипуляции и преобразования для платформы C#. Преобразования из Markdown в другие форматы проходят этап преобразования Markdown в HTML. Разработчики .NET могут легко загружать и конвертировать MD в PDF, написав всего несколько строк кода. Мощный C# API позволяет быстро и качественно конвертировать MD в популярные форматы!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации MD
---

Проверьте качество преобразования MD в PDF прямо в браузере! Это быстро, просто, безопасно и совершенно бесплатно! В следующем примере C# показано, как преобразовать документ MD. Мы описываем исходный код для чтения MD из файла и последующего преобразования MD в PDF с параметрами сохранения по умолчанию. Пожалуйста, загрузите MD из локальной файловой системы, выберите выходной формат и запустите пример. Вы сразу получите результат в виде отдельного файла.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MD PDF DOCX "JPG|JPEG" GIF BMP XPS TIFF PNG >}}
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
h2: Шаги по преобразованию MD в PDF на C#
---
1. Укажите путь к исходному файлу Markdown.
1. Конвертируйте Markdown в HTML. Используйте метод [ConvertMarkdown(`sourcePath`)](https://reference.aspose.com/html/net/aspose.html.converters.converter/convertmarkdown/methods/4), чтобы сохранить Markdown как документ HTML.
1. Создайте новый объект [PdfSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions).
1. Используйте метод [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) для преобразования промежуточного документа HTML в файл PDF. Вам необходимо передать HTMLDocument, DocSaveOptions и путь к выходному файлу методу ConvertHTML().

{{<section documentation>}}
---
h2: Преобразование MD в PDF в документации
---

Markdown часто используется в качестве формата для документации и файлов readme, поскольку он позволяет писать в удобном для чтения и написания стиле. Преобразование MD в PDF часто требуется, чтобы использовать преимущества формата PDF для конкретных задач. Пожалуйста, посетите статью документации [Преобразование Markdown в PDF](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-pdf/), чтобы узнать больше о функциях преобразования Aspose.HTML for .NET API и рассмотреть примеры C# для наиболее распространенных сценариев преобразования MD в PDF. В статье вы найдете информацию о том, как преобразовать Markdown в PDF с помощью методов ConvertMarkdown() и как применить PdfSaveOptions.

 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-pdf/#convert-markdown-to-pdf" target="_blank">Преобразовать Markdown в PDF</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-pdf/#convert-markdown-to-pdf-using-pdfsaveoptions" target="_blank" >Преобразование Markdown в PDF с помощью PdfSaveOptions</a>

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