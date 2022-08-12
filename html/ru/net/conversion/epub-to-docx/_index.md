---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать EPUB в DOCX
description: Пример C# кода для преобразования EPUB в DOCX. Легко используйте C# API в любом приложении .NET. Попробуйте онлайн-конвертер EPUB в DOCX бесплатно!
url: /net/conversion/epub-to-docx/
family: html
platformtag: net
feature: conversion
informat: EPUB
outformat: DOCX
otherformats: PDF DOCX XPS GIF JPEG PNG TIFF BMP
---

{{<section banner>}}
---
h1: Конвертировать EPUB в DOCX на C#
h2: Создайте DOCX из исходного файла EPUB с помощью .NET API. Мгновенно конвертируйте EPUB в формат DOCX с помощью нашего бесплатного онлайн-конвертера!
---

{{<section overview>}}
---
h2: Конвертировать EPUB в DOCX с помощью C#
---

Чтобы преобразовать EPUB в DOCX, мы будем использовать API [Aspose.HTML для .NET,](https://products.aspose.com/html/net/) который представляет собой многофункциональный, мощный и простой в использовании документ. API манипуляции и преобразования для платформы C#. EPUB — это открытый формат цифровых книг и публикаций на основе XML, который можно просматривать и читать на различных устройствах. DOCX — широко известный формат документов Microsoft Word. Этот формат популярен, потому что он поддерживает широкий спектр функций форматирования и предлагает пользователям множество вариантов для написания любого типа документа. Разработчики .NET могут легко загружать и конвертировать EPUB в DOCX, написав всего несколько строк кода.

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации EPUB
---

Проверьте качество преобразования EPUB в DOCX прямо в браузере! Это быстро, просто, безопасно и совершенно бесплатно! В следующем примере C# показано, как преобразовать документ EPUB. Мы описываем исходный код для чтения EPUB из файла и последующего преобразования EPUB в DOCX с параметрами сохранения по умолчанию. Пожалуйста, загрузите EPUB из локальной файловой системы, выберите выходной формат и запустите пример. Вы сразу получите результат в виде отдельного файла.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter EPUB DOCX PDF "JPG|JPEG" PNG GIF TIFF XPS BMP >}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var stream = File.OpenRead(DataDir + "input.epub");
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
    Converter.ConvertEPUB(stream, options, "output.{{output lower}}");   
{{< /app/html/converter>}}


{{<section steps>}}
---
h2: Шаги по преобразованию EPUB в DOCX на C#
---

Если вы хотите использовать функции преобразования в своем продукте или хотите программно преобразовать EPUB в DOCX, см. приведенный выше пример кода C# или изучите главу «Документация». Во всех случаях любое преобразование требует некоторых обязательных шагов:

1. Откройте существующий файл EPUB.
1. Создайте новый объект [DocSaveOptions.](https://reference.aspose.com/html/net/aspose.html.saving/docsaveoptions/)
1. Используйте метод [ConvertEPUB()](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertepub/) класса Converter, чтобы сохранить EPUB в виде файла DOCX. Вам необходимо передать файловый поток EPUB, DocSaveOptions и путь к выходному файлу методу ConvertEPUB() для преобразования EPUB в DOCX.
1. Файл DOCX будет сохранен по указанному пути.

{{<section documentation>}}
---
h2: Преобразование EPUB в DOCX в документации
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#epub-to-docx-by-two-lines-of-code" target="_blank">EPUB в DOCX двумя строками кода</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#convert-epub-to-docx-using-docsaveoptions" target="_blank" >Конвертировать EPUB в DOCX с помощью DocSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/#output-stream-providers" target="_blank">Конвертировать EPUB в DOCX, используя MemoryStreamProvider</a>

Формат EPUB приобрел популярность как формат электронных книг на основе XML и предназначен для адаптации представления контента к устройству чтения. Преобразование EPUB в DOCX часто требуется, чтобы использовать формат DOCX для конкретных пользовательских задач. Пожалуйста, посетите статью документации [Преобразование EPUB в DOCX,](https://docs.aspose.com/html/net/converting-between-formats/epub-to-docx/) чтобы узнать больше о функциях преобразования Aspose.HTML for .NET API и рассмотреть примеры C# для наиболее распространенных сценариев преобразования EPUB в DOCX. В статье вы найдете информацию о том, как преобразовать EPUB в DOCX с помощью методов ConvertEPUB() и как применить параметры DocSaveOptions и ICreateStreamProvider.

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
title: Другие поддерживаемые преобразования EPUB
subTitle: "Вы также можете конвертировать EPUB в другие форматы файлов:"
---