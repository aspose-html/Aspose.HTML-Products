---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать HTML в MD
description: Преобразование HTML в MD в C#. Легко используйте API преобразователя в ASP.NET или любом приложении .NET. Попробуйте онлайн-конвертер HTML в MD бесплатно!
url: /net/conversion/html-to-md/
family: html
platformtag: net
feature: conversion
informat: HTML
outformat: MD
otherformats: PDF DOCX XPS GIF JPEG PNG TIFF BMP XHTML MHTML
---

{{<section banner>}}
---
h1: Преобразование HTML в MD через C#
h2: Создайте MD из исходной HTML-страницы с помощью .NET API. Мгновенно конвертируйте HTML в формат MD с помощью нашего бесплатного онлайн-конвертера.
---

{{<section overview>}}
---
h2: Преобразование HTML в MD с помощью C#
---

Markdown — это язык разметки с синтаксисом форматирования простого текста. Его дизайн позволяет легко преобразовывать его во многие форматы вывода, но изначально он был создан для преобразования только в HTML. Библиотека классов Aspose.HTML обеспечивает обратное преобразование из HTML в Markdown. С помощью [Aspose.HTML for .NET](https://products.aspose.com/html/net/) API вы можете программно преобразовывать HTML в MD с полным контролем над широким диапазоном параметров преобразования. Существуют различные случаи преобразования HTML в MD, такие как чтение HTML из файла, URL-адреса, редактора WYSISYG, строки или потока. Мощный C# API позволяет быстро и качественно конвертировать HTML в популярные форматы!

{{<section demos>}}
---
h2: Бесплатные онлайн-демонстрации конвертера
---

Проверьте качество преобразования HTML в MD прямо в браузере! Пожалуйста, загрузите файл HTML из локальной файловой системы, выберите требуемый формат вывода из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование HTML в MD будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или HTML в формат MD онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter HTML MD PDF "JPG|JPEG" GIF DOCX BMP XPS TIFF PNG MHTML >}}
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
h2: Шаги по преобразованию HTML в MD в C#
---

Если вы хотели бы использовать функции преобразования в своем продукте или хотите программно преобразовать HTML в MD, см. приведенный выше пример кода C# или изучите главу «Документация». Во всех случаях любое преобразование требует некоторых обязательных шагов:
1. Загрузите HTML-документ с помощью одного из конструкторов [HTMLDocument()](https://apireference.aspose.com/html/net/aspose.html/htmldocument). Вы можете загрузить HTML из файла, HTML-кода, потока или URL-адреса.
1. Создайте новый объект [MarkdownSaveOptions](https://apireference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions).
1. Используйте метод [ConvertHTML()](https://apireference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) класса Converter, чтобы сохранить HTML в виде файла Markdown. Вам необходимо передать HTMLDocument, MarkdownSaveOptions и путь к выходному файлу методу ConvertHTML().
1. MD-файл будет сохранен по указанному пути.




{{<section documentation>}}
---
h2: Преобразование HTML в Markdown в документации
---

  - <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#html-to-markdown-by-a-some-lines-of-code " target="_blank">HTML в Markdown с помощью нескольких строк кода</a>
  - цель <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#convert-html-to-markdown-in-c-using-markdownsaveoptions" ="_blank">Преобразование HTML в Markdown с помощью MarkdownSaveOptions</a>
  – <a href="https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/#limitation" target="_blank">Ограничение конверсии</a>

Пожалуйста, посетите статью документации [Преобразование HTML в Markdown](https://docs.aspose.com/html/net/converting-between-formats/html-to-markdown/), чтобы узнать больше об Aspose.HTML для .NET API. функции преобразования и рассмотреть примеры C# для наиболее распространенных сценариев преобразования HTML в MD. В статье вы найдете информацию о том, как преобразовать HTML в MD с помощью методов ConvertHTML() и как применить параметры MarkdownSaveOptions и ICreateStreamProvider.

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