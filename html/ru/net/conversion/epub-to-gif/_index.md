---
translation: true
template: /templates/_template-conversion-child.md
title: Преобразование EPUB в GIF - C# - онлайн-конвертер EPUB в GIF
description: Пример кода для преобразования EPUB в GIF на C#. Легко используйте С# API в любом приложении .NET. Попробуйте онлайн-конвертер EPUB в GIF бесплатно!
url: /net/conversion/epub-to-gif/
family: html
platformtag: net
feature: conversion
informat: EPUB
outformat: GIF
otherformats: PDF DOCX XPS BMP JPEG PNG TIFF
---

{{<section banner>}}
---
h1: Конвертировать EPUB в GIF на C#
h2: Создание GIF из исходного файла EPUB с помощью .NET API. Конвертируйте EPUB в GIF с помощью бесплатного онлайн-конвертера!
---

{{<section overview>}}
---
h2: Преобразование EPUB в GIF с помощью C#
---

Чтобы преобразовать EPUB в GIF, мы будем использовать API [Aspose.HTML для .NET,](https://products.aspose.com/html/net/) который представляет собой многофункциональный, мощный и простой в использовании документ. API манипуляции и преобразования для платформы C#. EPUB — это открытый формат цифровых книг и публикаций на основе XML, который можно просматривать и читать на различных устройствах. Преобразование EPUB часто требуется для использования преимуществ других форматов. Вы можете программно преобразовать EPUB в GIF с полным контролем над широким диапазоном параметров преобразования. Мощный C# API позволяет быстро и качественно конвертировать EPUB в популярные форматы!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации EPUB
---

Проверьте качество преобразования EPUB в GIF прямо в браузере! Это быстро, просто, безопасно и совершенно бесплатно! В следующем примере C# показано, как преобразовать документ EPUB. Мы описываем исходный код для чтения EPUB из файла и последующего преобразования EPUB в GIF с параметрами сохранения по умолчанию. Пожалуйста, загрузите EPUB из локальной файловой системы, выберите выходной формат и запустите пример. Вы сразу получите результат в виде отдельного файла.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter EPUB GIF PDF DOCX "JPG|JPEG" PNG BMP TIFF XPS >}}
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
h2: Шаги по преобразованию EPUB в GIF на C#
---

Если вы хотите использовать функции преобразования в своем продукте или хотите программно преобразовать EPUB в GIF, см. приведенный выше пример кода C# или изучите главу «Документация». Это могут быть разные сценарии, но любое преобразование EPUB можно выполнить, выполнив несколько обязательных шагов:

1. Откройте существующий файл EPUB.
1. Создайте новый объект [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) с GIF ImageFormat. По умолчанию свойство Format имеет значение [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/).
1. Используйте метод [ConvertEPUB()](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertepub/) класса Converter для сохранения EPUB в виде изображения GIF. Вам необходимо передать файловый поток EPUB, ImageSaveOptions и путь к выходному файлу в метод ConvertEPUB() для преобразования EPUB в GIF.
1. Файл GIF будет сохранен по указанному пути.

{{<section documentation>}}
---
h2: Преобразование EPUB в GIF в документации
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/#convert-epub-to-gif" target="_blank">Конвертировать EPUB в GIF</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/#convert-epub-to-gif-using-imagesaveoptions" target="_blank" >Конвертировать EPUB в GIF с помощью ImageSaveOptions</a>

GIF — это популярный формат изображения, который часто используется в веб-публикациях. Преобразование EPUB в GIF позволяет сохранить документ EPUB в виде изображения GIF. Пожалуйста, посетите статью документации [Преобразование EPUB в GIF](https://docs.aspose.com/html/net/converting-between-formats/html-to-gif/), чтобы узнать больше о функциях преобразования Aspose.HTML for .NET API и рассмотреть примеры C# для наиболее распространенных сценариев преобразования EPUB в GIF. В статье вы найдете информацию о том, как преобразовать EPUB в GIF с помощью методов ConvertEPUB() и как применить параметры ImageSaveOptions и ICreateStreamProvider.

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