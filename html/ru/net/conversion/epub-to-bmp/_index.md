---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать EPUB в BMP
description: Пример C# кода для преобразования EPUB в BMP. Попробуйте онлайн-конвертер EPUB в BMP бесплатно!
url: /net/conversion/epub-to-bmp/
family: html
platformtag: net
feature: conversion
informat: EPUB
outformat: BMP
otherformats: PDF DOCX XPS GIF JPEG PNG TIFF
---

{{<section banner>}}
---
h1: Конвертировать EPUB в BMP через C#
h2: Создайте BMP из исходного файла EPUB с помощью .NET API. Мгновенно конвертируйте формат EPUB в BMP с помощью нашего бесплатного онлайн-конвертера!
---

{{<section overview>}}
---
h2: Конвертировать EPUB в BMP с помощью C#
---

Чтобы преобразовать EPUB в BMP, мы будем использовать API [Aspose.HTML для .NET](https://products.aspose.com/html/net/), который представляет собой многофункциональный, мощный и простой в использовании документ. API манипуляции и преобразования для платформы C#. EPUB — это открытый формат цифровых книг и публикаций на основе XML, который можно просматривать и читать на различных устройствах. Преобразование EPUB часто требуется для использования преимуществ других форматов. Вы можете преобразовать EPUB в BMP программно с полным контролем над широким диапазоном параметров преобразования. Мощный C# API позволяет быстро и качественно конвертировать EPUB в популярные форматы!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации EPUB
---

Проверьте качество преобразования EPUB в BMP прямо в браузере! Это быстро, просто, безопасно и совершенно бесплатно! В следующем примере C# показано, как преобразовать документ EPUB. Мы описываем исходный код для чтения EPUB из файла и последующего преобразования EPUB в BMP с параметрами сохранения по умолчанию. Пожалуйста, загрузите EPUB из локальной файловой системы, выберите выходной формат и запустите пример. Вы сразу получите результат в виде отдельного файла.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter EPUB BMP PDF DOCX "JPG|JPEG" PNG GIF TIFF XPS >}}
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
h2: Шаги по преобразованию EPUB в BMP на C#
---

Если вы хотите использовать функции преобразования в своем продукте или хотите программно преобразовать EPUB в BMP, рассмотрите приведенный выше пример кода C# или изучите главу «Документация». Во всех случаях любое преобразование требует некоторых обязательных шагов:

1. Откройте существующий файл EPUB.
1. Создайте новый объект [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) с форматом изображения BMP. По умолчанию свойство Format имеет значение [PNG.](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/)
1. Используйте метод [ConvertEPUB()](https://reference.aspose.com/html/net/aspose.html.converters.converter/convertepub/) класса Converter для сохранения EPUB в виде изображения BMP. Вам необходимо передать файловый поток EPUB, ImageSaveOptions и путь к выходному файлу в метод ConvertEPUB() для преобразования EPUB в BMP.
1. Файл BMP будет сохранен по указанному пути.

{{<section documentation>}}
---
h2: Преобразование EPUB в BMP в документации
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/#convert-epub-to-bmp" target="_blank">Конвертировать EPUB в BMP</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/#convert-epub-to-bmp-using-imagesaveoptions" target="_blank" >Конвертировать EPUB в BMP с помощью ImageSaveOptions</a>

Файлы BMP представляют собой файлы растровых изображений, которые используются для хранения высококачественных растровых цифровых изображений. Таким образом, иногда может возникнуть необходимость конвертировать EPUB в BMP. Пожалуйста, посетите статью документации [Преобразование EPUB в BMP,](https://docs.aspose.com/html/net/converting-between-formats/html-to-bmp/) чтобы узнать больше о функциях преобразования Aspose.HTML for .NET API и рассмотреть примеры C# для наиболее распространенных сценариев преобразования EPUB в BMP. В статье вы найдете информацию о том, как преобразовать EPUB в BMP с помощью методов ConvertEPUB() и как применить параметры ImageSaveOptions и ICreateStreamProvider.

{{<section online-converters>}}
---
h2: Бесплатные онлайн Конвертеры
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