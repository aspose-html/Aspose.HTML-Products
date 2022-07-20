---
translation: true
template: /templates/_template-conversion-child.md
title: Преобразование SVG в изображение
description: Преобразование SVG в изображение на C#. Легко используйте API преобразователя в ASP.NET или любом приложении .NET. Попробуйте онлайн SVG to Image Converter бесплатно!
url: /net/conversion/svg-to-image/
family: html
platformtag: net
feature: conversion
informat: SVG
outformat: Image
otherformats: GIF JPEG PNG TIFF BMP PDF XPS
---

{{<section banner>}}
---
h1: Преобразование SVG в изображение с помощью C#
h2: Высокоточное преобразование SVG в изображение с использованием серверных .NET API. Мгновенно конвертируйте SVG в растровые форматы изображений с помощью нашего бесплатного онлайн-конвертера!
---

{{<section overview>}}
---
h2: Преобразование SVG в изображение с помощью C#
---

SVG — это язык XML для создания двумерной векторной и смешанной векторно-растровой графики. Чтобы преобразовать SVG в изображение, мы будем использовать API [Aspose.HTML для .NET](https://products.aspose.com/html/net/), который представляет собой многофункциональное, мощное и простое в использовании средство для работы с документами. и API преобразования для платформы C#. Преобразование SVG часто требуется для использования преимуществ других форматов. Используя нашу библиотеку обработки документов, вы можете программно преобразовать SVG в изображение с полным контролем над различными параметрами преобразования всего несколькими строками кода.

{{<section demos>}}
---
h2: Бесплатные онлайн-демонстрации конвертера
---

Проверьте качество преобразования SVG в изображение прямо в браузере! В следующем примере C# показано, как преобразовать документ SVG. Мы описываем исходный код для чтения SVG из файла и последующего преобразования SVG в изображение с параметрами сохранения по умолчанию. Пожалуйста, загрузите SVG из локальной файловой системы, выберите выходной формат и запустите пример. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте SVG в форматы изображений онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/svg/converter SVG PNG BMP  TIFF "JPG|JPEG" GIF XPS PDF>}}
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
h2: Шаги по преобразованию SVG в изображение на C#
---
1. Загрузите файл SVG с помощью одного из конструкторов SVGDocument() класса [SVGDocument](https://apireference.aspose.com/html/net/aspose.html.dom.svg/svgdocument).
1. Создайте новый объект [ImageSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions) и укажите ImageFormat. По умолчанию свойство Format имеет значение [PNG](https://apireference.aspose.com/html/net/aspose.html.rendering.image/imageformat).
1. Используйте метод [ConvertSVG()](https://apireference.aspose.com/html/net/aspose.html.converters.converter/convertsvg/methods/3), чтобы сохранить SVG как изображение BMP. Вам необходимо передать SVGDocument, ImageSaveOptions и путь к выходному файлу методу ConvertSVG().




{{<section documentation>}}
---
h2: Преобразование SVG в изображение в документации
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/#svg-to-jpg-by-a-single-of-code " target="_blank">SVG в JPG с помощью одной строки кода</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/#convert-svg-to-jpg-using-imagesaveoptions" target="_blank" >Конвертировать SVG в JPG с помощью ImageSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/#output-stream-providers" target="_blank">Преобразование SVG в JPG с помощью MemoryStreamProvider</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/" target="_blank">Конвертировать SVG в PNG</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/" target="_blank">Конвертировать SVG в BMP</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-tiff/" target="_blank">Конвертировать SVG в TIFF</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-gif/" target="_blank">Конвертировать SVG в GIF</a>

SVG — один из наиболее часто используемых форматов для создания веб-сайтов и печати графики для обеспечения масштабируемости. Но иногда вам нужно преобразовать SVG и сохранить его в распространенном формате растрового изображения. Пожалуйста, посетите главу документации [Преобразование между форматами](https://docs.aspose.com/html/net/converting-between-formats/), чтобы узнать больше о функциях преобразования Aspose.HTML для .NET API и рассмотреть примеры C#. для наиболее распространенных сценариев преобразования SVG в изображение. В статьях вы найдете информацию о том, как преобразовать HTML в изображение с помощью методов ConvertSVG() и как применить ImageSaveOptions.

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