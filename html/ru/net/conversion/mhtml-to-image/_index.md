---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать MHTML в изображение
description: Преобразование MHTML в изображение на C#. Легко используйте API в любом приложении .NET. Попробуйте онлайн MHTML to Image Converter бесплатно!
url: /net/conversion/mhtml-to-image/
family: html
platformtag: net
feature: conversion
informat: MHTML
outformat: Image
otherformats: DOCX PDF XPS BMP GIF JPEG PNG TIFF
---

{{<section banner>}}
---
h1: Конвертировать MHTML в изображение на C#
h2: Высокоточное преобразование MHTML в изображение с использованием .NET API. Мгновенно конвертируйте MHTML в формат изображения онлайн!
---

{{<section overview>}}
---
h2: Конвертировать MHTML в изображение с помощью C#
---

Чтобы преобразовать MHTML в изображение, мы будем использовать API [Aspose.HTML для .NET](https://products.aspose.com/html/net/), который представляет собой многофункциональное, мощное и простое в использовании средство для работы с документами и API преобразования для платформы C#. Преобразования MHTML часто требуются для использования преимуществ других форматов. Используя нашу высокоскоростную библиотеку, вы можете программно преобразовать MHTML в изображение с полным контролем над различными параметрами преобразования. Мощный C# API позволяет быстро и качественно конвертировать MHTML в популярные форматы!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации MHTML
---

Проверьте качество преобразования MHTML в изображение прямо в браузере! Пожалуйста, загрузите файл MHTML из локальной файловой системы, выберите требуемый формат вывода из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование MHTML в изображение будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или MHTML в формат изображения онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MHTML "JPG|JPEG" GIF TIFF PNG BMP DOCX PDF XPS >}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var stream = File.OpenRead("sample.mht");
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
    Converter.ConvertMHTML(stream, options, "output.{{output lower}}");   
{{< /app/html/converter>}} 


{{<section steps>}}
---
h2: Действия по преобразованию MHTML в изображение на C#
---

Если вы хотите программно преобразовать MHTML в изображение, выполните несколько обязательных шагов:
1. Откройте существующий файл MHTML.
1. Создайте новый объект [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) и укажите ImageFormat. По умолчанию свойство Format имеет значение [PNG.](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/)
1. Используйте метод [ConvertMHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertmhtml/) класса Converter, чтобы сохранить MHTML как изображение.
1. Файл растрового изображения будет сохранен по указанному пути.

{{<section documentation>}}
---
h2: Преобразование MHTML в изображение в документации
---

Преобразование MHTML в изображение позволяет сохранить документ MHTML в виде файла изображения. Пожалуйста, посетите статью документации [Преобразование MHTML в изображение](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-image/), чтобы узнать больше о функции преобразования Aspose.HTML для .NET API и рассмотреть примеры C# для наиболее распространенных сценариев преобразования. В статье вы найдете информацию о том, как преобразовать MHTML в изображение с помощью методов ConvertMHTML(), а также о том, как применить ImageSaveOptions или [ICreateStreamProvider](https://reference.aspose.com/html/net/aspose.html.io/icreatestreamprovider/).

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
title: Другие поддерживаемые преобразования MHTML
subTitle: "Вы также можете конвертировать MHTML во многие другие форматы файлов:"
---