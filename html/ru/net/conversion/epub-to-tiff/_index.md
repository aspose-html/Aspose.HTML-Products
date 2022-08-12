---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать EPUB в TIFF на C# - Онлайн-конвертер EPUB в TIFF
description: Пример C# кода для преобразования EPUB в TIFF. Легко используйте С# API в любом приложении .NET. Попробуйте онлайн-конвертер EPUB в TIFF бесплатно!
url: /net/conversion/epub-to-tiff/
family: html
platformtag: net
feature: conversion
informat: EPUB
outformat: TIFF
otherformats: PDF DOCX XPS BMP JPEG PNG TIFF GIF
---

{{<section banner>}}
---
h1: Конвертировать EPUB в TIFF на C#
h2: Создайте TIFF из исходного файла EPUB с помощью .NET API. Мгновенно конвертируйте формат EPUB в TIFF онлайн!
---

{{<section overview>}}
---
h2: Конвертировать EPUB в TIFF с помощью C#
---

Чтобы преобразовать EPUB в TIFF, мы будем использовать API [Aspose.HTML для .NET](https://products.aspose.com/html/net/), который представляет собой многофункциональный, мощный и простой в использовании документ. API манипуляции и преобразования для платформы C#. EPUB — это открытый формат цифровых книг и публикаций на основе XML, который можно просматривать и читать на различных устройствах. Преобразование EPUB часто требуется для использования преимуществ других форматов. Мощный C# API позволяет быстро и качественно конвертировать EPUB в популярные форматы!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации EPUB
---

Проверьте качество преобразования EPUB в TIFF прямо в браузере! Это быстро, просто, безопасно и совершенно бесплатно! В следующем примере C# показано, как преобразовать документ EPUB. Мы описываем исходный код для чтения EPUB из файла и последующего преобразования EPUB в TIFF с параметрами сохранения по умолчанию. Пожалуйста, загрузите EPUB из локальной файловой системы, выберите выходной формат и запустите пример. Вы сразу получите результат в виде отдельного файла.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter EPUB TIFF GIF PDF DOCX "JPG|JPEG" PNG BMP XPS >}}
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
h2: Шаги по преобразованию EPUB в TIFF на C#
---

Если вы хотите использовать функции преобразования в своем продукте или хотите программно преобразовать EPUB в TIFF, см. приведенный выше пример кода C# или изучите главу «Документация». Вы можете преобразовать EPUB в TIFF с полным контролем над широким диапазоном параметров преобразования. Это могут быть разные сценарии, но любое преобразование EPUB можно выполнить, выполнив несколько обязательных шагов:

1. Откройте существующий файл EPUB.
1. Создайте новый объект [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) в формате TIFF ImageFormat. По умолчанию свойство Format имеет значение [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/).
1. Используйте метод [ConvertEPUB()](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertepub/) класса Converter для сохранения EPUB в виде изображения TIFF. Вам необходимо передать файловый поток EPUB, ImageSaveOptions и путь к выходному файлу методу ConvertEPUB() для преобразования EPUB в TIFF.
1. Файл TIFF будет сохранен по указанному пути.


{{<section documentation>}}
---
h2: Преобразование EPUB в TIFF в документации
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/#convert-epub-to-tiff" target="_blank">Конвертировать EPUB в ТIFF</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/#convert-epub-to-tiff-using-imagesaveoptions" target="_blank" >Конвертировать EPUB в TIFF с помощью ImageSaveOptions</a>

Формат EPUB приобрел популярность как формат электронных книг на основе XML и предназначен для адаптации представления контента к устройству чтения. Иногда требуется получить изображение вместо документов EPUB, например, сделать их переносимыми и легко распространяемыми на различных устройствах, сохранить электронные книги в виде изображений в формате TIFF и т. д. См. статью документации [Конвертировать EPUB в TIFF,](https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/) чтобы узнать больше о функциях преобразования Aspose.HTML для .NET API и рассмотреть примеры C# для наиболее распространенных форматов EPUB в Сценарии преобразования TIFF. В статье вы найдете информацию о том, как преобразовать EPUB в TIFF с помощью методов ConvertEPUB() и как применить ImageSaveOptions.

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