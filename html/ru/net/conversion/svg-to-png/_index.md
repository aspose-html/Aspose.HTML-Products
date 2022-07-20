---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать SVG в PNG
description: Преобразование SVG в PNG на C#. Легко используйте API в любом приложении .NET. Попробуйте онлайн-конвертер SVG в PNG бесплатно!
url: /net/conversion/svg-to-png/
family: html
platformtag: net
feature: conversion
informat: SVG
outformat: PNG
otherformats: PDF XPS GIF JPEG BMP TIFF
---

{{<section banner>}}
---
h1: Конвертировать SVG в PNG на C#
h2: Преобразование SVG в PNG с использованием серверных .NET API. Мгновенно конвертируйте SVG в формат PNG онлайн!
---

{{<section overview>}}
---
h2: Конвертировать SVG в PNG с помощью C#
---

SVG — это язык XML для создания двумерной векторной и смешанной векторно-растровой графики. Чтобы преобразовать SVG в PNG, мы будем использовать API [Aspose.HTML для .NET,](https://products.aspose.com/html/net/) который представляет собой многофункциональное, мощное и простое в использовании средство для работы с документами. и API преобразования для платформы C#. Преобразование SVG часто требуется для использования преимуществ других форматов. Используя нашу библиотеку обработки документов, вы можете программно преобразовать изображение SVG в PNG с полным контролем над различными параметрами преобразования всего несколькими строками кода.

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации SVG
---

Проверьте качество преобразования SVG в PNG прямо в браузере! В следующем примере C# показано, как преобразовать документ SVG. Мы описываем исходный код для чтения SVG из файла и последующего преобразования SVG в PNG с параметрами сохранения по умолчанию. Пожалуйста, загрузите SVG из локальной файловой системы, выберите выходной формат и запустите пример. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте SVG в формат PNG онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/svg/converter SVG PNG PDF XPS TIFF BMP "JPG|JPEG" GIF>}}
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
h2: Шаги по преобразованию SVG в PNG в C#
---

1. Загрузите файл SVG с помощью одного из конструкторов SVGDocument() класса [SVGDocument](https://apireference.aspose.com/html/net/aspose.html.dom.svg/svgdocument).
1. Создайте новый объект [ImageSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/imagesaveoptions). По умолчанию свойство Format имеет значение [PNG](https://apireference.aspose.com/html/net/aspose.html.rendering.image/imageformat).
1. Используйте метод [ConvertSVG()](https://apireference.aspose.com/html/net/aspose.html.converters.converter/convertsvg/methods/3), чтобы сохранить SVG в виде изображения PNG. Вам необходимо передать SVGDocument, ImageSaveOptions и путь к выходному файлу методу ConvertSVG().

{{<section documentation>}}
---
h2: Преобразование SVG в PNG в документации
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/#svg-to-png-by-a-single-of-code " target="_blank">SVG в PNG одной строкой кода</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/#convert-svg-to-png-using-imagesaveoptions" target="_blank" >Конвертировать SVG в PNG с помощью ImageSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/#output-stream-providers" target="_blank">Конвертировать SVG в PNG с помощью MemoryStreamProvider</a>

Формат файлов PNG поддерживает сжатие изображений без потерь, что делает его популярным среди пользователей. Пожалуйста, посетите статью документации [Конвертировать SVG в PNG,](https://docs.aspose.com/html/net/converting-between-formats/svg-to-png/) чтобы узнать больше о функции преобразования Aspose.HTML для .NET API и рассмотреть примеры C# для наиболее распространенных сценариев преобразования SVG в PNG. В статье вы найдете информацию о том, как преобразовать SVG в PNG с помощью методов ConvertSVG() и как применить ImageSaveOptions.

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