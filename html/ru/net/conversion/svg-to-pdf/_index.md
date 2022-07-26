---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать SVG в PDF
description: Преобразование SVG в PDF на C#. Легко используйте API в любом приложении .NET. Попробуйте онлайн-конвертер SVG в PDF бесплатно!
url: /net/conversion/svg-to-pdf/
family: html
platformtag: net
feature: conversion
informat: SVG
outformat: PDF
otherformats: XPS GIF JPEG PNG TIFF BMP
---

{{<section banner>}}
---
h1: Конвертировать SVG в PDF на C#
h2: Преобразование SVG в PDF с использованием серверных .NET API. Мгновенно конвертируйте формат SVG в PDF онлайн!
---

{{<section overview>}}
---
h2: Преобразование SVG в PDF с помощью C#
---

SVG — это язык XML для создания двумерной векторной и смешанной векторно-растровой графики. Чтобы преобразовать SVG в PDF, мы будем использовать API [Aspose.HTML для .NET,](https://products.aspose.com/html/net/) который представляет собой многофункциональное, мощное и простое в использовании средство для работы с документами. и API преобразования для платформы C#. Преобразование SVG часто требуется для использования преимуществ других форматов. Используя нашу библиотеку обработки документов, вы можете программно конвертировать SVG в PDF с полным контролем над различными параметрами преобразования всего несколькими строками кода.

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации SVG
---

Проверьте качество преобразования SVG в PDF прямо в браузере! В следующем примере C# показано, как преобразовать документ SVG. Мы описываем исходный код для чтения SVG из файла и последующего преобразования SVG в PDF с параметрами сохранения по умолчанию. Пожалуйста, загрузите SVG из локальной файловой системы, выберите выходной формат и запустите пример. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте SVG в формат PDF онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/svg/converter SVG PDF  XPS TIFF PNG BMP "JPG|JPEG" GIF>}}
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
h2: Шаги по преобразованию SVG в PDF на C#
---

1. Загрузите файл SVG с помощью одного из конструкторов SVGDocument() класса [SVGDocument.](https://reference.aspose.com/html/net/aspose.html.dom.svg/svgdocument/)
1. Создайте новый объект [PdfSaveOptions.](https://reference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions/)
1. Используйте метод [ConvertSVG(),](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertsvg/#convertsvg_3) чтобы сохранить SVG в виде файла PDF. Вам необходимо передать SVGDocument, PdfSaveOptions и путь к выходному файлу методу ConvertSVG().

{{<section documentation>}}
---
h2: Преобразование SVG в PDF в документации
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#svg-to-pdf-by-a-одной строкой кода " target="_blank">SVG в PDF с помощью одной строки кода</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#convert-svg-to-pdf-using-pdfsaveoptions" target="_blank" >Конвертировать SVG в PDF с помощью PdfSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/#output-stream-providers" target="_blank">Конвертировать SVG в PDF с помощью MemoryStreamProvider</a>

Преобразование SVG в PDF часто требуется для установления ограниченного доступа к редактированию или копированию документов, для создания официальной документации или отправки какой-либо информации, например, по электронной почте. Пожалуйста, посетите статью документации [Конвертировать SVG в PDF,](https://docs.aspose.com/html/net/converting-between-formats/svg-to-pdf/) чтобы узнать больше о функции преобразования Aspose.HTML для .NET API и рассмотреть примеры C# для наиболее распространенных сценариев преобразования SVG в PDF. В статье вы найдете информацию о том, как преобразовать SVG в PDF с помощью методов ConvertSVG() и как применить PdfSaveOptions.

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