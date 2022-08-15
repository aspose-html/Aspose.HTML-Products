---
translation: true
template: /templates/_template-conversion-child.md
title: Преобразование EPUB в XPS на C# - Онлайн-конвертер EPUB в XPS
description: Пример C# кода для преобразования EPUB в XPS. Легко используйте С# API в любом приложении .NET. Попробуйте онлайн-конвертер EPUB в XPS бесплатно!
url: /net/conversion/epub-to-xps/
family: html
platformtag: net
feature: conversion
informat: EPUB
outformat: XPS
otherformats: DOCX PDF XPS GIF JPEG PNG TIFF BMP
---

{{<section banner>}}
---
h1: Конвертировать EPUB в XPS на C#
h2: Создайте XPS из исходного файла EPUB с помощью .NET API. Мгновенно конвертируйте формат EPUB в XPS онлайн!
---

{{<section overview>}}
---
h2: Конвертировать EPUB в XPS с помощью C#
---

Чтобы преобразовать EPUB в XPS, мы будем использовать API [Aspose.HTML для .NET](https://products.aspose.com/html/net/), который представляет собой многофункциональный, мощный и простой в использовании документ. API манипуляции и преобразования для платформы C#. EPUB — это открытый формат цифровых книг и публикаций на основе XML, который можно просматривать и читать на различных устройствах. Преобразование EPUB в XPS часто требуется для использования преимуществ формата XPS. Разработчики .NET могут легко загружать и конвертировать EPUB в XPS, написав всего несколько строк кода. Мощный C# API позволяет быстро и качественно конвертировать EPUB в популярные форматы!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации EPUB
---

Проверьте качество преобразования EPUB в XPS прямо в браузере! Это быстро, просто, безопасно и совершенно бесплатно! В следующем примере C# показано, как преобразовать документ EPUB. Мы описываем исходный код для чтения EPUB из файла и последующего преобразования EPUB в XPS с параметрами сохранения по умолчанию. Пожалуйста, загрузите EPUB из локальной файловой системы, выберите выходной формат и запустите пример. Вы сразу получите результат в виде отдельного файла.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter EPUB  XPS PDF DOCX "JPG|JPEG" PNG GIF TIFF BMP >}}
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
h2: Шаги по преобразованию EPUB в XPS на C#
---

Если вы хотите использовать функции преобразования в своем продукте или хотите программно преобразовать EPUB в XPS, см. приведенный выше пример кода C# или изучите главу «Документация». API, вы можете преобразовать EPUB в XPS с полным контролем над широким диапазоном параметров преобразования. Это могут быть разные сценарии, но любое преобразование EPUB можно выполнить, выполнив несколько обязательных шагов:

1. Откройте существующий файл EPUB.
1. Создайте новый объект [XpsSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/xpssaveoptions/).
1. Используйте метод [ConvertEPUB()](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertepub/) класса Converter, чтобы сохранить EPUB в виде файла XPS. Вам необходимо передать файловый поток EPUB, PdfSaveOptions и путь к выходному файлу методу ConvertEPUB() для преобразования EPUB в XPS.
1. Файл XPS будет сохранен по указанному пути.

{{<section documentation>}}
---
h2: Преобразование EPUB в XPS в документации
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#epub-to-xps-by-two-lines-of-code" target="_blank">EPUB в XPS с помощью двух строк кода</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#convert-epub-to-xps-using-xpssaveoptions" target="_blank" >Конвертировать EPUB в XPS с помощью XpsSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/#output-stream-providers" target="_blank">Преобразование EPUB в XPS с помощью MemoryStreamProvider</a>

Формат EPUB приобрел популярность как формат электронных книг на основе XML и предназначен для адаптации представления контента к устройству чтения. Файл XPS представляет собой файлы макета страницы, основанные на спецификациях XML Paper, созданных Microsoft. Иногда вам нужно получить документы XPS вместо EPUB, например, сделать их оптимизированными для печати, безопасными и т. д. См. статью документации [Преобразование EPUB в XPS,](https://docs.aspose.com/html/net/converting-between-formats/epub-to-xps/) чтобы узнать больше о функциях преобразования Aspose.HTML для .NET API и рассмотреть примеры C# для наиболее распространенных сценариев преобразования EPUB в XPS. В статье вы найдете информацию о том, как преобразовать EPUB в XPS с помощью методов ConvertEPUB() и как применить параметры XpsSaveOptions и ICreateStreamProvider.

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