---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать SVG в TIFF
description: Преобразование SVG в TIFF на C#. Легко используйте API преобразователя в ASP.NET или любом приложении .NET. Попробуйте онлайн-конвертер SVG в TIFF бесплатно!
url: /net/conversion/svg-to-tiff/
family: html
platformtag: net
feature: conversion
informat: SVG
outformat: TIFF
otherformats: PDF XPS GIF JPEG PNG BMP
---

{{<section banner>}}
---
h1: Преобразование SVG в TIFF через C#
h2: Высокоточное преобразование SVG в TIFF с использованием серверных .NET API. Мгновенно конвертируйте SVG в формат TIFF с помощью нашего бесплатного онлайн-конвертера!
---

{{<section overview>}}
---
h2: Преобразование SVG в TIFF с помощью C#
---

SVG — это язык XML для создания двумерной векторной и смешанной векторно-растровой графики. Чтобы преобразовать SVG в TIFF, мы будем использовать API [Aspose.HTML для .NET](https://products.aspose.com/html/net/), который представляет собой многофункциональное, мощное и простое в использовании средство для работы с документами. и API преобразования для платформы C#. Преобразование SVG часто требуется для использования преимуществ других форматов. Используя нашу библиотеку обработки документов, вы можете программно преобразовать изображение SVG в TIFF с полным контролем над различными параметрами преобразования всего несколькими строками кода.

{{<section demos>}}
---
h2: Бесплатные онлайн-демонстрации конвертера
---

Проверьте качество преобразования SVG в TIFF прямо в браузере! В следующем примере C# показано, как преобразовать документ SVG. Мы описываем исходный код для чтения SVG из файла и последующего преобразования SVG в TIFF с параметрами сохранения по умолчанию. Пожалуйста, загрузите SVG из локальной файловой системы, выберите выходной формат и запустите пример. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте SVG в формат TIFF онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/svg/converter SVG TIFF BMP PNG "JPG|JPEG" GIF XPS PDF>}}
using Aspose.Html;
using Aspose.Html.Dom.Svg;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new SVGDocument("image.svg");
{{#if_output 'PDF'}}
    var options = new PdfSaveOptions();
{{/if_output}}
{{#if_output 'XPS'}}
    var options = new XpsSaveOptions();
{{/if_output}}
{{#if_output 'BMP' 'JPG' 'GIF' 'PNG' 'TIFF'}}
    var options = new ImageSaveOptions(ImageFormat.{{output param2 camel}});
{{/if_output}}
    Converter.ConvertSVG(document, options, "output.{{output lower}}");   
{{< /app/svg/converter>}}


{{<section steps>}}
---
h2: Шаги по преобразованию SVG в TIFF на C#
---
1. Загрузите файл SVG с помощью одного из конструкторов SVGDocument() класса [SVGDocument](https://apireference.aspose.com/html/net/aspose.html.dom.svg/svgdocument).
1. Создайте новый объект [ImageSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions) в формате TIFF ImageFormat. По умолчанию свойство Format имеет значение [PNG](https://apireference.aspose.com/html/net/aspose.html.rendering.image/imageformat).
1. Используйте метод [ConvertSVG()](https://apireference.aspose.com/html/net/aspose.html.converters.converter/convertsvg/methods/3), чтобы сохранить SVG в виде изображения TIFF. Вам необходимо передать SVGDocument, ImageSaveOptions и путь к выходному файлу методу ConvertSVG().




{{<section documentation>}}
---
h2: Преобразование SVG в TIFF в документации
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/#svg-to-tiff-by-a-single-of-code " target="_blank">SVG в TIFF одной строкой кода</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/#convert-svg-to-tiff-using-imagesaveoptions" target="_blank" >Преобразование SVG в TIFF с помощью ImageSaveOptions</a>

TIFF — это формат для хранения растровых графических изображений с широкой палитрой цветов. Широко используется для полиграфии и журнальной офсетной печати. Иногда может потребоваться преобразовать SVG в TIFF. Пожалуйста, посетите статью документации [Преобразование SVG в TIFF](https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/), чтобы узнать больше об Aspose.HTML для .NET API. функции преобразования и рассмотреть примеры C# для наиболее распространенных сценариев преобразования SVG в TIFF. В статье вы найдете информацию о том, как преобразовать SVG в TIFF с помощью методов ConvertSVG() и как применить ImageSaveOptions.

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
title: Другие поддерживаемые преобразования SVG
subTitle: "Вы также можете конвертировать SVG во многие другие форматы файлов:"
---