---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать EPUB в PNG — C#
description: Пример C# кода для преобразования EPUB в PNG. Попробуйте онлайн-конвертер EPUB в PNG бесплатно!
url: /net/conversion/epub-to-png/
family: html
platformtag: net
feature: conversion
informat: EPUB
outformat: PNG
otherformats: PDF DOCX XPS BMP JPEG GIF TIFF
---

{{<section banner>}}
---
h1: Конвертировать EPUB в PNG на C#
h2: Сгенерируйте PNG из исходного файла EPUB, используя .NET API. Мгновенно конвертируйте формат EPUB в PNG онлайн!
---

{{<section overview>}}
---
h2: Конвертировать EPUB в PNG с помощью C#
---

Чтобы преобразовать EPUB в PNG, мы будем использовать API [Aspose.HTML для .NET](https://products.aspose.com/html/net/), который представляет собой многофункциональный, мощный и простой в использовании документ. API манипуляции и преобразования для платформы C#. EPUB — это открытый формат цифровых книг и публикаций на основе XML, который можно просматривать и читать на различных устройствах. Преобразование EPUB часто требуется для использования преимуществ других форматов. Вы можете программно преобразовать EPUB в PNG с полным контролем над широким диапазоном параметров преобразования. Мощный C# API позволяет быстро и качественно конвертировать EPUB в популярные форматы!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации EPUB
---

Проверьте качество преобразования EPUB в PNG прямо в браузере! Это быстро, просто, безопасно и совершенно бесплатно! В следующем примере C# показано, как преобразовать документ EPUB. Мы описываем исходный код для чтения EPUB из файла и последующего преобразования EPUB в PNG с параметрами сохранения по умолчанию. Пожалуйста, загрузите EPUB из локальной файловой системы, выберите выходной формат и запустите пример. Вы сразу получите результат в виде отдельного файла.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter EPUB PNG GIF PDF DOCX "JPG|JPEG" BMP TIFF XPS >}}
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
h2: Шаги по преобразованию EPUB в PNG на C#
---

Если вы хотите использовать функцию преобразования в своем продукте или хотите программно преобразовать EPUB в PNG, см. приведенный выше пример кода C# или изучите главу «Документация». Это могут быть разные сценарии, но любое преобразование EPUB можно выполнить, выполнив несколько обязательных шагов:

1. Откройте существующий файл EPUB.
1. Создайте новый объект [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/). По умолчанию свойство Format имеет значение [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/).
1. Используйте метод [ConvertEPUB()](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertepub/) класса Converter, чтобы сохранить EPUB в виде изображения PNG. Вам необходимо передать файловый поток EPUB, ImageSaveOptions и путь к выходному файлу в метод ConvertEPUB() для преобразования EPUB в PNG.
1. Файл PNG будет сохранен по указанному пути.




{{<section documentation>}}
---
h2: Преобразование EPUB в PNG в документации
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#epub-to-png-by-a-single-of-code " target="_blank">EPUB в PNG одной строкой кода</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#convert-epub-to-png-using-imagesaveoptions" target="_blank" >Конвертировать EPUB в PNG с помощью ImageSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/#output-stream-providers" target="_blank">Конвертировать EPUB в PNG, используя MemoryStreamProvider</a>

Формат EPUB приобрел популярность как формат электронных книг на основе XML и предназначен для адаптации представления контента к устройству чтения. Иногда требуется получить изображение вместо документов EPUB, например, сделать их переносимыми и легко распространяемыми на различных устройствах, создать галерею изображений из электронных книг и т. д. Формат файлов PNG поддерживает сжатие изображений без потерь, что делает его популярным среди пользователей. Пожалуйста, посетите статью документации [Преобразование EPUB в PNG](https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/), чтобы узнать больше о функциях преобразования Aspose.HTML for .NET API и рассмотреть примеры C# для наиболее распространенных сценариев преобразования EPUB в PNG. В статье вы найдете информацию о том, как преобразовать EPUB в PNG с помощью методов ConvertEPUB() и как применить параметры ImageSaveOptions и ICreateStreamProvider.

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