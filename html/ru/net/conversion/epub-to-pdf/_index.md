---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать EPUB в PDF
description: Пример C# кода для преобразования EPUB в PDF. Попробуйте онлайн-конвертер EPUB в PDF бесплатно!
url: /net/conversion/epub-to-pdf/
family: html
platformtag: net
feature: conversion
informat: EPUB
outformat: PDF
otherformats: DOCX XPS GIF JPEG PNG TIFF BMP
---

{{<section banner>}}
---
h1: Конвертировать EPUB в PDF на C#
h2: Создавайте PDF из исходного файла EPUB с помощью .NET API. Мгновенно конвертируйте формат EPUB в PDF с помощью нашего бесплатного онлайн-конвертера!
---

{{<section overview>}}
---
h2: Преобразование EPUB в PDF с помощью C#
---

Чтобы преобразовать EPUB в PDF, мы будем использовать API [Aspose.HTML для .NET](https://products.aspose.com/html/net/), который представляет собой многофункциональный, мощный и простой в использовании документ. API манипуляции и преобразования для платформы C#. EPUB — это открытый формат цифровых книг и публикаций на основе XML, который можно просматривать и читать на различных устройствах. Преобразование EPUB в PDF часто требуется для использования преимуществ формата PDF. Разработчики .NET могут легко загружать и конвертировать EPUB в PDF, написав всего несколько строк кода. Мощный C# API позволяет быстро и качественно конвертировать EPUB в популярные форматы!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации EPUB
---

Проверьте качество преобразования EPUB в PDF прямо в браузере! Это быстро, просто, безопасно и совершенно бесплатно! В следующем примере C# показано, как преобразовать документ EPUB. Мы описываем исходный код для чтения EPUB из файла и последующего преобразования EPUB в PDF с параметрами сохранения по умолчанию. Пожалуйста, загрузите EPUB из локальной файловой системы, выберите выходной формат и запустите пример. Вы сразу получите результат в виде отдельного файла.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter EPUB PDF DOCX "JPG|JPEG" PNG GIF TIFF XPS BMP >}}
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
h2: Шаги по преобразованию EPUB в PDF на C#
---

Если вы хотите использовать функции преобразования в своем продукте или хотите программно преобразовать EPUB в PDF, см. приведенный выше пример кода C# или изучите главу «Документация». API, вы можете преобразовать EPUB в PDF с полным контролем над широким диапазоном параметров преобразования. Это могут быть разные сценарии, но любое преобразование EPUB можно выполнить, выполнив несколько обязательных шагов:

1. Откройте существующий файл EPUB.
1. Создайте новый объект [PdfSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions/).
1. Используйте метод [ConvertEPUB()](https://reference.aspose.com/html/net/aspose.html.converters.converter/convertepub/) класса Converter, чтобы сохранить EPUB в виде файла PDF. Вам необходимо передать файловый поток EPUB, PdfSaveOptions и путь к выходному файлу методу ConvertEPUB() для преобразования EPUB в PDF.
1. Файл PDF будет сохранен по указанному пути.

{{<section documentation>}}
---
h2: Преобразование EPUB в PDF в документации
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#epub-to-pdf-by-two-lines-of-code" target="_blank">EPUB в PDF двумя строками кода</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#convert-epub-to-pdf-using-pdfsaveoptions" target="_blank" >Конвертировать EPUB в PDF с помощью PdfSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/#output-stream-providers" target="_blank">преобразование EPUB в PDF с помощью MemoryStreamProvider</a>

Формат EPUB приобрел популярность как формат электронных книг на основе XML и предназначен для адаптации представления контента к устройству чтения. Иногда вам нужно получить PDF-документы вместо EPUB, например, сделать их оптимизированными для печати, безопасными и надежными, сделать копии документов EPUB и т. д. Пожалуйста, посетите статью документации [Преобразование EPUB в PDF,](https://docs.aspose.com/html/net/converting-between-formats/epub-to-pdf/) чтобы узнать больше о функциях преобразования Aspose.HTML для .NET API и рассмотреть примеры C# для наиболее распространенных сценариев преобразования EPUB в PDF. В статье вы найдете информацию о том, как преобразовать EPUB в PDF с помощью методов ConvertEPUB() и как применить параметры PdfSaveOptions и ICreateStreamProvider.

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
subTitle: "Вы также можете конвертировать EPUB во многие другие форматы файлов:"
---