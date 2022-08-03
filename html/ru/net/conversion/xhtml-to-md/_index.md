---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать XHTML в MD
description: Преобразование XHTML в MD на C#. Легко используйте API в любом приложении .NET. Попробуйте онлайн-конвертер XHTML в MD бесплатно!
url: /net/conversion/xhtml-to-md/
family: html
platformtag: net
feature: conversion
informat: XHTML
outformat: MD
otherformats: PDF XPS DOCX GIF JPEG PNG TIFF BMP HTML MHTML
howto: howtoXhtml
---

{{<section banner>}}
---
h1: Конвертировать XHTML в MD через C#
h2: Создайте MD из исходной страницы XHTML с помощью .NET API. Мгновенно конвертируйте XHTML в формат MD онлайн!
---

{{<section overview>}}
---
h2: Конвертировать XHTML в MD с помощью C#
---

Markdown — это язык разметки с синтаксисом форматирования простого текста. Его дизайн позволяет легко преобразовывать его во многие форматы вывода, но изначально он был создан для преобразования только в HTML. Библиотека классов Aspose.HTML обеспечивает обратное преобразование из (X)HTML в Markdown. С помощью API [Aspose.HTML для .NET](https://products.aspose.com/html/net/) вы можете программно конвертировать XHTML в MD с полным контролем над параметрами преобразования. Любое преобразование, которое вы хотите выполнить, включает в себя загрузку документа XHTML и его сохранение в формате Markdown. Мощный C# API позволяет быстро и качественно конвертировать XHTML в MD!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации XHTML
---

Проверьте качество преобразования XHTML в MD прямо в браузере! Пожалуйста, загрузите файл XHTML из локальной файловой системы, выберите требуемый выходной формат из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование XHTML в MD будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или XHTML в формат MD онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter XHTML MD BMP TIFF PNG "JPG|JPEG" GIF PDF XPS DOCX MHTML >}}
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Saving;

    using var document = new HTMLDocument("document.{{input lower}}");
{{#if_output 'PDF'}}
    var options = new PdfSaveOptions();
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
{{#if_output 'MHTML'}}
    var options = new MHTMLSaveOptions();
{{/if_output}}
{{#if_output 'BMP' 'JPG' 'GIF' 'PNG' 'TIFF'}}
    var options = new ImageSaveOptions(ImageFormat.{{output param2 camel}});
{{/if_output}}
    Converter.ConvertHTML(document, options, "output.{{output lower}}");   
{{< /app/html/converter>}} 


{{<section steps>}}
---
h2: Шаги по преобразованию XHTML в MD в C#
---

Если вы хотите программно преобразовать XHTML в MD, см. приведенный выше пример кода C# или изучите главу «Документация». Во всех случаях любое преобразование XHTML в MD требует некоторых обязательных шагов:
1. Загрузите файл XHTML, используя один из конструкторов HTMLDocument() класса [HTMLDocument.](https://reference.aspose.com/html/net/aspose.html/htmldocument/)
1. Создайте новый объект [MarkdownSaveOptions.](https://reference.aspose.com/html/net/aspose.html.saving/markdownsaveoptions/)
1. Используйте метод [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) класса Converter, чтобы сохранить XHTML в виде файла Markdown.
1. MD-файл будет сохранен по указанному пути.

{{<section documentation>}}
---
h2: Конвертация (X)HTML в документации
---

Aspose.HTML for .NET API позволяет быстро и качественно конвертировать (X)HTML в другие популярные форматы. Посетите главу документации <a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">Преобразование между форматами</a>, чтобы узнать больше об API. В главе описываются популярные преобразования, а также примеры C# для наиболее распространенных сценариев преобразования.

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
title: Другие поддерживаемые преобразования XHTML
subTitle: "Вы также можете конвертировать XHTML во многие другие форматы файлов:"
---