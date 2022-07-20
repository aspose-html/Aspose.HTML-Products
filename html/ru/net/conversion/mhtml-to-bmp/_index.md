---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать MHTML в BMP
description: Преобразование MHTML в BMP на C#. Легко используйте API преобразователя в ASP.NET или любом приложении .NET. Попробуйте онлайн-конвертер MHTML в BMP бесплатно!
url: /net/conversion/mhtml-to-bmp/
family: html
platformtag: net
feature: conversion
informat: MHTML
outformat: BMP
otherformats: DOCX PDF XPS GIF JPEG PNG TIFF
---

{{<section banner>}}
---
h1: Преобразование MHTML в BMP через C#
h2: Высокоточное преобразование MHTML в BMP с использованием .NET API. Мгновенно конвертируйте формат MHTML в BMP с помощью нашего бесплатного онлайн-конвертера.
---

{{<section overview>}}
---
h2: Преобразование MHTML в BMP с помощью C#
---

Чтобы преобразовать MHTML в BMP, мы будем использовать API [Aspose.HTML для .NET](https://products.aspose.com/html/net/), который представляет собой многофункциональное, мощное и простое в использовании средство для работы с документами и API преобразования для платформы C#. Преобразования MHTML часто требуются для использования преимуществ других форматов. Используя нашу высокоскоростную библиотеку, вы можете программно конвертировать MHTML в BMP с полным контролем над различными параметрами конвертации. Мощный C# API позволяет быстро и качественно конвертировать MHTML в популярные форматы!

{{<section demos>}}
---
h2: Бесплатные онлайн-демонстрации конвертера
---

Проверьте качество преобразования MHTML в BMP прямо в браузере! Пожалуйста, загрузите файл MHTML из локальной файловой системы, выберите требуемый формат вывода из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование MHTML в BMP будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или MHTML в формат BMP онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MHTML BMP "JPG|JPEG" GIF TIFF PNG DOCX PDF XPS >}}
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
h2: Действия по преобразованию MHTML в BMP на C#
---

Если вы хотите программно преобразовать MHTML в BMP, выполните несколько обязательных шагов:
1. Откройте существующий файл MHTML.
1. Создайте новый объект [ImageSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions) с форматом изображения BMP. По умолчанию свойство Format имеет значение [PNG](https://apireference.aspose.com/html/net/aspose.html.rendering.image/imageformat).
1. Используйте метод [ConvertMHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/convertmhtml/) класса Converter, чтобы сохранить MHTML как изображение BMP.
1. Файл BMP будет сохранен по указанному пути.




{{<section documentation>}}
---
h2: Преобразование MHTML в BMP в документации
---

Файлы BMP представляют собой файлы растровых изображений, которые используются для хранения высококачественных растровых цифровых изображений. Таким образом, иногда может возникнуть необходимость преобразовать изображение MHTML в BMP. Пожалуйста, посетите статью документации [Преобразование MHTML в изображение](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-image/), чтобы узнать больше об Aspose.HTML для .NET API. функции преобразования и рассмотреть примеры C# для наиболее распространенных сценариев преобразования MHTML в BMP. В статье вы найдете информацию о том, как <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-image/#convert-mhtml-to-bmp " target="_blank">Преобразование MHTML в BMP</a> с помощью методов ConvertMHTML() и способов применения ImageSaveOptions.

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