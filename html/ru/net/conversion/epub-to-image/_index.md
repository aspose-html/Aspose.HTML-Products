---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать EPUB в изображение — C#
description: Пример кода C# для преобразования EPUB в изображение. Попробуйте онлайн-конвертер EPUB в изображения бесплатно!
url: /net/conversion/epub-to-image/
family: html
platformtag: net
feature: conversion
informat: EPUB
outformat: "Image"
otherformats: PDF DOCX XPS JPEG BMP GIF PNG TIFF
---

{{<section banner>}}
---
h1: Конвертировать EPUB в изображение на C#
h2: Создавайте изображения из исходного файла EPUB с помощью .NET API. Мгновенно конвертируйте EPUB в формат изображения онлайн!
---

{{<section overview>}}
---
h2: Конвертировать EPUB в изображение с помощью C#
---

Чтобы преобразовать EPUB в изображение, мы будем использовать API [Aspose.HTML для .NET](https://products.aspose.com/html/net/), который представляет собой многофункциональный, мощный и простой в использовании документ. API манипуляции и преобразования для платформы C#. EPUB — это открытый формат цифровых книг и публикаций на основе XML, который можно просматривать и читать на различных устройствах. Преобразование EPUB часто требуется для использования преимуществ других форматов. Вы можете программно преобразовывать форматы EPUB в изображения с полным контролем над широким диапазоном параметров преобразования. Мощный C# API позволяет быстро и качественно конвертировать EPUB в изображения!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации EPUB
---

Проверьте качество преобразования EPUB в изображение прямо в браузере! Это быстро, просто, безопасно и совершенно бесплатно! В следующем примере C# показано, как преобразовать документ EPUB. Мы описываем исходный код для чтения EPUB из файла и последующего преобразования EPUB в формат растрового изображения с параметрами сохранения по умолчанию. Пожалуйста, загрузите EPUB из локальной файловой системы, выберите выходной формат и запустите пример. Вы сразу получите результат в виде отдельного файла.

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter EPUB "JPG|JPEG" GIF PDF DOCX PNG BMP TIFF XPS >}}
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
h2: Шаги по преобразованию EPUB в изображение на C#
---

Если вы хотите использовать функцию преобразования в своем продукте или хотите программно преобразовать EPUB в изображение, см. приведенный выше пример кода C# или изучите главу «Документация». Это могут быть разные сценарии, но любое преобразование EPUB можно выполнить, выполнив несколько обязательных шагов:

1. Откройте существующий файл EPUB.
1. Создайте новый объект [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) и укажите ImageFormat. По умолчанию свойство Format имеет значение [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/).
1. Используйте метод [ConvertEPUB()](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertepub/) класса Converter, чтобы сохранить EPUB как изображение. Вам необходимо передать файловый поток EPUB, ImageSaveOptions и путь к выходному файлу в метод ConvertEPUB() для преобразования EPUB в изображение.
1. Файл изображения будет сохранен по указанному пути.

{{<section documentation>}}
---
h2: Преобразование EPUB в изображение в документации
---

Формат EPUB приобрел популярность как формат электронных книг на основе XML и предназначен для адаптации представления контента к устройству чтения. Иногда требуется получить изображение вместо документов EPUB, например, сделать их переносимыми и легко распространяемыми на различных устройствах, создать галерею изображений из электронных книг и т. д. Пожалуйста, посетите главу документации [Преобразование между форматами](https:// docs.aspose.com/html/net/converting-between-formats/), чтобы узнать больше о функциях преобразования Aspose.HTML для .NET API и рассмотреть примеры C# для наиболее распространенных сценариев преобразования EPUB в изображение. В статьях вы найдете информацию о том, как преобразовать EPUB в изображение с помощью методов ConvertEPUB() и как применить ImageSaveOptions или [ICreateStreamProvider](https://reference.aspose.com/html/net/aspose.html.io/icreatestreamprovider/).

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#epub-to-jpg-by-two-lines-of-code" target="_blank">EPUB в JPG двумя строками кода</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#convert-epub-to-jpg-using-imagesaveoptions" target="_blank" >Конвертировать EPUB в JPG с помощью ImageSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-jpg/#output-stream-providers" target="_blank">Конвертировать EPUB в JPG, используя MemoryStreamProvider</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-png/" target="_blank">Конвертировать EPUB в PNG</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-bmp/" target="_blank">Конвертировать EPUB в BMP</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-tiff/" target="_blank">Конвертировать EPUB в TIFF</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/epub-to-gif/" target="_blank">Конвертировать EPUB в GIF</a>


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