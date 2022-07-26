---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать SVG в JPEG
description: Преобразование SVG в JPEG на C#. Легко используйте API в любом приложении .NET. Попробуйте онлайн-конвертер SVG в JPEG бесплатно!
url: /net/conversion/svg-to-jpeg/
family: html
platformtag: net
feature: conversion
informat: SVG
outformat: JPEG
otherformats: PDF XPS GIF BMP PNG TIFF
---

{{<section banner>}}
---
h1: Конвертировать SVG в JPEG через C#
h2: Преобразование SVG в JPEG с использованием серверных .NET API. Мгновенно конвертируйте SVG в формат JPEG онлайн!
---

{{<section overview>}}
---
h2: Преобразование SVG в JPEG с помощью C#
---

SVG — это язык XML для создания двумерной векторной и смешанной векторно-растровой графики. Чтобы преобразовать SVG в JPEG, мы будем использовать API [Aspose.HTML для .NET,](https://products.aspose.com/html/net/) который представляет собой многофункциональное, мощное и простое в использовании средство для работы с документами. и API преобразования для платформы C#. Преобразование SVG часто требуется для использования преимуществ других форматов. Используя нашу библиотеку обработки документов, вы можете программно преобразовать изображение SVG в JPEG с полным контролем над различными параметрами преобразования всего несколькими строками кода.

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации SVG
---

Проверьте качество преобразования SVG в JPEG прямо в браузере! В следующем примере C# показано, как преобразовать документ SVG. Мы описываем исходный код для чтения SVG из файла и последующего преобразования SVG в JPEG с параметрами сохранения по умолчанию. Пожалуйста, загрузите SVG из локальной файловой системы, выберите выходной формат и запустите пример. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте SVG в формат JPEG онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/svg/converter SVG "JPG|JPEG" BMP TIFF PNG GIF XPS PDF>}}
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
h2: Шаги по преобразованию SVG в JPEG на C#
---

1. Загрузите файл SVG с помощью одного из конструкторов SVGDocument() класса [SVGDocument.](https://reference.aspose.com/html/net/aspose.html.dom.svg/svgdocument/)
1. Создайте новый объект [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) с JPEG ImageFormat. По умолчанию свойство Format имеет значение [PNG.](https://reference.aspose.com/html/net/aspose.html.rendering.image/imageformat/)
1. Используйте метод [ConvertSVG(),](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertsvg/#convertsvg_3) чтобы сохранить SVG как изображение JPEG. Вам необходимо передать SVGDocument, ImageSaveOptions и путь к выходному файлу методу ConvertSVG().

{{<section documentation>}}
---
h2: Преобразование SVG в JPEG в документации
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/#svg-to-jpg-by-a-single-of-code " target="_blank">SVG в JPG с помощью одной строки кода</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/#convert-svg-to-jpg-using-imagesaveoptions" target="_blank" >Конвертировать SVG в JPG с помощью ImageSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/#output-stream-providers" target="_blank">Конвертировать SVG в JPG с помощью MemoryStreamProvider</a>

JPG является одним из наиболее часто используемых форматов изображений. Его уникальность заключается в контролируемой потере качества при сжатии. Поэтому он широко используется для хранения и отправки через Интернет графического цифрового контента (фотографий, сканированных копий, оцифрованных изображений). Поэтому иногда может возникнуть необходимость конвертировать SVG в JPEG. Пожалуйста, посетите статью документации [Конвертировать SVG в JPG](https://docs.aspose.com/html/net/converting-between-formats/svg-to-jpg/), чтобы узнать больше о функции преобразования Aspose.HTML для .NET API и рассмотреть примеры C# для наиболее распространенных сценариев преобразования SVG в JPG. В статье вы найдете информацию о том, как преобразовать SVG в JPG с помощью методов ConvertSVG() и как применить ImageSaveOptions.

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