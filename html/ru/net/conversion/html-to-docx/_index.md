---
translation: true
template: /templates/_template-conversion-child.md
title: Преобразование HTML в DOCX в C# .NET
description: Конвертировать HTML в DOCX на C#. Легко используйте API преобразователя в ASP.NET или любом приложении .NET. Попробуйте онлайн-конвертер HTML в DOCX бесплатно!
url: /net/conversion/html-to-docx/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: DOCX
otherformats: PDF XPS GIF JPEG PNG TIFF BMP XHTML MHTML MD
---

{{<section banner>}}
---
h1: Конвертировать HTML в DOCX на C#
h2: Создайте DOCX из исходной HTML-страницы с помощью .NET API. Мгновенно конвертируйте HTML в формат DOCX онлайн!
---

{{<section overview>}}
---
h2: Преобразование HTML в DOCX с помощью C#
---

Формат файла DOCX является одним из наиболее широко используемых и доступен во многих программах. Файл DOCX легко редактируется, прост в использовании и имеет удобный размер. Его можно просматривать, редактировать, искать и распечатывать с помощью MS Word или другого средства просмотра и редактирования Word. С помощью [Aspose.HTML для .NET](https://products.aspose.com/html/net/) API вы можете программно преобразовывать HTML в DOCX с полным контролем над широким диапазоном параметров преобразования. Существуют различные случаи преобразования HTML в DOCX, такие как чтение из файла, URL-адреса, редактора WYSISYG, строки или потока. Мощный C# API позволяет быстро и качественно конвертировать HTML в популярные форматы!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации HTML
---

Проверьте качество преобразования HTML в DOCX прямо в браузере! Пожалуйста, загрузите файл HTML из локальной файловой системы, выберите требуемый формат вывода из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование HTML в DOCX будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или HTML в формат DOCX онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML DOCX PDF MD "JPG|JPEG" GIF BMP XPS TIFF PNG MHTML >}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new HTMLDocument("document.{{input lower}}");
{{#if_output 'PDF'}}
    var options = new PdfSaveOptions();
{{/if_output}}
{{#if_output 'MHTML'}}
    var options = new MHTMLSaveOptions();
{{/if_output}}
{{#if_output 'DOCX'}}
    var options = new DocSaveOptions();
{{/if_output}}
{{#if_output 'XPS'}}
    var options = new XpsSaveOptions();
{{/if_output}}
{{#if_output 'MD'}}
    var options = new MarkdownSaveOptions();
{{/if_output}}
{{#if_output 'BMP' 'JPG' 'GIF' 'PNG' 'TIFF'}}
    var options = new ImageSaveOptions(ImageFormat.{{output param2 camel}});
{{/if_output}}
    Converter.ConvertHTML(document, options, "output.{{output lower}}");   
{{< /app/html/converter>}} 


{{<section steps>}}
---
h2: Шаги по преобразованию HTML в DOCX на C#
---

Если вы хотели бы использовать функции преобразования в своем продукте или хотите программно преобразовать HTML в DOCX, см. приведенный выше пример кода C# или изучите главу «Документация». Во всех случаях любое преобразование требует некоторых обязательных шагов:

1. Загрузите HTML-документ с помощью одного из конструкторов [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). Вы можете загрузить HTML из файла, HTML-кода, потока или URL-адреса.
1. Создайте новый объект [DocSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/docsaveoptions/).
1. Используйте метод [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) класса Converter для сохранения HTML в виде файла DOCX. Вам необходимо передать HTMLDocument, DocSaveOptions и путь к выходному файлу методу ConvertHTML().
1. Файл DOCX будет сохранен по указанному пути.

{{<section documentation>}}
---
h2: Преобразование HTML в DOCX в документации
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#html-to-docx-by-a-single-line-of-code " target="_blank">Конвертировать HTML в DOCX одной строкой кода</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#convert-html-to-docx-in-c-using-docsaveoptions" target="_blank">Преобразование HTML в DOCX с помощью DocSaveOptions</a>
  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#output-stream-providers" target="_blank">Конвертировать HTML в DOCX с помощью MemoryStreamProvider</a>

Преобразование HTML в DOCX часто требуется, чтобы использовать формат DOCX для конкретных задач. Этот формат популярен, потому что он поддерживает широкий спектр функций форматирования и предлагает пользователям множество вариантов для написания любого типа документа. Пожалуйста, посетите статью документации [Преобразование HTML в DOCX](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/), чтобы узнать больше о функциях преобразования Aspose.HTML for .NET API и рассмотреть примеры C# для наиболее распространенных сценариев преобразования HTML в DOCX. В статье вы найдете информацию о том, как преобразовать HTML в DOCX с помощью методов ConvertHTML() и как применить параметры DocSaveOptions и ICreateStreamProvider.

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
title: Другие поддерживаемые преобразования HTML
subTitle: "Вы также можете конвертировать HTML во многие другие форматы файлов:"
---