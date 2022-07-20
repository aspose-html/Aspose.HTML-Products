---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать MD в XPS
description: Пример кода C# для преобразования MD в XPS. Легко используйте API преобразователя в ASP.NET или любом приложении .NET. Попробуйте онлайн Конвертер MD в XPS бесплатно!
url: /net/conversion/md-to-xps/
family: html
platformtag: net
feature: conversion
informat: MD
outformat: XPS
otherformats: PDF DOCX JPEG BMP GIF PNG TIFF HTML
---

{{<section banner>}}
---
h1: Преобразование MD в XPS через C#
h2: Высокоточное преобразование MD в XPS с использованием серверных .NET API. Мгновенно конвертируйте формат MD в XPS с помощью нашего бесплатного онлайн-конвертера!
---

{{<section overview>}}
---
h2: Преобразование MD в XPS с помощью C#
---

Чтобы преобразовать MD в XPS, мы будем использовать API [Aspose.HTML для .NET](https://products.aspose.com/html/net/), который представляет собой многофункциональный, мощный и простой в использовании документ. API манипуляции и преобразования для платформы C#. Преобразования из Markdown в другие форматы проходят этап преобразования Markdown в HTML. Разработчики .NET могут легко загружать и преобразовывать MD в XPS, написав всего несколько строк кода. Мощный C# API позволяет быстро и качественно конвертировать MD в популярные форматы!

{{<section demos>}}
---
h2: Бесплатные онлайн-демонстрации конвертера
---

Проверьте качество конвертации MD в XPS прямо в браузере! Это быстро, просто, безопасно и совершенно бесплатно! В следующем примере C# показано, как преобразовать документ MD. Мы описываем исходный код для чтения MD из файла и последующего преобразования MD в XPS с параметрами сохранения по умолчанию. Пожалуйста, загрузите MD из локальной файловой системы, выберите выходной формат и запустите пример. Вы сразу получите результат в виде отдельного файла.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MD XPS DOCX "JPG|JPEG" GIF BMP TIFF PNG PDF >}}
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
h2: Шаги по преобразованию MD в XPS в C#
---
1. Укажите путь к исходному файлу Markdown.
1. Конвертируйте Markdown в HTML. Используйте метод [ConvertMarkdown(`sourcePath`)](https://apireference.aspose.com/html/net/aspose.html.converters.converter/convertmarkdown/methods/4), чтобы сохранить Markdown как документ HTML.
1. Создайте новый объект [XpsSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions).
1. Используйте метод [ConvertHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) для преобразования промежуточного документа HTML в файл XPS. Вам необходимо передать HTMLDocument, DocSaveOptions и путь к выходному файлу методу ConvertHTML().




{{<section documentation>}}
---
h2: Преобразование MD в XPS в документации
---

 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-xps/#convert-markdown-to-xps" target="_blank">Преобразовать Markdown в XPS</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/markdown-to-xps/#convert-markdown-to-xps-using-xpssaveoptions" target="_blank" >Преобразование Markdown в XPS с помощью XpsSaveOptions</a>

Markdown часто используется в качестве формата для документации и файлов readme, поскольку он позволяет писать в удобном для чтения и написания стиле. XPS — это формат хранения и просмотра документов, разработанный Microsoft. Он имеет ряд преимуществ, которые поддерживают функции безопасности, такие как цифровые подписи для обеспечения большей безопасности документов и многое другое. Преобразование MD в XPS часто требуется для использования преимуществ формата XPS для конкретных задач. Пожалуйста, посетите статью документации [Преобразование Markdown в XPS](https://docs.aspose.com/html/net/converting-between-formats/markdown-to-xps/), чтобы узнать больше об Aspose.HTML для .NET API. функции преобразования и рассмотреть примеры C# для наиболее распространенных сценариев преобразования MD в XPS. В статье вы найдете информацию о том, как преобразовать Markdown в XPS с помощью методов ConvertMarkdown() и как применить XpsSaveOptions.

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