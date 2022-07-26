---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать SVG в BMP
description: Преобразование SVG в BMP на C#. Легко используйте API в любом приложении .NET. Попробуйте онлайн Конвертер SVG в BMP бесплатно!
url: /net/conversion/svg-to-bmp/
family: html
platformtag: net
feature: conversion
informat: SVG
outformat: BMP
otherformats: PDF XPS GIF JPEG PNG TIFF
---

{{<section banner>}}
---
h1: Конвертировать SVG в BMP на C#
h2: Преобразование SVG в BMP с использованием серверных .NET API. Мгновенно конвертируйте SVG в формат BMP онлайн!
---

{{<section overview>}}
---
h2: Преобразование SVG в BMP с помощью C#
---

SVG — это язык XML для создания двумерной векторной и смешанной векторно-растровой графики. Чтобы преобразовать SVG в BMP, мы будем использовать API [Aspose.HTML для .NET,](https://products.aspose.com/html/net/) который представляет собой многофункциональное, мощное и простое в использовании средство для работы с документами. и API преобразования для платформы C#. Преобразование SVG часто требуется для использования преимуществ других форматов. Используя нашу библиотеку обработки документов, вы можете программно преобразовать изображение SVG в BMP с полным контролем над различными параметрами преобразования всего несколькими строками кода.

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации SVG
---

Проверьте качество преобразования SVG в BMP прямо в браузере! В следующем примере C# показано, как преобразовать документ SVG. Мы описываем исходный код для чтения SVG из файла и последующего преобразования SVG в BMP с параметрами сохранения по умолчанию. Пожалуйста, загрузите SVG из локальной файловой системы, выберите выходной формат и запустите пример. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте формат SVG в формат BMP онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/svg/converter SVG BMP XPS TIFF PNG PDF "JPG|JPEG" GIF>}}
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
h2: Шаги по преобразованию SVG в BMP на C#
---

1. Загрузите файл SVG с помощью одного из конструкторов SVGDocument() класса [SVGDocument](https://reference.aspose.com/html/net/aspose.html.dom.svg/svgdocument/).
1. Создайте новый объект [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) с форматом изображения BMP. По умолчанию свойство Format имеет значение [PNG](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/)
1. Используйте метод [ConvertSVG()](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertsvg/#convertsvg_3), чтобы сохранить SVG как изображение BMP. Вам необходимо передать SVGDocument, ImageSaveOptions и путь к выходному файлу методу ConvertSVG().

{{<section documentation>}}
---
h2: Конвертировать SVG в BMP в документации
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/#convert-svg-to-bmp" target="_blank">Преобразовать SVG в BMP</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/#convert-svg-to-bmp-using-imagesaveoptions" target="_blank" >Конвертировать SVG в BMP с помощью ImageSaveOptions</a>

Файлы BMP представляют собой файлы растровых изображений, которые используются для хранения высококачественных растровых цифровых изображений, и иногда может потребоваться преобразование SVG в BMP. Пожалуйста, посетите статью документации [Конвертировать SVG в BMP,](https://docs.aspose.com/html/net/converting-between-formats/svg-to-bmp/) чтобы узнать больше о функции преобразования Aspose.HTML для .NET API и рассмотреть примеры C# для наиболее распространенных сценариев преобразования SVG в BMP. В статье вы найдете информацию о том, как преобразовать SVG в BMP с помощью методов ConvertSVG() и как применить ImageSaveOptions.

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