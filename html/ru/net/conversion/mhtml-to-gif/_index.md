---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать MHTML в GIF
description: Конвертировать MHTML в GIF на C#. Легко используйте API в любом приложении .NET. Попробуйте онлайн-конвертер MHTML в GIF бесплатно!
url: /net/conversion/mhtml-to-gif/
family: html
platformtag: net
feature: conversion
informat: MHTML
outformat: GIF
otherformats: DOCX PDF XPS BMP GIF JPEG PNG TIFF
---

{{<section banner>}}
---
h1: Конвертировать MHTML в GIF на C#
h2: Преобразование MHTML в GIF с использованием .NET API. Мгновенно конвертируйте формат MHTML в GIF онлайн!
---

{{<section overview>}}
---
h2: Преобразование MHTML в GIF с помощью C#
---

Чтобы преобразовать MHTML в GIF, мы будем использовать API [Aspose.HTML для .NET](https://products.aspose.com/html/net/), который представляет собой многофункциональное, мощное и простое в использовании средство для работы с документами и API преобразования для платформы C#. Преобразования MHTML часто требуются для использования преимуществ других форматов. Используя нашу высокоскоростную библиотеку, вы можете программно конвертировать MHTML в GIF с полным контролем над различными параметрами конвертации. Мощный C# API позволяет быстро и качественно конвертировать MHTML в популярные форматы!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации MHTML
---

Проверьте качество преобразования MHTML в GIF прямо в браузере! Пожалуйста, загрузите файл MHTML из локальной файловой системы, выберите требуемый формат вывода из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование MHTML в GIF будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или MHTML в формат GIF онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MHTML GIF BMP "JPG|JPEG" TIFF PNG DOCX PDF XPS >}}
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
h2: Шаги по преобразованию MHTML в GIF в C#
---

Если вы хотите программно преобразовать MHTML в GIF, выполните несколько обязательных шагов:
1. Откройте существующий файл MHTML.
1. Создайте новый объект [ImageSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions) с GIF ImageFormat. По умолчанию свойство Format имеет значение [PNG](https://apireference.aspose.com/html/net/aspose.html.rendering.image/imageformat).
1. Используйте метод [ConvertMHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/convertmhtml/) класса Converter, чтобы сохранить MHTML в виде изображения GIF.
1. Файл GIF будет сохранен по указанному пути.

{{<section documentation>}}
---
h2: Преобразование MHTML в GIF в документации
---

GIF — это популярный формат изображения, который поддерживает анимированные изображения и часто используется в веб-публикациях. Преобразование MHTML в GIF позволяет сохранить документ MHTML в виде изображения GIF. Пожалуйста, посетите статью документации [Преобразование MHTML в изображение,](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-image/) чтобы узнать больше о функции преобразования Aspose.HTML для .NET API и рассмотреть примеры C# для наиболее распространенных сценариев преобразования MHTML в GIF. В статье вы найдете информацию о том, как <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-image/#convert-mhtml-to-gif " target="_blank">Преобразование MHTML в GIF</a> с помощью методов ConvertMHTML() и способов применения ImageSaveOptions.

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
subTitle: "Вы также можете конвертировать MHTML в другие форматы файлов:"
---