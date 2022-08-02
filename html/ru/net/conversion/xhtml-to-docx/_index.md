---
translation: true
template: /templates/_template-conversion-child.md
title: Конвертировать XHTML в DOCX
description: Преобразование XHTML в DOCX на C#. Легко используйте API в любом приложении .NET. Попробуйте онлайн-конвертер XHTML в DOCX бесплатно!
url: /net/conversion/xhtml-to-docx/
family: html
platformtag: net
feature: conversion
informat: XHTML
outformat: DOCX
otherformats: PDF XPS GIF JPEG PNG TIFF BMP HTML MHTML MD
howto: howtoXhtml
---

{{<section banner>}}
---
h1: Конвертировать XHTML в DOCX на C#
h2: Создайте DOCX из исходной страницы XHTML с помощью .NET API. Мгновенно конвертируйте XHTML в формат DOCX онлайн!
---

{{<section overview>}}
---
h2: Конвертировать XHTML в DOCX с помощью C#
---

Формат файла DOCX является одним из наиболее широко используемых и доступен во многих программах. Файл DOCX легко редактируется, прост в использовании и имеет удобный размер. Его можно просматривать, редактировать, искать и распечатывать с помощью MS Word или другого средства просмотра и редактирования Word. С помощью [Aspose.HTML .NET](https://products.aspose.com/html/net/) API вы можете программно преобразовывать XHTML в DOCX с полным контролем над параметрами преобразования. Любое преобразование, которое вы хотите выполнить, включает в себя загрузку документа XHTML и его сохранение в поддерживаемом формате. Мощный C# API позволяет быстро и качественно конвертировать XHTML в DOCX!

{{<section demos>}}
---
h2: Бесплатное приложение для конвертации XHTML
---

Проверьте качество преобразования XHTML в DOCX прямо в браузере! Пожалуйста, загрузите файл XHTML из локальной файловой системы, выберите требуемый выходной формат из списка и запустите пример. Это быстро, просто, безопасно и совершенно бесплатно! Преобразование XHTML в DOCX будет выполнено с параметрами сохранения по умолчанию. Вы сразу получите результат в виде отдельного файла. Итак, быстро конвертируйте любую веб-страницу или XHTML в формат DOCX онлайн!

{{<section "app-pluging" i18n-exclude>}}

{{< app/html/converter XHTML DOCX BMP TIFF PNG "JPG|JPEG" GIF PDF XPS MD MHTML>}}
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
h2: Действия по преобразованию XHTML в DOCX на C#
---

Если вы хотите программно преобразовать XHTML в DOCX, см. приведенный выше пример кода C# или изучите главу «Документация». Во всех случаях любое преобразование XHTML требует некоторых обязательных шагов:
1. Загрузите файл XHTML, используя один из конструкторов HTMLDocument() класса [HTMLDocument.](https://reference.aspose.com/html/net/aspose.html/htmldocument)
1. Создайте новый объект [DocSaveOptions.](https://reference.aspose.com/html/net/aspose.html.saving/docsaveoptions)
1. Используйте метод [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) класса Converter, чтобы сохранить XHTML в виде файла DOCX.
1. Файл DOCX будет сохранен по указанному пути.

{{<section documentation>}}
---
h2: Преобразование (X)HTML в документации
---

Преобразование XHTML в DOCX часто требуется, чтобы использовать преимущества формата DOCX для конкретных задач. Формат DOCX популярен, потому что он поддерживает широкий спектр функций форматирования и предлагает пользователям множество вариантов для написания любого типа документа. Aspose.HTML for .NET API позволяет быстро и качественно конвертировать (X)HTML в другие популярные форматы. Посетите главу документации <a href="https://docs.aspose.com/html/net/converting-between-formats/" target="_blank">Преобразование между форматами</a>, чтобы узнать больше об API. В главе описываются популярные преобразования, а также примеры C# для наиболее распространенных сценариев преобразования.

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