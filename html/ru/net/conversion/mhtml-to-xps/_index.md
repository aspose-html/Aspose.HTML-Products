---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать MHTML в XPS
description: Конвертировать MHTML в XPS на C#. Легко используйте API в любом приложении .NET. Попробуйте онлайн-конвертер MHTML в XPS бесплатно!
url: /net/conversion/mhtml-to-xps/
family: html
platformtag: net
feature: conversion
informat: MHTML
outformat: XPS
otherformats: DOCX PDF GIF JPEG PNG TIFF BMP
---

{{<section banner>}}
---
h1: Конвертировать MHTML в XPS на C#
h2: Преобразование MHTML в XPS с использованием .NET API. Мгновенно конвертируйте формат MHTML в XPS онлайн!
---

{{<section overview>}}
---
h2: Преобразование MHTML в XPS с помощью C#
---

Чтобы преобразовать MHTML в XPS, мы будем использовать API [Aspose.HTML для .NET,](https://products.aspose.com/html/net/) который представляет собой многофункциональное, мощное и простое в использовании средство для работы с документами и API преобразования для платформы C#. Преобразования MHTML часто требуются для использования преимуществ других форматов. Используя нашу высокоскоростную библиотеку, вы можете программно конвертировать MHTML в XPS с полным контролем над различными параметрами конвертации. Мощный C# API позволяет быстро и качественно конвертировать MHTML в популярные форматы!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации MHTML
---

Проверьте качество преобразования MHTML в XPS прямо в браузере! Пожалуйста, загрузите файл MHTML из локальной файловой системы, выберите требуемый формат вывода из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование MHTML в XPS будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или MHTML в формат XPS онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MHTML XPS PDF DOCX "JPG|JPEG" GIF BMP TIFF PNG >}}
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
h2: Действия по преобразованию MHTML в XPS в C#
---

Если вы хотите программно преобразовать MHTML в XPS, выполните несколько обязательных шагов:
1. Откройте существующий файл MHTML.
1. Создайте экземпляр класса [XpsSaveOptions.](https://reference.aspose.com/html/net/aspose.html.saving/xpssaveoptions/)
1. Используйте метод [ConvertMHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/convertmhtml/#convertmhtml_29) в [Converter](https://reference.aspose.com/html/net/aspose.html.converters/converter/) для сохранения MHTML в виде XPS-файла. Вам необходимо передать файловый поток MHTML, XpsSaveOptions и путь к выходному файлу методу ConvertMHTML().
1. Файл XPS будет сохранен по указанному пути.

{{<section documentation>}}
---
h2: Преобразование MHTML в XPS в документации
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#mhtml-to-xps-by-two-lines-of-code" target="_blank">MHTML в XPS двумя строками кода</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#convert-mhtml-to-xps-using-xpssaveoptions" target="_blank" >Преобразование MHTML в XPS с помощью XpsSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/#output-stream-providers" target="_blank">преобразование MHTML в XPS с помощью MemoryStreamProvider</a>

XPS — это формат хранения и просмотра документов, разработанный Microsoft. Он имеет ряд преимуществ, которые поддерживают функции безопасности, такие как цифровые подписи для обеспечения большей безопасности документов и многое другое. Пожалуйста, посетите статью документации [Преобразование MHTML в XPS,](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-xps/) чтобы узнать больше о функции преобразования Aspose.HTML для .NET API и рассмотреть примеры C# для наиболее распространенных сценариев преобразования MHTML в XPS. В статье вы найдете информацию о том, как преобразовать MHTML в XPS с помощью методов ConvertMHTML() и как применить параметры XpsSaveOptions или ICreateStreamProvider.

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