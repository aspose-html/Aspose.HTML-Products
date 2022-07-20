---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать MHTML в JPEG
description: Преобразование MHTML в JPEG на C#. Легко используйте API преобразователя в ASP.NET или любом приложении .NET. Попробуйте онлайн-конвертер MHTML в JPEG бесплатно!
url: /net/conversion/mhtml-to-jpeg/
family: html
platformtag: net
feature: conversion
informat: MHTML
outformat: JPEG
otherformats: DOCX PDF XPS BMP GIF PNG TIFF
---

{{<section banner>}}
---
h1: Преобразование MHTML в JPEG через C#
h2: Высокоточное преобразование MHTML в JPEG с использованием .NET API. Мгновенно конвертируйте формат MHTML в JPEG с помощью нашего бесплатного онлайн-конвертера.
---

{{<section overview>}}
---
h2: Преобразование MHTML в JPEG с помощью C#
---

Чтобы преобразовать MHTML в JPEG, мы будем использовать API [Aspose.HTML для .NET](https://products.aspose.com/html/net/), который представляет собой многофункциональное, мощное и простое в использовании средство для работы с документами и API преобразования для платформы C#. Преобразования MHTML часто требуются для использования преимуществ других форматов. Используя нашу высокоскоростную библиотеку, вы можете программно конвертировать изображения MHTML в JPEG с полным контролем над различными параметрами преобразования. Мощный C# API позволяет быстро и качественно конвертировать MHTML в популярные форматы!

{{<section demos>}}
---
h2: Бесплатные онлайн-демонстрации конвертера
---

Проверьте качество преобразования MHTML в JPEG прямо в браузере! Пожалуйста, загрузите файл MHTML из локальной файловой системы, выберите требуемый формат вывода из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование MHTML в JPEG будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или MHTML в формат JPEG онлайн!

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
h2: Действия по преобразованию MHTML в JPEG в C#
---

Если вы хотите программно преобразовать MHTML в JPEG, выполните несколько обязательных шагов:
1. Откройте существующий файл MHTML.
1. Создайте новый объект [ImageSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions) с JPEG ImageFormat. По умолчанию свойство Format имеет значение [PNG](https://apireference.aspose.com/html/net/aspose.html.rendering.image/imageformat).
1. Используйте метод [ConvertMHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/convertmhtml/) класса Converter, чтобы сохранить MHTML как изображение JPEG.
1. Файл JPEG будет сохранен по указанному пути.




{{<section documentation>}}
---
h2: Преобразование MHTML в JPEG в документации
---

JPEG является одним из наиболее часто используемых форматов изображений. Его уникальность заключается в контролируемой потере качества при сжатии. Эта функция сжатия позволяет быстро и эффективно обмениваться изображениями JPG и широко использовать их в Интернете, на компьютерах и мобильных устройствах. Преобразование MHTML в JPEG позволяет сохранить документ MHTML как изображение JPEG. Пожалуйста, посетите статью документации [Преобразование MHTML в изображение](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-image/), чтобы узнать больше об Aspose.HTML для .NET API. функции преобразования и рассмотреть примеры C# для наиболее распространенных сценариев преобразования MHTML в JPEG. В статье вы найдете информацию о том, как <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-image/#convert-mhtml-to-jpg -using-imagesaveoptions" target="_blank">Преобразование MHTML в JPG</a> с помощью методов ConvertMHTML() и способов применения ImageSaveOptions или [ICreateStreamProvider](https://apireference.aspose.com/html/net/aspose.html.io/icreatestreamprovider).

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