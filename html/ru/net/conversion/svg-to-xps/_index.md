---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать SVG в XPS
description: Преобразование SVG в XPS на C#. Легко используйте API преобразователя в ASP.NET или любом приложении .NET. Попробуйте онлайн Конвертер SVG в XPS бесплатно!
url: /net/conversion/svg-to-xps/
family: html
platformtag: net
feature: conversion
informat: SVG
outformat: XPS
otherformats: PDF BMP GIF JPEG PNG TIFF
---

{{<section banner>}}
---
h1: Преобразование SVG в XPS через C#
h2: Высокоточное преобразование SVG в XPS с использованием серверных API .NET. Мгновенно конвертируйте формат SVG в формат XPS с помощью нашего бесплатного онлайн-конвертера!
---

{{<section overview>}}
---
h2: Преобразование SVG в XPS с помощью C#
---

SVG — это язык XML для создания двумерной векторной и смешанной векторно-растровой графики. Чтобы преобразовать SVG в XPS, мы будем использовать API [Aspose.HTML для .NET](https://products.aspose.com/html/net/), который представляет собой многофункциональное, мощное и простое в использовании средство для работы с документами. и API преобразования для платформы C#. Преобразование SVG часто требуется для использования преимуществ других форматов. Формат файла XPS обеспечивает управление правами доступа и позволяет создавать высококачественные документы для печати. Используя нашу библиотеку обработки документов, вы можете программно преобразовать изображение SVG в XPS с полным контролем над различными параметрами преобразования всего несколькими строками кода.

{{<section demos>}}
---
h2: Бесплатные онлайн-демонстрации конвертера
---

Проверьте качество преобразования SVG в XPS прямо в браузере! В следующем примере C# показано, как преобразовать документ SVG. Мы описываем исходный код для чтения SVG из файла и последующего преобразования SVG в XPS с параметрами сохранения по умолчанию. Пожалуйста, загрузите SVG из локальной файловой системы, выберите выходной формат и запустите пример. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте формат SVG в формат XPS онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/svg/converter SVG  XPS PDF TIFF BMP PNG "JPG|JPEG" GIF>}}
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
h2: Шаги по преобразованию SVG в XPS на C#
---
1. Загрузите файл SVG с помощью одного из конструкторов SVGDocument() класса [SVGDocument](https://apireference.aspose.com/html/net/aspose.html.dom.svg/svgdocument).
1. Создайте новый объект [XpsSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/xpssaveoptions).
1. Используйте метод [ConvertSVG()](https://apireference.aspose.com/html/net/aspose.html.converters.converter/convertsvg/methods/3), чтобы сохранить SVG в виде файла XPS. Вам необходимо передать SVGDocument, XpsSaveOptions и путь к выходному файлу методу ConvertSVG().




{{<section documentation>}}
---
h2: Преобразование SVG в XPS в документации
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#svg-to-xps-by-a-single-of-code " target="_blank">SVG в XPS с помощью одной строки кода</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#convert-svg-to-xps-using-xpssaveoptions" target="_blank" >Преобразование SVG в XPS с помощью XpsSaveOptions</a>
 - <a href="https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/#output-stream-providers" target="_blank">Преобразование SVG в XPS с помощью MemoryStreamProvider</a>

XPS — это формат хранения и просмотра документов, разработанный Microsoft. Он имеет ряд преимуществ, которые поддерживают функции безопасности, такие как цифровые подписи для обеспечения большей безопасности документов и многое другое. Пожалуйста, посетите статью документации [Преобразование SVG в XPS](https://docs.aspose.com/html/net/converting-between-formats/svg-to-xps/), чтобы узнать больше об Aspose.HTML для .NET API. функции преобразования и рассмотреть примеры C# для наиболее распространенных сценариев преобразования SVG в XPS. В статье вы найдете информацию о том, как преобразовать SVG в XPS с помощью методов ConvertSVG() и как применить XpsSaveOptions.

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