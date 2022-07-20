---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать MHTML в PDF
description: Преобразование MHTML в PDF на C#. Легко используйте API преобразователя в ASP.NET или любом приложении .NET. Попробуйте онлайн-конвертер MHTML в PDF бесплатно!
url: /net/conversion/mhtml-to-pdf/
family: html
platformtag: net
feature: conversion
informat: MHTML
outformat: PDF
otherformats: DOCX XPS GIF JPEG PNG TIFF BMP
---

{{<section banner>}}
---
h1: Преобразование MHTML в PDF через C#
h2: Высокоточное преобразование MHTML в PDF с использованием .NET API. Мгновенно конвертируйте MHTML в формат PDF с помощью нашего бесплатного онлайн-конвертера.
---

{{<section overview>}}
---
h2: Преобразование MHTML в PDF с помощью C#
---

Чтобы преобразовать MHTML в PDF, мы будем использовать API [Aspose.HTML для .NET](https://products.aspose.com/html/net/), который представляет собой многофункциональное, мощное и простое в использовании средство для работы с документами и API преобразования для платформы C#. Преобразования MHTML часто требуются для использования преимуществ других форматов. Используя нашу высокоскоростную библиотеку, вы можете программно конвертировать MHTML в PDF с полным контролем над различными параметрами конвертации. Мощный C# API позволяет быстро и качественно конвертировать MHTML в популярные форматы!

{{<section demos>}}
---
h2: Бесплатные онлайн-демонстрации конвертера
---

Проверьте качество преобразования MHTML в PDF прямо в браузере! Пожалуйста, загрузите файл MHTML из локальной файловой системы, выберите требуемый формат вывода из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование MHTML в PDF будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или MHTML в формат PDF онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MHTML PDF "JPG|JPEG" GIF DOCX BMP XPS TIFF PNG >}}
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
h2: Действия по преобразованию MHTML в PDF на C#
---

Если вы хотите программно преобразовать MHTML в PDF, выполните несколько обязательных шагов:
1. Откройте существующий файл MHTML.
1. Создайте экземпляр класса [PdfSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/pdfsaveoptions).
1. Используйте метод [ConvertMHTML()](https://apireference.aspose.com/html/net/aspose.html.converters.converter/convertmhtml/methods/29) в [Converter](https://apireference.aspose.com/html/net/aspose.html.converters/converter), чтобы сохранить MHTML в виде файла PDF. Вам необходимо передать файловый поток MHTML, PdfSaveOptions и путь к выходному файлу методу ConvertMHTML().
1. Файл PDF будет сохранен по указанному пути.




{{<section documentation>}}
---
h2: Преобразование MHTML в PDF в документации
---

  - цель <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#mhtml-to-pdf-by-two-lines-of-code" ="_blank">MHTML в PDF двумя строками кода</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#convert-mhtml-to-pdf-using-pdfsaveoptions" target="_blank" >Преобразование MHTML в PDF с помощью PdfSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/#output-stream-providers" target="_blank">преобразование MHTML в PDF с помощью MemoryStreamProvider</a>

Преобразование MHTML в PDF часто требуется для установления ограниченного доступа к редактированию или копированию документов, для создания официальной документации или отправки какой-либо информации, например, по электронной почте. Пожалуйста, посетите статью документации [Преобразование MHTML в PDF](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-pdf/), чтобы узнать больше об Aspose.HTML для .NET API. функции преобразования и рассмотреть примеры C# для наиболее распространенных сценариев преобразования MHTML в PDF. В статье вы найдете информацию о том, как преобразовать MHTML в PDF с помощью методов ConvertMHTML() и как применить параметры PdfSaveOptions или ICreateStreamProvider.

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