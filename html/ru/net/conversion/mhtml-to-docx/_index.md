---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать MHTML в DOCX
description: Преобразование MHTML в DOCX на C#. Легко используйте API преобразователя в ASP.NET или любом приложении .NET. Попробуйте онлайн-конвертер MHTML в DOCX бесплатно!
url: /net/conversion/mhtml-to-docx/
family: html
platformtag: net
feature: conversion
informat: MHTML
outformat: DOCX
otherformats: PDF XPS GIF JPEG PNG TIFF BMP
---

{{<section banner>}}
---
h1: Преобразование MHTML в DOCX через C#
h2: Высокоточное преобразование MHTML в DOCX с использованием .NET API. Мгновенно конвертируйте MHTML в формат DOCX с помощью нашего бесплатного онлайн-конвертера.
---

{{<section overview>}}
---
h2: Преобразование MHTML в DOCX с помощью C#
---

Чтобы преобразовать MHTML в DOCX, мы будем использовать API [Aspose.HTML для .NET](https://products.aspose.com/html/net/), который представляет собой многофункциональное, мощное и простое в использовании средство для работы с документами и API преобразования для платформы C#. Преобразования MHTML часто требуются для использования преимуществ других форматов. Используя нашу высокоскоростную библиотеку, вы можете программно конвертировать MHTML в DOCX с полным контролем над различными параметрами конвертации. Мощный C# API позволяет быстро и качественно конвертировать MHTML в популярные форматы!

{{<section demos>}}
---
h2: Бесплатные онлайн-демонстрации конвертера
---

Проверьте качество преобразования MHTML в DOCX прямо в браузере! Пожалуйста, загрузите файл MHTML из локальной файловой системы, выберите требуемый формат вывода из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование MHTML в DOCX будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или MHTML в формат DOCX онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter MHTML DOCX PDF "JPG|JPEG" GIF BMP XPS TIFF PNG >}}
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
h2: Действия по преобразованию MHTML в DOCX на C#
---

Если вы хотите программно преобразовать MHTML в DOCX, выполните несколько обязательных шагов:
1. Откройте существующий файл MHTML.
1. Создайте экземпляр класса [DocSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/docsaveoptions).
1. Используйте метод [ConvertMHTML()](https://apireference.aspose.com/html/net/aspose.html.converters.converter/convertmhtml/methods/29) в [Converter](https://apireference.aspose.com/html/net/aspose.html.converters/converter), чтобы сохранить MHTML в виде файла DOCX. Вам необходимо передать файловый поток MHTML, DocSaveOptions и путь к выходному файлу методу ConvertMHTML().
1. Файл DOCX будет сохранен по указанному пути.




{{<section documentation>}}
---
h2: Преобразование MHTML в DOCX в документации
---

  - цель <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#mhtml-to-docx-by-two-lines-of-code" ="_blank">MHTML в DOCX двумя строками кода</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#convert-mhtml-to-docx-using-docsaveoptions" target="_blank" >Преобразование MHTML в DOCX с помощью DocSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/#output-stream-providers" target="_blank">преобразование MHTML в DOCX с помощью MemoryStreamProvider</a>

Преобразование MHTML в DOCX часто требуется, чтобы использовать преимущества формата DOCX для конкретных задач. Формат DOCX популярен, потому что он поддерживает широкий спектр функций форматирования и предлагает пользователям множество вариантов для написания любого типа документа. Пожалуйста, посетите статью документации [Преобразование MHTML в DOCX](https://docs.aspose.com/html/net/converting-between-formats/mhtml-to-docx/), чтобы узнать больше об Aspose.HTML для .NET API. функции преобразования и рассмотреть примеры C# для наиболее распространенных сценариев преобразования MHTML в DOCX. В статье вы найдете информацию о том, как преобразовать MHTML в DOCX с помощью методов ConvertMHTML() и как применить параметры DocSaveOptions или ICreateStreamProvider.

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